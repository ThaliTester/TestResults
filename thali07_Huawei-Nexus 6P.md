#### Test 937485009d40c45_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-15 13:54:37.544   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:54:38.112  5775  5775 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-15 13:54:38.117  5775  5775 D AndroidRuntime: CheckJNI is OFF
11-15 13:54:38.150  5775  5775 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-15 13:54:38.201  5775  5775 I Radio-JNI: register_android_hardware_Radio DONE
11-15 13:54:38.216  5775  5775 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-15 13:54:38.229   928  3893 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-15 13:54:38.256  4054  4079 W SearchService: Abort, client detached.
11-15 13:54:38.257  5775  5775 D AndroidRuntime: Shutting down VM
11-15 13:54:38.267  4054  4054 I HotwordDetector: Closing mic
11-15 13:54:38.267  4054  4295 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@45fb6e8
11-15 13:54:38.269  4054  4317 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-15 13:54:38.293   928   939 I ActivityManager: Start proc 5784:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-15 13:54:38.348   513  4320 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-15 13:54:38.351   513  4320 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-15 13:54:38.355   513  4320 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-15 13:54:38.355   513  4320 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-15 13:54:38.356   513  3136 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-15 13:54:38.358  4054  4296 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-15 13:54:38.359  4054  4315 I MicroRecognitionRnrImpl: Detection finished
11-15 13:54:38.399  5784  5784 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-15 13:54:38.417  5784  5784 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-15 13:54:38.490  5784  5784 I LibraryLoader: Time to load native libraries: 69 ms (timestamps 7355-7424)
11-15 13:54:38.490  5784  5784 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-15 13:54:38.525  5784  5784 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ad13a91}
,11-15 13:54:38.525  5784  5784 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-15 13:54:38.526  5784  5784 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-15 13:54:38.531  5784  5784 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-15 13:54:38.533  5784  5784 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-15 13:54:38.545   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:54:38.581  5784  5784 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-15 13:54:38.595  5784  5784 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-15 13:54:38.595  5784  5784 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-15 13:54:38.595  5784  5784 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-15 13:54:38.595  5784  5784 I Adreno  : Build Date                       : 12/06/15
11-15 13:54:38.595  5784  5784 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-15 13:54:38.595  5784  5784 I Adreno  : Local Branch                     : mybranch17112971
11-15 13:54:38.595  5784  5784 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-15 13:54:38.595  5784  5784 I Adreno  : Remote Branch                    : NONE
11-15 13:54:38.595  5784  5784 I Adreno  : Reconstruct Branch               : NOTHING
,11-15 13:54:38.657   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@384752d:true
,11-15 13:54:38.696   401   401 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[26229]" dev="sockfs" ino=26229 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 13:54:38.696   401   401 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26229]" dev="sockfs" ino=26229 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 13:54:38.711  5784  5784 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-15 13:54:38.722  5784  5784 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-15 13:54:38.749  5784  5821 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-15 13:54:38.746  3077  3077 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[30311]" dev="sockfs" ino=30311 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 13:54:38.746  3077  3077 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30311]" dev="sockfs" ino=30311 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 13:54:38.752   939   939 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[26240]" dev="sockfs" ino=26240 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 13:54:38.752   939   939 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[26240]" dev="sockfs" ino=26240 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 13:54:38.757  5784  5808 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-15 13:54:38.782  5784  5821 I OpenGLRenderer: Initialized EGL, version 1.4
,11-15 13:54:38.855   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +591ms
,11-15 13:54:38.852  3673  3673 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30314]" dev="sockfs" ino=30314 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 13:54:38.852  3673  3673 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[30314]" dev="sockfs" ino=30314 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 13:54:38.852  3755  3755 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[30313]" dev="sockfs" ino=30313 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 13:54:38.852  3755  3755 W Binder_6: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[30313]" dev="sockfs" ino=30313 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 13:54:38.861  3800  3800 I Keyboard.Facilitator: onFinishInput()
,11-15 13:54:38.886  5784  5784 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5784
,11-15 13:54:38.986  5784  5784 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-15 13:54:39.091   928  5754 I ActivityManager: Killing 5421:com.android.settings/1000 (adj 15): empty #17
,11-15 13:54:39.113   928  5754 I ActivityManager: Killing 5356:org.codeaurora.ims/1001 (adj 15): empty #18
,11-15 13:54:39.270  5784  5824 D jxcore_app_log: JniHelper::setJavaVM(0xf55bc000), pthread_self() = -579860176
,11-15 13:54:39.293  5784  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-15 13:54:39.293  5784  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-15 13:54:39.293  5784  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-15 13:54:39.293  5784  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-15 13:54:39.293  5784  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-15 13:54:39.293  5784  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db3c0af added. We now have 1 listener(s)
,11-15 13:54:39.299  5784  5824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
11-15 13:54:39.300  5784  5824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 13:54:39.301  5784  5824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 13:54:39.301  5784  5824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-15 13:54:39.309  5784  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0ee79a added. We now have 1 listener(s)
11-15 13:54:39.310  5784  5824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 13:54:39.316   928  3128 D WifiService: New client listening to asynchronous messages
,11-15 13:54:39.319  5784  5824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 13:54:39.319  5784  5824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-15 13:54:39.320  5784  5824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-15 13:54:39.320  5784  5824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-15 13:54:39.320  5784  5824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-15 13:54:39.320  5784  5824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-15 13:54:39.320  5784  5824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-15 13:54:39.324  5784  5824 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-15 13:54:39.363  5784  5784 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-15 13:54:39.545   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-15 13:54:39.854  5784  5793 I art     : Background sticky concurrent mark sweep GC freed 73997(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 919us total 147.707ms
,11-15 13:54:41.094  5784  5793 I art     : Background partial concurrent mark sweep GC freed 53919(6MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 2.025ms total 342.667ms
,11-15 13:54:41.706  5784  5831 W jxcore-log: Initializing JXcore engine
,11-15 13:54:41.706  5784  5831 W jxcore-log: JXcore engine is ready
,11-15 13:54:41.726  5831  5831 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12632 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-15 13:54:41.726  5831  5831 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[17437]" dev="sockfs" ino=17437 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-15 13:54:41.726  5831  5831 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5540 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-15 13:54:41.726  5831  5831 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34068]" dev="sockfs" ino=34068 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-15 13:54:41.738  5784  5831 W jxcore-log: Starting JXcore engine
,11-15 13:54:41.788  5784  5831 W jxcore-log: Platform android
11-15 13:54:41.788  5784  5831 W jxcore-log: 
,11-15 13:54:41.789  5784  5831 W jxcore-log: Process ARCH arm
11-15 13:54:41.789  5784  5831 W jxcore-log: 
,11-15 13:54:41.973  5784  5831 I jxcore-log: JXcore Cordova bridge is ready!
11-15 13:54:41.973  5784  5831 I jxcore-log: 
,11-15 13:54:41.973  5784  5831 W jxcore-log: JXcore engine is started
,11-15 13:54:41.986  5784  5824 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-15 13:54:41.993  5784  5784 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-15 13:54:48.368  4054  5832 W CronetSyncConnectionRcs: Upload content type not set.
,11-15 13:54:50.526   928  3116 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 13:54:51.844  5784  5831 I jxcore-log: 2016-11-15 12:54:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-15 13:54:51.844  5784  5831 I jxcore-log: 
,11-15 13:54:51.846  5784  5831 I jxcore-log: 2016-11-15 12:54:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-15 13:54:51.846  5784  5831 I jxcore-log: 
,11-15 13:54:51.851  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-15 13:54:51.851  5784  5831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 13:54:51.851  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:54:51.851  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:54:51.851  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:54:51.851  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 13:54:51.851  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 13:54:51.851  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 13:54:51.851  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 13:54:51.851  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 13:54:51.853  5784  5831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 13:54:51.855  5784  5831 I jxcore-log: 2016-11-15 12:54:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-15 13:54:51.855  5784  5831 I jxcore-log: 
,11-15 13:54:51.856  5784  5831 I jxcore-log: 2016-11-15 12:54:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-15 13:54:51.856  5784  5831 I jxcore-log: 
,11-15 13:54:52.105  5784  5831 I jxcore-log: 2016-11-15 12:54:52 - DEBUG UnitTest_app: 'Running unit tests'
11-15 13:54:52.105  5784  5831 I jxcore-log: 
,11-15 13:54:52.106  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 13:54:52.106  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64e2e58 added. We now have 2 listener(s)
,11-15 13:54:52.107  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 13:54:52.107  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-15 13:54:52.107  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 13:54:52.107  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 13:54:52.107  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@178bbb1 added. We now have 2 listener(s)
11-15 13:54:52.107  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 13:54:52.108  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 13:54:52.109  5784  5831 D executeNativeTests: Running unit tests
,11-15 13:54:52.148  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 13:54:52.148  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 added. We now have 3 listener(s)
11-15 13:54:52.149  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 13:54:52.149  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-15 13:54:52.149  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 13:54:52.149  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 13:54:52.149  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 added. We now have 3 listener(s)
11-15 13:54:52.149  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 13:54:52.150  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-15 13:54:52.151  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 13:54:52.151  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-15 13:54:52.152  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 13:54:52.152  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 13:54:52.152  5784  5831 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-15 13:54:52.152  5784  5831 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-15 13:54:52.152  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-15 13:54:52.153  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 13:54:52.153  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 13:54:52.153  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 13:54:52.153  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:54:52.153  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:54:52.153  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:54:52.153  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:54:52.153  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:54:52.153  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 13:54:52.153  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 removed from the list
11-15 13:54:52.153  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 13:54:52.153  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 removed from the list
11-15 13:54:52.154  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:54:52.154  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.154  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:54:52.154  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.154  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.154  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:54:52.154  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:54:52.154  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:54:52.154  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
,11-15 13:54:52.155  5784  5831 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-15 13:54:52.156  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:54:52.156  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:54:52.156  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:54:52.156  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:54:52.156  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:54:52.156  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:54:52.156  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:54:52.156  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:54:52.156  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:54:52.156  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.156  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.156  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.156  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.157  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:54:52.157  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:54:52.157  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:54:52.157  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
,11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-15 13:54:52.159  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-15 13:54:52.160  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-15 13:54:52.160  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-15 13:54:52.160  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-15 13:54:52.160  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-15 13:54:52.160  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-15 13:54:52.160  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-15 13:54:52.160  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-15 13:54:52.160  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-15 13:54:52.160  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-15 13:54:52.160  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:54:52.160  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_,STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:54:52.160  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:54:52.160  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:54:52.160  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:54:52.160  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:54:52.160  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:54:52.160  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:54:52.160  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:54:52.160  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.161  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.161  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.161  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.161  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:54:52.161  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:54:52.161  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:54:52.161  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:54:52.161  5784  5831 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-15 13:54:52.162  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 13:54:52.162  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 13:54:52.168  5784  5831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 13:54:52.168  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:54:52.168  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:54:52.168  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:54:52.168  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 13:54:52.168  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 13:54:52.168  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 13:54:52.168  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 13:54:52.168  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 13:54:52.169  5784  5831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 13:54:52.169  5784  5831 D io.jxcore.node.ConnectivityMonitor: start: OK
11-15 13:54:52.169  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 13:54:52.169  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 13:54:52.169  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 13:54:52.169  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 13:54:52.169  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 13:54:52.172  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 13:54:52.172  5784  5831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 13:54:52.172  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 13:54:52.173  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 13:54:52.176  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.176  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 13:54:52.176  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 13:54:52.177  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 13:54:52.177  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-15 13:54:52.178  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-15 13:54:52.179  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 13:54:52.180  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-15 13:54:52.180  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.180  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 13:54:52.180  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 13:54:52.180  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 13:54:52.180  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 13:54:52.180  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.181  5784  5831 D BluetoothAdapter: STATE_ON
11-15 13:54:52.183  4732  4941 D BtGatt.GattService: registerClient() - UUID=65d3880b-c9ed-4888-8442-b283b595794c
11-15 13:54:52.184  4732  4794 D BtGatt.GattService: onClientRegistered() - UUID=65d3880b-c9ed-4888-8442-b283b595794c, clientIf=5
11-15 13:54:52.185  5784  5795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 13:54:52.186  4732  4745 D BtGatt.GattService: start scan with filters
11-15 13:54:52.193  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 13:54:52.193  4732  4797 D BtGatt.ScanManager: handling starting scan
11-15 13:54:52.193  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.193  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 13:54:52.193  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.193  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 13:54:52.193  5784  5784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 13:54:52.194  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 13:54:52.194  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 13:54:52.194  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 13:54:52.194  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 13:54:52.194  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.194  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 13:54:52.194  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 13:54:52.194  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 13:54:52.194  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.194  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.195  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:52.195  4732  4797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:54:52.195  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 13:54:52.195  5784  5831 I io.jxcore.node.ConnectionHelper: start: OK
11-15 13:54:52.199  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 13:54:52.200  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 13:54:52.200  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 13:54:52.200  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 13:54:52.200  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 13:54:52.200  5784  5784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 13:54:52.203  4732  4794 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-15 13:54:52.203  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:54:52.204  4732  4797 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-15 13:54:52.210  4732  4794 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-15 13:54:52.210  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:54:52.211  4732  4797 D BtGatt.ScanManager: Starting BLE batch scan
11-15 13:54:52.211  4732  4797 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-15 13:54:52.224  4732  4794 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-15 13:54:52.224  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:54:52.231  4732  4794 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 13:54:52.231  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:54:52.702  5784  5784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-15 13:54:52.702  5784  5784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 13:54:52.702  5784  5784 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 13:54:53.383   928  5490 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-15 13:54:57.199  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 13:54:57.199  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-15 13:54:57.200  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-15 13:54:57.200  5784  5831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 13:54:57.200  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 13:54:57.200  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:54:57.200  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-15 13:54:57.200  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 13:54:57.200  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 13:54:57.200  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 13:54:57.201  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:54:57.201  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:57.202  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:57.202  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-15 13:54:57.202  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:54:57.203  5784  5831 D BluetoothAdapter: STATE_ON
11-15 13:54:57.203  4732  4942 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-15 13:54:57.204  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 13:54:57.205  5784  5831 D BluetoothAdapter: STATE_ON
11-15 13:54:57.205  4732  4797 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-15 13:54:57.206  4732  4745 D BtGatt.GattService: stopScan() - queue size =1
11-15 13:54:57.208  4732  4744 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 13:54:57.209  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 13:54:57.210  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:57.210  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 13:54:57.210  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:57.210  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:54:57.210  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:57.211  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:54:57.211  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 13:54:57.212  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-15 13:54:57.212  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:54:57.212  4732  4732 D BtGatt.ScanManager: awakened up at time 186147
,11-15 13:54:57.212  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:57.213  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 13:54:57.213  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 13:54:57.217  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 13:54:57.218  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:54:57.220  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:57.220  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 13:54:57.220  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:57.221  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:54:57.221  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 13:54:57.221  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 13:54:57.221  5784  5831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 13:54:57.221  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 13:54:57.221  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 13:54:57.221  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 13:54:57.221  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:54:57.221  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:54:57.221  5784  5784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-15 13:54:57.221  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:54:57.221  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 13:54:57.221  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:54:57.222  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 13:54:57.222  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-15 13:54:57.223  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 13:54:57.223  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 13:54:57.223  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-15 13:54:57.223  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,11-15 13:54:57.224  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 13:54:57.226  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 13:54:57.226  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 13:54:57.226  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-15 13:54:57.226  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 13:54:57.226  5784  5784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 13:54:57.242  4732  4794 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:54:57.242  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:54:57.243  4732  4794 D BtGatt.GattService: current time is 186177465096
,11-15 13:54:57.243  4732  4794 D BtGatt.GattService: Batch record : [96, 42, -109, 88, -26, 116, 1, -128, -87, 1, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 71, -122, -77, 84, 69, -12, 1, -128, -86, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -89, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, -128, -96, 13, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
11-15 13:54:57.245  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
11-15 13:54:57.245  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:54:57.246  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:54:57.246  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:54:57.246  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:54:57.246  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:54:57.247  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:54:57.247  4732  4794 E BtGatt.ContextMap: Context not found for ID 5
,11-15 13:54:57.256  4732  4794 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-15 13:54:57.256  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:54:57.256  4732  4797 D BtGatt.ScanManager: stopping BLe Batch
,11-15 13:54:57.263  4732  4794 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-15 13:54:57.263  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:54:57.264  4732  4797 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:54:57.270  4732  4794 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 13:54:57.270  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:54:57.728  5784  5784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 13:54:59.547   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:00.548   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:01.550   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:02.224  5784  5831 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-15 13:55:02.230  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 13:55:02.231  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 13:55:02.244  5784  5831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 13:55:02.244  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:02.244  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:02.244  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:55:02.244  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 13:55:02.244  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 13:55:02.244  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 13:55:02.244  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 13:55:02.244  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 13:55:02.247  5784  5831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 13:55:02.247  5784  5831 D io.jxcore.node.ConnectivityMonitor: start: OK
11-15 13:55:02.247  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 13:55:02.248  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 13:55:02.248  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 13:55:02.248  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 13:55:02.248  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 13:55:02.252  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 13:55:02.252  5784  5831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 13:55:02.252  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 13:55:02.252  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:55:02.258  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.258  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:55:02.258  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 13:55:02.259  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 13:55:02.259  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 13:55:02.259  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-15 13:55:02.263  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.264  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 13:55:02.264  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 13:55:02.264  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-15 13:55:02.264  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 13:55:02.264  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.266  5784  5831 D BluetoothAdapter: STATE_ON
,11-15 13:55:02.268  4732  4744 D BtGatt.GattService: registerClient() - UUID=b5753d8a-791e-4110-b6ef-fcaa8298576d
11-15 13:55:02.269  4732  4794 D BtGatt.GattService: onClientRegistered() - UUID=b5753d8a-791e-4110-b6ef-fcaa8298576d, clientIf=5
,11-15 13:55:02.269  5784  5795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-15 13:55:02.270  4732  4942 D BtGatt.GattService: start scan with filters
11-15 13:55:02.272  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 13:55:02.272  4732  4797 D BtGatt.ScanManager: handling starting scan
11-15 13:55:02.272  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.272  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-15 13:55:02.272  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.273  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 13:55:02.273  5784  5784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 13:55:02.273  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-15 13:55:02.273  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 13:55:02.273  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 13:55:02.273  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.273  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.273  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 13:55:02.274  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 13:55:02.275  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.277  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.277  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 13:55:02.277  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.277  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.277  5784  5831 I io.jxcore.node.ConnectionHelper: start: OK
11-15 13:55:02.277  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-15 13:55:02.280  4732  4794 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-15 13:55:02.280  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:55:02.280  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.280  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.280  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.280  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.280  5784  5784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 13:55:02.280  4732  4797 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-15 13:55:02.281  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:02.281  5784  5831 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-15 13:55:02.281  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-15 13:55:02.281  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 13:55:02.282  5784  5831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 13:55:02.282  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 13:55:02.282  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:02.282  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 13:55:02.282  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 13:55:02.282  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 13:55:02.282  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 13:55:02.282  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.282  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.282  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.282  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-15 13:55:02.283  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.283  5784  5831 D BluetoothAdapter: STATE_ON
11-15 13:55:02.284  4732  4941 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-15 13:55:02.284  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 13:55:02.284  5784  5831 D BluetoothAdapter: STATE_ON
11-15 13:55:02.285  4732  4932 D BtGatt.GattService: stopScan() - queue size =1
,11-15 13:55:02.285  4732  4942 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.286  4732  4794 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-15 13:55:02.286  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.286  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 13:55:02.287  4732  4797 D BtGatt.ScanManager: Starting BLE batch scan
11-15 13:55:02.287  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 13:55:02.287  4732  4797 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-15 13:55:02.287  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 13:55:02.287  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.290  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.290  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 13:55:02.290  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.290  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.290  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 13:55:02.290  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 13:55:02.290  5784  5831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 13:55:02.290  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 13:55:02.290  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 13:55:02.290  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:02.290  5784  5784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 13:55:02.290  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.290  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
,11-15 13:55:02.290  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:02.290  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 13:55:02.290  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 13:55:02.290  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:02.290  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:02.290  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.290  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 13:55:02.290  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.291  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,11-15 13:55:02.291  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.292  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.292  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.292  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.293  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.293  5784  5784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 13:55:02.293  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.294  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:02.294  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.294  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.294  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:02.294  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:02.294  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:02.294  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:02.295  5784  5831 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-15 13:55:02.296  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 13:55:02.296  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 13:55:02.300  4732  4794 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-15 13:55:02.300  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:55:02.302  5784  5831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 13:55:02.302  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:02.302  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:02.302  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:55:02.302  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 13:55:02.302  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 13:55:02.302  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 13:55:02.302  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 13:55:02.302  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 13:55:02.304  5784  5831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 13:55:02.304  5784  5831 D io.jxcore.node.ConnectivityMonitor: start: OK
11-15 13:55:02.304  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 13:55:02.304  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 13:55:02.304  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 13:55:02.304  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 13:55:02.304  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 13:55:02.305  4732  4794 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 13:55:02.305  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:55:02.307  4732  4797 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:55:02.307  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:55:02.308  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 13:55:02.308  5784  5831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 13:55:02.309  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 13:55:02.310  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:55:02.312  4732  4794 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 13:55:02.312  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:55:02.312  4732  4794 E BtGatt.ContextMap: Context not found for ID 5
11-15 13:55:02.312  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.312  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-15 13:55:02.313  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 13:55:02.313  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-15 13:55:02.313  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-15 13:55:02.316  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.316  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 13:55:02.316  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 13:55:02.316  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 13:55:02.316  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-15 13:55:02.316  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:02.318  5784  5831 D BluetoothAdapter: STATE_ON
,11-15 13:55:02.318  4732  4794 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-15 13:55:02.318  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:55:02.318  4732  4797 D BtGatt.ScanManager: stopping BLe Batch
11-15 13:55:02.320  4732  4941 D BtGatt.GattService: registerClient() - UUID=1bbda6d1-870a-42d6-85f3-73e3c9cb04a7
,11-15 13:55:02.321  4732  4794 D BtGatt.GattService: onClientRegistered() - UUID=1bbda6d1-870a-42d6-85f3-73e3c9cb04a7, clientIf=5
,11-15 13:55:02.321  5784  5794 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-15 13:55:02.321  4732  4744 D BtGatt.GattService: start scan with filters
11-15 13:55:02.324  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-15 13:55:02.324  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.324  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 13:55:02.324  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:02.324  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 13:55:02.324  4732  4794 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-15 13:55:02.324  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:55:02.324  5784  5784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 13:55:02.324  4732  4797 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-15 13:55:02.324  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.324  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 13:55:02.324  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 13:55:02.325  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.325  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.325  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 13:55:02.325  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 13:55:02.326  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.328  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.328  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 13:55:02.328  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.328  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:02.328  5784  5831 I io.jxcore.node.ConnectionHelper: start: OK
11-15 13:55:02.328  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-15 13:55:02.329  4732  4794 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 13:55:02.329  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:55:02.330  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-15 13:55:02.330  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.330  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.330  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 13:55:02.330  5784  5784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 13:55:02.331  4732  4797 D BtGatt.ScanManager: handling starting scan
,11-15 13:55:02.336  4732  4794 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-15 13:55:02.336  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:55:02.337  4732  4797 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-15 13:55:02.341  4732  4794 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-15 13:55:02.341  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:55:02.341  4732  4797 D BtGatt.ScanManager: Starting BLE batch scan
,11-15 13:55:02.341  4732  4797 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-15 13:55:02.350  4732  4794 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-15 13:55:02.350  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:55:02.355  4732  4794 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 13:55:02.355  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:55:02.551   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:02.832  5784  5784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-15 13:55:02.832  5784  5784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 13:55:02.832  5784  5784 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 13:55:03.553   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:04.553   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 13:55:07.328  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 13:55:07.329  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:07.329  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 13:55:07.329  5784  5831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 13:55:07.329  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 13:55:07.329  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:07.330  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 13:55:07.330  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 13:55:07.330  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 13:55:07.330  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 13:55:07.330  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.331  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.331  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.331  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-15 13:55:07.331  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.334  5784  5831 D BluetoothAdapter: STATE_ON
11-15 13:55:07.334  4732  4941 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-15 13:55:07.335  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 13:55:07.336  4732  4797 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-15 13:55:07.337  5784  5831 D BluetoothAdapter: STATE_ON
11-15 13:55:07.340  4732  4932 D BtGatt.GattService: stopScan() - queue size =1
11-15 13:55:07.343  4732  4745 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 13:55:07.345  4732  4732 D BtGatt.ScanManager: awakened up at time 196279
11-15 13:55:07.346  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 13:55:07.346  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.346  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 13:55:07.346  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.347  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.347  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.347  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.347  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 13:55:07.348  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.348  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.348  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:07.348  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 13:55:07.348  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 13:55:07.350  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 13:55:07.350  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:07.353  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:07.353  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 13:55:07.354  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.354  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:07.354  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 13:55:07.355  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 13:55:07.355  5784  5784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-15 13:55:07.355  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-15 13:55:07.355  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-15 13:55:07.355  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 13:55:07.356  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 13:55:07.356  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-15 13:55:07.356  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-15 13:55:07.356  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 13:55:07.358  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 13:55:07.358  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-15 13:55:07.358  5784  5784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 13:55:07.358  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 13:55:07.358  5784  5784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 13:55:07.371  4732  4794 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 13:55:07.371  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:55:07.371  4732  4794 D BtGatt.GattService: current time is 196306301930
11-15 13:55:07.372  4732  4794 D BtGatt.GattService: Batch record : [96, 42, -109, 88, -26, 116, 1, -128, -87, 2, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -93, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, -128, -94, 6, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 116, -43, -111, -91, -20, -29, 1, -128, -88, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:55:07.372  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
11-15 13:55:07.372  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 13:55:07.373  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:55:07.373  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:55:07.373  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 13:55:07.373  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:55:07.374  4732  4794 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:55:07.380  4732  4794 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-15 13:55:07.380  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:55:07.380  4732  4797 D BtGatt.ScanManager: stopping BLe Batch
,11-15 13:55:07.387  4732  4794 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-15 13:55:07.387  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:55:07.387  4732  4797 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:55:07.393  4732  4794 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 13:55:07.393  4732  4794 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:55:07.860  5784  5784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 13:55:07.860  5784  5784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-15 13:55:07.860  5784  5784 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 13:55:10.530   928  3116 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 13:55:12.356  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 13:55:12.356  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-15 13:55:12.357  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:12.357  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.357  5784  5831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 13:55:12.357  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-15 13:55:12.357  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:12.357  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:12.358  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 13:55:12.358  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.358  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 13:55:12.358  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 13:55:12.362  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:12.366  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:12.366  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.367  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.367  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:12.367  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-15 13:55:12.367  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.367  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.368  5784  5831 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-15 13:55:12.370  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 13:55:12.370  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:12.371  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:12.371  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.371  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:12.371  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
,11-15 13:55:12.371  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.371  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.372  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:12.372  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:12.375  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.375  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.375  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.376  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:12.376  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-15 13:55:12.376  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.376  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.378  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-15 13:55:12.378  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 13:55:12.378  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:12.378  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:12.378  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.378  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 13:55:12.378  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
,11-15 13:55:12.379  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.379  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
,11-15 13:55:12.379  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:12.380  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.381  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:12.382  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:12.382  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.382  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:12.382  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-15 13:55:12.382  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.382  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.383  5784  5831 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-15 13:55:12.383  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:12.384  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:12.384  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-15 13:55:12.384  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.384  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:12.384  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:12.384  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 13:55:12.384  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.384  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:12.385  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.387  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.388  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.388  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.388  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-15 13:55:12.388  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:12.388  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.388  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
,11-15 13:55:12.389  5784  5831 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-15 13:55:12.389  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 13:55:12.390  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:12.390  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:12.390  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.390  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:12.390  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:12.390  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.390  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
,11-15 13:55:12.390  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:12.391  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.393  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.393  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.393  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.393  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-15 13:55:12.394  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:12.394  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.394  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.395  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 13:55:12.395  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 13:55:12.395  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 13:55:12.395  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 13:55:12.396  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 13:55:12.396  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 13:55:12.396  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 13:55:12.397  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 13:55:12.397  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 13:55:12.397  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:12.397  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:12.397  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:12.397  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.397  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 13:55:12.397  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:12.397  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.398  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.398  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:12.399  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:12.403  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.403  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.403  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.403  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-15 13:55:12.403  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:12.403  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.403  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.404  5784  5831 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 13:55:12.404  5784  5831 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-15 13:55:12.405  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-15 13:55:12.408  5784  5831 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-15 13:55:12.408  5784  5831 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-15 13:55:12.409  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-15 13:55:12.410  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-15 13:55:12.411  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-15 13:55:12.411  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-15 13:55:12.411  5784  5831 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-15 13:55:12.411  5784  5831 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-15 13:55:12.411  5784  5831 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-15 13:55:12.411  5784  5831 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 13:55:12.411  5784  5831 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-15 13:55:12.411  5784  5831 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-15 13:55:12.412  5784  5831 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 13:55:12.412  5784  5831 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-15 13:55:12.412  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-15 13:55:12.418  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-15 13:55:12.419  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-15 13:55:12.419  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-15 13:55:12.420  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-15 13:55:12.420  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-15 13:55:12.420  5784  5831 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-15 13:55:12.421  5784  5831 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 13:55:12.421  5784  5831 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-15 13:55:12.421  5784  5836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
11-15 13:55:12.421  5784  5836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-15 13:55:12.421  5784  5836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-15 13:55:12.421  5784  5836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-15 13:55:12.422  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:12.422  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:12.422  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:12.422  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.422  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:12.423  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-15 13:55:12.424  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:12.424  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.424  5784  5836 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-15 13:55:12.424  5784  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 13:55:12.425  5784  5837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
11-15 13:55:12.425  5784  5837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-15 13:55:12.425  5784  5837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
11-15 13:55:12.425  5784  5837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
11-15 13:55:12.422  4932  4932 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30339]" dev="sockfs" ino=30339 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 13:55:12.422  4932  4932 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[30339]" dev="sockfs" ino=30339 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 13:55:12.427  5784  5836 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-15 13:55:12.428  5784  5836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-15 13:55:12.428  5784  5836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
11-15 13:55:12.424  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.428  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:12.428  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.433  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.433  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.433  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.433  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:12.433  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:12.433  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.433  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.434  5784  5831 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-15 13:55:12.435  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:12.435  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:12.435  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:12.435  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.435  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:12.436  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:12.436  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.436  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.436  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:12.436  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.437  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.438  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.438  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.438  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:12.438  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:12.438  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.438  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.439  5784  5831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-15 13:55:12.439  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:12.439  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:12.439  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:12.439  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.439  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:12.439  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:12.439  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.439  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.439  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:12.439  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.440  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.441  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.441  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.441  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:12.441  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:12.441  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.441  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.441  5784  5831 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-15 13:55:12.441  5784  5831 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-15 13:55:12.442  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 13:55:12.442  5784  5831 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-15 13:55:12.442  5784  5831 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-15 13:55:12.442  5784  5831 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-15 13:55:12.442  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 13:55:12.442  5784  5831 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-15 13:55:12.442  5784  5831 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-15 13:55:12.442  5784  5831 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-15 13:55:12.442  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 13:55:12.442  5784  5831 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-15 13:55:12.442  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:12.442  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:12.442  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:12.443  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.443  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:12.443  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:12.443  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.443  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.443  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:12.443  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.444  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.444  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:12.444  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:12.444  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:12.444  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:12.444  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.444  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.445  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:12.445  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:12.445  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:12.445  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:12.445  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:12.445  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 13:55:17.051   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 13:55:17.446  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 13:55:17.446  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:17.446  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 13:55:17.446  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:17.447  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:17.447  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:17.447  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:17.447  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-15 13:55:17.447  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:17.448  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:17.448  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:17.448  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:17.448  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:17.448  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:17.449  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:17.451  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.452  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.452  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.452  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-15 13:55:17.452  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:17.452  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:17.453  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
,11-15 13:55:17.457  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 13:55:17.458  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 13:55:17.458  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 13:55:17.464  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 13:55:17.466  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-15 13:55:17.466  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 13:55:17.466  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 13:55:17.467  5784  5838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 13:55:17.467  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 13:55:17.467  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 13:55:17.467  5784  5784 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 13:55:17.467  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:17.467  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-15 13:55:17.468  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 13:55:17.468  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 13:55:17.468  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 13:55:17.468  5784  5838 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 13:55:17.469  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 13:55:17.469  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 13:55:17.469  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:17.469  5784  5784 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 13:55:17.469  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:17.469  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 13:55:17.469  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-15 13:55:17.470  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 13:55:17.470  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:17.469  4941  4941 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32570]" dev="sockfs" ino=32570 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 13:55:17.472  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.472  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 13:55:17.472  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.473  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:17.473  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:17.473  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 13:55:17.473  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:17.473  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 13:55:17.473  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:17.473  5784  5784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 13:55:17.473  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-15 13:55:17.469  4941  4941 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32570]" dev="sockfs" ino=32570 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 13:55:17.473  5784  5838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 13:55:17.473  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:17.473  5784  5838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 13:55:17.473  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 13:55:17.473  5784  5838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 13:55:17.474  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
,11-15 13:55:17.474  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:17.474  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:17.474  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:17.474  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.474  5784  5784 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 13:55:17.475  5784  5784 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 13:55:17.476  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:17.476  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.476  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:17.477  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:17.477  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-15 13:55:17.477  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:17.477  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:17.479  5784  5831 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-15 13:55:17.479  5784  5831 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-15 13:55:17.479  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 13:55:17.479  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 13:55:17.479  5784  5831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 13:55:17.480  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 13:55:17.480  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:17.480  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:17.480  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:17.480  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:17.480  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:17.480  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 13:55:17.480  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:17.480  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:17.480  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.482  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.482  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.482  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:17.482  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:17.482  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:17.482  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:17.483  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:17.488  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:17.488  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:17.488  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:17.488  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:55:17.488  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 13:55:17.488  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:17.488  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:17.488  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:17.488  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:17.489  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.490  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.491  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.491  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.491  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-15 13:55:17.491  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:17.491  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:17.491  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
,11-15 13:55:17.493  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:55:17.493  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:55:17.494  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:55:17.494  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 13:55:17.494  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:55:17.494  5784  5831 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867c346 not in the list
11-15 13:55:17.494  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:17.494  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
11-15 13:55:17.494  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:17.494  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.496  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:55:17.496  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.496  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:55:17.496  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:55:17.496  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:55:17.496  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:17.496  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd1a907 not in the list
,11-15 13:55:17.498  5784  5831 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-15 13:55:17.498  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 13:55:17.498  5784  5831 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-15 13:55:17.498  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 13:55:17.498  5784  5831 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-15 13:55:17.498  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-15 13:55:17.500  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-15 13:55:17.501  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-15 13:55:17.501  5784  5831 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-15 13:55:17.501  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-15 13:55:17.501  5784  5831 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-15 13:55:17.501  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-15 13:55:17.501  5784  5831 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-15 13:55:17.501  5784  5831 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-15 13:55:17.502  5784  5831 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-15 13:55:17.502  5784  5831 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-15 13:55:17.503  5784  5831 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-15 13:55:17.503  5784  5831 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-15 13:55:17.503  5784  5831 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-15 13:55:17.503  5784  5831 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-15 13:55:17.504  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 13:55:17.504  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@53a864 added. We now have 3 listener(s)
11-15 13:55:17.504  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 13:55:17.507  5784  5831 D BluetoothAdapter: enable(): BT is already enabled..!
,11-15 13:55:17.507   928  3673 D WifiService: setWifiEnabled: true pid=5784, uid=10077
11-15 13:55:17.507   928  3673 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 13:55:17.554  4732  4922 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-15 13:55:17.554  4732  4930 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-15 13:55:17.974  5784  5784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 13:55:20.078   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 13:55:22.513  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 13:55:22.513  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2455acd added. We now have 4 listener(s)
,11-15 13:55:22.513  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 13:55:22.526  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 13:55:22.526  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2455acd removed from the list
11-15 13:55:22.526  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:55:22.528  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 13:55:22.528  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c04f82 added. We now have 4 listener(s)
11-15 13:55:22.528  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 13:55:22.530  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 13:55:22.530  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c04f82 removed from the list
11-15 13:55:22.531  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 13:55:22.532  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 13:55:22.533  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa7a693 added. We now have 4 listener(s)
11-15 13:55:22.533  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 13:55:22.537   928  3902 D WifiService: setWifiEnabled: false pid=5784, uid=10077
,11-15 13:55:22.537   928  3902 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 13:55:22.543   928  3116 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-15 13:55:22.543   928  3116 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-15 13:55:22.543   928  3116 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 13:55:22.543   928  3116 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 13:55:22.550  4732  4790 D BluetoothAdapterState: Current state: ON, message: 23
,11-15 13:55:22.550  4732  4790 D BluetoothAdapterProperties: Setting state to 13
11-15 13:55:22.550  4732  4790 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-15 13:55:22.551  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 13:55:22.551  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 13:55:22.552  4732  4790 D BluetoothAdapterProperties: onBluetoothDisable()
,11-15 13:55:22.552  4732  4790 I BluetoothAdapterState: Entering PendingCommandState
,11-15 13:55:22.560  4732  4732 D BluetoothMapService: onReceive
,11-15 13:55:22.560  4732  4732 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 13:55:22.560  4732  4732 D BluetoothMapService: STATE_TURNING_OFF
11-15 13:55:22.561  4732  4732 D BluetoothMapService: MAP Service closeService in
,11-15 13:55:22.561  4732  4732 D BluetoothMapMasInstance0: MAP Service shutdown
,11-15 13:55:22.561  4732  4732 D ObexServerSockets0: shutdown(block = true)
,11-15 13:55:22.562   928  5491 D DhcpClient: Clearing IP address
11-15 13:55:22.562  4732  4732 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 13:55:22.562  4732  4944 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-15 13:55:22.562   508   921 D CommandListener: Clearing all IP addresses on wlan0
11-15 13:55:22.562  4732  4930 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-15 13:55:22.562  4732  4732 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 13:55:22.563  4732  4945 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-15 13:55:22.566  4732  4732 I BtOppRfcommListener: stopping Accept Thread
11-15 13:55:22.567  5784  5831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 13:55:22.567  5784  5831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 13:55:22.567  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:22.567  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:22.567  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:55:22.567  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 13:55:22.567  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 13:55:22.567  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 13:55:22.567  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 13:55:22.567  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 13:55:22.568  5784  5831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 13:55:22.568   508   921 D CommandListener: Setting iface cfg
11-15 13:55:22.568  5784  5831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 13:55:22.569  5784  5831 D io.jxcore.node.ConnectivityMonitor: start: OK
11-15 13:55:22.569  4732  5444 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-15 13:55:22.569  4732  5444 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-15 13:55:22.571  3697  5554 V NativeCrypto: Read error: ssl=0x7f6c649380: I/O error during system call, Connection timed out
11-15 13:55:22.573  3697  5554 V NativeCrypto: SSL shutdown failed: ssl=0x7f6c649380: I/O error during system call, Broken pipe
11-15 13:55:22.574  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 13:55:22.578  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 13:55:22.579   928  3755 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-15 13:55:22.579   928  5489 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-15 13:55:22.581   928  5489 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-15 13:55:22.582   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-15 13:55:22.582   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-15 13:55:22.583   928  3129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-15 13:55:22.586   928   941 I ActivityManager: Start proc 5842:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-15 13:55:22.586  4732  4794 D BluetoothAdapterProperties: Scan Mode:20
11-15 13:55:22.587  4732  4790 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-15 13:55:22.593  4732  4732 D HeadsetService: Received stop request...Stopping profile...
11-15 13:55:22.594   622   622 E Parcel  : Reading a NULL string not supported here.
11-15 13:55:22.595  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:22.595   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-15 13:55:22.595  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:55:22.595  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:22.595  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:22.595  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:55:22.595  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 13:55:22.595  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 13:55:22.595  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-15 13:55:22.595  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 13:55:22.595  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 13:55:22.595   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-15 13:55:22.597  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:22.598  5784  5784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-15 13:55:22.599   928   928 D BluetoothHeadset: Proxy object disconnected
11-15 13:55:22.600  3892  3911 D BluetoothHeadset: Proxy object disconnected
,11-15 13:55:22.600  4732  4732 D A2dpService: Received stop request...Stopping profile...
11-15 13:55:22.601  3218  3230 D BluetoothHeadset: Proxy object disconnected
11-15 13:55:22.601   928  3129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-15 13:55:22.601   928   928 D BluetoothHeadset: Proxy object disconnected
11-15 13:55:22.603   928   928 D BluetoothHeadset: Proxy object disconnected
11-15 13:55:22.603   928   928 D RttService: SCAN_AVAILABLE : 1
11-15 13:55:22.603   928   928 D BluetoothA2dp: Proxy object disconnected
11-15 13:55:22.601  4732  4936 D A2dpStateMachine: Exit Disconnected: -1
11-15 13:55:22.603   928  3184 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-15 13:55:22.603  3859  3979 W QCNEJ   : |CORE| network lost: 100
11-15 13:55:22.605  3859  3979 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-15 13:55:22.605  4732  4732 D HidService: Received stop request...Stopping profile...
11-15 13:55:22.612  4732  4732 D HidService: Stopping Bluetooth HidService
,11-15 13:55:22.614  4732  4732 V BluetoothAdapterState: isTurningOff()=true
,11-15 13:55:22.616   928  5492 D DhcpClient: Receive thread stopped
11-15 13:55:22.616  4732  4732 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:22.616  4732  4732 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:22.616  4732  4732 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:22.616  4732  4732 D HealthService: Received stop request...Stopping profile...
11-15 13:55:22.619  3218  3218 D HeadsetProfile: Bluetooth service disconnected
11-15 13:55:22.619  3218  3218 D BluetoothA2dp: Proxy object disconnected
11-15 13:55:22.620  4732  4732 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-15 13:55:22.621  4732  4732 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-15 13:55:22.621  4732  4732 D PanService: Received stop request...Stopping profile...
11-15 13:55:22.621  4732  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:22.621  3218  3218 D BluetoothInputDevice: Proxy object disconnected
11-15 13:55:22.621  4732  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:22.622  3218  3218 D HidProfile: Bluetooth service disconnected
11-15 13:55:22.622  4732  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:22.622  4732  4794 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-15 13:55:22.622  3218  3218 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 13:55:22.622  3218  3218 D PanProfile: Bluetooth service disconnected
11-15 13:55:22.622  4732  4794 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-15 13:55:22.622  4732  4732 D BluetoothMapService: Received stop request...Stopping profile...
11-15 13:55:22.623  4732  4732 D BluetoothMapService: stop()
11-15 13:55:22.623  4732  4732 D BluetoothMapAppObserver: deinitObservers()
11-15 13:55:22.623  4732  4732 D BluetoothMapAppObserver: removeReceiver()
11-15 13:55:22.624  4732  4732 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:22.624  3218  3218 D BluetoothMap: Proxy object disconnected
11-15 13:55:22.624  3218  3218 D MapProfile: Bluetooth service disconnected
11-15 13:55:22.624  4732  4732 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:22.624  4732  4732 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:22.624  4732  4732 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:22.625   928  3116 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-15 13:55:22.626  4732  4794 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-15 13:55:22.626  4732  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:22.626  4732  4732 D SapService: Received stop request...Stopping profile...
11-15 13:55:22.626  4732  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:22.626  4732  4732 V SapService: stop()
11-15 13:55:22.626  4732  4922 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 13:55:22.626  4732  4922 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-15 13:55:22.627  4732  4922 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 13:55:22.627  4732  4922 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-15 13:55:22.628  4732  4732 V BluetoothAdapterState: isTurningOff()=true
,11-15 13:55:22.628  4732  4732 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:22.628  4732  4732 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:22.628  4732  4732 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:22.628  4732  4732 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-15 13:55:22.628  4732  4732 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-15 13:55:22.628  4732  4732 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:22.628  4732  4794 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 13:55:22.629  4732  4732 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:22.629  4732  4732 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:22.629  4732  4732 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 13:55:22.629  4732  4732 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-15 13:55:22.629  4732  4794 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-15 13:55:22.629  4732  4732 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-15 13:55:22.629  4732  4732 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:22.629  4732  4732 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:22.629  4732  4732 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:22.630  4732  4732 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:22.630  4732  4732 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-15 13:55:22.630  4732  4732 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-15 13:55:22.632  4732  4732 D BluetoothMapService: MAP Service closeService in
11-15 13:55:22.632  4732  4732 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:22.632  4732  4732 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:22.632  4732  4732 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:22.632  4732  4732 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:22.632  4732  4732 D BluetoothMapService: cleanup()
11-15 13:55:22.633  4732  4732 D BluetoothMapService: MAP Service closeService in
11-15 13:55:22.633  4732  4732 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:22.633  4732  4732 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:22.633  4732  4732 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:22.633  4732  4732 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:22.633  4732  4790 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-15 13:55:22.633  4732  4790 D BluetoothAdapterProperties: Setting state to 15
11-15 13:55:22.633  4732  4790 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-15 13:55:22.634  4732  4790 I BluetoothAdapterState: Entering BleOnState
11-15 13:55:22.634   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 13:55:22.634   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-15 13:55:22.634  3218  3230 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 13:55:22.635   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-15 13:55:22.635  3218  3232 D BluetoothMap: onBluetoothStateChange: up=false
11-15 13:55:22.639  3218  4038 D BluetoothPbap: onBluetoothStateChange: up=false
,11-15 13:55:22.641  3218  3230 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 13:55:22.642   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-15 13:55:22.642  3218  3232 D BluetoothPan: onBluetoothStateChange on: false
11-15 13:55:22.642   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 13:55:22.643  3892  3909 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 13:55:22.643  3218  4038 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 13:55:22.643  4732  4790 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-15 13:55:22.643  4732  4790 D BluetoothAdapterProperties: Setting state to 16
11-15 13:55:22.643  4732  4790 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-15 13:55:22.644  4732  4790 D BluetoothAdapterProperties: onBleDisable
11-15 13:55:22.644  4732  4790 I BluetoothAdapterState: Entering PendingCommandState
11-15 13:55:22.644  4732  4791 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-15 13:55:22.645  4732  4794 D BluetoothAdapterProperties: Scan Mode:20
11-15 13:55:22.646   928  3116 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 13:55:22.646  4732  4922 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-15 13:55:22.646  4732  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-15 13:55:22.647  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:22.647  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:55:22.647  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:22.647  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:22.647  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:55:22.647  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 13:55:22.647  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 13:55:22.647  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 13:55:22.647  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 13:55:22.647  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 13:55:22.648  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:22.648  5784  5784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 13:55:22.651  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:55:22.660   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 13:55:22.661   508   921 D CommandListener: Clearing all IP addresses on wlan0
11-15 13:55:22.662   928  3129 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-15 13:55:22.662   928  3129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-15 13:55:22.663   928  3116 D DhcpClient: doQuit
11-15 13:55:22.663   928  3116 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-15 13:55:22.664   928  5491 D DhcpClient: onQuitting
,11-15 13:55:22.666  3586  3586 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-15 13:55:22.666  5842  5842 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-15 13:55:22.670   928   945 D Tethering: MasterInitialState.processMessage what=3
11-15 13:55:22.671  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:22.671  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:55:22.671  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:22.671  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:22.671  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 13:55:22.671  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 13:55:22.671  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 13:55:22.671  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 13:55:22.671  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 13:55:22.671  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 13:55:22.672  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:22.672  5784  5784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-15 13:55:22.674  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:55:22.681  5372  5372 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5e5b08d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-15 13:55:22.682  4054  4054 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-15 13:55:22.684  5079  5095 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-15 13:55:22.685  5079  5095 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-15 13:55:22.685  5079  5095 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-15 13:55:22.685  5079  5095 E SarControlService: no key has been found,reset the power
11-15 13:55:22.685  5079  5122 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-15 13:55:22.685  5079  5122 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-15 13:55:22.685  3586  3586 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-15 13:55:22.685  5079  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-15 13:55:22.686  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 13:55:22.686  5109  5109 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-15 13:55:22.687  5079  5122 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-15 13:55:22.688  5079  5122 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-15 13:55:22.688  5079  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-15 13:55:22.690  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 13:55:22.690  3586  3586 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-15 13:55:22.690  5109  5109 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-15 13:55:22.695  3697  5862 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-15 13:55:22.696  5109  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fcea31b HexData = [00000000ea03000000000000ffffffff]
11-15 13:55:22.696  5109  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 13:55:22.697  5109  5130 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,11-15 13:55:22.697  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 13:55:22.697  5079  5092 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-15 13:55:22.702  5109  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fcea31b HexData = [00000000eb03000000000000ffffffff]
,11-15 13:55:22.702  5109  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 13:55:22.702  5109  5130 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-15 13:55:22.703  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 13:55:22.703  5079  5091 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-15 13:55:22.712  5842  5842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 13:55:22.714  3586  3586 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-15 13:55:22.718   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1388446:true
,11-15 13:55:22.720  3697  3697 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 13:55:22.728   508   921 E Netd    : netlink response contains error (No such file or directory)
,11-15 13:55:22.729   928  3129 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-15 13:55:22.736  3586  3586 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-15 13:55:22.736  3697  5859 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-15 13:55:22.739  3697  5859 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-15 13:55:22.751  5842  5842 D LocalBluetoothProfileManager: Adding local MAP profile
,11-15 13:55:22.753  5842  5842 D BluetoothMap: Create BluetoothMap proxy object
,11-15 13:55:22.760  5842  5842 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-15 13:55:22.763  3697  5862 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 13:55:22.767  5842  5842 D DockEventReceiver: finishStartingService: stopping service
,11-15 13:55:22.770  5842  5842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 13:55:22.773  3697  5859 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
11-15 13:55:22.775  3697  3697 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 13:55:22.776  5842  5842 D DockEventReceiver: finishStartingService: stopping service
,11-15 13:55:22.780   928  3273 I ActivityManager: Killing 5372:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-15 13:55:22.825   928  3893 I ActivityManager: Start proc 5873:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-15 13:55:22.839  4476  4476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 13:55:22.838   928  3116 D wifi    : In wifi stop Hal
11-15 13:55:22.840   928  3116 D wifi    : halHandle = 0x7f59ee6120, mVM = 0x7f764cd140, mCls = 0x100a02
11-15 13:55:22.840   928  3585 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-15 13:55:22.840   928  3585 D WifiHAL : Got a signal to exit!!!
11-15 13:55:22.840   928  3585 I WifiHAL : Exit wifi_event_loop
11-15 13:55:22.841   928  3116 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-15 13:55:22.841   928  3116 E WifiHAL : Event processing terminated
11-15 13:55:22.841   928  3116 D wifi    : In wifi cleaned up handler
11-15 13:55:22.841   928  3116 I WifiHAL : Internal cleanup completed
,11-15 13:55:22.842  4228  4336 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 13:55:22.842  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:55:22.854  4732  4794 I bt_hci  : shut_down
,11-15 13:55:22.854  5873  5873 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-15 13:55:22.858  4732  4798 D bt_hwcfg: hw_epilog_process
,11-15 13:55:22.858  4732  4798 I bt_vendor: low_power_mode_cb
,11-15 13:55:22.861  4732  4798 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-15 13:55:22.861   928  3585 D wifi    : set interface wlan0 flags (DOWN)
11-15 13:55:22.862  4732  4798 I bt_vendor: epilog_cb
11-15 13:55:22.862  4732  4798 I bt_hci  : epilog_finished_callback
11-15 13:55:22.862   928  3116 D WifiNative-HAL: HAL event thread stopped successfully
11-15 13:55:22.863   928  3882 I ActivityManager: Killing 5523:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-15 13:55:22.897  4732  4794 I bt_hci_h4: hal_close
,11-15 13:55:22.897  4732  4794 I bt_userial_vendor: device fd = 54 close
,11-15 13:55:22.905  4066  4066 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-15 13:55:22.909  4066  4066 D SystemUpdateService: onCreate
,11-15 13:55:22.911  4066  4066 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-15 13:55:22.915  4066  5891 I SystemUpdateService: active receiver: enabled
,11-15 13:55:22.920  4066  4066 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-15 13:55:22.925  4066  5891 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 13:55:22.926  4066  5519 I iu.UploadsManager: num queued entries: 0
,11-15 13:55:22.927  4066  5519 I iu.UploadsManager: num updated entries: 0
11-15 13:55:22.927  4066  5519 I iu.SyncManager: NEXT; no task
,11-15 13:55:22.928   508   921 E Netd    : netlink response contains error (No such file or directory)
,11-15 13:55:22.929  4066  4066 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 13:55:22.931  4066  4066 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 13:55:22.932  4066  5891 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-15 13:55:22.932  4066  5891 I SystemUpdateService: now status is 0 (complete)
11-15 13:55:22.932  4066  5891 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 13:55:22.933  4066  5891 I SystemUpdateService: file has been verified
11-15 13:55:22.933  4066  5891 I SystemUpdateService: OTA package size = 21989297
,11-15 13:55:22.938  4066  5891 I SystemUpdateService: showing system update notification
,11-15 13:55:22.943   928   938 I ActivityManager: Start proc 5894:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-15 13:55:22.956   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 13:55:22.957  4066  4066 D SystemUpdateService: onDestroy
,11-15 13:55:22.985  5894  5894 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
11-15 13:55:22.987  5894  5894 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 13:55:22.994  5894  5894 D SprintDMHelper: simOperator: 
11-15 13:55:22.994  5894  5894 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 13:55:23.000  4732  4791 D bt_stack_manager: event_shut_down_stack finished.
,11-15 13:55:23.001  4732  4790 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-15 13:55:23.003  4732  4790 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-15 13:55:23.003  4732  4732 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-15 13:55:23.003  4732  4732 D BtGatt.GattService: Received stop request...Stopping profile...
11-15 13:55:23.003  4732  4732 D BtGatt.GattService: stop()
11-15 13:55:23.003  4732  4732 D BtGatt.AdvertiseManager: advertise clients cleared
11-15 13:55:23.005  4732  4732 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:23.005  4732  4732 V BluetoothAdapterState: isTurningOn()=false
,11-15 13:55:23.005  4732  4732 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:23.005  4732  4732 V BluetoothAdapterState: isBleTurningOff()=true
11-15 13:55:23.005  4732  4790 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-15 13:55:23.005  4732  4790 D BluetoothAdapterProperties: Setting state to 10
,11-15 13:55:23.005  4732  4790 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-15 13:55:23.006  4732  4790 I BluetoothAdapterState: Entering OffState
11-15 13:55:23.006   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-15 13:55:23.013  4732  4732 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-15 13:55:23.013  4732  4732 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-15 13:55:23.013  4732  4732 I BluetoothServiceJni: cleanupNative: return from cleanup
11-15 13:55:23.015  4732  4791 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-15 13:55:23.023  4732  4732 I art     : System.exit called, status: 0
,11-15 13:55:23.025  4732  4732 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-15 13:55:23.028  4476  5907 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-15 13:55:23.048   928  3273 I ActivityManager: Killing 5614:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-15 13:55:23.065   928  3932 I ActivityManager: Process com.android.bluetooth (pid 4732) has died
,11-15 13:55:23.066   928   945 D Tethering: InitialState.processMessage what=4
,11-15 13:55:23.069   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-15 13:55:27.571   928  3902 D WifiService: setWifiEnabled: true pid=5784, uid=10077
,11-15 13:55:27.571   928  3902 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 13:55:27.584   508   921 D SoftapController: Softap fwReload - Ok
,11-15 13:55:27.589   508   921 D CommandListener: Setting iface cfg
11-15 13:55:27.589   508   921 D CommandListener: Trying to bring down wlan0
,11-15 13:55:27.592   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-15 13:55:27.598   928  3116 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 13:55:28.205   928  3116 D wifi    : set interface wlan0 flags (UP)
11-15 13:55:28.206   928  3116 I WifiHAL : Initializing wifi
11-15 13:55:28.206   928  3116 I WifiHAL : Creating socket
,11-15 13:55:28.211   928  3116 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-15 13:55:28.211   928  3116 D wifi    : Did set static halHandle = 0x7f59ee6120
,11-15 13:55:28.211   928  3116 D wifi    : halHandle = 0x7f59ee6120, mVM = 0x7f764cd140, mCls = 0x101906
,11-15 13:55:28.212   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-15 13:55:28.212   928  3116 D wifi    : array field set
11-15 13:55:28.213   928  3116 I WifiNative-HAL: interface[0] = wlan0
11-15 13:55:28.215   928  5913 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546969641248
11-15 13:55:28.215   928  5913 D wifi    : waitForHalEvents called, vm = 0x7f764cd140, obj = 0x101906, env = 0x7f5b87ca40
,11-15 13:55:28.291  5914  5914 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-15 13:55:28.316   928  3116 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-15 13:55:28.320  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:55:28.354  5914  5914 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 13:55:28.370  5914  5914 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 13:55:28.370  5914  5914 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-15 13:55:28.380   928  3116 D WifiConfigStore: Loading config and enabling all networks 
,11-15 13:55:28.382  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 13:55:28.382  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:55:28.382  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:28.382  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:28.382  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:55:28.382  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 13:55:28.382  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 13:55:28.382  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 13:55:28.382  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 13:55:28.382  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 13:55:28.382  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:28.382  5784  5784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 13:55:28.392   928  3116 D WifiConfigStore: loaded 0 passpoint configs
,11-15 13:55:28.393   928  3116 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-15 13:55:28.393   928  3116 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-15 13:55:28.393   928  3116 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-15 13:55:28.394   928  3116 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-15 13:55:28.394   928  3116 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-15 13:55:28.394   928  3116 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-15 13:55:28.395   928  3116 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-15 13:55:28.395   928  3116 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-15 13:55:28.395   928  3116 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-15 13:55:28.395   928  3116 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-15 13:55:28.395   928  3116 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-15 13:55:28.395   928  3116 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-15 13:55:28.396   928  3116 D WifiNative-HAL: Setting external_sim to 1
11-15 13:55:28.397   928  3116 D wifi    : setting dfs flag to true, 0x7f5bc6df00
11-15 13:55:28.397   928  3116 D WifiStateMachine: Setting OUI to DA-A1-19
11-15 13:55:28.397   928  3116 D wifi    : setting scan oui 0x7f5bc6df00
,11-15 13:55:28.397   928  3116 D WifiHAL : Sending mac address OUI
,11-15 13:55:28.398  4476  4476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 13:55:28.400   928  3116 E native  : do suspend false
,11-15 13:55:28.406   928  3116 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-15 13:55:28.407   928   928 D RttService: SCAN_AVAILABLE : 3
,11-15 13:55:28.407   928  3184 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-15 13:55:28.410   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-15 13:55:28.413   508   921 D CommandListener: Setting iface cfg
,11-15 13:55:28.418   928  3115 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-15 13:55:28.419   928  3115 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-15 13:55:28.427   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=217361 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-15 13:55:28.427   928  3115 D WifiNative-HAL: p2pGetDeviceAddress
11-15 13:55:28.427   928  3115 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-15 13:55:29.554   624   624 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-15 13:55:29.554   624   624 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 13:55:30.532   928  3116 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 12, 13 -> obsolete
,11-15 13:55:31.516  5914  5914 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 13:55:31.524  5914  5914 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 13:55:31.530  5914  5914 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 13:55:31.535  5914  5914 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 13:55:31.559   928  3116 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-15 13:55:31.561   928  3116 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-15 13:55:31.561   928  3116 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 13:55:31.571   928  3116 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-15 13:55:31.605   928  3116 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-15 13:55:31.611  5914  5914 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-15 13:55:32.028  5914  5914 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-15 13:55:32.064  5914  5914 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-15 13:55:32.064  5914  5914 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-15 13:55:32.075   928  3116 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 13:55:32.075   928  3116 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-15 13:55:32.075   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-15 13:55:32.091   928  3116 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 13:55:32.103   508   921 D CommandListener: Setting iface cfg
,11-15 13:55:32.108   928  3116 D WifiStateMachine: Start Dhcp Watchdog 2
,11-15 13:55:32.114   928  5930 D DhcpClient: Receive thread started
,11-15 13:55:32.120   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 13:55:32.120   928  3116 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-15 13:55:32.120   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-15 13:55:32.200   928  3116 E native  : do suspend false
,11-15 13:55:32.217   928  5929 D DhcpClient: Broadcasting DHCPDISCOVER
,11-15 13:55:32.231   928  5930 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172618, domain null
,11-15 13:55:32.231   928  5929 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172618 seconds
,11-15 13:55:32.232   928  5929 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-15 13:55:32.247   928  5930 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-15 13:55:32.248   928  5929 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-15 13:55:32.250   508   921 D CommandListener: Setting iface cfg
,11-15 13:55:32.255   928  3116 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-15 13:55:32.257   928  5929 D DhcpClient: Scheduling renewal in 86399s
,11-15 13:55:32.268   928  3116 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-15 13:55:32.269   928  3116 D WifiConfigStore: No blacklist allowed without epno enabled
,11-15 13:55:32.270   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-15 13:55:32.273   928  3129 D ConnectivityService: Adding iface wlan0 to network 101
11-15 13:55:32.273   928  3116 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-15 13:55:32.315   928  3129 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-15 13:55:32.316   928  3129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-15 13:55:32.318   928  3129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-15 13:55:32.320   928  3129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-15 13:55:32.323   928  3129 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-15 13:55:32.330   928  3129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 13:55:32.335   928  3129 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-15 13:55:32.335   928  3129 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-15 13:55:32.335   928  3129 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-15 13:55:32.335   928  3116 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-15 13:55:32.335   928  3129 D ConnectivityService:    accepting network in place of null
11-15 13:55:32.335   928  3116 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 13:55:32.336   928  3129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 13:55:32.349   928  5928 D NetlinkSocketObserver: NeighborEvent{elapsedMs=221283, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-15 13:55:32.359   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 13:55:32.379   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 13:55:32.382   928  3129 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-15 13:55:32.382  3859  3979 W QCNEJ   : |CORE| network available: 101
,11-15 13:55:32.382   928  3129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-15 13:55:32.383   928  3129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-15 13:55:32.385   928   945 D Tethering: MasterInitialState.processMessage what=3
11-15 13:55:32.387  3859  3979 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-15 13:55:32.388  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:32.388  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:55:32.388  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:32.388  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:32.388  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:55:32.388  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 13:55:32.388  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 13:55:32.388  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 13:55:32.388  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 13:55:32.388  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 13:55:32.388  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 13:55:32.388  5784  5784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 13:55:32.389  3859  3979 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-15 13:55:32.389  3859  3979 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-15 13:55:32.398  5079  5095 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-15 13:55:32.398  5079  5095 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-15 13:55:32.398  5079  5095 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-15 13:55:32.398  5079  5095 E SarControlService: no key has been found,reset the power
11-15 13:55:32.398  5079  5122 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-15 13:55:32.398  5079  5122 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-15 13:55:32.399  5079  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-15 13:55:32.399  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-15 13:55:32.400  5109  5109 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-15 13:55:32.401  5079  5122 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-15 13:55:32.401  5079  5122 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-15 13:55:32.401  5079  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-15 13:55:32.402  4054  4054 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-15 13:55:32.404  4066  4066 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-15 13:55:32.407  4066  4066 D SystemUpdateService: onCreate
11-15 13:55:32.409  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 13:55:32.409  5109  5109 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-15 13:55:32.414  4066  4066 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-15 13:55:32.415  5109  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fcea31b HexData = [00000000ec03000000000000ffffffff]
11-15 13:55:32.415  5109  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 13:55:32.415  5109  5130 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-15 13:55:32.416  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 13:55:32.416  5079  5092 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-15 13:55:32.419  5109  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fcea31b HexData = [00000000ed03000000000000ffffffff]
,11-15 13:55:32.419  5109  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 13:55:32.419  5109  5130 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-15 13:55:32.419  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-15 13:55:32.419  5079  5091 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-15 13:55:32.427  4066  4066 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-15 13:55:32.434  4066  5519 I iu.UploadsManager: num queued entries: 0
,11-15 13:55:32.435  4066  5519 I iu.UploadsManager: num updated entries: 0
,11-15 13:55:32.437   928  5927 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,11-15 13:55:32.442  4066  4066 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 13:55:32.444  4066  4066 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-15 13:55:32.446  5894  5894 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 13:55:32.449  5894  5894 D SprintDMHelper: simOperator: 
11-15 13:55:32.449  5894  5894 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 13:55:32.461  4066  5940 I SystemUpdateService: active receiver: enabled
,11-15 13:55:32.465  4066  5519 I iu.SyncManager: NEXT; no task
,11-15 13:55:32.484   928  5927 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Nov 2016 12:55:32 GMT], X-Android-Received-Millis=[1479214532483], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479214532459]}
,11-15 13:55:32.484   928  3129 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-15 13:55:32.485   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-15 13:55:32.485   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 13:55:32.486   928  3129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-15 13:55:32.489  4066  5940 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 13:55:32.493  4066  5940 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-15 13:55:32.493  4066  5940 I SystemUpdateService: now status is 0 (complete)
11-15 13:55:32.493  4066  5940 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 13:55:32.493  4066  5940 I SystemUpdateService: file has been verified
11-15 13:55:32.493  4066  5940 I SystemUpdateService: OTA package size = 21989297
,11-15 13:55:32.499  4066  5940 I SystemUpdateService: showing system update notification
,11-15 13:55:32.508   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 13:55:32.509  4066  4066 D SystemUpdateService: onDestroy
,11-15 13:55:32.582   928  3893 D WifiService: setWifiEnabled: false pid=5784, uid=10077
,11-15 13:55:32.582   928  3893 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 13:55:32.583  4476  5945 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-15 13:55:32.584   928  3116 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-15 13:55:32.584   928  3116 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-15 13:55:32.584   928  3116 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 13:55:32.584   928  3116 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 13:55:32.592   928  5929 D DhcpClient: Clearing IP address
,11-15 13:55:32.592   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-15 13:55:32.594   508   921 D CommandListener: Setting iface cfg
,11-15 13:55:32.599  3697  5950 V NativeCrypto: Read error: ssl=0x7f701c6d00: I/O error during system call, Connection timed out
,11-15 13:55:32.600  3697  5950 V NativeCrypto: SSL shutdown failed: ssl=0x7f701c6d00: I/O error during system call, Broken pipe
,11-15 13:55:32.604   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-15 13:55:32.604   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-15 13:55:32.609   928   928 D RttService: SCAN_AVAILABLE : 1
,11-15 13:55:32.610   928  3184 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-15 13:55:32.610   622   622 E Parcel  : Reading a NULL string not supported here.
11-15 13:55:32.611   928  3116 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-15 13:55:32.613   928  3129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-15 13:55:32.614   928  3116 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 13:55:32.616  3859  3979 W QCNEJ   : |CORE| network lost: 101
11-15 13:55:32.616   928  5930 D DhcpClient: Receive thread stopped
,11-15 13:55:32.616  3859  3979 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-15 13:55:32.639   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 13:55:32.656   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 13:55:32.657   928  3129 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-15 13:55:32.657   508   921 D CommandListener: Clearing all IP addresses on wlan0
11-15 13:55:32.657   928  3129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-15 13:55:32.658   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-15 13:55:32.660   928  3116 D DhcpClient: doQuit
,11-15 13:55:32.660   928  3116 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-15 13:55:32.660   928  5929 D DhcpClient: onQuitting
11-15 13:55:32.661  5914  5914 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-15 13:55:32.661  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 13:55:32.661  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:55:32.661  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:32.661  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:32.661  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:55:32.661  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 13:55:32.661  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 13:55:32.661  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 13:55:32.661  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 13:55:32.661  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 13:55:32.661  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 13:55:32.661  5784  5784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 13:55:32.665  4054  4054 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-15 13:55:32.666  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:32.666  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:55:32.666  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:32.666  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:32.666  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 13:55:32.666  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 13:55:32.666  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 13:55:32.666  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 13:55:32.666  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 13:55:32.666  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 13:55:32.666  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:32.666  5784  5784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 13:55:32.670  4066  4066 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-15 13:55:32.670  5914  5914 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-15 13:55:32.671  5079  5095 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-15 13:55:32.671  5079  5095 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-15 13:55:32.671  5079  5095 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-15 13:55:32.671  5079  5095 E SarControlService: no key has been found,reset the power
11-15 13:55:32.671  5079  5122 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-15 13:55:32.671  5079  5122 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-15 13:55:32.671  5079  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-15 13:55:32.672  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-15 13:55:32.672  5109  5109 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-15 13:55:32.672  5914  5914 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-15 13:55:32.674  5079  5122 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-15 13:55:32.674  5079  5122 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-15 13:55:32.674  5079  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-15 13:55:32.675  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 13:55:32.675  5109  5109 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-15 13:55:32.678  5109  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fcea31b HexData = [00000000ee03000000000000ffffffff]
11-15 13:55:32.678  5109  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 13:55:32.679  5109  5130 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,11-15 13:55:32.679  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 13:55:32.679  5079  5091 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-15 13:55:32.681  4066  4066 D SystemUpdateService: onCreate
,11-15 13:55:32.684  5109  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fcea31b HexData = [00000000ef03000000000000ffffffff]
,11-15 13:55:32.684  5109  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 13:55:32.684  5109  5130 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-15 13:55:32.685  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 13:55:32.685  5079  5092 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-15 13:55:32.686  4066  4066 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-15 13:55:32.693  4066  5960 I SystemUpdateService: active receiver: enabled
,11-15 13:55:32.695  4066  4066 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-15 13:55:32.698  5914  5914 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-15 13:55:32.700  4066  5519 I iu.UploadsManager: num queued entries: 0
,11-15 13:55:32.700  4066  5519 I iu.UploadsManager: num updated entries: 0
11-15 13:55:32.701  4066  5519 I iu.SyncManager: NEXT; no task
,11-15 13:55:32.704  4066  4066 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 13:55:32.705  4066  4066 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 13:55:32.706  5914  5914 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-15 13:55:32.707  5894  5894 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 13:55:32.712  5894  5894 D SprintDMHelper: simOperator: 
11-15 13:55:32.712  5894  5894 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 13:55:32.721   508   921 E Netd    : netlink response contains error (No such file or directory)
,11-15 13:55:32.722   928  3129 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-15 13:55:32.725  4476  5964 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-15 13:55:32.728  4066  5960 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 13:55:32.730  4066  5960 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-15 13:55:32.731  4066  5960 I SystemUpdateService: now status is 0 (complete)
11-15 13:55:32.731  4066  5960 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-15 13:55:32.732  4066  5960 I SystemUpdateService: file has been verified
11-15 13:55:32.732  4066  5960 I SystemUpdateService: OTA package size = 21989297
,11-15 13:55:32.744  4066  5960 I SystemUpdateService: showing system update notification
,11-15 13:55:32.753   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 13:55:32.754  4066  4066 D SystemUpdateService: onDestroy
,11-15 13:55:32.808   928  3116 D wifi    : In wifi stop Hal
,11-15 13:55:32.808  4476  4476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 13:55:32.808   928  3116 D wifi    : halHandle = 0x7f59ee6120, mVM = 0x7f764cd140, mCls = 0x101906
11-15 13:55:32.808   928  5913 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-15 13:55:32.808   928  5913 D WifiHAL : Got a signal to exit!!!
11-15 13:55:32.808   928  5913 I WifiHAL : Exit wifi_event_loop
11-15 13:55:32.809   928  3116 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-15 13:55:32.809   928  3116 E WifiHAL : Event processing terminated
11-15 13:55:32.809   928  3116 D wifi    : In wifi cleaned up handler
,11-15 13:55:32.809   928  3116 I WifiHAL : Internal cleanup completed
11-15 13:55:32.810  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 13:55:32.811  4228  4336 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 13:55:32.831   928  5913 D wifi    : set interface wlan0 flags (DOWN)
,11-15 13:55:32.832   928  3116 D WifiNative-HAL: HAL event thread stopped successfully
,11-15 13:55:32.893   508   921 E Netd    : netlink response contains error (No such file or directory)
,11-15 13:55:33.039   928   945 D Tethering: InitialState.processMessage what=4
,11-15 13:55:33.045   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-15 13:55:33.383   928  3129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-15 13:55:37.623   928   945 I ActivityManager: Start proc 5972:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-15 13:55:37.719  5972  5972 D AdapterServiceConfig: Adding HeadsetService
,11-15 13:55:37.720  5972  5972 D AdapterServiceConfig: Adding A2dpService
11-15 13:55:37.720  5972  5972 D AdapterServiceConfig: Adding HidService
11-15 13:55:37.720  5972  5972 D AdapterServiceConfig: Adding HealthService
11-15 13:55:37.720  5972  5972 D AdapterServiceConfig: Adding PanService
11-15 13:55:37.720  5972  5972 D AdapterServiceConfig: Adding GattService
,11-15 13:55:37.721  5972  5972 D AdapterServiceConfig: Adding BluetoothMapService
11-15 13:55:37.721  5972  5972 D AdapterServiceConfig: Adding SapService
,11-15 13:55:37.735   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2aafc54:true
,11-15 13:55:37.736  5972  5972 D BluetoothAdapterState: make() - Creating AdapterState
,11-15 13:55:37.738  5972  5972 I bt_bluedroid: init
11-15 13:55:37.738  5972  5984 I BluetoothAdapterState: Entering OffState
,11-15 13:55:37.740  5972  5985 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-15 13:55:37.740  5972  5985 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-15 13:55:37.740  5972  5985 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-15 13:55:37.741  5972  5985 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-15 13:55:37.741  5972  5972 I bt_bluedroid: get_profile_interface socket
11-15 13:55:37.742  5972  5988 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-15 13:55:37.742  5972  5972 I bt_bluedroid: get_profile_interface sdp
,11-15 13:55:37.747  5972  5988 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 13:55:37.747  5972  5983 I bt_bluedroid: config_hci_snoop_log
,11-15 13:55:37.748   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-15 13:55:37.753  5972  5984 D BluetoothAdapterState: Current state: OFF, message: 0
,11-15 13:55:37.753  5972  5984 D BluetoothAdapterProperties: Setting state to 14
11-15 13:55:37.753  5972  5984 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-15 13:55:37.754  5972  5984 D BluetoothBondStateMachine: make
,11-15 13:55:37.756  5972  5989 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-15 13:55:37.760  5972  5984 I BluetoothAdapterState: Entering PendingCommandState
,11-15 13:55:37.761  5972  5972 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-15 13:55:37.763  5972  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:37.763  5972  5972 D BtGatt.DebugUtils: handleDebugAction() action=null
11-15 13:55:37.764  5972  5972 D BtGatt.GattService: Received start request. Starting profile...
,11-15 13:55:37.764  5972  5972 D BtGatt.GattService: start()
11-15 13:55:37.764  5972  5972 I bt_bluedroid: get_profile_interface gatt
,11-15 13:55:37.765  5972  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
,11-15 13:55:37.765  5972  5972 D BtGatt.AdvertiseManager: advertise manager created
,11-15 13:55:37.770  5972  5972 V BluetoothAdapterState: isTurningOff()=false
,11-15 13:55:37.770  5972  5972 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:37.770  5972  5972 V BluetoothAdapterState: isBleTurningOn()=true
11-15 13:55:37.770  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:37.770  5972  5984 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-15 13:55:37.772  5972  5984 I bt_bluedroid: bt_bluedroid
,11-15 13:55:37.772  5972  5985 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-15 13:55:37.772  5972  5985 I bt_hci  : start_up
,11-15 13:55:37.777  5972  5985 I bt_vendor: alloc value 0xf428d871
11-15 13:55:37.778  5972  5985 I bt_vendor: init
,11-15 13:55:37.778  5972  5985 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-15 13:55:37.778  5972  5985 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-15 13:55:37.889  5972  5985 D bt_hci  : start_up starting async portion
11-15 13:55:37.889  5972  5992 I bt_hci  : event_finish_startup
11-15 13:55:37.889  5972  5992 I bt_hci_h4: hal_open
11-15 13:55:37.890  5972  5992 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-15 13:55:37.892  5972  5992 I bt_userial_vendor: device fd = 54 open
,11-15 13:55:37.886  5993  5993 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 13:55:37.906  5972  5992 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 13:55:37.909  5972  5992 D bt_hwcfg: Chipset BCM4358A3
,11-15 13:55:37.909  5972  5992 D bt_hwcfg: Target name = [BCM4358A3]
11-15 13:55:37.910  5972  5992 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-15 13:55:38.309  5972  5992 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-15 13:55:38.310  5972  5992 D bt_hwcfg: Settlement delay -- 100 ms
11-15 13:55:38.310  5972  5992 I bt_hwcfg: Setting fw settlement delay to 100 
,11-15 13:55:38.444  5972  5992 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 13:55:38.445  5972  5992 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-15 13:55:38.446  5972  5992 I bt_hwcfg: vendor lib fwcfg completed
,11-15 13:55:38.446  5972  5992 I bt_vendor: firmware callback
,11-15 13:55:38.446  5972  5992 I bt_hci  : firmware_config_callback
,11-15 13:55:38.455  5972  5995 I bt_btu  : btu_task pending for preload complete event
11-15 13:55:38.455  5972  5995 I bt_btu_task: Bluetooth chip preload is complete
,11-15 13:55:38.455  5972  5995 I bt_btu  : btu_task received preload complete event
,11-15 13:55:38.461  5972  5995 I         : BTE_InitTraceLevels -- TRC_HCI
,11-15 13:55:38.461  5972  5995 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-15 13:55:38.461  5972  5995 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-15 13:55:38.461  5972  5995 I         : BTE_InitTraceLevels -- TRC_AVDT
11-15 13:55:38.461  5972  5995 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-15 13:55:38.461  5972  5995 I         : BTE_InitTraceLevels -- TRC_A2D
11-15 13:55:38.462  5972  5995 I         : BTE_InitTraceLevels -- TRC_BNEP
11-15 13:55:38.462  5972  5995 I         : BTE_InitTraceLevels -- TRC_BTM
11-15 13:55:38.462  5972  5995 I         : BTE_InitTraceLevels -- TRC_GAP
,11-15 13:55:38.462  5972  5995 I         : BTE_InitTraceLevels -- TRC_PAN
11-15 13:55:38.462  5972  5995 I         : BTE_InitTraceLevels -- TRC_SDP
11-15 13:55:38.462  5972  5995 I         : BTE_InitTraceLevels -- TRC_GATT
,11-15 13:55:38.462  5972  5995 I         : BTE_InitTraceLevels -- TRC_SMP
11-15 13:55:38.462  5972  5995 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-15 13:55:38.463  5972  5995 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-15 13:55:38.544  5972  5995 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf420b549
11-15 13:55:38.544  5972  5995 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf420b549 
,11-15 13:55:38.568  5972  5988 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-15 13:55:38.569  5972  5988 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-15 13:55:38.570  5972  5988 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-15 13:55:38.572  5972  5988 D BluetoothAdapterProperties: Name is: Nexus 6P
11-15 13:55:38.574  5972  5988 D BluetoothAdapterProperties: Scan Mode:20
11-15 13:55:38.574  5972  5988 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 13:55:38.574  5972  5988 D bt_hci  : do_postload posting postload work item
11-15 13:55:38.575  5972  5992 I bt_hci  : event_postload
11-15 13:55:38.575  5972  5992 I bt_vendor: sco_config_cb
,11-15 13:55:38.575  5972  5992 I bt_hci  : sco_config_callback postload finished.
11-15 13:55:38.578  5972  5988 D bt_bte_conf: Device ID record 1 : primary
11-15 13:55:38.578  5972  5988 D bt_bte_conf:   vendorId            = 000f
11-15 13:55:38.578  5972  5988 D bt_bte_conf:   vendorIdSource      = 0001
11-15 13:55:38.578  5972  5988 D bt_bte_conf:   product             = 1200
11-15 13:55:38.579  5972  5988 D bt_bte_conf:   version             = 1436
,11-15 13:55:38.579  5972  5988 D bt_bte_conf:   clientExecutableURL = 
11-15 13:55:38.579  5972  5988 D bt_bte_conf:   serviceDescription  = 
11-15 13:55:38.579  5972  5988 D bt_bte_conf:   documentationURL    = 
11-15 13:55:38.579  5972  5988 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-15 13:55:38.579  5972  5985 D bt_stack_manager: event_start_up_stack finished
,11-15 13:55:38.581  5972  5984 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-15 13:55:38.581  5972  5984 D BluetoothAdapterProperties: Setting state to 15
11-15 13:55:38.581  5972  5984 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-15 13:55:38.581  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 13:55:38.583  5972  5984 I BluetoothAdapterState: Entering BleOnState
,11-15 13:55:38.588  5972  5984 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-15 13:55:38.588  5972  5984 D BluetoothAdapterProperties: Setting state to 11
11-15 13:55:38.588  5972  5984 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-15 13:55:38.589  5972  5992 I bt_vendor: low_power_mode_cb
,11-15 13:55:38.593  5972  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:38.594  5972  5972 D HeadsetService: Received start request. Starting profile...
11-15 13:55:38.596  5972  5972 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-15 13:55:38.597  5972  5972 D HeadsetStateMachine: make
11-15 13:55:38.600  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:55:38.611  5972  5984 I BluetoothAdapterState: Entering PendingCommandState
,11-15 13:55:38.611  5972  5972 D HeadsetStateMachine: max_hf_connections = 1
11-15 13:55:38.611  5972  5972 I bt_bluedroid: get_profile_interface handsfree
,11-15 13:55:38.612  5972  5988 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-15 13:55:38.615  5972  5988 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-15 13:55:38.616  5972  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
,11-15 13:55:38.617  5972  5972 D A2dpService: Received start request. Starting profile...
11-15 13:55:38.617  5972  5972 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-15 13:55:38.618  5972  5972 I bt_bluedroid: get_profile_interface avrcp
,11-15 13:55:38.623  5972  5972 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-15 13:55:38.624  5972  5972 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-15 13:55:38.624  5972  5972 D A2dpStateMachine: make
11-15 13:55:38.625  5972  5972 I bt_bluedroid: get_profile_interface a2dp
,11-15 13:55:38.625  5972  5988 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-15 13:55:38.627  5972  6003 D A2dpStateMachine: Enter Disconnected: -2
11-15 13:55:38.627  5972  5972 I BluetoothHidServiceJni: classInitNative: succeeds
11-15 13:55:38.628  5972  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
,11-15 13:55:38.629  5842  5842 D BluetoothInputDevice: Proxy object connected
,11-15 13:55:38.632  5972  5972 D HidService: Received start request. Starting profile...
11-15 13:55:38.632  5972  5972 I bt_bluedroid: get_profile_interface hidhost
11-15 13:55:38.633  5972  5972 D HidService: setHidService(): set to: null
11-15 13:55:38.633  5972  5988 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41ec56d
11-15 13:55:38.633  5972  5988 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-15 13:55:38.633  5972  5972 I BluetoothHealthServiceJni: classInitNative: succeeds
11-15 13:55:38.634  5972  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:38.634  5972  5972 D HealthService: Received start request. Starting profile...
11-15 13:55:38.635  5842  5842 D HidProfile: Bluetooth service connected
11-15 13:55:38.635  5972  5972 I bt_bluedroid: get_profile_interface health
,11-15 13:55:38.637  5972  5972 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-15 13:55:38.638  5972  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:38.638  3697  3697 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 13:55:38.640  5972  5972 D PanService: Received start request. Starting profile...
11-15 13:55:38.640  5972  5972 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-15 13:55:38.640  5972  5972 I bt_bluedroid: get_profile_interface pan
11-15 13:55:38.640  5972  5988 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-15 13:55:38.641  5842  5842 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 13:55:38.641  5842  5842 D PanProfile: Bluetooth service connected
11-15 13:55:38.643  5972  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
,11-15 13:55:38.645  5972  5972 D BluetoothMapService: Received start request. Starting profile...
,11-15 13:55:38.645  5972  5972 D BluetoothMapService: start()
11-15 13:55:38.647  5972  5972 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-15 13:55:38.648  5842  5842 D BluetoothMap: Proxy object connected
11-15 13:55:38.649  5972  5972 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-15 13:55:38.649  5972  5972 D BluetoothMapAppObserver: createReceiver()
11-15 13:55:38.650  5972  5972 D BluetoothMapAppObserver: initObservers()
11-15 13:55:38.650  5972  5972 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-15 13:55:38.656  5972  5972 V SapService: SapBinder()
,11-15 13:55:38.656  5972  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:38.656  5972  5972 D SapService: Received start request. Starting profile...
11-15 13:55:38.657  5972  5972 V SapService: start()
11-15 13:55:38.658  5972  5972 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:38.658  5972  5972 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:38.658  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:38.658  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:38.658  5972  5972 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:38.658  5972  5972 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:38.658  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:38.658  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:38.658  5972  5972 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:38.658  5972  6000 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-15 13:55:38.658  5972  5972 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:38.659  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:38.659  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:38.659  5972  5972 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:38.659  5972  5972 V BluetoothAdapterState: isTurningOn()=true
,11-15 13:55:38.659  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:38.659  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:38.659  5972  5972 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:38.659  5972  5972 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:38.659  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 13:55:38.659  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:38.660  5972  5972 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:38.660  5972  5972 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:38.660  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:38.660  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:38.661  5972  5972 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:38.661  5972  5972 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:38.661  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:38.661  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:38.661  5972  5984 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-15 13:55:38.661  5972  5984 D BluetoothAdapterProperties: ScanMode =  20
,11-15 13:55:38.661  5972  5984 D BluetoothAdapterProperties: State =  11
11-15 13:55:38.662  5972  5984 D BluetoothAdapterProperties: Setting state to 12
11-15 13:55:38.662  5972  5984 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-15 13:55:38.662  5972  5984 I BluetoothAdapterState: Entering OnState
11-15 13:55:38.663  5842  5842 D MapProfile: Bluetooth service connected
11-15 13:55:38.663  5842  5842 D BluetoothMap: getConnectedDevices()
11-15 13:55:38.663   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 13:55:38.663  5972  5988 D BluetoothAdapterProperties: Scan Mode:21
11-15 13:55:38.663   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 13:55:38.663  5972  5988 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-15 13:55:38.664  5842  5854 D BluetoothPbap: onBluetoothStateChange: up=true
,11-15 13:55:38.664  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-15 13:55:38.665  5842  5856 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-15 13:55:38.666  3218  3230 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 13:55:38.667  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:55:38.667  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:38.667  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:38.667  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 13:55:38.667  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 13:55:38.667  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 13:55:38.667  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 13:55:38.667  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 13:55:38.667  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 13:55:38.668  3218  3232 D BluetoothMap: onBluetoothStateChange: up=true
,11-15 13:55:38.670  5784  5784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 13:55:38.670  3218  3218 D BluetoothA2dp: Proxy object connected
11-15 13:55:38.670  3218  3232 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 13:55:38.671  3218  4038 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 13:55:38.672  3218  3218 D BluetoothMap: Proxy object connected
11-15 13:55:38.672  3218  3218 D MapProfile: Bluetooth service connected
11-15 13:55:38.672  3218  3218 D BluetoothMap: getConnectedDevices()
11-15 13:55:38.673   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 13:55:38.673   928   928 D BluetoothA2dp: Proxy object connected
11-15 13:55:38.673  3218  3218 D BluetoothInputDevice: Proxy object connected
11-15 13:55:38.673  3218  4038 D BluetoothPan: onBluetoothStateChange on: true
11-15 13:55:38.673  3218  3218 D HidProfile: Bluetooth service connected
11-15 13:55:38.675  5972  5972 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 13:55:38.675  5972  5972 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-15 13:55:38.677   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-15 13:55:38.677  3218  3218 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 13:55:38.677  3218  3218 D PanProfile: Bluetooth service connected
11-15 13:55:38.677  5842  5854 D BluetoothPan: onBluetoothStateChange on: true
,11-15 13:55:38.678  3892  3911 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 13:55:38.678  5972  5972 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 13:55:38.678  3218  3230 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-15 13:55:38.679  5842  5856 D BluetoothMap: onBluetoothStateChange: up=true
,11-15 13:55:38.680  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-15 13:55:38.681   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-15 13:55:38.681  5972  5972 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 13:55:38.682  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 13:55:38.682  5842  5842 D LocalBluetoothProfileManager: Adding local A2DP profile
11-15 13:55:38.683  5972  5972 D ObexServerSockets: Succeed to create listening sockets 
11-15 13:55:38.683  5972  5972 D ObexServerSockets0: startAccept()
11-15 13:55:38.683  5972  5972 D ObexServerSockets0: prepareForNewConnect()
,11-15 13:55:38.686  5842  5842 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-15 13:55:38.686  5972  5972 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-15 13:55:38.686  5972  5972 D BluetoothSdpJni: SDP Create record success - handle: 0
11-15 13:55:38.686  5972  6010 D ObexServerSockets0: Accepting socket connection...
11-15 13:55:38.686  5972  5972 D BluetoothMapService: onReceive
,11-15 13:55:38.686  5972  5972 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 13:55:38.686  5972  5972 D BluetoothMapService: STATE_ON
11-15 13:55:38.687  5972  6011 D ObexServerSockets0: Accepting socket connection...
,11-15 13:55:38.690  5972  6012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 13:55:38.691  5972  6012 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-15 13:55:38.691  5842  5842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 13:55:38.691  5972  6012 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-15 13:55:38.693  5842  5842 D BluetoothA2dp: Proxy object connected
,11-15 13:55:38.698  3697  3697 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 13:55:38.706  3218  3218 D BluetoothPbap: Proxy object connected
,11-15 13:55:38.706  3218  3218 D PbapServerProfile: Bluetooth service connected
,11-15 13:55:38.712  5972  5972 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 13:55:38.712  5972  5972 D ObexServerSockets0: prepareForNewConnect()
,11-15 13:55:38.715  5842  5842 D DockEventReceiver: finishStartingService: stopping service
,11-15 13:55:38.715  5842  5842 D BluetoothPbap: Proxy object connected
11-15 13:55:38.716  5972  6016 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 13:55:38.716  5842  5842 D PbapServerProfile: Bluetooth service connected
,11-15 13:55:38.728  5972  6020 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 13:55:38.729  5972  6020 I BtOppRfcommListener: Accept thread started.
,11-15 13:55:38.764   928   928 D BluetoothHeadset: Proxy object connected
,11-15 13:55:38.764  3892  4122 D BluetoothHeadset: Proxy object connected
11-15 13:55:38.765  3218  3232 D BluetoothHeadset: Proxy object connected
11-15 13:55:38.765  3218  3218 D HeadsetProfile: Bluetooth service connected
,11-15 13:55:38.765   928   928 D BluetoothHeadset: Proxy object connected
11-15 13:55:38.765   928   928 D BluetoothHeadset: Proxy object connected
,11-15 13:55:38.776   928   945 D BluetoothHeadset: Proxy object connected
,11-15 13:55:38.778  3892  3909 D BluetoothHeadset: Proxy object connected
,11-15 13:55:38.779  3218  3230 D BluetoothHeadset: Proxy object connected
,11-15 13:55:38.780  3218  3218 D HeadsetProfile: Bluetooth service connected
,11-15 13:55:38.789  5842  5854 D BluetoothHeadset: Proxy object connected
,11-15 13:55:38.791  5842  5842 D HeadsetProfile: Bluetooth service connected
,11-15 13:55:38.861  3800  5590 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-15 13:55:38.861  3800  5590 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-15 13:55:38.873  3697  3697 I ConfigService: onCreate
,11-15 13:55:39.555   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:40.342   928  3129 D ConnectivityService: handlePromptUnvalidated 101
,11-15 13:55:40.556   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:41.557   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:42.558   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:42.598  5972  5984 D BluetoothAdapterState: Current state: ON, message: 23
,11-15 13:55:42.598  5972  5984 D BluetoothAdapterProperties: Setting state to 13
,11-15 13:55:42.598  5972  5984 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-15 13:55:42.599  5972  5984 D BluetoothAdapterProperties: onBluetoothDisable()
11-15 13:55:42.602  5972  5984 I BluetoothAdapterState: Entering PendingCommandState
11-15 13:55:42.605  5972  5972 D BluetoothMapService: onReceive
11-15 13:55:42.610  5972  5972 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-15 13:55:42.609  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:42.611  5972  5972 D BluetoothMapService: STATE_TURNING_OFF
11-15 13:55:42.611  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:55:42.611  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:42.611  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:42.611  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 13:55:42.611  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 13:55:42.611  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 13:55:42.611  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 13:55:42.611  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 13:55:42.611  5784  5784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 13:55:42.611  5972  5972 D BluetoothMapService: MAP Service closeService in
11-15 13:55:42.611  5842  5842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 13:55:42.611  5972  5972 D BluetoothMapMasInstance0: MAP Service shutdown
11-15 13:55:42.612  5972  5972 D ObexServerSockets0: shutdown(block = true)
11-15 13:55:42.613  5972  5972 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 13:55:42.614  5972  6010 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-15 13:55:42.614  5972  5972 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 13:55:42.614  5972  6011 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-15 13:55:42.614  5972  5997 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-15 13:55:42.610  5972  5988 D BluetoothAdapterProperties: Scan Mode:20
11-15 13:55:42.615  5784  5784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 13:55:42.615  5784  5784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-15 13:55:42.615  5972  5984 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-15 13:55:42.621  5972  5972 I BtOppRfcommListener: stopping Accept Thread
,11-15 13:55:42.621  5972  6020 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-15 13:55:42.622  5972  6020 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-15 13:55:42.625  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 13:55:42.626  5972  5972 D HeadsetService: Received stop request...Stopping profile...
11-15 13:55:42.629  5842  5854 D BluetoothHeadset: Proxy object disconnected
11-15 13:55:42.629   928   928 D BluetoothHeadset: Proxy object disconnected
,11-15 13:55:42.631  3892  4092 D BluetoothHeadset: Proxy object disconnected
,11-15 13:55:42.632  5972  5972 D A2dpService: Received stop request...Stopping profile...
11-15 13:55:42.633  3697  3697 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 13:55:42.633  5972  6003 D A2dpStateMachine: Exit Disconnected: -1
11-15 13:55:42.633  3218  3232 D BluetoothHeadset: Proxy object disconnected
11-15 13:55:42.634   928   928 D BluetoothHeadset: Proxy object disconnected
11-15 13:55:42.634   928   928 D BluetoothHeadset: Proxy object disconnected
,11-15 13:55:42.636  3218  3218 D HeadsetProfile: Bluetooth service disconnected
11-15 13:55:42.636   928   928 D BluetoothA2dp: Proxy object disconnected
,11-15 13:55:42.636  5842  5842 D DockEventReceiver: finishStartingService: stopping service
,11-15 13:55:42.638  5842  5842 D HeadsetProfile: Bluetooth service disconnected
11-15 13:55:42.638  5842  5842 D BluetoothA2dp: Proxy object disconnected
,11-15 13:55:42.640  5972  5972 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:42.640  5972  5972 V BluetoothAdapterState: isTurningOn()=false
,11-15 13:55:42.640  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:42.640  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:42.641  5972  5972 D HidService: Received stop request...Stopping profile...
11-15 13:55:42.641  5972  5972 D HidService: Stopping Bluetooth HidService
,11-15 13:55:42.644  5972  5972 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-15 13:55:42.644  5972  5972 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-15 13:55:42.644  5972  5995 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:42.644  5972  5995 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:42.645  5972  5995 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:42.645  5972  5988 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-15 13:55:42.645  5972  5988 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-15 13:55:42.645  5972  5972 D HealthService: Received stop request...Stopping profile...
11-15 13:55:42.653  5842  5842 D BluetoothInputDevice: Proxy object disconnected
11-15 13:55:42.653  5842  5842 D HidProfile: Bluetooth service disconnected
11-15 13:55:42.654  3218  3218 D BluetoothA2dp: Proxy object disconnected
11-15 13:55:42.654  3218  3218 D BluetoothInputDevice: Proxy object disconnected
11-15 13:55:42.654  3218  3218 D HidProfile: Bluetooth service disconnected
,11-15 13:55:42.655  5972  5972 D PanService: Received stop request...Stopping profile...
11-15 13:55:42.655  3218  3218 D BluetoothPbap: Proxy object disconnected
11-15 13:55:42.655  3218  3218 D PbapServerProfile: Bluetooth service disconnected
11-15 13:55:42.656  3218  3218 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-15 13:55:42.656  3218  3218 D PanProfile: Bluetooth service disconnected
11-15 13:55:42.657  5972  5972 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:42.657  5972  5972 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:42.657  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 13:55:42.657  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:42.658  5972  5972 D BluetoothMapService: Received stop request...Stopping profile...
11-15 13:55:42.658  5972  5972 D BluetoothMapService: stop()
,11-15 13:55:42.659  5972  5972 D BluetoothMapAppObserver: deinitObservers()
,11-15 13:55:42.659  5972  5972 D BluetoothMapAppObserver: removeReceiver()
11-15 13:55:42.660  3218  3218 D BluetoothMap: Proxy object disconnected
11-15 13:55:42.660  3218  3218 D MapProfile: Bluetooth service disconnected
,11-15 13:55:42.661  5972  5972 D SapService: Received stop request...Stopping profile...
11-15 13:55:42.661  5972  5972 V SapService: stop()
11-15 13:55:42.661  5842  5842 D BluetoothPbap: Proxy object disconnected
11-15 13:55:42.661  5842  5842 D PbapServerProfile: Bluetooth service disconnected
11-15 13:55:42.661  5842  5842 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 13:55:42.661  5842  5842 D PanProfile: Bluetooth service disconnected
11-15 13:55:42.661  5842  5842 D BluetoothMap: Proxy object disconnected
11-15 13:55:42.661  5842  5842 D MapProfile: Bluetooth service disconnected
11-15 13:55:42.663  5972  5988 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-15 13:55:42.663  5972  5995 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:42.663  5972  5995 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:42.663  5972  5972 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:42.663  5972  5972 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:42.663  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 13:55:42.663  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 13:55:42.664  5972  5995 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-15 13:55:42.664  5972  5995 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 13:55:42.664  5972  5972 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-15 13:55:42.664  5972  5972 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-15 13:55:42.664  5972  5988 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-15 13:55:42.664  5972  5972 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:42.664  5972  5972 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:42.664  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:42.664  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 13:55:42.664  5972  5972 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-15 13:55:42.665  5972  5995 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 13:55:42.665  5972  5995 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 13:55:42.665  5972  5972 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-15 13:55:42.665  5972  5972 V BluetoothAdapterState: isTurningOff()=true
,11-15 13:55:42.665  5972  5972 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:42.665  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:42.665  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:42.666  5972  5988 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-15 13:55:42.666  5972  5972 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-15 13:55:42.666  5972  5972 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-15 13:55:42.667  5972  5972 D BluetoothMapService: MAP Service closeService in
11-15 13:55:42.667  5972  5972 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:42.667  5972  5972 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:42.668  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:42.668  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 13:55:42.668  5972  5972 D BluetoothMapService: cleanup()
11-15 13:55:42.668  5972  5972 D BluetoothMapService: MAP Service closeService in
11-15 13:55:42.668  5972  5972 V BluetoothAdapterState: isTurningOff()=true
11-15 13:55:42.668  5972  5972 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:42.668  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 13:55:42.668  5972  5972 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:42.669  5972  5984 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-15 13:55:42.669  5972  5984 D BluetoothAdapterProperties: Setting state to 15
11-15 13:55:42.669  5972  5984 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-15 13:55:42.669  5972  5984 I BluetoothAdapterState: Entering BleOnState
11-15 13:55:42.669   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-15 13:55:42.669  5842  5856 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 13:55:42.670   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 13:55:42.670  5842  5854 D BluetoothPbap: onBluetoothStateChange: up=false
11-15 13:55:42.670  5842  5856 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 13:55:42.671  3218  4038 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-15 13:55:42.672  3218  3230 D BluetoothMap: onBluetoothStateChange: up=false
11-15 13:55:42.673  3218  3232 D BluetoothPbap: onBluetoothStateChange: up=false
11-15 13:55:42.673  3218  4038 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 13:55:42.674   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 13:55:42.674  5842  5854 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 13:55:42.675  3218  3230 D BluetoothPan: onBluetoothStateChange on: false
,11-15 13:55:42.675   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 13:55:42.675  5842  5856 D BluetoothPan: onBluetoothStateChange on: false
11-15 13:55:42.676  3892  3911 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 13:55:42.676  3218  3232 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 13:55:42.676  5842  5854 D BluetoothMap: onBluetoothStateChange: up=false
11-15 13:55:42.677  5972  5984 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-15 13:55:42.677  5972  5984 D BluetoothAdapterProperties: Setting state to 16
11-15 13:55:42.677  5972  5984 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-15 13:55:42.678  5972  5984 D BluetoothAdapterProperties: onBleDisable
11-15 13:55:42.678  5972  5984 I BluetoothAdapterState: Entering PendingCommandState
11-15 13:55:42.678  5972  5985 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-15 13:55:42.679  5972  5995 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-15 13:55:42.679  5972  5995 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 13:55:42.680  5972  5988 D BluetoothAdapterProperties: Scan Mode:20
11-15 13:55:42.680  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 13:55:42.682  5784  5784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 13:55:42.683  5842  5842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 13:55:42.687  3697  3697 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 13:55:42.694  5842  5842 D DockEventReceiver: finishStartingService: stopping service
,11-15 13:55:42.892  5972  5988 I bt_hci  : shut_down
,11-15 13:55:42.903  5972  5992 D bt_hwcfg: hw_epilog_process
,11-15 13:55:42.903  5972  5992 I bt_vendor: low_power_mode_cb
,11-15 13:55:42.906  5972  5992 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-15 13:55:42.907  5972  5992 I bt_vendor: epilog_cb
,11-15 13:55:42.907  5972  5992 I bt_hci  : epilog_finished_callback
,11-15 13:55:42.913  5972  5988 I bt_hci_h4: hal_close
,11-15 13:55:42.914  5972  5988 I bt_userial_vendor: device fd = 54 close
,11-15 13:55:43.026  5972  5985 D bt_stack_manager: event_shut_down_stack finished.
,11-15 13:55:43.027  5972  5984 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-15 13:55:43.031  5972  5984 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-15 13:55:43.031  5972  5972 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-15 13:55:43.033  5972  5972 D BtGatt.GattService: Received stop request...Stopping profile...
,11-15 13:55:43.033  5972  5972 D BtGatt.GattService: stop()
,11-15 13:55:43.033  5972  5972 D BtGatt.AdvertiseManager: advertise clients cleared
,11-15 13:55:43.037  5972  5972 V BluetoothAdapterState: isTurningOff()=false
,11-15 13:55:43.037  5972  5972 V BluetoothAdapterState: isTurningOn()=false
,11-15 13:55:43.038  5972  5972 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:43.038  5972  5972 V BluetoothAdapterState: isBleTurningOff()=true
,11-15 13:55:43.038  5972  5984 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-15 13:55:43.039  5972  5984 D BluetoothAdapterProperties: Setting state to 10
11-15 13:55:43.039  5972  5984 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-15 13:55:43.040  5972  5984 I BluetoothAdapterState: Entering OffState
,11-15 13:55:43.043   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-15 13:55:43.060  5972  5972 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-15 13:55:43.061  5972  5972 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-15 13:55:43.061  5972  5985 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-15 13:55:43.063  5972  5972 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-15 13:55:43.069  5972  5972 I art     : System.exit called, status: 0
,11-15 13:55:43.069  5972  5972 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-15 13:55:43.106   928  3893 I ActivityManager: Process com.android.bluetooth (pid 5972) has died
,11-15 13:55:43.516   928  2871 I hubconnection: sensorhub said: 'set_bias 3: -4.5600, 0.0000, 0.0000'
,11-15 13:55:43.559   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:43.898  3697  3697 I ConfigService: onDestroy
,11-15 13:55:44.559   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 13:55:47.596  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 13:55:47.596  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-15 13:55:47.602  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 13:55:47.602  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa7a693 removed from the list
11-15 13:55:47.602  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 13:55:47.604  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 13:55:47.605  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a7e1ce added. We now have 4 listener(s)
11-15 13:55:47.605  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 13:55:47.608  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 13:55:47.609  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a7e1ce removed from the list
11-15 13:55:47.609  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 13:55:47.611  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 13:55:47.611  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@89c18ef added. We now have 4 listener(s)
,11-15 13:55:47.611  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 13:55:49.560   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:50.562   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:51.563   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:52.565   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:52.622  5784  5831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:55:52.653   928   945 I ActivityManager: Start proc 6029:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-15 13:55:52.740  6029  6029 D AdapterServiceConfig: Adding HeadsetService
,11-15 13:55:52.740  6029  6029 D AdapterServiceConfig: Adding A2dpService
11-15 13:55:52.740  6029  6029 D AdapterServiceConfig: Adding HidService
11-15 13:55:52.740  6029  6029 D AdapterServiceConfig: Adding HealthService
11-15 13:55:52.740  6029  6029 D AdapterServiceConfig: Adding PanService
11-15 13:55:52.741  6029  6029 D AdapterServiceConfig: Adding GattService
11-15 13:55:52.741  6029  6029 D AdapterServiceConfig: Adding BluetoothMapService
11-15 13:55:52.741  6029  6029 D AdapterServiceConfig: Adding SapService
,11-15 13:55:52.752   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79af680:true
,11-15 13:55:52.752  6029  6029 D BluetoothAdapterState: make() - Creating AdapterState
,11-15 13:55:52.755  6029  6029 I bt_bluedroid: init
11-15 13:55:52.755  6029  6041 I BluetoothAdapterState: Entering OffState
,11-15 13:55:52.758  6029  6042 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-15 13:55:52.758  6029  6042 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-15 13:55:52.758  6029  6042 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-15 13:55:52.758  6029  6042 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-15 13:55:52.759  6029  6029 I bt_bluedroid: get_profile_interface socket
,11-15 13:55:52.761  6029  6045 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-15 13:55:52.761  6029  6029 I bt_bluedroid: get_profile_interface sdp
11-15 13:55:52.762  6029  6045 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 13:55:52.766  6029  6040 I bt_bluedroid: config_hci_snoop_log
,11-15 13:55:52.767   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-15 13:55:52.771  6029  6041 D BluetoothAdapterState: Current state: OFF, message: 0
11-15 13:55:52.771  6029  6041 D BluetoothAdapterProperties: Setting state to 14
11-15 13:55:52.771  6029  6041 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-15 13:55:52.773  6029  6041 D BluetoothBondStateMachine: make
,11-15 13:55:52.775  6029  6046 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-15 13:55:52.777  6029  6041 I BluetoothAdapterState: Entering PendingCommandState
,11-15 13:55:52.778  6029  6029 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-15 13:55:52.781  6029  6029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:52.781  6029  6029 D BtGatt.DebugUtils: handleDebugAction() action=null
11-15 13:55:52.782  6029  6029 D BtGatt.GattService: Received start request. Starting profile...
11-15 13:55:52.782  6029  6029 D BtGatt.GattService: start()
11-15 13:55:52.782  6029  6029 I bt_bluedroid: get_profile_interface gatt
,11-15 13:55:52.783  6029  6029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:52.783  6029  6029 D BtGatt.AdvertiseManager: advertise manager created
,11-15 13:55:52.789  6029  6029 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:52.789  6029  6029 V BluetoothAdapterState: isTurningOn()=false
11-15 13:55:52.789  6029  6029 V BluetoothAdapterState: isBleTurningOn()=true
11-15 13:55:52.789  6029  6029 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:52.789  6029  6041 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-15 13:55:52.790  6029  6041 I bt_bluedroid: bt_bluedroid
,11-15 13:55:52.791  6029  6042 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-15 13:55:52.791  6029  6042 I bt_hci  : start_up
,11-15 13:55:52.797  6029  6042 I bt_vendor: alloc value 0xf428d871
11-15 13:55:52.797  6029  6042 I bt_vendor: init
,11-15 13:55:52.797  6029  6042 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,11-15 13:55:52.808  6029  6042 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-15 13:55:52.919  6029  6042 D bt_hci  : start_up starting async portion
11-15 13:55:52.920  6029  6049 I bt_hci  : event_finish_startup
11-15 13:55:52.920  6029  6049 I bt_hci_h4: hal_open
11-15 13:55:52.920  6029  6049 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-15 13:55:52.923  6029  6049 I bt_userial_vendor: device fd = 54 open
,11-15 13:55:52.916  6050  6050 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 13:55:52.939  6029  6049 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 13:55:52.943  6029  6049 D bt_hwcfg: Chipset BCM4358A3
,11-15 13:55:52.943  6029  6049 D bt_hwcfg: Target name = [BCM4358A3]
11-15 13:55:52.944  6029  6049 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-15 13:55:53.445  6029  6049 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-15 13:55:53.445  6029  6049 D bt_hwcfg: Settlement delay -- 100 ms
11-15 13:55:53.446  6029  6049 I bt_hwcfg: Setting fw settlement delay to 100 
,11-15 13:55:53.566   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:55:53.580  6029  6049 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 13:55:53.580  6029  6049 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-15 13:55:53.582  6029  6049 I bt_hwcfg: vendor lib fwcfg completed
11-15 13:55:53.582  6029  6049 I bt_vendor: firmware callback
11-15 13:55:53.582  6029  6049 I bt_hci  : firmware_config_callback
,11-15 13:55:53.591  6029  6052 I bt_btu  : btu_task pending for preload complete event
,11-15 13:55:53.592  6029  6052 I bt_btu_task: Bluetooth chip preload is complete
11-15 13:55:53.592  6029  6052 I bt_btu  : btu_task received preload complete event
,11-15 13:55:53.600  6029  6052 I         : BTE_InitTraceLevels -- TRC_HCI
,11-15 13:55:53.600  6029  6052 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-15 13:55:53.600  6029  6052 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-15 13:55:53.600  6029  6052 I         : BTE_InitTraceLevels -- TRC_AVDT
11-15 13:55:53.601  6029  6052 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-15 13:55:53.601  6029  6052 I         : BTE_InitTraceLevels -- TRC_A2D
11-15 13:55:53.601  6029  6052 I         : BTE_InitTraceLevels -- TRC_BNEP
11-15 13:55:53.601  6029  6052 I         : BTE_InitTraceLevels -- TRC_BTM
11-15 13:55:53.601  6029  6052 I         : BTE_InitTraceLevels -- TRC_GAP
11-15 13:55:53.601  6029  6052 I         : BTE_InitTraceLevels -- TRC_PAN
11-15 13:55:53.601  6029  6052 I         : BTE_InitTraceLevels -- TRC_SDP
11-15 13:55:53.601  6029  6052 I         : BTE_InitTraceLevels -- TRC_GATT
,11-15 13:55:53.601  6029  6052 I         : BTE_InitTraceLevels -- TRC_SMP
11-15 13:55:53.602  6029  6052 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-15 13:55:53.602  6029  6052 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-15 13:55:53.698  6029  6052 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf420b549
,11-15 13:55:53.698  6029  6052 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf420b549 
,11-15 13:55:53.718  6029  6045 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-15 13:55:53.720  6029  6045 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-15 13:55:53.720  6029  6045 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 13:55:53.723  6029  6045 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 13:55:53.726  6029  6045 D BluetoothAdapterProperties: Scan Mode:20
,11-15 13:55:53.726  6029  6045 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-15 13:55:53.726  6029  6045 D bt_hci  : do_postload posting postload work item
11-15 13:55:53.726  6029  6049 I bt_hci  : event_postload
11-15 13:55:53.727  6029  6049 I bt_vendor: sco_config_cb
11-15 13:55:53.727  6029  6049 I bt_hci  : sco_config_callback postload finished.
11-15 13:55:53.730  6029  6045 D bt_bte_conf: Device ID record 1 : primary
11-15 13:55:53.731  6029  6045 D bt_bte_conf:   vendorId            = 000f
11-15 13:55:53.731  6029  6045 D bt_bte_conf:   vendorIdSource      = 0001
11-15 13:55:53.731  6029  6045 D bt_bte_conf:   product             = 1200
11-15 13:55:53.731  6029  6045 D bt_bte_conf:   version             = 1436
11-15 13:55:53.731  6029  6045 D bt_bte_conf:   clientExecutableURL = 
11-15 13:55:53.731  6029  6045 D bt_bte_conf:   serviceDescription  = 
11-15 13:55:53.731  6029  6045 D bt_bte_conf:   documentationURL    = 
11-15 13:55:53.731  6029  6045 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-15 13:55:53.731  6029  6042 D bt_stack_manager: event_start_up_stack finished
11-15 13:55:53.732  6029  6041 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-15 13:55:53.733  6029  6041 D BluetoothAdapterProperties: Setting state to 15
11-15 13:55:53.733  6029  6041 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-15 13:55:53.736  6029  6049 I bt_vendor: low_power_mode_cb
,11-15 13:55:53.737  6029  6041 I BluetoothAdapterState: Entering BleOnState
11-15 13:55:53.741  6029  6041 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-15 13:55:53.741  6029  6041 D BluetoothAdapterProperties: Setting state to 11
11-15 13:55:53.741  6029  6041 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-15 13:55:53.756  6029  6029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:53.757  6029  6029 D HeadsetService: Received start request. Starting profile...
11-15 13:55:53.759  6029  6029 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-15 13:55:53.760  6029  6029 D HeadsetStateMachine: make
,11-15 13:55:53.770  6029  6041 I BluetoothAdapterState: Entering PendingCommandState
,11-15 13:55:53.779  6029  6029 D HeadsetStateMachine: max_hf_connections = 1
,11-15 13:55:53.779  6029  6029 I bt_bluedroid: get_profile_interface handsfree
11-15 13:55:53.780  6029  6045 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-15 13:55:53.780  6029  6045 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-15 13:55:53.785  6029  6029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:53.786  6029  6029 D A2dpService: Received start request. Starting profile...
11-15 13:55:53.787  6029  6029 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-15 13:55:53.787  6029  6029 I bt_bluedroid: get_profile_interface avrcp
,11-15 13:55:53.787  3697  3697 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 13:55:53.794  6029  6029 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-15 13:55:53.795  6029  6029 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-15 13:55:53.795  6029  6029 D A2dpStateMachine: make
,11-15 13:55:53.796  6029  6029 I bt_bluedroid: get_profile_interface a2dp
,11-15 13:55:53.797  6029  6045 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-15 13:55:53.798  6029  6059 D A2dpStateMachine: Enter Disconnected: -2
,11-15 13:55:53.799  6029  6029 I BluetoothHidServiceJni: classInitNative: succeeds
,11-15 13:55:53.799  6029  6029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
,11-15 13:55:53.800  6029  6029 D HidService: Received start request. Starting profile...
,11-15 13:55:53.800  6029  6029 I bt_bluedroid: get_profile_interface hidhost
11-15 13:55:53.801  6029  6029 D HidService: setHidService(): set to: null
11-15 13:55:53.801  6029  6045 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41ec56d
11-15 13:55:53.801  6029  6045 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-15 13:55:53.801  6029  6029 I BluetoothHealthServiceJni: classInitNative: succeeds
11-15 13:55:53.802  6029  6029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:53.803  6029  6029 D HealthService: Received start request. Starting profile...
11-15 13:55:53.804  6029  6029 I bt_bluedroid: get_profile_interface health
11-15 13:55:53.805  6029  6029 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-15 13:55:53.806  6029  6029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
,11-15 13:55:53.806  6029  6029 D PanService: Received start request. Starting profile...
11-15 13:55:53.807  6029  6029 D BluetoothPanServiceJni: initializeNative(L110): pan
11-15 13:55:53.807  6029  6029 I bt_bluedroid: get_profile_interface pan
11-15 13:55:53.809  6029  6045 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-15 13:55:53.809  6029  6029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
,11-15 13:55:53.810  6029  6029 D BluetoothMapService: Received start request. Starting profile...
,11-15 13:55:53.810  6029  6029 D BluetoothMapService: start()
11-15 13:55:53.813  6029  6029 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-15 13:55:53.814  6029  6029 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-15 13:55:53.814  6029  6029 D BluetoothMapAppObserver: createReceiver()
11-15 13:55:53.816  6029  6029 D BluetoothMapAppObserver: initObservers()
,11-15 13:55:53.816  6029  6029 D BluetoothMapAppObserver: getEnabledAccountItems()
11-15 13:55:53.821  6029  6029 V SapService: SapBinder()
11-15 13:55:53.821  6029  6029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:55:53.822  6029  6029 D SapService: Received start request. Starting profile...
11-15 13:55:53.822  6029  6029 V SapService: start()
,11-15 13:55:53.825  6029  6029 V BluetoothAdapterState: isTurningOff()=false
,11-15 13:55:53.825  6029  6029 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:53.825  6029  6029 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:53.825  6029  6029 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:53.825  6029  6057 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 13:55:53.826  6029  6029 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:53.827  6029  6029 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:53.827  6029  6029 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:53.827  6029  6029 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:53.827  6029  6029 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:53.828  6029  6029 V BluetoothAdapterState: isTurningOff()=false
11-15 13:55:53.828  6029  6029 V BluetoothAdapterState: isTurningOn()=true
11-15 13:55:53.828  6029  6029 V BluetoothAdapterState: isBleTurningOn()=false
11-15 13:55:53.828  6029  6029 V BluetoothAdapterState: isBleTurningOff()=false
11-15 13:55:53.828  6029  6041 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-15 13:55:53.828  6029  6041 D BluetoothAdapterProperties: ScanMode =  20
11-15 13:55:53.828  6029  6041 D BluetoothAdapterProperties: State =  11
11-15 13:55:53.828  6029  6041 D BluetoothAdapterProperties: Setting state to 12
11-15 13:55:53.828  6029  6041 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-15 13:55:53.829   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 13:55:53.829  6029  6041 I BluetoothAdapterState: Entering OnState
11-15 13:55:53.829  5842  5854 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 13:55:53.830   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 13:55:53.830  5842  5856 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 13:55:53.830  6029  6045 D BluetoothAdapterProperties: Scan Mode:21
11-15 13:55:53.830  6029  6045 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-15 13:55:53.834  5842  5854 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-15 13:55:53.836  3218  3232 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-15 13:55:53.837  5842  5842 D BluetoothInputDevice: Proxy object connected
,11-15 13:55:53.837  5842  5842 D HidProfile: Bluetooth service connected
,11-15 13:55:53.839  3218  4038 D BluetoothMap: onBluetoothStateChange: up=true
,11-15 13:55:53.840  3218  3218 D BluetoothA2dp: Proxy object connected
11-15 13:55:53.841  3218  3232 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 13:55:53.842  6029  6029 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-15 13:55:53.843  3218  3230 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 13:55:53.843  6029  6029 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-15 13:55:53.844  6029  6029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 13:55:53.845   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 13:55:53.845   928   928 D BluetoothA2dp: Proxy object connected
11-15 13:55:53.846  6029  6029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 13:55:53.846  5842  5854 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-15 13:55:53.846  6029  6029 D ObexServerSockets: Succeed to create listening sockets 
11-15 13:55:53.847  6029  6029 D ObexServerSockets0: startAccept()
11-15 13:55:53.847  6029  6029 D ObexServerSockets0: prepareForNewConnect()
11-15 13:55:53.848  3218  3218 D BluetoothInputDevice: Proxy object connected
11-15 13:55:53.848  3218  3218 D HidProfile: Bluetooth service connected
11-15 13:55:53.848  3218  3230 D BluetoothPan: onBluetoothStateChange on: true
11-15 13:55:53.850  6029  6029 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-15 13:55:53.850  6029  6029 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-15 13:55:53.851  5842  5842 D BluetoothA2dp: Proxy object connected
11-15 13:55:53.851  6029  6067 D ObexServerSockets0: Accepting socket connection...
11-15 13:55:53.851   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 13:55:53.851  5842  5856 D BluetoothPan: onBluetoothStateChange on: true
11-15 13:55:53.852  3218  3218 D BluetoothMap: Proxy object connected
11-15 13:55:53.852  3218  3218 D MapProfile: Bluetooth service connected
11-15 13:55:53.852  3218  3218 D BluetoothMap: getConnectedDevices()
11-15 13:55:53.853  6029  6068 D ObexServerSockets0: Accepting socket connection...
,11-15 13:55:53.854  3892  3911 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 13:55:53.854  3218  3232 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 13:55:53.855  3218  3218 D BluetoothPan: BluetoothPAN Proxy object connected
,11-15 13:55:53.855  3218  3218 D PanProfile: Bluetooth service connected
11-15 13:55:53.855  5842  5856 D BluetoothMap: onBluetoothStateChange: up=true
11-15 13:55:53.858  6029  6029 D BluetoothMapService: onReceive
11-15 13:55:53.858  6029  6029 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 13:55:53.858  6029  6029 D BluetoothMapService: STATE_ON
11-15 13:55:53.859   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-15 13:55:53.860  6029  6069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 13:55:53.861  6029  6069 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-15 13:55:53.861  6029  6069 D BluetoothSdpJni: SDP Create record success - handle: 1
11-15 13:55:53.861  5842  5842 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 13:55:53.861  5842  5842 D PanProfile: Bluetooth service connected
11-15 13:55:53.861  5842  5842 D BluetoothMap: Proxy object connected
11-15 13:55:53.861  5842  5842 D MapProfile: Bluetooth service connected
11-15 13:55:53.861  5842  5842 D BluetoothMap: getConnectedDevices()
,11-15 13:55:53.867  5842  5842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 13:55:53.872  3697  3697 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 13:55:53.878  5842  5842 D DockEventReceiver: finishStartingService: stopping service
,11-15 13:55:53.879  5842  5842 D BluetoothPbap: Proxy object connected
11-15 13:55:53.879  5842  5842 D PbapServerProfile: Bluetooth service connected
,11-15 13:55:53.883  3218  3218 D BluetoothPbap: Proxy object connected
11-15 13:55:53.884  3218  3218 D PbapServerProfile: Bluetooth service connected
,11-15 13:55:53.885  6029  6029 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 13:55:53.885  6029  6029 D ObexServerSockets0: prepareForNewConnect()
,11-15 13:55:53.888  6029  6073 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 13:55:53.903  6029  6077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 13:55:53.904  6029  6077 I BtOppRfcommListener: Accept thread started.
,11-15 13:55:53.931  5842  5854 D BluetoothHeadset: Proxy object connected
,11-15 13:55:53.931   928   928 D BluetoothHeadset: Proxy object connected
11-15 13:55:53.931  5842  5842 D HeadsetProfile: Bluetooth service connected
,11-15 13:55:53.932  3892  4122 D BluetoothHeadset: Proxy object connected
,11-15 13:55:53.932  3218  3230 D BluetoothHeadset: Proxy object connected
11-15 13:55:53.932   928   928 D BluetoothHeadset: Proxy object connected
11-15 13:55:53.932  3218  3218 D HeadsetProfile: Bluetooth service connected
11-15 13:55:53.932   928   928 D BluetoothHeadset: Proxy object connected
,11-15 13:55:53.951   928   945 D BluetoothHeadset: Proxy object connected
,11-15 13:55:53.954  3892  3909 D BluetoothHeadset: Proxy object connected
,11-15 13:55:53.955  3218  4038 D BluetoothHeadset: Proxy object connected
11-15 13:55:53.955  3218  3218 D HeadsetProfile: Bluetooth service connected
,11-15 13:55:54.567   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 13:55:57.640  5784  5831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:55:57.640  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:55:57.640  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:55:57.640  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 13:55:57.640  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 13:55:57.640  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 13:55:57.640  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 13:55:57.640  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 13:55:57.640  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 13:55:57.645  5784  5831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 13:55:57.646  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:55:57.646  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@89c18ef removed from the list
11-15 13:55:57.646  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 13:55:57.651  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 13:55:57.652  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e99ffc added. We now have 4 listener(s)
,11-15 13:55:57.652  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 13:55:57.657   928  3893 D WifiService: setWifiEnabled: false pid=5784, uid=10077
,11-15 13:55:57.657   928  3893 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 13:56:02.667  5784  5831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 13:56:02.669   928  3882 D WifiService: setWifiEnabled: true pid=5784, uid=10077
,11-15 13:56:02.670   928  3882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 13:56:02.678   508   921 D SoftapController: Softap fwReload - Ok
,11-15 13:56:02.684   508   921 D CommandListener: Setting iface cfg
,11-15 13:56:02.684   508   921 D CommandListener: Trying to bring down wlan0
11-15 13:56:02.686   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-15 13:56:02.692   928  3116 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 13:56:03.357   928  3116 D wifi    : set interface wlan0 flags (UP)
,11-15 13:56:03.358   928  3116 I WifiHAL : Initializing wifi
,11-15 13:56:03.358   928  3116 I WifiHAL : Creating socket
,11-15 13:56:03.364   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-15 13:56:03.364   928  3116 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-15 13:56:03.365   928  3116 D wifi    : Did set static halHandle = 0x7f59ee6120
11-15 13:56:03.365   928  3116 D wifi    : halHandle = 0x7f59ee6120, mVM = 0x7f764cd140, mCls = 0x2016e2
11-15 13:56:03.365   928  3116 D wifi    : array field set
11-15 13:56:03.365   928  3116 I WifiNative-HAL: interface[0] = wlan0
11-15 13:56:03.367   928  6084 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546969641248
,11-15 13:56:03.367   928  6084 D wifi    : waitForHalEvents called, vm = 0x7f764cd140, obj = 0x2016e2, env = 0x7f5b87cec0
,11-15 13:56:03.432  6085  6085 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-15 13:56:03.468   928  3116 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-15 13:56:03.469   928  3116 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-15 13:56:03.497  6085  6085 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 13:56:03.587  6085  6085 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 13:56:03.587  6085  6085 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-15 13:56:04.486   928  3116 D WifiConfigStore: Loading config and enabling all networks 
,11-15 13:56:04.526   928  3116 D WifiConfigStore: loaded 0 passpoint configs
,11-15 13:56:04.527   928  3116 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-15 13:56:04.528   928  3116 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-15 13:56:04.529   928  3116 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-15 13:56:04.530   928  3116 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-15 13:56:04.531   928  3116 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-15 13:56:04.532   928  3116 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-15 13:56:04.533   928  3116 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-15 13:56:04.533   928  3116 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-15 13:56:04.533   928  3116 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-15 13:56:04.533   928  3116 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-15 13:56:04.533   928  3116 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-15 13:56:04.533   928  3116 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-15 13:56:04.538   928  3116 D WifiNative-HAL: Setting external_sim to 1
,11-15 13:56:04.539  4476  4476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 13:56:04.539   928  3116 D wifi    : setting dfs flag to true, 0x7f5bc6d160
11-15 13:56:04.541   928  3116 D WifiStateMachine: Setting OUI to DA-A1-19
,11-15 13:56:04.541   928  3116 D wifi    : setting scan oui 0x7f5bc6d160
11-15 13:56:04.541   928  3116 D WifiHAL : Sending mac address OUI
,11-15 13:56:04.547   928  3116 E native  : do suspend false
,11-15 13:56:04.560   928  3116 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-15 13:56:04.561   928   928 D RttService: SCAN_AVAILABLE : 3
11-15 13:56:04.561   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-15 13:56:04.561   928  3184 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-15 13:56:04.562   508   921 D CommandListener: Setting iface cfg
,11-15 13:56:04.567   928  3115 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
11-15 13:56:04.567   624   624 I ServiceManager: Waiting for service AtCmdFwd...
11-15 13:56:04.567   928  3115 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-15 13:56:04.577   928  3115 D WifiNative-HAL: p2pGetDeviceAddress
,11-15 13:56:04.582   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=253517 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-15 13:56:04.583   928  3115 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-15 13:56:05.569   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:06.570   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:07.571   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:07.681  6085  6085 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 13:56:07.686  5784  5831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 13:56:07.686  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 13:56:07.686  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 13:56:07.686  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 13:56:07.686  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 13:56:07.686  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 13:56:07.686  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 13:56:07.686  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 13:56:07.686  5784  5831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 13:56:07.690  5784  5831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-15 13:56:07.690  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:56:07.690  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e99ffc removed from the list
11-15 13:56:07.690  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:56:07.693  6085  6085 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 13:56:07.697  5784  5831 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-15 13:56:07.698  5784  5831 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-15 13:56:07.700  6085  6085 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 13:56:07.703  5784  5831 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5300cef Bundle[{}]
,11-15 13:56:07.704  5784  5831 I io.jxcore.node.LifeCycleMonitor: start: OK
11-15 13:56:07.704  5784  5831 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-15 13:56:07.705  5784  5831 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-15 13:56:07.705  5784  5831 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-15 13:56:07.705  6085  6085 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-15 13:56:07.706  5784  5831 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-15 13:56:07.706  5784  5831 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-15 13:56:07.712  5784  5831 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 164)
11-15 13:56:07.713  5784  5831 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-15 13:56:07.713  5784  5831 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,11-15 13:56:07.715  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 13:56:07.715  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8201685 added. We now have 3 listener(s)
,11-15 13:56:07.717  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 13:56:07.717  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 13:56:07.717  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 13:56:07.717  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 13:56:07.717  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c644cda added. We now have 4 listener(s)
11-15 13:56:07.717  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 13:56:07.718  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 13:56:07.720  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 13:56:07.720  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb550b added. We now have 4 listener(s)
,11-15 13:56:07.722  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 13:56:07.722  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 13:56:07.722  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 13:56:07.722  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 13:56:07.722  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52ebfe8 added. We now have 5 listener(s)
11-15 13:56:07.722  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 13:56:07.722  5784  5831 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 13:56:07.722  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 13:56:07.722  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 13:56:07.722  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:56:07.722  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:56:07.723  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 13:56:07.723  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8201685 removed from the list
11-15 13:56:07.723  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:56:07.723  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c644cda removed from the list
11-15 13:56:07.723  5784  5831 D io.jxcore.node.ConnectivityMonitor: stop
11-15 13:56:07.723  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:56:07.724  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.724  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.724  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.724  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:56:07.725  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:56:07.725  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 13:56:07.725  5784  5831 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c644cda not in the list
11-15 13:56:07.725  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:56:07.726  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.726  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.726  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.727  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 13:56:07.727  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 13:56:07.727  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 13:56:07.727  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52ebfe8 removed from the list
11-15 13:56:07.727  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 13:56:07.727  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:56:07.727  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 13:56:07.727  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb550b removed from the list
11-15 13:56:07.728  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 13:56:07.728  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d09601 added. We now have 3 listener(s)
,11-15 13:56:07.729  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 13:56:07.729  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 13:56:07.729  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 13:56:07.730  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 13:56:07.730  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44a5ca6 added. We now have 4 listener(s)
11-15 13:56:07.730  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 13:56:07.731  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 13:56:07.732  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 13:56:07.732  5784  5831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4836e7 added. We now have 4 listener(s)
11-15 13:56:07.733   928  3116 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-15 13:56:07.734  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 13:56:07.734  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 13:56:07.734  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 13:56:07.734  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 13:56:07.734  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f23f294 added. We now have 5 listener(s)
,11-15 13:56:07.734  5784  5831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 13:56:07.734  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 13:56:07.734  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 13:56:07.734  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 13:56:07.734  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 13:56:07.734   928  3116 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-15 13:56:07.734  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 13:56:07.734   928  3116 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 13:56:07.737  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-15 13:56:07.741  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-15 13:56:07.741  5784  5831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 13:56:07.741  5784  5831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-15 13:56:07.746   928  3116 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-15 13:56:07.746  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.747  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 13:56:07.747  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 13:56:07.747  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 13:56:07.747  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-15 13:56:07.749  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.749  5784  5831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 13:56:07.749  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 13:56:07.749  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 13:56:07.749  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 13:56:07.749  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.750  5784  5831 D BluetoothAdapter: STATE_ON
11-15 13:56:07.752  6029  6064 D BtGatt.GattService: registerClient() - UUID=80942ef6-2374-41aa-b149-2771d70c7566
11-15 13:56:07.753  6029  6045 D BtGatt.GattService: onClientRegistered() - UUID=80942ef6-2374-41aa-b149-2771d70c7566, clientIf=5
11-15 13:56:07.753  5784  5795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 13:56:07.754  6029  6040 D BtGatt.GattService: start scan with filters
11-15 13:56:07.756  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 13:56:07.757  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 13:56:07.757  6029  6048 D BtGatt.ScanManager: handling starting scan
11-15 13:56:07.757  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 13:56:07.757  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.757  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 13:56:07.757  5784  5784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 13:56:07.757  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 13:56:07.757  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 13:56:07.757  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 13:56:07.757  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 13:56:07.757  5784  5784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 13:56:07.757  5784  5784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 13:56:07.758  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 13:56:07.758  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.758  6029  6048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c58ad0
11-15 13:56:07.760  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.760  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-15 13:56:07.760  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.760  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 13:56:07.761  5784  5831 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-15 13:56:07.761  5784  5831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-15 13:56:07.761  5784  5831 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 13:56:07.761  5784  5831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 13:56:07.761  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 13:56:07.761  5784  5831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 13:56:07.761  5784  5831 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 13:56:07.761  5784  5831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 13:56:07.761  5784  5831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 13:56:07.761  5784  5831 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-15 13:56:07.766  6029  6045 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-15 13:56:07.766  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:56:07.767  6029  6048 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-15 13:56:07.772  6029  6045 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-15 13:56:07.772  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:56:07.773  6029  6048 D BtGatt.ScanManager: Starting BLE batch scan
11-15 13:56:07.773  6029  6048 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-15 13:56:07.780   928  3116 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-15 13:56:07.784  6029  6045 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-15 13:56:07.784  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:56:07.786  6085  6085 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-15 13:56:07.790  6029  6045 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 13:56:07.790  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:56:08.417  6085  6085 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-15 13:56:08.476  6085  6085 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-15 13:56:08.476  6085  6085 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-15 13:56:08.485   928  3116 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-15 13:56:08.485   928  3116 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-15 13:56:08.485   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-15 13:56:08.502   928  3116 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 13:56:08.515   508   921 D CommandListener: Setting iface cfg
,11-15 13:56:08.520   928  3116 D WifiStateMachine: Start Dhcp Watchdog 3
,11-15 13:56:08.527   928  6099 D DhcpClient: Receive thread started
,11-15 13:56:08.534   928  3116 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-15 13:56:08.534   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-15 13:56:08.534   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-15 13:56:08.572   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:08.628   928  3116 E native  : do suspend false
,11-15 13:56:08.652   928  6098 D DhcpClient: Broadcasting DHCPDISCOVER
,11-15 13:56:08.716   928  6099 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-15 13:56:08.717   928  6098 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-15 13:56:08.722  6029  6029 D BtGatt.ScanManager: awakened up at time 257657
,11-15 13:56:08.723   928  6098 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-15 13:56:08.727  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:56:08.735   928  6099 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-15 13:56:08.736   928  6098 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-15 13:56:08.739   508   921 D CommandListener: Setting iface cfg
,11-15 13:56:08.745   928  3116 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-15 13:56:08.750   928  6098 D DhcpClient: Scheduling renewal in 86399s
,11-15 13:56:08.752  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
11-15 13:56:08.752  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:56:08.752  6029  6045 D BtGatt.GattService: current time is 257686842224
11-15 13:56:08.752  6029  6045 D BtGatt.GattService: Batch record : [96, 42, -109, 88, -26, 116, 1, -128, -90, 2, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -79, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
11-15 13:56:08.754  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
11-15 13:56:08.756  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:56:08.756  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,11-15 13:56:08.758   928  3116 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-15 13:56:08.758   928  3116 D WifiConfigStore: No blacklist allowed without epno enabled
11-15 13:56:08.759   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-15 13:56:08.760   928  3116 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-15 13:56:08.763   928  3129 D ConnectivityService: Adding iface wlan0 to network 102
,11-15 13:56:08.790   928  3129 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-15 13:56:08.790   928  3129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-15 13:56:08.792   928  3129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-15 13:56:08.793   928  3129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-15 13:56:08.795   928  3129 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-15 13:56:08.801   928  3129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:56:08.806   928  3129 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-15 13:56:08.806   928  3129 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-15 13:56:08.806   928  3129 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-15 13:56:08.806   928  3129 D ConnectivityService:    accepting network in place of null
11-15 13:56:08.806   928  3116 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-15 13:56:08.806   928  3116 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 13:56:08.806   928  3129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 13:56:08.813   928  6097 D NetlinkSocketObserver: NeighborEvent{elapsedMs=257747, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-15 13:56:08.826   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 13:56:08.847   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 13:56:08.851   928  3129 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-15 13:56:08.851  3859  3979 W QCNEJ   : |CORE| network available: 102
11-15 13:56:08.851   928  3129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-15 13:56:08.852   928  3129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-15 13:56:08.852   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-15 13:56:08.855  3859  3979 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-15 13:56:08.856  3859  3979 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-15 13:56:08.856  3859  3979 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-15 13:56:08.864  5079  5095 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-15 13:56:08.864  5079  5095 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-15 13:56:08.864  5079  5095 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-15 13:56:08.865  5079  5095 E SarControlService: no key has been found,reset the power
11-15 13:56:08.865  5079  5122 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-15 13:56:08.865  5079  5122 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-15 13:56:08.865  5079  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-15 13:56:08.865  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 13:56:08.865  5109  5109 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-15 13:56:08.867  5079  5122 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-15 13:56:08.867  5079  5122 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-15 13:56:08.867  5079  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-15 13:56:08.868  4054  4054 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-15 13:56:08.872  4066  4066 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-15 13:56:08.875  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 13:56:08.875  5109  5109 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-15 13:56:08.876  4066  4066 D SystemUpdateService: onCreate
,11-15 13:56:08.881  5109  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fcea31b HexData = [00000000f003000000000000ffffffff]
11-15 13:56:08.881   928  6096 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
11-15 13:56:08.881  5109  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 13:56:08.881  5109  5130 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-15 13:56:08.882  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-15 13:56:08.882  5079  5091 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-15 13:56:08.883  4066  4066 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-15 13:56:08.884  5109  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fcea31b HexData = [00000000f103000000000000ffffffff]
11-15 13:56:08.884  5109  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 13:56:08.884  5109  5130 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
,11-15 13:56:08.886  5109  5109 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-15 13:56:08.886  5079  5092 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-15 13:56:08.896  4066  4066 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-15 13:56:08.902  4066  5519 I iu.UploadsManager: num queued entries: 0
11-15 13:56:08.902  4066  5519 I iu.UploadsManager: num updated entries: 0
11-15 13:56:08.903  4066  5519 I iu.SyncManager: NEXT; no task
,11-15 13:56:08.906  4066  6110 I SystemUpdateService: active receiver: enabled
,11-15 13:56:08.910  4066  4066 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 13:56:08.912  4066  4066 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 13:56:08.915  5894  5894 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-15 13:56:08.918  5894  5894 D SprintDMHelper: simOperator: 
11-15 13:56:08.918  5894  5894 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 13:56:08.930   928  6096 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Nov 2016 12:56:08 GMT], X-Android-Received-Millis=[1479214568929], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479214568904]}
,11-15 13:56:08.931   928  3129 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-15 13:56:08.931   928  3129 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-15 13:56:08.931   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-15 13:56:08.932   928  3129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-15 13:56:08.937  4066  6110 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 13:56:08.941  4066  6110 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-15 13:56:08.941  4066  6110 I SystemUpdateService: now status is 0 (complete)
11-15 13:56:08.941  4066  6110 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-15 13:56:08.941  4066  6110 I SystemUpdateService: file has been verified
11-15 13:56:08.941  4066  6110 I SystemUpdateService: OTA package size = 21989297
,11-15 13:56:08.947  4066  6110 I SystemUpdateService: showing system update notification
,11-15 13:56:08.956   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 13:56:08.957  4066  4066 D SystemUpdateService: onDestroy
,11-15 13:56:09.175  4476  6114 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-15 13:56:09.573   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 13:56:10.219   928  3116 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,11-15 13:56:10.233   928  3129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:56:10.238  3859  3979 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-15 13:56:10.239  3859  3979 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-15 13:56:11.554   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:56:14.328   928  2871 I hubconnection: sensorhub said: 'set_bias 3: -4.3200, 0.0000, 0.0000'
,11-15 13:56:16.812   928  3129 D ConnectivityService: handlePromptUnvalidated 102
,11-15 13:56:19.587   928  3116 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,11-15 13:56:24.575   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:25.576   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:26.578   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:27.579   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:28.580   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:29.581   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-15 13:56:32.736   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:56:35.767   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:56:43.457   928  6097 D NetlinkSocketObserver: NeighborEvent{elapsedMs=292391, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 13:56:45.134   928  2871 I hubconnection: sensorhub said: 'set_bias 3: -3.8400, 0.0000, 0.0000'
,11-15 13:56:48.794   928  3116 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 13:56:49.583   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:50.584   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:51.586   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:52.587   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:53.589   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:56:54.590   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 13:56:59.985   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:56:59.993   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 56
,11-15 13:57:03.018   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:57:03.022   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-15 13:57:03.223   928  6097 D NetlinkSocketObserver: NeighborEvent{elapsedMs=312157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 13:57:08.934   928   941 W BroadcastQueue: Timeout of broadcast BroadcastRecord{bd39e94 u-1 android.net.conn.CONNECTIVITY_CHANGE} - receiver=android.os.BinderProxy@de3cd3d, started 60000ms ago
,11-15 13:57:08.935   928   941 W BroadcastQueue: Receiver during timeout: ResolveInfo{cb52932 com.test.thalitest/io.jxcore.node.ConnectivityChangeListener m=0x108000}
,11-15 13:57:08.977  6029  6029 D BtGatt.ScanManager: awakened up at time 317912
,11-15 13:57:08.980  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:09.013  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
11-15 13:57:09.013  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:57:09.013  6029  6045 D BtGatt.GattService: current time is 317947842708
11-15 13:57:09.013  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 103, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -92, 3, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 96, 42, -109, 88, -26, 116, 1, -128, -87, 98, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -87, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -78, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -88, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:57:09.014  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:57:09.014  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,11-15 13:57:09.014  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
11-15 13:57:09.014  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:57:09.014  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:57:09.014  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:57:09.015  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:57:09.015  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:57:09.055   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:57:09.081   928   941 I Process : Sending signal. PID: 5784 SIG: 3
,11-15 13:57:09.081  5784  5789 I art     : Thread[2,tid=5789,WaitingInMainSignalCatcherLoop,Thread*=0xef6a6500,peer=0x12c2e0a0,"Signal Catcher"]: reacting to signal 3
,11-15 13:57:09.282   928   941 I Process : Sending signal. PID: 928 SIG: 3
,11-15 13:57:09.283   928   933 I art     : Thread[2,tid=933,WaitingInMainSignalCatcherLoop,Thread*=0x7f6c642000,peer=0x12c010a0,"Signal Catcher"]: reacting to signal 3
,11-15 13:57:09.483   928   941 I Process : Sending signal. PID: 3892 SIG: 3
,11-15 13:57:09.484  3892  3899 I art     : Thread[2,tid=3899,WaitingInMainSignalCatcherLoop,Thread*=0x7f6c642000,peer=0x12c530a0,"Signal Catcher"]: reacting to signal 3
,11-15 13:57:09.577  5784  5789 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-15 13:57:09.577   928   941 I Process : Sending signal. PID: 3877 SIG: 3
,11-15 13:57:09.578  3877  3883 I art     : Thread[2,tid=3883,WaitingInMainSignalCatcherLoop,Thread*=0x7f6c642000,peer=0x12c510a0,"Signal Catcher"]: reacting to signal 3
,11-15 13:57:09.626  3877  3883 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-15 13:57:09.627   928   941 I Process : Sending signal. PID: 3859 SIG: 3
11-15 13:57:09.627  3859  3866 I art     : Thread[2,tid=3866,WaitingInMainSignalCatcherLoop,Thread*=0x7f6c642000,peer=0x12c500a0,"Signal Catcher"]: reacting to signal 3
,11-15 13:57:09.708  3892  3899 I art     : Wrote stack traces to '/data/anr/traces.txt'
11-15 13:57:09.709   928   941 I Process : Sending signal. PID: 3218 SIG: 3
,11-15 13:57:09.709  3218  3222 I art     : Thread[2,tid=3222,WaitingInMainSignalCatcherLoop,Thread*=0x7f6c642000,peer=0x12c320a0,"Signal Catcher"]: reacting to signal 3
,11-15 13:57:09.711  3859  3866 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-15 13:57:09.885  3218  3222 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-15 13:57:10.194   928   933 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-15 13:57:12.071   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:57:12.980   928   941 E ActivityManager: ANR in com.test.thalitest
11-15 13:57:12.980   928   941 E ActivityManager: PID: 5784
11-15 13:57:12.980   928   941 E ActivityManager: Reason: Broadcast of Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.test.thalitest/io.jxcore.node.ConnectivityChangeListener (has extras) }
11-15 13:57:12.980   928   941 E ActivityManager: Load: 7.07 / 4.93 / 2.23
11-15 13:57:12.980   928   941 E ActivityManager: CPU usage from 283970ms to 0ms ago:
11-15 13:57:12.980   928   941 E ActivityManager:   5.7% 928/system_server: 3.9% user + 1.8% kernel / faults: 53652 minor
11-15 13:57:12.980   928   941 E ActivityManager:   2.9% 4916/com.android.vending: 2.7% user + 0.2% kernel / faults: 24801 minor
11-15 13:57:12.980   928   941 E ActivityManager:   2.2% 4054/com.google.android.googlequicksearchbox:search: 2.2% user + 0% kernel / faults: 6238 minor 1 major
11-15 13:57:12.980   928   941 E ActivityManager:   1.1% 503/adbd: 0.1% user + 0.9% kernel / faults: 5258 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0.7% 513/mediaserver: 0.3% user + 0.4% kernel / faults: 45 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0.4% 3218/com.android.systemui: 0.2% user + 0.1% kernel / faults: 1953 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0.4% 4/kworker/0:0: 0% user + 0.4% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0.3% 65/kworker/0:3: 0% user + 0.3% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0.3% 374/kworker/u16:4: 0% user + 0.3% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0.3% 4066/com.google.android.gms: 0.2% user + 0% kernel / faults: 15150 minor 17 major
11-15 13:57:12.980   928   941 E ActivityManager:   0.3% 248/mmcqd/0: 0% user + 0.3% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0.2% 290/msm-core:sampli: 0% user + 0.2% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0.2% 3697/com.google.process.gapps: 0.1% user + 0% kernel / faults: 7948 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0.2% 8/rcu_preempt: 0% user + 0.2% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0.2% 45/kworker/u16:2: 0% user + 0.2% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0.2% 388/msm_irqbalance: 0% user + 0.1% kernel / faults: 33 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0.2% 382/surfaceflinger: 0% user + 0.1% kernel / faults: 449 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0.2% 239/cfinteractive: 0% user + 0.2% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0.1% 347/logd: 0% user + 0.1% kernel / faults: 170 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0.1% 436/irq/215-fc38800: 0% user + 0.1% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0.1% 3800/com.google.android.inputmethod.latin: 0% user + 0% kernel / faults: 3285 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0.1% 16/ksoftirqd/2: 0% user + 0.1% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0.1% 519/thermal-engine: 0% user + 0% kernel / faults: 25 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0.1% 4337/kworker/u16:6: 0% user + 0.1% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 12/ksoftirqd/1: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 4476/com.google.android.talk: 0% user + 0% kernel / faults: 8951 minor 23 major
11-15 13:57:12.980   928   941 E ActivityManager:   0% 3/ksoftirqd/0: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 600/kworker/0:4: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 3859/com.quicinc.cne.CNEService: 0% user + 0% kernel / faults: 696 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 35/kworker/u17:0: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 3231/android.process.media: 0% user + 0% kernel / faults: 3692 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 508/netd: 0% user + 0% kernel / fau,lts: 1608 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 28/kworker/3:1: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 451/mdss_fb0: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 130/kswapd0: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 251/kworker/u16:3: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 2807/kworker/u17:7: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 3892/com.android.phone: 0% user + 0% kernel / faults: 211 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 20/ksoftirqd/3: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 37/kworker/u17:1: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 329/kworker/u17:5: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 4228/com.google.android.gms.persistent: 0% user + 0% kernel / faults: 404 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 3918/com.google.android.googlequicksearchbox: 0% user + 0% kernel / faults: 3332 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 326/kworker/u17:2: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 527/zygote64: 0% user + 0% kernel / faults: 13077 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 327/kworker/u17:3: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 500/jbd2/dm-2-8: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 478/dmcrypt_write: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 5096/com.google.android.apps.maps: 0% user + 0% kernel / faults: 3658 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 328/kworker/u17:4: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 380/lmkd: 0% user + 0% kernel / faults: 13 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 496/kworker/u17:6: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 528/zygote: 0% user + 0% kernel / faults: 4680 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 161/msm_serial_hs_0: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 381/servicemanager: 0% user + 0% kernel / faults: 51 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 4297/com.google.android.gms.wearable: 0% user + 0% kernel / faults: 4542 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 162/hwrng: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 41/ksoftirqd/4: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 160/msm_serial_hs_0: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 312/kworker/1:2: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 622/cnd: 0% user + 0% kernel / faults: 54 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 5109/com.qualcomm.qcrilmsgtunnel: 0% user + 0% kernel / faults: 2157 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 29/kworker/2:1: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 30/kworker/2:1H: 0% user + 0% kernel
11-15 13:57:12.980   928   941 E ActivityManager:   0% 319/ueventd: 0% user + 0% kernel / faults: 56 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 520/qmuxd: 0% user + 0% kernel / faults: 122 minor
11-15 13:57:12.980   928   941 E ActivityManager:   0% 624/ATFWD-daemon: 0% user + 0% kernel / fa
,11-15 13:57:13.029  4282  4282 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[35637]" dev="sockfs" ino=35637 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 13:57:13.029  4282  4282 W Binder_5: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[35637]" dev="sockfs" ino=35637 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 13:57:13.036   928  6123 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-15 13:57:13.032  4282  4282 W Binder_5: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[35640]" dev="sockfs" ino=35640 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 13:57:13.032  4282  4282 W Binder_5: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[35640]" dev="sockfs" ino=35640 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 13:57:13.137   928  6123 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-15 13:57:13.137   928  6123 I Adreno  : Build Date                       : 12/06/15
11-15 13:57:13.137   928  6123 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-15 13:57:13.137   928  6123 I Adreno  : Local Branch                     : mybranch17112971
11-15 13:57:13.137   928  6123 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-15 13:57:13.137   928  6123 I Adreno  : Remote Branch                    : NONE
11-15 13:57:13.137   928  6123 I Adreno  : Reconstruct Branch               : NOTHING
,11-15 13:57:13.145   928  6123 I OpenGLRenderer: Initialized EGL, version 1.4
,11-15 13:57:14.018  6029  6029 D BtGatt.ScanManager: awakened up at time 322952
11-15 13:57:14.020  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:14.058  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 13:57:14.058  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:57:14.058  6029  6045 D BtGatt.GattService: current time is 322993155361
,11-15 13:57:14.059  6029  6045 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, 4, -86, 6, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -77, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:57:14.059  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:57:14.060  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:57:14.060  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:57:14.061  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:57:14.061  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:57:14.062  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 13:57:15.102   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:57:15.938   928  2871 I hubconnection: sensorhub said: 'set_bias 3: -2.8800, 0.0000, 0.0000'
,11-15 13:57:19.072  6029  6029 D BtGatt.ScanManager: awakened up at time 328006
,11-15 13:57:19.075  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:19.131   928   938 I ActivityManager: Start proc 6128:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-15 13:57:19.133  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:57:19.133  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:57:19.133  6029  6045 D BtGatt.GattService: current time is 328067896936
11-15 13:57:19.134  6029  6045 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -86, 84, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -80, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -88, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:57:19.134  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:57:19.134  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:57:19.135  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:57:19.135  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:57:19.136  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:57:19.136  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 13:57:19.137  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 13:57:19.177  6128  6128 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-15 13:57:19.274  6128  6140 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-15 13:57:19.359  6128  6140 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-15 13:57:19.405  6128  6140 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-15 13:57:19.438  6153  6153 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1148093860.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1148093860.dex
,11-15 13:57:19.445  6128  6128 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-15 13:57:19.468  6153  6153 I dex2oat : dex2oat took 31.275ms (threads: 2) arena alloc=180KB java alloc=37KB native alloc=1257KB free=1302KB
,11-15 13:57:19.591   624   624 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-15 13:57:19.591   624   624 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 13:57:19.603  6128  6128 W InstanceID/Rpc: Found 10012
,11-15 13:57:20.160   928  3902 I ActivityManager: Killing 3512:android.process.acore/u0a2 (adj 15): empty #17
,11-15 13:57:20.192  6029  6029 D BtGatt.ScanManager: awakened up at time 329126
,11-15 13:57:20.192  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:20.209  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-15 13:57:20.209  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:57:20.209  6029  6045 D BtGatt.GattService: current time is 329143790957
,11-15 13:57:20.209  6029  6045 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -88, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -89, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:57:20.209  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:57:20.210  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:57:20.210  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:57:20.210  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:57:20.210  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 13:57:25.213  6029  6029 D BtGatt.ScanManager: awakened up at time 334148
,11-15 13:57:25.216  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:25.251  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 13:57:25.251  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:57:25.252  6029  6045 D BtGatt.GattService: current time is 334186423905
11-15 13:57:25.252  6029  6045 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -101, 9, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -87, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:57:25.253  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:57:25.253  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:57:25.253  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:57:25.254  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 13:57:25.254  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:57:25.254  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:57:28.799   928  3116 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 13:57:30.247   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:57:30.254   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 56
11-15 13:57:30.258  6029  6029 D BtGatt.ScanManager: awakened up at time 339192
,11-15 13:57:30.260  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:30.304  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:57:30.304  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:57:30.304  6029  6045 D BtGatt.GattService: current time is 339239191397
11-15 13:57:30.305  6029  6045 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -89, 11, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -78, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -77, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -80, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -91, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:57:30.305  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,11-15 13:57:30.306  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:57:30.306  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:57:30.307  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:57:30.307  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:57:30.307  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:57:30.308  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 13:57:33.281   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:57:33.288   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-15 13:57:34.593   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:57:35.309  6029  6029 D BtGatt.ScanManager: awakened up at time 344243
,11-15 13:57:35.311  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:35.345  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 13:57:35.345  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:57:35.346  6029  6045 D BtGatt.GattService: current time is 344280315604
11-15 13:57:35.346  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -88, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -89, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:57:35.346  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:57:35.347  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:57:35.347  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 13:57:35.347  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:57:35.348  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:57:35.348  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:57:35.594   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:57:36.596   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:57:37.597   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:57:38.599   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:57:39.334   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:57:39.343   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 55
,11-15 13:57:39.600   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 13:57:40.351  6029  6029 D BtGatt.ScanManager: awakened up at time 349285
,11-15 13:57:40.354  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:40.389  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:57:40.389  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:57:40.389  6029  6045 D BtGatt.GattService: current time is 349323963561
,11-15 13:57:40.390  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -99, 25, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -91, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:57:40.390  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:57:40.391  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:57:40.391  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,11-15 13:57:40.391  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:57:40.392  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:57:40.392  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:57:40.392  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 13:57:42.372   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:57:42.375   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-15 13:57:44.601   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:57:45.394  6029  6029 D BtGatt.ScanManager: awakened up at time 354329
11-15 13:57:45.397  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:45.445  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:57:45.445  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:57:45.446  6029  6045 D BtGatt.GattService: current time is 354380398724
11-15 13:57:45.446  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -92, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -86, 27, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -80, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -87, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:57:45.447  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 13:57:45.447  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:57:45.448  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:57:45.448  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:57:45.448  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:57:45.449  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:57:45.449  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:57:45.603   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:57:46.604   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:57:47.606   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:57:48.607   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:57:48.801   928  3116 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 13:57:49.608   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 13:57:50.456  6029  6029 D BtGatt.ScanManager: awakened up at time 359391
,11-15 13:57:50.459  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:50.492  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-15 13:57:50.492  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:57:50.492  6029  6045 D BtGatt.GattService: current time is 359426934784
11-15 13:57:50.492  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -78, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -88, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, -128, -98, 18, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -78, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:57:50.493  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 13:57:50.493  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:57:50.493  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:57:50.494  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:57:50.495  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:57:50.495  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 13:57:50.998  6029  6029 D BtGatt.ScanManager: awakened up at time 359932
,11-15 13:57:50.999  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:51.004  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-15 13:57:51.004  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:57:51.461   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:57:54.494   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:57:56.008  6029  6029 D BtGatt.ScanManager: awakened up at time 364942
,11-15 13:57:56.012  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:57:56.045  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:57:56.045  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:57:56.046  6029  6045 D BtGatt.GattService: current time is 364980534768
11-15 13:57:56.046  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -84, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -85, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -90, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -86, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, -128, -97, 19, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
11-15 13:57:56.047  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:57:56.047  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 13:57:56.047  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:57:56.047  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:57:56.048  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:57:56.048  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:57:56.048  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,11-15 13:57:59.609   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:00.611   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:01.053  6029  6029 D BtGatt.ScanManager: awakened up at time 369987
11-15 13:58:01.055  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:01.107  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:58:01.108  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:58:01.108  6029  6045 D BtGatt.GattService: current time is 370042865146
11-15 13:58:01.109  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -91, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -77, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -78, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -85, 21, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -84, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -80, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -88, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:58:01.109  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:58:01.110  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:58:01.110  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:01.110  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,11-15 13:58:01.111  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:58:01.111  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:58:01.111  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:58:01.612   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:02.614   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:03.615   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:04.616   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 13:58:06.114  6029  6029 D BtGatt.ScanManager: awakened up at time 375048
,11-15 13:58:06.117  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:06.153  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:58:06.154  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:58:06.154  6029  6045 D BtGatt.GattService: current time is 375088749853
,11-15 13:58:06.155  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -98, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -96, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -77, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -89, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -78, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -94, 23, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
11-15 13:58:06.155  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:58:06.156  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:06.157  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:58:06.157  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:58:06.157  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:58:06.157  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:58:06.158  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,11-15 13:58:11.158  6029  6029 D BtGatt.ScanManager: awakened up at time 380093
,11-15 13:58:11.163  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:11.186  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-15 13:58:11.187  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:58:11.187  6029  6045 D BtGatt.GattService: current time is 380121563539
11-15 13:58:11.187  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -85, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -95, 36, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 116, -43, -111, -91, -20, -29, 1, -128, -86, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:58:11.187  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:11.188  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:58:11.188  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:58:16.193  6029  6029 D BtGatt.ScanManager: awakened up at time 385127
,11-15 13:58:16.195  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:16.229  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:58:16.229  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:58:16.229  6029  6045 D BtGatt.GattService: current time is 385163816622
11-15 13:58:16.229  6029  6045 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -86, 27, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -90, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -77, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -80, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -83, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:58:16.230  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:58:16.230  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:58:16.230  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:58:16.230  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:16.230  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:58:16.231  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:58:16.231  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:58:19.618   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:20.619   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:21.236  6029  6029 D BtGatt.ScanManager: awakened up at time 390170
,11-15 13:58:21.238  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:21.267  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:58:21.267  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:58:21.267  6029  6045 D BtGatt.GattService: current time is 390201752774
11-15 13:58:21.267  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -96, 51, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -89, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -78, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -87, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:58:21.268  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:21.268  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:58:21.268  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:58:21.268  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:58:21.268  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 13:58:21.269  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:58:21.269  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:58:21.621   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:22.622   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:23.624   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:24.625   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-15 13:58:25.036   928  6097 D NetlinkSocketObserver: NeighborEvent{elapsedMs=393970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 13:58:26.275  6029  6029 D BtGatt.ScanManager: awakened up at time 395209
,11-15 13:58:26.277  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:26.317  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 13:58:26.317  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:58:26.317  6029  6045 D BtGatt.GattService: current time is 395252019416
11-15 13:58:26.318  6029  6045 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -94, 41, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -84, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -88, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -87, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:58:26.318  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:58:26.318  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:58:26.319  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:26.319  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:58:26.319  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,11-15 13:58:26.320  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:58:28.806   928  3116 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 13:58:31.324  6029  6029 D BtGatt.ScanManager: awakened up at time 400258
,11-15 13:58:31.326  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:31.368  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:58:31.368  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:58:31.369  6029  6045 D BtGatt.GattService: current time is 400303513140
11-15 13:58:31.369  6029  6045 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -87, 32, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -89, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -87, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -78, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -80, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:58:31.370  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:58:31.370  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 13:58:31.370  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:58:31.370  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:31.371  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:58:31.371  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:58:31.371  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:58:36.377  6029  6029 D BtGatt.ScanManager: awakened up at time 405312
,11-15 13:58:36.380  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:36.412  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 13:58:36.412  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:58:36.412  6029  6045 D BtGatt.GattService: current time is 405346907170
11-15 13:58:36.413  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -81, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -88, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -78, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -89, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:58:36.413  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:36.413  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:58:36.414  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:58:36.414  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 13:58:36.414  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:58:36.415  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:58:41.417  6029  6029 D BtGatt.ScanManager: awakened up at time 410351
,11-15 13:58:41.420  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:41.459  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:58:41.459  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:58:41.459  6029  6045 D BtGatt.GattService: current time is 410393992596
11-15 13:58:41.460  6029  6045 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -86, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -88, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -91, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, -128, -105, 36, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
11-15 13:58:41.460  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 13:58:41.461  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:41.461  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:58:41.462  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 13:58:41.465  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:58:41.466  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:58:41.467  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,11-15 13:58:44.626   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:45.628   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:46.468  6029  6029 D BtGatt.ScanManager: awakened up at time 415402
,11-15 13:58:46.470  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:46.516  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:58:46.516  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:58:46.516  6029  6045 D BtGatt.GattService: current time is 415451037123
11-15 13:58:46.517  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -90, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -92, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -88, 38, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -80, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:58:46.517  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:58:46.518  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:58:46.518  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 13:58:46.519  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:58:46.519  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:58:46.520  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:58:46.520  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:58:46.629   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:47.631   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:48.633   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:58:48.809   928  3116 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 13:58:49.634   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 13:58:51.521  6029  6029 D BtGatt.ScanManager: awakened up at time 420456
,11-15 13:58:51.524  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:51.566  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-15 13:58:51.566  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:58:51.567  6029  6045 D BtGatt.GattService: current time is 420501517051
11-15 13:58:51.567  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -89, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -79, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:58:51.568  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:51.568  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:58:51.569  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 13:58:51.569  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:58:51.569  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 13:58:53.918   928  6097 D NetlinkSocketObserver: NeighborEvent{elapsedMs=422851, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 13:58:56.577  6029  6029 D BtGatt.ScanManager: awakened up at time 425511
,11-15 13:58:56.579  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:58:56.614  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-15 13:58:56.614  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:58:56.615  6029  6045 D BtGatt.GattService: current time is 425549300529
,11-15 13:58:56.615  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -92, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -99, 30, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 116, -43, -111, -91, -20, -29, 1, -128, -86, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:58:56.616  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,11-15 13:58:56.616  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:58:56.617  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:58:56.617  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:58:56.617  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:58:56.618  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:59:01.620  6029  6029 D BtGatt.ScanManager: awakened up at time 430555
,11-15 13:59:01.622  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:01.651  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-15 13:59:01.651  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:01.652  6029  6045 D BtGatt.GattService: current time is 430586443021
11-15 13:59:01.652  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -78, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -88, 32, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -87, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -83, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:59:01.652  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 13:59:01.653  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:59:01.653  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:59:01.653  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:59:01.653  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:59:06.656  6029  6029 D BtGatt.ScanManager: awakened up at time 435590
,11-15 13:59:06.660  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:06.695  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:59:06.696  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:06.696  6029  6045 D BtGatt.GattService: current time is 435630566524
11-15 13:59:06.696  6029  6045 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -100, 45, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 116, -43, -111, -91, -20, -29, 1, -128, -79, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -88, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -89, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:59:06.697  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:59:06.697  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:59:06.697  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 13:59:06.698  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:59:06.698  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:59:06.698  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:59:06.699  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:59:08.811   928  3116 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 13:59:10.157   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:59:10.163   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 56
,11-15 13:59:11.705  6029  6029 D BtGatt.ScanManager: awakened up at time 440639
,11-15 13:59:11.707  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:11.746  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 13:59:11.746  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:11.746  6029  6045 D BtGatt.GattService: current time is 440680896496
11-15 13:59:11.747  6029  6045 D BtGatt.GattService: Batch record : [43, -86, -118, 67, 121, 76, 1, -128, -101, 62, 0, 27, 2, 1, 26, 23, -1, 76, 0, 12, 14, 0, -106, 95, -75, 73, -37, 21, -49, 58, -74, -24, 75, 122, -6, 16, 2, 11, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -100, 58, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -87, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -93, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 13:59:11.747  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 23, -1, 76, 0, 12, 14, 0, -106, 95, -75, 73, -37, 21, -49, 58, -74, -24, 75, 122, -6, 16, 2, 11, 0]
11-15 13:59:11.748  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:59:11.748  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:59:11.749  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:59:11.749  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 13:59:11.749  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 13:59:13.184   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:59:13.188   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-15 13:59:14.635   624   624 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-15 13:59:14.635   624   624 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 13:59:16.751  6029  6029 D BtGatt.ScanManager: awakened up at time 445685
,11-15 13:59:16.753  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:16.790  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-15 13:59:16.791  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:16.791  6029  6045 D BtGatt.GattService: current time is 445725670849
11-15 13:59:16.791  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -78, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -86, 38, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -92, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -78, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -92, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,11-15 13:59:16.792  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:59:16.793  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:59:16.794  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:59:16.794  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:59:16.794  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,11-15 13:59:19.249   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-15 13:59:19.254   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 54
,11-15 13:59:21.796  6029  6029 D BtGatt.ScanManager: awakened up at time 450731
,11-15 13:59:21.799  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:21.837  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-15 13:59:21.837  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:21.837  6029  6045 D BtGatt.GattService: current time is 450772196017
11-15 13:59:21.838  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -78, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -87, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -89, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:59:21.839  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:59:21.839  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 13:59:21.840  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:59:21.840  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:59:21.840  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 13:59:22.281   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:59:22.291   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-15 13:59:25.308   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:59:26.843  6029  6029 D BtGatt.ScanManager: awakened up at time 455778
,11-15 13:59:26.845  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:26.879  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-15 13:59:26.879  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 13:59:26.880  6029  6045 D BtGatt.GattService: current time is 455814453312
,11-15 13:59:26.880  6029  6045 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -97, 64, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -93, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:59:26.881  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:59:26.881  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:59:26.881  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:59:26.882  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:59:26.882  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 13:59:28.077   928  6097 D NetlinkSocketObserver: NeighborEvent{elapsedMs=457010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 13:59:28.339   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:59:31.885  6029  6029 D BtGatt.ScanManager: awakened up at time 460819
,11-15 13:59:31.890  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:31.927  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-15 13:59:31.928  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:31.928  6029  6045 D BtGatt.GattService: current time is 460862594094
,11-15 13:59:31.928  6029  6045 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -87, 43, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -79, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -78, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -81, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:59:31.929  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:59:31.929  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:59:31.930  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 13:59:31.930  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:59:31.930  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:59:34.637   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:59:35.638   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:59:36.640   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:59:36.932  6029  6029 D BtGatt.ScanManager: awakened up at time 465867
,11-15 13:59:36.934  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:36.970  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 13:59:36.970  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:36.971  6029  6045 D BtGatt.GattService: current time is 465905318874
,11-15 13:59:36.971  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -78, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -90, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -90, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -77, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:59:36.972  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:59:36.972  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 13:59:36.973  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:59:36.973  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 13:59:36.973  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:59:36.974  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:59:37.490   928  6097 D NetlinkSocketObserver: NeighborEvent{elapsedMs=466424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 13:59:37.641   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:59:38.642   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:59:39.643   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 13:59:41.977  6029  6029 D BtGatt.ScanManager: awakened up at time 470912
11-15 13:59:41.980  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:42.014  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:59:42.014  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:42.015  6029  6045 D BtGatt.GattService: current time is 470949460381
11-15 13:59:42.015  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -90, 57, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -89, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -85, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -92, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:59:42.015  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:59:42.016  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:59:42.016  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:59:42.016  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:59:42.016  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:59:42.016  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:59:42.017  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 13:59:43.480   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:59:44.645   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:59:45.647   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:59:46.514   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 13:59:46.648   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:59:47.019  6029  6029 D BtGatt.ScanManager: awakened up at time 475954
,11-15 13:59:47.021  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:47.068  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 13:59:47.068  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:47.068  6029  6045 D BtGatt.GattService: current time is 476002985749
11-15 13:59:47.069  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -90, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -77, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -77, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -87, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, 4, -86, 49, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 13:59:47.069  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:59:47.070  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:59:47.070  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:59:47.070  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:59:47.071  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:59:47.071  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:59:47.071  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,11-15 13:59:47.649   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:59:48.651   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 13:59:48.816   928  3116 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 13:59:49.652   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 13:59:52.074  6029  6029 D BtGatt.ScanManager: awakened up at time 481008
,11-15 13:59:52.077  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:52.109  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-15 13:59:52.109  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:52.110  6029  6045 D BtGatt.GattService: current time is 481044354117
11-15 13:59:52.110  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -78, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -93, 61, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 116, -43, -111, -91, -20, -29, 1, -128, -78, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -88, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 13:59:52.110  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 13:59:52.111  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 13:59:52.111  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:59:52.111  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:59:52.112  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 13:59:57.115  6029  6029 D BtGatt.ScanManager: awakened up at time 486049
,11-15 13:59:57.119  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 13:59:57.159  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 13:59:57.159  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 13:59:57.160  6029  6045 D BtGatt.GattService: current time is 486094566488
11-15 13:59:57.160  6029  6045 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -84, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -95, 63, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -87, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -87, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 13:59:57.161  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 13:59:57.161  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 13:59:57.163  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 13:59:57.163  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 13:59:57.164  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 13:59:57.164  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 13:59:59.653   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:00:00.654   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:00:01.656   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:00:02.164  6029  6029 D BtGatt.ScanManager: awakened up at time 491099
11-15 14:00:02.166  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:00:02.218  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:00:02.218  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:00:02.218  6029  6045 D BtGatt.GattService: current time is 491152990224
11-15 14:00:02.219  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -90, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -77, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -87, 44, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -87, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:00:02.219  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:00:02.220  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:00:02.220  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:00:02.220  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:00:02.221  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:00:02.221  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:00:02.221  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:00:02.657   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:00:03.659   624   624 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:00:04.660   624   624 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 14:00:04.677   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 14:00:04.686   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 55
,11-15 14:00:07.223  6029  6029 D BtGatt.ScanManager: awakened up at time 496158
,11-15 14:00:07.226  6029  6048 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:00:07.254  6029  6045 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-15 14:00:07.255  6029  6045 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:00:07.255  6029  6045 D BtGatt.GattService: current time is 496189538390
11-15 14:00:07.255  6029  6045 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -92, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -89, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -91, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:00:07.255  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:00:07.256  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-15 14:00:07.256  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:00:07.256  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:00:07.256  6029  6045 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:00:07.710   928  3129 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-15 14:00:07.715   928  3129 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-15 14:00:08.817   928  3116 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437

```
