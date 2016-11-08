#### Test 8962479670bc939_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-08 17:40:38.656  3964  4130 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-08 17:40:38.741  3964  4130 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-08 17:40:39.132  5489  5489 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-08 17:40:39.137  5489  5489 D AndroidRuntime: CheckJNI is OFF
11-08 17:40:39.165  5489  5489 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-08 17:40:39.197  5489  5489 I Radio-JNI: register_android_hardware_Radio DONE
11-08 17:40:39.213  5489  5489 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-08 17:40:39.216   928  3328 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-08 17:40:39.234  5489  5489 D AndroidRuntime: Shutting down VM
11-08 17:40:39.238  3870  3884 W SearchService: Abort, client detached.
11-08 17:40:39.249  3870  3870 I HotwordDetector: Closing mic
11-08 17:40:39.249  3870  4121 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c88f9ea
11-08 17:40:39.249  3870  4125 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-08 17:40:39.264   928   939 I ActivityManager: Start proc 5499:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-08 17:40:39.322   513  4128 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-08 17:40:39.323   513  4128 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-08 17:40:39.330   513  4128 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-08 17:40:39.331   513  4128 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-08 17:40:39.332   513  2907 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-08 17:40:39.334  3870  4122 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-08 17:40:39.334  3870  4124 I MicroRecognitionRnrImpl: Detection finished
11-08 17:40:39.367  5499  5499 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-08 17:40:39.389  5499  5499 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-08 17:40:39.451  5499  5499 I LibraryLoader: Time to load native libraries: 54 ms (timestamps 6050-6104)
11-08 17:40:39.451  5499  5499 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 17:40:39.482  5499  5499 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2b61a65}
,11-08 17:40:39.482  5499  5499 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-08 17:40:39.483  5499  5499 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-08 17:40:39.488  5499  5499 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-08 17:40:39.490  5499  5499 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-08 17:40:39.545  5499  5499 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-08 17:40:39.562  5499  5499 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-08 17:40:39.563  5499  5499 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 17:40:39.563  5499  5499 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 17:40:39.563  5499  5499 I Adreno  : Build Date                       : 12/06/15
11-08 17:40:39.563  5499  5499 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 17:40:39.563  5499  5499 I Adreno  : Local Branch                     : mybranch17112971
11-08 17:40:39.563  5499  5499 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 17:40:39.563  5499  5499 I Adreno  : Remote Branch                    : NONE
11-08 17:40:39.563  5499  5499 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 17:40:39.609   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a1f5679:true
,11-08 17:40:39.642   407   407 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[23263]" dev="sockfs" ino=23263 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-08 17:40:39.642   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[23263]" dev="sockfs" ino=23263 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:40:39.653  5499  5499 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-08 17:40:39.661  5499  5499 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-08 17:40:39.682   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32080]" dev="sockfs" ino=32080 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:40:39.685  5499  5536 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-08 17:40:39.682   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32080]" dev="sockfs" ino=32080 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:40:39.686  3102  3102 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[23274]" dev="sockfs" ino=23274 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:40:39.686  3102  3102 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[23274]" dev="sockfs" ino=23274 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:40:39.689  5499  5523 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-08 17:40:39.713  5499  5536 I OpenGLRenderer: Initialized EGL, version 1.4
,11-08 17:40:39.782  3701  3701 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32084]" dev="sockfs" ino=32084 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:40:39.782  3701  3701 W Binder_9: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32084]" dev="sockfs" ino=32084 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:40:39.784   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +543ms
,11-08 17:40:39.786   939   939 W Binder_2: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32083]" dev="sockfs" ino=32083 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:40:39.786   939   939 W Binder_2: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32083]" dev="sockfs" ino=32083 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:40:39.788  3559  3559 I Keyboard.Facilitator: onFinishInput()
,11-08 17:40:39.815  5499  5499 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5499
,11-08 17:40:39.904  5499  5499 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-08 17:40:40.044  5499  5539 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -587986640
,11-08 17:40:40.047  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-08 17:40:40.047  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-08 17:40:40.047  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-08 17:40:40.047  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-08 17:40:40.047  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-08 17:40:40.047  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6bafd9 added. We now have 1 listener(s)
,11-08 17:40:40.049  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-08 17:40:40.050  5499  5539 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 17:40:40.050  5499  5539 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-08 17:40:40.050  5499  5539 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-08 17:40:40.052  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63fd84c added. We now have 1 listener(s)
11-08 17:40:40.053  5499  5539 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 17:40:40.056   928  2886 D WifiService: New client listening to asynchronous messages
11-08 17:40:40.057  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-08 17:40:40.057  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-08 17:40:40.057  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-08 17:40:40.057  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-08 17:40:40.057  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-08 17:40:40.063  5499  5539 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:40:40.063  5499  5539 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-08 17:40:40.067  5499  5539 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-08 17:40:40.068  5499  5539 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:40:40.068  5499  5539 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:40:40.068  5499  5539 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:40:40.068  5499  5539 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:40:40.068  5499  5539 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:40:40.068  5499  5539 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:40:40.068  5499  5539 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:40:40.068  5499  5539 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:40:40.068  5499  5539 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-08 17:40:40.068  5499  5539 D io.jxcore.node.ConnectivityMonitor: start: OK
11-08 17:40:40.068  5499  5539 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-08 17:40:40.152  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:40:40.156  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:40:40.158  5499  5499 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-08 17:40:40.564  5499  5545 W jxcore-log: Initializing JXcore engine
11-08 17:40:40.564  5499  5545 W jxcore-log: JXcore engine is ready
,11-08 17:40:40.589  5545  5545 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12698 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-08 17:40:40.589  5545  5545 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15494]" dev="sockfs" ino=15494 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-08 17:40:40.589  5545  5545 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-08 17:40:40.589  5545  5545 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32052]" dev="sockfs" ino=32052 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-08 17:40:40.599  5499  5545 W jxcore-log: Starting JXcore engine
,11-08 17:40:40.649  5499  5545 W jxcore-log: Platform android
11-08 17:40:40.649  5499  5545 W jxcore-log: 
,11-08 17:40:40.649  5499  5545 W jxcore-log: Process ARCH arm
11-08 17:40:40.649  5499  5545 W jxcore-log: 
,11-08 17:40:40.792  5499  5545 I jxcore-log: JXcore Cordova bridge is ready!
11-08 17:40:40.792  5499  5545 I jxcore-log: 
,11-08 17:40:40.792  5499  5545 W jxcore-log: JXcore engine is started
,11-08 17:40:40.802  5499  5539 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-08 17:40:40.807  5499  5499 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-08 17:40:42.771  3487  3487 I ConfigService: onDestroy
,11-08 17:40:44.259   928  3701 I ActivityManager: Killing 5051:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-08 17:40:44.350   928  2885 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-08 17:40:47.169   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:40:48.170   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:40:49.171   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:40:50.173   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:40:50.495  5499  5545 I jxcore-log: 2016-11-08 16:40:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-08 17:40:50.495  5499  5545 I jxcore-log: 
,11-08 17:40:50.497  5499  5545 I jxcore-log: 2016-11-08 16:40:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-08 17:40:50.497  5499  5545 I jxcore-log: 
,11-08 17:40:50.501  5499  5545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:40:50.501  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:40:50.501  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:40:50.501  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:40:50.501  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:40:50.501  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:40:50.501  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:40:50.501  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:40:50.503  5499  5545 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:40:50.504  5499  5545 I jxcore-log: 2016-11-08 16:40:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-08 17:40:50.504  5499  5545 I jxcore-log: 
,11-08 17:40:50.506  5499  5545 I jxcore-log: 2016-11-08 16:40:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-08 17:40:50.506  5499  5545 I jxcore-log: 
,11-08 17:40:50.759  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 17:40:50.761  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@653f955 added. We now have 2 listener(s)
,11-08 17:40:50.761  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 17:40:50.762  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-08 17:40:50.762  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 17:40:50.762  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 17:40:50.762  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4773f6a added. We now have 2 listener(s)
,11-08 17:40:50.762  5499  5545 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 17:40:50.762  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-08 17:40:50.765  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:40:50.767  5499  5545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:40:50.767  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:40:50.767  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:40:50.767  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:40:50.767  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:40:50.767  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:40:50.767  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:40:50.767  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:40:50.768  5499  5545 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:40:50.768  5499  5545 D io.jxcore.node.ConnectivityMonitor: start: OK
11-08 17:40:50.769  5499  5545 D ExecuteNativeTests: Running unit tests
11-08 17:40:50.770  5499  5545 D BluetoothAdapter: enable(): BT is already enabled..!
,11-08 17:40:50.770   928  3703 D WifiService: setWifiEnabled: true pid=5499, uid=10077
11-08 17:40:50.770   928  3703 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:40:50.775  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:40:50.783  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:40:51.174   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:40:52.175   554   554 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-08 17:40:52.452   928  2886 D WifiService: New client listening to asynchronous messages
,11-08 17:40:52.456  3870  5548 W CronetSyncConnectionRcs: Upload content type not set.
,11-08 17:40:52.533  4790  4832 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-08 17:40:52.534  4790  4790 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-08 17:40:52.537   928  3703 I ActivityManager: Killing 5140:org.codeaurora.ims/1001 (adj 15): empty #17
,11-08 17:41:00.179   928   928 I ActivityManager: Killing 5156:com.android.settings/1000 (adj 15): empty #17
,11-08 17:41:00.776  5499  5545 I com.test.thalitest.ThaliTestRunner: Running UT
,11-08 17:41:00.839  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 17:41:00.839  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b1806c added. We now have 3 listener(s)
,11-08 17:41:00.840  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 17:41:00.840  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-08 17:41:00.840  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 17:41:00.840  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 17:41:00.840  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83cc635 added. We now have 3 listener(s)
,11-08 17:41:00.840  5499  5545 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 17:41:00.841  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-08 17:41:00.843  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:41:00.846  5499  5545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:41:00.846  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:00.846  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:00.846  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:00.846  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:00.846  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:00.846  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:00.846  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:41:00.847  5499  5545 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:00.847  5499  5545 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 17:41:00.850  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:00.852  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:00.852  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-08 17:41:00.852  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-08 17:41:00.853  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:41:00.853  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:41:00.853  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:41:00.854  5499  5545 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-08 17:41:00.854  5499  5545 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-08 17:41:00.854  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 17:41:00.854  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-08 17:41:00.854  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:41:00.854  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:41:00.855  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-08 17:41:00.855  5499  5545 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-08 17:41:00.856  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-08 17:41:00.858  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-08 17:41:00.858  5499  5545 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 17:41:00.858  5499  5545 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-08 17:41:00.858  5499  5545 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-08 17:41:00.858  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-08 17:41:00.858  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-08 17:41:00.858  5499  5545 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 17:41:00.858  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:41:00.859  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:41:00.859  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 17:41:00.860  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 17:41:00.860  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 17:41:00.860  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-08 17:41:00.860  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:41:00.860  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 17:41:00.860  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:41:00.860  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 17:41:00.860  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 17:41:00.861  5499  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-08 17:41:00.862  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:41:00.862  5499  5545 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:41:00.863  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 17:41:00.865  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 17:41:00.865  5499  5560 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:41:00.866  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-08 17:41:00.866  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:41:00.872  5499  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 17:41:00.872  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:00.874  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:41:00.874  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:41:00.874  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
,11-08 17:41:00.874  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:41:00.874  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:00.874  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:00.874  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:00.875  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:00.875  5499  5545 D BluetoothAdapter: STATE_ON
,11-08 17:41:00.869  4810  4810 W Binder_5: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32779]" dev="sockfs" ino=32779 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:41:00.869  4810  4810 W Binder_5: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32779]" dev="sockfs" ino=32779 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:41:00.878  4578  4808 D BtGatt.GattService: registerClient() - UUID=42668912-98cf-4bd8-b9e8-715b33c1347f
11-08 17:41:00.879  4578  4650 D BtGatt.GattService: onClientRegistered() - UUID=42668912-98cf-4bd8-b9e8-715b33c1347f, clientIf=5
,11-08 17:41:00.881  5499  5510 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 17:41:00.883  4578  4652 D BtGatt.AdvertiseManager: message : 0
,11-08 17:41:00.888  4578  4652 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:41:00.908  4578  4650 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:41:00.917  4578  4650 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:41:00.918  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:00.919  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:00.919  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 17:41:00.919  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:00.919  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:00.919  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:00.919  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:00.919  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:00.919  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 17:41:00.920  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:41:00.920  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:00.921  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:00.921  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:00.921  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:00.922  5499  5545 I io.jxcore.node.ConnectionHelper: start: OK
11-08 17:41:00.922  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-08 17:41:00.922  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:41:00.922  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-08 17:41:00.923  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:41:00.923  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:41:00.923  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:00.923  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:41:00.923  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:41:00.924  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 17:41:00.924  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-08 17:41:00.924  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 17:41:00.924  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 17:41:00.924  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:41:00.927  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:41:00.928  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 17:41:00.928  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:41:00.928  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:41:00.928  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:41:00.929  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:00.929  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 17:41:01.425  5499  5545 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-08 17:41:01.425  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-08 17:41:01.425  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-08 17:41:01.425  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-08 17:41:01.425  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-08 17:41:01.425  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-08 17:41:01.426  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-08 17:41:01.426  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-08 17:41:01.426  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-08 17:41:01.426  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-08 17:41:01.426  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-08 17:41:01.426  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-08 17:41:01.426  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-08 17:41:01.426  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-08 17:41:01.426  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-08 17:41:01.427  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-08 17:41:01.427  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-08 17:41:01.427  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-08 17:41:01.427  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-08 17:41:01.427  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-08 17:41:01.427  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-08 17:41:01.427  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-08 17:41:01.427  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-08 17:41:01.427  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-08 17:41:01.427  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-08 17:41:01.428  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-08 17:41:01.428  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-08 17:41:01.428  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-08 17:41:01.428  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-08 17:41:01.428  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-08 17:41:01.428  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-08 17:41:01.428  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-08 17:41:01.429  5499  5545 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-08 17:41:01.429  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-08 17:41:01.429  5499  5545 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 17:41:01.429  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 17:41:01.429  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 17:41:01.429  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 17:41:01.430  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 17:41:01.430  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 17:41:01.430  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 17:41:01.430  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 17:41:01.430  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 17:41:01.431  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 17:41:01.431  5499  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 17:41:01.431  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 17:41:01.431  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 17:41:01.431  5499  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 17:41:01.431  5499  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 17:41:01.432  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.432  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.433  5499  5545 D BluetoothAdapter: STATE_ON
11-08 17:41:01.433  5499  5545 D BluetoothLeScanner: could not find callback wrapper
11-08 17:41:01.433  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-08 17:41:01.434  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.434  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.434  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 17:41:01.434  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.435  4578  4652 D BtGatt.AdvertiseManager: message : 1
11-08 17:41:01.436  4578  4652 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 17:41:01.448  4578  4650 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 17:41:01.448  4578  4650 D BtGatt.GattService: Client app is not null!
11-08 17:41:01.449  4578  4591 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:41:01.450  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 17:41:01.453  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.453  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:41:01.453  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.454  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.454  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.454  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 17:41:01.454  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:41:01.454  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.454  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.454  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-08 17:41:01.454  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.455  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.455  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:41:01.456  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.456  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.456  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.456  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:01.456  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.456  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 17:41:01.456  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 17:41:01.457  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 17:41:01.457  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:01.458  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.459  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.459  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.459  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-08 17:41:01.459  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 17:41:01.460  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-08 17:41:01.460  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:01.460  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:01.460  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-08 17:41:01.460  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 17:41:01.460  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 17:41:01.463  5499  5545 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 17:41:01.463  5499  5545 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 17:41:01.463  5499  5545 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-08 17:41:01.464  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,11-08 17:41:01.464  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 17:41:01.464  5499  5545 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 17:41:01.464  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:41:01.464  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:41:01.465  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 17:41:01.469  4590  4590 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31239]" dev="sockfs" ino=31239 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 17:41:01.469  4590  4590 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31239]" dev="sockfs" ino=31239 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 17:41:01.468  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-08 17:41:01.468  5499  5563 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 17:41:01.468  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 17:41:01.468  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 17:41:01.468  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:41:01.468  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 17:41:01.468  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 17:41:01.469  5499  5563 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:41:01.469  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:41:01.469  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 17:41:01.471  5499  5563 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 17:41:01.475  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:41:01.475  5499  5545 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:41:01.475  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-08 17:41:01.480  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 17:41:01.481  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:41:01.481  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:41:01.483  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.483  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:41:01.484  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:41:01.484  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-08 17:41:01.484  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:41:01.484  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.484  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.484  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.484  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.485  5499  5545 D BluetoothAdapter: STATE_ON
11-08 17:41:01.487  4578  4809 D BtGatt.GattService: registerClient() - UUID=fdc5057a-8850-4829-8c2d-063b6b626085
11-08 17:41:01.487  4578  4650 D BtGatt.GattService: onClientRegistered() - UUID=fdc5057a-8850-4829-8c2d-063b6b626085, clientIf=5
11-08 17:41:01.488  5499  5509 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 17:41:01.489  4578  4652 D BtGatt.AdvertiseManager: message : 0
11-08 17:41:01.491  4578  4652 D BtGatt.AdvertiseManager: starting multi advertising
11-08 17:41:01.501  4578  4650 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-08 17:41:01.508  4578  4650 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-08 17:41:01.508  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.508  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.508  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 17:41:01.509  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.509  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.509  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.509  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.509  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.509  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 17:41:01.510  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-08 17:41:01.510  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.512  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.512  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.512  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:01.512  5499  5545 I io.jxcore.node.ConnectionHelper: start: OK
11-08 17:41:01.512  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 17:41:01.512  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:41:01.512  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:01.513  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:41:01.513  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:41:01.513  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:01.513  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:41:01.513  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:41:01.513  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 17:41:01.513  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:41:01.513  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 17:41:01.513  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 17:41:01.513  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:41:01.516  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:41:01.516  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:41:01.516  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:41:01.516  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:41:01.516  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:41:01.516  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:01.516  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 17:41:02.016  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 17:41:02.017  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 17:41:02.017  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-08 17:41:02.017  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 17:41:02.017  5499  5545 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 17:41:02.017  5499  5545 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 17:41:02.017  5499  5545 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-08 17:41:02.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,11-08 17:41:02.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 17:41:02.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 17:41:02.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 17:41:02.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-08 17:41:02.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 17:41:02.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 17:41:02.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 17:41:02.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 17:41:02.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-08 17:41:02.018  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.020  4578  4652 D BtGatt.AdvertiseManager: message : 1
,11-08 17:41:02.022  4578  4652 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 17:41:02.037  4578  4650 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 17:41:02.037  4578  4650 D BtGatt.GattService: Client app is not null!
11-08 17:41:02.038  4578  4809 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:41:02.039  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 17:41:02.039  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.039  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:41:02.039  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.039  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:02.039  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 17:41:02.039  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.039  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:41:02.039  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:41:02.039  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-08 17:41:02.040  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:41:02.040  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.040  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.040  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.040  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.041  5499  5545 D BluetoothAdapter: STATE_ON
,11-08 17:41:02.044  4578  4808 D BtGatt.GattService: registerClient() - UUID=6c7d4a32-6e80-48c1-9f16-022a67699dd0
11-08 17:41:02.044  4578  4650 D BtGatt.GattService: onClientRegistered() - UUID=6c7d4a32-6e80-48c1-9f16-022a67699dd0, clientIf=5
11-08 17:41:02.045  5499  5510 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 17:41:02.046  4578  4652 D BtGatt.AdvertiseManager: message : 0
,11-08 17:41:02.049  4578  4652 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:41:02.061  4578  4650 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:41:02.068  4578  4650 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:41:02.069  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:02.069  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.069  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.069  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 17:41:02.069  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.069  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.069  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.069  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:02.069  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.069  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:41:02.069  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:02.069  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:41:02.069  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:41:02.069  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.069  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 17:41:02.069  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-08 17:41:02.069  5499  5545 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-08 17:41:02.070  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.070  5499  5545 I io.jxcore.node.ConnectionHelper: start: OK
11-08 17:41:02.070  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:41:02.070  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:41:02.070  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.070  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.070  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-08 17:41:02.071  5499  5545 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-08 17:41:02.071  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-08 17:41:02.071  5499  5545 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 17:41:02.071  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 17:41:02.072  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-08 17:41:02.072  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 17:41:02.072  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 17:41:02.072  5499  5563 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 17:41:02.072  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 17:41:02.072  5499  5563 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 17:41:02.072  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 17:41:02.072  5499  5563 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 17:41:02.072  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 17:41:02.072  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 17:41:02.072  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 17:41:02.072  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 17:41:02.072  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 17:41:02.072  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.072  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:02.073  5499  5545 D BluetoothAdapter: STATE_ON
11-08 17:41:02.073  5499  5545 D BluetoothLeScanner: could not find callback wrapper
11-08 17:41:02.073  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 17:41:02.073  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.073  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.073  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 17:41:02.073  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.074  4578  4652 D BtGatt.AdvertiseManager: message : 1
11-08 17:41:02.075  4578  4652 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 17:41:02.081  4578  4650 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 17:41:02.081  4578  4650 D BtGatt.GattService: Client app is not null!
11-08 17:41:02.082  4578  4591 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:41:02.082  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 17:41:02.082  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.082  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:41:02.082  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.083  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.083  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:02.083  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 17:41:02.083  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:41:02.083  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.083  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.086  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 17:41:02.086  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.087  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.087  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:41:02.087  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.088  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.088  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.088  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.088  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.088  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 17:41:02.088  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 17:41:02.088  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 17:41:02.088  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.090  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.090  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:02.090  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.090  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 17:41:02.090  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 17:41:02.091  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 17:41:02.091  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 17:41:02.091  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:02.091  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:02.091  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 17:41:02.093  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-08 17:41:02.093  5499  5545 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-08 17:41:02.094  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-08 17:41:02.094  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-08 17:41:02.095  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-08 17:41:02.095  5499  5545 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-08 17:41:02.095  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-08 17:41:02.096  5499  5545 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-08 17:41:02.096  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-08 17:41:02.096  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 17:41:02.096  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:41:02.096  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:41:02.096  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:41:02.096  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-08 17:41:02.097  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:41:02.097  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:41:02.097  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:41:02.097  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 17:41:02.097  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:41:02.097  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:41:02.097  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:41:02.098  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-08 17:41:02.098  5499  5545 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-08 17:41:02.098  5499  5545 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-08 17:41:02.101  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,11-08 17:41:02.101  5499  5545 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-08 17:41:02.102  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-08 17:41:02.102  5499  5545 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-08 17:41:02.103  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-08 17:41:02.103  5499  5545 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-08 17:41:02.103  5499  5545 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-08 17:41:02.103  5499  5545 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-08 17:41:02.104  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 17:41:02.104  5499  5545 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-08 17:41:02.104  5499  5545 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-08 17:41:02.104  5499  5545 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-08 17:41:02.104  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-08 17:41:02.104  5499  5545 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-08 17:41:02.104  5499  5545 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-08 17:41:02.104  5499  5545 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-08 17:41:02.104  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 17:41:02.104  5499  5545 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-08 17:41:02.105  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,11-08 17:41:02.105  5499  5545 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-08 17:41:02.105  5499  5545 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 17:41:02.105  5499  5545 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-08 17:41:02.105  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-08 17:41:02.105  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-08 17:41:02.105  5499  5545 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 17:41:02.105  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:41:02.105  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:41:02.107  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 17:41:02.108  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-08 17:41:02.108  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-08 17:41:02.108  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-08 17:41:02.108  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:41:02.108  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 17:41:02.108  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:41:02.108  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 17:41:02.108  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 17:41:02.108  5499  5567 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 17:41:02.109  5499  5567 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:41:02.109  4590  4590 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31248]" dev="sockfs" ino=31248 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:41:02.109  4590  4590 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31248]" dev="sockfs" ino=31248 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 17:41:02.111  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:41:02.111  5499  5545 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-08 17:41:02.111  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 17:41:02.112  5499  5567 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 17:41:02.115  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 17:41:02.115  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:41:02.115  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:41:02.118  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:41:02.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:41:02.118  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-08 17:41:02.118  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:41:02.118  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.118  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.118  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.119  5499  5545 D BluetoothAdapter: STATE_ON
11-08 17:41:02.122  4578  4808 D BtGatt.GattService: registerClient() - UUID=6e21d603-06dd-4b20-adc4-a05b2fd62d25
11-08 17:41:02.122  4578  4650 D BtGatt.GattService: onClientRegistered() - UUID=6e21d603-06dd-4b20-adc4-a05b2fd62d25, clientIf=5
11-08 17:41:02.122  5499  5510 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 17:41:02.123  4578  4652 D BtGatt.AdvertiseManager: message : 0
11-08 17:41:02.125  4578  4652 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:41:02.134  4578  4650 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:41:02.139  4578  4650 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:41:02.140  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.140  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.140  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-08 17:41:02.140  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.140  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.140  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.140  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.140  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.140  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-08 17:41:02.142  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:41:02.142  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.143  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.143  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:02.143  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.143  5499  5545 I io.jxcore.node.ConnectionHelper: start: OK
11-08 17:41:02.143  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 17:41:02.143  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.144  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:02.144  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:41:02.144  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
,11-08 17:41:02.144  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:02.144  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.144  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:41:02.144  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 17:41:02.144  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.144  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.144  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 17:41:02.144  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 17:41:02.146  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-08 17:41:02.147  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:41:02.147  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.147  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.147  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:41:02.147  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:02.147  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 17:41:02.645  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-08 17:41:02.645  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-08 17:41:02.645  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 17:41:02.645  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-08 17:41:02.646  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 17:41:02.646  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-08 17:41:02.646  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 17:41:02.646  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-08 17:41:02.646  5499  5567 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 17:41:02.647  5499  5567 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 17:41:02.647  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 17:41:02.647  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b1806c removed from the list
11-08 17:41:02.647  5499  5567 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 17:41:02.647  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 17:41:02.647  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 17:41:02.647  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 17:41:02.647  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 17:41:02.647  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-08 17:41:02.648  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 17:41:02.647  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-08 17:41:02.649  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.649  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.652  5499  5545 D BluetoothAdapter: STATE_ON
11-08 17:41:02.652  5499  5545 D BluetoothLeScanner: could not find callback wrapper
11-08 17:41:02.652  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 17:41:02.653  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.653  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:02.653  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-08 17:41:02.653  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.655  4578  4652 D BtGatt.AdvertiseManager: message : 1
,11-08 17:41:02.656  4578  4652 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 17:41:02.668  4578  4650 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 17:41:02.668  4578  4650 D BtGatt.GattService: Client app is not null!
11-08 17:41:02.669  4578  4809 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:41:02.670  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 17:41:02.670  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:02.670  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:41:02.670  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.670  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.670  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:02.670  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 17:41:02.670  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:41:02.670  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.670  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.671  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 17:41:02.671  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.672  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.672  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 17:41:02.672  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.672  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.672  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.672  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.672  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.672  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 17:41:02.673  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 17:41:02.673  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-08 17:41:02.673  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.674  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.675  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.675  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:02.675  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83cc635 removed from the list
11-08 17:41:02.675  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:02.675  5499  5545 D io.jxcore.node.ConnectivityMonitor: stop
11-08 17:41:02.675  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 17:41:02.675  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:02.675  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 17:41:03.177  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 17:41:07.679  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-08 17:41:07.681  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-08 17:41:07.681  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:41:07.683  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 17:41:07.684  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-08 17:41:07.685  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 17:41:07.685  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 17:41:07.685  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:41:07.685  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-08 17:41:07.685  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 17:41:07.685  5499  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-08 17:41:07.688  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-08 17:41:07.688  5499  5568 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:41:07.689  5499  5545 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-08 17:41:07.690  5499  5545 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-08 17:41:07.690  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-08 17:41:07.690  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:41:07.691  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:41:07.692  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-08 17:41:07.692  4809  4809 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[29592]" dev="sockfs" ino=29592 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:41:07.695  5499  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 17:41:07.692  4809  4809 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[29592]" dev="sockfs" ino=29592 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:41:07.700  5499  5545 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-08 17:41:07.700  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-08 17:41:07.701  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 17:41:07.701  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-08 17:41:07.701  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 17:41:07.701  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 17:41:07.701  5499  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 17:41:07.701  5499  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 17:41:07.701  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 17:41:07.701  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 17:41:07.701  5499  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 17:41:07.702  5499  5545 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b1806c not in the list
11-08 17:41:07.702  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-08 17:41:07.702  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 17:41:07.702  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 17:41:07.702  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 17:41:07.702  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-08 17:41:07.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 17:41:07.702  5499  5545 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 17:41:07.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-08 17:41:07.702  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 17:41:07.702  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:07.704  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:07.705  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 17:41:07.705  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:07.705  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:07.705  5499  5545 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83cc635 not in the list
11-08 17:41:07.705  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-08 17:41:07.705  5499  5545 D io.jxcore.node.ConnectivityMonitor: stop
11-08 17:41:07.705  5499  5545 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 17:41:07.705  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:07.705  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 17:41:07.705  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:41:07.706  5499  5545 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-08 17:41:07.707  5499  5545 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-08 17:41:07.707  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-08 17:41:07.707  5499  5545 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-08 17:41:07.707  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 17:41:07.707  5499  5545 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-08 17:41:07.707  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 17:41:07.708  5499  5545 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-08 17:41:07.709  5499  5545 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-08 17:41:07.711  5499  5545 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-08 17:41:07.711  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-08 17:41:07.711  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-08 17:41:07.712  5499  5545 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-08 17:41:07.712  5499  5545 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-08 17:41:07.712  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-08 17:41:07.713  5499  5545 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-08 17:41:07.714  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-08 17:41:07.714  5499  5545 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-08 17:41:07.714  5499  5545 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-08 17:41:07.715  5499  5545 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-08 17:41:07.715  5499  5545 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-08 17:41:07.715  5499  5545 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-08 17:41:07.715  5499  5545 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-08 17:41:07.716  5499  5545 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-08 17:41:07.716  5499  5545 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-08 17:41:07.716  5499  5545 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-08 17:41:07.716  5499  5545 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-08 17:41:07.716  5499  5545 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-08 17:41:07.717  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-08 17:41:07.717  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42ca6a5 added. We now have 3 listener(s)
,11-08 17:41:07.719  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:41:07.719  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 17:41:07.719  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 17:41:07.719  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 17:41:07.719  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a676a7a added. We now have 3 listener(s)
11-08 17:41:07.719  5499  5545 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 17:41:07.720  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 17:41:07.723  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:41:07.727  5499  5545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:41:07.727  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:07.727  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:07.727  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:07.727  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:07.727  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:07.727  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:07.727  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:41:07.728  5499  5545 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:07.728  5499  5545 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 17:41:07.731  5499  5545 D BluetoothAdapter: enable(): BT is already enabled..!
,11-08 17:41:07.731   928  3329 D WifiService: setWifiEnabled: true pid=5499, uid=10077
11-08 17:41:07.731   928  3329 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 17:41:07.732  5499  5545 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
11-08 17:41:07.733  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:07.735  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:07.738  5499  5545 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-08 17:41:07.738  5499  5545 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-08 17:41:07.741   928  3701 D WifiService: setWifiEnabled: false pid=5499, uid=10077
11-08 17:41:07.741   928  3701 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:41:07.743   928  2885 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-08 17:41:07.743   928  2885 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-08 17:41:07.743   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 17:41:07.744   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:41:07.751   928  5265 D DhcpClient: Clearing IP address
,11-08 17:41:07.751   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-08 17:41:07.754   508   922 D CommandListener: Setting iface cfg
,11-08 17:41:07.755   928  5266 D DhcpClient: Receive thread stopped
,11-08 17:41:07.758  3487  5322 V NativeCrypto: Read error: ssl=0x7f7d2c9380: I/O error during system call, Connection timed out
11-08 17:41:07.760  3487  5322 V NativeCrypto: SSL shutdown failed: ssl=0x7f7d2c9380: I/O error during system call, Broken pipe
,11-08 17:41:07.762   928  3703 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-08 17:41:07.762   928  5263 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-08 17:41:07.765   928  5263 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-08 17:41:07.765   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-08 17:41:07.766   928  2887 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-08 17:41:07.767   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-08 17:41:07.770   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-08 17:41:07.771   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-08 17:41:07.775   928   928 D RttService: SCAN_AVAILABLE : 1
11-08 17:41:07.776   928  2994 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 17:41:07.777   550   550 E Parcel  : Reading a NULL string not supported here.
,11-08 17:41:07.779   928  2887 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-08 17:41:07.782  3628  3765 W QCNEJ   : |CORE| network lost: 100
11-08 17:41:07.783  3628  3765 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-08 17:41:07.794   928  2885 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-08 17:41:07.808   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 17:41:07.811   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 17:41:07.830   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 17:41:07.830   508   922 D CommandListener: Clearing all IP addresses on wlan0
11-08 17:41:07.830   508   922 D TetherController: Setting IP forward enable = 0
11-08 17:41:07.831   928  2887 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-08 17:41:07.831   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-08 17:41:07.832   928   945 D Tethering: MasterInitialState.processMessage what=3
11-08 17:41:07.834   928  2885 D DhcpClient: doQuit
11-08 17:41:07.834   928  2885 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-08 17:41:07.835   928  5265 D DhcpClient: onQuitting
11-08 17:41:07.835  3363  3363 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-08 17:41:07.839  3870  3870 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-08 17:41:07.842  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:07.842  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:07.842  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:07.842  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:07.842  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:07.842  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:07.842  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:07.842  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:07.844  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:07.847  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:07.847  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:07.847  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:07.847  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:41:07.847  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:07.847  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:07.847  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:07.847  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:07.835  5171  5171 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6d3eda1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-08 17:41:07.849  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:41:07.852  3964  3964 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-08 17:41:07.853  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:07.853  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:07.853  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:07.853  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:41:07.853  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:07.853  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:07.853  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:07.853  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:41:07.855  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:41:07.860  3363  3363 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-08 17:41:07.861  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:07.861  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:07.861  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:07.861  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:41:07.861  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:07.861  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:07.861  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:07.861  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:07.863  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:07.863  3363  3363 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-08 17:41:07.864   508   915 W SocketClient: write error (Broken pipe)
11-08 17:41:07.864   508   915 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-08 17:41:07.865   508   915 W SocketListener: Error sending broadcast (Broken pipe)
11-08 17:41:07.865  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:07.867  3964  3964 D SystemUpdateService: onCreate
,11-08 17:41:07.869  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:07.872  3964  3964 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-08 17:41:07.875  3964  5590 I SystemUpdateService: active receiver: enabled
,11-08 17:41:07.885  3964  3964 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-08 17:41:07.890   508   922 E Netd    : netlink response contains error (No such file or directory)
11-08 17:41:07.891   508   922 D TetherController: Setting IP forward enable = 0
11-08 17:41:07.891  3964  4196 I iu.UploadsManager: num queued entries: 0
11-08 17:41:07.891  3964  4196 I iu.UploadsManager: num updated entries: 0
11-08 17:41:07.892   928  2887 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-08 17:41:07.892   928  2887 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-08 17:41:07.892  3964  4196 I iu.SyncManager: NEXT; no task
11-08 17:41:07.893  3964  5590 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 17:41:07.894  3964  3964 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 17:41:07.896  3964  3964 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 17:41:07.898  5294  5294 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 17:41:07.900  3363  3363 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-08 17:41:07.902  5294  5294 D SprintDMHelper: simOperator: 
11-08 17:41:07.902  5294  5294 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 17:41:07.912  3964  5590 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-08 17:41:07.913  3964  5590 I SystemUpdateService: now status is 0 (complete)
11-08 17:41:07.913  3964  5590 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-08 17:41:07.915  3363  3363 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-08 17:41:07.917  3964  5590 I SystemUpdateService: file has been verified
11-08 17:41:07.918  3964  5590 I SystemUpdateService: OTA package size = 21989297
,11-08 17:41:07.922  3964  5590 I SystemUpdateService: showing system update notification
,11-08 17:41:07.929   928  3503 I ActivityManager: Start proc 5596:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-08 17:41:07.939   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 17:41:07.940  3964  3964 D SystemUpdateService: onDestroy
,11-08 17:41:07.961  5596  5596 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-08 17:41:07.968   928  3328 I ActivityManager: Killing 4958:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-08 17:41:08.019   928  2885 D wifi    : In wifi stop Hal
,11-08 17:41:08.019   928  2885 D wifi    : halHandle = 0x7f6ab48400, mVM = 0x7f8714d140, mCls = 0x100a02
,11-08 17:41:08.019   928  3362 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-08 17:41:08.020   928  3362 D WifiHAL : Got a signal to exit!!!
11-08 17:41:08.020   928  3362 I WifiHAL : Exit wifi_event_loop
,11-08 17:41:08.021   928  2885 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-08 17:41:08.021   928  2885 E WifiHAL : Event processing terminated
11-08 17:41:08.021   928  2885 D wifi    : In wifi cleaned up handler
,11-08 17:41:08.022   928  2885 I WifiHAL : Internal cleanup completed
11-08 17:41:08.024  4424  4424 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 17:41:08.025  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:08.026  3854  4108 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 17:41:08.029  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:08.030  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:08.049   928  3362 D wifi    : set interface wlan0 flags (DOWN)
11-08 17:41:08.050   928  2885 D WifiNative-HAL: HAL event thread stopped successfully
,11-08 17:41:08.206  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 17:41:08.247  5499  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:08.250   928  3102 D WifiService: setWifiEnabled: true pid=5499, uid=10077
11-08 17:41:08.250   928  3102 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:41:08.256   928   945 D Tethering: InitialState.processMessage what=4
,11-08 17:41:08.261   508   922 D SoftapController: Softap fwReload - Ok
,11-08 17:41:08.263   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-08 17:41:08.266   508   922 D CommandListener: Setting iface cfg
,11-08 17:41:08.267   508   922 D CommandListener: Trying to bring down wlan0
,11-08 17:41:08.268   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-08 17:41:08.272   928  2885 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 17:41:08.760   928  3328 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-08 17:41:08.762   928  3328 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:41:08.879   928  2885 D wifi    : set interface wlan0 flags (UP)
11-08 17:41:08.879   928  2885 I WifiHAL : Initializing wifi
,11-08 17:41:08.880   928  2885 I WifiHAL : Creating socket
,11-08 17:41:08.886   928  2885 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-08 17:41:08.886   928  2885 D wifi    : Did set static halHandle = 0x7f6ab48400
11-08 17:41:08.886   928  2885 D wifi    : halHandle = 0x7f6ab48400, mVM = 0x7f8714d140, mCls = 0x1015e2
,11-08 17:41:08.887   928  2885 D wifi    : array field set
11-08 17:41:08.887   928  2885 I WifiNative-HAL: interface[0] = wlan0
11-08 17:41:08.890   928  5611 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547251061760
11-08 17:41:08.890   928  5611 D wifi    : waitForHalEvents called, vm = 0x7f8714d140, obj = 0x1015e2, env = 0x7f6b3bcf40
,11-08 17:41:08.898   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-08 17:41:08.952  5612  5612 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-08 17:41:08.991   928  2885 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-08 17:41:09.000  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:09.004  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:09.005  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:09.020  5612  5612 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 17:41:09.065  5612  5612 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 17:41:09.066  5612  5612 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-08 17:41:09.087   928  2885 D WifiConfigStore: Loading config and enabling all networks 
,11-08 17:41:09.094  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:09.094  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:09.094  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:09.094  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:09.094  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:09.094  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:09.094  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:09.094  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:09.098  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:09.102  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:09.102  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:09.102  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:09.102  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:09.102  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:09.102  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:09.102  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:09.102  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:09.105  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:09.108  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:09.108  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:09.108  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:09.108  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:09.108  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:09.108  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:09.108  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:09.108  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:09.110   928  2885 D WifiConfigStore: loaded 0 passpoint configs
,11-08 17:41:09.111   928  2885 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-08 17:41:09.112   928  2885 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-08 17:41:09.112  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:09.112   928  2885 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-08 17:41:09.112   928  2885 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-08 17:41:09.113   928  2885 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-08 17:41:09.116   928  2885 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-08 17:41:09.117   928  2885 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-08 17:41:09.117   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-08 17:41:09.117   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-08 17:41:09.117   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-08 17:41:09.117   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-08 17:41:09.117   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-08 17:41:09.119   928  2885 D WifiNative-HAL: Setting external_sim to 1
,11-08 17:41:09.119   928  2885 D wifi    : setting dfs flag to true, 0x7f6b9f9be0
11-08 17:41:09.119  4424  4424 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 17:41:09.119   928  2885 D WifiStateMachine: Setting OUI to DA-A1-19
11-08 17:41:09.120   928  2885 D wifi    : setting scan oui 0x7f6b9f9be0
11-08 17:41:09.120   928  2885 D WifiHAL : Sending mac address OUI
,11-08 17:41:09.123   928  2885 E native  : do suspend false
,11-08 17:41:09.129   928  2885 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-08 17:41:09.129   928   928 D RttService: SCAN_AVAILABLE : 3
11-08 17:41:09.129   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-08 17:41:09.129   928  2994 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 17:41:09.130   508   922 D CommandListener: Setting iface cfg
,11-08 17:41:09.134   928  2883 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,11-08 17:41:09.134   928  2883 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-08 17:41:09.142   928  2883 D WifiNative-HAL: p2pGetDeviceAddress
,11-08 17:41:09.143   928  2883 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-08 17:41:09.148   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=105801 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-08 17:41:09.268  5499  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:09.284  4578  4646 D BluetoothAdapterState: Current state: ON, message: 23
,11-08 17:41:09.284  4578  4646 D BluetoothAdapterProperties: Setting state to 13
,11-08 17:41:09.284  4578  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-08 17:41:09.286  4578  4646 D BluetoothAdapterProperties: onBluetoothDisable()
,11-08 17:41:09.289  4578  4578 D BluetoothMapService: onReceive
,11-08 17:41:09.289  4578  4578 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-08 17:41:09.289  4578  4578 D BluetoothMapService: STATE_TURNING_OFF
11-08 17:41:09.289  4578  4578 D BluetoothMapService: MAP Service closeService in
11-08 17:41:09.289  4578  4578 D BluetoothMapMasInstance0: MAP Service shutdown
11-08 17:41:09.290  4578  4578 D ObexServerSockets0: shutdown(block = true)
11-08 17:41:09.290  4578  4578 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 17:41:09.291  4578  4578 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 17:41:09.291  4578  4812 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-08 17:41:09.293  4578  4787 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-08 17:41:09.293  4578  4646 I BluetoothAdapterState: Entering PendingCommandState
,11-08 17:41:09.294  4578  4813 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-08 17:41:09.299  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 17:41:09.299  4578  4578 I BtOppRfcommListener: stopping Accept Thread
11-08 17:41:09.300  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:09.300  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:09.300  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:09.300  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:09.300  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:41:09.300  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:09.300  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:09.300  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:41:09.300  4578  5199 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-08 17:41:09.301  4578  5199 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-08 17:41:09.302  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:09.302  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:41:09.308  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 17:41:09.308  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:09.308  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:09.308  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:09.308  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:09.308  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:41:09.308  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:09.308  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:09.308  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:41:09.309  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:09.309  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:41:09.316  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:09.316  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:09.316  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:09.316  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:09.316  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:09.316  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:41:09.316  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:09.316  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:09.316  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:41:09.317  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:09.317  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:09.327   928   941 I ActivityManager: Start proc 5616:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-08 17:41:09.327  4578  4650 D BluetoothAdapterProperties: Scan Mode:20
11-08 17:41:09.328  4578  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-08 17:41:09.329  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:09.331  4578  4578 D HeadsetService: Received stop request...Stopping profile...
11-08 17:41:09.331  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:09.333  3041  3053 D BluetoothHeadset: Proxy object disconnected
11-08 17:41:09.333  3041  3041 D HeadsetProfile: Bluetooth service disconnected
11-08 17:41:09.333  3668  3890 D BluetoothHeadset: Proxy object disconnected
11-08 17:41:09.333  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:09.334   928   928 D BluetoothHeadset: Proxy object disconnected
11-08 17:41:09.334   928   928 D BluetoothHeadset: Proxy object disconnected
11-08 17:41:09.334   928   928 D BluetoothHeadset: Proxy object disconnected
,11-08 17:41:09.334  4578  4578 D A2dpService: Received stop request...Stopping profile...
11-08 17:41:09.335  4578  4803 D A2dpStateMachine: Exit Disconnected: -1
11-08 17:41:09.338   928   928 D BluetoothA2dp: Proxy object disconnected
11-08 17:41:09.339  3041  3041 D BluetoothA2dp: Proxy object disconnected
,11-08 17:41:09.339  4578  4578 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:09.339  4578  4578 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:09.339  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:09.339  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:09.341  4578  4578 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-08 17:41:09.343  4578  4578 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-08 17:41:09.344  4578  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:09.344  4578  4578 D HidService: Received stop request...Stopping profile...
11-08 17:41:09.344  4578  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:09.344  4578  4578 D HidService: Stopping Bluetooth HidService
11-08 17:41:09.344  4578  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:09.345  3041  3041 D BluetoothInputDevice: Proxy object disconnected
11-08 17:41:09.345  3041  3041 D HidProfile: Bluetooth service disconnected
11-08 17:41:09.345  4578  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-08 17:41:09.345  4578  4650 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-08 17:41:09.347  4578  4578 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:09.347  4578  4578 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:09.347  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:09.347  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:09.347  4578  4578 D HealthService: Received stop request...Stopping profile...
11-08 17:41:09.349  4578  4578 D PanService: Received stop request...Stopping profile...
,11-08 17:41:09.349  3041  3041 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 17:41:09.349  3041  3041 D PanProfile: Bluetooth service disconnected
,11-08 17:41:09.350  4578  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:09.350  4578  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:09.350  4578  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-08 17:41:09.350  4578  4784 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 17:41:09.351  4578  4784 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 17:41:09.351  4578  4784 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 17:41:09.351  4578  4578 D BluetoothMapService: Received stop request...Stopping profile...
11-08 17:41:09.351  4578  4784 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-08 17:41:09.351  4578  4578 D BluetoothMapService: stop()
11-08 17:41:09.351  4578  4578 D BluetoothMapAppObserver: deinitObservers()
,11-08 17:41:09.352  4578  4578 D BluetoothMapAppObserver: removeReceiver()
,11-08 17:41:09.353  3041  3041 D BluetoothMap: Proxy object disconnected
11-08 17:41:09.353  3041  3041 D MapProfile: Bluetooth service disconnected
,11-08 17:41:09.356  4578  4578 D SapService: Received stop request...Stopping profile...
11-08 17:41:09.356  4578  4578 V SapService: stop()
,11-08 17:41:09.360  4578  4578 V BluetoothAdapterState: isTurningOff()=true
,11-08 17:41:09.360  4578  4578 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:09.360  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:09.360  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:09.360  4578  4578 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-08 17:41:09.360  4578  4578 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-08 17:41:09.360  4578  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 17:41:09.360  4578  4578 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:09.360  4578  4578 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:09.360  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:09.360  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:09.361  4578  4578 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-08 17:41:09.361  4578  4650 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-08 17:41:09.361  4578  4578 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-08 17:41:09.361  4578  4578 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:09.361  4578  4578 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:09.361  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:09.361  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:09.362  4578  4578 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-08 17:41:09.362  4578  4578 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-08 17:41:09.365  4578  4578 D BluetoothMapService: MAP Service closeService in
,11-08 17:41:09.366  4578  4578 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:09.366  4578  4578 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:09.366  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:09.366  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:09.366  4578  4578 D BluetoothMapService: cleanup()
11-08 17:41:09.366  4578  4578 D BluetoothMapService: MAP Service closeService in
,11-08 17:41:09.369  4578  4578 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:09.369  4578  4578 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:09.369  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:09.369  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:09.369  4578  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-08 17:41:09.369  4578  4646 D BluetoothAdapterProperties: Setting state to 15
11-08 17:41:09.369  4578  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-08 17:41:09.370  4578  4646 I BluetoothAdapterState: Entering BleOnState
11-08 17:41:09.370   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 17:41:09.370  3041  5498 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 17:41:09.371  3041  3052 D BluetoothPan: onBluetoothStateChange on: false
11-08 17:41:09.372  3668  3695 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:41:09.373  3041  3053 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:41:09.373   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:41:09.373  3041  3885 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 17:41:09.374  3041  5498 D BluetoothMap: onBluetoothStateChange: up=false
11-08 17:41:09.374   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:41:09.374   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:41:09.374  3041  3052 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 17:41:09.375  5616  5616 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-08 17:41:09.375  4578  4646 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-08 17:41:09.375  4578  4646 D BluetoothAdapterProperties: Setting state to 16
11-08 17:41:09.375  4578  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-08 17:41:09.376  4578  4646 D BluetoothAdapterProperties: onBleDisable
11-08 17:41:09.376  4578  4646 I BluetoothAdapterState: Entering PendingCommandState
11-08 17:41:09.376  4578  4647 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-08 17:41:09.378  4578  4650 D BluetoothAdapterProperties: Scan Mode:20
11-08 17:41:09.379  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:09.381  4578  4784 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-08 17:41:09.381  4578  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:09.383  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:09.385  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:09.387  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:09.388  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:09.390  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:09.397  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 17:41:09.402   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@946d6e2:true
11-08 17:41:09.404  3487  3487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 17:41:09.417   928  3102 I ActivityManager: Start proc 5628:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-08 17:41:09.428  5616  5616 D LocalBluetoothProfileManager: Adding local MAP profile
,11-08 17:41:09.432  5616  5616 D BluetoothMap: Create BluetoothMap proxy object
,11-08 17:41:09.446  5616  5616 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-08 17:41:09.453  5628  5628 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-08 17:41:09.464  5616  5616 D DockEventReceiver: finishStartingService: stopping service
,11-08 17:41:09.467   928   939 I ActivityManager: Killing 5171:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-08 17:41:09.590  4578  4650 I bt_hci  : shut_down
,11-08 17:41:09.594  4578  4654 D bt_hwcfg: hw_epilog_process
,11-08 17:41:09.595  4578  4654 I bt_vendor: low_power_mode_cb
,11-08 17:41:09.597  4578  4654 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-08 17:41:09.597  4578  4654 I bt_vendor: epilog_cb
,11-08 17:41:09.597  4578  4654 I bt_hci  : epilog_finished_callback
11-08 17:41:09.599  4578  4650 I bt_hci_h4: hal_close
11-08 17:41:09.600  4578  4650 I bt_userial_vendor: device fd = 54 close
,11-08 17:41:09.682  5628  5628 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:41:09.682  5628  5628 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:41:09.682  5628  5628 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:41:09.682  5628  5628 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.e.b(PG:170)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:41:09.682  5628  5628 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.k.d(PG:583)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.e.b(PG:170)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:41:09.682  5628  5628 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:41:09.682  5628  5628 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:41:09.682  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:41:09.683  5628  5628 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:41:09.683  5628  5628 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:41:09.683  5628  5628 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:41:09.687  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 17:41:09.692  3487  3487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 17:41:09.695  5616  5616 D DockEventReceiver: finishStartingService: stopping service
11-08 17:41:09.696   928  3060 I ActivityManager: Killing 3780:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-08 17:41:09.728  4578  4647 D bt_stack_manager: event_shut_down_stack finished.
11-08 17:41:09.728  4578  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-08 17:41:09.730  4578  4646 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-08 17:41:09.730  4578  4578 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 17:41:09.730  4578  4578 D BtGatt.GattService: Received stop request...Stopping profile...
11-08 17:41:09.730  4578  4578 D BtGatt.GattService: stop()
11-08 17:41:09.731  4578  4578 D BtGatt.AdvertiseManager: advertise clients cleared
11-08 17:41:09.733  4578  4578 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:09.733  4578  4578 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:09.733  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:09.733  4578  4578 V BluetoothAdapterState: isBleTurningOff()=true
11-08 17:41:09.733  4578  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-08 17:41:09.733  4578  4646 D BluetoothAdapterProperties: Setting state to 10
11-08 17:41:09.733  4578  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-08 17:41:09.734   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-08 17:41:09.735  4578  4646 I BluetoothAdapterState: Entering OffState
11-08 17:41:09.740  4578  4578 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-08 17:41:09.740  4578  4578 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-08 17:41:09.740  4578  4578 I BluetoothServiceJni: cleanupNative: return from cleanup
11-08 17:41:09.741  4578  4647 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-08 17:41:09.744  4578  4578 I art     : System.exit called, status: 0
11-08 17:41:09.744  4578  4578 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-08 17:41:09.781  5499  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:09.783   380   380 E lowmemorykiller: Error writing /proc/4578/oom_score_adj; errno=22
,11-08 17:41:09.783   928   945 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
11-08 17:41:09.784   928   945 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1308)
11-08 17:41:09.784   928   945 W ActivityManager: Application dead when creating service ServiceRecord{9fc67d5 u0 com.android.bluetooth/.btservice.AdapterService}
,11-08 17:41:09.790   928   945 I ActivityManager: Process com.android.bluetooth (pid 4578) has died
,11-08 17:41:09.790   928   945 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
11-08 17:41:09.791   928   945 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
11-08 17:41:09.791   928   945 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
11-08 17:41:09.791   928   945 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-08 17:41:09.791   928   945 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
11-08 17:41:09.791   928   945 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
11-08 17:41:09.791   928   945 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
11-08 17:41:09.791   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
11-08 17:41:09.791   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
11-08 17:41:09.791   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
11-08 17:41:09.791   928   945 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
11-08 17:41:09.791   928   945 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
11-08 17:41:09.791   928   945 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
11-08 17:41:09.791   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
11-08 17:41:09.791   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
11-08 17:41:09.791   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
11-08 17:41:09.791   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
11-08 17:41:09.791   928   945 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:41:09.791   928   945 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:09.791   928   945 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 17:41:09.791   928   945 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-08 17:41:09.792   928  3703 W ActivityManager: Spurious death for ProcessRecord{b244480 0:com.android.bluetooth/1002}, curProc for 4578: null
,11-08 17:41:09.901  5628  5650 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-08 17:41:09.912   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a2cedb:true
,11-08 17:41:12.235  5612  5612 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:41:12.241  5612  5612 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:41:12.248  5612  5612 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:41:12.252  5612  5612 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:41:12.302   928  2885 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-08 17:41:12.304   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-08 17:41:12.304   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:41:12.318   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-08 17:41:12.354   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-08 17:41:12.363  5612  5612 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-08 17:41:12.783   928   945 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,11-08 17:41:12.792  5612  5612 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-08 17:41:12.825  5612  5612 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-08 17:41:12.825  5612  5612 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-08 17:41:12.830   928   945 I ActivityManager: Start proc 5664:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-08 17:41:12.840   928  2885 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 17:41:12.842   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-08 17:41:12.842   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-08 17:41:12.854   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:41:12.864   508   922 D CommandListener: Setting iface cfg
,11-08 17:41:12.868   928  2885 D WifiStateMachine: Start Dhcp Watchdog 2
,11-08 17:41:12.879   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-08 17:41:12.879   928  2887 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-08 17:41:12.879   928  2887 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-08 17:41:12.888   928  5679 D DhcpClient: Receive thread started
,11-08 17:41:12.901  5664  5664 D AdapterServiceConfig: Adding HeadsetService
,11-08 17:41:12.901  5664  5664 D AdapterServiceConfig: Adding A2dpService
11-08 17:41:12.901  5664  5664 D AdapterServiceConfig: Adding HidService
11-08 17:41:12.901  5664  5664 D AdapterServiceConfig: Adding HealthService
11-08 17:41:12.901  5664  5664 D AdapterServiceConfig: Adding PanService
11-08 17:41:12.901  5664  5664 D AdapterServiceConfig: Adding GattService
,11-08 17:41:12.901  5664  5664 D AdapterServiceConfig: Adding BluetoothMapService
11-08 17:41:12.902  5664  5664 D AdapterServiceConfig: Adding SapService
,11-08 17:41:12.912   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@377a708:true
,11-08 17:41:12.913  5664  5664 D BluetoothAdapterState: make() - Creating AdapterState
,11-08 17:41:12.916  5664  5664 I bt_bluedroid: init
11-08 17:41:12.916  5664  5680 I BluetoothAdapterState: Entering OffState
,11-08 17:41:12.917  5664  5681 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-08 17:41:12.918  5664  5681 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-08 17:41:12.918  5664  5681 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-08 17:41:12.918  5664  5681 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-08 17:41:12.918  5664  5664 I bt_bluedroid: get_profile_interface socket
,11-08 17:41:12.920  5664  5684 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 17:41:12.920  5664  5664 I bt_bluedroid: get_profile_interface sdp
11-08 17:41:12.921  5664  5684 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 17:41:12.924  5664  5676 I bt_bluedroid: config_hci_snoop_log
,11-08 17:41:12.925   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-08 17:41:12.928  5664  5680 D BluetoothAdapterState: Current state: OFF, message: 0
11-08 17:41:12.928  5664  5680 D BluetoothAdapterProperties: Setting state to 14
11-08 17:41:12.929  5664  5680 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-08 17:41:12.930  5664  5680 D BluetoothBondStateMachine: make
,11-08 17:41:12.931  5664  5685 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-08 17:41:12.934  5664  5680 I BluetoothAdapterState: Entering PendingCommandState
,11-08 17:41:12.935  5664  5664 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-08 17:41:12.937  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
11-08 17:41:12.937  5664  5664 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 17:41:12.938  5664  5664 D BtGatt.GattService: Received start request. Starting profile...
11-08 17:41:12.938  5664  5664 D BtGatt.GattService: start()
11-08 17:41:12.938  5664  5664 I bt_bluedroid: get_profile_interface gatt
11-08 17:41:12.939  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
11-08 17:41:12.939  5664  5664 D BtGatt.AdvertiseManager: advertise manager created
,11-08 17:41:12.943  5664  5664 V BluetoothAdapterState: isTurningOff()=false
,11-08 17:41:12.943  5664  5664 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:12.943  5664  5664 V BluetoothAdapterState: isBleTurningOn()=true
11-08 17:41:12.943  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:12.944  5664  5680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-08 17:41:12.944  5664  5680 I bt_bluedroid: bt_bluedroid
11-08 17:41:12.945  5664  5681 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-08 17:41:12.945  5664  5681 I bt_hci  : start_up
,11-08 17:41:12.949  5664  5681 I bt_vendor: alloc value 0xf3c49871
,11-08 17:41:12.949  5664  5681 I bt_vendor: init
11-08 17:41:12.950  5664  5681 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-08 17:41:12.950  5664  5681 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-08 17:41:12.968   928  2885 E native  : do suspend false
,11-08 17:41:12.976   928  5678 D DhcpClient: Broadcasting DHCPDISCOVER
,11-08 17:41:12.995   928  5679 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172732, domain null
,11-08 17:41:12.996   928  5678 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172732 seconds
,11-08 17:41:12.996   928  5678 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-08 17:41:13.009   928  5679 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-08 17:41:13.010   928  5678 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-08 17:41:13.011   508   922 D CommandListener: Setting iface cfg
,11-08 17:41:13.013   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-08 17:41:13.015   928  5678 D DhcpClient: Scheduling renewal in 86399s
,11-08 17:41:13.019   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-08 17:41:13.020   928  2885 D WifiConfigStore: No blacklist allowed without epno enabled
,11-08 17:41:13.020   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-08 17:41:13.021   928  2887 D ConnectivityService: Adding iface wlan0 to network 101
11-08 17:41:13.025   928  2885 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-08 17:41:13.050   928  2887 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-08 17:41:13.050   928  2887 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-08 17:41:13.051   928  2887 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
11-08 17:41:13.053   928  2887 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-08 17:41:13.055   928  2887 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-08 17:41:13.056  5664  5681 D bt_hci  : start_up starting async portion
11-08 17:41:13.057  5664  5688 I bt_hci  : event_finish_startup
11-08 17:41:13.057  5664  5688 I bt_hci_h4: hal_open
11-08 17:41:13.058  5664  5688 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-08 17:41:13.058  5664  5688 I bt_userial_vendor: device fd = 54 open
11-08 17:41:13.056  5693  5693 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-08 17:41:13.061   928  2887 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-08 17:41:13.066   928  2887 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-08 17:41:13.067   928  2887 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-08 17:41:13.067   928  2887 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-08 17:41:13.067   928  2885 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-08 17:41:13.067   928  2887 D ConnectivityService:    accepting network in place of null
11-08 17:41:13.067   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 17:41:13.068   928  2887 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 17:41:13.071  5664  5688 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 17:41:13.073   928  5677 D NetlinkSocketObserver: NeighborEvent{elapsedMs=109726, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-08 17:41:13.073  5664  5688 D bt_hwcfg: Chipset BCM4358A3
11-08 17:41:13.073  5664  5688 D bt_hwcfg: Target name = [BCM4358A3]
11-08 17:41:13.073  5664  5688 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-08 17:41:13.087   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 17:41:13.105   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 17:41:13.108   928  2887 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-08 17:41:13.108   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-08 17:41:13.108  3628  3765 W QCNEJ   : |CORE| network available: 101
,11-08 17:41:13.110  3628  3765 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-08 17:41:13.110   928  2887 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-08 17:41:13.111  3628  3765 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-08 17:41:13.111  3628  3765 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-08 17:41:13.112   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-08 17:41:13.117  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 17:41:13.117  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:13.117  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:13.117  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:13.117  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:13.117  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:41:13.117  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.117  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:13.117  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:41:13.117  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:13.118  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:41:13.121  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 17:41:13.122  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:13.122  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:13.122  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:13.122  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:13.122  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:41:13.122  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.122  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:13.122  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:41:13.122  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:13.122  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.123  3964  3964 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-08 17:41:13.126  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:13.126  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:13.126  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:13.126  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:13.126  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:13.126  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:41:13.126  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.126  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:13.126  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:41:13.126  3964  3964 D SystemUpdateService: onCreate
11-08 17:41:13.126  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:13.127  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:41:13.127  3870  3870 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-08 17:41:13.132  3964  3964 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-08 17:41:13.142  3964  3964 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-08 17:41:13.148  3964  4196 I iu.UploadsManager: num queued entries: 0
11-08 17:41:13.148  3964  4196 I iu.UploadsManager: num updated entries: 0
,11-08 17:41:13.149  3964  4196 I iu.SyncManager: NEXT; no task
,11-08 17:41:13.151  3964  5702 I SystemUpdateService: active receiver: enabled
,11-08 17:41:13.153  3964  3964 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 17:41:13.154  3964  3964 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-08 17:41:13.156  5294  5294 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 17:41:13.160  5294  5294 D SprintDMHelper: simOperator: 
,11-08 17:41:13.160  5294  5294 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 17:41:13.188  3964  5702 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 17:41:13.190  3964  5702 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-08 17:41:13.190  3964  5702 I SystemUpdateService: now status is 0 (complete)
11-08 17:41:13.190  3964  5702 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-08 17:41:13.190  3964  5702 I SystemUpdateService: file has been verified
11-08 17:41:13.190  3964  5702 I SystemUpdateService: OTA package size = 21989297
,11-08 17:41:13.195  3964  5702 I SystemUpdateService: showing system update notification
,11-08 17:41:13.203   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 17:41:13.205  3964  3964 D SystemUpdateService: onDestroy
,11-08 17:41:13.214   928  5673 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-08 17:41:13.264   928  5673 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 08 Nov 2016 16:41:13 GMT], X-Android-Received-Millis=[1478623273263], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478623273239]}
,11-08 17:41:13.265   928  2887 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-08 17:41:13.265   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-08 17:41:13.265   928  2887 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-08 17:41:13.266   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-08 17:41:13.302  5664  5680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 17:41:13.379  5664  5688 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-08 17:41:13.380  5664  5688 D bt_hwcfg: Settlement delay -- 100 ms
,11-08 17:41:13.380  5664  5688 I bt_hwcfg: Setting fw settlement delay to 100 
,11-08 17:41:13.503  5664  5688 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 17:41:13.504  5664  5688 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-08 17:41:13.505  5664  5688 I bt_hwcfg: vendor lib fwcfg completed
11-08 17:41:13.505  5664  5688 I bt_vendor: firmware callback
11-08 17:41:13.505  5664  5688 I bt_hci  : firmware_config_callback
,11-08 17:41:13.513  5664  5710 I bt_btu  : btu_task pending for preload complete event
,11-08 17:41:13.513  5664  5710 I bt_btu_task: Bluetooth chip preload is complete
11-08 17:41:13.513  5664  5710 I bt_btu  : btu_task received preload complete event
,11-08 17:41:13.519  5664  5710 I         : BTE_InitTraceLevels -- TRC_HCI
,11-08 17:41:13.520  5664  5710 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-08 17:41:13.520  5664  5710 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-08 17:41:13.520  5664  5710 I         : BTE_InitTraceLevels -- TRC_AVDT
11-08 17:41:13.520  5664  5710 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-08 17:41:13.520  5664  5710 I         : BTE_InitTraceLevels -- TRC_A2D
11-08 17:41:13.521  5664  5710 I         : BTE_InitTraceLevels -- TRC_BNEP
11-08 17:41:13.521  5664  5710 I         : BTE_InitTraceLevels -- TRC_BTM
11-08 17:41:13.521  5664  5710 I         : BTE_InitTraceLevels -- TRC_GAP
11-08 17:41:13.521  5664  5710 I         : BTE_InitTraceLevels -- TRC_PAN
11-08 17:41:13.521  5664  5710 I         : BTE_InitTraceLevels -- TRC_SDP
,11-08 17:41:13.521  5664  5710 I         : BTE_InitTraceLevels -- TRC_GATT
11-08 17:41:13.521  5664  5710 I         : BTE_InitTraceLevels -- TRC_SMP
11-08 17:41:13.521  5664  5710 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-08 17:41:13.521  5664  5710 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-08 17:41:13.593  5664  5710 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bc7549
,11-08 17:41:13.593  5664  5710 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bc7549 
,11-08 17:41:13.615  5664  5684 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-08 17:41:13.616  5664  5684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-08 17:41:13.616  5664  5684 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-08 17:41:13.619  5664  5684 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 17:41:13.621  5664  5684 D BluetoothAdapterProperties: Scan Mode:20
,11-08 17:41:13.622  5664  5684 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-08 17:41:13.622  5664  5684 D bt_hci  : do_postload posting postload work item
11-08 17:41:13.622  5664  5688 I bt_hci  : event_postload
11-08 17:41:13.622  5664  5688 I bt_vendor: sco_config_cb
11-08 17:41:13.623  5664  5688 I bt_hci  : sco_config_callback postload finished.
,11-08 17:41:13.631  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:13.631  5664  5688 I bt_vendor: low_power_mode_cb
11-08 17:41:13.635  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:13.639  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:13.640  5664  5684 D bt_bte_conf: Device ID record 1 : primary
11-08 17:41:13.640  5664  5684 D bt_bte_conf:   vendorId            = 000f
11-08 17:41:13.640  5664  5684 D bt_bte_conf:   vendorIdSource      = 0001
11-08 17:41:13.640  5664  5684 D bt_bte_conf:   product             = 1200
11-08 17:41:13.640  5664  5684 D bt_bte_conf:   version             = 1436
,11-08 17:41:13.640  5664  5684 D bt_bte_conf:   clientExecutableURL = 
11-08 17:41:13.640  5664  5684 D bt_bte_conf:   serviceDescription  = 
11-08 17:41:13.640  5664  5684 D bt_bte_conf:   documentationURL    = 
11-08 17:41:13.641  5664  5684 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-08 17:41:13.641  5664  5681 D bt_stack_manager: event_start_up_stack finished
,11-08 17:41:13.641  5664  5680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-08 17:41:13.642  5664  5680 D BluetoothAdapterProperties: Setting state to 15
11-08 17:41:13.642  5664  5680 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-08 17:41:13.643  5664  5680 I BluetoothAdapterState: Entering BleOnState
,11-08 17:41:13.645  5664  5680 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-08 17:41:13.646  5664  5680 D BluetoothAdapterProperties: Setting state to 11
11-08 17:41:13.646  5664  5680 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-08 17:41:13.653  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:13.655  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
11-08 17:41:13.656  5664  5664 D HeadsetService: Received start request. Starting profile...
,11-08 17:41:13.656  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:13.662  5664  5664 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-08 17:41:13.662  5664  5664 D HeadsetStateMachine: make
11-08 17:41:13.663  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:13.668  5664  5680 I BluetoothAdapterState: Entering PendingCommandState
,11-08 17:41:13.674  5664  5664 D HeadsetStateMachine: max_hf_connections = 1
,11-08 17:41:13.674  5664  5664 I bt_bluedroid: get_profile_interface handsfree
11-08 17:41:13.674  5664  5684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-08 17:41:13.675  5664  5684 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-08 17:41:13.679  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
11-08 17:41:13.680  5664  5664 D A2dpService: Received start request. Starting profile...
11-08 17:41:13.681  5664  5664 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-08 17:41:13.681  3487  3487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 17:41:13.681  5664  5664 I bt_bluedroid: get_profile_interface avrcp
,11-08 17:41:13.687  5664  5664 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-08 17:41:13.687  5664  5664 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-08 17:41:13.687  5664  5664 D A2dpStateMachine: make
,11-08 17:41:13.689  5664  5664 I bt_bluedroid: get_profile_interface a2dp
,11-08 17:41:13.690  5664  5684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-08 17:41:13.692  5664  5717 D A2dpStateMachine: Enter Disconnected: -2
,11-08 17:41:13.692  5664  5664 I BluetoothHidServiceJni: classInitNative: succeeds
,11-08 17:41:13.692  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
,11-08 17:41:13.694  5616  5616 D BluetoothInputDevice: Proxy object connected
11-08 17:41:13.694  5664  5664 D HidService: Received start request. Starting profile...
11-08 17:41:13.694  5664  5664 I bt_bluedroid: get_profile_interface hidhost
11-08 17:41:13.694  5664  5684 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ba856d
11-08 17:41:13.694  5664  5664 D HidService: setHidService(): set to: null
11-08 17:41:13.694  5664  5684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-08 17:41:13.694  5616  5616 D HidProfile: Bluetooth service connected
11-08 17:41:13.695  5664  5664 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-08 17:41:13.695  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
11-08 17:41:13.696  5664  5664 D HealthService: Received start request. Starting profile...
11-08 17:41:13.698  5664  5664 I bt_bluedroid: get_profile_interface health
11-08 17:41:13.698  5664  5664 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-08 17:41:13.699  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
,11-08 17:41:13.700  5616  5616 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 17:41:13.700  5664  5664 D PanService: Received start request. Starting profile...
11-08 17:41:13.701  5664  5664 D BluetoothPanServiceJni: initializeNative(L110): pan
11-08 17:41:13.701  5664  5664 I bt_bluedroid: get_profile_interface pan
,11-08 17:41:13.701  5616  5616 D PanProfile: Bluetooth service connected
11-08 17:41:13.701  5664  5684 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-08 17:41:13.703  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
,11-08 17:41:13.704  5616  5616 D BluetoothMap: Proxy object connected
11-08 17:41:13.704  5664  5664 D BluetoothMapService: Received start request. Starting profile...
11-08 17:41:13.705  5664  5664 D BluetoothMapService: start()
11-08 17:41:13.705  5616  5616 D MapProfile: Bluetooth service connected
11-08 17:41:13.706  5616  5616 D BluetoothMap: getConnectedDevices()
11-08 17:41:13.706  5616  5616 D BluetoothMap: Bluetooth is Not enabled
11-08 17:41:13.707  5664  5664 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-08 17:41:13.708  5664  5664 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-08 17:41:13.708  5664  5664 D BluetoothMapAppObserver: createReceiver()
,11-08 17:41:13.709  5664  5664 D BluetoothMapAppObserver: initObservers()
11-08 17:41:13.709  5664  5664 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-08 17:41:13.714  5664  5664 V SapService: SapBinder()
,11-08 17:41:13.714  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
11-08 17:41:13.715  5664  5664 D SapService: Received start request. Starting profile...
11-08 17:41:13.715  5664  5664 V SapService: start()
,11-08 17:41:13.718  5664  5664 V BluetoothAdapterState: isTurningOff()=false
,11-08 17:41:13.718  5664  5664 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:13.718  5664  5715 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-08 17:41:13.718  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.718  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:13.718  5664  5664 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.719  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:13.720  5664  5664 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:13.720  5664  5664 V BluetoothAdapterState: isTurningOn()=true
,11-08 17:41:13.720  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.720  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:13.720  5664  5664 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:13.720  5664  5664 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:13.720  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.720  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:13.721  5664  5664 V BluetoothAdapterState: isTurningOff()=false
,11-08 17:41:13.721  5664  5664 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:13.721  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 17:41:13.721  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:13.722  5664  5680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-08 17:41:13.722  5664  5680 D BluetoothAdapterProperties: ScanMode =  20
,11-08 17:41:13.722  5664  5680 D BluetoothAdapterProperties: State =  11
,11-08 17:41:13.722  5664  5680 D BluetoothAdapterProperties: Setting state to 12
11-08 17:41:13.722  5664  5680 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-08 17:41:13.722   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 17:41:13.723  3041  5498 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 17:41:13.724  5664  5684 D BluetoothAdapterProperties: Scan Mode:21
11-08 17:41:13.724  5664  5680 I BluetoothAdapterState: Entering OnState
11-08 17:41:13.724  5664  5684 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 17:41:13.724   928   928 D BluetoothA2dp: Proxy object connected
11-08 17:41:13.724  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-08 17:41:13.727  5499  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-08 17:41:13.728  3041  3885 D BluetoothPan: onBluetoothStateChange on: true
,11-08 17:41:13.730  3668  3890 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:41:13.730  3041  3041 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 17:41:13.730  3041  3041 D PanProfile: Bluetooth service connected
11-08 17:41:13.730  3041  3053 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-08 17:41:13.731  5616  5627 D BluetoothPan: onBluetoothStateChange on: true
11-08 17:41:13.731   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:41:13.731  5616  5626 D BluetoothMap: onBluetoothStateChange: up=true
11-08 17:41:13.732  5499  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-08 17:41:13.732  5616  5627 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 17:41:13.734  5664  5664 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 17:41:13.734  5664  5664 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-08 17:41:13.735  3041  5498 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 17:41:13.735  5664  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:41:13.737  3041  3041 D BluetoothA2dp: Proxy object connected
11-08 17:41:13.737  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:13.737  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:13.737  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:13.737  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:13.737  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:13.737  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.737  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:13.737  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:41:13.740  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.740  3041  3052 D BluetoothMap: onBluetoothStateChange: up=true
,11-08 17:41:13.741  5664  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:41:13.743  3041  3041 D BluetoothMap: Proxy object connected
11-08 17:41:13.743  3041  3041 D MapProfile: Bluetooth service connected
11-08 17:41:13.743  3041  3041 D BluetoothMap: getConnectedDevices()
11-08 17:41:13.743   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:41:13.743   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:41:13.743  5616  5626 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-08 17:41:13.744  3041  3885 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-08 17:41:13.744  5664  5664 D ObexServerSockets: Succeed to create listening sockets 
11-08 17:41:13.744  5664  5664 D ObexServerSockets0: startAccept()
11-08 17:41:13.744  5664  5664 D ObexServerSockets0: prepareForNewConnect()
,11-08 17:41:13.747   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-08 17:41:13.747  3041  3041 D BluetoothInputDevice: Proxy object connected
11-08 17:41:13.747  3041  3041 D HidProfile: Bluetooth service connected
11-08 17:41:13.748  5664  5664 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-08 17:41:13.748  5664  5664 D BluetoothSdpJni: SDP Create record success - handle: 0
11-08 17:41:13.749  5616  5616 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-08 17:41:13.749  5664  5723 D ObexServerSockets0: Accepting socket connection...
,11-08 17:41:13.749  5664  5664 D BluetoothMapService: onReceive
,11-08 17:41:13.749  5664  5664 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 17:41:13.750  5664  5664 D BluetoothMapService: STATE_ON
11-08 17:41:13.750  5664  5724 D ObexServerSockets0: Accepting socket connection...
11-08 17:41:13.751  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:13.751  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:13.751  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:13.751  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:13.751  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:13.751  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.751  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:13.751  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:41:13.753  5664  5726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:41:13.754  5616  5616 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-08 17:41:13.754  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.755  5664  5726 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-08 17:41:13.755  5664  5726 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-08 17:41:13.758  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:13.758  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:13.758  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:13.758  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:13.758  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:13.758  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.758  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:13.758  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:41:13.761  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.761  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 17:41:13.762  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 17:41:13.763  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:13.764  5616  5616 D BluetoothA2dp: Proxy object connected
11-08 17:41:13.765  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:13.767  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:13.767  3487  3487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 17:41:13.769  5616  5616 D DockEventReceiver: finishStartingService: stopping service
,11-08 17:41:13.774  5616  5616 D BluetoothPbap: Proxy object connected
,11-08 17:41:13.775  5664  5664 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 17:41:13.775  5664  5664 D ObexServerSockets0: prepareForNewConnect()
11-08 17:41:13.775  5616  5616 D PbapServerProfile: Bluetooth service connected
,11-08 17:41:13.777  3041  3041 D BluetoothPbap: Proxy object connected
11-08 17:41:13.777  3041  3041 D PbapServerProfile: Bluetooth service connected
,11-08 17:41:13.781  5664  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:41:13.796  5664  5734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:41:13.797  5664  5734 I BtOppRfcommListener: Accept thread started.
,11-08 17:41:13.805  5499  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:13.806  5499  5545 D io.jxcore.node.ConnectivityMonitor: stop
11-08 17:41:13.806  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 17:41:13.807  5499  5545 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-08 17:41:13.808  5499  5545 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-08 17:41:13.810  5664  5680 D BluetoothAdapterState: Current state: ON, message: 23
11-08 17:41:13.810  5664  5680 D BluetoothAdapterProperties: Setting state to 13
,11-08 17:41:13.811  5664  5680 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-08 17:41:13.811  5664  5680 D BluetoothAdapterProperties: onBluetoothDisable()
11-08 17:41:13.811  5499  5545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:13.811  5664  5680 I BluetoothAdapterState: Entering PendingCommandState
,11-08 17:41:13.814  5664  5664 D BluetoothMapService: onReceive
,11-08 17:41:13.814  5664  5664 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 17:41:13.814  5664  5664 D BluetoothMapService: STATE_TURNING_OFF
11-08 17:41:13.814  5664  5664 D BluetoothMapService: MAP Service closeService in
,11-08 17:41:13.814  5664  5664 D BluetoothMapMasInstance0: MAP Service shutdown
,11-08 17:41:13.815  5664  5664 D ObexServerSockets0: shutdown(block = true)
11-08 17:41:13.815  5664  5723 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-08 17:41:13.815  5664  5684 D BluetoothAdapterProperties: Scan Mode:20
11-08 17:41:13.815  5664  5664 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-08 17:41:13.815  5664  5664 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 17:41:13.815  5664  5712 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-08 17:41:13.815  5664  5680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-08 17:41:13.817  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:13.817  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:13.817  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:13.817  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:13.817  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:13.817  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:41:13.817  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.817  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:13.817  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:41:13.818  5664  5724 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-08 17:41:13.818  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:13.818  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.818  5664  5664 I BtOppRfcommListener: stopping Accept Thread
11-08 17:41:13.819  5664  5734 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-08 17:41:13.819  5664  5734 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-08 17:41:13.820  5664  5664 D HeadsetService: Received stop request...Stopping profile...
11-08 17:41:13.821  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:13.821  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:13.821  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:13.821  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:13.821  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:13.821  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:41:13.821  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:13.821  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:13.821  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:41:13.821  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 17:41:13.821  5499  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:13.822  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:41:13.823  5664  5664 D A2dpService: Received stop request...Stopping profile...
11-08 17:41:13.823  5664  5717 D A2dpStateMachine: Exit Disconnected: -1
11-08 17:41:13.825   928   928 D BluetoothA2dp: Proxy object disconnected
11-08 17:41:13.825  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:13.825  5664  5664 D HidService: Received stop request...Stopping profile...
11-08 17:41:13.826  5664  5664 D HidService: Stopping Bluetooth HidService
,11-08 17:41:13.828  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:13.828  5664  5664 D HealthService: Received stop request...Stopping profile...
11-08 17:41:13.829  5616  5616 D DockEventReceiver: finishStartingService: stopping service
11-08 17:41:13.829  5664  5664 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:13.829  5664  5664 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:13.829  5616  5616 D BluetoothA2dp: Proxy object disconnected
11-08 17:41:13.829  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 17:41:13.829  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:13.830  5616  5616 D BluetoothInputDevice: Proxy object disconnected
11-08 17:41:13.830  5616  5616 D HidProfile: Bluetooth service disconnected
11-08 17:41:13.830  5664  5664 D PanService: Received stop request...Stopping profile...
11-08 17:41:13.831  3041  3041 D BluetoothA2dp: Proxy object disconnected
11-08 17:41:13.831  3041  3041 D BluetoothInputDevice: Proxy object disconnected
11-08 17:41:13.831  3041  3041 D HidProfile: Bluetooth service disconnected
11-08 17:41:13.832  5616  5616 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 17:41:13.832  5616  5616 D PanProfile: Bluetooth service disconnected
11-08 17:41:13.832  3041  3041 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 17:41:13.833  3041  3041 D PanProfile: Bluetooth service disconnected
11-08 17:41:13.834  5664  5664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-08 17:41:13.834  5664  5664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-08 17:41:13.834  5664  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:13.834  5664  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:13.834  5664  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-08 17:41:13.834  5664  5664 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:13.834  5664  5664 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:13.834  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.834  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:13.837  5664  5664 D BluetoothMapService: Received stop request...Stopping profile...
11-08 17:41:13.837  5664  5664 D BluetoothMapService: stop()
11-08 17:41:13.837  5664  5684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-08 17:41:13.837  5664  5684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-08 17:41:13.837  5664  5684 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
11-08 17:41:13.837  5664  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:13.837  5664  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:13.837  5664  5664 D BluetoothMapAppObserver: deinitObservers()
11-08 17:41:13.837  5664  5664 D BluetoothMapAppObserver: removeReceiver()
11-08 17:41:13.837  5664  5710 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-08 17:41:13.837  5664  5710 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 17:41:13.837  5664  5710 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 17:41:13.837  5664  5710 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 17:41:13.838  5616  5616 D BluetoothMap: Proxy object disconnected
11-08 17:41:13.838  5616  5616 D MapProfile: Bluetooth service disconnected
11-08 17:41:13.839  5664  5664 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:13.839  5664  5664 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:13.839  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.839  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:13.840  5664  5664 D SapService: Received stop request...Stopping profile...
,11-08 17:41:13.840  5664  5664 V SapService: stop()
11-08 17:41:13.841  5664  5664 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-08 17:41:13.841  5664  5664 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-08 17:41:13.841  5664  5684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 17:41:13.842  5664  5664 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:13.842  5664  5664 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:13.842  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.842  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:13.842  5664  5664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-08 17:41:13.842  5664  5684 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-08 17:41:13.842  5664  5664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-08 17:41:13.842  5664  5664 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:13.842  5664  5664 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:13.842  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.842  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:13.843  5664  5664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-08 17:41:13.843  5664  5664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-08 17:41:13.844  5664  5664 D BluetoothMapService: MAP Service closeService in
11-08 17:41:13.845  5616  5616 D BluetoothPbap: Proxy object disconnected
11-08 17:41:13.845  5616  5616 D PbapServerProfile: Bluetooth service disconnected
11-08 17:41:13.845  5664  5664 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:13.845  5664  5664 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:13.845  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.845  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:13.845  5664  5664 D BluetoothMapService: cleanup()
11-08 17:41:13.845  5664  5664 D BluetoothMapService: MAP Service closeService in
11-08 17:41:13.845  5664  5664 V BluetoothAdapterState: isTurningOff()=true
11-08 17:41:13.845  5664  5664 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:13.845  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:13.845  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:13.845  5664  5680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-08 17:41:13.846  5664  5680 D BluetoothAdapterProperties: Setting state to 15
11-08 17:41:13.846  5664  5680 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-08 17:41:13.846  5664  5680 I BluetoothAdapterState: Entering BleOnState
11-08 17:41:13.846   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-08 17:41:13.846  3041  3041 D BluetoothMap: Proxy object disconnected
11-08 17:41:13.847  3041  3041 D MapProfile: Bluetooth service disconnected
11-08 17:41:13.847  3041  3041 D BluetoothPbap: Proxy object disconnected
11-08 17:41:13.847  3041  3041 D PbapServerProfile: Bluetooth service disconnected
11-08 17:41:13.847  3041  3885 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 17:41:13.847  3487  3487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 17:41:13.849  3041  3053 D BluetoothPan: onBluetoothStateChange on: false
,11-08 17:41:13.851  3668  3695 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-08 17:41:13.852  3041  3052 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-08 17:41:13.852  5616  5627 D BluetoothPan: onBluetoothStateChange on: false
,11-08 17:41:13.853  5616  5626 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 17:41:13.853   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:41:13.854  5616  5627 D BluetoothMap: onBluetoothStateChange: up=false
11-08 17:41:13.855  5616  5626 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 17:41:13.856  3041  5498 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 17:41:13.857  3041  3885 D BluetoothMap: onBluetoothStateChange: up=false
11-08 17:41:13.857   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:41:13.857   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-08 17:41:13.857  5616  5627 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-08 17:41:13.859  3041  3053 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 17:41:13.859  5616  5626 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:41:13.860  5664  5680 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-08 17:41:13.860  5664  5680 D BluetoothAdapterProperties: Setting state to 16
11-08 17:41:13.860  5664  5680 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-08 17:41:13.860  5664  5680 D BluetoothAdapterProperties: onBleDisable
11-08 17:41:13.861  5664  5680 I BluetoothAdapterState: Entering PendingCommandState
11-08 17:41:13.861  5664  5681 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-08 17:41:13.862  5664  5710 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-08 17:41:13.862  5664  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:41:13.862  5664  5684 D BluetoothAdapterProperties: Scan Mode:20
11-08 17:41:13.863  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 17:41:13.864  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:13.866  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:13.870  3487  3487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 17:41:13.870  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:13.874  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:13.876  5616  5616 D DockEventReceiver: finishStartingService: stopping service
,11-08 17:41:14.062  5664  5684 I bt_hci  : shut_down
11-08 17:41:14.062  5664  5688 D bt_hwcfg: hw_epilog_process
11-08 17:41:14.063  5664  5688 I bt_vendor: low_power_mode_cb
,11-08 17:41:14.065  5664  5688 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-08 17:41:14.066  5664  5688 I bt_vendor: epilog_cb
11-08 17:41:14.066  5664  5688 I bt_hci  : epilog_finished_callback
11-08 17:41:14.066  5664  5684 I bt_hci_h4: hal_close
11-08 17:41:14.067  5664  5684 I bt_userial_vendor: device fd = 54 close
,11-08 17:41:14.108   928  2887 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-08 17:41:14.187  5664  5681 D bt_stack_manager: event_shut_down_stack finished.
,11-08 17:41:14.188  5664  5680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-08 17:41:14.191  5664  5680 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-08 17:41:14.191  5664  5664 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 17:41:14.192  5664  5664 D BtGatt.GattService: Received stop request...Stopping profile...
11-08 17:41:14.192  5664  5664 D BtGatt.GattService: stop()
11-08 17:41:14.192  5664  5664 D BtGatt.AdvertiseManager: advertise clients cleared
11-08 17:41:14.194  5664  5664 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:14.194  5664  5664 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:14.194  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 17:41:14.194  5664  5664 V BluetoothAdapterState: isBleTurningOff()=true
11-08 17:41:14.194  5664  5680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-08 17:41:14.195  5664  5680 D BluetoothAdapterProperties: Setting state to 10
11-08 17:41:14.195  5664  5680 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-08 17:41:14.196   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
11-08 17:41:14.196  5664  5680 I BluetoothAdapterState: Entering OffState
,11-08 17:41:14.207  5664  5664 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-08 17:41:14.207  5664  5664 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-08 17:41:14.207  5664  5664 I BluetoothServiceJni: cleanupNative: return from cleanup
11-08 17:41:14.209  5664  5681 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-08 17:41:14.214  5664  5664 I art     : System.exit called, status: 0
,11-08 17:41:14.214  5664  5664 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-08 17:41:14.243   928  3703 I ActivityManager: Process com.android.bluetooth (pid 5664) has died
,11-08 17:41:14.312  5499  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:14.312  5499  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:14.312  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:14.312  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:14.312  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:14.312  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:41:14.312  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:14.312  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:14.312  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:41:14.312  5499  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:41:14.312  5499  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:41:14.318  5499  5545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:14.342   928   945 I ActivityManager: Start proc 5740:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-08 17:41:14.409  5740  5740 D AdapterServiceConfig: Adding HeadsetService
,11-08 17:41:14.410  5740  5740 D AdapterServiceConfig: Adding A2dpService
11-08 17:41:14.410  5740  5740 D AdapterServiceConfig: Adding HidService
11-08 17:41:14.410  5740  5740 D AdapterServiceConfig: Adding HealthService
11-08 17:41:14.410  5740  5740 D AdapterServiceConfig: Adding PanService
,11-08 17:41:14.411  5740  5740 D AdapterServiceConfig: Adding GattService
11-08 17:41:14.411  5740  5740 D AdapterServiceConfig: Adding BluetoothMapService
11-08 17:41:14.411  5740  5740 D AdapterServiceConfig: Adding SapService
,11-08 17:41:14.424   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8d7160c:true
,11-08 17:41:14.424  5740  5740 D BluetoothAdapterState: make() - Creating AdapterState
,11-08 17:41:14.426  5740  5740 I bt_bluedroid: init
,11-08 17:41:14.426  5740  5752 I BluetoothAdapterState: Entering OffState
,11-08 17:41:14.428  5740  5753 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-08 17:41:14.428  5740  5753 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-08 17:41:14.428  5740  5753 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-08 17:41:14.429  5740  5753 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-08 17:41:14.429  5740  5740 I bt_bluedroid: get_profile_interface socket
,11-08 17:41:14.430  5740  5756 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 17:41:14.430  5740  5740 I bt_bluedroid: get_profile_interface sdp
11-08 17:41:14.432  5740  5756 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 17:41:14.436  5740  5751 I bt_bluedroid: config_hci_snoop_log
,11-08 17:41:14.437   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-08 17:41:14.489  5740  5752 D BluetoothAdapterState: Current state: OFF, message: 0
,11-08 17:41:14.489  5740  5752 D BluetoothAdapterProperties: Setting state to 14
11-08 17:41:14.489  5740  5752 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-08 17:41:14.490  5740  5752 D BluetoothBondStateMachine: make
,11-08 17:41:14.492  5740  5757 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-08 17:41:14.494  5740  5752 I BluetoothAdapterState: Entering PendingCommandState
,11-08 17:41:14.495  5740  5740 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-08 17:41:14.497  5740  5740 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
,11-08 17:41:14.498  5740  5740 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 17:41:14.498  5740  5740 D BtGatt.GattService: Received start request. Starting profile...
11-08 17:41:14.498  5740  5740 D BtGatt.GattService: start()
11-08 17:41:14.498  5740  5740 I bt_bluedroid: get_profile_interface gatt
11-08 17:41:14.499  5740  5740 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
11-08 17:41:14.499  5740  5740 D BtGatt.AdvertiseManager: advertise manager created
,11-08 17:41:14.503  5740  5740 V BluetoothAdapterState: isTurningOff()=false
,11-08 17:41:14.503  5740  5740 V BluetoothAdapterState: isTurningOn()=false
11-08 17:41:14.503  5740  5740 V BluetoothAdapterState: isBleTurningOn()=true
11-08 17:41:14.503  5740  5740 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:14.504  5740  5752 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-08 17:41:14.505  5740  5752 I bt_bluedroid: bt_bluedroid
11-08 17:41:14.505  5740  5753 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-08 17:41:14.505  5740  5753 I bt_hci  : start_up
,11-08 17:41:14.510  5740  5753 I bt_vendor: alloc value 0xf3c49871
,11-08 17:41:14.510  5740  5753 I bt_vendor: init
11-08 17:41:14.510  5740  5753 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-08 17:41:14.510  5740  5753 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-08 17:41:14.620  5740  5753 D bt_hci  : start_up starting async portion
,11-08 17:41:14.620  5740  5760 I bt_hci  : event_finish_startup
,11-08 17:41:14.621  5740  5760 I bt_hci_h4: hal_open
11-08 17:41:14.621  5740  5760 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-08 17:41:14.619  5761  5761 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 17:41:14.624  5740  5760 I bt_userial_vendor: device fd = 54 open
,11-08 17:41:14.638  5740  5760 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 17:41:14.641  5740  5760 D bt_hwcfg: Chipset BCM4358A3
,11-08 17:41:14.641  5740  5760 D bt_hwcfg: Target name = [BCM4358A3]
11-08 17:41:14.642  5740  5760 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-08 17:41:14.822  5740  5752 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 17:41:15.022  5740  5760 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-08 17:41:15.022  5740  5760 D bt_hwcfg: Settlement delay -- 100 ms
11-08 17:41:15.022  5740  5760 I bt_hwcfg: Setting fw settlement delay to 100 
,11-08 17:41:15.146  5740  5760 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 17:41:15.146  5740  5760 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-08 17:41:15.148  5740  5760 I bt_hwcfg: vendor lib fwcfg completed
,11-08 17:41:15.148  5740  5760 I bt_vendor: firmware callback
11-08 17:41:15.148  5740  5760 I bt_hci  : firmware_config_callback
11-08 17:41:15.156  5740  5763 I bt_btu  : btu_task pending for preload complete event
,11-08 17:41:15.156  5740  5763 I bt_btu_task: Bluetooth chip preload is complete
11-08 17:41:15.157  5740  5763 I bt_btu  : btu_task received preload complete event
,11-08 17:41:15.164  5740  5763 I         : BTE_InitTraceLevels -- TRC_HCI
,11-08 17:41:15.164  5740  5763 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-08 17:41:15.164  5740  5763 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-08 17:41:15.164  5740  5763 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-08 17:41:15.164  5740  5763 I         : BTE_InitTraceLevels -- TRC_AVRC
11-08 17:41:15.165  5740  5763 I         : BTE_InitTraceLevels -- TRC_A2D
11-08 17:41:15.165  5740  5763 I         : BTE_InitTraceLevels -- TRC_BNEP
11-08 17:41:15.165  5740  5763 I         : BTE_InitTraceLevels -- TRC_BTM
,11-08 17:41:15.165  5740  5763 I         : BTE_InitTraceLevels -- TRC_GAP
11-08 17:41:15.165  5740  5763 I         : BTE_InitTraceLevels -- TRC_PAN
11-08 17:41:15.165  5740  5763 I         : BTE_InitTraceLevels -- TRC_SDP
,11-08 17:41:15.165  5740  5763 I         : BTE_InitTraceLevels -- TRC_GATT
11-08 17:41:15.165  5740  5763 I         : BTE_InitTraceLevels -- TRC_SMP
11-08 17:41:15.165  5740  5763 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-08 17:41:15.166  5740  5763 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-08 17:41:15.249  5740  5763 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bc7549
11-08 17:41:15.249  5740  5763 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bc7549 
,11-08 17:41:15.277  5740  5756 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-08 17:41:15.279  5740  5756 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 17:41:15.279  5740  5756 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 17:41:15.281  5740  5756 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 17:41:15.284  5740  5756 D BluetoothAdapterProperties: Scan Mode:20
11-08 17:41:15.284  5740  5756 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 17:41:15.284  5740  5756 D bt_hci  : do_postload posting postload work item
,11-08 17:41:15.284  5740  5760 I bt_hci  : event_postload
,11-08 17:41:15.284  5740  5760 I bt_vendor: sco_config_cb
,11-08 17:41:15.284  5740  5760 I bt_hci  : sco_config_callback postload finished.
,11-08 17:41:15.292  5740  5760 I bt_vendor: low_power_mode_cb
,11-08 17:41:15.292  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:15.295  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:15.296  5740  5756 D bt_bte_conf: Device ID record 1 : primary
11-08 17:41:15.296  5740  5756 D bt_bte_conf:   vendorId            = 000f
11-08 17:41:15.296  5740  5756 D bt_bte_conf:   vendorIdSource      = 0001
11-08 17:41:15.296  5740  5756 D bt_bte_conf:   product             = 1200
11-08 17:41:15.296  5740  5756 D bt_bte_conf:   version             = 1436
11-08 17:41:15.296  5740  5756 D bt_bte_conf:   clientExecutableURL = 
11-08 17:41:15.296  5740  5756 D bt_bte_conf:   serviceDescription  = 
11-08 17:41:15.296  5740  5756 D bt_bte_conf:   documentationURL    = 
11-08 17:41:15.296  5740  5756 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-08 17:41:15.296  5740  5753 D bt_stack_manager: event_start_up_stack finished
,11-08 17:41:15.297  5740  5752 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-08 17:41:15.297  5740  5752 D BluetoothAdapterProperties: Setting state to 15
11-08 17:41:15.297  5740  5752 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-08 17:41:15.298  5740  5752 I BluetoothAdapterState: Entering BleOnState
,11-08 17:41:15.300  5740  5752 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-08 17:41:15.300  5740  5752 D BluetoothAdapterProperties: Setting state to 11
11-08 17:41:15.300  5740  5752 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-08 17:41:15.304  5740  5740 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
,11-08 17:41:15.310  5740  5740 D HeadsetService: Received start request. Starting profile...
,11-08 17:41:15.310  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:15.312  3041  5498 D BluetoothHeadset: Proxy object connected
11-08 17:41:15.313  5740  5740 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-08 17:41:15.313  5740  5740 D HeadsetStateMachine: make
11-08 17:41:15.313  3668  3890 D BluetoothHeadset: Proxy object connected
,11-08 17:41:15.315  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:15.315  3041  3041 D HeadsetProfile: Bluetooth service connected
11-08 17:41:15.317   928   928 D BluetoothHeadset: Proxy object connected
11-08 17:41:15.317   928   928 D BluetoothHeadset: Proxy object connected
11-08 17:41:15.317   928   928 D BluetoothHeadset: Proxy object connected
,11-08 17:41:15.319  5616  5627 D BluetoothHeadset: Proxy object connected
11-08 17:41:15.321  5616  5616 D HeadsetProfile: Bluetooth service connected
11-08 17:41:15.322  5740  5752 I BluetoothAdapterState: Entering PendingCommandState
,11-08 17:41:15.324  5740  5740 D HeadsetStateMachine: max_hf_connections = 1
11-08 17:41:15.325  5740  5740 I bt_bluedroid: get_profile_interface handsfree
,11-08 17:41:15.325  5740  5756 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-08 17:41:15.325  5740  5756 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
11-08 17:41:15.327  5740  5740 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
11-08 17:41:15.328  5740  5752 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
11-08 17:41:15.328  5740  5740 D A2dpService: Received start request. Starting profile...
,11-08 17:41:15.329  5740  5740 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-08 17:41:15.329  5740  5740 I bt_bluedroid: get_profile_interface avrcp
,11-08 17:41:15.334  5740  5740 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-08 17:41:15.334  5740  5740 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-08 17:41:15.334  5740  5740 D A2dpStateMachine: make
,11-08 17:41:15.335  5740  5740 I bt_bluedroid: get_profile_interface a2dp
,11-08 17:41:15.336  5740  5756 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-08 17:41:15.337  5740  5771 D A2dpStateMachine: Enter Disconnected: -2
11-08 17:41:15.338  5740  5740 I BluetoothHidServiceJni: classInitNative: succeeds
11-08 17:41:15.338  5740  5740 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
,11-08 17:41:15.339  5740  5740 D HidService: Received start request. Starting profile...
11-08 17:41:15.339  5740  5740 I bt_bluedroid: get_profile_interface hidhost
11-08 17:41:15.339  5740  5740 D HidService: setHidService(): set to: null
11-08 17:41:15.339  5740  5756 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ba856d
11-08 17:41:15.339  5740  5756 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-08 17:41:15.340  5740  5740 I BluetoothHealthServiceJni: classInitNative: succeeds
11-08 17:41:15.340  5740  5740 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
11-08 17:41:15.341  5740  5740 D HealthService: Received start request. Starting profile...
,11-08 17:41:15.342  5740  5740 I bt_bluedroid: get_profile_interface health
,11-08 17:41:15.344  5740  5740 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-08 17:41:15.345  3487  3487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 17:41:15.345  5740  5740 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
,11-08 17:41:15.346  5740  5740 D PanService: Received start request. Starting profile...
,11-08 17:41:15.346  5740  5740 D BluetoothPanServiceJni: initializeNative(L110): pan
11-08 17:41:15.346  5740  5740 I bt_bluedroid: get_profile_interface pan
11-08 17:41:15.347  5740  5756 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-08 17:41:15.348  5740  5740 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
,11-08 17:41:15.349  5740  5740 D BluetoothMapService: Received start request. Starting profile...
,11-08 17:41:15.349  5740  5740 D BluetoothMapService: start()
11-08 17:41:15.352  5740  5740 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-08 17:41:15.352  5740  5740 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-08 17:41:15.353  5740  5740 D BluetoothMapAppObserver: createReceiver()
11-08 17:41:15.354  5740  5740 D BluetoothMapAppObserver: initObservers()
11-08 17:41:15.354  5740  5740 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-08 17:41:15.360  5740  5740 V SapService: SapBinder()
11-08 17:41:15.360  5740  5740 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
,11-08 17:41:15.361  5740  5740 D SapService: Received start request. Starting profile...
11-08 17:41:15.361  5740  5740 V SapService: start()
,11-08 17:41:15.364  5740  5740 V BluetoothAdapterState: isTurningOff()=false
,11-08 17:41:15.364  5740  5740 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:15.364  5740  5740 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:15.364  5740  5740 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:15.365  5740  5740 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:15.365  5740  5740 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:15.365  5740  5740 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:15.365  5740  5740 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:15.365  5740  5769 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-08 17:41:15.365  5740  5740 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:15.365  5740  5740 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:15.365  5740  5740 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:15.365  5740  5740 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:41:15.365  5740  5740 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:15.365  5740  5740 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:15.366  5740  5740 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:15.366  5740  5740 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:15.366  5740  5740 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:15.366  5740  5740 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:15.366  5740  5740 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:15.366  5740  5740 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:15.367  5740  5740 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:15.367  5740  5740 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:15.367  5740  5740 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:15.367  5740  5740 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:15.368  5740  5740 V BluetoothAdapterState: isTurningOff()=false
11-08 17:41:15.368  5740  5740 V BluetoothAdapterState: isTurningOn()=true
11-08 17:41:15.368  5740  5740 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:41:15.368  5740  5740 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:41:15.368  5740  5752 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-08 17:41:15.368  5740  5752 D BluetoothAdapterProperties: ScanMode =  20
,11-08 17:41:15.368  5740  5752 D BluetoothAdapterProperties: State =  11
11-08 17:41:15.369  5740  5752 D BluetoothAdapterProperties: Setting state to 12
11-08 17:41:15.369  5740  5752 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-08 17:41:15.369   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 17:41:15.369  5740  5752 I BluetoothAdapterState: Entering OnState
11-08 17:41:15.369  5740  5756 D BluetoothAdapterProperties: Scan Mode:21
11-08 17:41:15.370  5740  5756 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-08 17:41:15.370  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 17:41:15.370  3041  3885 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 17:41:15.372   928   928 D BluetoothA2dp: Proxy object connected
11-08 17:41:15.374  3041  3052 D BluetoothPan: onBluetoothStateChange on: true
11-08 17:41:15.374  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:15.374  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:15.374  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:15.374  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:15.374  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:15.374  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:15.374  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:15.374  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:41:15.376  3668  3704 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:41:15.376  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:15.377  3041  5498 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:41:15.377  3041  3041 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 17:41:15.377  5616  5626 D BluetoothPan: onBluetoothStateChange on: true
11-08 17:41:15.377  3041  3041 D PanProfile: Bluetooth service connected
11-08 17:41:15.378  5616  5627 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 17:41:15.379  5740  5740 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-08 17:41:15.380  5740  5740 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-08 17:41:15.380   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:41:15.380  5616  5626 D BluetoothMap: onBluetoothStateChange: up=true
11-08 17:41:15.380  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:15.380  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:15.380  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:15.380  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:15.380  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:15.380  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:15.380  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:15.380  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:41:15.381  5740  5740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:41:15.382  5616  5737 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 17:41:15.382  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:15.383  5740  5740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:41:15.383  5616  5616 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 17:41:15.383  5616  5616 D PanProfile: Bluetooth service connected
11-08 17:41:15.383  5616  5616 D BluetoothA2dp: Proxy object connected
11-08 17:41:15.384  3041  3885 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 17:41:15.384  5740  5740 D ObexServerSockets: Succeed to create listening sockets 
11-08 17:41:15.384  5740  5740 D ObexServerSockets0: startAccept()
11-08 17:41:15.384  5740  5740 D ObexServerSockets0: prepareForNewConnect()
11-08 17:41:15.385  3041  3041 D BluetoothA2dp: Proxy object connected
11-08 17:41:15.385  3041  5498 D BluetoothMap: onBluetoothStateChange: up=true
11-08 17:41:15.386  5740  5740 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-08 17:41:15.386  5740  5740 D BluetoothSdpJni: SDP Create record success - handle: 0
11-08 17:41:15.387  5740  5777 D ObexServerSockets0: Accepting socket connection...
,11-08 17:41:15.387   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:41:15.387   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:41:15.387  5616  5627 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 17:41:15.387  3041  3041 D BluetoothMap: Proxy object connected
11-08 17:41:15.387  5740  5778 D ObexServerSockets0: Accepting socket connection...
11-08 17:41:15.387  3041  3041 D MapProfile: Bluetooth service connected
11-08 17:41:15.388  3041  3041 D BluetoothMap: getConnectedDevices()
11-08 17:41:15.388  5616  5616 D BluetoothMap: Proxy object connected
11-08 17:41:15.388  5616  5616 D MapProfile: Bluetooth service connected
11-08 17:41:15.388  5616  5616 D BluetoothMap: getConnectedDevices()
11-08 17:41:15.390  3041  3885 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 17:41:15.391  3041  3041 D BluetoothInputDevice: Proxy object connected
11-08 17:41:15.391  5616  5626 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:41:15.391  3041  3041 D HidProfile: Bluetooth service connected
11-08 17:41:15.392   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-08 17:41:15.393   928   928 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
11-08 17:41:15.393  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 17:41:15.393  5740  5740 D BluetoothMapService: onReceive
11-08 17:41:15.393  5740  5740 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 17:41:15.393  5740  5740 D BluetoothMapService: STATE_ON
11-08 17:41:15.394  5616  5616 D BluetoothInputDevice: Proxy object connected
11-08 17:41:15.394  5616  5616 D HidProfile: Bluetooth service connected
11-08 17:41:15.396  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:15.398  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:15.398  5740  5780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:41:15.399  5740  5780 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-08 17:41:15.399  5740  5780 D BluetoothSdpJni: SDP Create record success - handle: 1
11-08 17:41:15.400  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 17:41:15.407  3487  3487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 17:41:15.410  5616  5616 D DockEventReceiver: finishStartingService: stopping service
,11-08 17:41:15.414  5616  5616 D BluetoothPbap: Proxy object connected
,11-08 17:41:15.414  5616  5616 D PbapServerProfile: Bluetooth service connected
,11-08 17:41:15.418  3041  3041 D BluetoothPbap: Proxy object connected
,11-08 17:41:15.418  3041  3041 D PbapServerProfile: Bluetooth service connected
,11-08 17:41:15.419  5740  5740 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 17:41:15.419  5740  5740 D ObexServerSockets0: prepareForNewConnect()
,11-08 17:41:15.420  5740  5784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:41:15.436  5740  5788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:41:15.437  5740  5788 I BtOppRfcommListener: Accept thread started.
,11-08 17:41:15.843  5499  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:15.843  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:15.843  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:15.843  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:15.843  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:15.843  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:15.843  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:15.843  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:41:15.848  5499  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:15.851  5499  5545 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-08 17:41:15.854   928  3060 D WifiService: setWifiEnabled: false pid=5499, uid=10077
,11-08 17:41:15.854   928  3060 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:41:15.859  5499  5545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:15.859   928  2885 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-08 17:41:15.859   928  2885 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-08 17:41:15.860   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 17:41:15.860   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:41:15.877   928  5678 D DhcpClient: Clearing IP address
,11-08 17:41:15.877   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-08 17:41:15.885   508   922 D CommandListener: Setting iface cfg
,11-08 17:41:15.888   928  5679 D DhcpClient: Receive thread stopped
,11-08 17:41:15.896  3487  5708 V NativeCrypto: Read error: ssl=0x7f7d2c9380: I/O error during system call, Connection timed out
,11-08 17:41:15.898  3487  5708 V NativeCrypto: SSL shutdown failed: ssl=0x7f7d2c9380: I/O error during system call, Broken pipe
,11-08 17:41:15.899   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-08 17:41:15.899   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-08 17:41:15.903   550   550 E Parcel  : Reading a NULL string not supported here.
11-08 17:41:15.904   928   928 D RttService: SCAN_AVAILABLE : 1
11-08 17:41:15.905   928  2994 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-08 17:41:15.908   928  2887 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-08 17:41:15.909  3628  3765 W QCNEJ   : |CORE| network lost: 101
,11-08 17:41:15.911  3628  3765 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-08 17:41:15.927   928  2885 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-08 17:41:15.936   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 17:41:15.941   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 17:41:15.959   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-08 17:41:15.959   508   922 D CommandListener: Clearing all IP addresses on wlan0
11-08 17:41:15.959   928  2887 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-08 17:41:15.960   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-08 17:41:15.961   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-08 17:41:15.964   928  2885 D DhcpClient: doQuit
11-08 17:41:15.964   928  2885 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-08 17:41:15.965   928  5678 D DhcpClient: onQuitting
11-08 17:41:15.965  5612  5612 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-08 17:41:15.969  3870  3870 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-08 17:41:15.969  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:15.969  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:15.969  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:15.969  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:15.969  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:15.969  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:15.969  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:15.969  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:15.973  3964  3964 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-08 17:41:15.975  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:41:15.977  3964  3964 D SystemUpdateService: onCreate
11-08 17:41:15.979  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:15.979  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:15.979  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:15.979  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:41:15.979  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:15.979  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:15.979  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:15.979  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:41:15.981  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:41:15.984  3964  3964 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-08 17:41:15.985  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:15.985  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:15.985  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:15.985  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:41:15.985  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:15.985  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:15.985  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:15.985  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:41:15.987  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:15.988  5612  5612 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-08 17:41:15.989  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:15.991  3964  5798 I SystemUpdateService: active receiver: enabled
,11-08 17:41:15.992  3964  3964 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-08 17:41:15.992  5612  5612 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-08 17:41:15.997  3964  4196 I iu.UploadsManager: num queued entries: 0
11-08 17:41:15.998  3964  4196 I iu.UploadsManager: num updated entries: 0
11-08 17:41:15.998  3964  4196 I iu.SyncManager: NEXT; no task
,11-08 17:41:16.001  3964  3964 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 17:41:16.002  3964  3964 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 17:41:16.004  5294  5294 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 17:41:16.008  5294  5294 D SprintDMHelper: simOperator: 
11-08 17:41:16.008  5294  5294 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 17:41:16.018  3964  5798 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 17:41:16.018   508   922 E Netd    : netlink response contains error (No such file or directory)
,11-08 17:41:16.019  5612  5612 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-08 17:41:16.024  3964  5798 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-08 17:41:16.025  3964  5798 I SystemUpdateService: now status is 0 (complete)
11-08 17:41:16.025  3964  5798 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-08 17:41:16.025  3964  5798 I SystemUpdateService: file has been verified
11-08 17:41:16.026  3964  5798 I SystemUpdateService: OTA package size = 21989297
,11-08 17:41:16.031  5612  5612 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-08 17:41:16.041  3964  5798 I SystemUpdateService: showing system update notification
,11-08 17:41:16.047   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 17:41:16.048  3964  3964 D SystemUpdateService: onDestroy
,11-08 17:41:16.135   928  2885 D wifi    : In wifi stop Hal
,11-08 17:41:16.135   928  2885 D wifi    : halHandle = 0x7f6ab48400, mVM = 0x7f8714d140, mCls = 0x1015e2
,11-08 17:41:16.135   928  5611 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-08 17:41:16.135   928  5611 D WifiHAL : Got a signal to exit!!!
11-08 17:41:16.135   928  5611 I WifiHAL : Exit wifi_event_loop
11-08 17:41:16.135   928  2885 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-08 17:41:16.136   928  2885 E WifiHAL : Event processing terminated
,11-08 17:41:16.136   928  2885 D wifi    : In wifi cleaned up handler
11-08 17:41:16.136   928  2885 I WifiHAL : Internal cleanup completed
,11-08 17:41:16.141  4424  4424 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 17:41:16.142  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:16.146  3854  4108 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 17:41:16.148  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:16.170   928  5611 D wifi    : set interface wlan0 flags (DOWN)
,11-08 17:41:16.170   928  2885 D WifiNative-HAL: HAL event thread stopped successfully
,11-08 17:41:16.365  5499  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:16.365  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:16.365  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:16.365  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:41:16.365  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:16.365  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:16.365  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:16.365  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:16.370  5499  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:16.373   928  3102 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-08 17:41:16.373   928  3102 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 17:41:16.374  5499  5545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:16.377   928   945 D Tethering: InitialState.processMessage what=4
,11-08 17:41:16.377   508   922 D SoftapController: Softap fwReload - Ok
,11-08 17:41:16.381   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-08 17:41:16.382   508   922 D CommandListener: Setting iface cfg
11-08 17:41:16.382   508   922 D CommandListener: Trying to bring down wlan0
,11-08 17:41:16.383   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-08 17:41:16.389   928  2885 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 17:41:16.877   928   938 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-08 17:41:16.880   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:41:16.996   928  2885 D wifi    : set interface wlan0 flags (UP)
,11-08 17:41:16.996   928  2885 I WifiHAL : Initializing wifi
,11-08 17:41:16.997   928  2885 I WifiHAL : Creating socket
,11-08 17:41:17.001   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-08 17:41:17.010   928  2885 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-08 17:41:17.010   928  2885 D wifi    : Did set static halHandle = 0x7f6ab48400
11-08 17:41:17.010   928  2885 D wifi    : halHandle = 0x7f6ab48400, mVM = 0x7f8714d140, mCls = 0x101916
11-08 17:41:17.011   928  2885 D wifi    : array field set
11-08 17:41:17.011   928  2885 I WifiNative-HAL: interface[0] = wlan0
11-08 17:41:17.012   928  5806 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547251061760
,11-08 17:41:17.013   928  5806 D wifi    : waitForHalEvents called, vm = 0x7f8714d140, obj = 0x101916, env = 0x7f6b3ba900
,11-08 17:41:17.073  5807  5807 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-08 17:41:17.113   928  2885 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-08 17:41:17.123  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:17.125  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:41:17.141  5807  5807 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 17:41:17.171  5807  5807 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 17:41:17.171  5807  5807 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-08 17:41:17.176   554   554 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-08 17:41:17.176   554   554 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-08 17:41:17.184   928  2885 D WifiConfigStore: Loading config and enabling all networks 
,11-08 17:41:17.193  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:17.193  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:17.193  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:17.193  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:17.193  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:17.193  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:17.193  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:17.193  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:17.197  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:17.199   928  2885 D WifiConfigStore: loaded 0 passpoint configs
11-08 17:41:17.200   928  2885 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-08 17:41:17.200   928  2885 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-08 17:41:17.201   928  2885 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-08 17:41:17.201   928  2885 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-08 17:41:17.201   928  2885 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-08 17:41:17.202   928  2885 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-08 17:41:17.202   928  2885 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-08 17:41:17.202   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-08 17:41:17.202   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-08 17:41:17.202   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-08 17:41:17.202   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-08 17:41:17.202   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-08 17:41:17.204  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:17.204  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:17.204  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:17.204  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:17.204  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:17.204  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:17.204  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:17.204  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:17.204   928  2885 D WifiNative-HAL: Setting external_sim to 1
11-08 17:41:17.205   928  2885 D wifi    : setting dfs flag to true, 0x7f6b9f90c0
11-08 17:41:17.205  4424  4424 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 17:41:17.205   928  2885 D WifiStateMachine: Setting OUI to DA-A1-19
11-08 17:41:17.205   928  2885 D wifi    : setting scan oui 0x7f6b9f90c0
11-08 17:41:17.205   928  2885 D WifiHAL : Sending mac address OUI
,11-08 17:41:17.207  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:17.208   928  2885 E native  : do suspend false
,11-08 17:41:17.214   928  2885 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-08 17:41:17.214   928   928 D RttService: SCAN_AVAILABLE : 3
,11-08 17:41:17.214   928  2994 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 17:41:17.219   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-08 17:41:17.221   508   922 D CommandListener: Setting iface cfg
,11-08 17:41:17.222   928  2883 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
,11-08 17:41:17.222   928  2883 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-08 17:41:17.229   928  2883 D WifiNative-HAL: p2pGetDeviceAddress
,11-08 17:41:17.230   928  2883 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-08 17:41:17.235   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=113888 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-08 17:41:17.391  5499  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:17.391  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:17.391  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:17.391  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:17.391  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:17.391  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:17.391  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:17.391  5499  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:17.396  5499  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:41:17.399  5499  5545 D BluetoothAdapter: enable(): BT is already enabled..!
,11-08 17:41:17.400   928  3701 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-08 17:41:17.400   928  3701 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:41:17.403  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-08 17:41:17.403  5499  5545 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 17:41:17.404  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 17:41:17.404  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-08 17:41:17.404  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-08 17:41:17.404  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42ca6a5 removed from the list
11-08 17:41:17.404  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-08 17:41:17.404  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a676a7a removed from the list
11-08 17:41:17.405  5499  5545 D io.jxcore.node.ConnectivityMonitor: stop
11-08 17:41:17.405  5499  5545 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 17:41:17.405  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 17:41:17.408  5499  5545 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-08 17:41:17.410  5499  5545 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-08 17:41:17.412  5499  5545 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-08 17:41:17.414  5499  5545 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-08 17:41:17.417  5499  5545 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-08 17:41:17.417  5499  5545 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-08 17:41:17.418  5499  5545 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-08 17:41:17.419  5499  5545 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-08 17:41:17.419  5499  5545 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-08 17:41:17.423  5499  5545 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-08 17:41:17.423  5499  5545 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@15f2d60 Bundle[{}]
,11-08 17:41:17.424  5499  5545 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-08 17:41:17.424  5499  5545 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-08 17:41:17.425  5499  5545 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-08 17:41:17.426  5499  5545 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-08 17:41:17.426  5499  5545 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-08 17:41:17.427  5499  5545 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,11-08 17:41:17.427  5499  5545 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-08 17:41:17.428  5499  5545 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,11-08 17:41:17.428  5499  5545 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-08 17:41:17.429  5499  5545 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-08 17:41:17.430  5499  5545 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-08 17:41:17.432  5499  5545 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-08 17:41:17.434  5499  5545 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-08 17:41:17.436  5499  5545 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-08 17:41:17.437  5499  5545 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-08 17:41:17.438  5499  5545 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-08 17:41:17.439  5499  5545 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-08 17:41:17.440  5499  5545 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-08 17:41:17.442  5499  5545 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-08 17:41:17.443  5499  5545 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-08 17:41:17.445  5499  5545 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-08 17:41:17.446  5499  5545 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-08 17:41:17.446  5499  5545 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-08 17:41:17.446  5499  5545 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
11-08 17:41:17.447  5499  5545 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-08 17:41:17.447  5499  5545 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-08 17:41:17.448  5499  5545 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
,11-08 17:41:17.448  5499  5545 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-08 17:41:17.449  5499  5545 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-08 17:41:17.450  5499  5545 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-08 17:41:17.451  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-08 17:41:17.451  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e60821 added. We now have 3 listener(s)
,11-08 17:41:17.453  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 17:41:17.453  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 17:41:17.453  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 17:41:17.453  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 17:41:17.453  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff1b446 added. We now have 3 listener(s)
11-08 17:41:17.453  5499  5545 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 17:41:17.454  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 17:41:17.457  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:41:17.461  5499  5545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:41:17.461  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:17.461  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:17.461  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:17.461  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:17.461  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:41:17.461  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:41:17.461  5499  5545 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:41:17.463  5499  5545 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:41:17.463  5499  5545 D io.jxcore.node.ConnectivityMonitor: start: OK
11-08 17:41:17.466  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:17.466  5499  5545 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-08 17:41:17.467  5499  5545 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-08 17:41:17.467  5499  5545 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-08 17:41:17.467  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-08 17:41:17.467  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:41:17.467  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-08 17:41:17.467  5499  5545 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 17:41:17.468  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:41:17.468  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:41:17.469  5776  5776 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33908]" dev="sockfs" ino=33908 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 17:41:17.469  5776  5776 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33908]" dev="sockfs" ino=33908 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:41:17.469  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 17:41:17.469  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 17:41:17.469  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 17:41:17.469  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 17:41:17.469  5499  5809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 17:41:17.470  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 17:41:17.470  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:41:17.470  5499  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:41:17.470  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-08 17:41:17.470  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:41:17.470  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 17:41:17.472  5499  5809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-08 17:41:17.477  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 17:41:17.478  5499  5545 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:41:17.478  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-08 17:41:17.481  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 17:41:17.482  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-08 17:41:17.482  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 17:41:17.484  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:17.484  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:41:17.484  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:41:17.484  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-08 17:41:17.485  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:41:17.485  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.485  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.485  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.485  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.485  5499  5545 D BluetoothAdapter: STATE_ON
,11-08 17:41:17.488  5740  5750 D BtGatt.GattService: registerClient() - UUID=4e97bbdf-89d7-4a33-b950-04540b3086da
,11-08 17:41:17.489  5740  5756 D BtGatt.GattService: onClientRegistered() - UUID=4e97bbdf-89d7-4a33-b950-04540b3086da, clientIf=5
,11-08 17:41:17.490  5499  5510 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 17:41:17.492  5740  5758 D BtGatt.AdvertiseManager: message : 0
,11-08 17:41:17.494  5740  5758 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:41:17.505  5740  5756 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:41:17.511  5740  5756 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:41:17.512  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.512  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.512  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-08 17:41:17.512  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.512  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.512  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.512  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.512  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.512  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-08 17:41:17.513  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-08 17:41:17.514  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.515  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.515  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.515  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:17.515  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 17:41:17.515  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-08 17:41:17.515  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:17.515  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:41:17.515  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:41:17.515  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:17.515  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:41:17.515  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:41:17.516  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 17:41:17.516  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:41:17.516  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 17:41:17.516  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 17:41:17.516  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 17:41:17.518  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-08 17:41:17.518  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:41:17.518  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:41:17.518  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:41:17.518  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:41:17.519  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:17.519  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 17:41:18.020  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-08 17:41:18.020  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 17:41:18.020  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 17:41:20.295  5807  5807 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:41:20.301  5807  5807 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:41:20.306  5807  5807 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:41:20.310  5807  5807 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:41:20.354   928  2885 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-08 17:41:20.355   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-08 17:41:20.355   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:41:20.369   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-08 17:41:20.403   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-08 17:41:20.410  5807  5807 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-08 17:41:20.836  5807  5807 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-08 17:41:20.868  5807  5807 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-08 17:41:20.869  5807  5807 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
11-08 17:41:20.877   928  2885 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 17:41:20.877   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-08 17:41:20.877   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-08 17:41:20.897   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:41:20.911   508   922 D CommandListener: Setting iface cfg
,11-08 17:41:20.917   928  2885 D WifiStateMachine: Start Dhcp Watchdog 3
,11-08 17:41:20.923   928  5814 D DhcpClient: Receive thread started
,11-08 17:41:20.928   928  2887 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-08 17:41:20.928   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-08 17:41:20.928   928  2887 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-08 17:41:21.009   928  2885 E native  : do suspend false
,11-08 17:41:21.017  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-08 17:41:21.018  5499  5545 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-08 17:41:21.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 17:41:21.018  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 17:41:21.018  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 17:41:21.019  5499  5809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 17:41:21.019  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-08 17:41:21.019  5499  5809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 17:41:21.019  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 17:41:21.019  5499  5809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 17:41:21.019  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 17:41:21.019  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-08 17:41:21.020  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 17:41:21.020  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 17:41:21.020  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 17:41:21.020  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 17:41:21.020  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-08 17:41:21.020  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 17:41:21.020  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.021  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.023  5499  5545 D BluetoothAdapter: STATE_ON
11-08 17:41:21.023  5499  5545 D BluetoothLeScanner: could not find callback wrapper
,11-08 17:41:21.023  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 17:41:21.024  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.024  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.024  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 17:41:21.024  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:21.025   928  5813 D DhcpClient: Broadcasting DHCPDISCOVER
11-08 17:41:21.028  5740  5758 D BtGatt.AdvertiseManager: message : 1
11-08 17:41:21.030  5740  5758 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 17:41:21.037   928  5814 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172791, domain null
,11-08 17:41:21.038   928  5813 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172791 seconds
11-08 17:41:21.040   928  5813 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-08 17:41:21.047  5740  5756 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 17:41:21.048  5740  5756 D BtGatt.GattService: Client app is not null!
,11-08 17:41:21.049  5740  5779 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 17:41:21.050  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 17:41:21.050  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.051  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-08 17:41:21.051  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.051  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:21.051  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.051  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 17:41:21.051  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:41:21.051  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.052  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.052  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 17:41:21.052  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.052   928  5814 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-08 17:41:21.053   928  5813 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-08 17:41:21.054  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:21.054  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:41:21.054  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.055  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.055  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.055  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.055  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.055  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-08 17:41:21.055  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 17:41:21.055   508   922 D CommandListener: Setting iface cfg
11-08 17:41:21.056  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 17:41:21.056  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.058   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-08 17:41:21.061  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:21.061  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.061  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.062  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 17:41:21.062  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 17:41:21.062  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:21.062  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:21.062  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 17:41:21.066  5499  5545 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-08 17:41:21.066  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 17:41:21.067   928  2887 D ConnectivityService: handlePromptUnvalidated 101
11-08 17:41:21.068  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 17:41:21.068  5499  5545 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-08 17:41:21.068  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-08 17:41:21.068  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:41:21.068   928  5813 D DhcpClient: Scheduling renewal in 86399s
,11-08 17:41:21.068  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 17:41:21.073  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:41:21.073  5499  5545 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:41:21.073  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 17:41:21.074   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-08 17:41:21.075   928  2885 D WifiConfigStore: No blacklist allowed without epno enabled
,11-08 17:41:21.076   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-08 17:41:21.076   928  2885 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-08 17:41:21.080  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 17:41:21.080   928  2887 D ConnectivityService: Adding iface wlan0 to network 102
,11-08 17:41:21.081  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:41:21.081  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 17:41:21.089  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:21.089  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-08 17:41:21.089  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-08 17:41:21.089  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-08 17:41:21.090  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-08 17:41:21.091  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.092  5499  5545 D BluetoothAdapter: STATE_ON
11-08 17:41:21.095  5740  5776 D BtGatt.GattService: registerClient() - UUID=24743b04-72fd-4979-9b6e-b60ef074f413
11-08 17:41:21.096  5740  5756 D BtGatt.GattService: onClientRegistered() - UUID=24743b04-72fd-4979-9b6e-b60ef074f413, clientIf=5
11-08 17:41:21.096  5499  5510 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-08 17:41:21.098  5740  5751 D BtGatt.GattService: start scan with filters
,11-08 17:41:21.105  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-08 17:41:21.106  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.106  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-08 17:41:21.106  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:21.106  5740  5759 D BtGatt.ScanManager: handling starting scan
11-08 17:41:21.107  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.107  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-08 17:41:21.107  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 17:41:21.107  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.107  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:21.107  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-08 17:41:21.107  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.108  5740  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b3a5f4
,11-08 17:41:21.110  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.110  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-08 17:41:21.110  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.110  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.110  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-08 17:41:21.110  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.110  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 17:41:21.111  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:41:21.112  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:21.114  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:21.115  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.115  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:21.115  5740  5756 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-08 17:41:21.116  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 17:41:21.116  5740  5759 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-08 17:41:21.119   928  2887 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-08 17:41:21.119   928  2887 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-08 17:41:21.121   928  2887 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-08 17:41:21.123  5740  5756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-08 17:41:21.123   928  2887 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
11-08 17:41:21.123  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:21.123  5740  5759 D BtGatt.ScanManager: Starting BLE batch scan
11-08 17:41:21.124  5740  5759 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-08 17:41:21.124   928  2887 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-08 17:41:21.129   928  2887 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-08 17:41:21.134  5740  5756 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-08 17:41:21.134  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:21.136   928  2887 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-08 17:41:21.136   928  2887 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-08 17:41:21.136   928  2887 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-08 17:41:21.136   928  2885 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-08 17:41:21.136   928  2887 D ConnectivityService:    accepting network in place of null
11-08 17:41:21.137   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 17:41:21.137   928  2887 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 17:41:21.140  5740  5756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-08 17:41:21.140  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 17:41:21.157   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 17:41:21.176   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 17:41:21.178   928  2887 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-08 17:41:21.178  3628  3765 W QCNEJ   : |CORE| network available: 102
11-08 17:41:21.178   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-08 17:41:21.179   928  2887 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-08 17:41:21.180   928   945 D Tethering: MasterInitialState.processMessage what=3
11-08 17:41:21.180  3628  3765 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-08 17:41:21.183  3628  3765 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-08 17:41:21.183  3628  3765 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-08 17:41:21.189  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:21.189  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:21.189  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:21.189  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:21.189  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:21.189  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:21.189  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:21.189  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:41:21.192  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:41:21.195  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:21.195  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:21.195  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:21.195  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:21.195  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:21.195  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:21.195  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:21.195  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:41:21.197  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:41:21.200  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:41:21.200  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:41:21.200  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:41:21.200  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:41:21.200  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:41:21.200  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:21.200  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:41:21.200  5499  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:41:21.202  5499  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:41:21.202  3870  3870 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-08 17:41:21.204  3964  3964 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-08 17:41:21.207  3964  3964 D SystemUpdateService: onCreate
,11-08 17:41:21.211  3964  3964 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-08 17:41:21.212   928  5812 D NetlinkSocketObserver: NeighborEvent{elapsedMs=117865, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-08 17:41:21.221  3964  3964 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-08 17:41:21.226  3964  4196 I iu.UploadsManager: num queued entries: 0
,11-08 17:41:21.226  3964  4196 I iu.UploadsManager: num updated entries: 0
,11-08 17:41:21.230  3964  5826 I SystemUpdateService: active receiver: enabled
,11-08 17:41:21.232  3964  3964 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 17:41:21.234  3964  3964 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 17:41:21.236  5294  5294 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 17:41:21.240  5294  5294 D SprintDMHelper: simOperator: 
,11-08 17:41:21.240  5294  5294 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 17:41:21.249  3964  4196 I iu.SyncManager: NEXT; no task
,11-08 17:41:21.250  3964  5826 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 17:41:21.264  3964  5826 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-08 17:41:21.264  3964  5826 I SystemUpdateService: now status is 0 (complete)
11-08 17:41:21.264  3964  5826 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-08 17:41:21.264  3964  5826 I SystemUpdateService: file has been verified
11-08 17:41:21.264  3964  5826 I SystemUpdateService: OTA package size = 21989297
,11-08 17:41:21.269  3964  5826 I SystemUpdateService: showing system update notification
,11-08 17:41:21.276   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 17:41:21.278  3964  3964 D SystemUpdateService: onDestroy
,11-08 17:41:21.387   928  5811 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-08 17:41:21.462   928  5811 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 08 Nov 2016 16:41:21 GMT], X-Android-Received-Millis=[1478623281460], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478623281414]}
,11-08 17:41:21.464   928  2887 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-08 17:41:21.464   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-08 17:41:21.465   928  2887 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-08 17:41:21.468   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-08 17:41:21.610  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-08 17:41:21.610  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 17:41:21.611  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 17:41:21.644  5740  5740 D BtGatt.ScanManager: awakened up at time 118297
,11-08 17:41:21.646  5740  5759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-08 17:41:21.675  5740  5756 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-08 17:41:21.675  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:21.675  5740  5756 D BtGatt.GattService: current time is 118329070633
11-08 17:41:21.676  5740  5756 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
,11-08 17:41:21.679  5740  5756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,11-08 17:41:21.685  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
,11-08 17:41:21.685  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 17:41:21.686  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=117979817091}
,11-08 17:41:22.178   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:22.179  5740  5740 D BtGatt.ScanManager: awakened up at time 118832
11-08 17:41:22.180   928  2887 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,11-08 17:41:22.181  5740  5759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-08 17:41:22.204  5740  5756 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-08 17:41:22.204  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:22.204  5740  5756 D BtGatt.GattService: current time is 118857836571
11-08 17:41:22.204  5740  5756 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-08 17:41:22.205  5740  5756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,11-08 17:41:22.205  5740  5756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-08 17:41:22.207  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
11-08 17:41:22.207  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 17:41:22.207  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-85, mTimestampNanos=118808284019}
,11-08 17:41:22.209  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 17:41:22.209  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=118608284019}
,11-08 17:41:23.179   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:23.945   928  2887 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-08 17:41:24.117  5499  5545 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-08 17:41:24.118  5499  5545 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-08 17:41:24.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-08 17:41:24.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 17:41:24.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 17:41:24.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 17:41:24.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-08 17:41:24.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 17:41:24.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 17:41:24.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 17:41:24.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 17:41:24.118  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-08 17:41:24.119  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 17:41:24.119  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:41:24.121  5499  5545 D BluetoothAdapter: STATE_ON
11-08 17:41:24.123  5740  5751 D BtGatt.GattService: stopScan() - queue size =1
,11-08 17:41:24.126  5740  5779 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:41:24.127  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 17:41:24.127  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.127  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-08 17:41:24.128  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:41:24.128  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.128  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-08 17:41:24.128  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-08 17:41:24.128  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-08 17:41:24.129  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-08 17:41:24.129  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.131  5499  5545 D BluetoothAdapter: STATE_ON
,11-08 17:41:24.136  5740  5740 D BtGatt.ScanManager: awakened up at time 120789
11-08 17:41:24.138  5740  5779 D BtGatt.GattService: registerClient() - UUID=295cbfff-b55e-4acb-9677-fc5973acd28f
11-08 17:41:24.139  5740  5756 D BtGatt.GattService: onClientRegistered() - UUID=295cbfff-b55e-4acb-9677-fc5973acd28f, clientIf=5
11-08 17:41:24.140  5499  5509 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-08 17:41:24.140  5740  5750 D BtGatt.GattService: start scan with filters
11-08 17:41:24.141  5740  5756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-08 17:41:24.142  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:24.142  5740  5759 D BtGatt.ScanManager: stopping BLe Batch
11-08 17:41:24.143   928  2885 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 11 -> obsolete
,11-08 17:41:24.145  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-08 17:41:24.146  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.146  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-08 17:41:24.146  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.146  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.146  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-08 17:41:24.147  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-08 17:41:24.147  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.147  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.147  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 17:41:24.147  5499  5545 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-08 17:41:24.147  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:41:24.147  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:41:24.149  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 17:41:24.149  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 17:41:24.149  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-08 17:41:24.149  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-08 17:41:24.150  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 17:41:24.150  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:41:24.150  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-08 17:41:24.151  5499  5834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 17:41:24.151  5740  5756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-08 17:41:24.151  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:24.151  5740  5759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-08 17:41:24.152  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:41:24.152  5499  5834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:41:24.152  5499  5545 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:41:24.156  5499  5834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 17:41:24.152  5751  5751 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32759]" dev="sockfs" ino=32759 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:41:24.152  5751  5751 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[32759]" dev="sockfs" ino=32759 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:41:24.162  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.162  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.162  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:41:24.162  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 17:41:24.162  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-08 17:41:24.162  5499  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:41:24.162  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.163  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.163  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.163  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.164  5499  5545 D BluetoothAdapter: STATE_ON
11-08 17:41:24.167  5740  5756 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-08 17:41:24.167  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:24.167  5740  5756 D BtGatt.GattService: current time is 120820564996
,11-08 17:41:24.167  5740  5750 D BtGatt.GattService: registerClient() - UUID=94193151-6716-4542-93f5-b1d482c6649f
11-08 17:41:24.167  5740  5756 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
11-08 17:41:24.167  5740  5756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-08 17:41:24.167  5740  5756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
11-08 17:41:24.170  5740  5759 D BtGatt.ScanManager: handling starting scan
11-08 17:41:24.170  5740  5756 D BtGatt.GattService: onClientRegistered() - UUID=94193151-6716-4542-93f5-b1d482c6649f, clientIf=6
11-08 17:41:24.170  5499  5510 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-08 17:41:24.171  5740  5758 D BtGatt.AdvertiseManager: message : 0
,11-08 17:41:24.177  5740  5758 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:41:24.178  5740  5756 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-08 17:41:24.178  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:24.178  5740  5759 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-08 17:41:24.179   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:24.194  5740  5756 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-08 17:41:24.196  5740  5756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-08 17:41:24.196  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:24.197  5740  5759 D BtGatt.ScanManager: Starting BLE batch scan
11-08 17:41:24.197  5740  5759 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-08 17:41:24.202  5740  5756 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
11-08 17:41:24.203  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:24.203  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.203  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-08 17:41:24.203  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.203  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.203  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.203  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.203  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.203  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.203  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.203  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.203  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-08 17:41:24.203  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-08 17:41:24.204  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 17:41:24.205  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:41:24.205  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:24.208  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.208  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.208  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:24.208  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 17:41:24.208  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:41:24.208  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:24.208  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:41:24.209  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:41:24.209  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:24.209  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:41:24.209  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-08 17:41:24.209  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-08 17:41:24.209  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:41:24.209  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 17:41:24.209  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-08 17:41:24.209  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 17:41:24.212  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:41:24.212  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-08 17:41:24.213  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:41:24.213  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:41:24.213  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:41:24.213  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:41:24.213  5740  5756 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-08 17:41:24.213  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-08 17:41:24.213  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 17:41:24.218  5740  5756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-08 17:41:24.218  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 17:41:24.354   928  2885 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 11 -> obsolete
,11-08 17:41:24.713  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
11-08 17:41:24.714  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-08 17:41:24.714  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 17:41:25.194   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:26.195   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:26.971   928  2887 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-08 17:41:27.195   554   554 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-08 17:41:27.212  5499  5545 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-08 17:41:27.212  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-08 17:41:27.212  5499  5545 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 17:41:27.212  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-08 17:41:27.213  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-08 17:41:27.213  5499  5834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 17:41:27.213  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 17:41:27.213  5499  5834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 17:41:27.213  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 17:41:27.214  5499  5834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 17:41:27.214  5499  5545 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 17:41:27.214  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-08 17:41:27.214  5499  5545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e60821 removed from the list
11-08 17:41:27.214  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 17:41:27.215  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-08 17:41:27.215  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 17:41:27.215  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-08 17:41:27.214  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 17:41:27.215  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 17:41:27.216  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:27.216  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:27.216  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 17:41:27.216  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-08 17:41:27.220  5499  5545 D BluetoothAdapter: STATE_ON
,11-08 17:41:27.222  5740  5768 D BtGatt.GattService: stopScan() - queue size =1
11-08 17:41:27.224  5740  5779 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 17:41:27.225  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 17:41:27.225  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.225  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-08 17:41:27.226  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.226  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.226  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:41:27.226  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-08 17:41:27.226  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.227  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.227  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-08 17:41:27.227  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:27.231  5740  5740 D BtGatt.ScanManager: awakened up at time 123884
,11-08 17:41:27.234  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.234  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 17:41:27.234  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.235  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.235  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.235  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.235  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 17:41:27.235  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.236  5740  5758 D BtGatt.AdvertiseManager: message : 1
,11-08 17:41:27.237  5740  5758 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-08 17:41:27.238  5740  5756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-08 17:41:27.239  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:27.239  5740  5759 D BtGatt.ScanManager: stopping BLe Batch
,11-08 17:41:27.246  5740  5756 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-08 17:41:27.246  5740  5756 D BtGatt.GattService: Client app is not null!
,11-08 17:41:27.247  5740  5768 D BtGatt.GattService: unregisterClient() - clientIf=6
11-08 17:41:27.247  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 17:41:27.247  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.247  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:41:27.247  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.247  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:27.248  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.248  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 17:41:27.248  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:41:27.248  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.248  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.248  5499  5545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 17:41:27.248  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.250  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.250  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:41:27.250  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:27.250  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.250  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.250  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.250  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.251  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 17:41:27.251  5499  5545 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-08 17:41:27.252  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 17:41:27.252  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:27.254  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 17:41:27.254  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.254  5499  5545 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 17:41:27.254  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:27.254  5499  5545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff1b446 removed from the list
11-08 17:41:27.254  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:41:27.254  5499  5545 D io.jxcore.node.ConnectivityMonitor: stop
11-08 17:41:27.254  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:41:27.254  5499  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 17:41:27.254  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:41:27.256  5499  5545 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,11-08 17:41:27.256  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-08 17:41:27.256  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 17:41:27.256  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 17:41:27.256  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 17:41:27.256  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-08 17:41:27.256  5499  5545 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-08 17:41:27.257  5499  5545 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-08 17:41:27.258  5499  5545 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-08 17:41:27.259  5499  5545 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,11-08 17:41:27.259  5499  5545 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-08 17:41:27.259  5499  5545 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-08 17:41:27.260  5740  5756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-08 17:41:27.260  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:27.260  5740  5759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-08 17:41:27.260  5499  5545 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-08 17:41:27.261  5499  5545 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-08 17:41:27.262  5499  5545 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-08 17:41:27.275  5740  5756 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-08 17:41:27.275  5740  5756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:41:27.275  5740  5756 D BtGatt.GattService: current time is 123929015462
11-08 17:41:27.275  5740  5756 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -89, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-08 17:41:27.276  5740  5756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-08 17:41:27.276  5740  5756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-08 17:41:27.276  5740  5756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-08 17:41:27.276  5740  5756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-08 17:41:27.755  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 17:41:29.139   928  2887 D ConnectivityService: handlePromptUnvalidated 102
,11-08 17:41:29.266  5499  5545 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-08 17:41:29.440  5499  5836 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 17:41:29.440  5499  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:41:29.985   928  2887 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-08 17:41:30.317  5499  5836 W !!      : call onHalfStreamCopied
,11-08 17:41:30.317  5499  5836 I testCopyDataAndClose: closing input stream
,11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 17:41:31.093  5499  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-08 17:41:32.197   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:32.238   928  2885 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-08 17:41:33.049   928  2885 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,11-08 17:41:33.198   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:34.199   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:35.200   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:35.355  5499  5545 I StreamCopyingThreadTest: Starting test: testRun
,11-08 17:41:35.362  5499  5837 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:41:35.362  5499  5837 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:41:36.202   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:37.203   554   554 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-08 17:41:39.792  3559  3750 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-08 17:41:39.792  3559  3750 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-08 17:41:39.826  3487  3487 I ConfigService: onCreate
,11-08 17:41:40.370  5499  5838 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-08 17:41:40.372  5499  5545 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-08 17:41:40.523  5499  5840 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 17:41:40.523  5499  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 17:41:42.167  5499  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-08 17:41:44.861  3487  3487 I ConfigService: onDestroy
,11-08 17:41:46.397  5499  5545 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-08 17:41:46.399  5499  5841 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:41:46.399  5499  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 17:41:46.399  5499  5841 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:41:46.399  5499  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:41:46.400  5499  5841 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 17:41:46.400  5499  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 17:41:46.400  5499  5841 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 17:41:46.400  5499  5841 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 17:41:46.400  5499  5841 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 17:41:46.400  5499  5841 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-08 17:41:46.401  5499  5841 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 17:41:46.401  5499  5841 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:41:46.401  5499  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-08 17:41:46.402  5499  5545 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-08 17:41:46.403  5499  5545 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-08 17:41:46.403  5499  5545 I StreamCopyingThreadTest: Starting test: testRunWithException
11-08 17:41:46.405  5499  5842 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:41:46.405  5499  5842 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:41:46.406  5499  5842 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-08 17:41:46.407  5499  5842 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:41:46.407  5499  5842 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-08 17:41:46.407  5499  5842 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-08 17:41:46.407  5499  5842 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:41:46.407  5499  5842 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-08 17:41:46.409  5499  5545 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
,11-08 17:41:46.409  5499  5545 E com.test.thalitest.ThaliTestRunner: 
11-08 17:41:46.409  5499  5545 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-08 17:41:46.409  5499  5545 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRun,ner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-08 17:41:46.410 , 5499  5545 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 17:41:46.410  5499  5545 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner,: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:41:46.411  5499  5545 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 17:41:46.414  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG UnitTest_app: 'Running unit tests'
11-08 17:41:46.414  5499  5545 I jxcore-log: 
11-08 17:41:46.415  5499  5545 I jxcore-log: *Native tests were executed*
11-08 17:41:46.415  5499  5545 I jxcore-log: 
11-08 17:41:46.415  5499  5545 I jxcore-log: Total number of executed tests:  82
11-08 17:41:46.415  5499  5545 I jxcore-log: 
11-08 17:41:46.415  5499  5545 I jxcore-log: Number of passed tests:  80
11-08 17:41:46.415  5499  5545 I jxcore-log: 
11-08 17:41:46.415  5499  5545 I jxcore-log: Number of failed tests:  2
11-08 17:41:46.415  5499  5545 I jxcore-log: 
11-08 17:41:46.415  5499  5545 I jxcore-log: Number of ignored tests:  0
11-08 17:41:46.415  5499  5545 I jxcore-log: 
11-08 17:41:46.415  5499  5545 I jxcore-log: Total duration:  45571
11-08 17:41:46.415  5499  5545 I jxcore-log: 
11-08 17:41:46.415 , 5499  5545 I jxcore-log: Failed to execute UT.
11-08 17:41:46.415  5499  5545 I jxcore-log: 
11-08 17:41:46.416  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-08 17:41:46.416  5499  5545 I jxcore-log: 
11-08 17:41:46.417  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-08 17:41:46.417  5499  5545 I jxcore-log: 
11-08 17:41:46.420  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.420  5499  5545 I jxcore-log: 
11-08 17:41:46.420  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.420  5499  5545 I jxcore-log: 
11-08 17:41:46.421  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.421  5499  5545 I jxcore-log: 
11-08 17:41:46.422  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.422  5499  5545 I jxcore-log: 
11-08 17:41:46.423  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.423  5499  5545 I jxcore-log: 
11-08 17:41:46.423  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.423  5499  5545 I jxcore-log: 
,11-08 17:41:46.423  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 17:41:46.423  5499  5545 I jxcore-log: 
11-08 17:41:46.423  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 17:41:46.423  5499  5545 I jxcore-log: 
,11-08 17:41:46.424  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 17:41:46.424  5499  5545 I jxcore-log: 
11-08 17:41:46.424  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 17:41:46.424  5499  5545 I jxcore-log: 
,11-08 17:41:46.424  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.424  5499  5545 I jxcore-log: 
11-08 17:41:46.424  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.424  5499  5545 I jxcore-log: 
11-08 17:41:46.425  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.425  5499  5545 I jxcore-log: 
,11-08 17:41:46.425  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.425  5499  5545 I jxcore-log: 
11-08 17:41:46.425  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:41:46.425  5499  5545 I jxcore-log: 
11-08 17:41:46.425  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.425  5499  5545 I jxcore-log: 
,11-08 17:41:46.425  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:41:46.425  5499  5545 I jxcore-log: 
11-08 17:41:46.426  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.426  5499  5545 I jxcore-log: 
11-08 17:41:46.426  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:41:46.426  5499  5545 I jxcore-log: 
,11-08 17:41:46.426  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.426  5499  5545 I jxcore-log: 
11-08 17:41:46.426  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 17:41:46.426  5499  5545 I jxcore-log: 
11-08 17:41:46.427  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.427  5499  5545 I jxcore-log: 
11-08 17:41:46.427  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.427  5499  5545 I jxcore-log: 
11-08 17:41:46.427  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.427  5499  5545 I jxcore-log: 
11-08 17:41:46.427  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.427  5499  5545 I jxcore-log: 
,11-08 17:41:46.427  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.427  5499  5545 I jxcore-log: 
11-08 17:41:46.428  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.428  5499  5545 I jxcore-log: 
11-08 17:41:46.428  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.428  5499  5545 I jxcore-log: 
,11-08 17:41:46.428  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.428  5499  5545 I jxcore-log: 
11-08 17:41:46.429  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.429  5499  5545 I jxcore-log: 
11-08 17:41:46.430  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.430  5499  5545 I jxcore-log: 
,11-08 17:41:46.430  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.430  5499  5545 I jxcore-log: 
11-08 17:41:46.430  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.430  5499  5545 I jxcore-log: 
11-08 17:41:46.430  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.430  5499  5545 I jxcore-log: 
,11-08 17:41:46.431  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.431  5499  5545 I jxcore-log: 
11-08 17:41:46.431  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.431  5499  5545 I jxcore-log: 
11-08 17:41:46.431  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,11-08 17:41:46.431  5499  5545 I jxcore-log: 
11-08 17:41:46.431  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.431  5499  5545 I jxcore-log: 
11-08 17:41:46.431  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.431  5499  5545 I jxcore-log: 
,11-08 17:41:46.432  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.432  5499  5545 I jxcore-log: 
11-08 17:41:46.432  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.432  5499  5545 I jxcore-log: 
11-08 17:41:46.432  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.432  5499  5545 I jxcore-log: 
11-08 17:41:46.432  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.432  5499  5545 I jxcore-log: 
11-08 17:41:46.432  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
,11-08 17:41:46.432  5499  5545 I jxcore-log: 
11-08 17:41:46.432  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.432  5499  5545 I jxcore-log: 
11-08 17:41:46.433  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.433  5499  5545 I jxcore-log: 
,11-08 17:41:46.433  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.433  5499  5545 I jxcore-log: 
11-08 17:41:46.433  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.433  5499  5545 I jxcore-log: 
11-08 17:41:46.433  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.433  5499  5545 I jxcore-log: 
,11-08 17:41:46.433  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.433  5499  5545 I jxcore-log: 
11-08 17:41:46.434  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.434  5499  5545 I jxcore-log: 
11-08 17:41:46.434  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.434  5499  5545 I jxcore-log: 
11-08 17:41:46.434  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).',
11-08 17:41:46.434  5499  5545 I jxcore-log: 
11-08 17:41:46.434  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.434  5499  5545 I jxcore-log: 
11-08 17:41:46.434  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.434  5499  5545 I jxcore-log: 
,11-08 17:41:46.435  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.435  5499  5545 I jxcore-log: 
11-08 17:41:46.435  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.435  5499  5545 I jxcore-log: 
11-08 17:41:46.435  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.435  5499  5545 I jxcore-log: 
11-08 17:41:46.435  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).',
11-08 17:41:46.435  5499  5545 I jxcore-log: 
11-08 17:41:46.435  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:41:46.435  5499  5545 I jxcore-log: 
11-08 17:41:46.435  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.435  5499  5545 I jxcore-log: 
,11-08 17:41:46.436  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:41:46.436  5499  5545 I jxcore-log: 
11-08 17:41:46.436  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.436  5499  5545 I jxcore-log: 
11-08 17:41:46.436  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:41:46.436  5499  5545 I jxcore-log: 
11-08 17:41:46.436  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.436  5499  5545 I jxcore-log: 
,11-08 17:41:46.436  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.436  5499  5545 I jxcore-log: 
11-08 17:41:46.437  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.437  5499  5545 I jxcore-log: 
11-08 17:41:46.437  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.437  5499  5545 I jxcore-log: 
11-08 17:41:46.437  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.437  5499  5545 I jxcore-log: 
,11-08 17:41:46.437  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.437  5499  5545 I jxcore-log: 
11-08 17:41:46.437  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.437  5499  5545 I jxcore-log: 
11-08 17:41:46.438  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:41:46.438  5499  5545 I jxcore-log: ,
11-08 17:41:46.438  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.438  5499  5545 I jxcore-log: 
11-08 17:41:46.438  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 17:41:46.438  5499  5545 I jxcore-log: 
11-08 17:41:46.438  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.438  5499  5545 I jxcore-log: 
,11-08 17:41:46.438  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.438  5499  5545 I jxcore-log: 
11-08 17:41:46.438  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.438  5499  5545 I jxcore-log: 
11-08 17:41:46.438  5499  5499 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-08 17:41:46.439  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.439  5499  5545 I jxcore-log: 
,11-08 17:41:46.439  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:41:46.439  5499  5545 I jxcore-log: 
11-08 17:41:46.439  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:41:46.439  5499  5545 I jxcore-log: 
11-08 17:41:46.439  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-08 17:41:46.439  5499  5545 I jxcore-log: 
11-08 17:41:46.439  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-08 17:41:46.439  5499  5545 I jxcore-log: 
11-08 17:41:46.440  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 17:41:46.440  5499  5545 I jxcore-log: ,
11-08 17:41:46.445  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-08 17:41:46.445  5499  5545 I jxcore-log: 
11-08 17:41:46.445  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - WARN testUtils: 'myNameCallback not set!'
11-08 17:41:46.445  5499  5545 I jxcore-log: 
11-08 17:41:46.446  5499  5545 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-08 17:41:46.447  5499  5545 I jxcore-log: 2016-11-08 16:41:46 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-08 17:41:46.447  5499  5545 I jxcore-log: 
,11-08 17:41:47.204   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:48.207   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:48.446  5499  5545 I jxcore-log: 2016-11-08 16:41:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-08 17:41:48.446  5499  5545 I jxcore-log: 
,11-08 17:41:48.774  5499  5545 I jxcore-log: 2016-11-08 16:41:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-08 17:41:48.774  5499  5545 I jxcore-log: 
,11-08 17:41:48.788  5499  5545 I jxcore-log: 2016-11-08 16:41:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-08 17:41:48.788  5499  5545 I jxcore-log: 
,11-08 17:41:49.208   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:49.858  5499  5545 I jxcore-log: 2016-11-08 16:41:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-08 17:41:49.858  5499  5545 I jxcore-log: 
,11-08 17:41:50.024  5499  5545 I jxcore-log: 2016-11-08 16:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-08 17:41:50.024  5499  5545 I jxcore-log: 
,11-08 17:41:50.029  5499  5545 I jxcore-log: 2016-11-08 16:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-08 17:41:50.029  5499  5545 I jxcore-log: 
,11-08 17:41:50.034  5499  5545 I jxcore-log: 2016-11-08 16:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-08 17:41:50.034  5499  5545 I jxcore-log: 
,11-08 17:41:50.209   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:50.506  5499  5545 I jxcore-log: 2016-11-08 16:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-08 17:41:50.506  5499  5545 I jxcore-log: 
,11-08 17:41:50.548  5499  5545 I jxcore-log: 2016-11-08 16:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-08 17:41:50.548  5499  5545 I jxcore-log: 
,11-08 17:41:50.561  5499  5545 I jxcore-log: 2016-11-08 16:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-08 17:41:50.561  5499  5545 I jxcore-log: 
,11-08 17:41:50.565  5499  5545 I jxcore-log: 2016-11-08 16:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-08 17:41:50.565  5499  5545 I jxcore-log: 
,11-08 17:41:50.843  5499  5545 I jxcore-log: 2016-11-08 16:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-08 17:41:50.843  5499  5545 I jxcore-log: 
,11-08 17:41:50.982  5499  5545 I jxcore-log: 2016-11-08 16:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-08 17:41:50.982  5499  5545 I jxcore-log: 
,11-08 17:41:51.209   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:41:51.348  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-08 17:41:51.348  5499  5545 I jxcore-log: 
,11-08 17:41:51.382  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-08 17:41:51.382  5499  5545 I jxcore-log: 
,11-08 17:41:51.388  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-08 17:41:51.388  5499  5545 I jxcore-log: 
,11-08 17:41:51.393  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-08 17:41:51.393  5499  5545 I jxcore-log: 
,11-08 17:41:51.401  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-08 17:41:51.401  5499  5545 I jxcore-log: 
,11-08 17:41:51.414  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-08 17:41:51.414  5499  5545 I jxcore-log: 
,11-08 17:41:51.419  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-08 17:41:51.419  5499  5545 I jxcore-log: 
,11-08 17:41:51.447  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-08 17:41:51.447  5499  5545 I jxcore-log: 
,11-08 17:41:51.485  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-08 17:41:51.485  5499  5545 I jxcore-log: 
,11-08 17:41:51.492  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-08 17:41:51.492  5499  5545 I jxcore-log: 
,11-08 17:41:51.498  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-08 17:41:51.498  5499  5545 I jxcore-log: 
,11-08 17:41:51.513  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-08 17:41:51.513  5499  5545 I jxcore-log: 
,11-08 17:41:51.517  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-08 17:41:51.517  5499  5545 I jxcore-log: 
,11-08 17:41:51.523  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-08 17:41:51.523  5499  5545 I jxcore-log: 
,11-08 17:41:51.528  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-08 17:41:51.528  5499  5545 I jxcore-log: 
,11-08 17:41:51.541  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-08 17:41:51.541  5499  5545 I jxcore-log: 
,11-08 17:41:51.548  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-08 17:41:51.548  5499  5545 I jxcore-log: 
,11-08 17:41:51.570  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-08 17:41:51.570  5499  5545 I jxcore-log: 
,11-08 17:41:51.580  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-08 17:41:51.580  5499  5545 I jxcore-log: 
,11-08 17:41:51.592  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-08 17:41:51.592  5499  5545 I jxcore-log: 
,11-08 17:41:51.602  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-08 17:41:51.602  5499  5545 I jxcore-log: 
,11-08 17:41:51.614  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-08 17:41:51.614  5499  5545 I jxcore-log: 
,11-08 17:41:51.624  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-08 17:41:51.624  5499  5545 I jxcore-log: 
,11-08 17:41:51.631  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-08 17:41:51.631  5499  5545 I jxcore-log: 
,11-08 17:41:51.636  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-08 17:41:51.636  5499  5545 I jxcore-log: 
,11-08 17:41:51.642  5499  5545 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-08 17:41:51.643  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - INFO testUtils: 'BLE multiple advertisement supported'
11-08 17:41:51.643  5499  5545 I jxcore-log: 
,11-08 17:41:51.707   928  5812 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148360, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-08 17:41:51.719  5499  5545 I jxcore-log: 2016-11-08 16:41:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:51.719  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:51.719  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:51.719  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:51.719  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:51.719  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:51.719  5499  5545 I jxcore-log: 
,11-08 17:41:52.020  5499  5545 I jxcore-log: 2016-11-08 16:41:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:52.020  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:52.020  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:52.020  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:52.020  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:52.020  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:52.020  5499  5545 I jxcore-log: 
,11-08 17:41:52.024  5499  5545 I jxcore-log: 2016-11-08 16:41:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:52.024  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:52.024  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:52.024  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:52.024  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:52.024  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:52.024  5499  5545 I jxcore-log: 
,11-08 17:41:52.210   554   554 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-08 17:41:53.137  5499  5545 I jxcore-log: 2016-11-08 16:41:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:53.137  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:53.137  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:53.137  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:53.137  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:53.137  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:53.137  5499  5545 I jxcore-log: 
,11-08 17:41:53.142  5499  5545 I jxcore-log: 2016-11-08 16:41:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:53.142  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:53.142  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:53.142  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:53.142  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:53.142  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:53.142  5499  5545 I jxcore-log: 
,11-08 17:41:54.030  5499  5545 I jxcore-log: 2016-11-08 16:41:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:54.030  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:54.030  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:54.030  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:54.030  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:54.030  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:54.030  5499  5545 I jxcore-log: 
,11-08 17:41:54.034  5499  5545 I jxcore-log: 2016-11-08 16:41:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:54.034  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:54.034  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:54.034  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:54.034  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:54.034  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:54.034  5499  5545 I jxcore-log: 
,11-08 17:41:55.078  5499  5545 I jxcore-log: 2016-11-08 16:41:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:55.078  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:55.078  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:55.078  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:55.078  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:55.078  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:55.078  5499  5545 I jxcore-log: 
,11-08 17:41:55.087  5499  5545 I jxcore-log: 2016-11-08 16:41:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:55.087  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:55.087  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:55.087  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:55.087  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:55.087  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:55.087  5499  5545 I jxcore-log: 
,11-08 17:41:55.678   928   948 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-08 17:41:55.686   939   939 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32083]" dev="sockfs" ino=32083 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:41:55.686   939   939 W Binder_2: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[32083]" dev="sockfs" ino=32083 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:41:55.691  3559  3559 I Keyboard.Facilitator: onFinishInput()
,11-08 17:41:55.701   928   948 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 17:41:55.701   928   948 I Adreno  : Build Date                       : 12/06/15
11-08 17:41:55.701   928   948 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 17:41:55.701   928   948 I Adreno  : Local Branch                     : mybranch17112971
11-08 17:41:55.701   928   948 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 17:41:55.701   928   948 I Adreno  : Remote Branch                    : NONE
11-08 17:41:55.701   928   948 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 17:41:55.741   382   405 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (225 us)
,11-08 17:41:56.181  5499  5545 I jxcore-log: 2016-11-08 16:41:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:56.181  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:56.181  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:56.181  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:56.181  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:56.181  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:56.181  5499  5545 I jxcore-log: 
,11-08 17:41:56.185  5499  5545 I jxcore-log: 2016-11-08 16:41:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:56.185  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:56.185  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:56.185  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:56.185  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:56.185  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:56.185  5499  5545 I jxcore-log: 
,11-08 17:41:56.458  5499  5499 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-08 17:41:56.458  5499  5499 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-08 17:41:56.490   928   948 I sensors : batch
11-08 17:41:56.491   928   948 V KeyguardServiceDelegate: onScreenTurnedOff()
11-08 17:41:56.494  5499  5499 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@15f2d60 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2af662a, 16908290=android.view.AbsSavedState$1@2af662a}, android:focusedViewId=100}]}]
11-08 17:41:56.495  5499  5499 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-08 17:41:56.495  5499  5499 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-08 17:41:56.495  5499  5499 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-08 17:41:56.496   928   948 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-08 17:41:56.496   928   948 I sensors : activate
,11-08 17:41:56.497   928   946 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,11-08 17:41:56.497   928  2699 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-08 17:41:56.499   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f93503c00
11-08 17:41:56.499   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-08 17:41:56.504   928  2699 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-08 17:41:56.725   508   922 D TetherController: Setting IP forward enable = 1
,11-08 17:41:56.787   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-08 17:41:56.788   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-08 17:41:56.789   928  2997 D SurfaceControl: Excessive delay in setPowerMode(): 291ms
,11-08 17:41:56.792   928   948 I DreamManagerService: Entering dreamland.
11-08 17:41:56.793   928   943 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
11-08 17:41:56.793   928   948 I PowerManagerService: Dozing...
,11-08 17:41:56.809  3693  3693 W Binder_8: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[33025]" dev="sockfs" ino=33025 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:41:56.809  3693  3693 W Binder_8: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[33025]" dev="sockfs" ino=33025 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:41:56.811   928  3701 I sensors : batch
11-08 17:41:56.811   928  3701 I sensors : activate
,11-08 17:41:56.814   928  2699 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-08 17:41:56.816   928  2699 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-08 17:41:56.820   513  2908 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-08 17:41:56.823   928  2885 E native  : do suspend false
,11-08 17:41:56.828   928  2885 D WifiConfigStore: No blacklist allowed without epno enabled
,11-08 17:41:56.838  3668  4663 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-08 17:41:56.838  3668  4663 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-08 17:41:56.839  3668  4663 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-08 17:41:56.839   526  1201 D         : oem-qmi: Connection accepted
11-08 17:41:56.839   526  1201 D         : oem-qmi: Waiting to accept connection
,11-08 17:41:56.840   928   928 I sensors : activate
,11-08 17:41:56.841   513  2909 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
11-08 17:41:56.841  3668  4663 D         : oem_qmi_lib:output 0
11-08 17:41:56.841  3668  4663 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-08 17:41:56.843   928  2699 I hubconnection: sensorhub said: 'activate 31 enable:0'
11-08 17:41:56.843   928  2885 E native  : do suspend true
,11-08 17:41:56.860  3668  4663 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-08 17:41:56.860  3668  4663 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-08 17:41:56.860  3668  4663 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-08 17:41:56.860   526  1201 D         : oem-qmi: Connection accepted
11-08 17:41:56.860   526  1201 D         : oem-qmi: Waiting to accept connection
,11-08 17:41:56.862  3668  4663 D         : oem_qmi_lib:output 0
,11-08 17:41:56.862  3668  4663 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-08 17:41:57.010   928  5812 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-08 17:41:57.215  5499  5545 I jxcore-log: 2016-11-08 16:41:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:57.215  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:57.215  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:57.215  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:57.215  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:57.215  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:57.215  5499  5545 I jxcore-log: 
,11-08 17:41:57.220  5499  5545 I jxcore-log: 2016-11-08 16:41:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:57.220  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:57.220  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:57.220  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:57.220  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:57.220  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:57.220  5499  5545 I jxcore-log: 
,11-08 17:41:57.322   928  2885 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-08 17:41:58.254  5499  5545 I jxcore-log: 2016-11-08 16:41:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:58.254  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:58.254  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:58.254  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:58.254  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:58.254  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:58.254  5499  5545 I jxcore-log: 
,11-08 17:41:58.259  5499  5545 I jxcore-log: 2016-11-08 16:41:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:58.259  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:58.259  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:58.259  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:58.259  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:58.259  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:58.259  5499  5545 I jxcore-log: 
,11-08 17:41:59.290  5499  5545 I jxcore-log: 2016-11-08 16:41:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:59.290  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:59.290  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:59.290  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:59.290  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:59.290  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:59.290  5499  5545 I jxcore-log: 
,11-08 17:41:59.295  5499  5545 I jxcore-log: 2016-11-08 16:41:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:41:59.295  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:41:59.295  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:41:59.295  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:41:59.295  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:41:59.295  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:41:59.295  5499  5545 I jxcore-log: 
,11-08 17:42:00.329  5499  5545 I jxcore-log: 2016-11-08 16:42:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:00.329  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:00.329  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:00.329  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:00.329  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:00.329  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:00.329  5499  5545 I jxcore-log: 
,11-08 17:42:00.335  5499  5545 I jxcore-log: 2016-11-08 16:42:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:00.335  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:00.335  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:00.335  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:00.335  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:00.335  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:00.335  5499  5545 I jxcore-log: 
,11-08 17:42:00.581  3854  4350 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-08 17:42:01.080   928  2885 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,11-08 17:42:01.406  5499  5545 I jxcore-log: 2016-11-08 16:42:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:01.406  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:01.406  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:01.406  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:01.406  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:01.406  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:01.406  5499  5545 I jxcore-log: 
,11-08 17:42:01.411  5499  5545 I jxcore-log: 2016-11-08 16:42:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:01.411  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:01.411  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:01.411  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:01.411  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:01.411  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:01.411  5499  5545 I jxcore-log: 
,11-08 17:42:02.447  5499  5545 I jxcore-log: 2016-11-08 16:42:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:02.447  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:02.447  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:02.447  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:02.447  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:02.447  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:02.447  5499  5545 I jxcore-log: 
,11-08 17:42:02.455  5499  5545 I jxcore-log: 2016-11-08 16:42:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:02.455  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:02.455  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:02.455  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:02.455  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:02.455  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:02.455  5499  5545 I jxcore-log: 
,11-08 17:42:03.485  5499  5545 I jxcore-log: 2016-11-08 16:42:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:03.485  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:03.485  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:03.485  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:03.485  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:03.485  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:03.485  5499  5545 I jxcore-log: 
,11-08 17:42:03.490  5499  5545 I jxcore-log: 2016-11-08 16:42:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:03.490  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:03.490  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:03.490  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:03.490  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:03.490  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:03.490  5499  5545 I jxcore-log: 
,11-08 17:42:04.521  5499  5545 I jxcore-log: 2016-11-08 16:42:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:04.521  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:04.521  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:04.521  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:04.521  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:04.521  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:04.521  5499  5545 I jxcore-log: 
,11-08 17:42:04.525  5499  5545 I jxcore-log: 2016-11-08 16:42:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:04.525  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:04.525  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:04.525  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:04.525  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:04.525  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:04.525  5499  5545 I jxcore-log: 
,11-08 17:42:05.555  5499  5545 I jxcore-log: 2016-11-08 16:42:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:05.555  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:05.555  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:05.555  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:05.555  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:05.555  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:05.555  5499  5545 I jxcore-log: 
,11-08 17:42:05.558  5499  5545 I jxcore-log: 2016-11-08 16:42:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:05.558  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:05.558  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:05.558  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:05.558  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:05.558  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:05.558  5499  5545 I jxcore-log: 
,11-08 17:42:06.592  5499  5545 I jxcore-log: 2016-11-08 16:42:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:42:06.592  5499  5545 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:42:06.592  5499  5545 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:42:06.592  5499  5545 I jxcore-log: emit@events.js:82:1
11-08 17:42:06.592  5499  5545 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:42:06.592  5499  5545 I jxcore-log: emit@events.js:82:1'
11-08 17:42:06.592  5499  5545 I jxcore-log: 
,11-08 17:42:06.604  5499  5545 E jxcore  : Error!: error is undefined
11-08 17:42:06.604  5499  5545 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-08 17:42:06.607  5499  5545 I jxcore-log: 2016-11-08 16:42:06 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-08 17:42:06.607  5499  5545 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-08 17:42:06.607  5499  5545 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-08 17:42:06.607  5499  5545 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-08 17:42:06.607  5499  5545 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-08 17:42:06.607  5499  5545 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-08 17:42:06.607  5499  5545 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-08 17:42:06.607  5499  5545 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-08 17:42:06.609  5499  5545 I jxcore-log: 2016-11-08 16:42:06 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-08 17:42:06.609  5499  5545 I jxcore-log: 
,11-08 17:42:06.611  5499  5545 E jxcore-log: TypeError: 
11-08 17:42:06.612  5499  5545 E jxcore-log: error is undefined
11-08 17:42:06.612  5499  5545 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-08 17:42:06.612  5499  5545 E jxcore-log: 
,11-08 17:42:06.695   928  2886 D WifiService: Client connection lost with reason: 4
11-08 17:42:06.695   928  3701 D GraphicsStats: Buffer count: 2
,11-08 17:42:06.695   928  3060 I WindowState: WIN DEATH: Window{6c5cfe9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-08 17:42:06.719   528   528 I Zygote  : Process 5499 exited cleanly (139)
,11-08 17:42:06.722   928  3102 I ActivityManager: Process com.test.thalitest (pid 5499) has died
,11-08 17:42:06.740   928  3102 I ActivityManager: Start proc 5888:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-08 17:42:06.805  5888  5888 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-08 17:42:06.823  5888  5888 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-08 17:42:06.828  5888  5888 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3480-3481)
,11-08 17:42:06.828  5888  5888 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 17:42:06.837  5888  5888 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {187c75c}
,11-08 17:42:06.838  5888  5888 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-08 17:42:06.838  5888  5888 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-08 17:42:06.841  5888  5888 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-08 17:42:06.842  5888  5888 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-08 17:42:06.854  5888  5888 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-08 17:42:06.862  5888  5888 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-08 17:42:06.862  5888  5888 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 17:42:06.862  5888  5888 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 17:42:06.862  5888  5888 I Adreno  : Build Date                       : 12/06/15
11-08 17:42:06.862  5888  5888 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 17:42:06.862  5888  5888 I Adreno  : Local Branch                     : mybranch17112971
11-08 17:42:06.862  5888  5888 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 17:42:06.862  5888  5888 I Adreno  : Remote Branch                    : NONE
11-08 17:42:06.862  5888  5888 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 17:42:06.892   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@931a3c0:true
,11-08 17:42:06.906  2532  2532 W Binder_4: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[15064]" dev="sockfs" ino=15064 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:42:06.906  2532  2532 W Binder_4: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[15064]" dev="sockfs" ino=15064 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:42:06.916  5888  5888 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-08 17:42:06.924  5888  5888 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-08 17:42:06.946  2532  2532 W Binder_4: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[35892]" dev="sockfs" ino=35892 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:42:06.949  5888  5924 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-08 17:42:06.946  2532  2532 W Binder_4: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[35892]" dev="sockfs" ino=35892 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:42:06.949  3503  3503 W Binder_7: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[14202]" dev="sockfs" ino=14202 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:42:06.949  3503  3503 W Binder_7: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[14202]" dev="sockfs" ino=14202 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:42:06.954  5888  5911 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-08 17:42:06.989  5888  5924 I OpenGLRenderer: Initialized EGL, version 1.4
,11-08 17:42:07.018   928  3060 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5499 uid 10077
11-08 17:42:07.019   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +258ms (total +294ms)
,11-08 17:42:07.016  3060  3060 W Binder_3: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[33044]" dev="sockfs" ino=33044 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:42:07.016  3060  3060 W Binder_3: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[33044]" dev="sockfs" ino=33044 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:42:07.016   938   938 W Binder_1: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[33043]" dev="sockfs" ino=33043 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:42:07.016   938   938 W Binder_1: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[33043]" dev="sockfs" ino=33043 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:42:07.020  3559  3559 I Keyboard.Facilitator: onFinishInput()
,11-08 17:42:07.025  5888  5888 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5888
,11-08 17:42:07.078  5888  5888 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-08 17:42:07.141  5886  5886 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-08 17:42:07.157  5886  5886 D AndroidRuntime: CheckJNI is OFF
,11-08 17:42:07.177  5886  5886 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-08 17:42:07.200  5886  5886 I Radio-JNI: register_android_hardware_Radio DONE
,11-08 17:42:07.211   554   554 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:42:07.215  5886  5886 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-08 17:42:07.218  5888  5925 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -562038480
,11-08 17:42:07.219   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-08 17:42:07.220   928   941 I ActivityManager: Killing 5888:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-08 17:42:07.252   928  3060 D GraphicsStats: Buffer count: 2
,11-08 17:42:07.252   928  3329 I WindowState: WIN DEATH: Window{e5bd8f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-08 17:42:07.314   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-08 17:42:07.314   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-08 17:42:07.315   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-08 17:42:07.315   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-08 17:42:07.315   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:42:07.315   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:42:07.315   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 17:42:07.315   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-08 17:42:07.315   928   941 I ActivityManager:   Force finishing activity ActivityRecord{291d736 u0 com.test.thalitest/.MainActivity t68}
11-08 17:42:07.316   928   951 I art     : Starting a blocking GC Explicit
,11-08 17:42:07.323   928  3328 W ActivityManager: Spurious death for ProcessRecord{89cdc25 0:com.test.thalitest/u0a77}, curProc for 5888: null
,11-08 17:42:07.407   928   951 I art     : Explicit concurrent mark sweep GC freed 16800(1127KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 1.938ms total 89.901ms
,11-08 17:42:07.431   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-08 17:42:07.434  5886  5886 I art     : System.exit called, status: 0
,11-08 17:42:07.435  5886  5886 I AndroidRuntime: VM exiting with result code 0.
,11-08 17:42:07.439   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-08 17:42:07.448   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
11-08 17:42:07.451  5740  5740 D BluetoothMapAppObserver: onReceive
11-08 17:42:07.451  5740  5740 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-08 17:42:07.456  3854  4012 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-08 17:42:07.459  3559  3559 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-08 17:42:07.463   928  2851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-08 17:42:07.487  3311  5942 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-08 17:42:07.489  3559  5940 I Keyboard.Facilitator.DecoderInitializer: run()
,11-08 17:42:07.502  3559  5940 I Decoder : createOrResetDecoder
,11-08 17:42:07.509  3668  3668 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-08 17:42:07.525   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-08 17:42:07.531  3487  3487 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-08 17:42:07.531  3487  3487 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-08 17:42:07.559   414   414 W kworker/3:2: type=1400 audit(0.0:141): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 17:42:07.566   414   414 W kworker/3:2: type=1400 audit(0.0:142): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 17:42:07.579   414   414 W kworker/3:2: type=1400 audit(0.0:143): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 17:42:07.584  3487  3487 I ConfigService: onCreate
,11-08 17:42:07.587  3487  5948 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-08 17:42:07.587  3487  5948 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-08 17:42:07.587  3487  5948 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-08 17:42:07.589  3487  5948 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-08 17:42:07.598  3559  5940 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-08 17:42:07.601  3487  3487 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/ns.db'.
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:42:07.601  3487  3487 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:42:07.602  3487  3487 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-08 17:42:07.602  3487  3487 E AndroidRuntime: FATAL EXCEPTION: main
11-08 17:42:07.602  3487  3487 E AndroidRuntime: Process: com.google.process.gapps, PID: 3487
11-08 17:42:07.602  3487  3487 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-08 17:42:07.60,2  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:42:07.602  3487  3487 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:42:07.608  3487  3487 I Process : Sending signal. PID: 3487 SIG: 9
11-08 17:42:07.609   928  5949 E DropBoxManagerService: Can't write: system_app_crash
11-08 17:42:07.609   928  5949 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 17:42:07.609   928  5949 E DropBoxManagerService: 	... 5 more
11-08 17:42:07.612  3311  5942 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-08 17:42:07.613  3311  5942 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-08 17:42:07.613  3311  5942 E AndroidRuntime: Process: android.process.acore, PID: 3311
11-08 17:42:07.613  3311  5942 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:42:07.613  3311  5942 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: Can't write: system_app_crash
11-08 17:42:07.615   928  5950 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 17:42:07.615   928  5950 E DropBoxManagerService: 	... 5 more
11-08 17:42:07.623  3311  5942 I Process : Sending signal. PID: 3311 SIG: 9
11-08 17:42:07.628  3964  5947 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-08 17:42:07.628  3964  5947 D AccountUtils: Clearing selected account for com.test.thalitest
11-08 17:42:07.638   928  2886 D WifiService: Client connection lost with reason: 4
11-08 17:42:07.639  3559  3559 W GmsClient: service died
,11-08 17:42:07.644   928  3703 I ActivityManager: Process com.google.process.gapps (pid 3487) has died
11-08 17:42:07.644   928  3703 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
11-08 17:42:07.644   928  3703 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
11-08 17:42:07.644   928  3703 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
11-08 17:42:07.644   928  3703 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 30999ms

```
