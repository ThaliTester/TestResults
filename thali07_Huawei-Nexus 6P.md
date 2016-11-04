#### Test 92300911d00ab7e_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-04 09:57:00.524  3913  4198 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-04 09:57:00.619  3913  4198 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-04 09:57:01.001  5559  5559 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-04 09:57:01.006  5559  5559 D AndroidRuntime: CheckJNI is OFF
11-04 09:57:01.034  5559  5559 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-04 09:57:01.069  5559  5559 I Radio-JNI: register_android_hardware_Radio DONE
11-04 09:57:01.084  5559  5559 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-04 09:57:01.087   927  3099 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-04 09:57:01.106  5559  5559 D AndroidRuntime: Shutting down VM
11-04 09:57:01.115  3925  4390 W SearchService: Abort, client detached.
11-04 09:57:01.127  3925  3925 I HotwordDetector: Closing mic
11-04 09:57:01.128  3925  4177 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1281ba3
11-04 09:57:01.128  3925  4196 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-04 09:57:01.141   927   937 I ActivityManager: Start proc 5568:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-04 09:57:01.207   512  4199 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-04 09:57:01.209   512  4199 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-04 09:57:01.217   512  4199 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-04 09:57:01.217   512  4199 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-04 09:57:01.220   512  2949 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-04 09:57:01.223  3925  4195 I MicroRecognitionRnrImpl: Detection finished
11-04 09:57:01.223  3925  4185 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-04 09:57:01.244  5568  5568 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-04 09:57:01.278  5568  5568 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-04 09:57:01.340  5568  5568 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 5107-5162)
,11-04 09:57:01.341  5568  5568 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 09:57:01.374  5568  5568 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {749417c}
,11-04 09:57:01.374  5568  5568 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 09:57:01.375  5568  5568 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 09:57:01.380  5568  5568 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 09:57:01.382  5568  5568 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 09:57:01.434  5568  5568 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 09:57:01.447  5568  5568 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 09:57:01.447  5568  5568 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 09:57:01.447  5568  5568 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 09:57:01.447  5568  5568 I Adreno  : Build Date                       : 12/06/15
11-04 09:57:01.447  5568  5568 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 09:57:01.447  5568  5568 I Adreno  : Local Branch                     : mybranch17112971
11-04 09:57:01.447  5568  5568 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 09:57:01.447  5568  5568 I Adreno  : Remote Branch                    : NONE
11-04 09:57:01.447  5568  5568 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 09:57:01.510   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8001850:true
,11-04 09:57:01.550   406   406 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[28899]" dev="sockfs" ino=28899 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:01.550   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[28899]" dev="sockfs" ino=28899 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 09:57:01.563  5568  5568 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 09:57:01.572  5568  5568 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 09:57:01.642  5568  5605 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 09:57:01.640  2543  2543 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34182]" dev="sockfs" ino=34182 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:01.640  2543  2543 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34182]" dev="sockfs" ino=34182 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 09:57:01.647  3724  3724 W Binder_9: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30153]" dev="sockfs" ino=30153 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:01.647  3724  3724 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30153]" dev="sockfs" ino=30153 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 09:57:01.649  5568  5592 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 09:57:01.676  5568  5605 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 09:57:01.750   938   938 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32966]" dev="sockfs" ino=32966 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:01.753   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +635ms
,11-04 09:57:01.750   938   938 W Binder_2: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32966]" dev="sockfs" ino=32966 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 09:57:01.756  3588  3588 I Keyboard.Facilitator: onFinishInput()
11-04 09:57:01.754  3102  3102 W Binder_4: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32965]" dev="sockfs" ino=32965 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:01.754  3102  3102 W Binder_4: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32965]" dev="sockfs" ino=32965 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 09:57:01.807  5568  5568 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5568
,11-04 09:57:01.895  5568  5568 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 09:57:02.183  5568  5608 D jxcore_app_log: JniHelper::setJavaVM(0xf517c000), pthread_self() = -584054480
,11-04 09:57:02.196  5568  5608 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-04 09:57:02.196  5568  5608 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-04 09:57:02.196  5568  5608 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-04 09:57:02.196  5568  5608 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-04 09:57:02.196  5568  5608 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-04 09:57:02.197  5568  5608 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@715e1c3 added. We now have 1 listener(s)
,11-04 09:57:02.201  5568  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-04 09:57:02.203  5568  5608 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 09:57:02.203  5568  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 09:57:02.204  5568  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-04 09:57:02.209  5568  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77efabe added. We now have 1 listener(s)
11-04 09:57:02.209  5568  5608 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 09:57:02.215   927  2920 D WifiService: New client listening to asynchronous messages
,11-04 09:57:02.216  5568  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 09:57:02.216  5568  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-04 09:57:02.216  5568  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-04 09:57:02.216  5568  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-04 09:57:02.216  5568  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-04 09:57:02.220  5568  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 09:57:02.220  5568  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 09:57:02.227  5568  5608 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-04 09:57:02.227  5568  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 09:57:02.227  5568  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:02.227  5568  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:02.227  5568  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:02.227  5568  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:02.227  5568  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:02.227  5568  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:02.227  5568  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:02.228  5568  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-04 09:57:02.228  5568  5608 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 09:57:02.229  5568  5608 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-04 09:57:02.510  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:02.517  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:02.523  5568  5568 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-04 09:57:02.820  5568  5577 I art     : Background sticky concurrent mark sweep GC freed 78387(7MB) AllocSpace objects, 17(1496KB) LOS objects, 26% free, 24MB/32MB, paused 1.323ms total 191.642ms
,11-04 09:57:03.028  5568  5616 W jxcore-log: Initializing JXcore engine
,11-04 09:57:03.028  5568  5616 W jxcore-log: JXcore engine is ready
,11-04 09:57:03.054  5616  5616 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12363 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-04 09:57:03.054  5616  5616 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15398]" dev="sockfs" ino=15398 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-04 09:57:03.054  5616  5616 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-04 09:57:03.054  5616  5616 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34152]" dev="sockfs" ino=34152 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-04 09:57:03.062  5568  5616 W jxcore-log: Starting JXcore engine
,11-04 09:57:03.113  5568  5616 W jxcore-log: Platform android
11-04 09:57:03.113  5568  5616 W jxcore-log: 
11-04 09:57:03.114  5568  5616 W jxcore-log: Process ARCH arm
11-04 09:57:03.114  5568  5616 W jxcore-log: 
,11-04 09:57:03.261  5568  5616 I jxcore-log: JXcore Cordova bridge is ready!
11-04 09:57:03.261  5568  5616 I jxcore-log: 
,11-04 09:57:03.261  5568  5616 W jxcore-log: JXcore engine is started
,11-04 09:57:03.269  5568  5608 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-04 09:57:03.277  5568  5568 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-04 09:57:04.659  3522  3522 I ConfigService: onDestroy
,11-04 09:57:06.131   927  3102 I ActivityManager: Killing 5007:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-04 09:57:10.368   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:11.370   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:12.371   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:13.249  5568  5616 I jxcore-log: 2016-11-04 08:57:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-04 09:57:13.249  5568  5616 I jxcore-log: 
,11-04 09:57:13.251  5568  5616 I jxcore-log: 2016-11-04 08:57:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-04 09:57:13.251  5568  5616 I jxcore-log: 
,11-04 09:57:13.256  5568  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 09:57:13.256  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:13.256  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:13.256  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:13.256  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:13.256  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:13.256  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:13.256  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 09:57:13.258  5568  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:13.260  5568  5616 I jxcore-log: 2016-11-04 08:57:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-04 09:57:13.260  5568  5616 I jxcore-log: 
11-04 09:57:13.262  5568  5616 I jxcore-log: 2016-11-04 08:57:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-04 09:57:13.262  5568  5616 I jxcore-log: 
,11-04 09:57:13.372   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:13.522  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 09:57:13.523  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60da1df added. We now have 2 listener(s)
11-04 09:57:13.523  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 09:57:13.523  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 09:57:13.523  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 09:57:13.524  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 09:57:13.524  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9a0e2c added. We now have 2 listener(s)
11-04 09:57:13.524  5568  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 09:57:13.524  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 09:57:13.526  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 09:57:13.529  5568  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 09:57:13.529  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:13.529  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:13.529  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:13.529  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:13.529  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:13.529  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:13.529  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 09:57:13.530  5568  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:13.531  5568  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 09:57:13.531  5568  5616 D ExecuteNativeTests: Running unit tests
11-04 09:57:13.532  5568  5616 D BluetoothAdapter: enable(): BT is already enabled..!
11-04 09:57:13.532   927   937 D WifiService: setWifiEnabled: true pid=5568, uid=10077
,11-04 09:57:13.533   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 09:57:13.540  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:13.544  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:14.304  3925  5618 W CronetSyncConnectionRcs: Upload content type not set.,
,11-04 09:57:14.373   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:14.461  4842  4872 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-04 09:57:14.463  4842  4842 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-04 09:57:14.465   927   938 I ActivityManager: Killing 5353:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-04 09:57:15.373   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 09:57:23.537  5568  5616 I com.test.thalitest.ThaliTestRunner: Running UT
,11-04 09:57:23.604  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 09:57:23.604  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ccdde added. We now have 3 listener(s)
11-04 09:57:23.605  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 09:57:23.605  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 09:57:23.605  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 09:57:23.605  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 09:57:23.605  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc17bbf added. We now have 3 listener(s)
11-04 09:57:23.605  5568  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 09:57:23.606  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 09:57:23.608  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 09:57:23.617  5568  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 09:57:23.617  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:23.617  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:23.617  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:23.617  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:23.617  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:23.617  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:23.617  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 09:57:23.624  5568  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:23.625  5568  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 09:57:23.632  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-04 09:57:23.633  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 09:57:23.633  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 09:57:23.633  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:23.633  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 09:57:23.633  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 09:57:23.634  5568  5616 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-04 09:57:23.634  5568  5616 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 09:57:23.634  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 09:57:23.634  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 09:57:23.634  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 09:57:23.634  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 09:57:23.635  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-04 09:57:23.635  5568  5616 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-04 09:57:23.636  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections,
11-04 09:57:23.638  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-04 09:57:23.638  5568  5616 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 09:57:23.638  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:23.639  5568  5616 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-04 09:57:23.639  5568  5616 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-04 09:57:23.639  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-04 09:57:23.639  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 09:57:23.639  5568  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 09:57:23.639  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 09:57:23.639  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 09:57:23.640  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 09:57:23.641  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 09:57:23.641  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 09:57:23.641  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 09:57:23.641  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 09:57:23.641  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-04 09:57:23.641  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 09:57:23.641  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 09:57:23.641  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 09:57:23.641  5568  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-04 09:57:23.645  5568  5622 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 09:57:23.646  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 09:57:23.647  5568  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 09:57:23.647  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 09:57:23.648  5568  5622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 09:57:23.644  4630  4630 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[27555]" dev="sockfs" ino=27555 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:23.644  4630  4630 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[27555]" dev="sockfs" ino=27555 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 09:57:23.650  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 09:57:23.651  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 09:57:23.651  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 09:57:23.652  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.652  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 09:57:23.652  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 09:57:23.652  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-04 09:57:23.653  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 09:57:23.653  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:23.653  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.653  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.653  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.653  5568  5616 D BluetoothAdapter: STATE_ON
11-04 09:57:23.657  4618  4829 D BtGatt.GattService: registerClient() - UUID=e2c662db-9605-4b25-8d5b-4a4c45dbc862
11-04 09:57:23.658  4618  4677 D BtGatt.GattService: onClientRegistered() - UUID=e2c662db-9605-4b25-8d5b-4a4c45dbc862, clientIf=5
,11-04 09:57:23.659  5568  5579 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-04 09:57:23.661  4618  4679 D BtGatt.AdvertiseManager: message : 0
,11-04 09:57:23.664  4618  4679 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 09:57:23.680  4618  4677 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 09:57:23.689  4618  4677 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 09:57:23.690  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.690  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.690  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-04 09:57:23.690  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.691  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.691  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.691  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.691  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:23.691  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 09:57:23.691  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 09:57:23.691  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.692  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.692  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.692  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:23.692  5568  5616 I io.jxcore.node.ConnectionHelper: start: OK
,11-04 09:57:23.693  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-04 09:57:23.693  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 09:57:23.693  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:23.693  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 09:57:23.693  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 09:57:23.694  5568  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:23.694  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 09:57:23.694  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 09:57:23.694  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 09:57:23.694  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-04 09:57:23.694  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 09:57:23.694  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-04 09:57:23.694  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 09:57:23.697  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 09:57:23.697  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 09:57:23.698  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-04 09:57:23.698  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 09:57:23.698  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 09:57:23.698  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:23.698  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 09:57:24.196  5568  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 09:57:24.196  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-04 09:57:24.196  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-04 09:57:24.196  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 09:57:24.196  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 09:57:24.196  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 09:57:24.196  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 09:57:24.197  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-04 09:57:24.197  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 09:57:24.197  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 09:57:24.197  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 09:57:24.197  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 09:57:24.197  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 09:57:24.197  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 09:57:24.197  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 09:57:24.197  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 09:57:24.197  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-04 09:57:24.198  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 09:57:24.198  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 09:57:24.198  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-04 09:57:24.198  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-04 09:57:24.198  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 09:57:24.198  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 09:57:24.199  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 09:57:24.199  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-04 09:57:24.199  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-04 09:57:24.199  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 09:57:24.199  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 09:57:24.199  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 09:57:24.199  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 09:57:24.199  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-04 09:57:24.199  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 09:57:24.200  5568  5616 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 09:57:24.200  5568  5568 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-04 09:57:24.200  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-04 09:57:24.200  5568  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 09:57:24.200  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 09:57:24.200  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 09:57:24.200  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 09:57:24.201  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 09:57:24.201  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 09:57:24.201  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 09:57:24.201  5568  5622 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 09:57:24.201  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 09:57:24.201  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 09:57:24.202  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 09:57:24.202  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 09:57:24.202  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.202  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.203  5568  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 09:57:24.204  5568  5616 D BluetoothAdapter: STATE_ON
11-04 09:57:24.204  5568  5616 D BluetoothLeScanner: could not find callback wrapper
11-04 09:57:24.205  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 09:57:24.205  5568  5622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 09:57:24.205  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.205  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.205  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 09:57:24.206  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.207  4618  4679 D BtGatt.AdvertiseManager: message : 1
11-04 09:57:24.208  4618  4679 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 09:57:24.226  4618  4677 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-04 09:57:24.226  4618  4677 D BtGatt.GattService: Client app is not null!
,11-04 09:57:24.226  4618  4631 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 09:57:24.227  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 09:57:24.227  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.227  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 09:57:24.227  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.227  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.228  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.228  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 09:57:24.228  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 09:57:24.228  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.228  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.228  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 09:57:24.228  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.229  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.229  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 09:57:24.229  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.229  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.230  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.230  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.230  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.230  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 09:57:24.230  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 09:57:24.231  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 09:57:24.231  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.232  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.232  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.232  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.233  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 09:57:24.233  5568  5568 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 09:57:24.233  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 09:57:24.234  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 09:57:24.234  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 09:57:24.234  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 09:57:24.234  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 09:57:24.234  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 09:57:24.234  5568  5616 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 09:57:24.234  5568  5616 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-04 09:57:24.234  5568  5616 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-04 09:57:24.234  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-04 09:57:24.241  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 09:57:24.241  5568  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 09:57:24.241  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 09:57:24.241  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 09:57:24.242  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 09:57:24.242  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 09:57:24.242  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 09:57:24.242  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 09:57:24.242  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 09:57:24.242  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 09:57:24.242  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-04 09:57:24.242  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 09:57:24.242  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 09:57:24.243  5568  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 09:57:24.244  5568  5625 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 09:57:24.244  4631  4631 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32990]" dev="sockfs" ino=32990 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:24.244  4631  4631 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32990]" dev="sockfs" ino=32990 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:24.247  5568  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 09:57:24.247  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 09:57:24.247  5568  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 09:57:24.247  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 09:57:24.250  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 09:57:24.251  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 09:57:24.251  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 09:57:24.253  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.253  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 09:57:24.254  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 09:57:24.254  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-04 09:57:24.254  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 09:57:24.254  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.254  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.254  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.254  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.255  5568  5616 D BluetoothAdapter: STATE_ON
11-04 09:57:24.257  4618  4837 D BtGatt.GattService: registerClient() - UUID=3193c950-8453-4cd2-b5d0-1883c2309be7
11-04 09:57:24.258  4618  4677 D BtGatt.GattService: onClientRegistered() - UUID=3193c950-8453-4cd2-b5d0-1883c2309be7, clientIf=5
11-04 09:57:24.258  5568  5607 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-04 09:57:24.259  4618  4679 D BtGatt.AdvertiseManager: message : 0
11-04 09:57:24.261  4618  4679 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 09:57:24.272  4618  4677 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-04 09:57:24.278  4618  4677 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-04 09:57:24.279  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.279  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.279  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 09:57:24.279  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.279  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.279  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.279  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.279  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.280  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 09:57:24.281  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 09:57:24.281  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.282  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.282  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.282  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.282  5568  5616 I io.jxcore.node.ConnectionHelper: start: OK
11-04 09:57:24.283  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 09:57:24.283  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.283  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:24.283  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 09:57:24.283  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.283  5568  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:24.283  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.283  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 09:57:24.283  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 09:57:24.283  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.284  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.284  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-04 09:57:24.285  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.287  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.287  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 09:57:24.287  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.287  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.288  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.288  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:24.288  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 09:57:24.787  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-04 09:57:24.787  5568  5616 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 09:57:24.787  5568  5616 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-04 09:57:24.787  5568  5616 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 09:57:24.787  5568  5616 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-04 09:57:24.788  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-04 09:57:24.788  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-04 09:57:24.788  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-04 09:57:24.788  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-04 09:57:24.788  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-04 09:57:24.788  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-04 09:57:24.788  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-04 09:57:24.788  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-04 09:57:24.788  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-04 09:57:24.788  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-04 09:57:24.788  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.789  5568  5568 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-04 09:57:24.791  4618  4679 D BtGatt.AdvertiseManager: message : 1
,11-04 09:57:24.792  4618  4679 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 09:57:24.807  4618  4677 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-04 09:57:24.807  4618  4677 D BtGatt.GattService: Client app is not null!
,11-04 09:57:24.808  4618  4837 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 09:57:24.809  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 09:57:24.810  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.810  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 09:57:24.810  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.810  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:24.810  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 09:57:24.810  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.810  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 09:57:24.810  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 09:57:24.811  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-04 09:57:24.811  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 09:57:24.811  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.811  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.811  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.812  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:24.813  5568  5616 D BluetoothAdapter: STATE_ON
,11-04 09:57:24.817  4618  4631 D BtGatt.GattService: registerClient() - UUID=b66f76cd-c1de-4fa7-af7d-fae750770a5b
,11-04 09:57:24.817  4618  4677 D BtGatt.GattService: onClientRegistered() - UUID=b66f76cd-c1de-4fa7-af7d-fae750770a5b, clientIf=5
11-04 09:57:24.819  5568  5607 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-04 09:57:24.820  4618  4679 D BtGatt.AdvertiseManager: message : 0
,11-04 09:57:24.823  4618  4679 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 09:57:24.834  4618  4677 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 09:57:24.840  4618  4677 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 09:57:24.841  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.841  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.841  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 09:57:24.841  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.841  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:24.841  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.841  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.841  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.841  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 09:57:24.841  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 09:57:24.842  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 09:57:24.842  5568  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 09:57:24.842  5568  5616 I io.jxcore.node.ConnectionHelper: start: OK
11-04 09:57:24.842  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-04 09:57:24.842  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:24.842  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 09:57:24.842  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.842  5568  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:24.842  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.842  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 09:57:24.842  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 09:57:24.842  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-04 09:57:24.843  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.843  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:24.843  5568  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 09:57:24.843  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-04 09:57:24.843  5568  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 09:57:24.843  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 09:57:24.843  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 09:57:24.843  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 09:57:24.843  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 09:57:24.843  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 09:57:24.844  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-04 09:57:24.844  5568  5625 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 09:57:24.844  5568  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 09:57:24.844  5568  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 09:57:24.844  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 09:57:24.844  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 09:57:24.844  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 09:57:24.844  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 09:57:24.844  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 09:57:24.844  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.844  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.845  5568  5616 D BluetoothAdapter: STATE_ON
11-04 09:57:24.846  5568  5616 D BluetoothLeScanner: could not find callback wrapper
11-04 09:57:24.846  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-04 09:57:24.846  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.846  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.846  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 09:57:24.846  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.847  4618  4679 D BtGatt.AdvertiseManager: message : 1
11-04 09:57:24.847  4618  4679 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 09:57:24.854  4618  4677 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-04 09:57:24.854  4618  4677 D BtGatt.GattService: Client app is not null!
,11-04 09:57:24.855  4618  4631 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 09:57:24.855  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 09:57:24.855  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.855  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-04 09:57:24.855  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.856  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.856  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.856  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 09:57:24.856  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 09:57:24.856  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.856  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.856  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 09:57:24.856  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.857  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.857  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 09:57:24.857  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.857  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.857  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:24.857  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.857  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.857  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 09:57:24.858  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 09:57:24.858  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 09:57:24.858  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.859  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.859  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.859  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.860  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 09:57:24.860  5568  5568 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 09:57:24.860  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 09:57:24.860  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 09:57:24.860  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 09:57:24.860  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 09:57:24.860  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 09:57:24.861  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-04 09:57:24.863  5568  5616 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-04 09:57:24.864  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-04 09:57:24.864  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-04 09:57:24.866  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-04 09:57:24.866  5568  5616 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-04 09:57:24.867  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-04 09:57:24.867  5568  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-04 09:57:24.868  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-04 09:57:24.868  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 09:57:24.868  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 09:57:24.868  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 09:57:24.868  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 09:57:24.868  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 09:57:24.868  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 09:57:24.868  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 09:57:24.868  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 09:57:24.868  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 09:57:24.868  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 09:57:24.869  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 09:57:24.869  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 09:57:24.869  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-04 09:57:24.870  5568  5616 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 09:57:24.870  5568  5616 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 09:57:24.873  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-04 09:57:24.873  5568  5616 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-04 09:57:24.874  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-04 09:57:24.875  5568  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-04 09:57:24.875  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-04 09:57:24.876  5568  5616 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-04 09:57:24.876  5568  5616 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-04 09:57:24.876  5568  5616 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,11-04 09:57:24.876  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-04 09:57:24.876  5568  5616 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-04 09:57:24.876  5568  5616 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 09:57:24.876  5568  5616 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,11-04 09:57:24.876  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 09:57:24.876  5568  5616 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-04 09:57:24.876  5568  5616 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 09:57:24.876  5568  5616 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 09:57:24.876  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 09:57:24.876  5568  5616 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-04 09:57:24.877  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-04 09:57:24.877  5568  5616 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 09:57:24.877  5568  5616 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-04 09:57:24.877  5568  5616 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,11-04 09:57:24.877  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-04 09:57:24.878  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 09:57:24.878  5568  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 09:57:24.878  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 09:57:24.878  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 09:57:24.879  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 09:57:24.880  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 09:57:24.880  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-04 09:57:24.880  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 09:57:24.880  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 09:57:24.880  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 09:57:24.880  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-04 09:57:24.880  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 09:57:24.880  5568  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 09:57:24.880  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 09:57:24.881  5568  5629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 09:57:24.880  4838  4838 W Binder_5: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33001]" dev="sockfs" ino=33001 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:24.883  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 09:57:24.883  5568  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-04 09:57:24.883  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 09:57:24.884  5568  5629 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 09:57:24.880  4838  4838 W Binder_5: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33001]" dev="sockfs" ino=33001 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 09:57:24.887  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 09:57:24.888  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 09:57:24.888  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 09:57:24.889  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.889  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 09:57:24.890  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 09:57:24.890  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-04 09:57:24.890  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 09:57:24.890  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.890  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.890  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.890  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.891  5568  5616 D BluetoothAdapter: STATE_ON
,11-04 09:57:24.893  4618  4630 D BtGatt.GattService: registerClient() - UUID=9691fffe-5cf1-48f6-9e50-51e3ff241391
11-04 09:57:24.893  4618  4677 D BtGatt.GattService: onClientRegistered() - UUID=9691fffe-5cf1-48f6-9e50-51e3ff241391, clientIf=5
11-04 09:57:24.893  5568  5578 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-04 09:57:24.894  4618  4679 D BtGatt.AdvertiseManager: message : 0
,11-04 09:57:24.898  4618  4679 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 09:57:24.908  4618  4677 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 09:57:24.914  4618  4677 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 09:57:24.915  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:24.915  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.915  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 09:57:24.916  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.916  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.916  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.916  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.916  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.916  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 09:57:24.917  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 09:57:24.917  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.918  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.918  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.918  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:24.918  5568  5616 I io.jxcore.node.ConnectionHelper: start: OK
,11-04 09:57:24.918  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 09:57:24.918  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.919  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:24.919  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 09:57:24.919  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.919  5568  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:24.919  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.919  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 09:57:24.919  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 09:57:24.919  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.919  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.919  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-04 09:57:24.919  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 09:57:24.921  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.921  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 09:57:24.922  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-04 09:57:24.922  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.922  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 09:57:24.922  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:24.922  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 09:57:25.419  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 09:57:25.420  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 09:57:25.420  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-04 09:57:25.420  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 09:57:25.420  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 09:57:25.421  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 09:57:25.421  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 09:57:25.421  5568  5629 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 09:57:25.421  5568  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-04 09:57:25.421  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 09:57:25.421  5568  5629 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 09:57:25.422  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 09:57:25.422  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ccdde removed from the list
11-04 09:57:25.422  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 09:57:25.422  5568  5568 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-04 09:57:25.422  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 09:57:25.422  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 09:57:25.422  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 09:57:25.422  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 09:57:25.422  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 09:57:25.423  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.423  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.425  5568  5616 D BluetoothAdapter: STATE_ON
11-04 09:57:25.426  5568  5616 D BluetoothLeScanner: could not find callback wrapper
11-04 09:57:25.426  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 09:57:25.426  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.426  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.426  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 09:57:25.427  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.429  4618  4679 D BtGatt.AdvertiseManager: message : 1
11-04 09:57:25.430  4618  4679 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 09:57:25.444  4618  4677 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-04 09:57:25.444  4618  4677 D BtGatt.GattService: Client app is not null!
,11-04 09:57:25.445  4618  4837 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 09:57:25.446  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 09:57:25.447  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:25.447  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-04 09:57:25.447  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.447  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.447  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.447  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 09:57:25.448  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 09:57:25.448  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.448  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:25.448  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 09:57:25.448  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.450  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.451  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 09:57:25.451  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.451  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.451  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.451  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.452  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.452  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 09:57:25.452  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-04 09:57:25.454  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-04 09:57:25.454  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.456  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.457  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:25.457  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:25.457  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc17bbf removed from the list
11-04 09:57:25.457  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 09:57:25.457  5568  5616 D io.jxcore.node.ConnectivityMonitor: stop
11-04 09:57:25.457  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 09:57:25.457  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 09:57:25.458  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 09:57:25.959  5568  5568 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 09:57:28.242   927  2914 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 09:57:30.461  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-04 09:57:30.465  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-04 09:57:30.465  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 09:57:30.467  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 09:57:30.468  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-04 09:57:30.468  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 09:57:30.468  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 09:57:30.469  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-04 09:57:30.469  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 09:57:30.469  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-04 09:57:30.469  5568  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 09:57:30.471  5568  5630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 09:57:30.474  4630  4630 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32412]" dev="sockfs" ino=32412 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 09:57:30.474  4630  4630 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32412]" dev="sockfs" ino=32412 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:30.474  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-04 09:57:30.475  5568  5616 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-04 09:57:30.476  5568  5616 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 09:57:30.476  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 09:57:30.476  5568  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 09:57:30.476  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 09:57:30.476  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 09:57:30.478  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-04 09:57:30.484  5568  5616 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
11-04 09:57:30.485  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 09:57:30.485  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 09:57:30.485  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 09:57:30.485  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 09:57:30.485  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-04 09:57:30.485  5568  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 09:57:30.485  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 09:57:30.485  5568  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 09:57:30.485  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 09:57:30.485  5568  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 09:57:30.486  5568  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ccdde not in the list
11-04 09:57:30.486  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 09:57:30.486  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 09:57:30.486  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 09:57:30.486  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 09:57:30.486  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 09:57:30.486  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 09:57:30.486  5568  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 09:57:30.486  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 09:57:30.486  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 09:57:30.487  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:30.489  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:30.489  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 09:57:30.489  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:30.490  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:30.490  5568  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc17bbf not in the list
11-04 09:57:30.490  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 09:57:30.490  5568  5616 D io.jxcore.node.ConnectivityMonitor: stop
11-04 09:57:30.490  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 09:57:30.490  5568  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 09:57:30.490  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 09:57:30.490  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-04 09:57:30.495  5568  5616 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-04 09:57:30.495  5568  5616 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-04 09:57:30.495  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 09:57:30.495  5568  5616 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-04 09:57:30.495  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 09:57:30.496  5568  5616 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-04 09:57:30.496  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-04 09:57:30.497  5568  5616 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-04 09:57:30.498  5568  5616 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-04 09:57:30.499  5568  5616 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-04 09:57:30.500  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-04 09:57:30.500  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-04 09:57:30.501  5568  5616 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,11-04 09:57:30.502  5568  5616 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-04 09:57:30.502  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 09:57:30.503  5568  5616 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-04 09:57:30.503  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 09:57:30.503  5568  5616 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-04 09:57:30.503  5568  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-04 09:57:30.504  5568  5616 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-04 09:57:30.504  5568  5616 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-04 09:57:30.504  5568  5616 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-04 09:57:30.505  5568  5616 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-04 09:57:30.505  5568  5616 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-04 09:57:30.505  5568  5616 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-04 09:57:30.505  5568  5616 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-04 09:57:30.505  5568  5616 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-04 09:57:30.506  5568  5616 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-04 09:57:30.506  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 09:57:30.506  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@696d2af added. We now have 3 listener(s)
11-04 09:57:30.507  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 09:57:30.508  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 09:57:30.508  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 09:57:30.508  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 09:57:30.508  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c336bc added. We now have 3 listener(s)
11-04 09:57:30.508  5568  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 09:57:30.508  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 09:57:30.510  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 09:57:30.515  5568  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 09:57:30.515  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:30.515  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:30.515  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:30.515  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:30.515  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:30.515  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:30.515  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 09:57:30.517  5568  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:30.517  5568  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 09:57:30.518  5568  5616 D BluetoothAdapter: enable(): BT is already enabled..!
,11-04 09:57:30.518   927  3762 D WifiService: setWifiEnabled: true pid=5568, uid=10077
,11-04 09:57:30.519   927  3762 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-04 09:57:30.519  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:30.520  5568  5616 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-04 09:57:30.522  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:30.522  5568  5616 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-04 09:57:30.523  5568  5616 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-04 09:57:30.526   927  3724 D WifiService: setWifiEnabled: false pid=5568, uid=10077
,11-04 09:57:30.526   927  3724 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 09:57:30.528   927  2914 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-04 09:57:30.528   927  2914 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-04 09:57:30.528   927  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 09:57:30.529   927  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 09:57:30.537   927  5327 D DhcpClient: Clearing IP address
,11-04 09:57:30.537   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-04 09:57:30.545   507   920 D CommandListener: Setting iface cfg
,11-04 09:57:30.546   927  5328 D DhcpClient: Receive thread stopped
,11-04 09:57:30.550   927  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-04 09:57:30.550   927  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-04 09:57:30.551   537   537 E Parcel  : Reading a NULL string not supported here.
11-04 09:57:30.554   927   927 D RttService: SCAN_AVAILABLE : 1
11-04 09:57:30.554   927  3028 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 09:57:30.556  3522  5394 V NativeCrypto: Read error: ssl=0x7f5cad8a80: I/O error during system call, Connection timed out
,11-04 09:57:30.558   927  2921 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-04 09:57:30.558  3522  5394 V NativeCrypto: SSL shutdown failed: ssl=0x7f5cad8a80: I/O error during system call, Broken pipe
,11-04 09:57:30.560  3715  3824 W QCNEJ   : |CORE| network lost: 100
11-04 09:57:30.561  3715  3824 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-04 09:57:30.570   927  2914 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-04 09:57:30.575   927  3099 I ActivityManager: Killing 5366:com.android.chrome/u0a39 (adj 15): empty #17
,11-04 09:57:30.580   927  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 09:57:30.588   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 09:57:30.606   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 09:57:30.606   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-04 09:57:30.606   507   920 D TetherController: Setting IP forward enable = 0
11-04 09:57:30.607   927  2921 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-04 09:57:30.607   927  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 09:57:30.615   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-04 09:57:30.616   927  2914 D DhcpClient: doQuit
11-04 09:57:30.616   927  2914 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 09:57:30.616   927  5327 D DhcpClient: onQuitting
11-04 09:57:30.617  5231  5231 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fd3f5d7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-04 09:57:30.618  3387  3387 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-04 09:57:30.621  3925  3925 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-04 09:57:30.622  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:30.622  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:30.622  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:30.622  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:30.622  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:30.622  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:30.622  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:30.622  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:30.627  3913  3913 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 09:57:30.627  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:30.630  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:30.630  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:30.630  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:30.630  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 09:57:30.630  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:30.630  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:30.630  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:30.630  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:30.633  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 09:57:30.636  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:30.636  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:30.636  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:30.636  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 09:57:30.636  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:30.636  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:30.636  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:30.636  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 09:57:30.638  3913  3913 D SystemUpdateService: onCreate
,11-04 09:57:30.640  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 09:57:30.641  3387  3387 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 09:57:30.644  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:30.644  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:30.644  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:30.644  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 09:57:30.644  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:30.644  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:30.644  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:30.644  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 09:57:30.646  3913  3913 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-04 09:57:30.646  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 09:57:30.647  3387  3387 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-04 09:57:30.647  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:30.648  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:30.654  3913  3913 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 09:57:30.660  3913  4179 I iu.UploadsManager: num queued entries: 0
,11-04 09:57:30.661  3913  4179 I iu.UploadsManager: num updated entries: 0
,11-04 09:57:30.662  3913  5648 I SystemUpdateService: active receiver: enabled
,11-04 09:57:30.664  3913  3913 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 09:57:30.666  3913  3913 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-04 09:57:30.669  3913  5648 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-04 09:57:30.670  3913  4179 I iu.SyncManager: NEXT; no task
,11-04 09:57:30.671  3913  5648 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-04 09:57:30.671  3913  5648 I SystemUpdateService: now status is 0 (complete)
11-04 09:57:30.671   507   920 E Netd    : netlink response contains error (No such file or directory)
11-04 09:57:30.672   927  2921 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-04 09:57:30.675  3913  5648 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-04 09:57:30.675  3913  5648 I SystemUpdateService: file has been verified
11-04 09:57:30.675  3913  5648 I SystemUpdateService: OTA package size = 21989297
,11-04 09:57:30.677   927  3099 I ActivityManager: Start proc 5651:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-04 09:57:30.684  3913  5648 I SystemUpdateService: showing system update notification
,11-04 09:57:30.694  3387  3387 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 09:57:30.694  3913  3913 D SystemUpdateService: onDestroy
11-04 09:57:30.695   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 09:57:30.706  3387  3387 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 09:57:30.713  5651  5651 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-04 09:57:30.715  5651  5651 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 09:57:30.722  5651  5651 D SprintDMHelper: simOperator: 
,11-04 09:57:30.722  5651  5651 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 09:57:30.735   927  3102 I ActivityManager: Start proc 5663:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-04 09:57:30.739   927  3102 I ActivityManager: Killing 4396:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-04 09:57:30.810   927  2914 D wifi    : In wifi stop Hal
,11-04 09:57:30.810   927  2914 D wifi    : halHandle = 0x7f5b1b7680, mVM = 0x7f7734d140, mCls = 0x100a02
11-04 09:57:30.810   927  3385 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 09:57:30.811  4463  4463 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 09:57:30.811   927  3385 D WifiHAL : Got a signal to exit!!!
11-04 09:57:30.811   927  3385 I WifiHAL : Exit wifi_event_loop
11-04 09:57:30.811   927  2914 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-04 09:57:30.811   927  2914 E WifiHAL : Event processing terminated
11-04 09:57:30.811   927  2914 D wifi    : In wifi cleaned up handler
11-04 09:57:30.812   927  2914 I WifiHAL : Internal cleanup completed
11-04 09:57:30.813  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:30.815  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:30.816  3681  4146 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 09:57:30.816  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:30.831   927  3385 D wifi    : set interface wlan0 flags (DOWN)
,11-04 09:57:30.832   927  2914 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 09:57:30.837   927  3536 I ActivityManager: Start proc 5678:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-04 09:57:30.839   927  3536 I ActivityManager: Killing 5076:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-04 09:57:30.875  5678  5678 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-04 09:57:30.881   927   938 I ActivityManager: Killing 5396:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-04 09:57:30.990  5568  5568 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 09:57:31.030  5568  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:31.032   927   937 D WifiService: setWifiEnabled: true pid=5568, uid=10077
11-04 09:57:31.032   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 09:57:31.038   507   920 D SoftapController: Softap fwReload - Ok
,11-04 09:57:31.040   927   944 D Tethering: InitialState.processMessage what=4
,11-04 09:57:31.041   507   920 D CommandListener: Setting iface cfg
11-04 09:57:31.042   507   920 D CommandListener: Trying to bring down wlan0
,11-04 09:57:31.044   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-04 09:57:31.047   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 09:57:31.048   927  2914 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 09:57:31.537   927  3149 D WifiService: setWifiEnabled: true pid=5568, uid=10077
11-04 09:57:31.539   927  3149 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 09:57:31.662   927  2914 D wifi    : set interface wlan0 flags (UP)
,11-04 09:57:31.662   927  2914 I WifiHAL : Initializing wifi
,11-04 09:57:31.663   927  2914 I WifiHAL : Creating socket
11-04 09:57:31.666   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 09:57:31.672   927  2914 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-04 09:57:31.672   927  2914 D wifi    : Did set static halHandle = 0x7f5b1b7680
11-04 09:57:31.672   927  2914 D wifi    : halHandle = 0x7f5b1b7680, mVM = 0x7f7734d140, mCls = 0x1014ea
11-04 09:57:31.673   927  2914 D wifi    : array field set
11-04 09:57:31.673   927  2914 I WifiNative-HAL: interface[0] = wlan0
11-04 09:57:31.675   927  5696 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546989373056
11-04 09:57:31.675   927  5696 D wifi    : waitForHalEvents called, vm = 0x7f7734d140, obj = 0x1014ea, env = 0x7f5c2bd500
,11-04 09:57:31.691   507   920 D TetherController: Setting IP forward enable = 0
,11-04 09:57:31.737  5697  5697 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 09:57:31.777   927  2914 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-04 09:57:31.777   927  2914 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-04 09:57:31.780  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:31.782  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:31.783  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:31.803  5697  5697 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 09:57:31.813  5697  5697 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 09:57:31.814  5697  5697 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 09:57:32.042   927  3784 D WifiService: setWifiEnabled: true pid=5568, uid=10077
,11-04 09:57:32.043   927  3784 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 09:57:32.546   927  3724 D WifiService: setWifiEnabled: true pid=5568, uid=10077
,11-04 09:57:32.546   927  3724 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 09:57:32.795   927  2914 D WifiConfigStore: Loading config and enabling all networks 
,11-04 09:57:32.802  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:32.802  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:32.802  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:32.802  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:32.802  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:32.802  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:32.802  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:32.802  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:32.808  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:32.815  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:32.815  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:32.815  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:32.815  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:32.815  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:32.815  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:32.815  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:32.815  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:32.819  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:32.828  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:32.828  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:32.828  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:32.828  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:32.828  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:32.828  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:32.828  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:32.828  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:32.831  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:32.839   927  2914 D WifiConfigStore: loaded 0 passpoint configs
,11-04 09:57:32.840   927  2914 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-04 09:57:32.841   927  2914 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-04 09:57:32.842   927  2914 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-04 09:57:32.842   927  2914 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-04 09:57:32.843   927  2914 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-04 09:57:32.844   927  2914 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 09:57:32.844   927  2914 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 09:57:32.844   927  2914 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 09:57:32.844   927  2914 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-04 09:57:32.845   927  2914 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 09:57:32.845   927  2914 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 09:57:32.845   927  2914 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 09:57:32.848   927  2914 D WifiNative-HAL: Setting external_sim to 1
,11-04 09:57:32.848  4463  4463 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 09:57:32.849   927  2914 D wifi    : setting dfs flag to true, 0x7f5c308ce0
,11-04 09:57:32.849   927  2914 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 09:57:32.850   927  2914 D wifi    : setting scan oui 0x7f5c308ce0
11-04 09:57:32.850   927  2914 D WifiHAL : Sending mac address OUI
,11-04 09:57:32.854   927  2914 E native  : do suspend false
,11-04 09:57:32.861   927  2914 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-04 09:57:32.862   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-04 09:57:32.862   927   927 D RttService: SCAN_AVAILABLE : 3
,11-04 09:57:32.863   927  3028 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-04 09:57:32.863   507   920 D CommandListener: Setting iface cfg
,11-04 09:57:32.867   927  2898 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-04 09:57:32.867   927  2898 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 09:57:32.876   927  2898 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 09:57:32.881   927  2898 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
11-04 09:57:32.881   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=106702 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-04 09:57:33.053  5568  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:33.067  4618  4673 D BluetoothAdapterState: Current state: ON, message: 23
11-04 09:57:33.067  4618  4673 D BluetoothAdapterProperties: Setting state to 13
11-04 09:57:33.067  4618  4673 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 09:57:33.069  4618  4673 D BluetoothAdapterProperties: onBluetoothDisable()
,11-04 09:57:33.070  4618  4673 I BluetoothAdapterState: Entering PendingCommandState
,11-04 09:57:33.072  4618  4618 D BluetoothMapService: onReceive
,11-04 09:57:33.072  4618  4618 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-04 09:57:33.072  4618  4618 D BluetoothMapService: STATE_TURNING_OFF
11-04 09:57:33.073  4618  4618 D BluetoothMapService: MAP Service closeService in
11-04 09:57:33.073  4618  4618 D BluetoothMapMasInstance0: MAP Service shutdown
,11-04 09:57:33.073  4618  4618 D ObexServerSockets0: shutdown(block = true)
11-04 09:57:33.075  4618  4618 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 09:57:33.075  4618  4841 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 09:57:33.076  4618  4840 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-04 09:57:33.077  4618  4826 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 09:57:33.079  4618  4618 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 09:57:33.083  4618  4618 I BtOppRfcommListener: stopping Accept Thread
11-04 09:57:33.084  4618  5245 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 09:57:33.084  4618  5245 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-04 09:57:33.089  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:33.089  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:33.089  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:33.089  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:33.089  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:33.089  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 09:57:33.089  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:33.089  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:33.089  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 09:57:33.091  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:33.091  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:33.094  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 09:57:33.094  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:33.094  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:33.094  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:33.094  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:33.094  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 09:57:33.094  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:33.094  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:33.094  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 09:57:33.096  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:33.096  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 09:57:33.097   927   940 I ActivityManager: Start proc 5703:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-04 09:57:33.098  4618  4677 D BluetoothAdapterProperties: Scan Mode:20
,11-04 09:57:33.098  4618  4673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 09:57:33.099  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:33.099  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:33.099  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:33.099  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:33.099  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:33.099  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 09:57:33.099  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:33.099  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:33.099  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 09:57:33.100  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:33.101  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:33.103  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:33.106  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:33.107  4618  4618 D HeadsetService: Received stop request...Stopping profile...
11-04 09:57:33.109  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:33.111   927   927 D BluetoothHeadset: Proxy object disconnected
,11-04 09:57:33.111   927   927 D BluetoothHeadset: Proxy object disconnected
11-04 09:57:33.112  3753  3771 D BluetoothHeadset: Proxy object disconnected
11-04 09:57:33.112  4618  4618 D A2dpService: Received stop request...Stopping profile...
,11-04 09:57:33.112   927   927 D BluetoothHeadset: Proxy object disconnected
11-04 09:57:33.112  4618  4832 D A2dpStateMachine: Exit Disconnected: -1
11-04 09:57:33.112  3074  3097 D BluetoothHeadset: Proxy object disconnected
11-04 09:57:33.113  3074  3074 D HeadsetProfile: Bluetooth service disconnected
11-04 09:57:33.114  3074  3074 D BluetoothA2dp: Proxy object disconnected
11-04 09:57:33.114   927   927 D BluetoothA2dp: Proxy object disconnected
11-04 09:57:33.115  4618  4618 D HidService: Received stop request...Stopping profile...
11-04 09:57:33.115  4618  4618 D HidService: Stopping Bluetooth HidService
11-04 09:57:33.116  3074  3074 D BluetoothInputDevice: Proxy object disconnected
,11-04 09:57:33.116  3074  3074 D HidProfile: Bluetooth service disconnected
11-04 09:57:33.116  4618  4618 D HealthService: Received stop request...Stopping profile...
11-04 09:57:33.117  4618  4618 D PanService: Received stop request...Stopping profile...
11-04 09:57:33.118  3074  3074 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 09:57:33.118  3074  3074 D PanProfile: Bluetooth service disconnected
,11-04 09:57:33.119  4618  4618 D BluetoothMapService: Received stop request...Stopping profile...
,11-04 09:57:33.119  4618  4618 D BluetoothMapService: stop()
11-04 09:57:33.120  4618  4618 D BluetoothMapAppObserver: deinitObservers()
11-04 09:57:33.120  4618  4618 D BluetoothMapAppObserver: removeReceiver()
11-04 09:57:33.121  3074  3074 D BluetoothMap: Proxy object disconnected
11-04 09:57:33.121  3074  3074 D MapProfile: Bluetooth service disconnected
11-04 09:57:33.121  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:33.121  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:33.121  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 09:57:33.121  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:33.122  4618  4618 D SapService: Received stop request...Stopping profile...
11-04 09:57:33.122  4618  4618 V SapService: stop()
,11-04 09:57:33.125  4618  4618 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-04 09:57:33.126  4618  4618 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 09:57:33.126  4618  4677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 09:57:33.127  4618  4809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 09:57:33.127  4618  4809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 09:57:33.127  4618  4809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 09:57:33.127  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:33.127  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:33.127  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:33.127  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:33.128  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:33.128  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:33.128  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 09:57:33.128  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:33.128  4618  4618 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 09:57:33.128  4618  4618 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 09:57:33.128  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:33.128  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:33.129  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:33.129  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:33.129  4618  4618 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 09:57:33.129  4618  4618 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 09:57:33.129  4618  4677 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 09:57:33.129  4618  4677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 09:57:33.129  4618  4677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 09:57:33.129  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:33.129  4618  4809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 09:57:33.129  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:33.129  4618  4677 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 09:57:33.129  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:33.129  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:33.129  4618  4809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 09:57:33.130  4618  4618 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 09:57:33.130  4618  4618 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-04 09:57:33.130  4618  4809 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 09:57:33.130  4618  4809 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 09:57:33.130  4618  4809 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 09:57:33.130  4618  4809 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 09:57:33.131  4618  4618 D BluetoothMapService: MAP Service closeService in
11-04 09:57:33.131  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:33.131  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:33.131  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:33.131  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:33.131  4618  4618 D BluetoothMapService: cleanup()
11-04 09:57:33.131  4618  4618 D BluetoothMapService: MAP Service closeService in
11-04 09:57:33.131  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:33.131  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:33.131  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:33.131  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:33.132  4618  4673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 09:57:33.132  4618  4673 D BluetoothAdapterProperties: Setting state to 15
11-04 09:57:33.132  4618  4673 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 09:57:33.133  4618  4673 I BluetoothAdapterState: Entering BleOnState
11-04 09:57:33.132   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 09:57:33.133  3074  3908 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 09:57:33.134  3074  3087 D BluetoothMap: onBluetoothStateChange: up=false
11-04 09:57:33.134  3074  3097 D BluetoothPan: onBluetoothStateChange on: false
11-04 09:57:33.135  3753  3952 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 09:57:33.135  3074  3908 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 09:57:33.136  3074  3087 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 09:57:33.137   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 09:57:33.137   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 09:57:33.137   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 09:57:33.137  3074  3097 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-04 09:57:33.143  4618  4673 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-04 09:57:33.143  4618  4673 D BluetoothAdapterProperties: Setting state to 16
11-04 09:57:33.143  4618  4673 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-04 09:57:33.149  4618  4673 D BluetoothAdapterProperties: onBleDisable
,11-04 09:57:33.150  4618  4673 I BluetoothAdapterState: Entering PendingCommandState
11-04 09:57:33.150  4618  4674 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 09:57:33.151  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:33.151  4618  4677 D BluetoothAdapterProperties: Scan Mode:20
11-04 09:57:33.151  4618  4809 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 09:57:33.151  4618  4809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 09:57:33.154  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:33.156  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:33.158  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:33.159  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:33.163  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:33.173  5703  5703 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-04 09:57:33.184  5703  5703 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 09:57:33.189   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5441ce6:true
,11-04 09:57:33.189  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 09:57:33.202   927  3716 I ActivityManager: Start proc 5715:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-04 09:57:33.214  5703  5703 D LocalBluetoothProfileManager: Adding local MAP profile
,11-04 09:57:33.217  5703  5703 D BluetoothMap: Create BluetoothMap proxy object
,11-04 09:57:33.232  5703  5703 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-04 09:57:33.239  5715  5715 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-04 09:57:33.250  5703  5703 D DockEventReceiver: finishStartingService: stopping service
,11-04 09:57:33.252   927  3537 I ActivityManager: Killing 5231:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-04 09:57:33.362  4618  4677 I bt_hci  : shut_down
,11-04 09:57:33.366  4618  4681 D bt_hwcfg: hw_epilog_process
,11-04 09:57:33.367  4618  4681 I bt_vendor: low_power_mode_cb
11-04 09:57:33.369  4618  4681 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-04 09:57:33.369  4618  4681 I bt_vendor: epilog_cb
11-04 09:57:33.369  4618  4681 I bt_hci  : epilog_finished_callback
,11-04 09:57:33.372  4618  4677 I bt_hci_h4: hal_close
,11-04 09:57:33.372  4618  4677 I bt_userial_vendor: device fd = 54 close
,11-04 09:57:33.456  5715  5715 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 09:57:33.456  5715  5715 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 09:57:33.456  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 09:57:33.457  5715  5715 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 09:57:33.457  5715  5715 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 09:57:33.457  5715  5715 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.k.d(PG:583)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 09:57:33.457  5715  5715 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 09:57:33.457  5715  5715 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 09:57:33.457  5715  5715 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 09:57:33.457  5715  5715 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 09:57:33.461  5703  5703 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 09:57:33.467  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 09:57:33.473  5703  5703 D DockEventReceiver: finishStartingService: stopping service
11-04 09:57:33.476  4618  4674 D bt_stack_manager: event_shut_down_stack finished.
11-04 09:57:33.477  4618  4673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-04 09:57:33.479  4618  4673 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-04 09:57:33.479  4618  4618 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 09:57:33.479  4618  4618 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 09:57:33.480  4618  4618 D BtGatt.GattService: stop()
11-04 09:57:33.480  4618  4618 D BtGatt.AdvertiseManager: advertise clients cleared
11-04 09:57:33.481  4618  4618 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:33.481  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:33.481  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:33.482  4618  4618 V BluetoothAdapterState: isBleTurningOff()=true
11-04 09:57:33.482  4618  4673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-04 09:57:33.482  4618  4673 D BluetoothAdapterProperties: Setting state to 10
11-04 09:57:33.482  4618  4673 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 09:57:33.483  4618  4673 I BluetoothAdapterState: Entering OffState
11-04 09:57:33.483   927   938 I ActivityManager: Killing 3832:com.android.providers.calendar/u0a1 (adj 15): empty #17
11-04 09:57:33.484   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-04 09:57:33.524  4618  4618 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-04 09:57:33.524  4618  4618 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 09:57:33.524  4618  4618 I BluetoothServiceJni: cleanupNative: return from cleanup
11-04 09:57:33.525  4618  4674 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-04 09:57:33.530  4618  4618 I art     : System.exit called, status: 0
11-04 09:57:33.530  4618  4618 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 09:57:33.563  5568  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:33.565   380   380 E lowmemorykiller: Error writing /proc/4618/oom_score_adj; errno=22
,11-04 09:57:33.566   927   944 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
11-04 09:57:33.566   927   944 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1308)
11-04 09:57:33.567   927   944 W ActivityManager: Application dead when creating service ServiceRecord{24ebee9 u0 com.android.bluetooth/.btservice.AdapterService}
,11-04 09:57:33.583   927   944 I ActivityManager: Process com.android.bluetooth (pid 4618) has died
,11-04 09:57:33.583   927   944 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
11-04 09:57:33.584   927   944 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
11-04 09:57:33.585   927   944 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
11-04 09:57:33.585   927   944 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-04 09:57:33.585   927   944 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
11-04 09:57:33.585   927   944 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
11-04 09:57:33.585   927   944 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
11-04 09:57:33.585   927   944 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
11-04 09:57:33.585   927   944 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
11-04 09:57:33.585   927   944 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
11-04 09:57:33.585   927   944 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
11-04 09:57:33.585   927   944 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
11-04 09:57:33.585   927   944 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
11-04 09:57:33.585   927   944 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
11-04 09:57:33.585   927   944 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
11-04 09:57:33.585   927   944 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
11-04 09:57:33.585   927   944 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
11-04 09:57:33.585   927   944 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:57:33.585   927   944 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:57:33.585   927   944 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 09:57:33.585   927   944 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-04 09:57:33.585   927  3149 W ActivityManager: Spurious death for ProcessRecord{36dee8e 0:com.android.bluetooth/1002}, curProc for 4618: null
,11-04 09:57:33.716  5715  5737 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-04 09:57:33.727   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6728e0f:true
,11-04 09:57:35.947  5697  5697 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 09:57:35.949  5697  5697 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 09:57:35.950  5697  5697 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-04 09:57:35.952  5697  5697 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 09:57:35.986   927  2914 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 09:57:35.988   927  2914 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-04 09:57:35.988   927  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 09:57:36.000   927  2914 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 09:57:36.029   927  2914 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 09:57:36.034  5697  5697 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 09:57:36.473  5697  5697 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 09:57:36.511  5697  5697 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 09:57:36.513  5697  5697 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 09:57:36.522   927  2914 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 09:57:36.522   927  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 09:57:36.522   927  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 09:57:36.541   927  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 09:57:36.553   507   920 D CommandListener: Setting iface cfg
,11-04 09:57:36.559   927  2914 D WifiStateMachine: Start Dhcp Watchdog 2
,11-04 09:57:36.565   927   944 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,11-04 09:57:36.565   927  5752 D DhcpClient: Receive thread started
,11-04 09:57:36.571   927  2921 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 09:57:36.571   927  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-04 09:57:36.571   927  2921 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-04 09:57:36.595   927   944 I ActivityManager: Start proc 5753:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 09:57:36.652   927  2914 E native  : do suspend false
,11-04 09:57:36.660   927  5751 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 09:57:36.666  5753  5753 D AdapterServiceConfig: Adding HeadsetService
,11-04 09:57:36.667  5753  5753 D AdapterServiceConfig: Adding A2dpService
11-04 09:57:36.667  5753  5753 D AdapterServiceConfig: Adding HidService
11-04 09:57:36.667  5753  5753 D AdapterServiceConfig: Adding HealthService
,11-04 09:57:36.668  5753  5753 D AdapterServiceConfig: Adding PanService
11-04 09:57:36.668  5753  5753 D AdapterServiceConfig: Adding GattService
11-04 09:57:36.668  5753  5753 D AdapterServiceConfig: Adding BluetoothMapService
,11-04 09:57:36.668  5753  5753 D AdapterServiceConfig: Adding SapService
,11-04 09:57:36.674   927  5752 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172732, domain null
,11-04 09:57:36.674   927  5751 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172732 seconds
11-04 09:57:36.675   927  5751 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 09:57:36.679   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a65b2c:true
,11-04 09:57:36.679  5753  5753 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 09:57:36.681  5753  5753 I bt_bluedroid: init
,11-04 09:57:36.681  5753  5765 I BluetoothAdapterState: Entering OffState
,11-04 09:57:36.683  5753  5766 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 09:57:36.683  5753  5766 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 09:57:36.683  5753  5766 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 09:57:36.683  5753  5766 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 09:57:36.684  5753  5753 I bt_bluedroid: get_profile_interface socket
,11-04 09:57:36.685  5753  5769 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 09:57:36.686  5753  5753 I bt_bluedroid: get_profile_interface sdp
11-04 09:57:36.687  5753  5769 D BluetoothAdapterProperties: Name is: Nexus 6P
11-04 09:57:36.687   927  5752 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-04 09:57:36.687   927  5751 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 09:57:36.688   507   920 D CommandListener: Setting iface cfg
,11-04 09:57:36.689   927  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 09:57:36.691  5753  5764 I bt_bluedroid: config_hci_snoop_log
,11-04 09:57:36.693   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-04 09:57:36.693   927  5751 D DhcpClient: Scheduling renewal in 86399s
,11-04 09:57:36.697  5753  5765 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 09:57:36.697  5753  5765 D BluetoothAdapterProperties: Setting state to 14
11-04 09:57:36.697  5753  5765 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-04 09:57:36.698   927  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-04 09:57:36.698   927  2914 D WifiConfigStore: No blacklist allowed without epno enabled
11-04 09:57:36.699  5753  5765 D BluetoothBondStateMachine: make
,11-04 09:57:36.700   927  2914 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-04 09:57:36.701   927  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-04 09:57:36.702   927  2921 D ConnectivityService: Adding iface wlan0 to network 101
,11-04 09:57:36.704  5753  5770 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 09:57:36.707  5753  5765 I BluetoothAdapterState: Entering PendingCommandState
,11-04 09:57:36.708  5753  5753 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 09:57:36.710  5753  5753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:36.710  5753  5753 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 09:57:36.710  5753  5753 D BtGatt.GattService: Received start request. Starting profile...
,11-04 09:57:36.710  5753  5753 D BtGatt.GattService: start()
,11-04 09:57:36.711  5753  5753 I bt_bluedroid: get_profile_interface gatt
11-04 09:57:36.711  5753  5753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
11-04 09:57:36.711  5753  5753 D BtGatt.AdvertiseManager: advertise manager created
11-04 09:57:36.715  5753  5753 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:36.715  5753  5753 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:36.716  5753  5753 V BluetoothAdapterState: isBleTurningOn()=true
11-04 09:57:36.716  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:36.716  5753  5765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 09:57:36.717  5753  5765 I bt_bluedroid: bt_bluedroid
,11-04 09:57:36.717  5753  5766 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-04 09:57:36.717  5753  5766 I bt_hci  : start_up
,11-04 09:57:36.723  5753  5766 I bt_vendor: alloc value 0xf3e2b871
,11-04 09:57:36.723  5753  5766 I bt_vendor: init
11-04 09:57:36.723  5753  5766 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 09:57:36.723  5753  5766 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 09:57:36.732   927  2921 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-04 09:57:36.732   927  2921 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-04 09:57:36.733   927  2921 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-04 09:57:36.734   927  2921 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-04 09:57:36.736   927  2921 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-04 09:57:36.744   927  2921 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 09:57:36.747   927  2921 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-04 09:57:36.747   927  2921 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-04 09:57:36.747   927  2921 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-04 09:57:36.747   927  2914 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 09:57:36.747   927  2921 D ConnectivityService:    accepting network in place of null
,11-04 09:57:36.747   927  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 09:57:36.748   927  2921 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 09:57:36.764   927  5750 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110585, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 09:57:36.766   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 09:57:36.785   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 09:57:36.787   927  2921 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-04 09:57:36.788   927  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 09:57:36.788  3715  3824 W QCNEJ   : |CORE| network available: 101
11-04 09:57:36.789   927  2921 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-04 09:57:36.790   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-04 09:57:36.791  3715  3824 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 09:57:36.792  3715  3824 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-04 09:57:36.793  3715  3824 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-04 09:57:36.797  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:36.798  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:36.798  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:36.798  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:36.798  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:36.798  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 09:57:36.798  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:36.798  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:36.798  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:36.800  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 09:57:36.800  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:36.804  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 09:57:36.804  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:36.804  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:36.804  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:36.804  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:36.804  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 09:57:36.804  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:36.804  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:36.804  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:36.805  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:36.805  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:36.807  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 09:57:36.807  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:36.807  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:36.807  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:36.807  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:36.807  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 09:57:36.807  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:36.807  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:36.807  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:36.808  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:36.808  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:36.812  3925  3925 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-04 09:57:36.815  3913  3913 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 09:57:36.820  3913  3913 D SystemUpdateService: onCreate
,11-04 09:57:36.823  3913  3913 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 09:57:36.832  5753  5766 D bt_hci  : start_up starting async portion
,11-04 09:57:36.832  5753  5777 I bt_hci  : event_finish_startup
,11-04 09:57:36.830  5788  5788 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-04 09:57:36.832  5753  5777 I bt_hci_h4: hal_open
,11-04 09:57:36.832  5753  5777 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-04 09:57:36.832  5753  5777 I bt_userial_vendor: device fd = 54 open
11-04 09:57:36.834  3913  3913 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 09:57:36.838  3913  5785 I SystemUpdateService: active receiver: enabled
,11-04 09:57:36.840  3913  4179 I iu.UploadsManager: num queued entries: 0
,11-04 09:57:36.841  3913  4179 I iu.UploadsManager: num updated entries: 0
11-04 09:57:36.841  3913  4179 I iu.SyncManager: NEXT; no task
,11-04 09:57:36.843   927  5749 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 09:57:36.843  3913  3913 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 09:57:36.845  5753  5777 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 09:57:36.845  3913  3913 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 09:57:36.847  5753  5777 D bt_hwcfg: Chipset BCM4358A3
,11-04 09:57:36.847  5753  5777 D bt_hwcfg: Target name = [BCM4358A3]
11-04 09:57:36.847  5753  5777 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 09:57:36.848  5651  5651 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-04 09:57:36.852  5651  5651 D SprintDMHelper: simOperator: 
11-04 09:57:36.852  5651  5651 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 09:57:36.876  3913  5785 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 09:57:36.881  3913  5785 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 09:57:36.881  3913  5785 I SystemUpdateService: now status is 0 (complete)
11-04 09:57:36.881  3913  5785 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 09:57:36.881  3913  5785 I SystemUpdateService: file has been verified
11-04 09:57:36.882  3913  5785 I SystemUpdateService: OTA package size = 21989297
,11-04 09:57:36.887  3913  5785 I SystemUpdateService: showing system update notification
,11-04 09:57:36.894   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 09:57:36.896   927  5749 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 08:57:36 GMT], X-Android-Received-Millis=[1478249856896], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478249856865]}
11-04 09:57:36.897   927  2921 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 09:57:36.897  3913  3913 D SystemUpdateService: onDestroy
,11-04 09:57:36.897   927  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-04 09:57:36.897   927  2921 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-04 09:57:36.898   927  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 09:57:37.081  5753  5765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-04 09:57:37.203  5753  5777 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 09:57:37.204  5753  5777 D bt_hwcfg: Settlement delay -- 100 ms
11-04 09:57:37.204  5753  5777 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 09:57:37.328  5753  5777 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 09:57:37.328  5753  5777 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-04 09:57:37.329  5753  5777 I bt_hwcfg: vendor lib fwcfg completed
11-04 09:57:37.330  5753  5777 I bt_vendor: firmware callback
11-04 09:57:37.330  5753  5777 I bt_hci  : firmware_config_callback
,11-04 09:57:37.339  5753  5795 I bt_btu  : btu_task pending for preload complete event
,11-04 09:57:37.341  5753  5795 I bt_btu_task: Bluetooth chip preload is complete
,11-04 09:57:37.341  5753  5795 I bt_btu  : btu_task received preload complete event
,11-04 09:57:37.347  5753  5795 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 09:57:37.347  5753  5795 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 09:57:37.347  5753  5795 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 09:57:37.348  5753  5795 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 09:57:37.348  5753  5795 I         : BTE_InitTraceLevels -- TRC_AVRC
11-04 09:57:37.348  5753  5795 I         : BTE_InitTraceLevels -- TRC_A2D
,11-04 09:57:37.348  5753  5795 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 09:57:37.348  5753  5795 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 09:57:37.348  5753  5795 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 09:57:37.348  5753  5795 I         : BTE_InitTraceLevels -- TRC_PAN
,11-04 09:57:37.349  5753  5795 I         : BTE_InitTraceLevels -- TRC_SDP
11-04 09:57:37.349  5753  5795 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 09:57:37.349  5753  5795 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 09:57:37.349  5753  5795 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-04 09:57:37.349  5753  5795 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 09:57:37.431  5753  5795 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3da9549
,11-04 09:57:37.431  5753  5795 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3da9549 
,11-04 09:57:37.452  5753  5769 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 09:57:37.454  5753  5769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 09:57:37.454  5753  5769 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-04 09:57:37.456  5753  5769 D BluetoothAdapterProperties: Name is: Nexus 6P
11-04 09:57:37.458  5753  5769 D BluetoothAdapterProperties: Scan Mode:20
11-04 09:57:37.458  5753  5769 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-04 09:57:37.459  5753  5769 D bt_hci  : do_postload posting postload work item
11-04 09:57:37.459  5753  5777 I bt_hci  : event_postload
11-04 09:57:37.459  5753  5777 I bt_vendor: sco_config_cb
,11-04 09:57:37.459  5753  5777 I bt_hci  : sco_config_callback postload finished.
,11-04 09:57:37.464  5753  5769 D bt_bte_conf: Device ID record 1 : primary
11-04 09:57:37.465  5753  5769 D bt_bte_conf:   vendorId            = 000f
,11-04 09:57:37.466  5753  5769 D bt_bte_conf:   vendorIdSource      = 0001
,11-04 09:57:37.466  5753  5769 D bt_bte_conf:   product             = 1200
11-04 09:57:37.466  5753  5769 D bt_bte_conf:   version             = 1436
11-04 09:57:37.466  5753  5769 D bt_bte_conf:   clientExecutableURL = 
,11-04 09:57:37.466  5753  5769 D bt_bte_conf:   serviceDescription  = 
11-04 09:57:37.466  5753  5769 D bt_bte_conf:   documentationURL    = 
11-04 09:57:37.466  5753  5769 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 09:57:37.467  5753  5766 D bt_stack_manager: event_start_up_stack finished
11-04 09:57:37.469  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:37.469  5753  5765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 09:57:37.471  5753  5777 I bt_vendor: low_power_mode_cb
11-04 09:57:37.471  5753  5765 D BluetoothAdapterProperties: Setting state to 15
,11-04 09:57:37.473  5753  5765 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 09:57:37.474  5753  5765 I BluetoothAdapterState: Entering BleOnState
,11-04 09:57:37.475  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:37.477  5753  5765 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-04 09:57:37.477  5753  5765 D BluetoothAdapterProperties: Setting state to 11
11-04 09:57:37.477  5753  5765 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-04 09:57:37.479  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:37.481  5753  5753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:37.482  5753  5753 D HeadsetService: Received start request. Starting profile...
,11-04 09:57:37.484  5753  5753 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 09:57:37.484  5753  5753 D HeadsetStateMachine: make
,11-04 09:57:37.487  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:37.491  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:37.495  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:37.496  5753  5753 D HeadsetStateMachine: max_hf_connections = 1
,11-04 09:57:37.497  5753  5753 I bt_bluedroid: get_profile_interface handsfree
11-04 09:57:37.497  5753  5769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 09:57:37.497  5753  5769 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-04 09:57:37.498  5753  5765 I BluetoothAdapterState: Entering PendingCommandState
11-04 09:57:37.500  5753  5753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
11-04 09:57:37.501  5753  5753 D A2dpService: Received start request. Starting profile...
11-04 09:57:37.501  5753  5753 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 09:57:37.502  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 09:57:37.502  5753  5753 I bt_bluedroid: get_profile_interface avrcp
,11-04 09:57:37.507  5753  5753 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 09:57:37.507  5753  5753 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 09:57:37.507  5753  5753 D A2dpStateMachine: make
,11-04 09:57:37.508  5753  5753 I bt_bluedroid: get_profile_interface a2dp
,11-04 09:57:37.509  5753  5769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-04 09:57:37.510  5753  5802 D A2dpStateMachine: Enter Disconnected: -2
,11-04 09:57:37.510  5753  5753 I BluetoothHidServiceJni: classInitNative: succeeds
,11-04 09:57:37.511  5753  5753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:37.513  5753  5753 D HidService: Received start request. Starting profile...
,11-04 09:57:37.513  5753  5753 I bt_bluedroid: get_profile_interface hidhost
11-04 09:57:37.513  5753  5753 D HidService: setHidService(): set to: null
11-04 09:57:37.513  5753  5769 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d8a56d
11-04 09:57:37.513  5753  5769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 09:57:37.514  5753  5753 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 09:57:37.515  5753  5753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
11-04 09:57:37.516  5753  5753 D HealthService: Received start request. Starting profile...
11-04 09:57:37.516  5703  5703 D BluetoothInputDevice: Proxy object connected
11-04 09:57:37.517  5703  5703 D HidProfile: Bluetooth service connected
11-04 09:57:37.517  5753  5753 I bt_bluedroid: get_profile_interface health
,11-04 09:57:37.518  5753  5753 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 09:57:37.518  5753  5753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:37.519  5703  5703 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 09:57:37.520  5753  5753 D PanService: Received start request. Starting profile...
11-04 09:57:37.520  5753  5753 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 09:57:37.520  5753  5753 I bt_bluedroid: get_profile_interface pan
11-04 09:57:37.521  5753  5769 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-04 09:57:37.521  5703  5703 D PanProfile: Bluetooth service connected
,11-04 09:57:37.522  5753  5753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:37.524  5703  5703 D BluetoothMap: Proxy object connected
,11-04 09:57:37.524  5703  5703 D MapProfile: Bluetooth service connected
11-04 09:57:37.524  5703  5703 D BluetoothMap: getConnectedDevices()
11-04 09:57:37.525  5703  5703 D BluetoothMap: Bluetooth is Not enabled
11-04 09:57:37.525  5753  5753 D BluetoothMapService: Received start request. Starting profile...
11-04 09:57:37.525  5753  5753 D BluetoothMapService: start()
,11-04 09:57:37.528  5753  5753 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-04 09:57:37.528  5753  5753 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-04 09:57:37.529  5753  5753 D BluetoothMapAppObserver: createReceiver()
,11-04 09:57:37.530  5753  5753 D BluetoothMapAppObserver: initObservers()
11-04 09:57:37.530  5753  5753 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 09:57:37.537  5753  5753 V SapService: SapBinder()
,11-04 09:57:37.537  5753  5753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:37.538  5753  5753 D SapService: Received start request. Starting profile...
11-04 09:57:37.538  5753  5753 V SapService: start()
,11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isTurningOff()=false
,11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.540  5753  5800 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isTurningOff()=false
,11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.540  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.541  5753  5753 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:37.541  5753  5753 V BluetoothAdapterState: isTurningOn()=true
,11-04 09:57:37.541  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.541  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.541  5753  5753 V BluetoothAdapterState: isTurningOff()=false
,11-04 09:57:37.542  5753  5753 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:37.542  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.542  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 09:57:37.542  5753  5753 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:37.542  5753  5753 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:37.542  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.542  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.543  5753  5753 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:37.543  5753  5753 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:37.543  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.543  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.543  5753  5765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 09:57:37.543  5753  5765 D BluetoothAdapterProperties: ScanMode =  20
11-04 09:57:37.543  5753  5765 D BluetoothAdapterProperties: State =  11
,11-04 09:57:37.545  5753  5769 D BluetoothAdapterProperties: Scan Mode:21
11-04 09:57:37.546  5753  5769 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 09:57:37.546  5753  5765 D BluetoothAdapterProperties: Setting state to 12
11-04 09:57:37.546  5753  5765 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 09:57:37.546  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 09:57:37.546   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 09:57:37.546  5753  5765 I BluetoothAdapterState: Entering OnState
11-04 09:57:37.547  3074  3087 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 09:57:37.548   927   927 D BluetoothA2dp: Proxy object connected
,11-04 09:57:37.548  5703  5714 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 09:57:37.549  5568  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-04 09:57:37.550  3074  3097 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 09:57:37.552  5568  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-04 09:57:37.554  3074  3074 D BluetoothMap: Proxy object connected
11-04 09:57:37.554  3074  3074 D MapProfile: Bluetooth service connected
11-04 09:57:37.554  3074  3074 D BluetoothMap: getConnectedDevices()
11-04 09:57:37.556  5703  5713 D BluetoothMap: onBluetoothStateChange: up=true
11-04 09:57:37.556  3074  3087 D BluetoothPan: onBluetoothStateChange on: true
,11-04 09:57:37.557  5753  5753 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 09:57:37.557  5753  5753 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 09:57:37.558  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:37.558  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:37.558  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:37.558  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:37.558  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:37.558  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:37.558  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:37.558  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:37.559  3753  3952 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 09:57:37.559  5753  5753 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 09:57:37.559  3074  3074 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 09:57:37.559  3074  3074 D PanProfile: Bluetooth service connected
11-04 09:57:37.559  3074  3097 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 09:57:37.560  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:37.561  5753  5753 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 09:57:37.562  3074  3074 D BluetoothInputDevice: Proxy object connected
11-04 09:57:37.562  3074  3908 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 09:57:37.562  3074  3074 D HidProfile: Bluetooth service connected
,11-04 09:57:37.563   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 09:57:37.563   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 09:57:37.563   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 09:57:37.564  5703  5714 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 09:57:37.564  5703  5713 D BluetoothPan: onBluetoothStateChange on: true
,11-04 09:57:37.565  3074  3097 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 09:57:37.567  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:37.567  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:37.567  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:37.567  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:37.567  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:37.567  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:37.567  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:37.567  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:37.567  3074  3074 D BluetoothA2dp: Proxy object connected
11-04 09:57:37.568   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,11-04 09:57:37.570  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:37.570  5753  5753 D ObexServerSockets: Succeed to create listening sockets 
,11-04 09:57:37.570  5753  5753 D ObexServerSockets0: startAccept()
11-04 09:57:37.571  5753  5753 D ObexServerSockets0: prepareForNewConnect()
11-04 09:57:37.573  5703  5703 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-04 09:57:37.573  5753  5753 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 09:57:37.573  5753  5753 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 09:57:37.574  5753  5810 D ObexServerSockets0: Accepting socket connection...
11-04 09:57:37.574  5753  5753 D BluetoothMapService: onReceive
,11-04 09:57:37.574  5753  5753 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 09:57:37.574  5753  5753 D BluetoothMapService: STATE_ON
11-04 09:57:37.574  5753  5811 D ObexServerSockets0: Accepting socket connection...
11-04 09:57:37.574  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:37.574  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:37.574  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:37.574  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:37.574  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:37.574  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:37.574  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:37.574  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:37.577  5753  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 09:57:37.579  5703  5703 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-04 09:57:37.579  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:37.579  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 09:57:37.582  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:37.582  5753  5812 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 09:57:37.582  5753  5812 D BluetoothSdpJni: SDP Create record success - handle: 1
11-04 09:57:37.584  5568  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:37.584  5568  5616 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 09:57:37.585  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 09:57:37.585  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:37.586  5568  5616 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-04 09:57:37.587  5568  5616 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-04 09:57:37.589  5703  5703 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 09:57:37.590  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:37.590  5753  5765 D BluetoothAdapterState: Current state: ON, message: 23
11-04 09:57:37.590  5753  5765 D BluetoothAdapterProperties: Setting state to 13
11-04 09:57:37.590  5753  5765 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 09:57:37.591  5753  5765 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 09:57:37.591  5703  5703 D BluetoothA2dp: Proxy object connected
11-04 09:57:37.591  5753  5765 I BluetoothAdapterState: Entering PendingCommandState
11-04 09:57:37.592  5753  5753 D BluetoothMapService: onReceive
11-04 09:57:37.592  5753  5753 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 09:57:37.592  5753  5753 D BluetoothMapService: STATE_TURNING_OFF
11-04 09:57:37.593  5753  5753 D BluetoothMapService: MAP Service closeService in
11-04 09:57:37.593  5753  5769 D BluetoothAdapterProperties: Scan Mode:20
11-04 09:57:37.593  5753  5753 D BluetoothMapMasInstance0: MAP Service shutdown
,11-04 09:57:37.593  5753  5765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 09:57:37.593  5753  5753 D ObexServerSockets0: shutdown(block = true)
11-04 09:57:37.593  5753  5753 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 09:57:37.594  5753  5753 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 09:57:37.594  5753  5811 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 09:57:37.594  5753  5810 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-04 09:57:37.594  5753  5797 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-04 09:57:37.596  5568  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:37.596  5568  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:37.596  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:37.596  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:37.596  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:37.596  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 09:57:37.596  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:37.596  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:37.596  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:37.599  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:37.599  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:37.599  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:37.599  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:37.599  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:37.599  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 09:57:37.599  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:37.599  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:37.599  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:37.599  5753  5753 D HeadsetService: Received stop request...Stopping profile...
11-04 09:57:37.599  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 09:57:37.599  5568  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 09:57:37.599  5568  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:37.601  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:37.601  5753  5753 D A2dpService: Received stop request...Stopping profile...
11-04 09:57:37.601  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:37.601  5753  5802 D A2dpStateMachine: Exit Disconnected: -1
11-04 09:57:37.602  5703  5703 D DockEventReceiver: finishStartingService: stopping service
11-04 09:57:37.604  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:37.604  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:37.604  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:37.604  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:37.604  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:37.604  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 09:57:37.604  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:37.604  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:37.604  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 09:57:37.604  5568  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 09:57:37.605  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:37.606   927   927 D BluetoothA2dp: Proxy object disconnected
11-04 09:57:37.606  5703  5703 D BluetoothA2dp: Proxy object disconnected
,11-04 09:57:37.607  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:37.609  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:37.615  5753  5753 D HidService: Received stop request...Stopping profile...
11-04 09:57:37.615  5753  5753 D HidService: Stopping Bluetooth HidService
,11-04 09:57:37.616  5753  5753 V BluetoothAdapterState: isTurningOff()=true
,11-04 09:57:37.616  5753  5753 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:37.616  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.616  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.616  5703  5703 D BluetoothPbap: Proxy object connected
11-04 09:57:37.617  5753  5753 D HealthService: Received stop request...Stopping profile...
11-04 09:57:37.617  5703  5703 D PbapServerProfile: Bluetooth service connected
11-04 09:57:37.617  5703  5703 D BluetoothInputDevice: Proxy object disconnected
11-04 09:57:37.617  5703  5703 D HidProfile: Bluetooth service disconnected
,11-04 09:57:37.619  5753  5753 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-04 09:57:37.619  5753  5753 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 09:57:37.619  5753  5769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 09:57:37.619  5753  5753 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:37.619  5753  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 09:57:37.619  5753  5753 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:37.619  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.619  5753  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 09:57:37.619  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.619  5753  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 09:57:37.619  5753  5769 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,11-04 09:57:37.620  5753  5753 D PanService: Received stop request...Stopping profile...
,11-04 09:57:37.621  5753  5753 D BluetoothMapService: Received stop request...Stopping profile...
,11-04 09:57:37.621  5753  5753 D BluetoothMapService: stop()
11-04 09:57:37.621  5753  5753 D BluetoothMapAppObserver: deinitObservers()
11-04 09:57:37.621  5753  5753 D BluetoothMapAppObserver: removeReceiver()
11-04 09:57:37.622  3074  3074 D BluetoothA2dp: Proxy object disconnected
11-04 09:57:37.622  3074  3074 D BluetoothPbap: Proxy object connected
11-04 09:57:37.622  3074  3074 D PbapServerProfile: Bluetooth service connected
11-04 09:57:37.622  3074  3074 D BluetoothInputDevice: Proxy object disconnected
,11-04 09:57:37.622  3074  3074 D HidProfile: Bluetooth service disconnected
11-04 09:57:37.622  3074  3074 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 09:57:37.622  3074  3074 D PanProfile: Bluetooth service disconnected
11-04 09:57:37.622  3074  3074 D BluetoothMap: Proxy object disconnected
11-04 09:57:37.622  3074  3074 D MapProfile: Bluetooth service disconnected
11-04 09:57:37.625  5703  5703 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 09:57:37.625  5703  5703 D PanProfile: Bluetooth service disconnected
11-04 09:57:37.625  5703  5703 D BluetoothMap: Proxy object disconnected
,11-04 09:57:37.625  5703  5703 D MapProfile: Bluetooth service disconnected
11-04 09:57:37.628  5753  5753 D SapService: Received stop request...Stopping profile...
11-04 09:57:37.628  5753  5753 V SapService: stop()
,11-04 09:57:37.632  5703  5703 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 09:57:37.632  5753  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 09:57:37.632  5753  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 09:57:37.632  5753  5753 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:37.632  5753  5753 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:37.632  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.632  5753  5795 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 09:57:37.632  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.632  5753  5795 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 09:57:37.632  5753  5795 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 09:57:37.632  5753  5795 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 09:57:37.633  5753  5753 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 09:57:37.633  5753  5753 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 09:57:37.633  5753  5753 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:37.633  5753  5753 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:37.633  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.633  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.633  5753  5753 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 09:57:37.633  5753  5769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 09:57:37.633  5753  5753 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 09:57:37.634  5753  5753 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:37.634  5753  5753 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:37.634  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.634  5753  5769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 09:57:37.634  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.634  5753  5769 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 09:57:37.634  5753  5753 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 09:57:37.634  5753  5753 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 09:57:37.635  5753  5753 D BluetoothMapService: MAP Service closeService in
11-04 09:57:37.635  5753  5753 V BluetoothAdapterState: isTurningOff()=true
11-04 09:57:37.635  5753  5753 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:37.635  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.635  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:37.635  5753  5753 D BluetoothMapService: cleanup()
11-04 09:57:37.636  5753  5753 D BluetoothMapService: MAP Service closeService in
11-04 09:57:37.637  5703  5703 D DockEventReceiver: finishStartingService: stopping service
,11-04 09:57:37.647  5753  5753 V BluetoothAdapterState: isTurningOff()=true
,11-04 09:57:37.648  5753  5753 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:37.648  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:37.648  5753  5753 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 09:57:37.648  5753  5765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 09:57:37.648  5753  5765 D BluetoothAdapterProperties: Setting state to 15
11-04 09:57:37.648  5753  5765 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 09:57:37.649  5753  5765 I BluetoothAdapterState: Entering BleOnState
11-04 09:57:37.650   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-04 09:57:37.652  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 09:57:37.652  3074  3074 D BluetoothPbap: Proxy object disconnected
11-04 09:57:37.652  3074  3074 D PbapServerProfile: Bluetooth service disconnected
11-04 09:57:37.652  5703  5703 D BluetoothPbap: Proxy object disconnected
11-04 09:57:37.652  5703  5703 D PbapServerProfile: Bluetooth service disconnected
11-04 09:57:37.653  5703  5713 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 09:57:37.653  3074  3097 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 09:57:37.654  5703  5714 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 09:57:37.654  3074  3908 D BluetoothMap: onBluetoothStateChange: up=false
,11-04 09:57:37.655  5703  5713 D BluetoothMap: onBluetoothStateChange: up=false
,11-04 09:57:37.656  3074  3087 D BluetoothPan: onBluetoothStateChange on: false
,11-04 09:57:37.657  3753  3767 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-04 09:57:37.657  3074  3097 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 09:57:37.658  3074  3908 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 09:57:37.659   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 09:57:37.659   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 09:57:37.659   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 09:57:37.659  5703  5714 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-04 09:57:37.660  5703  5713 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 09:57:37.660  5703  5714 D BluetoothPan: onBluetoothStateChange on: false
11-04 09:57:37.661  3074  3087 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 09:57:37.661  5753  5765 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 09:57:37.661  5753  5765 D BluetoothAdapterProperties: Setting state to 16
11-04 09:57:37.661  5753  5765 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-04 09:57:37.662  5753  5765 D BluetoothAdapterProperties: onBleDisable
11-04 09:57:37.662  5753  5765 I BluetoothAdapterState: Entering PendingCommandState
11-04 09:57:37.662  5753  5766 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-04 09:57:37.664  5753  5795 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-04 09:57:37.664  5753  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 09:57:37.667  5753  5769 D BluetoothAdapterProperties: Scan Mode:20
,11-04 09:57:37.670  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:37.672  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:37.673  5703  5703 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 09:57:37.674  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:37.677  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 09:57:37.677  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:37.679  5703  5703 D DockEventReceiver: finishStartingService: stopping service
,11-04 09:57:37.788   927  2921 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-04 09:57:37.865  5753  5769 I bt_hci  : shut_down
11-04 09:57:37.865  5753  5777 D bt_hwcfg: hw_epilog_process
,11-04 09:57:37.866  5753  5777 I bt_vendor: low_power_mode_cb
,11-04 09:57:37.869  5753  5777 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-04 09:57:37.869  5753  5777 I bt_vendor: epilog_cb
11-04 09:57:37.869  5753  5777 I bt_hci  : epilog_finished_callback
11-04 09:57:37.869  5753  5769 I bt_hci_h4: hal_close
,11-04 09:57:37.870  5753  5769 I bt_userial_vendor: device fd = 54 close
,11-04 09:57:37.990  5753  5766 D bt_stack_manager: event_shut_down_stack finished.
,11-04 09:57:37.991  5753  5765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-04 09:57:37.995  5753  5765 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-04 09:57:37.995  5753  5753 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 09:57:37.997  5753  5753 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 09:57:37.997  5753  5753 D BtGatt.GattService: stop()
11-04 09:57:37.997  5753  5753 D BtGatt.AdvertiseManager: advertise clients cleared
,11-04 09:57:38.002  5753  5753 V BluetoothAdapterState: isTurningOff()=false
,11-04 09:57:38.002  5753  5753 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:38.002  5753  5753 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:38.002  5753  5753 V BluetoothAdapterState: isBleTurningOff()=true
11-04 09:57:38.002  5753  5765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-04 09:57:38.003  5753  5765 D BluetoothAdapterProperties: Setting state to 10
11-04 09:57:38.003  5753  5765 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 09:57:38.004  5753  5765 I BluetoothAdapterState: Entering OffState
,11-04 09:57:38.005   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-04 09:57:38.016  5753  5753 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 09:57:38.016  5753  5753 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 09:57:38.017  5753  5753 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-04 09:57:38.019  5753  5766 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 09:57:38.027  5753  5753 I art     : System.exit called, status: 0
,11-04 09:57:38.027  5753  5753 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 09:57:38.062   927  3762 I ActivityManager: Process com.android.bluetooth (pid 5753) has died
,11-04 09:57:38.093  5568  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:38.096  5568  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:38.113   927   944 I ActivityManager: Start proc 5823:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 09:57:38.176  5823  5823 D AdapterServiceConfig: Adding HeadsetService
,11-04 09:57:38.176  5823  5823 D AdapterServiceConfig: Adding A2dpService
11-04 09:57:38.177  5823  5823 D AdapterServiceConfig: Adding HidService
11-04 09:57:38.177  5823  5823 D AdapterServiceConfig: Adding HealthService
11-04 09:57:38.177  5823  5823 D AdapterServiceConfig: Adding PanService
,11-04 09:57:38.177  5823  5823 D AdapterServiceConfig: Adding GattService
11-04 09:57:38.177  5823  5823 D AdapterServiceConfig: Adding BluetoothMapService
11-04 09:57:38.178  5823  5823 D AdapterServiceConfig: Adding SapService
,11-04 09:57:38.190   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a78f933:true
,11-04 09:57:38.191  5823  5823 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 09:57:38.193  5823  5823 I bt_bluedroid: init
,11-04 09:57:38.193  5823  5835 I BluetoothAdapterState: Entering OffState
,11-04 09:57:38.195  5823  5836 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 09:57:38.195  5823  5836 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 09:57:38.195  5823  5836 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 09:57:38.195  5823  5836 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 09:57:38.196  5823  5823 I bt_bluedroid: get_profile_interface socket
,11-04 09:57:38.197  5823  5839 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-04 09:57:38.197  5823  5823 I bt_bluedroid: get_profile_interface sdp
,11-04 09:57:38.198  5823  5839 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 09:57:38.201  5823  5834 I bt_bluedroid: config_hci_snoop_log
,11-04 09:57:38.202   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 09:57:38.205  5823  5835 D BluetoothAdapterState: Current state: OFF, message: 0
11-04 09:57:38.205  5823  5835 D BluetoothAdapterProperties: Setting state to 14
11-04 09:57:38.206  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-04 09:57:38.207  5823  5835 D BluetoothBondStateMachine: make
,11-04 09:57:38.208  5823  5840 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 09:57:38.211  5823  5835 I BluetoothAdapterState: Entering PendingCommandState
,11-04 09:57:38.212  5823  5823 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 09:57:38.213  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:38.214  5823  5823 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 09:57:38.214  5823  5823 D BtGatt.GattService: Received start request. Starting profile...
11-04 09:57:38.214  5823  5823 D BtGatt.GattService: start()
11-04 09:57:38.214  5823  5823 I bt_bluedroid: get_profile_interface gatt
,11-04 09:57:38.215  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
11-04 09:57:38.215  5823  5823 D BtGatt.AdvertiseManager: advertise manager created
,11-04 09:57:38.219  5823  5823 V BluetoothAdapterState: isTurningOff()=false
,11-04 09:57:38.220  5823  5823 V BluetoothAdapterState: isTurningOn()=false
11-04 09:57:38.220  5823  5823 V BluetoothAdapterState: isBleTurningOn()=true
11-04 09:57:38.220  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:38.220  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 09:57:38.222  5823  5835 I bt_bluedroid: bt_bluedroid
,11-04 09:57:38.222  5823  5836 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-04 09:57:38.222  5823  5836 I bt_hci  : start_up
,11-04 09:57:38.227  5823  5836 I bt_vendor: alloc value 0xf3e2b871
,11-04 09:57:38.227  5823  5836 I bt_vendor: init
11-04 09:57:38.227  5823  5836 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 09:57:38.227  5823  5836 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 09:57:38.337  5823  5836 D bt_hci  : start_up starting async portion
11-04 09:57:38.337  5823  5843 I bt_hci  : event_finish_startup
11-04 09:57:38.337  5823  5843 I bt_hci_h4: hal_open
11-04 09:57:38.337  5823  5843 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 09:57:38.334  5844  5844 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 09:57:38.339  5823  5843 I bt_userial_vendor: device fd = 54 open
,11-04 09:57:38.352  5823  5843 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 09:57:38.354  5823  5843 D bt_hwcfg: Chipset BCM4358A3
11-04 09:57:38.354  5823  5843 D bt_hwcfg: Target name = [BCM4358A3]
,11-04 09:57:38.354  5823  5843 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 09:57:38.601  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-04 09:57:38.732  5823  5843 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 09:57:38.733  5823  5843 D bt_hwcfg: Settlement delay -- 100 ms
11-04 09:57:38.733  5823  5843 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 09:57:38.857  5823  5843 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 09:57:38.858  5823  5843 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-04 09:57:38.860  5823  5843 I bt_hwcfg: vendor lib fwcfg completed
11-04 09:57:38.860  5823  5843 I bt_vendor: firmware callback
11-04 09:57:38.860  5823  5843 I bt_hci  : firmware_config_callback
,11-04 09:57:38.870  5823  5846 I bt_btu  : btu_task pending for preload complete event
,11-04 09:57:38.870  5823  5846 I bt_btu_task: Bluetooth chip preload is complete
11-04 09:57:38.870  5823  5846 I bt_btu  : btu_task received preload complete event
,11-04 09:57:38.877  5823  5846 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 09:57:38.877  5823  5846 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 09:57:38.877  5823  5846 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 09:57:38.877  5823  5846 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 09:57:38.877  5823  5846 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-04 09:57:38.877  5823  5846 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 09:57:38.877  5823  5846 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 09:57:38.877  5823  5846 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 09:57:38.877  5823  5846 I         : BTE_InitTraceLevels -- TRC_GAP
,11-04 09:57:38.877  5823  5846 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 09:57:38.878  5823  5846 I         : BTE_InitTraceLevels -- TRC_SDP
11-04 09:57:38.878  5823  5846 I         : BTE_InitTraceLevels -- TRC_GATT
,11-04 09:57:38.878  5823  5846 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 09:57:38.878  5823  5846 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-04 09:57:38.878  5823  5846 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 09:57:38.951  5823  5846 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3da9549
11-04 09:57:38.952  5823  5846 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3da9549 
,11-04 09:57:38.969  5823  5839 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 09:57:38.970  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 09:57:38.971  5823  5839 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 09:57:38.973  5823  5839 D BluetoothAdapterProperties: Name is: Nexus 6P
11-04 09:57:38.975  5823  5839 D BluetoothAdapterProperties: Scan Mode:20
11-04 09:57:38.975  5823  5839 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 09:57:38.975  5823  5839 D bt_hci  : do_postload posting postload work item
11-04 09:57:38.975  5823  5843 I bt_hci  : event_postload
11-04 09:57:38.976  5823  5843 I bt_vendor: sco_config_cb
11-04 09:57:38.976  5823  5843 I bt_hci  : sco_config_callback postload finished.
,11-04 09:57:38.979  5823  5839 D bt_bte_conf: Device ID record 1 : primary
11-04 09:57:38.979  5823  5839 D bt_bte_conf:   vendorId            = 000f
11-04 09:57:38.979  5823  5839 D bt_bte_conf:   vendorIdSource      = 0001
11-04 09:57:38.979  5823  5839 D bt_bte_conf:   product             = 1200
11-04 09:57:38.979  5823  5839 D bt_bte_conf:   version             = 1436
11-04 09:57:38.979  5823  5839 D bt_bte_conf:   clientExecutableURL = 
11-04 09:57:38.979  5823  5839 D bt_bte_conf:   serviceDescription  = 
11-04 09:57:38.980  5823  5839 D bt_bte_conf:   documentationURL    = 
11-04 09:57:38.980  5823  5839 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 09:57:38.980  5823  5836 D bt_stack_manager: event_start_up_stack finished
11-04 09:57:38.980  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 09:57:38.981  5823  5835 D BluetoothAdapterProperties: Setting state to 15
11-04 09:57:38.981  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 09:57:38.982  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:38.982  5823  5835 I BluetoothAdapterState: Entering BleOnState
,11-04 09:57:38.987  5823  5835 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-04 09:57:38.987  5823  5835 D BluetoothAdapterProperties: Setting state to 11
11-04 09:57:38.987  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-04 09:57:38.988  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:38.993  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:38.996  5823  5843 I bt_vendor: low_power_mode_cb
,11-04 09:57:38.999   927   927 D BluetoothHeadset: Proxy object connected
,11-04 09:57:38.999  5703  5713 D BluetoothHeadset: Proxy object connected
11-04 09:57:38.999  5823  5823 D HeadsetService: Received start request. Starting profile...
11-04 09:57:39.001   927   927 D BluetoothHeadset: Proxy object connected
11-04 09:57:39.002  5823  5823 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 09:57:39.002  3753  3952 D BluetoothHeadset: Proxy object connected
,11-04 09:57:39.002  5823  5823 D HeadsetStateMachine: make
11-04 09:57:39.003   927   927 D BluetoothHeadset: Proxy object connected
11-04 09:57:39.003  3074  3097 D BluetoothHeadset: Proxy object connected
11-04 09:57:39.004  5703  5703 D HeadsetProfile: Bluetooth service connected
,11-04 09:57:39.010  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:39.010  5823  5835 I BluetoothAdapterState: Entering PendingCommandState
,11-04 09:57:39.013  5823  5823 D HeadsetStateMachine: max_hf_connections = 1
11-04 09:57:39.013  5823  5823 I bt_bluedroid: get_profile_interface handsfree
11-04 09:57:39.013  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:39.013  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-04 09:57:39.013  5823  5839 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-04 09:57:39.016  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:39.017  5823  5823 D A2dpService: Received start request. Starting profile...
11-04 09:57:39.017  5823  5823 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 09:57:39.018  5823  5823 I bt_bluedroid: get_profile_interface avrcp
,11-04 09:57:39.023  3074  3074 D HeadsetProfile: Bluetooth service connected
,11-04 09:57:39.027  5823  5823 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 09:57:39.028  5823  5823 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 09:57:39.028  5823  5823 D A2dpStateMachine: make
,11-04 09:57:39.029  5823  5823 I bt_bluedroid: get_profile_interface a2dp
,11-04 09:57:39.030  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-04 09:57:39.031  5823  5823 I BluetoothHidServiceJni: classInitNative: succeeds
,11-04 09:57:39.031  5823  5856 D A2dpStateMachine: Enter Disconnected: -2
,11-04 09:57:39.032  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:39.033  5823  5823 D HidService: Received start request. Starting profile...
,11-04 09:57:39.033  5823  5823 I bt_bluedroid: get_profile_interface hidhost
,11-04 09:57:39.033  5823  5839 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d8a56d
,11-04 09:57:39.033  5823  5823 D HidService: setHidService(): set to: null
11-04 09:57:39.033  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 09:57:39.034  5823  5823 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 09:57:39.034  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
11-04 09:57:39.035  5823  5823 D HealthService: Received start request. Starting profile...
11-04 09:57:39.036  5823  5823 I bt_bluedroid: get_profile_interface health
,11-04 09:57:39.038  5823  5823 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-04 09:57:39.039  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
11-04 09:57:39.039  5823  5823 D PanService: Received start request. Starting profile...
11-04 09:57:39.039  5823  5823 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 09:57:39.039  5823  5823 I bt_bluedroid: get_profile_interface pan
11-04 09:57:39.040  5823  5839 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-04 09:57:39.042  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:39.042  5823  5823 D BluetoothMapService: Received start request. Starting profile...
,11-04 09:57:39.042  5823  5823 D BluetoothMapService: start()
,11-04 09:57:39.046  5823  5823 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-04 09:57:39.047  5823  5823 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-04 09:57:39.047  5823  5823 D BluetoothMapAppObserver: createReceiver()
,11-04 09:57:39.048  5823  5823 D BluetoothMapAppObserver: initObservers()
,11-04 09:57:39.049  5823  5823 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 09:57:39.056  5823  5823 V SapService: SapBinder()
,11-04 09:57:39.056  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
11-04 09:57:39.057  5823  5823 D SapService: Received start request. Starting profile...
11-04 09:57:39.057  5823  5823 V SapService: start()
,11-04 09:57:39.059  5823  5823 V BluetoothAdapterState: isTurningOff()=false
,11-04 09:57:39.059  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:39.059  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:39.059  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:39.059  5823  5852 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isTurningOn()=true
,11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:39.060  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:39.061  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-04 09:57:39.061  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:39.061  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 09:57:39.061  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-04 09:57:39.062  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-04 09:57:39.062  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 09:57:39.062  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-04 09:57:39.062  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 09:57:39.062  5823  5835 D BluetoothAdapterProperties: ScanMode =  20
11-04 09:57:39.062  5823  5835 D BluetoothAdapterProperties: State =  11
11-04 09:57:39.062  5823  5835 D BluetoothAdapterProperties: Setting state to 12
11-04 09:57:39.062  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 09:57:39.063  5823  5835 I BluetoothAdapterState: Entering OnState
,11-04 09:57:39.063   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 09:57:39.067  5823  5839 D BluetoothAdapterProperties: Scan Mode:21
,11-04 09:57:39.067  5823  5839 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 09:57:39.068  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-04 09:57:39.068  5703  5713 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 09:57:39.069   927   927 D BluetoothA2dp: Proxy object connected
,11-04 09:57:39.069  3074  3087 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 09:57:39.071  5703  5851 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 09:57:39.072  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:39.072  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:39.072  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:39.072  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:39.072  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:39.072  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:39.072  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:39.072  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:39.074  5823  5823 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 09:57:39.074  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:39.074  5823  5823 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-04 09:57:39.076  3074  3097 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 09:57:39.076  5823  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 09:57:39.078  5703  5714 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 09:57:39.079  5823  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 09:57:39.080  3074  3908 D BluetoothPan: onBluetoothStateChange on: true
11-04 09:57:39.080  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:39.080  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:39.080  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:39.080  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:39.080  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:39.080  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:39.080  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:39.080  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:39.080  5823  5823 D ObexServerSockets: Succeed to create listening sockets 
11-04 09:57:39.080  5823  5823 D ObexServerSockets0: startAccept()
,11-04 09:57:39.080  5823  5823 D ObexServerSockets0: prepareForNewConnect()
11-04 09:57:39.081  3753  3771 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 09:57:39.082  3074  3087 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 09:57:39.082  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:39.082  5823  5823 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 09:57:39.083  5823  5823 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 09:57:39.083  5823  5861 D ObexServerSockets0: Accepting socket connection...
,11-04 09:57:39.084  3074  3097 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 09:57:39.084  5823  5862 D ObexServerSockets0: Accepting socket connection...
11-04 09:57:39.085  3074  3074 D BluetoothMap: Proxy object connected
11-04 09:57:39.085  3074  3074 D MapProfile: Bluetooth service connected
11-04 09:57:39.085  3074  3074 D BluetoothMap: getConnectedDevices()
,11-04 09:57:39.086   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 09:57:39.086   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 09:57:39.086   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 09:57:39.086  5703  5851 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 09:57:39.087  3074  3074 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 09:57:39.087  3074  3074 D PanProfile: Bluetooth service connected
11-04 09:57:39.087  3074  3074 D BluetoothInputDevice: Proxy object connected
11-04 09:57:39.087  3074  3074 D HidProfile: Bluetooth service connected
11-04 09:57:39.088  5703  5713 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 09:57:39.088  5703  5703 D BluetoothMap: Proxy object connected
11-04 09:57:39.088  5703  5703 D MapProfile: Bluetooth service connected
11-04 09:57:39.088  5703  5703 D BluetoothMap: getConnectedDevices()
11-04 09:57:39.090  5703  5851 D BluetoothPan: onBluetoothStateChange on: true
,11-04 09:57:39.092  3074  3908 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 09:57:39.093  3074  3074 D BluetoothA2dp: Proxy object connected
11-04 09:57:39.094   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 09:57:39.094   927   927 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
11-04 09:57:39.095  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 09:57:39.096  5703  5703 D BluetoothA2dp: Proxy object connected
11-04 09:57:39.097  5703  5703 D BluetoothInputDevice: Proxy object connected
11-04 09:57:39.098  5703  5703 D HidProfile: Bluetooth service connected
,11-04 09:57:39.098  5823  5823 D BluetoothMapService: onReceive
,11-04 09:57:39.098  5823  5823 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 09:57:39.098  5823  5823 D BluetoothMapService: STATE_ON
11-04 09:57:39.099  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:39.101  5823  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 09:57:39.101  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:39.103  5823  5864 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 09:57:39.103  5823  5864 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 09:57:39.105  5568  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:39.105  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:39.105  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:39.105  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:39.105  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:39.105  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:39.105  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:39.105  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 09:57:39.107  5568  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:39.107  5703  5703 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 09:57:39.107  5703  5703 D PanProfile: Bluetooth service connected
11-04 09:57:39.108  5568  5616 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-04 09:57:39.108   927  3745 D WifiService: setWifiEnabled: false pid=5568, uid=10077
11-04 09:57:39.109   927  3745 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-04 09:57:39.110   927  2914 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-04 09:57:39.110   927  2914 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 09:57:39.110   927  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 09:57:39.110   927  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 09:57:39.111  5568  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:39.112  5703  5703 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 09:57:39.119  5823  5823 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 09:57:39.119  5823  5823 D ObexServerSockets0: prepareForNewConnect()
11-04 09:57:39.120  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 09:57:39.121  5703  5703 D DockEventReceiver: finishStartingService: stopping service
11-04 09:57:39.123   927  5751 D DhcpClient: Clearing IP address
11-04 09:57:39.123   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-04 09:57:39.130   507   920 D CommandListener: Setting iface cfg
11-04 09:57:39.131  3074  3074 D BluetoothPbap: Proxy object connected
11-04 09:57:39.131  3074  3074 D PbapServerProfile: Bluetooth service connected
,11-04 09:57:39.132   927  5752 D DhcpClient: Receive thread stopped
,11-04 09:57:39.134  5703  5703 D BluetoothPbap: Proxy object connected
11-04 09:57:39.134  5703  5703 D PbapServerProfile: Bluetooth service connected
,11-04 09:57:39.140  5823  5869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 09:57:39.142  3522  5794 V NativeCrypto: Read error: ssl=0x7f5cad8000: I/O error during system call, Connection timed out
11-04 09:57:39.143  3522  5794 V NativeCrypto: SSL shutdown failed: ssl=0x7f5cad8000: I/O error during system call, Broken pipe
,11-04 09:57:39.146   927  3536 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-04 09:57:39.146   927  5749 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-04 09:57:39.147   927  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-04 09:57:39.147   927  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-04 09:57:39.148   537   537 E Parcel  : Reading a NULL string not supported here.
11-04 09:57:39.150   927  5749 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-04 09:57:39.151   927  2921 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-04 09:57:39.152  3715  3824 W QCNEJ   : |CORE| network lost: 101
,11-04 09:57:39.153   927   927 D RttService: SCAN_AVAILABLE : 1
11-04 09:57:39.153  3715  3824 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-04 09:57:39.153   927  3028 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 09:57:39.161  5823  5877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 09:57:39.163  5823  5877 I BtOppRfcommListener: Accept thread started.
,11-04 09:57:39.172   927  2914 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-04 09:57:39.175   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 09:57:39.179   927  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 09:57:39.194   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-04 09:57:39.194   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-04 09:57:39.195   927  2921 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-04 09:57:39.195   927  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 09:57:39.197   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-04 09:57:39.200   927  2914 D DhcpClient: doQuit
,11-04 09:57:39.200   927  2914 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 09:57:39.201  5697  5697 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-04 09:57:39.201   927  5751 D DhcpClient: onQuitting
11-04 09:57:39.202  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:39.202  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:39.202  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:39.202  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:39.202  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:39.202  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:39.202  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:39.202  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 09:57:39.204  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:39.208  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:39.208  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:39.208  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:39.208  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 09:57:39.208  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:39.208  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:39.208  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:39.208  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:39.210  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:39.213  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:39.213  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:39.213  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:39.213  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 09:57:39.213  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:39.213  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:39.213  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:39.213  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:39.214  3925  3925 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-04 09:57:39.215  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:39.217  3913  3913 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 09:57:39.220  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:39.220  3913  3913 D SystemUpdateService: onCreate
,11-04 09:57:39.224  3913  3913 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-04 09:57:39.224  5697  5697 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 09:57:39.229  5697  5697 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-04 09:57:39.233  3913  3913 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 09:57:39.237  3913  4179 I iu.UploadsManager: num queued entries: 0
11-04 09:57:39.237  3913  4179 I iu.UploadsManager: num updated entries: 0
11-04 09:57:39.238  3913  4179 I iu.SyncManager: NEXT; no task
,11-04 09:57:39.238  3913  5884 I SystemUpdateService: active receiver: enabled
,11-04 09:57:39.241  3913  3913 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 09:57:39.242  3913  3913 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-04 09:57:39.242   507   920 E Netd    : netlink response contains error (No such file or directory)
,11-04 09:57:39.244   927  2921 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-04 09:57:39.244   927  2921 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 09:57:39.244  5651  5651 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 09:57:39.248  5651  5651 D SprintDMHelper: simOperator: 
11-04 09:57:39.248  5651  5651 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 09:57:39.261  5697  5697 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 09:57:39.262  3913  5884 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 09:57:39.264  3913  5884 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-04 09:57:39.264  3913  5884 I SystemUpdateService: now status is 0 (complete)
11-04 09:57:39.264  3913  5884 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 09:57:39.264  3913  5884 I SystemUpdateService: file has been verified
,11-04 09:57:39.266  3913  5884 I SystemUpdateService: OTA package size = 21989297
,11-04 09:57:39.279  3913  5884 I SystemUpdateService: showing system update notification
,11-04 09:57:39.282  5697  5697 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 09:57:39.285   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 09:57:39.286  3913  3913 D SystemUpdateService: onDestroy
,11-04 09:57:39.386   927  2914 D wifi    : In wifi stop Hal
,11-04 09:57:39.387   927  2914 D wifi    : halHandle = 0x7f5b1b7680, mVM = 0x7f7734d140, mCls = 0x1014ea
,11-04 09:57:39.387   927  5696 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 09:57:39.387   927  5696 D WifiHAL : Got a signal to exit!!!
,11-04 09:57:39.387   927  5696 I WifiHAL : Exit wifi_event_loop
11-04 09:57:39.388   927  2914 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-04 09:57:39.389   927  2914 E WifiHAL : Event processing terminated
11-04 09:57:39.389   927  2914 D wifi    : In wifi cleaned up handler
11-04 09:57:39.389   927  2914 I WifiHAL : Internal cleanup completed
11-04 09:57:39.392  4463  4463 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 09:57:39.393  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:39.394  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:39.395  3681  4146 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 09:57:39.411   927  5696 D wifi    : set interface wlan0 flags (DOWN)
,11-04 09:57:39.411   927  2914 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 09:57:39.618   927   944 D Tethering: InitialState.processMessage what=4
,11-04 09:57:39.619  5568  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:39.619  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:39.619  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:39.619  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 09:57:39.619  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:39.619  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:39.619  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:39.619  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:39.624  5568  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:39.625   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 09:57:39.628   927  3716 D WifiService: setWifiEnabled: true pid=5568, uid=10077
11-04 09:57:39.629   927  3716 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-04 09:57:39.630  5568  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:39.633   507   920 D SoftapController: Softap fwReload - Ok
,11-04 09:57:39.636   507   920 D CommandListener: Setting iface cfg
,11-04 09:57:39.636   507   920 D CommandListener: Trying to bring down wlan0
11-04 09:57:39.637   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-04 09:57:39.640   927  2914 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 09:57:40.133   927  3099 D WifiService: setWifiEnabled: true pid=5568, uid=10077
11-04 09:57:40.138   927  3099 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 09:57:40.231   927  2914 D wifi    : set interface wlan0 flags (UP)
,11-04 09:57:40.231   927  2914 I WifiHAL : Initializing wifi
,11-04 09:57:40.231   927  2914 I WifiHAL : Creating socket
,11-04 09:57:40.240   927  2914 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-04 09:57:40.240   927  2914 D wifi    : Did set static halHandle = 0x7f5b1b7680
,11-04 09:57:40.240   927  2914 D wifi    : halHandle = 0x7f5b1b7680, mVM = 0x7f7734d140, mCls = 0x197e
,11-04 09:57:40.240   927  2914 D wifi    : array field set
11-04 09:57:40.241   927  2914 I WifiNative-HAL: interface[0] = wlan0
11-04 09:57:40.242   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-04 09:57:40.243   927  5891 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546989373056
,11-04 09:57:40.243   927  5891 D wifi    : waitForHalEvents called, vm = 0x7f7734d140, obj = 0x197e, env = 0x7f5c2bed00
,11-04 09:57:40.303  5892  5892 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 09:57:40.344   927  2914 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 09:57:40.353  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:40.354  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:40.374   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-04 09:57:40.374   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-04 09:57:40.378  5892  5892 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 09:57:40.383  5892  5892 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 09:57:40.383  5892  5892 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 09:57:40.393   927  2914 D WifiConfigStore: Loading config and enabling all networks 
,11-04 09:57:40.400  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:40.400  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:40.400  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:40.400  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:40.400  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:40.400  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:40.400  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:40.400  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 09:57:40.402  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 09:57:40.407  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:40.407  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:40.407  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:40.407  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:40.407  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:40.407  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:40.407  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:40.407  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:40.410  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:40.410   927  2914 D WifiConfigStore: loaded 0 passpoint configs
11-04 09:57:40.410   927  2914 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-04 09:57:40.411   927  2914 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-04 09:57:40.411   927  2914 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-04 09:57:40.411   927  2914 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-04 09:57:40.412   927  2914 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-04 09:57:40.412   927  2914 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-04 09:57:40.413   927  2914 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 09:57:40.413   927  2914 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 09:57:40.413   927  2914 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-04 09:57:40.413   927  2914 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 09:57:40.413   927  2914 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 09:57:40.413   927  2914 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 09:57:40.417   927  2914 D WifiNative-HAL: Setting external_sim to 1
,11-04 09:57:40.417   927  2914 D wifi    : setting dfs flag to true, 0x7f5c308180
11-04 09:57:40.417  4463  4463 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 09:57:40.418   927  2914 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 09:57:40.418   927  2914 D wifi    : setting scan oui 0x7f5c308180
,11-04 09:57:40.418   927  2914 D WifiHAL : Sending mac address OUI
,11-04 09:57:40.422   927  2914 E native  : do suspend false
,11-04 09:57:40.428   927  2914 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-04 09:57:40.428   927   927 D RttService: SCAN_AVAILABLE : 3
11-04 09:57:40.429   927  3028 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-04 09:57:40.429   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-04 09:57:40.430   507   920 D CommandListener: Setting iface cfg
,11-04 09:57:40.434   927  2898 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,11-04 09:57:40.434   927  2898 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 09:57:40.444   927  2898 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 09:57:40.444   927  2898 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 09:57:40.449   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=114271 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-04 09:57:40.649  5568  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:40.649  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:40.649  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:40.649  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:40.649  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:40.649  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:40.649  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:40.649  5568  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:40.654  5568  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 09:57:40.658  5568  5616 D BluetoothAdapter: enable(): BT is already enabled..!
,11-04 09:57:40.659   927  3724 D WifiService: setWifiEnabled: true pid=5568, uid=10077
,11-04 09:57:40.659   927  3724 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 09:57:40.660  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 09:57:40.660  5568  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 09:57:40.660  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 09:57:40.660  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 09:57:40.660  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 09:57:40.661  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@696d2af removed from the list
,11-04 09:57:40.661  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 09:57:40.661  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c336bc removed from the list
,11-04 09:57:40.661  5568  5616 D io.jxcore.node.ConnectivityMonitor: stop
11-04 09:57:40.661  5568  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 09:57:40.661  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 09:57:40.664  5568  5616 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-04 09:57:40.666  5568  5616 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-04 09:57:40.668  5568  5616 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-04 09:57:40.670  5568  5616 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
11-04 09:57:40.673  5568  5616 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-04 09:57:40.674  5568  5616 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-04 09:57:40.676  5568  5616 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-04 09:57:40.676  5568  5616 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-04 09:57:40.677  5568  5616 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-04 09:57:40.680  5568  5616 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-04 09:57:40.681  5568  5616 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@aaa0ab2 Bundle[{}]
11-04 09:57:40.681  5568  5616 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-04 09:57:40.682  5568  5616 I io.jxcore.node.LifeCycleMonitor: start: OK
11-04 09:57:40.682  5568  5616 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-04 09:57:40.683  5568  5616 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-04 09:57:40.683  5568  5616 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-04 09:57:40.683  5568  5616 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-04 09:57:40.683  5568  5616 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 09:57:40.684  5568  5616 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-04 09:57:40.684  5568  5616 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-04 09:57:40.685  5568  5616 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-04 09:57:40.686  5568  5616 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-04 09:57:40.687  5568  5616 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-04 09:57:40.689  5568  5616 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
11-04 09:57:40.691  5568  5616 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-04 09:57:40.692  5568  5616 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-04 09:57:40.693  5568  5616 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-04 09:57:40.694  5568  5616 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-04 09:57:40.696  5568  5616 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
11-04 09:57:40.697  5568  5616 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-04 09:57:40.699  5568  5616 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-04 09:57:40.701  5568  5616 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-04 09:57:40.702  5568  5616 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-04 09:57:40.703  5568  5616 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-04 09:57:40.703  5568  5616 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-04 09:57:40.704  5568  5616 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-04 09:57:40.704  5568  5616 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-04 09:57:40.704  5568  5616 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 143)
11-04 09:57:40.705  5568  5616 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-04 09:57:40.706  5568  5616 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-04 09:57:40.707  5568  5616 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-04 09:57:40.707  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 09:57:40.707  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b07eacb added. We now have 3 listener(s)
11-04 09:57:40.709  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 09:57:40.710  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 09:57:40.710  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 09:57:40.710  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 09:57:40.710  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@feb02a8 added. We now have 3 listener(s)
11-04 09:57:40.710  5568  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 09:57:40.711  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 09:57:40.714  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 09:57:40.717  5568  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 09:57:40.717  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:40.717  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:40.717  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:40.717  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:40.717  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 09:57:40.717  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 09:57:40.717  5568  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 09:57:40.719  5568  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 09:57:40.719  5568  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 09:57:40.721  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 09:57:40.723  5568  5616 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-04 09:57:40.723  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 09:57:40.723  5568  5616 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-04 09:57:40.724  5568  5616 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-04 09:57:40.724  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,11-04 09:57:40.724  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 09:57:40.724  5568  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 09:57:40.724  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 09:57:40.724  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 09:57:40.726  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 09:57:40.726  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-04 09:57:40.726  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 09:57:40.726  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 09:57:40.726  5568  5894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 09:57:40.727  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 09:57:40.727  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-04 09:57:40.727  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-04 09:57:40.727  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 09:57:40.727  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 09:57:40.727  5568  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 09:57:40.730  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-04 09:57:40.730  5568  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 09:57:40.730  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 09:57:40.734  5854  5854 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33288]" dev="sockfs" ino=33288 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:40.736  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 09:57:40.736  5568  5894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 09:57:40.734  5854  5854 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33288]" dev="sockfs" ino=33288 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 09:57:40.737  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-04 09:57:40.737  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 09:57:40.739  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.739  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 09:57:40.739  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 09:57:40.740  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-04 09:57:40.740  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 09:57:40.740  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.740  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:40.740  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.740  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.741  5568  5616 D BluetoothAdapter: STATE_ON
,11-04 09:57:40.744  5823  5853 D BtGatt.GattService: registerClient() - UUID=d7e75654-0fea-44e3-9425-741cdb52d483
,11-04 09:57:40.745  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=d7e75654-0fea-44e3-9425-741cdb52d483, clientIf=5
,11-04 09:57:40.746  5568  5607 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-04 09:57:40.747  5823  5841 D BtGatt.AdvertiseManager: message : 0
,11-04 09:57:40.750  5823  5841 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 09:57:40.752  5823  5839 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 09:57:40.755  5823  5839 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 09:57:40.756  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:40.756  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.756  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 09:57:40.756  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.756  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.756  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.756  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.756  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:40.757  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 09:57:40.758  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 09:57:40.758  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:40.760  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:40.760  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.760  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:40.760  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 09:57:40.761  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 09:57:40.761  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:40.761  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 09:57:40.761  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
,11-04 09:57:40.761  5568  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-04 09:57:40.761  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 09:57:40.761  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 09:57:40.761  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 09:57:40.761  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 09:57:40.761  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 09:57:40.761  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-04 09:57:40.762  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 09:57:40.764  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 09:57:40.764  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 09:57:40.764  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 09:57:40.764  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 09:57:40.765  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 09:57:40.765  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:40.765  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 09:57:41.266  5568  5568 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-04 09:57:41.266  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 09:57:41.266  5568  5568 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 09:57:43.487  5892  5892 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 09:57:43.493  5892  5892 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 09:57:43.498  5892  5892 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 09:57:43.555   927  2914 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 09:57:43.556   927  2914 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-04 09:57:43.556   927  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 09:57:43.569   927  2914 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 09:57:43.598   927  2914 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 09:57:43.604  5892  5892 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 09:57:44.039  5892  5892 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 09:57:44.073  5892  5892 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 09:57:44.073  5892  5892 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 09:57:44.087   927  2914 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 09:57:44.087   927  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 09:57:44.087   927  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 09:57:44.106   927  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 09:57:44.122   507   920 D CommandListener: Setting iface cfg
,11-04 09:57:44.127   927  2914 D WifiStateMachine: Start Dhcp Watchdog 3
,11-04 09:57:44.134   927  5899 D DhcpClient: Receive thread started
,11-04 09:57:44.140   927  2921 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-04 09:57:44.140   927  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-04 09:57:44.140   927  2921 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-04 09:57:44.220   927  2914 E native  : do suspend false
,11-04 09:57:44.236   927  5898 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 09:57:44.255   927  5899 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
,11-04 09:57:44.256   927  5898 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds
,11-04 09:57:44.258   927  5898 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 09:57:44.263  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-04 09:57:44.263  5568  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 09:57:44.263  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 09:57:44.264  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 09:57:44.264  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 09:57:44.264  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-04 09:57:44.264  5568  5894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 09:57:44.264  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 09:57:44.264  5568  5894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 09:57:44.264  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-04 09:57:44.264  5568  5894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 09:57:44.265  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 09:57:44.265  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 09:57:44.265  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 09:57:44.265  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 09:57:44.265  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 09:57:44.266  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.266  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.269  5568  5616 D BluetoothAdapter: STATE_ON
,11-04 09:57:44.269  5568  5616 D BluetoothLeScanner: could not find callback wrapper
11-04 09:57:44.269  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 09:57:44.270  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.270  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.270  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 09:57:44.270  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.274  5823  5841 D BtGatt.AdvertiseManager: message : 1
,11-04 09:57:44.276   927  5899 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-04 09:57:44.277   927  5898 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-04 09:57:44.277  5823  5841 D BtGatt.AdvertiseManager: stop advertise for client 5
11-04 09:57:44.279   507   920 D CommandListener: Setting iface cfg
,11-04 09:57:44.282   927  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 09:57:44.288   927  5898 D DhcpClient: Scheduling renewal in 86399s
,11-04 09:57:44.293  5823  5839 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-04 09:57:44.293  5823  5839 D BtGatt.GattService: Client app is not null!
11-04 09:57:44.295  5823  5834 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 09:57:44.296  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 09:57:44.296  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.296  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 09:57:44.296  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.297  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.297  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.297  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-04 09:57:44.297  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 09:57:44.297  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.297  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.297  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 09:57:44.297  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.299   927  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-04 09:57:44.300   927  2914 D WifiConfigStore: No blacklist allowed without epno enabled
11-04 09:57:44.300   927  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-04 09:57:44.302  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.302   927  2914 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 09:57:44.302  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 09:57:44.302  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.302  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.302  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.302  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.302  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.302  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 09:57:44.302  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 09:57:44.303   927  2921 D ConnectivityService: Adding iface wlan0 to network 102
11-04 09:57:44.313  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 09:57:44.313  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.315  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.315  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.315  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.315  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 09:57:44.316  5568  5568 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 09:57:44.316  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 09:57:44.316  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 09:57:44.316  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 09:57:44.316  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 09:57:44.316  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 09:57:44.319  5568  5616 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-04 09:57:44.320  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 09:57:44.321  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-04 09:57:44.321  5568  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 09:57:44.321  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 09:57:44.321  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 09:57:44.321  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 09:57:44.325  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 09:57:44.325  5568  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 09:57:44.325  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 09:57:44.329  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 09:57:44.330  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 09:57:44.330  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 09:57:44.334  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.334  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 09:57:44.334  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 09:57:44.334  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-04 09:57:44.335  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 09:57:44.335  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.336  5568  5616 D BluetoothAdapter: STATE_ON
,11-04 09:57:44.339  5823  5863 D BtGatt.GattService: registerClient() - UUID=389e2da2-87d4-41c5-954c-218c96b5f707
11-04 09:57:44.339  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=389e2da2-87d4-41c5-954c-218c96b5f707, clientIf=5
,11-04 09:57:44.340   927  2921 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-04 09:57:44.340  5568  5578 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 09:57:44.340   927  2921 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-04 09:57:44.341  5823  5833 D BtGatt.GattService: start scan with filters
,11-04 09:57:44.341   927  2921 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-04 09:57:44.344   927  2921 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-04 09:57:44.345  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 09:57:44.345   927  2921 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
11-04 09:57:44.345  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.346  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-04 09:57:44.346  5823  5842 D BtGatt.ScanManager: handling starting scan
11-04 09:57:44.346  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.346  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.347  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 09:57:44.347  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 09:57:44.347  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.347  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.347  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-04 09:57:44.347  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.349  5823  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@602de67
,11-04 09:57:44.352  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.352  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 09:57:44.353  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.353  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 09:57:44.353  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.353  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.353  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 09:57:44.354  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 09:57:44.354  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.356  5823  5839 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 09:57:44.356  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 09:57:44.356  5823  5842 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 09:57:44.358   927  2921 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-04 09:57:44.359  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.359  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:44.359  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:44.362  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 09:57:44.362  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 09:57:44.362  5823  5842 D BtGatt.ScanManager: Starting BLE batch scan
,11-04 09:57:44.362  5823  5842 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 09:57:44.363   927  2921 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-04 09:57:44.363   927  2921 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-04 09:57:44.363   927  2921 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-04 09:57:44.364   927  2914 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 09:57:44.364   927  2921 D ConnectivityService:    accepting network in place of null
11-04 09:57:44.364   927  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 09:57:44.364   927  2921 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 09:57:44.371  5823  5839 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-04 09:57:44.371  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 09:57:44.376   927  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 09:57:44.378  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 09:57:44.378  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 09:57:44.383   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 09:57:44.401   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 09:57:44.405   927  2921 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-04 09:57:44.405   927  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 09:57:44.405  3715  3824 W QCNEJ   : |CORE| network available: 102
11-04 09:57:44.406   927  2921 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-04 09:57:44.407  3715  3824 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 09:57:44.408  3715  3824 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 09:57:44.408  3715  3824 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-04 09:57:44.409   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-04 09:57:44.415  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:44.415  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:44.415  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:44.415  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:44.415  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:44.415  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:44.415  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:44.415  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 09:57:44.417  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:44.419  3925  3925 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-04 09:57:44.421  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:44.421  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:44.421  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:44.421  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:44.421  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:44.421  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:44.421  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:44.421  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 09:57:44.421  3913  3913 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 09:57:44.424  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:44.424  3913  3913 D SystemUpdateService: onCreate
11-04 09:57:44.427  5568  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 09:57:44.427  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 09:57:44.427  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 09:57:44.427  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 09:57:44.427  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 09:57:44.427  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 09:57:44.427  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 09:57:44.427  5568  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 09:57:44.428  3913  3913 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-04 09:57:44.429  5568  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 09:57:44.438  3913  3913 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 09:57:44.443  3913  4179 I iu.UploadsManager: num queued entries: 0
,11-04 09:57:44.444  3913  4179 I iu.UploadsManager: num updated entries: 0
11-04 09:57:44.444  3913  4179 I iu.SyncManager: NEXT; no task
,11-04 09:57:44.445  3913  5911 I SystemUpdateService: active receiver: enabled
,11-04 09:57:44.448  3913  3913 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 09:57:44.449  3913  3913 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 09:57:44.451  5651  5651 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 09:57:44.454  5651  5651 D SprintDMHelper: simOperator: 
,11-04 09:57:44.455  5651  5651 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 09:57:44.474  3913  5911 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 09:57:44.483  3913  5911 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 09:57:44.483  3913  5911 I SystemUpdateService: now status is 0 (complete)
11-04 09:57:44.483  3913  5911 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 09:57:44.483  3913  5911 I SystemUpdateService: file has been verified
11-04 09:57:44.484  3913  5911 I SystemUpdateService: OTA package size = 21989297
,11-04 09:57:44.489  3913  5911 I SystemUpdateService: showing system update notification
,11-04 09:57:44.496   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 09:57:44.498  3913  3913 D SystemUpdateService: onDestroy
,11-04 09:57:44.640   927  5896 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 09:57:44.723   927  5896 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 08:57:44 GMT], X-Android-Received-Millis=[1478249864720], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478249864669]}
,11-04 09:57:44.724   927  2921 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 09:57:44.724   927  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-04 09:57:44.725   927  2921 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-04 09:57:44.728   927  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 09:57:44.747   927  2921 D ConnectivityService: handlePromptUnvalidated 101
,11-04 09:57:44.853  5568  5568 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 09:57:44.854  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 09:57:44.854  5568  5568 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 09:57:44.881  5823  5823 D BtGatt.ScanManager: awakened up at time 118703
11-04 09:57:44.884  5823  5842 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 09:57:44.913  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-04 09:57:44.913  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 09:57:44.914  5823  5839 D BtGatt.GattService: current time is 118735872862
11-04 09:57:44.914  5823  5839 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
11-04 09:57:44.917  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-04 09:57:44.918  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
11-04 09:57:44.919  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,11-04 09:57:44.923  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
,11-04 09:57:44.923  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 09:57:44.924  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-78, mTimestampNanos=118636606924}
11-04 09:57:44.924  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-04 09:57:44.924  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-85, mTimestampNanos=118336606924}
11-04 09:57:44.924  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 09:57:44.924  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=118236606924}
,11-04 09:57:45.375   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:45.406   927  2921 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,11-04 09:57:45.417  5823  5823 D BtGatt.ScanManager: awakened up at time 119239
,11-04 09:57:45.421  5823  5842 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 09:57:45.446  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
11-04 09:57:45.446  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 09:57:45.446  5823  5839 D BtGatt.GattService: current time is 119268124269
,11-04 09:57:45.446  5823  5839 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -88, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
11-04 09:57:45.447  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-04 09:57:45.447  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-04 09:57:45.447  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-04 09:57:45.448  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
11-04 09:57:45.448  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-04 09:57:45.449  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-88, mTimestampNanos=119068409060}
11-04 09:57:45.449  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-04 09:57:45.449  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=119218409060}
11-04 09:57:45.449  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-04 09:57:45.449  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=119168409060}
,11-04 09:57:46.376   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:47.362  5568  5616 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
11-04 09:57:47.362  5568  5616 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-04 09:57:47.362  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-04 09:57:47.363  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-04 09:57:47.363  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-04 09:57:47.363  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-04 09:57:47.363  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-04 09:57:47.363  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-04 09:57:47.363  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-04 09:57:47.363  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-04 09:57:47.363  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-04 09:57:47.363  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,11-04 09:57:47.363  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 09:57:47.363  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 09:57:47.365  5568  5616 D BluetoothAdapter: STATE_ON
11-04 09:57:47.367  5823  5833 D BtGatt.GattService: stopScan() - queue size =1
11-04 09:57:47.369  5823  5853 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 09:57:47.370  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-04 09:57:47.370  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.370  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 09:57:47.370  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 09:57:47.371  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.371  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 09:57:47.371  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 09:57:47.371  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 09:57:47.372  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 09:57:47.372  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:47.374  5568  5616 D BluetoothAdapter: STATE_ON
11-04 09:57:47.380  5823  5833 D BtGatt.GattService: registerClient() - UUID=42bd8234-9add-4a25-8fd9-03ef2261c2be
11-04 09:57:47.380   539   539 I ServiceManager: Waiting for service AtCmdFwd...
11-04 09:57:47.381  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=42bd8234-9add-4a25-8fd9-03ef2261c2be, clientIf=5
11-04 09:57:47.381  5823  5823 D BtGatt.ScanManager: awakened up at time 121203
11-04 09:57:47.382  5568  5578 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 09:57:47.383  5823  5863 D BtGatt.GattService: start scan with filters
11-04 09:57:47.386  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 09:57:47.386  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 09:57:47.386  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 09:57:47.386  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:47.386  5823  5842 D BtGatt.ScanManager: stopping BLe Batch
,11-04 09:57:47.386  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 09:57:47.386  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.386  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.387  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 09:57:47.387  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 09:57:47.387  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.387  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.387  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 09:57:47.387  5568  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 09:57:47.387  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-04 09:57:47.387  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 09:57:47.389  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 09:57:47.389  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 09:57:47.389  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 09:57:47.389  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 09:57:47.389  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-04 09:57:47.389  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-04 09:57:47.389  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 09:57:47.389  5568  5919 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 09:57:47.390  5568  5919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 09:57:47.391  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 09:57:47.391  5568  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 09:57:47.392  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 09:57:47.393  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 09:57:47.390  5834  5834 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[35028]" dev="sockfs" ino=35028 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:47.393  5823  5842 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 09:57:47.390  5834  5834 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[35028]" dev="sockfs" ino=35028 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 09:57:47.393  5568  5919 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-04 09:57:47.399  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.399  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:47.399  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 09:57:47.399  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 09:57:47.399  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-04 09:57:47.399  5568  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 09:57:47.399  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.399  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.399  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.400  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.400  5568  5616 D BluetoothAdapter: STATE_ON
11-04 09:57:47.403  5823  5833 D BtGatt.GattService: registerClient() - UUID=2f81dcd3-6fba-441a-95a0-a37288903faf
,11-04 09:57:47.403  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=2f81dcd3-6fba-441a-95a0-a37288903faf, clientIf=6
11-04 09:57:47.403  5568  5607 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-04 09:57:47.404  5823  5841 D BtGatt.AdvertiseManager: message : 0
,11-04 09:57:47.406  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-04 09:57:47.406  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 09:57:47.406  5823  5839 D BtGatt.GattService: current time is 121227766985
11-04 09:57:47.406  5823  5839 D BtGatt.GattService: Batch record : [64, 76, 122, -48, -44, 81, 1, -128, -92, 33, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 81, 34, 97, 112, -14, -5, 1, -128, -97, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -75, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 09:57:47.406  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
,11-04 09:57:47.406  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-04 09:57:47.407  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 09:57:47.407  5823  5842 D BtGatt.ScanManager: handling starting scan
11-04 09:57:47.407  5823  5841 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 09:57:47.413  5823  5839 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 09:57:47.413  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 09:57:47.413  5823  5842 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 09:57:47.422  5823  5839 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-04 09:57:47.427  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 09:57:47.427  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 09:57:47.427  5823  5842 D BtGatt.ScanManager: Starting BLE batch scan
11-04 09:57:47.427  5823  5842 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 09:57:47.432  5823  5839 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-04 09:57:47.432  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:47.432  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.432  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 09:57:47.432  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.432  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.433  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.433  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.433  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.433  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:47.433  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.433  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.433  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-04 09:57:47.433  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-04 09:57:47.433  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 09:57:47.434  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 09:57:47.434  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:47.437  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.437  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.437  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:47.437  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 09:57:47.437  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 09:57:47.437  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-04 09:57:47.438  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 09:57:47.438  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 09:57:47.438  5568  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:47.438  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 09:57:47.438  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-04 09:57:47.438  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 09:57:47.438  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 09:57:47.438  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 09:57:47.438  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-04 09:57:47.438  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 09:57:47.441  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 09:57:47.441  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-04 09:57:47.441  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-04 09:57:47.441  5568  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 09:57:47.441  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 09:57:47.441  5568  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 09:57:47.441  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-04 09:57:47.442  5823  5839 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 09:57:47.442  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 09:57:47.447  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 09:57:47.447  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 09:57:47.882   927  2914 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 11 -> obsolete
,11-04 09:57:47.942  5568  5568 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-04 09:57:47.942  5568  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-04 09:57:47.943  5568  5568 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 09:57:48.244   927  2914 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 11 -> obsolete
,11-04 09:57:48.381   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:49.382   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:50.382   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-04 09:57:50.441  5568  5616 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-04 09:57:50.442  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 09:57:50.442  5568  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-04 09:57:50.442  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-04 09:57:50.442  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-04 09:57:50.443  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 09:57:50.443  5568  5919 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-04 09:57:50.443  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 09:57:50.443  5568  5919 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-04 09:57:50.443  5568  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 09:57:50.443  5568  5919 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 09:57:50.444  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-04 09:57:50.444  5568  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 09:57:50.444  5568  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b07eacb removed from the list
11-04 09:57:50.444  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 09:57:50.444  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-04 09:57:50.444  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 09:57:50.444  5568  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 09:57:50.444  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 09:57:50.444  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 09:57:50.445  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.445  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.445  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-04 09:57:50.448  5568  5616 D BluetoothAdapter: STATE_ON
11-04 09:57:50.450  5823  5833 D BtGatt.GattService: stopScan() - queue size =1
11-04 09:57:50.452  5823  5863 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 09:57:50.452  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 09:57:50.453  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:50.453  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 09:57:50.453  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.453  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.453  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 09:57:50.454  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-04 09:57:50.454  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.454  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.454  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-04 09:57:50.454  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.457  5823  5823 D BtGatt.ScanManager: awakened up at time 124278
,11-04 09:57:50.461  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.461  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 09:57:50.461  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.461  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.462  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:50.462  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.462  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 09:57:50.462  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.464  5823  5841 D BtGatt.AdvertiseManager: message : 1
11-04 09:57:50.464  5823  5841 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-04 09:57:50.468  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 09:57:50.468  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 09:57:50.469  5823  5842 D BtGatt.ScanManager: stopping BLe Batch
,11-04 09:57:50.476  5823  5839 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-04 09:57:50.476  5823  5839 D BtGatt.GattService: Client app is not null!
,11-04 09:57:50.477  5823  5854 D BtGatt.GattService: unregisterClient() - clientIf=6
11-04 09:57:50.477  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 09:57:50.478  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:50.478  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 09:57:50.478  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:50.479  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.479  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.479  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 09:57:50.480  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 09:57:50.480  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.480  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.480  5568  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 09:57:50.480  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:50.483  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.483  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 09:57:50.483  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.483  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.483  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.483  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.483  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.483  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 09:57:50.484  5568  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 09:57:50.484  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 09:57:50.484  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:50.486  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.486  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 09:57:50.486  5568  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 09:57:50.486  5568  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@feb02a8 removed from the list
11-04 09:57:50.486  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 09:57:50.486  5568  5616 D io.jxcore.node.ConnectivityMonitor: stop
11-04 09:57:50.486  5568  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 09:57:50.486  5568  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 09:57:50.486  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 09:57:50.486  5568  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 09:57:50.488  5568  5616 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-04 09:57:50.489  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-04 09:57:50.489  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 09:57:50.489  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 09:57:50.489  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 09:57:50.489  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,11-04 09:57:50.489  5568  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 09:57:50.490  5568  5616 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-04 09:57:50.490  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 09:57:50.490  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 09:57:50.490  5823  5842 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 09:57:50.491  5568  5616 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-04 09:57:50.492  5568  5616 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-04 09:57:50.493  5568  5616 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-04 09:57:50.494  5568  5616 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-04 09:57:50.495  5568  5616 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-04 09:57:50.496  5568  5616 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-04 09:57:50.497  5568  5616 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-04 09:57:50.515  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,11-04 09:57:50.515  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 09:57:50.515  5823  5839 D BtGatt.GattService: current time is 124337213312
11-04 09:57:50.516  5823  5839 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 64, 76, 122, -48, -44, 81, 1, -128, -84, 3, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 37, -47, 14, -113, 116, -46, 1, -128, -84, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -76, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -94, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -82, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -116, -17, 53, -42, 34, 116, 1, -128, -102, 31, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 116, -43, -111, -91, -20, -29, 1, -128, -88, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-04 09:57:50.516  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-04 09:57:50.516  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
11-04 09:57:50.516  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-04 09:57:50.517  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-04 09:57:50.517  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-04 09:57:50.517  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 09:57:50.517  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
11-04 09:57:50.517  5823  5839 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-04 09:57:50.987  5568  5568 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 09:57:52.369   927  2921 D ConnectivityService: handlePromptUnvalidated 102
,11-04 09:57:52.502  5568  5616 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-04 09:57:52.647  5568  5921 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 09:57:52.647  5568  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 09:57:53.468  5568  5921 W !!      : call onHalfStreamCopied
,11-04 09:57:53.468  5568  5921 I testCopyDataAndClose: closing input stream
,11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 09:57:54.243  5568  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 09:57:55.383   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:55.447   927  2914 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-04 09:57:56.384   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:56.704   927  2914 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,11-04 09:57:57.386   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:58.387   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:57:58.511  5568  5616 I StreamCopyingThreadTest: Starting test: testRun
,11-04 09:57:58.517  5568  5922 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-04 09:57:58.517  5568  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 09:57:59.389   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:58:00.389   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-04 09:58:01.757  3588  3806 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-04 09:58:01.758  3588  3806 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-04 09:58:01.786  3522  3522 I ConfigService: onCreate
,11-04 09:58:03.526  5568  5923 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-04 09:58:03.528  5568  5616 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-04 09:58:03.668  5568  5925 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 09:58:03.668  5568  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 09:58:05.351  5568  5925 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 09:58:05.351  5568  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 09:58:05.351  5568  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 09:58:05.351  5568  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 09:58:05.351  5568  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 09:58:05.351  5568  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 09:58:05.351  5568  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-04 09:58:05.351  5568  5925 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 09:58:05.352  5568  5925 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 09:58:05.352  5568  5925 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 09:58:05.352  5568  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 09:58:06.819  3522  3522 I ConfigService: onDestroy
,11-04 09:58:09.239   927  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=143060, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-04 09:58:09.512  5568  5616 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-04 09:58:09.515  5568  5926 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-04 09:58:09.515  5568  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 09:58:09.516  5568  5926 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
11-04 09:58:09.516  5568  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 09:58:09.516  5568  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 09:58:09.516  5568  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 09:58:09.516  5568  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 09:58:09.516  5568  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 09:58:09.516  5568  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 09:58:09.516  5568  5926 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 09:58:09.516  5568  5926 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-04 09:58:09.517  5568  5926 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-04 09:58:09.517  5568  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-04 09:58:09.518  5568  5616 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-04 09:58:09.518  5568  5616 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-04 09:58:09.519  5568  5616 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-04 09:58:09.521  5568  5927 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-04 09:58:09.521  5568  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 09:58:09.522  5568  5927 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
,11-04 09:58:09.522  5568  5927 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-04 09:58:09.522  5568  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-04 09:58:09.522  5568  5927 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-04 09:58:09.522  5568  5927 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-04 09:58:09.522  5568  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-04 09:58:09.524  5568  5616 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-04 09:58:09.524  5568  5616 E com.test.thalitest.ThaliTestRunner: 
11-04 09:58:09.524  5568  5616 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-04 09:58:09.524  5568  5616 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 09:58:09.525  5568,  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-04 09:58:09.525  5568  5616 E com.test.t,halitest.ThaliTestRunner: Expected: is <true>
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363,)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: ,	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:58:09.525  5568  5616 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-04 09:58:09.528  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG UnitTest_app: 'Running unit tests'
11-04 09:58:09.528  5568  5616 I jxcore-log: 
11-04 09:58:09.528  5568  5616 I jxcore-log: *Native tests were executed*
11-04 09:58:09.528  5568  5616 I jxcore-log: 
11-04 09:58:09.528  5568  5616 I jxcore-log: Total number of executed tests:  82
11-04 09:58:09.528  5568  5616 I jxcore-log: 
11-04 09:58:09.528  5568  5616 I jxcore-log: Number of passed tests:  80
11-04 09:58:09.528  5568  5616 I jxcore-log: 
11-04 09:58:09.528  5568  5616 I jxcore-log: Number of failed tests:  2
11-04 09:58:09.528  5568  5616 I jxcore-log: 
11-04 09:58:09.528  5568  5616 I jxcore-log: Number of ignored tests:  0
11-04 09:58:09.528  5568  5616 I jxcore-log: 
11-04 09:58:09.528  5568  5616 I jxcore-log: Total duration:  45922
11-04 09:58:09.528  5568  5616 I jxcore-log: 
11-04 09:58:09.528  5568  5616 I jxcore-log: Failed to execute UT.
11-04 09:58:09.528  5568  5616 I jxcore-log: 
11-04 09:58:09.529  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-04 09:58:09.529  5568  5616 I jxcore-log: 
11-04 09:58:09.531  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-04 09:58:09.531  5568  5616 I jxcore-log: 
11-04 09:58:09.535  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.535  5568  5616 I jxcore-log: 
11-04 09:58:09.535  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.535  5568  5616 I jxcore-log: 
11-04 09:58:09.536  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.536  5568  5616 I jxcore-log: 
11-04 09:58:09.537  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.537  5568  5616 I jxcore-log: 
11-04 09:58:09.538  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.538  5568  5616 I jxcore-log: 
11-04 09:58:09.538  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.538  5568  5616 I jxcore-log: 
11-04 09:58:09.538  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive",:false,"advertisingActive":true}'
11-04 09:58:09.538  5568  5616 I jxcore-log: 
11-04 09:58:09.539  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 09:58:09.539  5568  5616 I jxcore-log: 
11-04 09:58:09.539  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 09:58:09.539  5568  5616 I jxcore-log: 
11-04 09:58:09.539  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 09:58:09.539  5568  5616 I jxcore-log: 
11-04 09:58:09.540  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.540  5568  5616 I jxcore-log: 
11-04 09:58:09.540  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.540  5568  5616 I jxcore-log: 
11-04 09:58:09.540  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.540  5568  5616 I jxcore-log: 
11-04 09:58:09.540  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.540  5568  5616 I jxcore-log: 
11-04 09:58:09.540  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 09:58:09.540  5568  5616 I jxcore-log: 
11-04 09:58:09.541  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.541  5568  5616 I jxcore-log: 
11-04 09:58:09.541  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 09:58:09.541  5568  5616 I jxcore-log: 
11-04 09:58:09.541  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.541  5568  5616 I jxcore-log: 
11-04 09:58:09.541  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 09:58:09.541  5568  5616 I jxcore-log: 
11-04 09:58:09.541  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.541  5568  5616 I jxcore-log: 
11-04 09:58:09.542  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 09:58:09.542  5568  5616 I jxcore-log: 
11-04 09:58:09.542  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.542  5568  5616 I jxcore-log: 
11-04 09:58:09.542  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.542  5568  5616 I jxcore-log: 
11-04 09:58:09.542  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.542  5568  5616 I jxcore-log: 
11-04 09:58:09.543  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.543  5568  5616 I jxcore-log: 
11-04 09:58:09.543  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.543  5568  5616 I jxcore-log: 
11-04 09:58:09.543  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.543  5568  5616 I jxcore-log: 
11-04 09:58:09.544  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.544  5568  5616 I jxcore-log: 
11-04 09:58:09.544  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.544  5568  5616 I jxcore-log: 
11-04 09:58:09.546  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.546  5568  5616 I jxcore-log: 
11-04 09:58:09.546  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.546  5568  5616 I jxcore-log: 
11-04 09:58:09.546  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.546  5568  5616 I jxcore-log: 
11-04 09:58:09.546  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.546  5568  5616 I jxcore-log: 
11-04 09:58:09.547  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.547  5568  5616 I jxcore-log: 
11-04 09:58:09.547  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.547  5568  5616 I jxcore-log: 
11-04 09:58:09.547  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.547  5568  5616 I jxcore-log: 
11-04 09:58:09.547  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.547  5568  5616 I jxcore-log: 
11-04 09:58:09.547  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.547  5568  5616 I jxcore-log: 
11-04 09:58:09.547  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.547  5568  5616 I jxcore-log: 
11-04 09:58:09.548  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.548  5568  5616 I jxcore-log: 
11-04 09:58:09.548  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.548  5568  5616 I jxcore-log: 
11-04 09:58:09.548  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.548  5568  5616 I jxcore-log: 
11-04 09:58:09.548  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.548  5568  5616 I jxcore-log: 
11-04 09:58:09.548  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.548  5568  5616 I jxcore-log: 
11-04 09:58:09.549  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.549  5568  5616 I jxcore-log: 
11-04 09:58:09.549  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.549  5568  5616 I jxcore-log: 
11-04 09:58:09.549  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.549  5568  5616 I jxcore-log: 
11-04 09:58:09.549  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.549  5568  5616 I jxcore-log: 
11-04 09:58:09.549  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.549  5568  5616 I jxcore-log: 
11-04 09:58:09.550  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.550  5568  5616 I jxcore-log: 
11-04 09:58:09.550  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.550  5568  5616 I jxcore-log: 
11-04 09:58:09.550  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.550  5568  5616 I jxcore-log: 
11-04 09:58:09.550  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.550  5568  5616 I jxcore-log: 
11-04 09:58:09.550  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.550  5568  5616 I jxcore-log: 
11-04 09:58:09.550  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.550  5568  5616 I jxcore-log: 
11-04 09:58:09.551  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.551  5568  5616 I jxcore-log: 
11-04 09:58:09.551  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.551  5568  5616 I jxcore-log: 
11-04 09:58:09.551  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.551  5568  5616 I jxcore-log: 
11-04 09:58:09.551  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.551  5568  5616 I jxcore-log: 
11-04 09:58:09.551  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 09:58:09.551  5568  5616 I jxcore-log: 
11-04 09:58:09.552  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.552  5568  5616 I jxcore-log: 
11-04 09:58:09.552  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 09:58:09.552  5568  5616 I jxcore-log: 
11-04 09:58:09.552  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.552  5568  5616 I jxcore-log: 
11-04 09:58:09.552  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 09:58:09.552  5568  5616 I jxcore-log: 
11-04 09:58:09.552  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.552  5568  5616 I jxcore-log: 
11-04 09:58:09.553  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.553  5568  5616 I jxcore-log: 
11-04 09:58:09.553  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.553  5568  5616 I jxcore-log: 
11-04 09:58:09.553  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.553  5568  5616 I jxcore-log: 
11-04 09:58:09.553  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.553  5568  5616 I jxcore-log: 
11-04 09:58:09.553  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.553  5568  5616 I jxcore-log: 
11-04 09:58:09.553  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.553  5568  5616 I jxcore-log: 
11-04 09:58:09.554  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 09:58:09.554  5568  5616 I jxcore-log: 
11-04 09:58:09.554  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.554  5568  5616 I jxcore-log: 
11-04 09:58:09.554  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 09:58:09.554  5568  5616 I jxcore-log: 
11-04 09:58:09.554  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.554  5568  5616 I jxcore-log: 
11-04 09:58:09.554  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.554  5568  5616 I jxcore-log: 
11-04 09:58:09.555  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.555  5568  5616 I jxcore-log: 
11-04 09:58:09.555  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.555  5568  5616 I jxcore-log: 
11-04 09:58:09.555  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 09:58:09.555  5568  5616 I jxcore-log: 
11-04 09:58:09.555  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 09:58:09.555  5568  5616 I jxcore-log: 
11-04 09:58:09.555  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 09:58:09.555  5568  5616 I jxcore-log: 
11-04 09:58:09.556  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-04 09:58:09.556  5568  5616 I jxcore-log: 
11-04 09:58:09.555  5568  5568 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-04 09:58:09.556  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 09:58:09.556  5568  5616 I jxcore-log: 
11-04 09:58:09.561  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-04 09:58:09.561  5568  5616 I jxcore-log: 
11-04 09:58:09.561  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - WARN testUtils: 'myNameCallback not set!'
11-04 09:58:09.561  5568  5616 I jxcore-log: 
11-04 09:58:09.562  5568  5616 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-04 09:58:09.563  5568  5616 I jxcore-log: 2016-11-04 08:58:09 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-04 09:58:09.563  5568  5616 I jxcore-log: 
,11-04 09:58:10.391   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:58:11.392   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:58:11.626  5568  5616 I jxcore-log: 2016-11-04 08:58:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-04 09:58:11.626  5568  5616 I jxcore-log: 
,11-04 09:58:11.959  5568  5616 I jxcore-log: 2016-11-04 08:58:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-04 09:58:11.959  5568  5616 I jxcore-log: 
,11-04 09:58:11.973  5568  5616 I jxcore-log: 2016-11-04 08:58:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-04 09:58:11.973  5568  5616 I jxcore-log: 
,11-04 09:58:12.393   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:58:13.079  5568  5616 I jxcore-log: 2016-11-04 08:58:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-04 09:58:13.079  5568  5616 I jxcore-log: 
,11-04 09:58:13.249  5568  5616 I jxcore-log: 2016-11-04 08:58:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-04 09:58:13.249  5568  5616 I jxcore-log: 
,11-04 09:58:13.254  5568  5616 I jxcore-log: 2016-11-04 08:58:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-04 09:58:13.254  5568  5616 I jxcore-log: 
,11-04 09:58:13.259  5568  5616 I jxcore-log: 2016-11-04 08:58:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-04 09:58:13.259  5568  5616 I jxcore-log: 
,11-04 09:58:13.394   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:58:13.742  5568  5616 I jxcore-log: 2016-11-04 08:58:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-04 09:58:13.742  5568  5616 I jxcore-log: 
,11-04 09:58:13.786  5568  5616 I jxcore-log: 2016-11-04 08:58:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-04 09:58:13.786  5568  5616 I jxcore-log: 
,11-04 09:58:13.799  5568  5616 I jxcore-log: 2016-11-04 08:58:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-04 09:58:13.799  5568  5616 I jxcore-log: 
,11-04 09:58:13.803  5568  5616 I jxcore-log: 2016-11-04 08:58:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-04 09:58:13.803  5568  5616 I jxcore-log: 
,11-04 09:58:14.090  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-04 09:58:14.090  5568  5616 I jxcore-log: 
,11-04 09:58:14.233  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-04 09:58:14.233  5568  5616 I jxcore-log: 
,11-04 09:58:14.394   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 09:58:14.604  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-04 09:58:14.604  5568  5616 I jxcore-log: 
,11-04 09:58:14.638  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-04 09:58:14.638  5568  5616 I jxcore-log: 
,11-04 09:58:14.644  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-04 09:58:14.644  5568  5616 I jxcore-log: 
,11-04 09:58:14.649  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-04 09:58:14.649  5568  5616 I jxcore-log: 
,11-04 09:58:14.657  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-04 09:58:14.657  5568  5616 I jxcore-log: 
,11-04 09:58:14.670  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-04 09:58:14.670  5568  5616 I jxcore-log: 
,11-04 09:58:14.675  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-04 09:58:14.675  5568  5616 I jxcore-log: 
,11-04 09:58:14.702  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-04 09:58:14.702  5568  5616 I jxcore-log: 
,11-04 09:58:14.739  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-04 09:58:14.739  5568  5616 I jxcore-log: 
,11-04 09:58:14.746  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-04 09:58:14.746  5568  5616 I jxcore-log: 
,11-04 09:58:14.753  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-04 09:58:14.753  5568  5616 I jxcore-log: 
,11-04 09:58:14.768  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-04 09:58:14.768  5568  5616 I jxcore-log: 
,11-04 09:58:14.772  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-04 09:58:14.772  5568  5616 I jxcore-log: 
,11-04 09:58:14.778  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-04 09:58:14.778  5568  5616 I jxcore-log: 
,11-04 09:58:14.783  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-04 09:58:14.783  5568  5616 I jxcore-log: 
,11-04 09:58:14.797  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-04 09:58:14.797  5568  5616 I jxcore-log: 
,11-04 09:58:14.804  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-04 09:58:14.804  5568  5616 I jxcore-log: 
,11-04 09:58:14.826  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-04 09:58:14.826  5568  5616 I jxcore-log: 
,11-04 09:58:14.837  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-04 09:58:14.837  5568  5616 I jxcore-log: 
,11-04 09:58:14.848  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-04 09:58:14.848  5568  5616 I jxcore-log: 
,11-04 09:58:14.858  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-04 09:58:14.858  5568  5616 I jxcore-log: 
,11-04 09:58:14.872  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-04 09:58:14.872  5568  5616 I jxcore-log: 
,11-04 09:58:14.881  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-04 09:58:14.881  5568  5616 I jxcore-log: 
,11-04 09:58:14.888  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-04 09:58:14.888  5568  5616 I jxcore-log: 
,11-04 09:58:14.894  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-04 09:58:14.894  5568  5616 I jxcore-log: 
,11-04 09:58:14.900  5568  5616 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-04 09:58:14.901  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - INFO testUtils: 'BLE multiple advertisement supported'
11-04 09:58:14.901  5568  5616 I jxcore-log: 
,11-04 09:58:14.973  5568  5616 I jxcore-log: 2016-11-04 08:58:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:14.973  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:14.973  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:14.973  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:14.973  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:14.973  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:14.973  5568  5616 I jxcore-log: 
,11-04 09:58:15.216  5568  5616 I jxcore-log: 2016-11-04 08:58:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:15.216  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:15.216  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:15.216  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:15.216  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:15.216  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:15.216  5568  5616 I jxcore-log: 
,11-04 09:58:15.220  5568  5616 I jxcore-log: 2016-11-04 08:58:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:15.220  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:15.220  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:15.220  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:15.220  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:15.220  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:15.220  5568  5616 I jxcore-log: 
,11-04 09:58:15.395   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-04 09:58:15.765  5568  5616 I jxcore-log: 2016-11-04 08:58:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:15.765  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:15.765  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:15.765  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:15.765  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:15.765  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:15.765  5568  5616 I jxcore-log: 
,11-04 09:58:15.768  5568  5616 I jxcore-log: 2016-11-04 08:58:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:15.768  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:15.768  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:15.768  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:15.768  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:15.768  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:15.768  5568  5616 I jxcore-log: 
,11-04 09:58:16.680  5568  5616 I jxcore-log: 2016-11-04 08:58:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:16.680  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:16.680  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:16.680  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:16.680  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:16.680  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:16.680  5568  5616 I jxcore-log: 
,11-04 09:58:16.686  5568  5616 I jxcore-log: 2016-11-04 08:58:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:16.686  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:16.686  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:16.686  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:16.686  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:16.686  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:16.686  5568  5616 I jxcore-log: 
,11-04 09:58:17.651  5568  5616 I jxcore-log: 2016-11-04 08:58:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:17.651  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:17.651  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:17.651  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:17.651  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:17.651  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:17.651  5568  5616 I jxcore-log: 
,11-04 09:58:17.658  5568  5616 I jxcore-log: 2016-11-04 08:58:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:17.658  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:17.658  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:17.658  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:17.658  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:17.658  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:17.658  5568  5616 I jxcore-log: 
,11-04 09:58:18.532   927   947 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-04 09:58:18.537  3745  3745 W Binder_A: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32965]" dev="sockfs" ino=32965 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:18.543  3588  3588 I Keyboard.Facilitator: onFinishInput()
,11-04 09:58:18.540  3745  3745 W Binder_A: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[32965]" dev="sockfs" ino=32965 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:18.551   927   947 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 09:58:18.551   927   947 I Adreno  : Build Date                       : 12/06/15
11-04 09:58:18.551   927   947 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 09:58:18.551   927   947 I Adreno  : Local Branch                     : mybranch17112971
11-04 09:58:18.551   927   947 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 09:58:18.551   927   947 I Adreno  : Remote Branch                    : NONE
11-04 09:58:18.551   927   947 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 09:58:18.588   382   408 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (218 us)
,11-04 09:58:18.681  5568  5616 I jxcore-log: 2016-11-04 08:58:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:18.681  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:18.681  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:18.681  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:18.681  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:18.681  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:18.681  5568  5616 I jxcore-log: 
,11-04 09:58:18.684  5568  5616 I jxcore-log: 2016-11-04 08:58:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:18.684  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:18.684  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:18.684  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:18.684  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:18.684  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:18.684  5568  5616 I jxcore-log: 
,11-04 09:58:19.316  5568  5568 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-04 09:58:19.317  5568  5568 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-04 09:58:19.353   927   947 I sensors : batch
,11-04 09:58:19.354   927   947 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-04 09:58:19.358  5568  5568 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@aaa0ab2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d9fc6ec, 16908290=android.view.AbsSavedState$1@d9fc6ec}, android:focusedViewId=100}]}]
11-04 09:58:19.358  5568  5568 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-04 09:58:19.359   927   947 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-04 09:58:19.359   927   947 I sensors : activate
11-04 09:58:19.359  5568  5568 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 09:58:19.360  5568  5568 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-04 09:58:19.361   927   945 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-04 09:58:19.365   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f8f303c00
11-04 09:58:19.365   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-04 09:58:19.366   927  2714 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-04 09:58:19.368   927  2714 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-04 09:58:19.584   507   920 D TetherController: Setting IP forward enable = 1
,11-04 09:58:19.661   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-04 09:58:19.662   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-04 09:58:19.662   927  3031 D SurfaceControl: Excessive delay in setPowerMode(): 301ms
,11-04 09:58:19.666   927   947 I DreamManagerService: Entering dreamland.
11-04 09:58:19.667   927   947 I PowerManagerService: Dozing...
,11-04 09:58:19.667   927   942 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-04 09:58:19.684  3716  3716 W Binder_8: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[34775]" dev="sockfs" ino=34775 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:19.684  3716  3716 W Binder_8: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[34775]" dev="sockfs" ino=34775 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 09:58:19.686   927  3745 I sensors : batch
11-04 09:58:19.686   927  3745 I sensors : activate
,11-04 09:58:19.690   927  2714 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-04 09:58:19.690   927  2714 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-04 09:58:19.694   512   512 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-04 09:58:19.698  5568  5616 I jxcore-log: 2016-11-04 08:58:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:19.698  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:19.698  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:19.698  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:19.698  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:19.698  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:19.698  5568  5616 I jxcore-log: 
,11-04 09:58:19.700  5568  5616 I jxcore-log: 2016-11-04 08:58:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:19.700  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:19.700  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:19.700  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:19.700  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:19.700  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:19.700  5568  5616 I jxcore-log: 
11-04 09:58:19.700   927  2914 E native  : do suspend false
,11-04 09:58:19.707   927  2914 D WifiConfigStore: No blacklist allowed without epno enabled
,11-04 09:58:19.713  3753  4704 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-04 09:58:19.713  3753  4704 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 09:58:19.714  3753  4704 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 09:58:19.714   525  1140 D         : oem-qmi: Connection accepted
11-04 09:58:19.714   525  1140 D         : oem-qmi: Waiting to accept connection
,11-04 09:58:19.715   927   927 I sensors : activate
,11-04 09:58:19.716  3753  4704 D         : oem_qmi_lib:output 0
11-04 09:58:19.716  3753  4704 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
11-04 09:58:19.716   512  2985 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-04 09:58:19.718   927  2714 I hubconnection: sensorhub said: 'activate 31 enable:0'
11-04 09:58:19.718   927  2914 E native  : do suspend true
,11-04 09:58:19.735  3753  4704 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
11-04 09:58:19.735  3753  4704 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 09:58:19.735  3753  4704 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
,11-04 09:58:19.735   525  1140 D         : oem-qmi: Connection accepted
11-04 09:58:19.735   525  1140 D         : oem-qmi: Waiting to accept connection
,11-04 09:58:19.737  3753  4704 D         : oem_qmi_lib:output 0
,11-04 09:58:19.737  3753  4704 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 09:58:19.965   927  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153787, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-04 09:58:20.196   927  2914 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-04 09:58:20.735  5568  5616 I jxcore-log: 2016-11-04 08:58:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:20.735  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:20.735  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:20.735  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:20.735  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:20.735  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:20.735  5568  5616 I jxcore-log: 
,11-04 09:58:20.740  5568  5616 I jxcore-log: 2016-11-04 08:58:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:20.740  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:20.740  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:20.740  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:20.740  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:20.740  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:20.740  5568  5616 I jxcore-log: 
,11-04 09:58:21.773  5568  5616 I jxcore-log: 2016-11-04 08:58:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:21.773  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:21.773  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:21.773  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:21.773  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:21.773  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:21.773  5568  5616 I jxcore-log: 
,11-04 09:58:21.776  5568  5616 I jxcore-log: 2016-11-04 08:58:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:21.776  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:21.776  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:21.776  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:21.776  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:21.776  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:21.776  5568  5616 I jxcore-log: 
,11-04 09:58:22.810  5568  5616 I jxcore-log: 2016-11-04 08:58:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:22.810  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:22.810  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:22.810  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:22.810  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:22.810  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:22.810  5568  5616 I jxcore-log: 
,11-04 09:58:22.816  5568  5616 I jxcore-log: 2016-11-04 08:58:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:22.816  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:22.816  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:22.816  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:22.816  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:22.816  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:22.816  5568  5616 I jxcore-log: 
,11-04 09:58:23.337  3681  4395 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-04 09:58:23.884  5568  5616 I jxcore-log: 2016-11-04 08:58:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:23.884  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:23.884  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:23.884  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:23.884  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:23.884  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:23.884  5568  5616 I jxcore-log: 
,11-04 09:58:23.888  5568  5616 I jxcore-log: 2016-11-04 08:58:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:23.888  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:23.888  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:23.888  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:23.888  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:23.888  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:23.888  5568  5616 I jxcore-log: 
,11-04 09:58:24.342   927  2914 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,11-04 09:58:24.923  5568  5616 I jxcore-log: 2016-11-04 08:58:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:24.923  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:24.923  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:24.923  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:24.923  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:24.923  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:24.923  5568  5616 I jxcore-log: 
,11-04 09:58:24.930  5568  5616 I jxcore-log: 2016-11-04 08:58:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:24.930  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:24.930  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:24.930  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:24.930  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:24.930  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:24.930  5568  5616 I jxcore-log: 
,11-04 09:58:25.963  5568  5616 I jxcore-log: 2016-11-04 08:58:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:25.963  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:25.963  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:25.963  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:25.963  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:25.963  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:25.963  5568  5616 I jxcore-log: 
,11-04 09:58:25.966  5568  5616 I jxcore-log: 2016-11-04 08:58:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:25.966  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:25.966  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:25.966  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:25.966  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:25.966  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:25.966  5568  5616 I jxcore-log: 
,11-04 09:58:26.997  5568  5616 I jxcore-log: 2016-11-04 08:58:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:26.997  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:26.997  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:26.997  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:26.997  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:26.997  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:26.997  5568  5616 I jxcore-log: 
,11-04 09:58:27.002  5568  5616 I jxcore-log: 2016-11-04 08:58:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:27.002  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:27.002  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:27.002  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:27.002  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:27.002  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:27.002  5568  5616 I jxcore-log: 
,11-04 09:58:28.034  5568  5616 I jxcore-log: 2016-11-04 08:58:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:28.034  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:28.034  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:28.034  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:28.034  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:28.034  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:28.034  5568  5616 I jxcore-log: 
,11-04 09:58:28.038  5568  5616 I jxcore-log: 2016-11-04 08:58:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:28.038  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:28.038  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:28.038  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:28.038  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:28.038  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:28.038  5568  5616 I jxcore-log: 
,11-04 09:58:29.324  5568  5616 I jxcore-log: 2016-11-04 08:58:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 09:58:29.324  5568  5616 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 09:58:29.324  5568  5616 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 09:58:29.324  5568  5616 I jxcore-log: emit@events.js:82:1
11-04 09:58:29.324  5568  5616 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 09:58:29.324  5568  5616 I jxcore-log: emit@events.js:82:1'
11-04 09:58:29.324  5568  5616 I jxcore-log: 
,11-04 09:58:29.338  5568  5616 E jxcore  : Error!: error is undefined
11-04 09:58:29.338  5568  5616 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-04 09:58:29.341  5568  5616 I jxcore-log: 2016-11-04 08:58:29 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-04 09:58:29.341  5568  5616 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-04 09:58:29.341  5568  5616 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-04 09:58:29.341  5568  5616 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-04 09:58:29.341  5568  5616 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-04 09:58:29.341  5568  5616 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-04 09:58:29.341  5568  5616 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-04 09:58:29.341  5568  5616 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-04 09:58:29.343  5568  5616 I jxcore-log: 2016-11-04 08:58:29 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-04 09:58:29.343  5568  5616 I jxcore-log: 
,11-04 09:58:29.345  5568  5616 E jxcore-log: TypeError: 
11-04 09:58:29.345  5568  5616 E jxcore-log: error is undefined
11-04 09:58:29.345  5568  5616 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-04 09:58:29.345  5568  5616 E jxcore-log: 
,11-04 09:58:29.433   927  3716 I WindowState: WIN DEATH: Window{8c529ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-04 09:58:29.433   927  3099 D GraphicsStats: Buffer count: 2
,11-04 09:58:29.434   927  2920 D WifiService: Client connection lost with reason: 4
,11-04 09:58:29.444   927   938 I ActivityManager: Process com.test.thalitest (pid 5568) has died
,11-04 09:58:29.443   527   527 I Zygote  : Process 5568 exited cleanly (139)
,11-04 09:58:29.456   927   938 I ActivityManager: Start proc 5973:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-04 09:58:29.527  5973  5973 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-04 09:58:29.547  5973  5973 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-04 09:58:29.553  5973  5973 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3373-3375)
,11-04 09:58:29.553  5973  5973 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 09:58:29.564  5973  5973 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {617506f}
,11-04 09:58:29.564  5973  5973 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 09:58:29.564  5973  5973 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 09:58:29.567  5973  5973 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 09:58:29.568  5973  5973 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 09:58:29.579  5973  5973 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 09:58:29.587  5973  5973 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 09:58:29.587  5973  5973 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 09:58:29.587  5973  5973 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 09:58:29.587  5973  5973 I Adreno  : Build Date                       : 12/06/15
11-04 09:58:29.587  5973  5973 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 09:58:29.587  5973  5973 I Adreno  : Local Branch                     : mybranch17112971
11-04 09:58:29.587  5973  5973 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 09:58:29.587  5973  5973 I Adreno  : Remote Branch                    : NONE
11-04 09:58:29.587  5973  5973 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 09:58:29.619   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8d997f7:true
,11-04 09:58:29.630  4165  4165 W Binder_5: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[30299]" dev="sockfs" ino=30299 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:29.630  4165  4165 W Binder_5: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[30299]" dev="sockfs" ino=30299 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:29.644  5973  5973 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 09:58:29.652  5973  5973 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 09:58:29.674  4165  4165 W Binder_5: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[34814]" dev="sockfs" ino=34814 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:29.678  5973  6009 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-04 09:58:29.674  4165  4165 W Binder_5: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[34814]" dev="sockfs" ino=34814 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:29.677  3536  3536 W Binder_6: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[16715]" dev="sockfs" ino=16715 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:29.677  3536  3536 W Binder_6: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[16715]" dev="sockfs" ino=16715 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:29.682  5973  5996 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 09:58:29.715  5973  6009 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 09:58:29.727  3537  3537 W Binder_7: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[37892]" dev="sockfs" ino=37892 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 09:58:29.727  3537  3537 W Binder_7: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[37892]" dev="sockfs" ino=37892 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:29.727  3724  3724 W Binder_9: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[37891]" dev="sockfs" ino=37891 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 09:58:29.727  3724  3724 W Binder_9: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[37891]" dev="sockfs" ino=37891 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 09:58:29.733  3588  3588 I Keyboard.Facilitator: onFinishInput()
,11-04 09:58:29.753   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +276ms (total +308ms)
,11-04 09:58:29.756  5973  5973 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5973
,11-04 09:58:29.784  5971  5971 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-04 09:58:29.787  5971  5971 D AndroidRuntime: CheckJNI is OFF
,11-04 09:58:29.810  5971  5971 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-04 09:58:29.821  5973  5973 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 09:58:29.833  5971  5971 I Radio-JNI: register_android_hardware_Radio DONE
,11-04 09:58:29.849  5971  5971 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-04 09:58:29.856   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-04 09:58:29.857   927   940 I ActivityManager: Killing 5973:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-04 09:58:29.890   927  3102 D GraphicsStats: Buffer count: 2
,11-04 09:58:29.890   927  3724 I WindowState: WIN DEATH: Window{f07cb32 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-04 09:58:29.992   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-04 09:58:29.993   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-04 09:58:29.995   927   940 E ActivityManager: Failure starting process com.test.thalitest
11-04 09:58:29.995   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-04 09:58:29.995   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:58:29.995   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:58:29.995   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 09:58:29.995   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-04 09:58:29.996   927   950 I art     : Starting a blocking GC Explicit
,11-04 09:58:29.997   927   940 I ActivityManager:   Force finishing activity ActivityRecord{ee103b4 u0 com.test.thalitest/.MainActivity t68}
,11-04 09:58:30.004   927  3149 W ActivityManager: Spurious death for ProcessRecord{7ee8200 0:com.test.thalitest/u0a77}, curProc for 5973: null
,11-04 09:58:30.091   927   950 I art     : Explicit concurrent mark sweep GC freed 16918(1136KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 1.622ms total 95.185ms
,11-04 09:58:30.114   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-04 09:58:30.119  5971  5971 I art     : System.exit called, status: 0
,11-04 09:58:30.119  5971  5971 I AndroidRuntime: VM exiting with result code 0.
,11-04 09:58:30.126   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-04 09:58:30.136   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
11-04 09:58:30.141  5823  5823 D BluetoothMapAppObserver: onReceive
11-04 09:58:30.141  5823  5823 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-04 09:58:30.147  3681  4029 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-04 09:58:30.158  3588  3588 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-04 09:58:30.162   927  2885 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-04 09:58:30.185  3588  6026 I Keyboard.Facilitator.DecoderInitializer: run()
,11-04 09:58:30.190  3344  6027 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-04 09:58:30.194    28    28 W kworker/1:1: type=1400 audit(0.0:141): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 09:58:30.200    28    28 W kworker/1:1: type=1400 audit(0.0:142): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 09:58:30.207  3753  3753 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
11-04 09:58:30.212   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-04 09:58:30.214  3522  3522 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-04 09:58:30.216  3522  3522 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-04 09:58:30.217  3522  3522 E AndroidRuntime: FATAL EXCEPTION: main
11-04 09:58:30.217  3522  3522 E AndroidRuntime: Process: com.google.process.gapps, PID: 3522
11-04 09:58:30.217  3522  3522 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-04 09:58:30.217  3522  3522 E AndroidRuntime: 	... 8 more
,11-04 09:58:30.223  3588  6026 I Decoder : createOrResetDecoder
,11-04 09:58:30.225  3522  3522 I Process : Sending signal. PID: 3522 SIG: 9
,11-04 09:58:30.225   380   380 E lowmemorykiller: Error writing /proc/3522/oom_score_adj; errno=22
,11-04 09:58:30.232  3777  3876 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-04 09:58:30.230    28    28 W kworker/1:1: type=1400 audit(0.0:143): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 09:58:30.237   927  2920 D WifiService: Client connection lost with reason: 4
,11-04 09:58:30.248   927  3536 I ActivityManager: Start proc 6032:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-04 09:58:30.248  3777  3876 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-04 09:58:30.248  3777  3876 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3777
11-04 09:58:30.248  3777  3876 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-04 09:58:30.248  3777  3876 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-04 09:58:30.264   927  3784 I ActivityManager: Process com.google.process.gapps (pid 3522) has died
11-04 09:58:30.264   927  3784 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,11-04 09:58:30.264   927  3784 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
11-04 09:58:30.264   927  3784 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 21000ms
11-04 09:58:30.265  3344  3371 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj33EB71968) - 
,11-04 09:58:30.278   927  3099 I ActivityManager: Start proc 6044:com.google.process.gapps/u0a12 for service com.google.android.gms/.config.ConfigService
,11-04 09:58:30.284   927  3102 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-04 09:58:30.286   927  6054 E DropBoxManagerService: Can't write: system_app_crash
11-04 09:58:30.286   927  6054 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 09:58:30.286   927  6054 E DropBoxManagerService: 	... 5 more
11-04 09:58:30.288  3344  6027 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-04 09:58:30.293  3777  3876 I Process : Sending signal. PID: 3777 SIG: 9

```
