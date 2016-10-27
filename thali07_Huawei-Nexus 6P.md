#### Test 9111335991ca3b4_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-27 02:39:37.047  3920  4285 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
10-27 02:39:37.127  3920  4285 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,10-27 02:39:37.540  5673  5673 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-27 02:39:37.546  5673  5673 D AndroidRuntime: CheckJNI is OFF
10-27 02:39:37.571  5673  5673 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-27 02:39:37.603  5673  5673 I Radio-JNI: register_android_hardware_Radio DONE
10-27 02:39:37.618  5673  5673 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-27 02:39:37.624   928  3872 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-27 02:39:37.646  5673  5673 D AndroidRuntime: Shutting down VM
10-27 02:39:37.663  4016  5669 W SearchService: Abort, client detached.
10-27 02:39:37.666  4016  4016 I HotwordDetector: Closing mic
10-27 02:39:37.667  4016  4262 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1da4b4e
10-27 02:39:37.667  4016  4278 E AudioRecord-JNI: Error -4 during AudioRecord native read
10-27 02:39:37.680   928   939 I ActivityManager: Start proc 5682:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-27 02:39:37.748   512  4282 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
10-27 02:39:37.750   512  4282 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
10-27 02:39:37.754   512  4282 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
10-27 02:39:37.754   512  4282 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
10-27 02:39:37.754   512  3086 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
10-27 02:39:37.756  4016  4270 I MicroRecognitionRnrImpl: Stopping hotword detection.
10-27 02:39:37.757  4016  4274 I MicroRecognitionRnrImpl: Detection finished
10-27 02:39:37.768  5682  5682 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
10-27 02:39:37.785  5682  5682 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
10-27 02:39:37.843  5682  5682 I LibraryLoader: Time to load native libraries: 54 ms (timestamps 9327-9381)
10-27 02:39:37.844  5682  5682 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-27 02:39:37.885  5682  5682 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ed7ae4}
,10-27 02:39:37.886  5682  5682 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-27 02:39:37.886  5682  5682 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-27 02:39:37.892  5682  5682 I BrowserStartupController: Initializing chromium process, singleProcess=true
10-27 02:39:37.893  5682  5682 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-27 02:39:37.938  5682  5682 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-27 02:39:37.953  5682  5682 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-27 02:39:37.953  5682  5682 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-27 02:39:37.953  5682  5682 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-27 02:39:37.953  5682  5682 I Adreno  : Build Date                       : 12/06/15
10-27 02:39:37.953  5682  5682 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-27 02:39:37.953  5682  5682 I Adreno  : Local Branch                     : mybranch17112971
10-27 02:39:37.953  5682  5682 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-27 02:39:37.953  5682  5682 I Adreno  : Remote Branch                    : NONE
10-27 02:39:37.953  5682  5682 I Adreno  : Reconstruct Branch               : NOTHING
,10-27 02:39:38.004   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ee3378:true
,10-27 02:39:38.041  3025  3025 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[30782]" dev="sockfs" ino=30782 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-27 02:39:38.041  3025  3025 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[30782]" dev="sockfs" ino=30782 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-27 02:39:38.057  5682  5682 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-27 02:39:38.066  5682  5682 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-27 02:39:38.097  3025  3025 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32763]" dev="sockfs" ino=32763 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-27 02:39:38.097  3025  3025 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32763]" dev="sockfs" ino=32763 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-27 02:39:38.099  5682  5719 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-27 02:39:38.101  3287  3287 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30787]" dev="sockfs" ino=30787 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:39:38.101  3287  3287 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30787]" dev="sockfs" ino=30787 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:39:38.105  5682  5706 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-27 02:39:38.142  5682  5719 I OpenGLRenderer: Initialized EGL, version 1.4
,10-27 02:39:38.226   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +562ms
,10-27 02:39:38.228  3734  3734 I Keyboard.Facilitator: onFinishInput()
10-27 02:39:38.224  3287  3287 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28582]" dev="sockfs" ino=28582 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:39:38.224  3287  3287 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[28582]" dev="sockfs" ino=28582 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-27 02:39:38.224   939   939 W Binder_2: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[28581]" dev="sockfs" ino=28581 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-27 02:39:38.224   939   939 W Binder_2: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[28581]" dev="sockfs" ino=28581 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:39:38.260  5682  5682 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5682
,10-27 02:39:38.361  5682  5682 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-27 02:39:38.532  5682  5721 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -583534288
,10-27 02:39:38.537  5682  5721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-27 02:39:38.537  5682  5721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-27 02:39:38.537  5682  5721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-27 02:39:38.537  5682  5721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-27 02:39:38.537  5682  5721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-27 02:39:38.538  5682  5721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f8e94b added. We now have 1 listener(s)
,10-27 02:39:38.542  5682  5721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,10-27 02:39:38.542  5682  5721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:39:38.542  5682  5721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-27 02:39:38.543  5682  5721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-27 02:39:38.545  5682  5721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff32de6 added. We now have 1 listener(s)
10-27 02:39:38.545  5682  5721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-27 02:39:38.550   928  3038 D WifiService: New client listening to asynchronous messages
,10-27 02:39:38.551  5682  5721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-27 02:39:38.551  5682  5721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-27 02:39:38.551  5682  5721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-27 02:39:38.552  5682  5721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-27 02:39:38.552  5682  5721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-27 02:39:38.558  5682  5721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:39:38.558  5682  5721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,10-27 02:39:38.562  5682  5721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-27 02:39:38.562  5682  5721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:39:38.562  5682  5721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:39:38.562  5682  5721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:39:38.562  5682  5721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:39:38.562  5682  5721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:39:38.562  5682  5721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:39:38.562  5682  5721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:39:38.562  5682  5721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:39:38.562  5682  5721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,10-27 02:39:38.562  5682  5721 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-27 02:39:38.563  5682  5721 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-27 02:39:38.700  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:39:38.704  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:39:38.716  5682  5682 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-27 02:39:39.005  5682  5691 I art     : Background sticky concurrent mark sweep GC freed 74620(7MB) AllocSpace objects, 17(1096KB) LOS objects, 24% free, 24MB/32MB, paused 1.422ms total 222.522ms
,10-27 02:39:39.797   928  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-27 02:39:40.166  5682  5729 W jxcore-log: Initializing JXcore engine
10-27 02:39:40.166  5682  5729 W jxcore-log: JXcore engine is ready
,10-27 02:39:40.191  5729  5729 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10639 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-27 02:39:40.191  5729  5729 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[12984]" dev="sockfs" ino=12984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-27 02:39:40.191  5729  5729 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-27 02:39:40.191  5729  5729 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32975]" dev="sockfs" ino=32975 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-27 02:39:40.199  5682  5729 W jxcore-log: Starting JXcore engine
,10-27 02:39:40.248  5682  5729 W jxcore-log: Platform android
10-27 02:39:40.248  5682  5729 W jxcore-log: 
,10-27 02:39:40.248  5682  5729 W jxcore-log: Process ARCH arm
10-27 02:39:40.248  5682  5729 W jxcore-log: 
,10-27 02:39:40.427  5682  5729 I jxcore-log: JXcore Cordova bridge is ready!
10-27 02:39:40.427  5682  5729 I jxcore-log: 
,10-27 02:39:40.427  5682  5729 W jxcore-log: JXcore engine is started
,10-27 02:39:40.436  5682  5721 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-27 02:39:40.440  5682  5682 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-27 02:39:41.184  3638  3638 I ConfigService: onDestroy
,10-27 02:39:41.619   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:39:42.620   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:39:42.676   928   938 I ActivityManager: Killing 5323:org.codeaurora.ims/1001 (adj 15): empty #17
,10-27 02:39:42.714   928   938 I ActivityManager: Killing 5234:com.google.android.youtube/u0a75 (adj 15): empty #18
,10-27 02:39:43.621   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:39:44.621   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:39:45.623   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:39:46.624   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-27 02:39:50.105  5682  5729 I jxcore-log: 2016-10-27 00:39:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-27 02:39:50.105  5682  5729 I jxcore-log: 
,10-27 02:39:50.107  5682  5729 I jxcore-log: 2016-10-27 00:39:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-27 02:39:50.107  5682  5729 I jxcore-log: 
,10-27 02:39:50.111  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:39:50.111  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:39:50.111  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:39:50.111  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:39:50.111  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:39:50.111  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:39:50.111  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:39:50.111  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:39:50.113  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-27 02:39:50.115  5682  5729 I jxcore-log: 2016-10-27 00:39:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-27 02:39:50.115  5682  5729 I jxcore-log: 
10-27 02:39:50.116  5682  5729 I jxcore-log: 2016-10-27 00:39:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-27 02:39:50.116  5682  5729 I jxcore-log: 
,10-27 02:39:50.365  5682  5729 I jxcore-log: 2016-10-27 00:39:50 - DEBUG UnitTest_app: 'Running unit tests'
10-27 02:39:50.365  5682  5729 I jxcore-log: 
10-27 02:39:50.365  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-27 02:39:50.365  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47d6f5a added. We now have 2 listener(s)
,10-27 02:39:50.366  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:39:50.366  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:39:50.366  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-27 02:39:50.366  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:39:50.366  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af2058b added. We now have 2 listener(s)
10-27 02:39:50.366  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-27 02:39:50.367  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-27 02:39:50.369  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-27 02:39:50.371  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:39:50.371  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:39:50.371  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:39:50.371  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:39:50.371  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:39:50.371  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:39:50.371  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:39:50.371  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:39:50.373  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:39:50.373  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
10-27 02:39:50.373  5682  5729 D executeNativeTests: Running unit tests
,10-27 02:39:50.378  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:39:50.383  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:39:50.407  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-27 02:39:50.407  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 added. We now have 3 listener(s)
10-27 02:39:50.408  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-27 02:39:50.408  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-27 02:39:50.408  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-27 02:39:50.408  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-27 02:39:50.408  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 added. We now have 3 listener(s)
10-27 02:39:50.408  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:39:50.409  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-27 02:39:50.410  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:39:50.412  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:39:50.412  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:39:50.412  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:39:50.412  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:39:50.412  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:39:50.412  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:39:50.412  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:39:50.412  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:39:50.414  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:39:50.415  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
10-27 02:39:50.416  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-27 02:39:50.417  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-27 02:39:50.417  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-27 02:39:50.417  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-27 02:39:50.417  5682  5729 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-27 02:39:50.417  5682  5729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-27 02:39:50.418  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-27 02:39:50.418  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-27 02:39:50.418  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-27 02:39:50.418  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-27 02:39:50.418  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:39:50.418  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:39:50.418  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:39:50.419  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:39:50.419  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:39:50.419  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:39:50.419  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:39:50.419  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:39:50.419  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 removed from the list
10-27 02:39:50.419  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:39:50.419  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 removed from the list
,10-27 02:39:50.422  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:39:50.427  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:39:50.428  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:39:50.428  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:39:50.428  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:39:50.428  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:39:50.429  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:39:50.429  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.429  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.429  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.429  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:39:50.429  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:39:50.429  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:39:50.429  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:39:50.430  5682  5729 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,10-27 02:39:50.430  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:39:50.431  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:39:50.431  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:39:50.431  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:39:50.431  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:39:50.431  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:39:50.431  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:39:50.431  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:39:50.431  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:39:50.431  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:39:50.431  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:39:50.431  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:39:50.431  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:39:50.431  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:39:50.431  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:39:50.431  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.432  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.432  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.432  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.432  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:39:50.432  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:39:50.432  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:39:50.432  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-27 02:39:50.434  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,10-27 02:39:50.435  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-27 02:39:50.435  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:39:50.435  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:39:50.435  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:39:50.435  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:39:50.435  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:39:50.435  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:39:50.435  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:39:50.435  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:39:50.435  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:39:50.436  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:39:50.436  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:39:50.436  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:39:50.436  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:39:50.436  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:39:50.436  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:39:50.436  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.436  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.436  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.436  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.436  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:39:50.436  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:39:50.436  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:39:50.437  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:39:50.437  5682  5729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-27 02:39:50.438  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:39:50.441  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:39:50.441  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:39:50.441  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:39:50.441  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:39:50.441  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:39:50.441  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:39:50.441  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:39:50.441  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:39:50.441  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:39:50.442  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
10-27 02:39:50.442  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:39:50.442  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-27 02:39:50.442  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-27 02:39:50.442  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:39:50.442  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-27 02:39:50.444  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-27 02:39:50.444  5682  5729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-27 02:39:50.444  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-27 02:39:50.445  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:39:50.447  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:39:50.447  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-27 02:39:50.448  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-27 02:39:50.448  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-27 02:39:50.450  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-27 02:39:50.451  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-27 02:39:50.451  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.451  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-27 02:39:50.451  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-27 02:39:50.451  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-27 02:39:50.452  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-27 02:39:50.452  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.452  5682  5729 D BluetoothAdapter: STATE_ON
10-27 02:39:50.454  4733  4946 D BtGatt.GattService: registerClient() - UUID=52672e1c-35f9-48c5-a159-eea965d53f68
10-27 02:39:50.455  4733  4796 D BtGatt.GattService: onClientRegistered() - UUID=52672e1c-35f9-48c5-a159-eea965d53f68, clientIf=5
10-27 02:39:50.455  5682  5693 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-27 02:39:50.456  4733  4954 D BtGatt.GattService: start scan with filters
10-27 02:39:50.461  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-27 02:39:50.461  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.461  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-27 02:39:50.461  4733  4801 D BtGatt.ScanManager: handling starting scan
10-27 02:39:50.461  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.461  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.461  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-27 02:39:50.461  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-27 02:39:50.461  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.462  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.462  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-27 02:39:50.462  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.463  4733  4801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
10-27 02:39:50.466  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.466  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:39:50.466  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.466  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.466  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.466  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-27 02:39:50.466  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:39:50.467  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-27 02:39:50.467  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.468  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.468  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.468  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:50.468  5682  5729 I io.jxcore.node.ConnectionHelper: start: OK
10-27 02:39:50.470  4733  4796 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-27 02:39:50.471  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:39:50.471  4733  4801 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-27 02:39:50.477  4733  4796 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-27 02:39:50.477  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:39:50.478  4733  4801 D BtGatt.ScanManager: Starting BLE batch scan
10-27 02:39:50.478  4733  4801 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-27 02:39:50.489  4733  4796 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-27 02:39:50.489  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:39:50.494  4733  4796 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-27 02:39:50.495  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-27 02:39:50.757  4016  5734 W CronetSyncConnectionRcs: Upload content type not set.
,10-27 02:39:50.827  4932  4976 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-27 02:39:50.829  4932  4932 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-27 02:39:50.968  5682  5682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-27 02:39:50.968  5682  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:39:50.968  5682  5682 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-27 02:39:55.472  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-27 02:39:55.473  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-27 02:39:55.473  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-27 02:39:55.473  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:39:55.473  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-27 02:39:55.473  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:39:55.473  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-27 02:39:55.473  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-27 02:39:55.473  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-27 02:39:55.473  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-27 02:39:55.474  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.474  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:39:55.474  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-27 02:39:55.476  5682  5729 D BluetoothAdapter: STATE_ON
10-27 02:39:55.476  4733  4946 D BtGatt.GattService: stopScan() - queue size =1
10-27 02:39:55.477  4733  4954 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-27 02:39:55.478  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-27 02:39:55.478  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.478  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-27 02:39:55.478  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
,10-27 02:39:55.478  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:39:55.478  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-27 02:39:55.478  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-27 02:39:55.479  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:39:55.479  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.479  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-27 02:39:55.479  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.480  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:39:55.480  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:39:55.480  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.480  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.480  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.480  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.481  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.481  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-27 02:39:55.481  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.481  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.481  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.481  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-27 02:39:55.482  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-27 02:39:55.482  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:39:55.482  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.486  4733  4733 D BtGatt.ScanManager: awakened up at time 97024
,10-27 02:39:55.487  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.487  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.487  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:39:55.487  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:39:55.488  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:39:55.488  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:39:55.488  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:39:55.488  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:39:55.488  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:39:55.488  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-27 02:39:55.488  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:39:55.488  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:39:55.488  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:39:55.488  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:39:55.488  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:39:55.492  4733  4796 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-27 02:39:55.492  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:39:55.493  4733  4801 D BtGatt.ScanManager: stopping BLe Batch
10-27 02:39:55.501  4733  4796 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-27 02:39:55.502  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:39:55.502  4733  4801 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-27 02:39:55.523  4733  4796 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-27 02:39:55.523  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:39:55.523  4733  4796 D BtGatt.GattService: current time is 97061868417
,10-27 02:39:55.524  4733  4796 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -81, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -76, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -79, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -79, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-27 02:39:55.525  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-27 02:39:55.526  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
10-27 02:39:55.526  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-27 02:39:55.527  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-27 02:39:55.527  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-27 02:39:55.990  5682  5682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-27 02:40:00.007   928   939 I ActivityManager: Killing 5363:com.android.settings/1000 (adj 15): empty #17
,10-27 02:40:00.493  5682  5729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-27 02:40:00.499  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-27 02:40:00.509  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:40:00.509  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:00.509  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:00.509  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:00.509  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:40:00.509  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:00.509  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:40:00.509  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:40:00.513  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-27 02:40:00.514  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
10-27 02:40:00.514  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:40:00.514  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-27 02:40:00.515  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-27 02:40:00.515  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-27 02:40:00.516  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-27 02:40:00.522  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:00.524  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-27 02:40:00.524  5682  5729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-27 02:40:00.524  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-27 02:40:00.527  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:00.532  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-27 02:40:00.534  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-27 02:40:00.534  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-27 02:40:00.540  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.540  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-27 02:40:00.541  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-27 02:40:00.541  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-27 02:40:00.541  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-27 02:40:00.541  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.542  5682  5729 D BluetoothAdapter: STATE_ON
,10-27 02:40:00.546  4733  4946 D BtGatt.GattService: registerClient() - UUID=53418892-9929-4e45-9bd8-1a736019f3e1
,10-27 02:40:00.547  4733  4796 D BtGatt.GattService: onClientRegistered() - UUID=53418892-9929-4e45-9bd8-1a736019f3e1, clientIf=5
,10-27 02:40:00.547  5682  5692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-27 02:40:00.548  4733  4954 D BtGatt.GattService: start scan with filters
,10-27 02:40:00.553  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-27 02:40:00.553  4733  4801 D BtGatt.ScanManager: handling starting scan
10-27 02:40:00.554  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.554  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-27 02:40:00.554  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.554  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.554  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-27 02:40:00.554  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-27 02:40:00.554  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.554  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.555  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-27 02:40:00.555  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.560  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.560  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:40:00.561  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.561  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.561  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.561  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:40:00.561  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-27 02:40:00.563  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-27 02:40:00.564  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.564  4733  4796 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-27 02:40:00.564  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:00.565  4733  4801 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-27 02:40:00.568  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.568  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.568  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.568  5682  5729 I io.jxcore.node.ConnectionHelper: start: OK
,10-27 02:40:00.572  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-27 02:40:00.572  5682  5729 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-27 02:40:00.572  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-27 02:40:00.572  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-27 02:40:00.572  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:00.572  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-27 02:40:00.572  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:00.573  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-27 02:40:00.573  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-27 02:40:00.573  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-27 02:40:00.573  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-27 02:40:00.573  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.573  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.573  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-27 02:40:00.575  5682  5729 D BluetoothAdapter: STATE_ON
10-27 02:40:00.576  4733  4954 D BtGatt.GattService: stopScan() - queue size =1
10-27 02:40:00.576  4733  4796 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-27 02:40:00.576  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:00.576  4733  4801 D BtGatt.ScanManager: Starting BLE batch scan
10-27 02:40:00.576  4733  4801 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-27 02:40:00.577  4733  4744 D BtGatt.GattService: unregisterClient() - clientIf=5
10-27 02:40:00.577  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-27 02:40:00.577  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.577  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-27 02:40:00.577  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.577  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.577  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-27 02:40:00.578  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-27 02:40:00.578  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.578  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.578  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-27 02:40:00.578  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.579  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.579  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:40:00.580  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.580  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.580  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.580  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.580  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.580  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-27 02:40:00.580  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.580  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.580  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.580  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-27 02:40:00.580  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-27 02:40:00.582  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:40:00.582  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.584  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.584  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.585  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.585  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:00.585  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:00.585  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:40:00.585  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:40:00.585  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:40:00.585  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:00.585  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:40:00.585  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:00.585  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:00.585  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:00.585  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:00.586  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:00.586  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:00.586  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:00.586  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.588  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.588  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.588  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.588  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:00.588  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:00.588  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:40:00.588  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:00.589  5682  5729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-27 02:40:00.590  4733  4796 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-27 02:40:00.590  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:00.591  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-27 02:40:00.596  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:40:00.596  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:00.596  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:00.596  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:00.596  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:40:00.596  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:00.596  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:40:00.596  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:40:00.598  4733  4796 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-27 02:40:00.598  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:00.598  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:00.598  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-27 02:40:00.599  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:40:00.599  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-27 02:40:00.599  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-27 02:40:00.599  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:40:00.599  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-27 02:40:00.602  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:00.602  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-27 02:40:00.602  5682  5729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-27 02:40:00.603  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-27 02:40:00.605  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:00.606  4733  4796 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-27 02:40:00.606  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:00.606  4733  4801 D BtGatt.ScanManager: stopping BLe Batch
,10-27 02:40:00.608  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-27 02:40:00.608  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-27 02:40:00.608  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-27 02:40:00.611  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.611  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-27 02:40:00.611  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-27 02:40:00.612  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-27 02:40:00.612  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-27 02:40:00.612  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.612  5682  5729 D BluetoothAdapter: STATE_ON
10-27 02:40:00.613  4733  4796 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-27 02:40:00.613  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:00.613  4733  4801 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-27 02:40:00.614  4733  4954 D BtGatt.GattService: registerClient() - UUID=2e26c516-39c8-47be-947a-5109711e9afc
10-27 02:40:00.615  4733  4796 D BtGatt.GattService: onClientRegistered() - UUID=2e26c516-39c8-47be-947a-5109711e9afc, clientIf=5
10-27 02:40:00.615  5682  5693 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-27 02:40:00.615  4733  4744 D BtGatt.GattService: start scan with filters
,10-27 02:40:00.619  4733  4796 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-27 02:40:00.619  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:00.619  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-27 02:40:00.619  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.619  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-27 02:40:00.619  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.619  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.619  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-27 02:40:00.619  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-27 02:40:00.619  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.619  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.619  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-27 02:40:00.619  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.620  4733  4801 D BtGatt.ScanManager: handling starting scan
10-27 02:40:00.621  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.621  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:40:00.621  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.621  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:40:00.621  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.621  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.621  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-27 02:40:00.623  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-27 02:40:00.623  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.625  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:00.625  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.625  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:00.625  5682  5729 I io.jxcore.node.ConnectionHelper: start: OK
10-27 02:40:00.625  4733  4796 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-27 02:40:00.625  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:00.626  4733  4801 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-27 02:40:00.630  4733  4796 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-27 02:40:00.630  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:00.631  4733  4801 D BtGatt.ScanManager: Starting BLE batch scan
10-27 02:40:00.631  4733  4801 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-27 02:40:00.639  4733  4796 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-27 02:40:00.639  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-27 02:40:00.644  4733  4796 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-27 02:40:00.644  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-27 02:40:01.123  5682  5682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-27 02:40:01.123  5682  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-27 02:40:01.123  5682  5682 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-27 02:40:03.033   928  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-27 02:40:05.625  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:05.626  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-27 02:40:05.626  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-27 02:40:05.626  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:05.626  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-27 02:40:05.626  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-27 02:40:05.626  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-27 02:40:05.627  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-27 02:40:05.627  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-27 02:40:05.627  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-27 02:40:05.627  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.627  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.628  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-27 02:40:05.630  5682  5729 D BluetoothAdapter: STATE_ON
,10-27 02:40:05.632  4733  4946 D BtGatt.GattService: stopScan() - queue size =1
10-27 02:40:05.635  4733  4746 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-27 02:40:05.636  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-27 02:40:05.636  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.636  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-27 02:40:05.636  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.637  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.637  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-27 02:40:05.637  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-27 02:40:05.637  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.637  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.637  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-27 02:40:05.638  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.640  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:05.640  4733  4733 D BtGatt.ScanManager: awakened up at time 107178
10-27 02:40:05.640  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:40:05.641  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.641  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:05.641  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.641  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.641  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.642  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-27 02:40:05.642  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.642  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.642  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.643  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-27 02:40:05.643  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-27 02:40:05.644  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:40:05.644  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.647  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.647  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.647  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:05.647  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-27 02:40:05.647  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:40:05.647  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:40:05.649  4733  4796 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-27 02:40:05.649  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:05.649  4733  4801 D BtGatt.ScanManager: stopping BLe Batch
,10-27 02:40:05.656  4733  4796 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-27 02:40:05.656  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:05.656  4733  4801 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-27 02:40:05.674  4733  4796 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-27 02:40:05.674  4733  4796 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:40:05.674  4733  4796 D BtGatt.GattService: current time is 107212590533
,10-27 02:40:05.674  4733  4796 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -77, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -79, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -91, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -75, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 50, -35, 86, -77, -92, -11, 1, 0, -98, 70, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 33, 100, 58, 3, 1, -37, 18, -106, 94, -13, 24, 28, 6, 8, 116, 105, 110, 54, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,10-27 02:40:05.674  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-27 02:40:05.675  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-27 02:40:05.675  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-27 02:40:05.675  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
10-27 02:40:05.675  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-27 02:40:05.676  4733  4796 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 33, 100, 58, 3, 1, -37, 18, -106, 94, -13, 24, 6, 8, 116, 105, 110, 54, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,10-27 02:40:06.051   928  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-27 02:40:06.148  5682  5682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-27 02:40:06.149  5682  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:06.149  5682  5682 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-27 02:40:10.649  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-27 02:40:10.649  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:10.649  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:40:10.649  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:10.650  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:40:10.650  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:40:10.650  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.650  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:10.650  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:40:10.650  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.651  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:10.651  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.653  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:40:10.653  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.654  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:10.658  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:10.659  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.659  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.659  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:10.659  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:10.660  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.660  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.661  5682  5729 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-27 02:40:10.663  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:10.663  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:10.663  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:40:10.663  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:10.664  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.664  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.664  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.664  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:10.664  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.664  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.664  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:10.665  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.665  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.665  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.665  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.665  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:10.669  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:10.669  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.669  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:10.669  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:10.669  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-27 02:40:10.670  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:40:10.670  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.673  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-27 02:40:10.673  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:10.673  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:10.674  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-27 02:40:10.674  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:10.674  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:40:10.674  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:10.676  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.676  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
,10-27 02:40:10.676  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.676  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.677  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:10.677  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:40:10.677  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.677  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.677  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.678  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:10.681  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.681  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.682  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.682  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:10.682  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-27 02:40:10.682  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:40:10.682  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.683  5682  5729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-27 02:40:10.684  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:10.684  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:10.684  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:40:10.684  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:10.684  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:40:10.684  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.685  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.685  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:10.685  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:40:10.685  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.685  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:10.685  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.685  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.685  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.686  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:10.686  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.689  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.689  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.690  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.690  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:10.690  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:10.690  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.690  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
,10-27 02:40:10.691  5682  5729 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,10-27 02:40:10.691  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:10.692  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:10.692  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:40:10.692  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-27 02:40:10.692  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.692  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.692  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.692  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:10.692  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.693  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.693  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
,10-27 02:40:10.693  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.693  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.693  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.693  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.693  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:10.695  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.695  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.696  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.696  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:10.696  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:10.696  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.696  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.697  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-27 02:40:10.697  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-27 02:40:10.697  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-27 02:40:10.697  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-27 02:40:10.698  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-27 02:40:10.698  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-27 02:40:10.698  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-27 02:40:10.698  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-27 02:40:10.698  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-27 02:40:10.698  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:10.698  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:10.699  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-27 02:40:10.699  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:10.699  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.699  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.699  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.699  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:10.699  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.699  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.699  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:10.700  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.700  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:10.700  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.700  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.700  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.702  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.702  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.703  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.703  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:10.703  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:10.703  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.703  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
,10-27 02:40:10.704  5682  5729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-27 02:40:10.704  5682  5729 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-27 02:40:10.704  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-27 02:40:10.710  5682  5729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-27 02:40:10.710  5682  5729 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-27 02:40:10.710  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-27 02:40:10.710  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-27 02:40:10.711  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-27 02:40:10.712  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-27 02:40:10.713  5682  5729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,10-27 02:40:10.713  5682  5729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-27 02:40:10.713  5682  5729 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,10-27 02:40:10.713  5682  5729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-27 02:40:10.713  5682  5729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-27 02:40:10.713  5682  5729 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-27 02:40:10.714  5682  5729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-27 02:40:10.714  5682  5729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-27 02:40:10.714  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-27 02:40:10.718  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-27 02:40:10.719  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-27 02:40:10.719  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-27 02:40:10.720  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-27 02:40:10.720  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,10-27 02:40:10.721  5682  5729 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-27 02:40:10.721  5682  5729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-27 02:40:10.721  5682  5738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-27 02:40:10.721  5682  5729 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-27 02:40:10.722  5682  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-27 02:40:10.722  5682  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-27 02:40:10.722  5682  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-27 02:40:10.723  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:10.723  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:10.723  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:40:10.723  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:10.723  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.723  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.723  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.724  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-27 02:40:10.724  5682  5738 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-27 02:40:10.724  5682  5738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-27 02:40:10.725  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:10.725  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.725  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.725  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:10.725  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.725  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.725  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.725  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.726  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.727  5682  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thre,ad ID: 125
10-27 02:40:10.727  5682  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-27 02:40:10.728  5682  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
10-27 02:40:10.728  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.728  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.728  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.724  4746  4746 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[35559]" dev="sockfs" ino=35559 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-27 02:40:10.724  4746  4746 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[35559]" dev="sockfs" ino=35559 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-27 02:40:10.728  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:10.728  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:10.728  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:40:10.728  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.728  5682  5738 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-27 02:40:10.729  5682  5738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-27 02:40:10.729  5682  5738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-27 02:40:10.729  5682  5729 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-27 02:40:10.730  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:10.730  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:10.730  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-27 02:40:10.730  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:10.730  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.730  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.730  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.730  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:10.730  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.730  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
,10-27 02:40:10.730  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:10.730  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.730  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.730  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.730  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.731  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.732  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:10.732  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.732  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.732  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:10.732  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:10.732  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.733  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.734  5682  5729 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-27 02:40:10.734  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:10.734  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-27 02:40:10.734  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:40:10.734  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:10.734  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.734  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.734  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.734  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:10.735  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.735  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.735  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
,10-27 02:40:10.735  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.735  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.735  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.735  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.735  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.736  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.737  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:10.737  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.737  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:10.737  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:10.737  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.737  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.738  5682  5729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-27 02:40:10.738  5682  5729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-27 02:40:10.738  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-27 02:40:10.738  5682  5729 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-27 02:40:10.738  5682  5729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-27 02:40:10.739  5682  5729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,10-27 02:40:10.739  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-27 02:40:10.739  5682  5729 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-27 02:40:10.739  5682  5729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-27 02:40:10.739  5682  5729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-27 02:40:10.739  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-27 02:40:10.739  5682  5729 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-27 02:40:10.739  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:10.739  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:10.739  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:40:10.739  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:10.740  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.740  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:10.740  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.740  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:10.740  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.740  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.740  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:10.740  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.740  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.740  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.740  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:10.740  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.742  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.742  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.742  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:10.742  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:10.742  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:10.743  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:40:10.743  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.743  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:10.743  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.744  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:10.744  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:10.744  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:10.744  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:10.744  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:10.744  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
,10-27 02:40:10.744  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:10.744  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:11.625   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-27 02:40:11.625   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-27 02:40:15.745  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:40:15.746  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:15.746  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:15.746  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.746  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:15.746  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:15.746  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:15.747  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-27 02:40:15.747  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:15.747  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:40:15.747  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:15.747  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.747  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.748  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:15.748  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
,10-27 02:40:15.748  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.748  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:15.748  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:15.748  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:40:15.749  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.749  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.749  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.750  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:15.754  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:15.755  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.755  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.755  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:15.755  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-27 02:40:15.756  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.756  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:15.760  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-27 02:40:15.760  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-27 02:40:15.763  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-27 02:40:15.767  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-27 02:40:15.767  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-27 02:40:15.767  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-27 02:40:15.768  5682  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-27 02:40:15.768  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-27 02:40:15.768  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-27 02:40:15.768  5682  5682 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-27 02:40:15.769  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-27 02:40:15.769  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-27 02:40:15.770  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-27 02:40:15.770  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-27 02:40:15.770  5682  5740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-27 02:40:15.770  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:15.770  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-27 02:40:15.771  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-27 02:40:15.771  5682  5682 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-27 02:40:15.771  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:15.771  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.771  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-27 02:40:15.771  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-27 02:40:15.771  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-27 02:40:15.772  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.772  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.772  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:15.770  4954  4954 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[35563]" dev="sockfs" ino=35563 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-27 02:40:15.770  4954  4954 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[35563]" dev="sockfs" ino=35563 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-27 02:40:15.775  5682  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-27 02:40:15.776  5682  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-27 02:40:15.776  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.776  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-27 02:40:15.776  5682  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-27 02:40:15.776  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.776  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.776  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:40:15.777  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
,10-27 02:40:15.777  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:40:15.777  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:15.777  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:40:15.777  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:15.777  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-27 02:40:15.777  5682  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-27 02:40:15.777  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:15.777  5682  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:15.777  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.777  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.778  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:15.778  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
,10-27 02:40:15.778  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.778  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:15.778  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:15.778  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.779  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.779  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:40:15.779  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.779  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:15.784  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.784  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.784  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.785  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:15.785  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-27 02:40:15.785  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.785  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:15.787  5682  5729 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,10-27 02:40:15.788  5682  5729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-27 02:40:15.788  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-27 02:40:15.788  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-27 02:40:15.788  5682  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-27 02:40:15.788  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:15.789  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:15.789  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-27 02:40:15.789  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-27 02:40:15.789  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.789  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.789  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:40:15.789  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:15.789  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.789  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
,10-27 02:40:15.789  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:15.789  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.790  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.790  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.790  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.790  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.793  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.793  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:15.793  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.793  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:15.793  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:15.793  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.794  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:15.799  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:40:15.799  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:15.800  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-27 02:40:15.800  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:15.800  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.800  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.800  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-27 02:40:15.800  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:15.800  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.800  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:15.800  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:15.800  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.800  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:15.800  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.801  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.801  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.803  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.803  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.803  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.803  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-27 02:40:15.803  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:15.803  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.803  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
,10-27 02:40:15.804  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-27 02:40:15.804  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:40:15.805  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:40:15.805  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:40:15.805  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.805  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.805  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-27 02:40:15.805  5682  5729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72785f1 not in the list
10-27 02:40:15.805  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.805  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
10-27 02:40:15.805  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:15.805  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.805  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:15.805  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:15.805  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:15.806  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.808  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.808  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:40:15.808  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:40:15.808  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:40:15.808  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:40:15.808  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:15.808  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a5d6 not in the list
,10-27 02:40:15.809  5682  5729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,10-27 02:40:15.810  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-27 02:40:15.811  5682  5729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-27 02:40:15.811  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-27 02:40:15.811  5682  5729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-27 02:40:15.811  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-27 02:40:15.813  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-27 02:40:15.813  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-27 02:40:15.814  5682  5729 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-27 02:40:15.814  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-27 02:40:15.814  5682  5729 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-27 02:40:15.814  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-27 02:40:15.814  5682  5729 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,10-27 02:40:15.815  5682  5729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-27 02:40:15.815  5682  5729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-27 02:40:15.815  5682  5729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-27 02:40:15.816  5682  5729 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-27 02:40:15.816  5682  5729 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,10-27 02:40:15.816  5682  5729 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,10-27 02:40:15.816  5682  5729 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-27 02:40:15.817  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:40:15.818  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@78db8c8 added. We now have 3 listener(s)
10-27 02:40:15.818  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-27 02:40:15.820  5682  5729 D BluetoothAdapter: enable(): BT is already enabled..!
,10-27 02:40:15.820   928  3287 D WifiService: setWifiEnabled: true pid=5682, uid=10077
10-27 02:40:15.821   928  3287 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-27 02:40:15.854  4733  4923 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-27 02:40:15.854  4733  4944 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-27 02:40:16.279  5682  5682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-27 02:40:16.626   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:17.627   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:18.628   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:19.629   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:19.803   928  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-27 02:40:20.630   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:20.827  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-27 02:40:20.827  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@854cd61 added. We now have 4 listener(s)
10-27 02:40:20.827  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-27 02:40:20.840  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:40:20.840  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@854cd61 removed from the list
,10-27 02:40:20.841  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
,10-27 02:40:20.841  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:40:20.841  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:20.843  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:40:20.843  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb53086 added. We now have 4 listener(s)
,10-27 02:40:20.843  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:40:20.847  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:20.847  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb53086 removed from the list
,10-27 02:40:20.847  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:20.847  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:20.847  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:20.848  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-27 02:40:20.848  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b92ad47 added. We now have 4 listener(s)
10-27 02:40:20.848  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-27 02:40:20.852   928  3222 D WifiService: setWifiEnabled: false pid=5682, uid=10077
10-27 02:40:20.852   928  3222 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-27 02:40:20.856   928  3037 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-27 02:40:20.857   928  3037 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-27 02:40:20.857   928  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-27 02:40:20.857   928  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-27 02:40:20.862  4733  4792 D BluetoothAdapterState: Current state: ON, message: 23
10-27 02:40:20.862  4733  4792 D BluetoothAdapterProperties: Setting state to 13
10-27 02:40:20.863  4733  4792 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-27 02:40:20.864  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-27 02:40:20.865  4733  4792 D BluetoothAdapterProperties: onBluetoothDisable()
,10-27 02:40:20.867  4733  4792 I BluetoothAdapterState: Entering PendingCommandState
,10-27 02:40:20.868  4733  4733 D BluetoothMapService: onReceive
10-27 02:40:20.868  4733  4733 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-27 02:40:20.868  4733  4733 D BluetoothMapService: STATE_TURNING_OFF
10-27 02:40:20.869  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.869  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:40:20.869  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:20.869  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:20.869  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:20.869  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:20.869  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:20.869  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:40:20.869  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:40:20.869  4733  4733 D BluetoothMapService: MAP Service closeService in
10-27 02:40:20.869  4733  4733 D BluetoothMapMasInstance0: MAP Service shutdown
10-27 02:40:20.869  4733  4733 D ObexServerSockets0: shutdown(block = true)
10-27 02:40:20.870  4733  4733 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-27 02:40:20.870  4733  4956 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-27 02:40:20.870  4733  4733 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-27 02:40:20.870  4733  4944 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-27 02:40:20.871  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-27 02:40:20.872  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:20.872  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
10-27 02:40:20.873  4733  4957 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-27 02:40:20.875  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:20.877   928  5454 D DhcpClient: Clearing IP address
10-27 02:40:20.877   507   920 D CommandListener: Clearing all IP addresses on wlan0
10-27 02:40:20.878  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:20.881  4733  4733 I BtOppRfcommListener: stopping Accept Thread
10-27 02:40:20.881  4733  5386 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-27 02:40:20.881  4733  5386 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-27 02:40:20.886  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-27 02:40:20.886  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:20.886  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:20.886  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:20.886  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:20.886  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:20.886  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:20.886  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:40:20.886  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:40:20.886  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.886  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:20.889   507   920 D CommandListener: Setting iface cfg
10-27 02:40:20.889  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.890  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:20.890  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:20.890  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:20.890  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:20.890  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:20.890  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:20.890  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:40:20.890  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:40:20.890  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.890  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:20.892  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:20.894   928   941 I ActivityManager: Start proc 5744:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-27 02:40:20.895  3638  5508 V NativeCrypto: Read error: ssl=0x7f7cc02000: I/O error during system call, Connection timed out
10-27 02:40:20.895  4733  4796 D BluetoothAdapterProperties: Scan Mode:20
,10-27 02:40:20.895  4733  4792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-27 02:40:20.895   928  5455 D DhcpClient: Receive thread stopped
10-27 02:40:20.897  3638  5508 V NativeCrypto: SSL shutdown failed: ssl=0x7f7cc02000: I/O error during system call, Broken pipe
,10-27 02:40:20.898  4733  4733 D HeadsetService: Received stop request...Stopping profile...
,10-27 02:40:20.900   928  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-27 02:40:20.901   928  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-27 02:40:20.901  3842  3859 D BluetoothHeadset: Proxy object disconnected
,10-27 02:40:20.902  4733  4733 D A2dpService: Received stop request...Stopping profile...
10-27 02:40:20.903   928   928 D BluetoothHeadset: Proxy object disconnected
10-27 02:40:20.903   928   928 D BluetoothHeadset: Proxy object disconnected
10-27 02:40:20.903  4733  4949 D A2dpStateMachine: Exit Disconnected: -1
10-27 02:40:20.903  3195  3428 D BluetoothHeadset: Proxy object disconnected
10-27 02:40:20.903   928   928 D BluetoothHeadset: Proxy object disconnected
,10-27 02:40:20.903  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.903  3195  3195 D HeadsetProfile: Bluetooth service disconnected
10-27 02:40:20.903  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:20.903  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:20.903  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:20.903  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:20.903  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:20.903  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:20.903  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:40:20.903  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:40:20.904  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.904  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:20.904   928   928 D RttService: SCAN_AVAILABLE : 1
,10-27 02:40:20.905   928   928 D BluetoothA2dp: Proxy object disconnected
10-27 02:40:20.905   928  3147 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-27 02:40:20.905  4733  4733 D HidService: Received stop request...Stopping profile...
10-27 02:40:20.905  4733  4733 D HidService: Stopping Bluetooth HidService
10-27 02:40:20.906  3195  3195 D BluetoothA2dp: Proxy object disconnected
10-27 02:40:20.906   542   542 E Parcel  : Reading a NULL string not supported here.
10-27 02:40:20.907  4733  4733 D HealthService: Received stop request...Stopping profile...
,10-27 02:40:20.907  3195  3195 D BluetoothInputDevice: Proxy object disconnected
10-27 02:40:20.907  3195  3195 D HidProfile: Bluetooth service disconnected
10-27 02:40:20.907  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.908  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:20.908  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:20.908  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:20.908  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:20.908  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:20.908  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:20.908  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:20.908  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:40:20.908  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.909  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:20.909   928  3039 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-27 02:40:20.909  4733  4733 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:20.909  4733  4733 V BluetoothAdapterState: isTurningOn()=false
,10-27 02:40:20.909  4733  4733 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:20.910  4733  4733 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:20.911  3819  3938 W QCNEJ   : |CORE| network lost: 100
10-27 02:40:20.911  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.911  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:20.911  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:20.911  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:20.911  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:20.911  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:20.911  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:20.911  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:20.911  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:40:20.911  3819  3938 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-27 02:40:20.912  4733  4733 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-27 02:40:20.912  4733  4733 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-27 02:40:20.912  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-27 02:40:20.912  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:20.912  4733  4923 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-27 02:40:20.912  4733  4923 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-27 02:40:20.912  4733  4733 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:20.912  4733  4923 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-27 02:40:20.912  4733  4733 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:20.912  4733  4733 V BluetoothAdapterState: isBleTurningOn()=false
,10-27 02:40:20.912  4733  4733 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:20.913  4733  4733 D PanService: Received stop request...Stopping profile...
10-27 02:40:20.913  4733  4796 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-27 02:40:20.913  4733  4796 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-27 02:40:20.915  4733  4796 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-27 02:40:20.915  4733  4923 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-27 02:40:20.915  4733  4923 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-27 02:40:20.915  4733  4923 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-27 02:40:20.915  4733  4923 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-27 02:40:20.915  4733  4923 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-27 02:40:20.915  4733  4733 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:20.915  4733  4923 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-27 02:40:20.915  4733  4733 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:20.916  4733  4733 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:20.916  4733  4733 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:20.916  4733  4733 D BluetoothMapService: Received stop request...Stopping profile...
10-27 02:40:20.916  4733  4733 D BluetoothMapService: stop()
10-27 02:40:20.917  4733  4733 D BluetoothMapAppObserver: deinitObservers()
10-27 02:40:20.917  4733  4733 D BluetoothMapAppObserver: removeReceiver()
10-27 02:40:20.918  4733  4733 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-27 02:40:20.918  4733  4733 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-27 02:40:20.918  4733  4796 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-27 02:40:20.918   928  3037 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-27 02:40:20.918  4733  4733 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:20.919  4733  4733 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:20.919  4733  4733 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:20.919  4733  4733 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:20.919  4733  4733 D SapService: Received stop request...Stopping profile...
10-27 02:40:20.919  4733  4733 V SapService: stop()
,10-27 02:40:20.921  4733  4733 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-27 02:40:20.923  4733  4733 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-27 02:40:20.923  4733  4796 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-27 02:40:20.923  4733  4733 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:20.923  4733  4733 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:20.923  4733  4733 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:20.923  4733  4733 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:20.924  4733  4733 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-27 02:40:20.924  4733  4733 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-27 02:40:20.926   928  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-27 02:40:20.928  4733  4733 D BluetoothMapService: MAP Service closeService in
10-27 02:40:20.928  4733  4733 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:20.928  4733  4733 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:20.928  4733  4733 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:20.928  4733  4733 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:20.928  4733  4733 D BluetoothMapService: cleanup()
10-27 02:40:20.928  4733  4733 D BluetoothMapService: MAP Service closeService in
10-27 02:40:20.928  4733  4733 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:20.929  4733  4733 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:20.929  4733  4733 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:20.929  4733  4733 V BluetoothAdapterState: isBleTurningOff()=false
,10-27 02:40:20.929  4733  4792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-27 02:40:20.929  4733  4792 D BluetoothAdapterProperties: Setting state to 15
10-27 02:40:20.929  4733  4792 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-27 02:40:20.929  3195  3195 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-27 02:40:20.929  3195  3195 D PanProfile: Bluetooth service disconnected
10-27 02:40:20.929  3195  3195 D BluetoothMap: Proxy object disconnected
10-27 02:40:20.929  3195  3195 D MapProfile: Bluetooth service disconnected
,10-27 02:40:20.929  4733  4792 I BluetoothAdapterState: Entering BleOnState
,10-27 02:40:20.930  3195  4040 D BluetoothMap: onBluetoothStateChange: up=false
,10-27 02:40:20.930  3842  3859 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-27 02:40:20.931   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-27 02:40:20.931  3195  3207 D BluetoothPbap: onBluetoothStateChange: up=false
,10-27 02:40:20.932  3195  3211 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-27 02:40:20.932   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-27 02:40:20.932  3195  3428 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-27 02:40:20.932   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-27 02:40:20.933  3195  4040 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-27 02:40:20.933   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-27 02:40:20.933  3195  3207 D BluetoothPan: onBluetoothStateChange on: false
,10-27 02:40:20.934  4733  4792 D BluetoothAdapterState: Current state: BLE ON, message: 20
,10-27 02:40:20.934  4733  4792 D BluetoothAdapterProperties: Setting state to 16
10-27 02:40:20.934  4733  4792 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-27 02:40:20.935  4733  4792 D BluetoothAdapterProperties: onBleDisable
,10-27 02:40:20.935  4733  4792 I BluetoothAdapterState: Entering PendingCommandState
,10-27 02:40:20.935  4733  4793 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,10-27 02:40:20.936  4733  4796 D BluetoothAdapterProperties: Scan Mode:20
10-27 02:40:20.938  4733  4923 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-27 02:40:20.938  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.938  4733  4923 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-27 02:40:20.938  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:20.938  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:20.938  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:20.938  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:20.938  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:20.938  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:20.938  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:20.938  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:20.942  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.942  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:20.942  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:20.942  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:20.942  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:20.942  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:20.942  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:20.942  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:20.942  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:20.945  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:20.946  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:20.946  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:20.946  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:20.946  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:20.946  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:20.946  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:20.946  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:20.946  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:20.946   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-27 02:40:20.947  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:20.949  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:20.950  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:20.963  5744  5744 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-27 02:40:20.970   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-27 02:40:20.970   507   920 D CommandListener: Clearing all IP addresses on wlan0
10-27 02:40:20.970   507   920 D TetherController: Setting IP forward enable = 0
10-27 02:40:20.971   928  3039 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-27 02:40:20.972   928  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-27 02:40:20.973   928   945 D Tethering: MasterInitialState.processMessage what=3
10-27 02:40:20.976  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:20.976  5340  5340 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@298de10 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-27 02:40:20.977  4016  4016 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-27 02:40:20.978  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:20.980  5128  5152 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-27 02:40:20.981  5128  5152 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-27 02:40:20.982  5128  5152 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-27 02:40:20.982  5128  5152 E SarControlService: no key has been found,reset the power
10-27 02:40:20.982  5128  5165 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-27 02:40:20.983  5128  5165 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-27 02:40:20.983  5128  5165 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-27 02:40:20.983  5153  5153 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-27 02:40:20.983  5153  5153 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-27 02:40:20.984  5128  5165 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-27 02:40:20.984  5128  5165 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-27 02:40:20.984  5128  5165 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-27 02:40:20.985  5153  5153 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-27 02:40:20.985  5153  5153 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-27 02:40:20.988  5153  5167 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f357876 HexData = [00000000ea03000000000000ffffffff]
10-27 02:40:20.988  5153  5167 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-27 02:40:20.988  5153  5167 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-27 02:40:20.988  5153  5153 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-27 02:40:20.988  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:20.988  5128  5138 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-27 02:40:20.993  5744  5744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-27 02:40:20.995  5153  5167 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f357876 HexData = [00000000eb03000000000000ffffffff]
10-27 02:40:20.995  5153  5167 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-27 02:40:20.995  5153  5167 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-27 02:40:20.996  5153  5153 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-27 02:40:20.996  5128  5139 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-27 02:40:20.999   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8fa7fe4:true
10-27 02:40:21.000  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-27 02:40:21.017  5744  5744 D LocalBluetoothProfileManager: Adding local MAP profile
,10-27 02:40:21.019  5744  5744 D BluetoothMap: Create BluetoothMap proxy object
,10-27 02:40:21.025  5744  5744 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-27 02:40:21.031  5744  5744 D DockEventReceiver: finishStartingService: stopping service
,10-27 02:40:21.033  5744  5744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-27 02:40:21.037  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-27 02:40:21.037  5744  5744 D DockEventReceiver: finishStartingService: stopping service
,10-27 02:40:21.039   928  3653 I ActivityManager: Killing 5483:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-27 02:40:21.057  3920  3920 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-27 02:40:21.061  3920  3920 D SystemUpdateService: onCreate
,10-27 02:40:21.064  3920  3920 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-27 02:40:21.072  3920  5775 I SystemUpdateService: active receiver: enabled
,10-27 02:40:21.073  3920  3920 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
10-27 02:40:21.077  3920  5481 I iu.UploadsManager: num queued entries: 0
10-27 02:40:21.078  3920  5481 I iu.UploadsManager: num updated entries: 0
,10-27 02:40:21.082  3920  3920 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-27 02:40:21.083  3920  3920 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-27 02:40:21.084  3920  5775 I SystemUpdateService: OffPeak download feature is not enabled!
,10-27 02:40:21.086  3920  5481 I iu.SyncManager: NEXT; no task
,10-27 02:40:21.087  3920  5775 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-27 02:40:21.087  3920  5775 I SystemUpdateService: now status is 0 (complete)
10-27 02:40:21.087  3920  5775 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-27 02:40:21.087  3920  5775 I SystemUpdateService: file has been verified
10-27 02:40:21.087  3920  5775 I SystemUpdateService: OTA package size = 21989297
,10-27 02:40:21.094  3920  5775 I SystemUpdateService: showing system update notification
,10-27 02:40:21.097   928  3653 I ActivityManager: Start proc 5777:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-27 02:40:21.108   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-27 02:40:21.110  3920  3920 D SystemUpdateService: onDestroy
,10-27 02:40:21.128  5777  5777 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-27 02:40:21.131  5777  5777 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-27 02:40:21.137  5777  5777 D SprintDMHelper: simOperator: 
10-27 02:40:21.137  5777  5777 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-27 02:40:21.147  4733  4796 I bt_hci  : shut_down
,10-27 02:40:21.150  5081  5789 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-27 02:40:21.150  4733  4802 D bt_hwcfg: hw_epilog_process
10-27 02:40:21.151  4733  4802 I bt_vendor: low_power_mode_cb
,10-27 02:40:21.154  4733  4802 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-27 02:40:21.154  4733  4802 I bt_vendor: epilog_cb
,10-27 02:40:21.154  4733  4802 I bt_hci  : epilog_finished_callback
,10-27 02:40:21.156  4733  4796 I bt_hci_h4: hal_close
,10-27 02:40:21.156  4733  4796 I bt_userial_vendor: device fd = 54 close
,10-27 02:40:21.164   928  3287 I ActivityManager: Killing 5340:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-27 02:40:21.263  4733  4793 D bt_stack_manager: event_shut_down_stack finished.
,10-27 02:40:21.263  4733  4792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-27 02:40:21.265  4733  4792 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-27 02:40:21.265  4733  4733 D BtGatt.DebugUtils: handleDebugAction() action=null
10-27 02:40:21.266  4733  4733 D BtGatt.GattService: Received stop request...Stopping profile...
10-27 02:40:21.266  4733  4733 D BtGatt.GattService: stop()
,10-27 02:40:21.266  4733  4733 D BtGatt.AdvertiseManager: advertise clients cleared
,10-27 02:40:21.269  4733  4733 V BluetoothAdapterState: isTurningOff()=false
,10-27 02:40:21.269  4733  4733 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:21.269  4733  4733 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:21.269  4733  4733 V BluetoothAdapterState: isBleTurningOff()=true
10-27 02:40:21.269  4733  4792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-27 02:40:21.270  4733  4792 D BluetoothAdapterProperties: Setting state to 10
,10-27 02:40:21.270  4733  4792 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-27 02:40:21.271  4733  4792 I BluetoothAdapterState: Entering OffState
,10-27 02:40:21.273   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-27 02:40:21.280  4733  4733 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-27 02:40:21.281  4733  4733 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-27 02:40:21.281  4733  4733 I BluetoothServiceJni: cleanupNative: return from cleanup
10-27 02:40:21.282  4733  4793 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-27 02:40:21.285  4733  4733 I art     : System.exit called, status: 0
,10-27 02:40:21.285  4733  4733 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-27 02:40:21.307   928  3287 I ActivityManager: Process com.android.bluetooth (pid 4733) has died
,10-27 02:40:21.631   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-27 02:40:22.057   507   920 E Netd    : netlink response contains error (No such file or directory)
,10-27 02:40:22.058   928  3039 E NetdConnector: NDC Command {109 network destroy 100} took too long (1086ms)
,10-27 02:40:22.059   928  3037 E NetdConnector: NDC Command {110 interface ipv6 wlan0 disable} took too long (1086ms)
,10-27 02:40:22.059   928  3039 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-27 02:40:22.060   928  3037 D DhcpClient: doQuit
,10-27 02:40:22.060   928  3035 E NetdConnector: NDC Command {111 bandwidth setglobalalert 2097152} took too long (1082ms)
,10-27 02:40:22.060   507   920 D TetherController: Setting IP forward enable = 0
,10-27 02:40:22.061   928  3037 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-27 02:40:22.062   928  5454 D DhcpClient: onQuitting
10-27 02:40:22.063  3531  3531 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-27 02:40:22.069  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:22.069  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:22.069  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:22.069  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:22.069  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:22.069  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:22.069  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:22.069  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:22.069  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-27 02:40:22.070  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:22.070  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:22.071  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:22.072  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:22.072  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:22.072  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:22.072  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:22.072  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:22.072  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:22.072  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:22.072  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-27 02:40:22.072  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:22.072  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:22.073  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:22.073  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:22.073  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:22.073  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:22.073  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:22.073  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:22.073  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:22.073  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:22.073  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-27 02:40:22.073  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:22.073  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-27 02:40:22.082   928   941 I ActivityManager: Start proc 5796:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-27 02:40:22.087  3531  3531 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-27 02:40:22.092  3531  3531 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-27 02:40:22.116  5796  5796 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-27 02:40:22.122   928  3857 I ActivityManager: Killing 3952:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-27 02:40:22.147  3531  3531 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-27 02:40:22.165  3531  3531 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-27 02:40:22.269   928  3037 D wifi    : In wifi stop Hal
10-27 02:40:22.270   928  3037 D wifi    : halHandle = 0x7f6b116400, mVM = 0x7f8770d140, mCls = 0x100a02
,10-27 02:40:22.270   928  3529 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-27 02:40:22.270   928  3529 D WifiHAL : Got a signal to exit!!!
10-27 02:40:22.271   928  3529 I WifiHAL : Exit wifi_event_loop
10-27 02:40:22.272  5081  5081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-27 02:40:22.276   928  3037 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-27 02:40:22.276   928  3037 E WifiHAL : Event processing terminated
10-27 02:40:22.276  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:22.276   928  3037 D wifi    : In wifi cleaned up handler
10-27 02:40:22.277   928  3037 I WifiHAL : Internal cleanup completed
,10-27 02:40:22.278  4126  4272 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-27 02:40:22.280  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:22.283  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:22.292   928  3529 D wifi    : set interface wlan0 flags (DOWN)
,10-27 02:40:22.292   928  3037 D WifiNative-HAL: HAL event thread stopped successfully
,10-27 02:40:22.499   928   945 D Tethering: InitialState.processMessage what=4
,10-27 02:40:22.507   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-27 02:40:25.874   928  3287 D WifiService: setWifiEnabled: true pid=5682, uid=10077
,10-27 02:40:25.874   928  3287 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-27 02:40:25.885   507   920 D SoftapController: Softap fwReload - Ok
,10-27 02:40:25.892   507   920 D CommandListener: Setting iface cfg
,10-27 02:40:25.893   507   920 D CommandListener: Trying to bring down wlan0
,10-27 02:40:25.894   507   920 D CommandListener: Clearing all IP addresses on wlan0
,10-27 02:40:25.898   928  3037 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-27 02:40:26.496   928  3037 D wifi    : set interface wlan0 flags (UP)
,10-27 02:40:26.501   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-27 02:40:26.502   928  3037 I WifiHAL : Initializing wifi
,10-27 02:40:26.502   928  3037 I WifiHAL : Creating socket
,10-27 02:40:26.510   928  3037 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-27 02:40:26.511   928  3037 D wifi    : Did set static halHandle = 0x7f6b116400
,10-27 02:40:26.511   928  3037 D wifi    : halHandle = 0x7f6b116400, mVM = 0x7f8770d140, mCls = 0x1956
10-27 02:40:26.511   928  3037 D wifi    : array field set
10-27 02:40:26.511   928  3037 I WifiNative-HAL: interface[0] = wlan0
,10-27 02:40:26.515   928  5810 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547257148416
,10-27 02:40:26.516   928  5810 D wifi    : waitForHalEvents called, vm = 0x7f8770d140, obj = 0x1956, env = 0x7f70d7d300
,10-27 02:40:26.518   928  3037 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-27 02:40:26.522  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:26.523  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:26.524  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:26.579  5811  5811 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-27 02:40:26.631   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:26.650  5811  5811 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-27 02:40:26.677  5811  5811 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-27 02:40:26.677  5811  5811 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-27 02:40:26.691   928  3037 D WifiConfigStore: Loading config and enabling all networks 
,10-27 02:40:26.696  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:26.696  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:26.696  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:26.696  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:26.696  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:26.696  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:26.696  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:26.696  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:26.696  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:26.696  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-27 02:40:26.696  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-27 02:40:26.699  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:26.699  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:26.699  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:26.699  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:26.699  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:26.699  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:26.699  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:26.699  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:26.699  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:26.699  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:26.700  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-27 02:40:26.702  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-27 02:40:26.702  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:26.702  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:26.702  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:26.702  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:26.702  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:26.702  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:26.702  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:26.702  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:26.703  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:26.703  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-27 02:40:26.711   928  3037 D WifiConfigStore: loaded 0 passpoint configs
,10-27 02:40:26.712   928  3037 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
10-27 02:40:26.712   928  3037 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-27 02:40:26.713   928  3037 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-27 02:40:26.713   928  3037 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-27 02:40:26.713   928  3037 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,10-27 02:40:26.714   928  3037 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-27 02:40:26.714   928  3037 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-27 02:40:26.714   928  3037 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,10-27 02:40:26.714   928  3037 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-27 02:40:26.714   928  3037 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-27 02:40:26.714   928  3037 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-27 02:40:26.714   928  3037 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-27 02:40:26.716   928  3037 D WifiNative-HAL: Setting external_sim to 1
,10-27 02:40:26.717   928  3037 D wifi    : setting dfs flag to true, 0x7f6a85ee00
,10-27 02:40:26.717  5081  5081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-27 02:40:26.717   928  3037 D WifiStateMachine: Setting OUI to DA-A1-19
,10-27 02:40:26.717   928  3037 D wifi    : setting scan oui 0x7f6a85ee00
10-27 02:40:26.717   928  3037 D WifiHAL : Sending mac address OUI
,10-27 02:40:26.720   928  3037 E native  : do suspend false
,10-27 02:40:26.727   928  3037 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-27 02:40:26.727   928   928 D RttService: SCAN_AVAILABLE : 3
10-27 02:40:26.727   928  3147 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-27 02:40:26.731   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-27 02:40:26.734   507   920 D CommandListener: Setting iface cfg
,10-27 02:40:26.740   928  3036 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '121 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 121 Failed to set address (No such device)'
10-27 02:40:26.740   928  3036 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-27 02:40:26.746   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128284 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,10-27 02:40:26.749   928  3036 D WifiNative-HAL: p2pGetDeviceAddress
,10-27 02:40:26.750   928  3036 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-27 02:40:27.632   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:28.633   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:29.634   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:29.832  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-27 02:40:29.841  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-27 02:40:29.847  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-27 02:40:29.852  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-27 02:40:29.884   928  3037 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-27 02:40:29.886   928  3037 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-27 02:40:29.886   928  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-27 02:40:29.898   928  3037 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-27 02:40:29.932   928  3037 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-27 02:40:29.939  5811  5811 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-27 02:40:30.360  5811  5811 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-27 02:40:30.397  5811  5811 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-27 02:40:30.397  5811  5811 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-27 02:40:30.413   928  3037 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-27 02:40:30.413   928  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-27 02:40:30.413   928  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-27 02:40:30.432   928  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-27 02:40:30.446   507   920 D CommandListener: Setting iface cfg
,10-27 02:40:30.452   928  3037 D WifiStateMachine: Start Dhcp Watchdog 2
,10-27 02:40:30.462   928  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-27 02:40:30.462   928  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-27 02:40:30.462   928  3039 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-27 02:40:30.487   928  5817 D DhcpClient: Receive thread started
,10-27 02:40:30.567   928  3037 E native  : do suspend false
,10-27 02:40:30.582   928  5816 D DhcpClient: Broadcasting DHCPDISCOVER
,10-27 02:40:30.595   928  5817 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,10-27 02:40:30.596   928  5816 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,10-27 02:40:30.598   928  5816 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-27 02:40:30.613   928  5817 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-27 02:40:30.614   928  5816 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-27 02:40:30.617   507   920 D CommandListener: Setting iface cfg
,10-27 02:40:30.621   928  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-27 02:40:30.628   928  5816 D DhcpClient: Scheduling renewal in 86399s
,10-27 02:40:30.635   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:30.636   928  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-27 02:40:30.637   928  3037 D WifiConfigStore: No blacklist allowed without epno enabled
,10-27 02:40:30.640   928  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-27 02:40:30.649   928  3039 D ConnectivityService: Adding iface wlan0 to network 101
,10-27 02:40:30.654   928  3037 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-27 02:40:30.689   928  3039 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-27 02:40:30.689   928  3039 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-27 02:40:30.691   928  3039 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-27 02:40:30.694   928  3039 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-27 02:40:30.697   928  3039 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-27 02:40:30.704   928  3039 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-27 02:40:30.708   928  3039 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-27 02:40:30.708   928  3039 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-27 02:40:30.709   928  3039 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,10-27 02:40:30.709   928  3037 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-27 02:40:30.709   928  3039 D ConnectivityService:    accepting network in place of null
10-27 02:40:30.709   928  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-27 02:40:30.710   928  3039 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-27 02:40:30.727   928  5815 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132265, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-27 02:40:30.733   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-27 02:40:30.753   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-27 02:40:30.756   928  3039 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-27 02:40:30.756  3819  3938 W QCNEJ   : |CORE| network available: 101
10-27 02:40:30.756   928  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-27 02:40:30.757   928  3039 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-27 02:40:30.758   928   945 D Tethering: MasterInitialState.processMessage what=3
10-27 02:40:30.759  3819  3938 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-27 02:40:30.762  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-27 02:40:30.762  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:30.762  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:30.762  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:30.762  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:30.762  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:30.762  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:30.762  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:40:30.762  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:40:30.762  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.762  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:30.762  3819  3938 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-27 02:40:30.763  3819  3938 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-27 02:40:30.765  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.765  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:30.765  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:30.765  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:30.765  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:30.765  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:30.765  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:30.765  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:40:30.765  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:40:30.766  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-27 02:40:30.766  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:30.768  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.768  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:30.768  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:30.768  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:30.768  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:30.768  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:30.768  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:30.768  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:40:30.768  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:40:30.768  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.768  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:40:30.770   928  3222 D ConnectivityService: Returning blocked NetworkInfo to uid=10062
10-27 02:40:30.771   928  3857 D ConnectivityService: Returning blocked NetworkInfo to uid=10043
10-27 02:40:30.775  4016  4016 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-27 02:40:30.777  3920  3920 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-27 02:40:30.780  3920  3920 D SystemUpdateService: onCreate
10-27 02:40:30.784  3920  3920 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-27 02:40:30.794  3920  3920 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
10-27 02:40:30.801  3920  5481 I iu.UploadsManager: num queued entries: 0
10-27 02:40:30.802  3920  5826 I SystemUpdateService: active receiver: enabled
10-27 02:40:30.806  3920  3920 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-27 02:40:30.807  3920  3920 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-27 02:40:30.807   928  5814 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-27 02:40:30.810  5777  5777 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-27 02:40:30.814  5777  5777 D SprintDMHelper: simOperator: 
10-27 02:40:30.815  5777  5777 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-27 02:40:30.827   928  3869 D ConnectivityService: Returning blocked NetworkInfo to uid=10053
10-27 02:40:30.829  3920  5481 I iu.UploadsManager: num updated entries: 0
10-27 02:40:30.838  3920  5826 I SystemUpdateService: OffPeak download feature is not enabled!
10-27 02:40:30.840  3920  5481 I iu.SyncManager: NEXT; no task
10-27 02:40:30.846  3920  5826 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-27 02:40:30.846  3920  5826 I SystemUpdateService: now status is 0 (complete)
10-27 02:40:30.846  3920  5826 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-27 02:40:30.846  3920  5826 I SystemUpdateService: file has been verified
10-27 02:40:30.846  3920  5826 I SystemUpdateService: OTA package size = 21989297
,10-27 02:40:30.852   928  5814 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 27 Oct 2016 00:40:30 GMT], X-Android-Received-Millis=[1477528830852], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477528830831]}
10-27 02:40:30.853   928  3039 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-27 02:40:30.853   928  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,10-27 02:40:30.853   928  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-27 02:40:30.854   928  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-27 02:40:30.854  3920  5826 I SystemUpdateService: showing system update notification
,10-27 02:40:30.862   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-27 02:40:30.863  3920  3920 D SystemUpdateService: onDestroy
,10-27 02:40:30.878   928  3222 D WifiService: setWifiEnabled: false pid=5682, uid=10077
,10-27 02:40:30.878   928  3222 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-27 02:40:30.879   928  3037 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-27 02:40:30.880   928  3037 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-27 02:40:30.880   928  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-27 02:40:30.880   928  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-27 02:40:30.890   928  5816 D DhcpClient: Clearing IP address
,10-27 02:40:30.890   507   920 D CommandListener: Clearing all IP addresses on wlan0
,10-27 02:40:30.892   507   920 D CommandListener: Setting iface cfg
,10-27 02:40:30.893   928  5817 D DhcpClient: Receive thread stopped
,10-27 02:40:30.896  3638  5827 V NativeCrypto: SSL handshake aborted: ssl=0x7f85f0e380: I/O error during system call, Connection timed out
,10-27 02:40:30.901   928  3857 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,10-27 02:40:30.902   928  5814 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,10-27 02:40:30.902   928  5814 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-27 02:40:30.903   928  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-27 02:40:30.903   928  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,10-27 02:40:30.907   542   542 E Parcel  : Reading a NULL string not supported here.
,10-27 02:40:30.908   928  5814 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
10-27 02:40:30.912   928   928 D RttService: SCAN_AVAILABLE : 1
10-27 02:40:30.912   928  3039 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-27 02:40:30.912   928  3147 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-27 02:40:30.913  3819  3938 W QCNEJ   : |CORE| network lost: 101
10-27 02:40:30.914  3819  3938 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-27 02:40:30.915   928  3037 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-27 02:40:30.918   928  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-27 02:40:30.934   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-27 02:40:30.952   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-27 02:40:30.953   507   920 D CommandListener: Clearing all IP addresses on wlan0
10-27 02:40:30.953   928  3039 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-27 02:40:30.953   928  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-27 02:40:30.955   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-27 02:40:30.957  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-27 02:40:30.957  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:30.957  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:30.957  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:30.957  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:30.957  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:30.957  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:30.957  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:30.957  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:30.957  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.957  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:30.958   928  3037 D DhcpClient: doQuit
10-27 02:40:30.958   928  3037 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-27 02:40:30.958   928  5816 D DhcpClient: onQuitting
10-27 02:40:30.959  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.959  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:30.959  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:30.959  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:30.959  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:40:30.959  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:30.959  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:30.959  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:30.959  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:30.959  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.959  5811  5811 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-27 02:40:30.959  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-27 02:40:30.961  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.961  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:30.961  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:30.961  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:30.961  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:30.961  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:30.961  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:30.961  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:30.961  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:30.961  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.961  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:30.962  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-27 02:40:30.963  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:30.963  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:30.963  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:30.963  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:30.963  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:30.963  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:30.963  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:30.963  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:30.963  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.963  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:30.963  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.964  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:30.964  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:30.964  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:30.964  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:30.964  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:30.964  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:30.964  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:30.964  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-27 02:40:30.964  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:30.964  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:30.965  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:30.967  4016  4016 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-27 02:40:30.969  3920  3920 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-27 02:40:30.973  3920  3920 D SystemUpdateService: onCreate
,10-27 02:40:30.975  3920  3920 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-27 02:40:30.976  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-27 02:40:30.980  5811  5811 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-27 02:40:30.984  3920  5841 I SystemUpdateService: active receiver: enabled
,10-27 02:40:30.986  3920  3920 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-27 02:40:30.991  3920  5481 I iu.UploadsManager: num queued entries: 0
,10-27 02:40:30.991  3920  5481 I iu.UploadsManager: num updated entries: 0
,10-27 02:40:30.993  3920  3920 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-27 02:40:30.995  3920  3920 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-27 02:40:30.997  5777  5777 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-27 02:40:31.001  5777  5777 D SprintDMHelper: simOperator: 
10-27 02:40:31.001  5777  5777 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-27 02:40:31.009   507   920 E Netd    : netlink response contains error (No such file or directory)
,10-27 02:40:31.010  3920  5841 I SystemUpdateService: OffPeak download feature is not enabled!
10-27 02:40:31.010   928  3039 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-27 02:40:31.010  5811  5811 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-27 02:40:31.013  3920  5481 I iu.SyncManager: NEXT; no task
,10-27 02:40:31.018  3920  5841 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-27 02:40:31.018  3920  5841 I SystemUpdateService: now status is 0 (complete)
10-27 02:40:31.018  3920  5841 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-27 02:40:31.018  3920  5841 I SystemUpdateService: file has been verified
10-27 02:40:31.019  3920  5841 I SystemUpdateService: OTA package size = 21989297
,10-27 02:40:31.022  5811  5811 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-27 02:40:31.034  3920  5841 I SystemUpdateService: showing system update notification
,10-27 02:40:31.040   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-27 02:40:31.041  3920  3920 D SystemUpdateService: onDestroy
,10-27 02:40:31.126   928  3037 D wifi    : In wifi stop Hal
10-27 02:40:31.126   928  3037 D wifi    : halHandle = 0x7f6b116400, mVM = 0x7f8770d140, mCls = 0x1956
10-27 02:40:31.126   928  5810 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-27 02:40:31.126   928  5810 D WifiHAL : Got a signal to exit!!!
10-27 02:40:31.126   928  5810 I WifiHAL : Exit wifi_event_loop
10-27 02:40:31.127   928  3037 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,10-27 02:40:31.127   928  3037 E WifiHAL : Event processing terminated
10-27 02:40:31.127   928  3037 D wifi    : In wifi cleaned up handler
10-27 02:40:31.127   928  3037 I WifiHAL : Internal cleanup completed
,10-27 02:40:31.128  5081  5081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-27 02:40:31.129  4126  4272 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-27 02:40:31.129  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:31.130  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:31.132  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:31.149   928  5810 D wifi    : set interface wlan0 flags (DOWN)
,10-27 02:40:31.150   928  3037 D WifiNative-HAL: HAL event thread stopped successfully
,10-27 02:40:31.357   928   945 D Tethering: InitialState.processMessage what=4
,10-27 02:40:31.364   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-27 02:40:31.636   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-27 02:40:31.757   928  3039 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-27 02:40:35.917   928   945 I ActivityManager: Start proc 5847:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-27 02:40:36.026  5847  5847 D AdapterServiceConfig: Adding HeadsetService
,10-27 02:40:36.026  5847  5847 D AdapterServiceConfig: Adding A2dpService
10-27 02:40:36.026  5847  5847 D AdapterServiceConfig: Adding HidService
10-27 02:40:36.026  5847  5847 D AdapterServiceConfig: Adding HealthService
10-27 02:40:36.027  5847  5847 D AdapterServiceConfig: Adding PanService
,10-27 02:40:36.027  5847  5847 D AdapterServiceConfig: Adding GattService
10-27 02:40:36.027  5847  5847 D AdapterServiceConfig: Adding BluetoothMapService
10-27 02:40:36.027  5847  5847 D AdapterServiceConfig: Adding SapService
,10-27 02:40:36.037   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6421758:true
,10-27 02:40:36.038  5847  5847 D BluetoothAdapterState: make() - Creating AdapterState
,10-27 02:40:36.040  5847  5847 I bt_bluedroid: init
,10-27 02:40:36.040  5847  5859 I BluetoothAdapterState: Entering OffState
,10-27 02:40:36.042  5847  5860 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-27 02:40:36.042  5847  5860 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-27 02:40:36.043  5847  5860 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-27 02:40:36.043  5847  5860 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-27 02:40:36.043  5847  5847 I bt_bluedroid: get_profile_interface socket
,10-27 02:40:36.045  5847  5863 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-27 02:40:36.046  5847  5847 I bt_bluedroid: get_profile_interface sdp
10-27 02:40:36.047  5847  5863 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-27 02:40:36.050  5847  5858 I bt_bluedroid: config_hci_snoop_log
,10-27 02:40:36.051   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-27 02:40:36.057  5847  5859 D BluetoothAdapterState: Current state: OFF, message: 0
,10-27 02:40:36.057  5847  5859 D BluetoothAdapterProperties: Setting state to 14
10-27 02:40:36.057  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-27 02:40:36.059  5847  5859 D BluetoothBondStateMachine: make
,10-27 02:40:36.060  5847  5864 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-27 02:40:36.063  5847  5859 I BluetoothAdapterState: Entering PendingCommandState
,10-27 02:40:36.063  5847  5847 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-27 02:40:36.066  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
,10-27 02:40:36.066  5847  5847 D BtGatt.DebugUtils: handleDebugAction() action=null
10-27 02:40:36.067  5847  5847 D BtGatt.GattService: Received start request. Starting profile...
10-27 02:40:36.067  5847  5847 D BtGatt.GattService: start()
10-27 02:40:36.067  5847  5847 I bt_bluedroid: get_profile_interface gatt
10-27 02:40:36.067  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
10-27 02:40:36.067  5847  5847 D BtGatt.AdvertiseManager: advertise manager created
,10-27 02:40:36.072  5847  5847 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:36.072  5847  5847 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:36.072  5847  5847 V BluetoothAdapterState: isBleTurningOn()=true
10-27 02:40:36.072  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:36.072  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-27 02:40:36.073  5847  5859 I bt_bluedroid: bt_bluedroid
,10-27 02:40:36.073  5847  5860 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-27 02:40:36.074  5847  5860 I bt_hci  : start_up
,10-27 02:40:36.079  5847  5860 I bt_vendor: alloc value 0xf41d3871
10-27 02:40:36.079  5847  5860 I bt_vendor: init
,10-27 02:40:36.079  5847  5860 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-27 02:40:36.079  5847  5860 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-27 02:40:36.190  5847  5860 D bt_hci  : start_up starting async portion
10-27 02:40:36.190  5847  5867 I bt_hci  : event_finish_startup
,10-27 02:40:36.190  5847  5867 I bt_hci_h4: hal_open
,10-27 02:40:36.187  5868  5868 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-27 02:40:36.191  5847  5867 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-27 02:40:36.192  5847  5867 I bt_userial_vendor: device fd = 54 open
,10-27 02:40:36.204  5847  5867 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-27 02:40:36.206  5847  5867 D bt_hwcfg: Chipset BCM4358A3
,10-27 02:40:36.206  5847  5867 D bt_hwcfg: Target name = [BCM4358A3]
10-27 02:40:36.207  5847  5867 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-27 02:40:36.521  5847  5867 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-27 02:40:36.522  5847  5867 D bt_hwcfg: Settlement delay -- 100 ms
10-27 02:40:36.522  5847  5867 I bt_hwcfg: Setting fw settlement delay to 100 
,10-27 02:40:36.656  5847  5867 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-27 02:40:36.656  5847  5867 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
10-27 02:40:36.657  5847  5867 I bt_hwcfg: vendor lib fwcfg completed
10-27 02:40:36.658  5847  5867 I bt_vendor: firmware callback
10-27 02:40:36.658  5847  5867 I bt_hci  : firmware_config_callback
,10-27 02:40:36.667  5847  5870 I bt_btu  : btu_task pending for preload complete event
,10-27 02:40:36.667  5847  5870 I bt_btu_task: Bluetooth chip preload is complete
10-27 02:40:36.667  5847  5870 I bt_btu  : btu_task received preload complete event
,10-27 02:40:36.676  5847  5870 I         : BTE_InitTraceLevels -- TRC_HCI
,10-27 02:40:36.676  5847  5870 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-27 02:40:36.676  5847  5870 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-27 02:40:36.676  5847  5870 I         : BTE_InitTraceLevels -- TRC_AVDT
10-27 02:40:36.676  5847  5870 I         : BTE_InitTraceLevels -- TRC_AVRC
10-27 02:40:36.676  5847  5870 I         : BTE_InitTraceLevels -- TRC_A2D
10-27 02:40:36.676  5847  5870 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-27 02:40:36.676  5847  5870 I         : BTE_InitTraceLevels -- TRC_BTM
10-27 02:40:36.677  5847  5870 I         : BTE_InitTraceLevels -- TRC_GAP
10-27 02:40:36.677  5847  5870 I         : BTE_InitTraceLevels -- TRC_PAN
10-27 02:40:36.677  5847  5870 I         : BTE_InitTraceLevels -- TRC_SDP
10-27 02:40:36.677  5847  5870 I         : BTE_InitTraceLevels -- TRC_GATT
10-27 02:40:36.677  5847  5870 I         : BTE_InitTraceLevels -- TRC_SMP
10-27 02:40:36.677  5847  5870 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-27 02:40:36.677  5847  5870 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-27 02:40:36.762  5847  5870 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4151549
10-27 02:40:36.762  5847  5870 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4151549 
,10-27 02:40:36.783  5847  5863 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-27 02:40:36.784  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-27 02:40:36.785  5847  5863 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
10-27 02:40:36.787  5847  5863 D BluetoothAdapterProperties: Name is: Nexus 6P
10-27 02:40:36.790  5847  5863 D BluetoothAdapterProperties: Scan Mode:20
10-27 02:40:36.790  5847  5863 D BluetoothAdapterProperties: Discoverable Timeout:120
10-27 02:40:36.790  5847  5863 D bt_hci  : do_postload posting postload work item
10-27 02:40:36.790  5847  5867 I bt_hci  : event_postload
10-27 02:40:36.790  5847  5867 I bt_vendor: sco_config_cb
10-27 02:40:36.791  5847  5867 I bt_hci  : sco_config_callback postload finished.
10-27 02:40:36.795  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:36.796  5847  5863 D bt_bte_conf: Device ID record 1 : primary
,10-27 02:40:36.796  5847  5863 D bt_bte_conf:   vendorId            = 000f
10-27 02:40:36.796  5847  5863 D bt_bte_conf:   vendorIdSource      = 0001
10-27 02:40:36.796  5847  5863 D bt_bte_conf:   product             = 1200
,10-27 02:40:36.796  5847  5863 D bt_bte_conf:   version             = 1436
10-27 02:40:36.796  5847  5863 D bt_bte_conf:   clientExecutableURL = 
10-27 02:40:36.796  5847  5863 D bt_bte_conf:   serviceDescription  = 
10-27 02:40:36.797  5847  5863 D bt_bte_conf:   documentationURL    = 
10-27 02:40:36.797  5847  5863 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-27 02:40:36.797  5847  5860 D bt_stack_manager: event_start_up_stack finished
10-27 02:40:36.798  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-27 02:40:36.799  5847  5859 D BluetoothAdapterProperties: Setting state to 15
10-27 02:40:36.799  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-27 02:40:36.799  5847  5859 I BluetoothAdapterState: Entering BleOnState
10-27 02:40:36.800  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:36.800  5847  5867 I bt_vendor: low_power_mode_cb
10-27 02:40:36.803  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:36.804  5847  5859 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-27 02:40:36.804  5847  5859 D BluetoothAdapterProperties: Setting state to 11
10-27 02:40:36.804  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-27 02:40:36.810  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:36.812  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:36.814  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:36.816  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-27 02:40:36.816  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
,10-27 02:40:36.817  5847  5847 D HeadsetService: Received start request. Starting profile...
,10-27 02:40:36.821  5847  5847 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-27 02:40:36.821  5847  5847 D HeadsetStateMachine: make
,10-27 02:40:36.829  5847  5859 I BluetoothAdapterState: Entering PendingCommandState
,10-27 02:40:36.830  5847  5847 D HeadsetStateMachine: max_hf_connections = 1
10-27 02:40:36.830  5847  5847 I bt_bluedroid: get_profile_interface handsfree
,10-27 02:40:36.830  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-27 02:40:36.830  5847  5863 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-27 02:40:36.834  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
,10-27 02:40:36.834  5847  5847 D A2dpService: Received start request. Starting profile...
10-27 02:40:36.835  5847  5847 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-27 02:40:36.835  5847  5847 I bt_bluedroid: get_profile_interface avrcp
,10-27 02:40:36.842  5847  5847 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-27 02:40:36.843  5847  5847 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-27 02:40:36.843  5847  5847 D A2dpStateMachine: make
,10-27 02:40:36.845  5847  5847 I bt_bluedroid: get_profile_interface a2dp
,10-27 02:40:36.845  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-27 02:40:36.847  5847  5878 D A2dpStateMachine: Enter Disconnected: -2
10-27 02:40:36.847  5847  5847 I BluetoothHidServiceJni: classInitNative: succeeds
,10-27 02:40:36.848  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
10-27 02:40:36.850  5847  5847 D HidService: Received start request. Starting profile...
,10-27 02:40:36.850  5847  5847 I bt_bluedroid: get_profile_interface hidhost
10-27 02:40:36.850  5847  5847 D HidService: setHidService(): set to: null
10-27 02:40:36.850  5847  5863 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf413256d
10-27 02:40:36.850  5744  5744 D BluetoothInputDevice: Proxy object connected
10-27 02:40:36.850  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-27 02:40:36.850  5847  5847 I BluetoothHealthServiceJni: classInitNative: succeeds
10-27 02:40:36.851  5744  5744 D HidProfile: Bluetooth service connected
10-27 02:40:36.851  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
10-27 02:40:36.851  5847  5847 D HealthService: Received start request. Starting profile...
,10-27 02:40:36.853  5847  5847 I bt_bluedroid: get_profile_interface health
,10-27 02:40:36.853  5847  5847 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-27 02:40:36.854  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
,10-27 02:40:36.855  5744  5744 D BluetoothPan: BluetoothPAN Proxy object connected
,10-27 02:40:36.855  5744  5744 D PanProfile: Bluetooth service connected
10-27 02:40:36.856  5847  5847 D PanService: Received start request. Starting profile...
10-27 02:40:36.856  5847  5847 D BluetoothPanServiceJni: initializeNative(L110): pan
10-27 02:40:36.856  5847  5847 I bt_bluedroid: get_profile_interface pan
10-27 02:40:36.856  5847  5863 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-27 02:40:36.858  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
10-27 02:40:36.859  5744  5744 D BluetoothMap: Proxy object connected
10-27 02:40:36.859  5847  5847 D BluetoothMapService: Received start request. Starting profile...
10-27 02:40:36.859  5847  5847 D BluetoothMapService: start()
10-27 02:40:36.859  5744  5744 D MapProfile: Bluetooth service connected
10-27 02:40:36.859  5744  5744 D BluetoothMap: getConnectedDevices()
,10-27 02:40:36.860  5744  5744 D BluetoothMap: Bluetooth is Not enabled
,10-27 02:40:36.862  5847  5847 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-27 02:40:36.863  5847  5847 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-27 02:40:36.863  5847  5847 D BluetoothMapAppObserver: createReceiver()
10-27 02:40:36.864  5847  5847 D BluetoothMapAppObserver: initObservers()
10-27 02:40:36.864  5847  5847 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-27 02:40:36.870  5847  5847 V SapService: SapBinder()
,10-27 02:40:36.871  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
,10-27 02:40:36.871  5847  5847 D SapService: Received start request. Starting profile...
10-27 02:40:36.871  5847  5847 V SapService: start()
,10-27 02:40:36.873  5847  5847 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:36.873  5847  5847 V BluetoothAdapterState: isTurningOn()=true
10-27 02:40:36.873  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:36.873  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:36.873  5847  5847 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:36.873  5847  5847 V BluetoothAdapterState: isTurningOn()=true
10-27 02:40:36.873  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
,10-27 02:40:36.873  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isTurningOn()=true
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isTurningOn()=true
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isTurningOn()=true
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isTurningOn()=true
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:36.874  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:36.875  5847  5847 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:36.875  5847  5847 V BluetoothAdapterState: isTurningOn()=true
10-27 02:40:36.875  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:36.875  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:36.875  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-27 02:40:36.875  5847  5859 D BluetoothAdapterProperties: ScanMode =  20
10-27 02:40:36.875  5847  5859 D BluetoothAdapterProperties: State =  11
10-27 02:40:36.876  5847  5863 D BluetoothAdapterProperties: Scan Mode:21
10-27 02:40:36.877  5847  5863 D BluetoothAdapterProperties: Discoverable Timeout:120
10-27 02:40:36.877  5847  5859 D BluetoothAdapterProperties: Setting state to 12
10-27 02:40:36.877  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,10-27 02:40:36.877  5682  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-27 02:40:36.877  5847  5859 I BluetoothAdapterState: Entering OnState
10-27 02:40:36.877  3195  3428 D BluetoothMap: onBluetoothStateChange: up=true
,10-27 02:40:36.880  3195  3195 D BluetoothMap: Proxy object connected
,10-27 02:40:36.880  3195  3195 D MapProfile: Bluetooth service connected
10-27 02:40:36.880  3195  3195 D BluetoothMap: getConnectedDevices()
10-27 02:40:36.880  3842  4043 D BluetoothHeadset: onBluetoothStateChange: up=true
10-27 02:40:36.881   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-27 02:40:36.881  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:36.881  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:36.881  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:36.881  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:36.881  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:40:36.881  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:36.881  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:36.881  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-27 02:40:36.881  3195  3211 D BluetoothPbap: onBluetoothStateChange: up=true
10-27 02:40:36.882   928   928 D BluetoothA2dp: Proxy object connected
,10-27 02:40:36.884  5744  5755 D BluetoothPbap: onBluetoothStateChange: up=true
,10-27 02:40:36.886  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:36.886  3195  4040 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-27 02:40:36.887  3195  3195 D BluetoothInputDevice: Proxy object connected
,10-27 02:40:36.887  3195  3195 D HidProfile: Bluetooth service connected
10-27 02:40:36.888  5744  5758 D BluetoothMap: onBluetoothStateChange: up=true
10-27 02:40:36.888   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-27 02:40:36.888  3195  3428 D BluetoothHeadset: onBluetoothStateChange: up=true
10-27 02:40:36.888  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:36.888  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:36.888  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:36.888  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:36.888  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:40:36.888  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:36.888  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:36.888  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:36.888   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-27 02:40:36.889  5744  5755 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-27 02:40:36.889  5847  5847 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-27 02:40:36.889  3195  3207 D BluetoothA2dp: onBluetoothStateChange: up=true
10-27 02:40:36.889  5847  5847 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-27 02:40:36.890  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-27 02:40:36.890   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-27 02:40:36.890  3195  3195 D BluetoothA2dp: Proxy object connected
10-27 02:40:36.891  3195  3211 D BluetoothPan: onBluetoothStateChange on: true
10-27 02:40:36.891  5847  5847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-27 02:40:36.892  5744  5758 D BluetoothPan: onBluetoothStateChange on: true
10-27 02:40:36.892  5847  5847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-27 02:40:36.893   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,10-27 02:40:36.895  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:36.895  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:36.895  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:36.895  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:36.895  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:40:36.895  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:36.895  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:36.895  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-27 02:40:36.897  3195  3195 D BluetoothPan: BluetoothPAN Proxy object connected
,10-27 02:40:36.897  3195  3195 D PanProfile: Bluetooth service connected
10-27 02:40:36.897  5847  5847 D ObexServerSockets: Succeed to create listening sockets 
10-27 02:40:36.898  5847  5847 D ObexServerSockets0: startAccept()
10-27 02:40:36.898  5744  5744 D LocalBluetoothProfileManager: Adding local A2DP profile
10-27 02:40:36.898  5847  5847 D ObexServerSockets0: prepareForNewConnect()
,10-27 02:40:36.898  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:36.898  5682  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-27 02:40:36.899  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:36.900  5847  5847 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-27 02:40:36.900  5847  5847 D BluetoothSdpJni: SDP Create record success - handle: 0
10-27 02:40:36.901  5847  5886 D ObexServerSockets0: Accepting socket connection...
10-27 02:40:36.901  5847  5847 D BluetoothMapService: onReceive
10-27 02:40:36.901  5847  5847 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-27 02:40:36.901  5847  5847 D BluetoothMapService: STATE_ON
,10-27 02:40:36.901  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:36.901  5847  5887 D ObexServerSockets0: Accepting socket connection...
10-27 02:40:36.903  5847  5888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-27 02:40:36.903  5744  5744 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-27 02:40:36.903  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:36.904  5847  5888 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-27 02:40:36.904  5847  5888 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-27 02:40:36.909  5744  5744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-27 02:40:36.911  5744  5744 D BluetoothA2dp: Proxy object connected
,10-27 02:40:36.915  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-27 02:40:36.916  5744  5744 D DockEventReceiver: finishStartingService: stopping service
,10-27 02:40:36.922  5744  5744 D BluetoothPbap: Proxy object connected
,10-27 02:40:36.922  5744  5744 D PbapServerProfile: Bluetooth service connected
,10-27 02:40:36.926  5847  5847 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-27 02:40:36.926  5847  5847 D ObexServerSockets0: prepareForNewConnect()
,10-27 02:40:36.930  3195  3195 D BluetoothPbap: Proxy object connected
,10-27 02:40:36.930  3195  3195 D PbapServerProfile: Bluetooth service connected
,10-27 02:40:36.935  5847  5892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-27 02:40:36.943  5847  5896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-27 02:40:36.944  5847  5896 I BtOppRfcommListener: Accept thread started.
,10-27 02:40:36.982  3842  4053 D BluetoothHeadset: Proxy object connected
,10-27 02:40:36.982   928   928 D BluetoothHeadset: Proxy object connected
10-27 02:40:36.982   928   928 D BluetoothHeadset: Proxy object connected
,10-27 02:40:36.983  3195  4040 D BluetoothHeadset: Proxy object connected
10-27 02:40:36.983  3195  3195 D HeadsetProfile: Bluetooth service connected
10-27 02:40:36.983   928   928 D BluetoothHeadset: Proxy object connected
,10-27 02:40:36.988   928   945 D BluetoothHeadset: Proxy object connected
,10-27 02:40:36.989  3195  3428 D BluetoothHeadset: Proxy object connected
10-27 02:40:36.989  3195  3195 D HeadsetProfile: Bluetooth service connected
,10-27 02:40:36.989   928   945 D BluetoothHeadset: Proxy object connected
,10-27 02:40:36.991   928   945 D BluetoothHeadset: Proxy object connected
,10-27 02:40:37.005  5744  5758 D BluetoothHeadset: Proxy object connected
10-27 02:40:37.006  5744  5744 D HeadsetProfile: Bluetooth service connected
,10-27 02:40:38.229  3734  3788 I Keyboard.Facilitator.LanguageModelFlusher: run()
,10-27 02:40:38.229  3734  3788 I Keyboard.Facilitator: flushDynamicLanguageModels()
,10-27 02:40:38.257  3638  3638 I ConfigService: onCreate
,10-27 02:40:38.715   928  3039 D ConnectivityService: handlePromptUnvalidated 101
,10-27 02:40:40.894  5847  5859 D BluetoothAdapterState: Current state: ON, message: 23
,10-27 02:40:40.894  5847  5859 D BluetoothAdapterProperties: Setting state to 13
10-27 02:40:40.895  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-27 02:40:40.896  5847  5859 D BluetoothAdapterProperties: onBluetoothDisable()
,10-27 02:40:40.899  5847  5859 I BluetoothAdapterState: Entering PendingCommandState
,10-27 02:40:40.903  5847  5847 D BluetoothMapService: onReceive
10-27 02:40:40.903  5847  5847 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-27 02:40:40.903  5847  5847 D BluetoothMapService: STATE_TURNING_OFF
10-27 02:40:40.903  5847  5847 D BluetoothMapService: MAP Service closeService in
10-27 02:40:40.903  5847  5847 D BluetoothMapMasInstance0: MAP Service shutdown
10-27 02:40:40.904  5847  5847 D ObexServerSockets0: shutdown(block = true)
10-27 02:40:40.905  5847  5847 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-27 02:40:40.906  5847  5887 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-27 02:40:40.907  5847  5863 D BluetoothAdapterProperties: Scan Mode:20
10-27 02:40:40.907  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-27 02:40:40.909  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:40.909  5847  5872 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-27 02:40:40.909  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:40.909  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:40.909  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:40.909  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:40.909  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:40.909  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:40.909  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:40.909  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:40.910  5847  5847 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-27 02:40:40.910  5847  5886 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-27 02:40:40.912  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:40.912  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:40.916  5847  5847 D HeadsetService: Received stop request...Stopping profile...
10-27 02:40:40.917  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:40.917  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:40.917  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:40.917  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:40.917  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:40.917  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:40.917  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:40.917  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:40.917  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:40.919  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-27 02:40:40.919  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:40.921  3842  3859 D BluetoothHeadset: Proxy object disconnected
10-27 02:40:40.922  5847  5847 I BtOppRfcommListener: stopping Accept Thread
10-27 02:40:40.922  5847  5896 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-27 02:40:40.923  5847  5896 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-27 02:40:40.923  5744  5755 D BluetoothHeadset: Proxy object disconnected
10-27 02:40:40.923  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:40.923  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:40.923  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:40.923  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:40.923  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:40.923  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-27 02:40:40.923  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:40.923  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:40.923  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:40.924   928   928 D BluetoothHeadset: Proxy object disconnected
10-27 02:40:40.924   928   928 D BluetoothHeadset: Proxy object disconnected
10-27 02:40:40.924  3195  3428 D BluetoothHeadset: Proxy object disconnected
10-27 02:40:40.924   928   928 D BluetoothHeadset: Proxy object disconnected
10-27 02:40:40.925  5847  5847 D A2dpService: Received stop request...Stopping profile...
10-27 02:40:40.925  5682  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-27 02:40:40.925  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:40.925  5847  5878 D A2dpStateMachine: Exit Disconnected: -1
10-27 02:40:40.927  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:40.928   928   928 D BluetoothA2dp: Proxy object disconnected
10-27 02:40:40.929  5847  5847 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:40.929  5847  5847 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:40.929  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:40.929  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:40.930  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:40.930  5847  5847 D HidService: Received stop request...Stopping profile...
10-27 02:40:40.930  5847  5847 D HidService: Stopping Bluetooth HidService
10-27 02:40:40.931  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:40.932  5744  5744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-27 02:40:40.933  3195  3195 D HeadsetProfile: Bluetooth service disconnected
10-27 02:40:40.933  3195  3195 D BluetoothA2dp: Proxy object disconnected
10-27 02:40:40.934  3195  3195 D BluetoothInputDevice: Proxy object disconnected
10-27 02:40:40.934  3195  3195 D HidProfile: Bluetooth service disconnected
10-27 02:40:40.935  5744  5744 D HeadsetProfile: Bluetooth service disconnected
10-27 02:40:40.935  5744  5744 D BluetoothA2dp: Proxy object disconnected
10-27 02:40:40.935  5744  5744 D BluetoothInputDevice: Proxy object disconnected
,10-27 02:40:40.935  5744  5744 D HidProfile: Bluetooth service disconnected
10-27 02:40:40.936  5847  5847 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-27 02:40:40.936  5847  5847 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-27 02:40:40.936  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-27 02:40:40.937  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-27 02:40:40.937  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-27 02:40:40.937  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-27 02:40:40.937  5847  5863 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-27 02:40:40.937  5847  5847 D HealthService: Received stop request...Stopping profile...
,10-27 02:40:40.940  5847  5847 D PanService: Received stop request...Stopping profile...
10-27 02:40:40.941  3195  3195 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-27 02:40:40.941  3195  3195 D PanProfile: Bluetooth service disconnected
,10-27 02:40:40.947  5847  5847 D BluetoothMapService: Received stop request...Stopping profile...
,10-27 02:40:40.947  5847  5847 D BluetoothMapService: stop()
10-27 02:40:40.947  5847  5847 D BluetoothMapAppObserver: deinitObservers()
10-27 02:40:40.947  5847  5847 D BluetoothMapAppObserver: removeReceiver()
,10-27 02:40:40.948  5744  5744 D DockEventReceiver: finishStartingService: stopping service
10-27 02:40:40.949  3195  3195 D BluetoothMap: Proxy object disconnected
10-27 02:40:40.949  3195  3195 D MapProfile: Bluetooth service disconnected
10-27 02:40:40.949  5847  5847 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:40.949  5847  5847 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:40.949  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:40.949  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:40.949  5744  5744 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-27 02:40:40.949  5744  5744 D PanProfile: Bluetooth service disconnected
10-27 02:40:40.950  5744  5744 D BluetoothMap: Proxy object disconnected
10-27 02:40:40.950  5744  5744 D MapProfile: Bluetooth service disconnected
10-27 02:40:40.951  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-27 02:40:40.951  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-27 02:40:40.951  5847  5847 D SapService: Received stop request...Stopping profile...
10-27 02:40:40.951  5847  5847 V SapService: stop()
10-27 02:40:40.952  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-27 02:40:40.952  5847  5870 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-27 02:40:40.952  5847  5870 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-27 02:40:40.952  5847  5870 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-27 02:40:40.952  5847  5870 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-27 02:40:40.952  5847  5847 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:40.953  5847  5847 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:40.953  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:40.953  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:40.953  5847  5847 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-27 02:40:40.953  5847  5847 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-27 02:40:40.953  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-27 02:40:40.955  5847  5847 V BluetoothAdapterState: isTurningOff()=true
,10-27 02:40:40.955  5847  5847 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:40.955  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:40.955  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
,10-27 02:40:40.955  5847  5847 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,10-27 02:40:40.955  5847  5863 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-27 02:40:40.956  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-27 02:40:40.957  5847  5847 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-27 02:40:40.958  5847  5847 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:40.958  5847  5847 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:40.958  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:40.958  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:40.959  5847  5847 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-27 02:40:40.959  5847  5847 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-27 02:40:40.960  5847  5847 D BluetoothMapService: MAP Service closeService in
10-27 02:40:40.960  5847  5847 V BluetoothAdapterState: isTurningOff()=true
10-27 02:40:40.960  5847  5847 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:40.960  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:40.960  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:40.960  5847  5847 D BluetoothMapService: cleanup()
10-27 02:40:40.960  5847  5847 D BluetoothMapService: MAP Service closeService in
10-27 02:40:40.960  5847  5847 V BluetoothAdapterState: isTurningOff()=true
,10-27 02:40:40.960  5847  5847 V BluetoothAdapterState: isTurningOn()=false
,10-27 02:40:40.969  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:40.970  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:40.970  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-27 02:40:40.970  5847  5859 D BluetoothAdapterProperties: Setting state to 15
10-27 02:40:40.970  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-27 02:40:40.970  3195  3428 D BluetoothMap: onBluetoothStateChange: up=false
10-27 02:40:40.971  3195  3195 D BluetoothPbap: Proxy object disconnected
10-27 02:40:40.971  3195  3195 D PbapServerProfile: Bluetooth service disconnected
10-27 02:40:40.971  5744  5744 D BluetoothPbap: Proxy object disconnected
10-27 02:40:40.971  5744  5744 D PbapServerProfile: Bluetooth service disconnected
10-27 02:40:40.972  3842  3860 D BluetoothHeadset: onBluetoothStateChange: up=false
10-27 02:40:40.972   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-27 02:40:40.974  5744  5758 D BluetoothHeadset: onBluetoothStateChange: up=false
10-27 02:40:40.975  5744  5755 D BluetoothA2dp: onBluetoothStateChange: up=false
10-27 02:40:40.975  3195  3211 D BluetoothPbap: onBluetoothStateChange: up=false
10-27 02:40:40.976  5744  5758 D BluetoothPbap: onBluetoothStateChange: up=false
10-27 02:40:40.976  5847  5859 I BluetoothAdapterState: Entering BleOnState
10-27 02:40:40.976  3195  3207 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-27 02:40:40.977  5744  5755 D BluetoothMap: onBluetoothStateChange: up=false
10-27 02:40:40.977   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-27 02:40:40.978  3195  3428 D BluetoothHeadset: onBluetoothStateChange: up=false
10-27 02:40:40.978   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-27 02:40:40.978  5744  5758 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-27 02:40:40.979  3195  4040 D BluetoothA2dp: onBluetoothStateChange: up=false
10-27 02:40:40.979   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-27 02:40:40.979  3195  3211 D BluetoothPan: onBluetoothStateChange on: false
10-27 02:40:40.980  5744  5755 D BluetoothPan: onBluetoothStateChange on: false
10-27 02:40:40.981  5847  5859 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-27 02:40:40.981  5847  5859 D BluetoothAdapterProperties: Setting state to 16
10-27 02:40:40.981  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-27 02:40:40.981  5847  5859 D BluetoothAdapterProperties: onBleDisable
10-27 02:40:40.982  5847  5859 I BluetoothAdapterState: Entering PendingCommandState
10-27 02:40:40.982  5847  5860 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,10-27 02:40:40.983  5847  5870 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-27 02:40:40.984  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-27 02:40:40.984  5744  5744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-27 02:40:40.985  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:40.986  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:40.987  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:40.988  5847  5863 D BluetoothAdapterProperties: Scan Mode:20
10-27 02:40:40.988  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:40.989  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:40.990  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-27 02:40:40.990  5744  5744 D DockEventReceiver: finishStartingService: stopping service
10-27 02:40:40.991  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:41.202  5847  5863 I bt_hci  : shut_down
,10-27 02:40:41.213  5847  5867 D bt_hwcfg: hw_epilog_process
,10-27 02:40:41.214  5847  5867 I bt_vendor: low_power_mode_cb
,10-27 02:40:41.217  5847  5867 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-27 02:40:41.217  5847  5867 I bt_vendor: epilog_cb
10-27 02:40:41.217  5847  5867 I bt_hci  : epilog_finished_callback
,10-27 02:40:41.222  5847  5863 I bt_hci_h4: hal_close
,10-27 02:40:41.223  5847  5863 I bt_userial_vendor: device fd = 54 close
,10-27 02:40:41.349  5847  5860 D bt_stack_manager: event_shut_down_stack finished.
,10-27 02:40:41.350  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-27 02:40:41.354  5847  5859 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-27 02:40:41.354  5847  5847 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-27 02:40:41.355  5847  5847 D BtGatt.GattService: Received stop request...Stopping profile...
,10-27 02:40:41.356  5847  5847 D BtGatt.GattService: stop()
10-27 02:40:41.356  5847  5847 D BtGatt.AdvertiseManager: advertise clients cleared
10-27 02:40:41.359  5847  5847 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:41.359  5847  5847 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:41.359  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:41.359  5847  5847 V BluetoothAdapterState: isBleTurningOff()=true
10-27 02:40:41.360  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-27 02:40:41.360  5847  5859 D BluetoothAdapterProperties: Setting state to 10
10-27 02:40:41.360  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,10-27 02:40:41.361  5847  5859 I BluetoothAdapterState: Entering OffState
,10-27 02:40:41.363   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-27 02:40:41.375  5847  5847 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-27 02:40:41.376  5847  5847 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,10-27 02:40:41.376  5847  5847 I BluetoothServiceJni: cleanupNative: return from cleanup
10-27 02:40:41.378  5847  5860 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-27 02:40:41.384  5847  5847 I art     : System.exit called, status: 0
,10-27 02:40:41.384  5847  5847 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-27 02:40:41.414   928  3869 I ActivityManager: Process com.android.bluetooth (pid 5847) has died
,10-27 02:40:41.637   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:42.637   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:43.285  3638  3638 I ConfigService: onDestroy
,10-27 02:40:43.640   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:44.640   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:45.642   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:40:45.892  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
,10-27 02:40:45.892  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:45.897  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:45.897  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b92ad47 removed from the list
,10-27 02:40:45.898  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:45.898  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:45.898  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:40:45.900  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-27 02:40:45.900  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42fde9d added. We now have 4 listener(s)
10-27 02:40:45.901  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-27 02:40:45.903  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:40:45.903  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42fde9d removed from the list
,10-27 02:40:45.903  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:45.903  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:45.904  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:45.906  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:40:45.906  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a3cf12 added. We now have 4 listener(s)
,10-27 02:40:45.906  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-27 02:40:46.642   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-27 02:40:50.685   928   948 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,10-27 02:40:50.691   939   939 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[28581]" dev="sockfs" ino=28581 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:40:50.694   939   939 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28581]" dev="sockfs" ino=28581 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:40:50.699  3734  3734 I Keyboard.Facilitator: onFinishInput()
,10-27 02:40:50.710   928   948 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-27 02:40:50.710   928   948 I Adreno  : Build Date                       : 12/06/15
10-27 02:40:50.710   928   948 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-27 02:40:50.710   928   948 I Adreno  : Local Branch                     : mybranch17112971
10-27 02:40:50.710   928   948 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-27 02:40:50.710   928   948 I Adreno  : Remote Branch                    : NONE
10-27 02:40:50.710   928   948 I Adreno  : Reconstruct Branch               : NOTHING
,10-27 02:40:50.744   381   951 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (151 us)
,10-27 02:40:50.915  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:50.937   928   945 I ActivityManager: Start proc 5906:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-27 02:40:50.987  5906  5906 D AdapterServiceConfig: Adding HeadsetService
10-27 02:40:50.988  5906  5906 D AdapterServiceConfig: Adding A2dpService
10-27 02:40:50.988  5906  5906 D AdapterServiceConfig: Adding HidService
10-27 02:40:50.988  5906  5906 D AdapterServiceConfig: Adding HealthService
10-27 02:40:50.988  5906  5906 D AdapterServiceConfig: Adding PanService
10-27 02:40:50.988  5906  5906 D AdapterServiceConfig: Adding GattService
,10-27 02:40:50.988  5906  5906 D AdapterServiceConfig: Adding BluetoothMapService
10-27 02:40:50.988  5906  5906 D AdapterServiceConfig: Adding SapService
,10-27 02:40:50.997   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4377773:true
,10-27 02:40:50.997  5906  5906 D BluetoothAdapterState: make() - Creating AdapterState
,10-27 02:40:51.000  5906  5906 I bt_bluedroid: init
,10-27 02:40:51.000  5906  5918 I BluetoothAdapterState: Entering OffState
,10-27 02:40:51.002  5906  5919 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-27 02:40:51.002  5906  5919 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-27 02:40:51.002  5906  5919 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-27 02:40:51.003  5906  5919 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-27 02:40:51.003  5906  5906 I bt_bluedroid: get_profile_interface socket
,10-27 02:40:51.005  5906  5922 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-27 02:40:51.005  5906  5906 I bt_bluedroid: get_profile_interface sdp
10-27 02:40:51.006  5906  5922 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-27 02:40:51.009  5906  5917 I bt_bluedroid: config_hci_snoop_log
10-27 02:40:51.010   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-27 02:40:51.014  5906  5918 D BluetoothAdapterState: Current state: OFF, message: 0
10-27 02:40:51.015  5906  5918 D BluetoothAdapterProperties: Setting state to 14
,10-27 02:40:51.015  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-27 02:40:51.016  5906  5918 D BluetoothBondStateMachine: make
,10-27 02:40:51.017  5906  5923 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-27 02:40:51.020  5906  5918 I BluetoothAdapterState: Entering PendingCommandState
,10-27 02:40:51.021  5906  5906 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-27 02:40:51.023  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
10-27 02:40:51.023  5906  5906 D BtGatt.DebugUtils: handleDebugAction() action=null
10-27 02:40:51.024  5906  5906 D BtGatt.GattService: Received start request. Starting profile...
10-27 02:40:51.024  5906  5906 D BtGatt.GattService: start()
10-27 02:40:51.024  5906  5906 I bt_bluedroid: get_profile_interface gatt
10-27 02:40:51.025  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
10-27 02:40:51.025  5906  5906 D BtGatt.AdvertiseManager: advertise manager created
,10-27 02:40:51.030  5906  5906 V BluetoothAdapterState: isTurningOff()=false
,10-27 02:40:51.031  5906  5906 V BluetoothAdapterState: isTurningOn()=false
10-27 02:40:51.031  5906  5906 V BluetoothAdapterState: isBleTurningOn()=true
10-27 02:40:51.031  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:51.031  5906  5918 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-27 02:40:51.032  5906  5918 I bt_bluedroid: bt_bluedroid
10-27 02:40:51.032  5906  5919 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-27 02:40:51.033  5906  5919 I bt_hci  : start_up
,10-27 02:40:51.037  5906  5919 I bt_vendor: alloc value 0xf41d3871
,10-27 02:40:51.038  5906  5919 I bt_vendor: init
10-27 02:40:51.038  5906  5919 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-27 02:40:51.038  5906  5919 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-27 02:40:51.147  5906  5919 D bt_hci  : start_up starting async portion
10-27 02:40:51.147  5906  5926 I bt_hci  : event_finish_startup
,10-27 02:40:51.147  5906  5926 I bt_hci_h4: hal_open
10-27 02:40:51.147  5906  5926 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-27 02:40:51.150  5906  5926 I bt_userial_vendor: device fd = 54 open
,10-27 02:40:51.147  5927  5927 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-27 02:40:51.164  5906  5926 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-27 02:40:51.167  5906  5926 D bt_hwcfg: Chipset BCM4358A3
,10-27 02:40:51.167  5906  5926 D bt_hwcfg: Target name = [BCM4358A3]
10-27 02:40:51.167  5906  5926 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-27 02:40:51.397  5682  5682 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
10-27 02:40:51.397  5682  5682 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,10-27 02:40:51.429   928   948 I sensors : batch
,10-27 02:40:51.430   928   948 V KeyguardServiceDelegate: onScreenTurnedOff()
,10-27 02:40:51.433  5682  5682 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@900f35a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c2d6e3, 16908290=android.view.AbsSavedState$1@c2d6e3}, android:focusedViewId=100}]}]
,10-27 02:40:51.433  5682  5682 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
10-27 02:40:51.433  5682  5682 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,10-27 02:40:51.434  5682  5682 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
10-27 02:40:51.434   928   948 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
10-27 02:40:51.434   928   948 I sensors : activate
10-27 02:40:51.435   381   381 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7faa043c00
10-27 02:40:51.435   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
10-27 02:40:51.436   928   946 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
10-27 02:40:51.438   928  2829 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
10-27 02:40:51.441   928  2829 I hubconnection: sensorhub said: 'activate 7 enable:0'
,10-27 02:40:51.632  5906  5926 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-27 02:40:51.632  5906  5926 D bt_hwcfg: Settlement delay -- 100 ms
10-27 02:40:51.632  5906  5926 I bt_hwcfg: Setting fw settlement delay to 100 
,10-27 02:40:51.747   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,10-27 02:40:51.751   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,10-27 02:40:51.753   928  3151 D SurfaceControl: Excessive delay in setPowerMode(): 317ms
,10-27 02:40:51.762   928   948 I DreamManagerService: Entering dreamland.
10-27 02:40:51.762   928   948 I PowerManagerService: Dozing...
,10-27 02:40:51.763   928   943 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,10-27 02:40:51.767  5906  5926 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-27 02:40:51.768  5906  5926 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
10-27 02:40:51.770  5906  5926 I bt_hwcfg: vendor lib fwcfg completed
,10-27 02:40:51.770  5906  5926 I bt_vendor: firmware callback
10-27 02:40:51.770  5906  5926 I bt_hci  : firmware_config_callback
,10-27 02:40:51.779  5906  5929 I bt_btu  : btu_task pending for preload complete event
10-27 02:40:51.779  5906  5929 I bt_btu_task: Bluetooth chip preload is complete
,10-27 02:40:51.779  5906  5929 I bt_btu  : btu_task received preload complete event
,10-27 02:40:51.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_HCI,
10-27 02:40:51.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-27 02:40:51.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-27 02:40:51.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_AVDT
10-27 02:40:51.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_AVRC
10-27 02:40:51.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_A2D
10-27 02:40:51.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_BNEP
10-27 02:40:51.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_BTM
10-27 02:40:51.784  5906  5929 I         : BTE_InitTraceLevels -- TRC_GAP
10-27 02:40:51.784  5906  5929 I         : BTE_InitTraceLevels -- TRC_PAN
10-27 02:40:51.784  5906  5929 I         : BTE_InitTraceLevels -- TRC_SDP
10-27 02:40:51.784  5906  5929 I         : BTE_InitTraceLevels -- TRC_GATT
10-27 02:40:51.784  5906  5929 I         : BTE_InitTraceLevels -- TRC_SMP
10-27 02:40:51.784  5906  5929 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-27 02:40:51.784  5906  5929 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-27 02:40:51.797   938   938 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33242]" dev="sockfs" ino=33242 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:40:51.797   938   938 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33242]" dev="sockfs" ino=33242 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:40:51.799   928  3869 I sensors : batch
,10-27 02:40:51.800   928  3869 I sensors : activate
,10-27 02:40:51.803   928  2829 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,10-27 02:40:51.805   928  2829 I hubconnection: sensorhub said: 'activate 21 enable:1'
,10-27 02:40:51.810   512  3087 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,10-27 02:40:51.843  3842  4807 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,10-27 02:40:51.843  3842  4807 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-27 02:40:51.843  3842  4807 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-27 02:40:51.844   525  1434 D         : oem-qmi: Connection accepted
10-27 02:40:51.844   525  1434 D         : oem-qmi: Waiting to accept connection
,10-27 02:40:51.851  3842  4807 D         : oem_qmi_lib:output 0
,10-27 02:40:51.851   928   928 I sensors : activate
,10-27 02:40:51.852  3842  4807 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-27 02:40:51.852   512  3088 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,10-27 02:40:51.855   928  2829 I hubconnection: sensorhub said: 'activate 31 enable:0'
,10-27 02:40:51.870  5906  5929 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4151549
,10-27 02:40:51.871  5906  5929 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4151549 
,10-27 02:40:51.894  5906  5922 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-27 02:40:51.897  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-27 02:40:51.897  5906  5922 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-27 02:40:51.899  5906  5922 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-27 02:40:51.902  5906  5922 D BluetoothAdapterProperties: Scan Mode:20
,10-27 02:40:51.902  5906  5922 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-27 02:40:51.902  5906  5922 D bt_hci  : do_postload posting postload work item
10-27 02:40:51.902  5906  5926 I bt_hci  : event_postload
10-27 02:40:51.902  5906  5926 I bt_vendor: sco_config_cb
10-27 02:40:51.902  5906  5926 I bt_hci  : sco_config_callback postload finished.
10-27 02:40:51.904  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:51.905  5906  5922 D bt_bte_conf: Device ID record 1 : primary
10-27 02:40:51.906  5906  5922 D bt_bte_conf:   vendorId            = 000f
10-27 02:40:51.906  5906  5922 D bt_bte_conf:   vendorIdSource      = 0001
10-27 02:40:51.906  5906  5922 D bt_bte_conf:   product             = 1200
10-27 02:40:51.906  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:51.906  5906  5922 D bt_bte_conf:   version             = 1436
10-27 02:40:51.906  5906  5922 D bt_bte_conf:   clientExecutableURL = 
10-27 02:40:51.906  5906  5922 D bt_bte_conf:   serviceDescription  = 
10-27 02:40:51.906  5906  5922 D bt_bte_conf:   documentationURL    = 
10-27 02:40:51.906  5906  5922 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-27 02:40:51.906  5906  5919 D bt_stack_manager: event_start_up_stack finished
10-27 02:40:51.907  5906  5918 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-27 02:40:51.907  3842  4807 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
10-27 02:40:51.907  3842  4807 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-27 02:40:51.907  5906  5918 D BluetoothAdapterProperties: Setting state to 15
10-27 02:40:51.907  3842  4807 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-27 02:40:51.907  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-27 02:40:51.908   525  1434 D         : oem-qmi: Connection accepted
10-27 02:40:51.908   525  1434 D         : oem-qmi: Waiting to accept connection
10-27 02:40:51.909  5906  5918 I BluetoothAdapterState: Entering BleOnState
,10-27 02:40:51.911  5906  5918 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-27 02:40:51.911  5906  5918 D BluetoothAdapterProperties: Setting state to 11
10-27 02:40:51.911  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-27 02:40:51.918  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
10-27 02:40:51.918  3842  4807 D         : oem_qmi_lib:output 0
10-27 02:40:51.918  3842  4807 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-27 02:40:51.919  5906  5906 D HeadsetService: Received start request. Starting profile...
,10-27 02:40:51.922  5906  5906 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-27 02:40:51.922  5906  5906 D HeadsetStateMachine: make
10-27 02:40:51.922  5906  5926 I bt_vendor: low_power_mode_cb
,10-27 02:40:51.928  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:40:51.929  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:51.930  5906  5918 I BluetoothAdapterState: Entering PendingCommandState
,10-27 02:40:51.934  5906  5906 D HeadsetStateMachine: max_hf_connections = 1
10-27 02:40:51.934  5906  5906 I bt_bluedroid: get_profile_interface handsfree
,10-27 02:40:51.934  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-27 02:40:51.935  5906  5922 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-27 02:40:51.937  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
,10-27 02:40:51.938  5906  5906 D A2dpService: Received start request. Starting profile...
10-27 02:40:51.939  5906  5906 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-27 02:40:51.939  5906  5906 I bt_bluedroid: get_profile_interface avrcp
,10-27 02:40:51.944  5906  5906 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-27 02:40:51.944  5906  5906 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-27 02:40:51.944  5906  5906 D A2dpStateMachine: make
10-27 02:40:51.946  5906  5906 I bt_bluedroid: get_profile_interface a2dp
10-27 02:40:51.946  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-27 02:40:51.947  5906  5941 D A2dpStateMachine: Enter Disconnected: -2
,10-27 02:40:51.948  5906  5906 I BluetoothHidServiceJni: classInitNative: succeeds
10-27 02:40:51.948  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
,10-27 02:40:51.950  5906  5906 D HidService: Received start request. Starting profile...
10-27 02:40:51.950  5906  5906 I bt_bluedroid: get_profile_interface hidhost
10-27 02:40:51.950  5906  5922 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf413256d
10-27 02:40:51.950  5906  5906 D HidService: setHidService(): set to: null
,10-27 02:40:51.950  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-27 02:40:51.951  5906  5906 I BluetoothHealthServiceJni: classInitNative: succeeds
10-27 02:40:51.952  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
10-27 02:40:51.952  5906  5906 D HealthService: Received start request. Starting profile...
,10-27 02:40:51.954  5906  5906 I bt_bluedroid: get_profile_interface health
10-27 02:40:51.954  5906  5906 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-27 02:40:51.955  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
,10-27 02:40:51.955  5906  5906 D PanService: Received start request. Starting profile...
,10-27 02:40:51.956  5906  5906 D BluetoothPanServiceJni: initializeNative(L110): pan
10-27 02:40:51.956  5906  5906 I bt_bluedroid: get_profile_interface pan
10-27 02:40:51.956  5906  5922 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-27 02:40:51.958  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
10-27 02:40:51.958  5906  5906 D BluetoothMapService: Received start request. Starting profile...
10-27 02:40:51.958  5906  5906 D BluetoothMapService: start()
10-27 02:40:51.960  5906  5906 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-27 02:40:51.961  5906  5906 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-27 02:40:51.961  5906  5906 D BluetoothMapAppObserver: createReceiver()
,10-27 02:40:51.962  5906  5906 D BluetoothMapAppObserver: initObservers()
,10-27 02:40:51.962  5906  5906 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-27 02:40:51.967  5906  5906 V SapService: SapBinder()
10-27 02:40:51.968  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
,10-27 02:40:51.968  5906  5906 D SapService: Received start request. Starting profile...
10-27 02:40:51.968  5906  5906 V SapService: start()
10-27 02:40:51.971  5906  5906 V BluetoothAdapterState: isTurningOff()=false
,10-27 02:40:51.971  5906  5906 V BluetoothAdapterState: isTurningOn()=true
10-27 02:40:51.971  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:51.971  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
,10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isTurningOn()=true
,10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
,10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isTurningOn()=true
,10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isTurningOn()=true
,10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
,10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:51.972  5906  5906 V BluetoothAdapterState: isTurningOn()=true
10-27 02:40:51.973  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:51.973  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:51.973  5906  5906 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:51.973  5906  5906 V BluetoothAdapterState: isTurningOn()=true
,10-27 02:40:51.973  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:51.973  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:51.973  5906  5906 V BluetoothAdapterState: isTurningOff()=false
10-27 02:40:51.973  5906  5906 V BluetoothAdapterState: isTurningOn()=true
10-27 02:40:51.973  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
10-27 02:40:51.973  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
10-27 02:40:51.974  5906  5918 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-27 02:40:51.974  5906  5918 D BluetoothAdapterProperties: ScanMode =  20
,10-27 02:40:51.974  5906  5918 D BluetoothAdapterProperties: State =  11
10-27 02:40:51.976  5906  5922 D BluetoothAdapterProperties: Scan Mode:21
10-27 02:40:51.976  5906  5922 D BluetoothAdapterProperties: Discoverable Timeout:120
10-27 02:40:51.976  5906  5918 D BluetoothAdapterProperties: Setting state to 12
10-27 02:40:51.976  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-27 02:40:51.976  5682  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-27 02:40:51.977  5906  5918 I BluetoothAdapterState: Entering OnState
,10-27 02:40:51.977  3195  3428 D BluetoothMap: onBluetoothStateChange: up=true
10-27 02:40:51.979  3842  4043 D BluetoothHeadset: onBluetoothStateChange: up=true
10-27 02:40:51.979  3195  3195 D BluetoothMap: Proxy object connected
10-27 02:40:51.979  3195  3195 D MapProfile: Bluetooth service connected
10-27 02:40:51.979  3195  3195 D BluetoothMap: getConnectedDevices()
10-27 02:40:51.979   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-27 02:40:51.980  5744  5758 D BluetoothHeadset: onBluetoothStateChange: up=true
10-27 02:40:51.981  5744  5755 D BluetoothA2dp: onBluetoothStateChange: up=true
10-27 02:40:51.981  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:51.981  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:51.981  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:51.981  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:51.981  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:40:51.981  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:51.981  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:51.981  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:51.982   928   928 D BluetoothA2dp: Proxy object connected
10-27 02:40:51.983  3195  3207 D BluetoothPbap: onBluetoothStateChange: up=true
,10-27 02:40:51.984  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-27 02:40:51.985  5744  5758 D BluetoothPbap: onBluetoothStateChange: up=true
,10-27 02:40:51.986  3195  3211 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-27 02:40:51.986  5906  5906 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-27 02:40:51.987  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:51.987  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:51.987  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:51.987  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:51.987  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:40:51.987  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:51.987  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:51.987  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:40:51.987  5906  5906 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-27 02:40:51.988  5744  5755 D BluetoothMap: onBluetoothStateChange: up=true
10-27 02:40:51.988  5906  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-27 02:40:51.989   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-27 02:40:51.990  3195  3428 D BluetoothHeadset: onBluetoothStateChange: up=true
10-27 02:40:51.990  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:51.990   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-27 02:40:51.990  5744  5758 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-27 02:40:51.991  5906  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-27 02:40:51.992  5744  5744 D BluetoothA2dp: Proxy object connected
10-27 02:40:51.992  3195  4040 D BluetoothA2dp: onBluetoothStateChange: up=true
10-27 02:40:51.992  5906  5906 D ObexServerSockets: Succeed to create listening sockets 
10-27 02:40:51.993  5906  5906 D ObexServerSockets0: startAccept()
10-27 02:40:51.993  5906  5906 D ObexServerSockets0: prepareForNewConnect()
,10-27 02:40:51.994   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-27 02:40:51.994  3195  3195 D BluetoothA2dp: Proxy object connected
10-27 02:40:51.994  3195  3211 D BluetoothPan: onBluetoothStateChange on: true
10-27 02:40:51.994  5906  5906 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-27 02:40:51.994  5906  5906 D BluetoothSdpJni: SDP Create record success - handle: 0
10-27 02:40:51.995  5906  5949 D ObexServerSockets0: Accepting socket connection...
10-27 02:40:51.996  3195  3195 D BluetoothInputDevice: Proxy object connected
10-27 02:40:51.996  3195  3195 D HidProfile: Bluetooth service connected
10-27 02:40:51.996  5906  5950 D ObexServerSockets0: Accepting socket connection...
,10-27 02:40:51.996  5744  5744 D BluetoothMap: Proxy object connected
10-27 02:40:51.997  5744  5744 D MapProfile: Bluetooth service connected
10-27 02:40:51.997  5744  5758 D BluetoothPan: onBluetoothStateChange on: true
10-27 02:40:51.997  5744  5744 D BluetoothMap: getConnectedDevices()
10-27 02:40:51.998  3195  3195 D BluetoothPan: BluetoothPAN Proxy object connected
10-27 02:40:51.998  3195  3195 D PanProfile: Bluetooth service connected
10-27 02:40:52.000   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-27 02:40:52.001  5682  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-27 02:40:52.001  5906  5906 D BluetoothMapService: onReceive
10-27 02:40:52.002  5906  5906 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-27 02:40:52.002  5906  5906 D BluetoothMapService: STATE_ON
,10-27 02:40:52.002  5744  5744 D BluetoothInputDevice: Proxy object connected
10-27 02:40:52.002  5744  5744 D HidProfile: Bluetooth service connected
10-27 02:40:52.003  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:52.004  5744  5744 D BluetoothPan: BluetoothPAN Proxy object connected
,10-27 02:40:52.004  5744  5744 D PanProfile: Bluetooth service connected
10-27 02:40:52.005  5906  5951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-27 02:40:52.005  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:40:52.007  5906  5951 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-27 02:40:52.007  5906  5951 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-27 02:40:52.010  5744  5744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-27 02:40:52.017  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-27 02:40:52.017  5744  5744 D DockEventReceiver: finishStartingService: stopping service
,10-27 02:40:52.023  5744  5744 D BluetoothPbap: Proxy object connected
,10-27 02:40:52.023  5744  5744 D PbapServerProfile: Bluetooth service connected
,10-27 02:40:52.028  5906  5906 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-27 02:40:52.028  5906  5906 D ObexServerSockets0: prepareForNewConnect()
,10-27 02:40:52.031  5906  5956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-27 02:40:52.033  3195  3195 D BluetoothPbap: Proxy object connected
10-27 02:40:52.033  3195  3195 D PbapServerProfile: Bluetooth service connected
,10-27 02:40:52.047  5906  5960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-27 02:40:52.048  5906  5960 I BtOppRfcommListener: Accept thread started.
,10-27 02:40:52.081  5744  5755 D BluetoothHeadset: Proxy object connected
,10-27 02:40:52.081  3842  4053 D BluetoothHeadset: Proxy object connected
10-27 02:40:52.081  5744  5948 D BluetoothHeadset: Proxy object connected
10-27 02:40:52.082   928   928 D BluetoothHeadset: Proxy object connected
,10-27 02:40:52.082   928   928 D BluetoothHeadset: Proxy object connected
10-27 02:40:52.082  3195  4040 D BluetoothHeadset: Proxy object connected
10-27 02:40:52.082   928   928 D BluetoothHeadset: Proxy object connected
10-27 02:40:52.082  3195  3195 D HeadsetProfile: Bluetooth service connected
,10-27 02:40:52.083  5744  5744 D HeadsetProfile: Bluetooth service connected
,10-27 02:40:52.085  5744  5744 D HeadsetProfile: Bluetooth service connected
,10-27 02:40:52.091   928   945 D BluetoothHeadset: Proxy object connected
10-27 02:40:52.091  3195  3207 D BluetoothHeadset: Proxy object connected
,10-27 02:40:52.091   928   945 D BluetoothHeadset: Proxy object connected
10-27 02:40:52.091  3195  3195 D HeadsetProfile: Bluetooth service connected
,10-27 02:40:52.094   928   945 D BluetoothHeadset: Proxy object connected
,10-27 02:40:55.790  4126  4528 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,10-27 02:40:55.928  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:40:55.928  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:40:55.928  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:40:55.928  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-27 02:40:55.928  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:40:55.928  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:40:55.928  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:40:55.928  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-27 02:40:55.932  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-27 02:40:55.933  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:40:55.933  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a3cf12 removed from the list
10-27 02:40:55.933  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:40:55.933  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:40:55.934  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:40:55.937  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-27 02:40:55.937  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@700d8e0 added. We now have 4 listener(s)
10-27 02:40:55.937  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-27 02:40:55.939   928   938 D WifiService: setWifiEnabled: false pid=5682, uid=10077
,10-27 02:40:55.940   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-27 02:41:00.948  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:41:00.950   928  3653 D WifiService: setWifiEnabled: true pid=5682, uid=10077
10-27 02:41:00.950   928  3653 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-27 02:41:00.961   507   920 D SoftapController: Softap fwReload - Ok
,10-27 02:41:00.968   507   920 D CommandListener: Setting iface cfg
,10-27 02:41:00.968   507   920 D CommandListener: Trying to bring down wlan0
,10-27 02:41:00.970   507   920 D CommandListener: Clearing all IP addresses on wlan0
,10-27 02:41:00.977   928  3037 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-27 02:41:01.644   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:41:01.647   928  3037 D wifi    : set interface wlan0 flags (UP)
,10-27 02:41:01.647   928  3037 I WifiHAL : Initializing wifi
,10-27 02:41:01.647   928  3037 I WifiHAL : Creating socket
,10-27 02:41:01.653   928  3037 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-27 02:41:01.653   928  3037 D wifi    : Did set static halHandle = 0x7f6b116400
10-27 02:41:01.654   928  3037 D wifi    : halHandle = 0x7f6b116400, mVM = 0x7f8770d140, mCls = 0x10163e
,10-27 02:41:01.654   928  3037 D wifi    : array field set
10-27 02:41:01.654   928  3037 I WifiNative-HAL: interface[0] = wlan0
10-27 02:41:01.658   928  5965 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547257148416
10-27 02:41:01.658   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-27 02:41:01.658   928  5965 D wifi    : waitForHalEvents called, vm = 0x7f8770d140, obj = 0x10163e, env = 0x7f70d7e8c0
,10-27 02:41:01.707  5966  5966 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-27 02:41:01.760   928  3037 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-27 02:41:01.770  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:41:01.772  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:41:01.778  5966  5966 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-27 02:41:01.824  5966  5966 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-27 02:41:01.825  5966  5966 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-27 02:41:01.843   928  3037 D WifiConfigStore: Loading config and enabling all networks 
,10-27 02:41:01.846  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:41:01.846  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:41:01.846  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:41:01.846  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:41:01.846  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:41:01.846  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:41:01.846  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:41:01.846  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:41:01.848  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-27 02:41:01.851  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:41:01.851  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:41:01.851  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:41:01.851  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:41:01.851  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:41:01.851  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-27 02:41:01.851  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-27 02:41:01.851  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-27 02:41:01.853  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-27 02:41:01.880   928  3037 D WifiConfigStore: loaded 0 passpoint configs
10-27 02:41:01.880   928  3037 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
10-27 02:41:01.881   928  3037 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-27 02:41:01.881   928  3037 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-27 02:41:01.881   928  3037 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-27 02:41:01.882   928  3037 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
10-27 02:41:01.882   928  3037 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-27 02:41:01.883   928  3037 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-27 02:41:01.883   928  3037 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
10-27 02:41:01.883   928  3037 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-27 02:41:01.883   928  3037 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-27 02:41:01.883   928  3037 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-27 02:41:01.883   928  3037 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
10-27 02:41:01.885   928  3037 D WifiNative-HAL: Setting external_sim to 1
10-27 02:41:01.885   928  3037 D wifi    : setting dfs flag to true, 0x7f70351b60
10-27 02:41:01.886  5081  5081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-27 02:41:01.886   928  3037 D WifiStateMachine: Setting OUI to DA-A1-19
10-27 02:41:01.886   928  3037 D wifi    : setting scan oui 0x7f70351b60
10-27 02:41:01.886   928  3037 D WifiHAL : Sending mac address OUI
10-27 02:41:01.889   928  3037 E native  : do suspend true
,10-27 02:41:01.899   928  3037 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-27 02:41:01.899   928   928 D RttService: SCAN_AVAILABLE : 3
10-27 02:41:01.899   928  3147 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-27 02:41:01.912   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-27 02:41:01.913   507   920 D CommandListener: Setting iface cfg
10-27 02:41:01.917   928  3036 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
10-27 02:41:01.917   928  3036 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
10-27 02:41:01.923   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163461 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
10-27 02:41:01.924   928  3036 D WifiNative-HAL: p2pGetDeviceAddress
10-27 02:41:01.924   928  3036 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-27 02:41:02.646   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:41:03.647   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:41:04.648   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:41:05.034  5966  5966 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-27 02:41:05.064   928  3037 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-27 02:41:05.072   928  3037 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,10-27 02:41:05.072   928  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-27 02:41:05.087   928  3037 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-27 02:41:05.141   928  3037 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-27 02:41:05.463  5966  5966 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-27 02:41:05.498  5966  5966 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-27 02:41:05.499  5966  5966 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-27 02:41:05.506   928  3037 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-27 02:41:05.507   928  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-27 02:41:05.507   928  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-27 02:41:05.521   928  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-27 02:41:05.533   507   920 D CommandListener: Setting iface cfg
,10-27 02:41:05.538   928  3037 D WifiStateMachine: Start Dhcp Watchdog 3
,10-27 02:41:05.542   928  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-27 02:41:05.557   928  5971 D DhcpClient: Receive thread started
,10-27 02:41:05.639   928  3037 E native  : do suspend false
,10-27 02:41:05.649   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:41:05.649   928  5970 D DhcpClient: Broadcasting DHCPDISCOVER
,10-27 02:41:05.665   928  5971 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-27 02:41:05.665   928  5970 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-27 02:41:05.667   928  5970 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-27 02:41:05.685   928  5971 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-27 02:41:05.686   928  5970 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
10-27 02:41:05.690   507   920 D CommandListener: Setting iface cfg
,10-27 02:41:05.694   928  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-27 02:41:05.701   928  5970 D DhcpClient: Scheduling renewal in 86399s
,10-27 02:41:05.702   928  3037 E native  : do suspend true
,10-27 02:41:05.722   928  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-27 02:41:05.723   928  3037 D WifiConfigStore: No blacklist allowed without epno enabled
,10-27 02:41:05.724   928  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-27 02:41:05.733   928  3039 D ConnectivityService: Adding iface wlan0 to network 102
,10-27 02:41:05.733   928  3037 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-27 02:41:05.783   928  3039 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-27 02:41:05.783   928  3039 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-27 02:41:05.785   928  3039 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-27 02:41:05.788   928  3039 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-27 02:41:05.792   928  3039 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-27 02:41:05.804   928  3039 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-27 02:41:05.810   928  3039 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-27 02:41:05.810   928  3039 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-27 02:41:05.810   928  3039 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-27 02:41:05.810   928  3037 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,10-27 02:41:05.810   928  3039 D ConnectivityService:    accepting network in place of null
10-27 02:41:05.810   928  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-27 02:41:05.811   928  3039 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-27 02:41:05.826   928  5969 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167364, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-27 02:41:05.840   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-27 02:41:05.864   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-27 02:41:05.868   928  3039 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
10-27 02:41:05.868   928  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-27 02:41:05.868  3819  3938 W QCNEJ   : |CORE| network available: 102
,10-27 02:41:05.869   928  3039 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,10-27 02:41:05.870   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-27 02:41:05.875  3819  3938 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-27 02:41:05.876  3819  3938 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-27 02:41:05.877  3819  3938 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-27 02:41:05.882  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:41:05.882  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:41:05.882  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:41:05.882  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:41:05.882  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:41:05.882  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:05.882  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:41:05.882  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:41:05.885  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-27 02:41:05.887  4016  4016 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-27 02:41:05.889  3920  3920 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-27 02:41:05.891  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:41:05.891  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:41:05.891  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:41:05.891  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:41:05.891  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:41:05.891  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:05.891  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:41:05.891  5682  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:41:05.892  3920  3920 D SystemUpdateService: onCreate
10-27 02:41:05.894  5682  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-27 02:41:05.896  3920  3920 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-27 02:41:05.907  3920  3920 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-27 02:41:05.913  3920  5481 I iu.UploadsManager: num queued entries: 0
,10-27 02:41:05.913   928  5968 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-27 02:41:05.914  3920  5481 I iu.UploadsManager: num updated entries: 0
,10-27 02:41:05.915  3920  5481 I iu.SyncManager: NEXT; no task
,10-27 02:41:05.915  3920  5980 I SystemUpdateService: active receiver: enabled
,10-27 02:41:05.919  3920  3920 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-27 02:41:05.920  3920  3920 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-27 02:41:05.922  5777  5777 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-27 02:41:05.925  5777  5777 D SprintDMHelper: simOperator: 
,10-27 02:41:05.925  5777  5777 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-27 02:41:05.948  3920  5980 I SystemUpdateService: OffPeak download feature is not enabled!
,10-27 02:41:05.953  3920  5980 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-27 02:41:05.953  3920  5980 I SystemUpdateService: now status is 0 (complete)
10-27 02:41:05.953  3920  5980 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-27 02:41:05.953  3920  5980 I SystemUpdateService: file has been verified
10-27 02:41:05.953  3920  5980 I SystemUpdateService: OTA package size = 21989297
,10-27 02:41:05.959  3920  5980 I SystemUpdateService: showing system update notification
,10-27 02:41:05.963   928  5968 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 27 Oct 2016 00:41:06 GMT], X-Android-Received-Millis=[1477528865962], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477528865938]}
10-27 02:41:05.964   928  3039 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-27 02:41:05.964   928  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-27 02:41:05.964   928  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-27 02:41:05.965   928  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-27 02:41:05.969  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-27 02:41:05.969  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:41:05.969  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:41:05.969  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:41:05.969  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:41:05.969  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:05.969  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:41:05.969  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:41:05.971  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-27 02:41:05.971   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
10-27 02:41:05.971  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:05.971  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@700d8e0 removed from the list
10-27 02:41:05.971  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
,10-27 02:41:05.971  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:05.971  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:05.972  3920  3920 D SystemUpdateService: onDestroy
10-27 02:41:05.975  5682  5729 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-27 02:41:05.976  5682  5729 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-27 02:41:05.978  5682  5729 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@900f35a Bundle[{}]
10-27 02:41:05.978  5682  5729 I io.jxcore.node.LifeCycleMonitor: start: OK
10-27 02:41:05.978  5682  5729 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-27 02:41:05.979  5682  5729 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-27 02:41:05.979  5682  5729 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-27 02:41:05.980  5682  5729 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-27 02:41:05.981  5682  5729 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-27 02:41:05.985  5682  5729 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
10-27 02:41:05.986  5682  5729 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-27 02:41:05.986  5682  5729 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
10-27 02:41:05.988  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-27 02:41:05.988  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab0c799 added. We now have 3 listener(s)
,10-27 02:41:05.990  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:41:05.990  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:41:05.990  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-27 02:41:05.990  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:41:05.990  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36bca5e added. We now have 4 listener(s)
10-27 02:41:05.990  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:41:05.991  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-27 02:41:05.993  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-27 02:41:05.997  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:41:05.997  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:41:05.997  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:41:05.997  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:41:05.997  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:41:05.997  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:05.997  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:41:05.997  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:41:05.998  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:05.998  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
10-27 02:41:05.998  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-27 02:41:05.998  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4aa30c added. We now have 4 listener(s)
,10-27 02:41:06.000  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:41:06.000  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:41:06.000  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:41:06.000  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-27 02:41:06.000  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:41:06.000  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abd4455 added. We now have 5 listener(s)
10-27 02:41:06.000  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:41:06.001  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:41:06.001  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:41:06.001  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:41:06.001  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:41:06.001  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.001  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-27 02:41:06.001  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-27 02:41:06.001  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:41:06.001  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab0c799 removed from the list
10-27 02:41:06.002  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.002  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36bca5e removed from the list
10-27 02:41:06.002  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:41:06.003  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:41:06.003  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:41:06.003  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-27 02:41:06.003  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.003  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:41:06.004  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.004  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.005  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.005  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-27 02:41:06.005  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:41:06.005  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.005  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36bca5e not in the list
10-27 02:41:06.005  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.005  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.005  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:41:06.006  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.006  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.006  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.006  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-27 02:41:06.006  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:41:06.006  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.006  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abd4455 removed from the list
10-27 02:41:06.006  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:41:06.006  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.006  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.006  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:41:06.006  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:41:06.006  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4aa30c removed from the list
10-27 02:41:06.007  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-27 02:41:06.007  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c262e6a added. We now have 3 listener(s)
,10-27 02:41:06.008  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-27 02:41:06.008  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:41:06.008  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-27 02:41:06.008  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:41:06.008  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e623f5b added. We now have 4 listener(s)
10-27 02:41:06.008  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:41:06.009  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-27 02:41:06.011  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-27 02:41:06.014  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:41:06.014  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:41:06.014  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:41:06.014  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:41:06.014  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:41:06.014  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:06.014  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:41:06.014  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:41:06.015  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:06.016  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
10-27 02:41:06.016  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-27 02:41:06.016  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dad0d1 added. We now have 4 listener(s)
10-27 02:41:06.017  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:41:06.017  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:41:06.017  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-27 02:41:06.017  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:41:06.017  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@870c736 added. We now have 5 listener(s)
10-27 02:41:06.017  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:41:06.017  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:41:06.017  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-27 02:41:06.017  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-27 02:41:06.017  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:41:06.017  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-27 02:41:06.018  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:41:06.021  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:41:06.021  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-27 02:41:06.021  5682  5729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-27 02:41:06.021  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-27 02:41:06.024  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-27 02:41:06.024  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-27 02:41:06.024  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-27 02:41:06.028  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:41:06.028  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-27 02:41:06.028  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-27 02:41:06.028  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-27 02:41:06.028  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-27 02:41:06.028  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:41:06.029  5682  5729 D BluetoothAdapter: STATE_ON
,10-27 02:41:06.032  5906  5917 D BtGatt.GattService: registerClient() - UUID=fee58bcf-4c0a-425f-8c3d-48b04c1a0eb2
,10-27 02:41:06.032  5906  5922 D BtGatt.GattService: onClientRegistered() - UUID=fee58bcf-4c0a-425f-8c3d-48b04c1a0eb2, clientIf=5
10-27 02:41:06.033  5682  5693 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-27 02:41:06.033  5906  5939 D BtGatt.GattService: start scan with filters
,10-27 02:41:06.036  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-27 02:41:06.037  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.037  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-27 02:41:06.037  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.037  5906  5925 D BtGatt.ScanManager: handling starting scan
10-27 02:41:06.037  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:41:06.037  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-27 02:41:06.037  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-27 02:41:06.037  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.037  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.037  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-27 02:41:06.037  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:41:06.038  5906  5925 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45cb56f
,10-27 02:41:06.039  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.039  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:41:06.039  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.039  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:41:06.039  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:41:06.039  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.039  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-27 02:41:06.041  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-27 02:41:06.041  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.044  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.044  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.044  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.044  5682  5729 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-27 02:41:06.044  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-27 02:41:06.044  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-27 02:41:06.044  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.044  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-27 02:41:06.044  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:41:06.045  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-27 02:41:06.045  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-27 02:41:06.045  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-27 02:41:06.045  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-27 02:41:06.045  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.045  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.045  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-27 02:41:06.045  5906  5922 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-27 02:41:06.045  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.046  5682  5729 D BluetoothAdapter: STATE_ON
10-27 02:41:06.046  5906  5925 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-27 02:41:06.046  5906  5947 D BtGatt.GattService: stopScan() - queue size =1
10-27 02:41:06.047  5906  5917 D BtGatt.GattService: unregisterClient() - clientIf=5
10-27 02:41:06.047  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-27 02:41:06.047  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.047  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-27 02:41:06.047  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScanne,rStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.047  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.048  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-27 02:41:06.048  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-27 02:41:06.048  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.048  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.048  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-27 02:41:06.048  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.049  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-27 02:41:06.049  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-27 02:41:06.050  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:41:06.050  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.051  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-27 02:41:06.051  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.051  5906  5925 D BtGatt.ScanManager: Starting BLE batch scan
10-27 02:41:06.051  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.051  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.051  5906  5925 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-27 02:41:06.051  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.052  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:41:06.052  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:41:06.052  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:41:06.054  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:41:06.054  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:41:06.054  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:41:06.054  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:41:06.055  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.055  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:41:06.055  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:41:06.055  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:41:06.055  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c262e6a removed from the list
10-27 02:41:06.055  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.055  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e623f5b removed from the list
10-27 02:41:06.055  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:41:06.055  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.056  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.056  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.056  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.057  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.057  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.057  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.058  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:41:06.058  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:41:06.058  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.058  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e623f5b not in the list
10-27 02:41:06.058  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.058  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.058  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.059  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.059  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.060  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.060  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:41:06.060  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:41:06.060  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.060  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@870c736 removed from the list
10-27 02:41:06.060  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:41:06.060  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.060  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.060  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:41:06.060  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:41:06.061  5906  5922 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-27 02:41:06.061  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dad0d1 removed from the list
10-27 02:41:06.061  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.061  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-27 02:41:06.061  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fa20c2 added. We now have 3 listener(s)
10-27 02:41:06.063  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:41:06.063  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:41:06.063  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-27 02:41:06.063  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:41:06.063  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3873ed3 added. We now have 4 listener(s)
10-27 02:41:06.063  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:41:06.064  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-27 02:41:06.065  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-27 02:41:06.066  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.067  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:41:06.072  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-27 02:41:06.072  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.072  5906  5925 D BtGatt.ScanManager: stopping BLe Batch
10-27 02:41:06.072  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:41:06.072  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:41:06.072  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:41:06.072  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:41:06.072  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:41:06.072  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:06.072  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:41:06.072  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:41:06.075  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:06.075  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
10-27 02:41:06.075  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-27 02:41:06.075  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a5c909 added. We now have 4 listener(s)
10-27 02:41:06.076  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-27 02:41:06.076  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.076  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:41:06.076  5906  5925 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-27 02:41:06.077  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:41:06.077  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-27 02:41:06.077  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:41:06.077  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cd870e added. We now have 5 listener(s)
10-27 02:41:06.077  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:41:06.077  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:41:06.077  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:41:06.077  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:41:06.078  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-27 02:41:06.078  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-27 02:41:06.078  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:41:06.078  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-27 02:41:06.079  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-27 02:41:06.080  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-27 02:41:06.080  5682  5729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-27 02:41:06.080  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-27 02:41:06.081  5906  5922 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-27 02:41:06.081  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.083  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-27 02:41:06.084  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-27 02:41:06.084  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-27 02:41:06.086  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.086  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-27 02:41:06.086  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-27 02:41:06.086  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-27 02:41:06.086  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-27 02:41:06.086  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.087  5682  5729 D BluetoothAdapter: STATE_ON
10-27 02:41:06.088  5906  5947 D BtGatt.GattService: registerClient() - UUID=3d7e3004-0aa0-4542-aecc-5c735dad0192
10-27 02:41:06.089  5906  5922 D BtGatt.GattService: onClientRegistered() - UUID=3d7e3004-0aa0-4542-aecc-5c735dad0192, clientIf=5
10-27 02:41:06.089  5682  5692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-27 02:41:06.089  5906  5917 D BtGatt.GattService: start scan with filters
10-27 02:41:06.091  5906  5925 D BtGatt.ScanManager: handling starting scan
10-27 02:41:06.092  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-27 02:41:06.092  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.092  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-27 02:41:06.092  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.092  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.092  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-27 02:41:06.092  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-27 02:41:06.092  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.092  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.092  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-27 02:41:06.092  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.094  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.094  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:41:06.095  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.095  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:41:06.095  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.095  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.095  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-27 02:41:06.096  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-27 02:41:06.096  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.096  5906  5922 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-27 02:41:06.096  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.096  5906  5925 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-27 02:41:06.098  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.098  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.098  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.098  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:41:06.098  5682  5729 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-27 02:41:06.099  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:41:06.099  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:41:06.099  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:41:06.099  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:41:06.099  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.099  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-27 02:41:06.099  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:41:06.099  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:41:06.099  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fa20c2 removed from the list
10-27 02:41:06.099  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.099  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3873ed3 removed from the list
10-27 02:41:06.099  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:41:06.099  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:41:06.099  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.100  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-27 02:41:06.100  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.100  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:41:06.100  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.100  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.100  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.101  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.101  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:41:06.101  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:41:06.101  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.101  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3873ed3 not in the list
10-27 02:41:06.101  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-27 02:41:06.101  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-27 02:41:06.101  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.101  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-27 02:41:06.101  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-27 02:41:06.101  5906  5925 D BtGatt.ScanManager: Starting BLE batch scan
10-27 02:41:06.101  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.101  5906  5925 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-27 02:41:06.101  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.101  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-27 02:41:06.102  5682  5729 D BluetoothAdapter: STATE_ON
10-27 02:41:06.102  5906  5947 D BtGatt.GattService: stopScan() - queue size =1
10-27 02:41:06.102  5906  5939 D BtGatt.GattService: unregisterClient() - clientIf=5
10-27 02:41:06.103  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-27 02:41:06.103  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.103  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-27 02:41:06.103  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.103  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.103  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-27 02:41:06.103  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-27 02:41:06.103  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.103  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.103  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-27 02:41:06.103  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.104  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.104  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:41:06.104  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.105  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.105  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.105  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.105  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.105  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-27 02:41:06.105  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.105  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.105  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.105  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-27 02:41:06.105  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-27 02:41:06.106  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.106  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.107  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.107  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.107  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.107  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:41:06.107  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:41:06.107  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.107  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:41:06.107  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cd870e removed from the list
10-27 02:41:06.107  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:41:06.107  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:41:06.107  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.107  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.107  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:41:06.107  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:41:06.107  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:41:06.108  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a5c909 removed from the list
10-27 02:41:06.108  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-27 02:41:06.108  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5f061a added. We now have 3 listener(s)
10-27 02:41:06.109  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:41:06.109  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:41:06.109  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-27 02:41:06.110  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:41:06.110  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6db54b added. We now have 4 listener(s)
10-27 02:41:06.110  5906  5922 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-27 02:41:06.110  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.110  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:41:06.114  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-27 02:41:06.115  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-27 02:41:06.115  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.117  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:41:06.120  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:41:06.120  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:41:06.120  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:41:06.120  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:41:06.120  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:41:06.120  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:06.120  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:41:06.120  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-27 02:41:06.121  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-27 02:41:06.121  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.121  5906  5925 D BtGatt.ScanManager: stopping BLe Batch
10-27 02:41:06.122  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:06.122  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
10-27 02:41:06.123  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-27 02:41:06.123  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9609041 added. We now have 4 listener(s)
10-27 02:41:06.124  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:41:06.124  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:41:06.124  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-27 02:41:06.124  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:41:06.124  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5769e6 added. We now have 5 listener(s)
10-27 02:41:06.124  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:41:06.124  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:41:06.124  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:41:06.124  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-27 02:41:06.125  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-27 02:41:06.125  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:41:06.125  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-27 02:41:06.125  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-27 02:41:06.125  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.125  5906  5925 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-27 02:41:06.127  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-27 02:41:06.127  5682  5729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-27 02:41:06.127  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-27 02:41:06.127  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:41:06.130  5906  5922 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-27 02:41:06.130  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.130  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-27 02:41:06.131  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-27 02:41:06.131  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-27 02:41:06.133  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.133  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-27 02:41:06.133  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-27 02:41:06.133  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-27 02:41:06.133  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-27 02:41:06.133  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.134  5682  5729 D BluetoothAdapter: STATE_ON
10-27 02:41:06.136  5906  5916 D BtGatt.GattService: registerClient() - UUID=1dd50e03-cd70-4642-a352-ed42610382a0
10-27 02:41:06.136  5906  5922 D BtGatt.GattService: onClientRegistered() - UUID=1dd50e03-cd70-4642-a352-ed42610382a0, clientIf=5
10-27 02:41:06.136  5682  5693 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-27 02:41:06.137  5906  5917 D BtGatt.GattService: start scan with filters
10-27 02:41:06.139  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-27 02:41:06.139  5906  5925 D BtGatt.ScanManager: handling starting scan
10-27 02:41:06.139  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.139  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-27 02:41:06.139  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.139  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.139  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-27 02:41:06.139  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-27 02:41:06.139  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.139  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.140  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-27 02:41:06.140  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.142  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.142  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:41:06.143  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.143  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-27 02:41:06.143  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.143  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.143  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-27 02:41:06.144  5906  5922 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-27 02:41:06.144  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.144  5906  5925 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-27 02:41:06.144  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-27 02:41:06.144  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.147  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.147  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.147  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.148  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-27 02:41:06.149  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.149  5906  5925 D BtGatt.ScanManager: Starting BLE batch scan
10-27 02:41:06.149  5906  5925 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-27 02:41:06.150  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-27 02:41:06.150  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:41:06.150  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:41:06.150  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:41:06.150  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.150  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-27 02:41:06.150  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:41:06.150  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:41:06.150  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5f061a removed from the list
10-27 02:41:06.150  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.150  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6db54b removed from the list
10-27 02:41:06.150  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:41:06.150  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:41:06.151  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.151  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-27 02:41:06.151  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.151  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:41:06.151  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.153  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.153  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.153  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.153  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:41:06.153  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:41:06.153  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.153  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6db54b not in the list
10-27 02:41:06.153  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-27 02:41:06.153  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-27 02:41:06.153  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-27 02:41:06.153  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.153  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.153  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-27 02:41:06.154  5682  5729 D BluetoothAdapter: STATE_ON
10-27 02:41:06.154  5906  5939 D BtGatt.GattService: stopScan() - queue size =1
10-27 02:41:06.155  5906  5946 D BtGatt.GattService: unregisterClient() - clientIf=5
10-27 02:41:06.155  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-27 02:41:06.155  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.155  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-27 02:41:06.156  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.156  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.156  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-27 02:41:06.156  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-27 02:41:06.156  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.156  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.156  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-27 02:41:06.156  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.157  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-27 02:41:06.157  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-27 02:41:06.159  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.159  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.159  5906  5922 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-27 02:41:06.159  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-27 02:41:06.162  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:41:06.162  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-27 02:41:06.162  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.162  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:41:06.162  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:41:06.162  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.162  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5769e6 removed from the list
10-27 02:41:06.162  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:41:06.162  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:41:06.162  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.162  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.162  5682  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-27 02:41:06.162  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:41:06.162  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:41:06.162  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9609041 removed from the list
10-27 02:41:06.162  5682  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-27 02:41:06.163  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-27 02:41:06.163  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6203e72 added. We now have 3 listener(s)
10-27 02:41:06.164  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-27 02:41:06.164  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:41:06.164  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.164  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:41:06.164  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-27 02:41:06.164  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:41:06.164  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ced82c3 added. We now have 4 listener(s)
10-27 02:41:06.164  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:41:06.165  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-27 02:41:06.169  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-27 02:41:06.171  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-27 02:41:06.171  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.171  5906  5925 D BtGatt.ScanManager: stopping BLe Batch
10-27 02:41:06.173  5682  5729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-27 02:41:06.173  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-27 02:41:06.173  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-27 02:41:06.173  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-27 02:41:06.173  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-27 02:41:06.173  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-27 02:41:06.173  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-27 02:41:06.173  5682  5729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-27 02:41:06.175  5682  5729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-27 02:41:06.175  5682  5729 D io.jxcore.node.ConnectivityMonitor: start: OK
10-27 02:41:06.175  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-27 02:41:06.175  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-27 02:41:06.175  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-27 02:41:06.175  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7560679 added. We now have 4 listener(s)
10-27 02:41:06.176  5906  5925 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-27 02:41:06.176  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-27 02:41:06.176  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-27 02:41:06.177  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-27 02:41:06.177  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-27 02:41:06.177  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcfbe added. We now have 5 listener(s)
10-27 02:41:06.177  5682  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-27 02:41:06.177  5682  5729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-27 02:41:06.177  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-27 02:41:06.177  5682  5729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-27 02:41:06.177  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:41:06.177  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.177  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:41:06.177  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-27 02:41:06.177  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:41:06.177  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:41:06.177  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6203e72 removed from the list
10-27 02:41:06.177  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-27 02:41:06.177  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ced82c3 removed from the list
10-27 02:41:06.179  5682  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-27 02:41:06.179  5682  5729 D io.jxcore.node.ConnectivityMonitor: stop
10-27 02:41:06.180  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.180  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.180  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.180  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.180  5906  5922 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-27 02:41:06.181  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-27 02:41:06.181  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.181  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.181  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.181  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:41:06.181  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:41:06.181  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.181  5682  5729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ced82c3 not in the list
10-27 02:41:06.181  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.181  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-27 02:41:06.181  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.182  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.182  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.182  5682  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-27 02:41:06.182  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-27 02:41:06.182  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-27 02:41:06.182  5682  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-27 02:41:06.182  5682  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcfbe removed from the list
,10-27 02:41:06.182  5682  5729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-27 02:41:06.182  5682  5729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-27 02:41:06.183  5682  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-27 02:41:06.183  5682  5729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-27 02:41:06.183  5682  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-27 02:41:06.183  5682  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7560679 removed from the list
10-27 02:41:06.183  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-27 02:41:06.183  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-27 02:41:06.183  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,10-27 02:41:06.183  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:41:06.183  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-27 02:41:06.184  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-27 02:41:06.552  5682  5682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-27 02:41:06.608  5682  5682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-27 02:41:06.649   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-27 02:41:06.663  5682  5682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-27 02:41:08.356  5682  5988 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-27 02:41:08.356  5682  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-27 02:41:09.174  5682  5988 W !!      : call onHalfStreamCopied
,10-27 02:41:09.174  5682  5988 I testCopyDataAndClose: closing input stream
,10-27 02:41:09.218  3638  5990 I VacuumService: Vacuum at: now=1477528869218 tag=VacuumService
,10-27 02:41:09.257  3638  5993 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-27 02:41:09.287  3638  5991 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-27 02:41:09.290  3638  5991 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-27 02:41:09.309  3638  5991 W Uploader:  no longer exists, so no auth token.
,10-27 02:41:09.315  3638  5993 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-27 02:41:09.624  3638  5995 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-27 02:41:09.761  3638  5993 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-27 02:41:09.823  3638  5991 W Uploader:  no longer exists, so no auth token.
,10-27 02:41:09.829  3638  5995 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-27 02:41:09.897  3638  5993 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-27 02:41:09.942  5682  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-27 02:41:09.984  3638  5995 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-27 02:41:13.819   928  3039 D ConnectivityService: handlePromptUnvalidated 102
,10-27 02:41:14.183  5682  6000 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-27 02:41:14.183  5682  6000 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-27 02:41:16.183  5682  5729 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
10-27 02:41:16.183  5682  5729 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-27 02:41:16.183  5682  5729 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,10-27 02:41:16.263  5682  6000 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-27 02:41:16.263  5682  6000 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-27 02:41:16.263  5682  6000 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,10-27 02:41:16.346  5682  6001 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-27 02:41:16.346  5682  6001 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-27 02:41:17.964  5682  6001 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-27 02:41:22.483  5682  6002 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-27 02:41:22.483  5682  6002 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-27 02:41:22.484  5682  6002 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
10-27 02:41:22.484  5682  6002 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-27 02:41:22.484  5682  6002 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-27 02:41:22.484  5682  6002 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-27 02:41:22.484  5682  6002 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-27 02:41:22.484  5682  6002 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-27 02:41:22.484  5682  6002 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-27 02:41:22.485  5682  6002 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-27 02:41:22.485  5682  6002 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-27 02:41:22.485  5682  6002 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-27 02:41:22.485  5682  6002 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-27 02:41:22.487  5682  5729 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-27 02:41:22.490  5682  6003 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-27 02:41:22.490  5682  6003 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-27 02:41:22.491  5682  6003 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
10-27 02:41:22.491  5682  6003 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-27 02:41:22.491  5682  6003 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-27 02:41:22.492  5682  6003 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,10-27 02:41:22.492  5682  6003 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-27 02:41:22.492  5682  6003 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-27 02:41:22.496  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-27 02:41:22.496  5682  5729 I jxcore-log: 
,10-27 02:41:22.497  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-27 02:41:22.497  5682  5729 I jxcore-log: 
,10-27 02:41:22.497  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-27 02:41:22.497  5682  5729 I jxcore-log: 
10-27 02:41:22.497  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-27 02:41:22.497  5682  5729 I jxcore-log: 
,10-27 02:41:22.497  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG UnitTest_app: 'Total duration:  92088'
10-27 02:41:22.497  5682  5729 I jxcore-log: 
10-27 02:41:22.500  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-27 02:41:22.500  5682  5729 I jxcore-log: 
,10-27 02:41:22.503  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.503  5682  5729 I jxcore-log: 
,10-27 02:41:22.504  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.504  5682  5729 I jxcore-log: 
10-27 02:41:22.505  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.505  5682  5729 I jxcore-log: 
10-27 02:41:22.505  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.505  5682  5729 I jxcore-log: 
,10-27 02:41:22.506  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-27 02:41:22.506  5682  5729 I jxcore-log: 
,10-27 02:41:22.506  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-27 02:41:22.506  5682  5729 I jxcore-log: 
10-27 02:41:22.506  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.506  5682  5729 I jxcore-log: 
10-27 02:41:22.507  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.507  5682  5729 I jxcore-log: 
,10-27 02:41:22.507  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-27 02:41:22.507  5682  5729 I jxcore-log: 
10-27 02:41:22.507  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-27 02:41:22.507  5682  5729 I jxcore-log: 
10-27 02:41:22.507  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-27 02:41:22.507  5682  5729 I jxcore-log: 
10-27 02:41:22.508  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.508  5682  5729 I jxcore-log: 
10-27 02:41:22.508  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.508  5682  5729 I jxcore-log: 
,10-27 02:41:22.508  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.508  5682  5729 I jxcore-log: 
10-27 02:41:22.508  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-27 02:41:22.508  5682  5729 I jxcore-log: 
10-27 02:41:22.509  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-27 02:41:22.509  5682  5729 I jxcore-log: 
10-27 02:41:22.509  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-27 02:41:22.509  5682  5729 I jxcore-log: 
,10-27 02:41:22.509  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.509  5682  5729 I jxcore-log: 
10-27 02:41:22.510  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.510  5682  5729 I jxcore-log: 
10-27 02:41:22.510  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.510  5682  5729 I jxcore-log: 
10-27 02:41:22.510  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-27 02:41:22.510  5682  5729 I jxcore-log: 
10-27 02:41:22.510  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-27 02:41:22.510  5682  5729 I jxcore-log: 
10-27 02:41:22.511  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-27 02:41:22.511  5682  5729 I jxcore-log: 
,10-27 02:41:22.512  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.512  5682  5729 I jxcore-log: 
10-27 02:41:22.513  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.513  5682  5729 I jxcore-log: 
10-27 02:41:22.513  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.513  5682  5729 I jxcore-log: 
10-27 02:41:22.513  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-27 02:41:22.513  5682  5729 I jxcore-log: 
10-27 02:41:22.513  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-27 02:41:22.513  5682  5729 I jxcore-log: 
,10-27 02:41:22.514  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.514  5682  5729 I jxcore-log: 
10-27 02:41:22.514  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.514  5682  5729 I jxcore-log: 
10-27 02:41:22.514  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.514  5682  5729 I jxcore-log: 
10-27 02:41:22.514  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.514  5682  5729 I jxcore-log: 
,10-27 02:41:22.515  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.515  5682  5729 I jxcore-log: 
10-27 02:41:22.515  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.515  5682  5729 I jxcore-log: 
10-27 02:41:22.515  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.515  5682  5729 I jxcore-log: 
10-27 02:41:22.515  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.515  5682  5729 I jxcore-log: 
,10-27 02:41:22.516  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.516  5682  5729 I jxcore-log: 
,10-27 02:41:22.516  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.516  5682  5729 I jxcore-log: 
,10-27 02:41:22.516  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.516  5682  5729 I jxcore-log: 
10-27 02:41:22.516  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-27 02:41:22.516  5682  5729 I jxcore-log: 
10-27 02:41:22.517  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-27 02:41:22.517  5682  5729 I jxcore-log: 
,10-27 02:41:22.517  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-27 02:41:22.517  5682  5729 I jxcore-log: 
10-27 02:41:22.517  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.517  5682  5729 I jxcore-log: 
10-27 02:41:22.517  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.517  5682  5729 I jxcore-log: 
10-27 02:41:22.517  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.517  5682  5729 I jxcore-log: 
10-27 02:41:22.518  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.518  5682  5729 I jxcore-log: 
10-27 02:41:22.518  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.518  5682  5729 I jxcore-log: 
10-27 02:41:22.518  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-27 02:41:22.518  5682  5729 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-27 02:41:22.518  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.518  5682  5729 I jxcore-log: 
,10-27 02:41:22.519  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.519  5682  5729 I jxcore-log: 
10-27 02:41:22.519  5682  5729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-27 02:41:22.519  5682  5729 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-27 02:41:22.519  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-27 02:41:22.519  5682  5729 I jxcore-log: 
10-27 02:41:22.519  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-27 02:41:22.519  5682  5729 I jxcore-log: 
10-27 02:41:22.519  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-27 02:41:22.519  5682  5729 I jxcore-log: 
10-27 02:41:22.520  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-27 02:41:22.520  5682  5729 I jxcore-log: 
,10-27 02:41:22.525  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-27 02:41:22.525  5682  5729 I jxcore-log: 
,10-27 02:41:22.525  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - WARN testUtils: 'myNameCallback not set!'
10-27 02:41:22.525  5682  5729 I jxcore-log: 
10-27 02:41:22.526  5682  5729 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-27 02:41:22.527  5682  5729 I jxcore-log: 2016-10-27 00:41:22 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-27 02:41:22.527  5682  5729 I jxcore-log: 
,10-27 02:41:22.529  5682  5682 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-27 02:41:24.539  5682  5729 I jxcore-log: 2016-10-27 00:41:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-27 02:41:24.539  5682  5729 I jxcore-log: 
,10-27 02:41:24.865  5682  5729 I jxcore-log: 2016-10-27 00:41:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-27 02:41:24.865  5682  5729 I jxcore-log: 
,10-27 02:41:24.878  5682  5729 I jxcore-log: 2016-10-27 00:41:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-27 02:41:24.878  5682  5729 I jxcore-log: 
,10-27 02:41:25.971  5682  5729 I jxcore-log: 2016-10-27 00:41:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-27 02:41:25.971  5682  5729 I jxcore-log: 
,10-27 02:41:26.152  5682  5729 I jxcore-log: 2016-10-27 00:41:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-27 02:41:26.152  5682  5729 I jxcore-log: 
,10-27 02:41:26.158  5682  5729 I jxcore-log: 2016-10-27 00:41:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-27 02:41:26.158  5682  5729 I jxcore-log: 
,10-27 02:41:26.162  5682  5729 I jxcore-log: 2016-10-27 00:41:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-27 02:41:26.162  5682  5729 I jxcore-log: 
,10-27 02:41:26.629  5682  5729 I jxcore-log: 2016-10-27 00:41:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-27 02:41:26.629  5682  5729 I jxcore-log: 
,10-27 02:41:26.650   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:41:26.671  5682  5729 I jxcore-log: 2016-10-27 00:41:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-27 02:41:26.671  5682  5729 I jxcore-log: 
,10-27 02:41:26.684  5682  5729 I jxcore-log: 2016-10-27 00:41:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-27 02:41:26.684  5682  5729 I jxcore-log: 
,10-27 02:41:26.688  5682  5729 I jxcore-log: 2016-10-27 00:41:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-27 02:41:26.688  5682  5729 I jxcore-log: 
,10-27 02:41:26.964  5682  5729 I jxcore-log: 2016-10-27 00:41:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-27 02:41:26.964  5682  5729 I jxcore-log: 
,10-27 02:41:27.087  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-27 02:41:27.087  5682  5729 I jxcore-log: 
,10-27 02:41:27.475  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-27 02:41:27.475  5682  5729 I jxcore-log: 
,10-27 02:41:27.482  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-27 02:41:27.482  5682  5729 I jxcore-log: 
,10-27 02:41:27.486  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-27 02:41:27.486  5682  5729 I jxcore-log: 
,10-27 02:41:27.490  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-27 02:41:27.490  5682  5729 I jxcore-log: 
,10-27 02:41:27.495  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-27 02:41:27.495  5682  5729 I jxcore-log: 
,10-27 02:41:27.521  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-27 02:41:27.521  5682  5729 I jxcore-log: 
,10-27 02:41:27.557  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-27 02:41:27.557  5682  5729 I jxcore-log: 
,10-27 02:41:27.565  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-27 02:41:27.565  5682  5729 I jxcore-log: 
,10-27 02:41:27.571  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-27 02:41:27.571  5682  5729 I jxcore-log: 
,10-27 02:41:27.586  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-27 02:41:27.586  5682  5729 I jxcore-log: 
,10-27 02:41:27.591  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-27 02:41:27.591  5682  5729 I jxcore-log: 
,10-27 02:41:27.597  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-27 02:41:27.597  5682  5729 I jxcore-log: 
,10-27 02:41:27.602  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-27 02:41:27.602  5682  5729 I jxcore-log: 
,10-27 02:41:27.615  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-27 02:41:27.615  5682  5729 I jxcore-log: 
,10-27 02:41:27.621  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-27 02:41:27.621  5682  5729 I jxcore-log: 
,10-27 02:41:27.643  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-27 02:41:27.643  5682  5729 I jxcore-log: 
,10-27 02:41:27.651   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:41:27.653  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-27 02:41:27.653  5682  5729 I jxcore-log: 
,10-27 02:41:27.665  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-27 02:41:27.665  5682  5729 I jxcore-log: 
,10-27 02:41:27.675  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-27 02:41:27.675  5682  5729 I jxcore-log: 
,10-27 02:41:27.688  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-27 02:41:27.688  5682  5729 I jxcore-log: 
,10-27 02:41:27.698  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-27 02:41:27.698  5682  5729 I jxcore-log: 
,10-27 02:41:27.705  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-27 02:41:27.705  5682  5729 I jxcore-log: 
,10-27 02:41:27.726  5682  5729 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-27 02:41:27.727  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - INFO testUtils: 'BLE multiple advertisement supported'
10-27 02:41:27.727  5682  5729 I jxcore-log: 
,10-27 02:41:27.806  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:27.806  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:27.806  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:27.806  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:27.806  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:27.806  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:27.806  5682  5729 I jxcore-log: 
,10-27 02:41:27.984  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:27.984  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:27.984  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:27.984  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:27.984  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:27.984  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:27.984  5682  5729 I jxcore-log: 
,10-27 02:41:27.987  5682  5729 I jxcore-log: 2016-10-27 00:41:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:27.987  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:27.987  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:27.987  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:27.987  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:27.987  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:27.987  5682  5729 I jxcore-log: 
,10-27 02:41:28.484  5682  5729 I jxcore-log: 2016-10-27 00:41:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:28.484  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:28.484  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:28.484  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:28.484  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:28.484  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:28.484  5682  5729 I jxcore-log: 
,10-27 02:41:28.487  5682  5729 I jxcore-log: 2016-10-27 00:41:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:28.487  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:28.487  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:28.487  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:28.487  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:28.487  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:28.487  5682  5729 I jxcore-log: 
,10-27 02:41:28.652   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:41:29.520  5682  5729 I jxcore-log: 2016-10-27 00:41:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:29.520  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:29.520  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:29.520  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:29.520  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:29.520  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:29.520  5682  5729 I jxcore-log: 
,10-27 02:41:29.527  5682  5729 I jxcore-log: 2016-10-27 00:41:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:29.527  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:29.527  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:29.527  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:29.527  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:29.527  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:29.527  5682  5729 I jxcore-log: 
,10-27 02:41:29.654   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:41:30.562  5682  5729 I jxcore-log: 2016-10-27 00:41:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:30.562  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:30.562  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:30.562  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:30.562  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:30.562  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:30.562  5682  5729 I jxcore-log: 
,10-27 02:41:30.567  5682  5729 I jxcore-log: 2016-10-27 00:41:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:30.567  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:30.567  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:30.567  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:30.567  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:30.567  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:30.567  5682  5729 I jxcore-log: 
,10-27 02:41:30.655   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,10-27 02:41:31.612  5682  5729 I jxcore-log: 2016-10-27 00:41:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:31.612  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:31.612  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:31.612  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:31.612  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:31.612  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:31.612  5682  5729 I jxcore-log: 
,10-27 02:41:31.615  5682  5729 I jxcore-log: 2016-10-27 00:41:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:31.615  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:31.615  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:31.615  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:31.615  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:31.615  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:31.615  5682  5729 I jxcore-log: 
,10-27 02:41:31.655   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-27 02:41:32.647  5682  5729 I jxcore-log: 2016-10-27 00:41:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:32.647  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:32.647  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:32.647  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:32.647  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:32.647  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:32.647  5682  5729 I jxcore-log: 
,10-27 02:41:32.651  5682  5729 I jxcore-log: 2016-10-27 00:41:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:32.651  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:32.651  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:32.651  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:32.651  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:32.651  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:32.651  5682  5729 I jxcore-log: 
,10-27 02:41:33.680  5682  5729 I jxcore-log: 2016-10-27 00:41:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:33.680  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:33.680  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:33.680  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:33.680  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:33.680  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:33.680  5682  5729 I jxcore-log: 
,10-27 02:41:33.684  5682  5729 I jxcore-log: 2016-10-27 00:41:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:33.684  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:33.684  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:33.684  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:33.684  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:33.684  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:33.684  5682  5729 I jxcore-log: 
,10-27 02:41:34.717  5682  5729 I jxcore-log: 2016-10-27 00:41:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:34.717  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:34.717  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:34.717  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:34.717  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:34.717  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:34.717  5682  5729 I jxcore-log: 
,10-27 02:41:34.721  5682  5729 I jxcore-log: 2016-10-27 00:41:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:34.721  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:34.721  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:34.721  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:34.721  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:34.721  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:34.721  5682  5729 I jxcore-log: 
,10-27 02:41:35.749  5682  5729 I jxcore-log: 2016-10-27 00:41:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:35.749  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:35.749  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:35.749  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:35.749  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:35.749  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:35.749  5682  5729 I jxcore-log: 
,10-27 02:41:35.752  5682  5729 I jxcore-log: 2016-10-27 00:41:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:35.752  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:35.752  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:35.752  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:35.752  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:35.752  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:35.752  5682  5729 I jxcore-log: 
,10-27 02:41:36.813  5682  5729 I jxcore-log: 2016-10-27 00:41:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:36.813  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:36.813  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:36.813  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:36.813  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:36.813  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:36.813  5682  5729 I jxcore-log: 
,10-27 02:41:36.816  5682  5729 I jxcore-log: 2016-10-27 00:41:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:36.816  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:36.816  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:36.816  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:36.816  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:36.816  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:36.816  5682  5729 I jxcore-log: 
,10-27 02:41:37.849  5682  5729 I jxcore-log: 2016-10-27 00:41:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:37.849  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:37.849  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:37.849  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:37.849  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:37.849  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:37.849  5682  5729 I jxcore-log: 
,10-27 02:41:37.855  5682  5729 I jxcore-log: 2016-10-27 00:41:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:37.855  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:37.855  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:37.855  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:37.855  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:37.855  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:37.855  5682  5729 I jxcore-log: 
,10-27 02:41:38.889  5682  5729 I jxcore-log: 2016-10-27 00:41:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:38.889  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:38.889  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:38.889  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:38.889  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:38.889  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:38.889  5682  5729 I jxcore-log: 
,10-27 02:41:38.893  5682  5729 I jxcore-log: 2016-10-27 00:41:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:38.893  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:38.893  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:38.893  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:38.893  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:38.893  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:38.893  5682  5729 I jxcore-log: 
,10-27 02:41:39.923  5682  5729 I jxcore-log: 2016-10-27 00:41:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:39.923  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:39.923  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:39.923  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:39.923  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:39.923  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:39.923  5682  5729 I jxcore-log: 
,10-27 02:41:39.927  5682  5729 I jxcore-log: 2016-10-27 00:41:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:39.927  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:39.927  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:39.927  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:39.927  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:39.927  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:39.927  5682  5729 I jxcore-log: 
,10-27 02:41:40.967  5682  5729 I jxcore-log: 2016-10-27 00:41:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:40.967  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:40.967  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:40.967  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:40.967  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:40.967  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:40.967  5682  5729 I jxcore-log: 
,10-27 02:41:40.974  5682  5729 I jxcore-log: 2016-10-27 00:41:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:40.974  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:40.974  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:40.974  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:40.974  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:40.974  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:40.974  5682  5729 I jxcore-log: 
,10-27 02:41:42.002  5682  5729 I jxcore-log: 2016-10-27 00:41:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-27 02:41:42.002  5682  5729 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-27 02:41:42.002  5682  5729 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-27 02:41:42.002  5682  5729 I jxcore-log: emit@events.js:82:1
10-27 02:41:42.002  5682  5729 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-27 02:41:42.002  5682  5729 I jxcore-log: emit@events.js:82:1'
10-27 02:41:42.002  5682  5729 I jxcore-log: 
,10-27 02:41:42.011  5682  5729 E jxcore  : Error!: error is undefined
10-27 02:41:42.011  5682  5729 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"222","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:222:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-27 02:41:42.013  5682  5729 I jxcore-log: 2016-10-27 00:41:42 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-27 02:41:42.013  5682  5729 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:222:1
10-27 02:41:42.013  5682  5729 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-27 02:41:42.013  5682  5729 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-27 02:41:42.013  5682  5729 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-27 02:41:42.013  5682  5729 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-27 02:41:42.013  5682  5729 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-27 02:41:42.013  5682  5729 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-27 02:41:42.015  5682  5729 I jxcore-log: 2016-10-27 00:41:42 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-27 02:41:42.015  5682  5729 I jxcore-log: 
,10-27 02:41:42.017  5682  5729 E jxcore-log: TypeError: 
10-27 02:41:42.017  5682  5729 E jxcore-log: error is undefined
10-27 02:41:42.018  5682  5729 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 222:0)
10-27 02:41:42.018  5682  5729 E jxcore-log: 
,10-27 02:41:42.081   928  3014 W InputDispatcher: channel '979e566 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-27 02:41:42.082   928  3014 E InputDispatcher: channel '979e566 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-27 02:41:42.093   928   939 I WindowState: WIN DEATH: Window{979e566 u0 com.test.thalitest/com.test.thalitest.MainActivity},
10-27 02:41:42.093   928   939 W InputDispatcher: Attempted to unregister already unregistered input channel '979e566 com.test.thalitest/com.test.thalitest.MainActivity (server)'
10-27 02:41:42.093   928  3038 D WifiService: Client connection lost with reason: 4
,10-27 02:41:42.094   928  3869 D GraphicsStats: Buffer count: 2
10-27 02:41:42.096   527   527 I Zygote  : Process 5682 exited cleanly (139)
,10-27 02:41:42.099   928  3872 I ActivityManager: Process com.test.thalitest (pid 5682) has died
,10-27 02:41:42.117   928  3872 I ActivityManager: Start proc 6006:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-27 02:41:42.200  6006  6006 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-27 02:41:42.219  6006  6006 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-27 02:41:42.225  6006  6006 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3761-3763)
,10-27 02:41:42.225  6006  6006 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-27 02:41:42.234  6006  6006 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5bc6e77}
,10-27 02:41:42.234  6006  6006 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-27 02:41:42.235  6006  6006 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-27 02:41:42.238  6006  6006 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-27 02:41:42.239  6006  6006 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-27 02:41:42.249  6006  6006 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-27 02:41:42.258  6006  6006 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-27 02:41:42.258  6006  6006 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-27 02:41:42.258  6006  6006 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-27 02:41:42.258  6006  6006 I Adreno  : Build Date                       : 12/06/15
10-27 02:41:42.258  6006  6006 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-27 02:41:42.258  6006  6006 I Adreno  : Local Branch                     : mybranch17112971
10-27 02:41:42.258  6006  6006 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-27 02:41:42.258  6006  6006 I Adreno  : Remote Branch                    : NONE
10-27 02:41:42.258  6006  6006 I Adreno  : Reconstruct Branch               : NOTHING
,10-27 02:41:42.287   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b573727:true
,10-27 02:41:42.301  3025  3025 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[15993]" dev="sockfs" ino=15993 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-27 02:41:42.301  3025  3025 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[15993]" dev="sockfs" ino=15993 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-27 02:41:42.312  6006  6006 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-27 02:41:42.319  6006  6006 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-27 02:41:42.341   401   401 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[36599]" dev="sockfs" ino=36599 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-27 02:41:42.341   401   401 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[36599]" dev="sockfs" ino=36599 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-27 02:41:42.344  6006  6042 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-27 02:41:42.344  3653  3653 W Binder_6: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[16005]" dev="sockfs" ino=16005 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:41:42.344  3653  3653 W Binder_6: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[16005]" dev="sockfs" ino=16005 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:41:42.349  6006  6029 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-27 02:41:42.381  6006  6042 I OpenGLRenderer: Initialized EGL, version 1.4
,10-27 02:41:42.397   938   938 W Binder_1: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[37030]" dev="sockfs" ino=37030 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:41:42.397   938   938 W Binder_1: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[37030]" dev="sockfs" ino=37030 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:41:42.401   939   939 W Binder_2: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[37029]" dev="sockfs" ino=37029 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-27 02:41:42.401   939   939 W Binder_2: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[37029]" dev="sockfs" ino=37029 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-27 02:41:42.401   928   938 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5682 uid 10077
10-27 02:41:42.403  3734  3734 I Keyboard.Facilitator: onFinishInput()
,10-27 02:41:42.428  6006  6006 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6006
,10-27 02:41:42.430   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +286ms (total +328ms)
,10-27 02:41:42.450  6004  6004 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-27 02:41:42.453  6004  6004 D AndroidRuntime: CheckJNI is OFF
,10-27 02:41:42.475  6004  6004 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-27 02:41:42.499  6006  6006 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-27 02:41:42.499  6004  6004 I Radio-JNI: register_android_hardware_Radio DONE
,10-27 02:41:42.515  6004  6004 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-27 02:41:42.523   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-27 02:41:42.523   928   941 I ActivityManager: Killing 6006:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-27 02:41:42.553   928  3872 I WindowState: WIN DEATH: Window{c35b422 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-27 02:41:42.553   928  3476 D GraphicsStats: Buffer count: 2
,10-27 02:41:42.655   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-27 02:41:42.656   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-27 02:41:42.657   928   941 E ActivityManager: Failure starting process com.test.thalitest
10-27 02:41:42.657   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-27 02:41:42.657   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-27 02:41:42.657   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-27 02:41:42.657   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-27 02:41:42.657   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-27 02:41:42.658   928   941 I ActivityManager:   Force finishing activity ActivityRecord{7d0652e u0 com.test.thalitest/.MainActivity t66}
10-27 02:41:42.659   928   952 I art     : Starting a blocking GC Explicit
,10-27 02:41:42.669   928  3287 W ActivityManager: Spurious death for ProcessRecord{5c36c70 0:com.test.thalitest/u0a77}, curProc for 6006: null
,10-27 02:41:42.750   928   952 I art     : Explicit concurrent mark sweep GC freed 50302(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 1.603ms total 90.263ms
,10-27 02:41:42.769   928   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-27 02:41:42.773  6004  6004 I art     : System.exit called, status: 0
,10-27 02:41:42.773  6004  6004 I AndroidRuntime: VM exiting with result code 0.
,10-27 02:41:42.778   928   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-27 02:41:42.791   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-27 02:41:42.795  5906  5906 D BluetoothMapAppObserver: onReceive
,10-27 02:41:42.795  5906  5906 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-27 02:41:42.797  3734  3734 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-27 02:41:42.800  4126  4238 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-27 02:41:42.813   928  3015 I InputReader: Reconfiguring input devices.  changes=0x00000010
10-27 02:41:42.827  3734  6058 I Keyboard.Facilitator.DecoderInitializer: run()
,10-27 02:41:42.852  3842  3842 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-27 02:41:42.861    27    27 W kworker/1:1: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-27 02:41:42.864  3734  6058 I Decoder : createOrResetDecoder
,10-27 02:41:42.866  3462  6061 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-27 02:41:42.867  3638  3638 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-27 02:41:42.867  3638  3638 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
10-27 02:41:42.867    27    27 W kworker/1:1: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-27 02:41:42.869   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
10-27 02:41:42.878  3883  3977 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-27 02:41:42.882  3920  6064 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-27 02:41:42.882  3920  6064 D AccountUtils: Clearing selected account for com.test.thalitest
,10-27 02:41:42.887    27    27 W kworker/1:1: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-27 02:41:42.892   928   938 I ActivityManager: Start proc 6066:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
10-27 02:41:42.892  3883  3977 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-27 02:41:42.892  3883  3977 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3883
10-27 02:41:42.892  3883  3977 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-27 02:41:42.892  3883  3977 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-27 02:41:42.899   928  6072 E DropBoxManagerService: Can't write: system_app_crash
10-27 02:41:42.899   928  6072 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-27 02:41:42.899   928  6072 E DropBoxManagerService: 	... 5 more
,10-27 02:41:42.900   928   939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-27 02:41:42.906  3883  3977 I Process : Sending signal. PID: 3883 SIG: 9
10-27 02:41:42.917  3920  6064 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-27 02:41:42.967   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,10-27 02:41:42.967   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
10-27 02:41:42.968  3638  3638 I ConfigService: onCreate

```
