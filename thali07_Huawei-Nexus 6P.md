#### Test 92126221e76fa0e_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-03 11:54:12.978  3986  4136 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-03 11:54:13.052  3986  4136 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-03 11:54:13.420  5504  5504 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-03 11:54:13.424  5504  5504 D AndroidRuntime: CheckJNI is OFF
11-03 11:54:13.452  5504  5504 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-03 11:54:13.495  5504  5504 I Radio-JNI: register_android_hardware_Radio DONE
11-03 11:54:13.509  5504  5504 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-03 11:54:13.513   927  3656 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-03 11:54:13.532  3872  3886 W SearchService: Abort, client detached.
11-03 11:54:13.534  5504  5504 D AndroidRuntime: Shutting down VM
11-03 11:54:13.542  3872  4115 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e5b7735
11-03 11:54:13.542  3872  3872 I HotwordDetector: Closing mic
11-03 11:54:13.543  3872  4140 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-03 11:54:13.565   927  3533 I ActivityManager: Start proc 5514:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-03 11:54:13.612   512  4146 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-03 11:54:13.614   512  4146 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-03 11:54:13.622   512  4146 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-03 11:54:13.623   512  4146 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-03 11:54:13.623   512  2933 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-03 11:54:13.627  3872  4135 I MicroRecognitionRnrImpl: Detection finished
11-03 11:54:13.628  3872  4117 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-03 11:54:13.662  5514  5514 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-03 11:54:13.679  5514  5514 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-03 11:54:13.745  5514  5514 I LibraryLoader: Time to load native libraries: 64 ms (timestamps 9528-9592)
11-03 11:54:13.746  5514  5514 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 11:54:13.780  5514  5514 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ce11c2f}
,11-03 11:54:13.780  5514  5514 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 11:54:13.781  5514  5514 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 11:54:13.786  5514  5514 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 11:54:13.788  5514  5514 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 11:54:13.837  5514  5514 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 11:54:13.849  5514  5514 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-03 11:54:13.849  5514  5514 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 11:54:13.849  5514  5514 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 11:54:13.849  5514  5514 I Adreno  : Build Date                       : 12/06/15
11-03 11:54:13.849  5514  5514 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 11:54:13.849  5514  5514 I Adreno  : Local Branch                     : mybranch17112971
11-03 11:54:13.849  5514  5514 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 11:54:13.849  5514  5514 I Adreno  : Remote Branch                    : NONE
11-03 11:54:13.849  5514  5514 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 11:54:13.887   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b933f9b:true
,11-03 11:54:13.921   752   752 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[28180]" dev="sockfs" ino=28180 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 11:54:13.921   752   752 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[28180]" dev="sockfs" ino=28180 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 11:54:13.934  5514  5514 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 11:54:13.942  5514  5514 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 11:54:13.961   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31673]" dev="sockfs" ino=31673 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 11:54:13.966  5514  5551 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 11:54:13.964   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31673]" dev="sockfs" ino=31673 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 11:54:13.967  3674  3674 W Binder_8: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14227]" dev="sockfs" ino=14227 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 11:54:13.967  3674  3674 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14227]" dev="sockfs" ino=14227 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 11:54:13.973  5514  5538 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 11:54:14.007  5514  5551 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 11:54:14.087   937   937 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31676]" dev="sockfs" ino=31676 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 11:54:14.087   937   937 W Binder_1: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31676]" dev="sockfs" ino=31676 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 11:54:14.092   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +559ms
,11-03 11:54:14.097  3579  3579 I Keyboard.Facilitator: onFinishInput()
,11-03 11:54:14.091  3674  3674 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31675]" dev="sockfs" ino=31675 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 11:54:14.091  3674  3674 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31675]" dev="sockfs" ino=31675 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 11:54:14.131  5514  5514 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5514
,11-03 11:54:14.224  5514  5514 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 11:54:14.454  5514  5553 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -606340816
,11-03 11:54:14.458  5514  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-03 11:54:14.458  5514  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-03 11:54:14.458  5514  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-03 11:54:14.458  5514  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-03 11:54:14.458  5514  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-03 11:54:14.458  5514  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@690a032 added. We now have 1 listener(s)
,11-03 11:54:14.460  5514  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-03 11:54:14.462  5514  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 11:54:14.463  5514  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 11:54:14.463  5514  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-03 11:54:14.466  5514  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9542339 added. We now have 1 listener(s)
11-03 11:54:14.466  5514  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 11:54:14.472   927  2889 D WifiService: New client listening to asynchronous messages
11-03 11:54:14.473  5514  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 11:54:14.473  5514  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-03 11:54:14.473  5514  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-03 11:54:14.473  5514  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-03 11:54:14.473  5514  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-03 11:54:14.473  5514  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-03 11:54:14.473  5514  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-03 11:54:14.475  5514  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 11:54:14.475  5514  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 11:54:14.479  5514  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-03 11:54:14.479  5514  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:54:14.479  5514  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:14.479  5514  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:14.479  5514  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:14.479  5514  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:54:14.479  5514  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:14.479  5514  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:54:14.479  5514  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:54:14.479  5514  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-03 11:54:14.479  5514  5553 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 11:54:14.480  5514  5553 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-03 11:54:14.646  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:14.651  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:14.659  5514  5514 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-03 11:54:14.981  5514  5523 I art     : Background sticky concurrent mark sweep GC freed 76893(7MB) AllocSpace objects, 17(1096KB) LOS objects, 24% free, 24MB/32MB, paused 1.066ms total 274.093ms
,11-03 11:54:15.871   927  2888 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 11:54:16.174  5514  5523 I art     : Background partial concurrent mark sweep GC freed 50614(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.030ms total 226.664ms
,11-03 11:54:16.725  5514  5561 W jxcore-log: Initializing JXcore engine
,11-03 11:54:16.725  5514  5561 W jxcore-log: JXcore engine is ready
,11-03 11:54:16.747  5561  5561 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12000 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-03 11:54:16.747  5561  5561 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[12742]" dev="sockfs" ino=12742 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-03 11:54:16.747  5561  5561 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-03 11:54:16.747  5561  5561 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32976]" dev="sockfs" ino=32976 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-03 11:54:16.758  5514  5561 W jxcore-log: Starting JXcore engine
,11-03 11:54:16.808  5514  5561 W jxcore-log: Platform android
11-03 11:54:16.808  5514  5561 W jxcore-log: 
,11-03 11:54:16.808  5514  5561 W jxcore-log: Process ARCH arm
11-03 11:54:16.808  5514  5561 W jxcore-log: 
,11-03 11:54:16.987  5514  5561 I jxcore-log: JXcore Cordova bridge is ready!
11-03 11:54:16.987  5514  5561 I jxcore-log: 
,11-03 11:54:16.988  5514  5561 W jxcore-log: JXcore engine is started
,11-03 11:54:16.999  5514  5553 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-03 11:54:17.002  5514  5514 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-03 11:54:17.093  3517  3517 I ConfigService: onDestroy
,11-03 11:54:18.545   927   938 I ActivityManager: Killing 5296:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-03 11:54:18.584   927   938 I ActivityManager: Killing 4953:com.google.android.apps.maps/u0a58 (adj 15): empty #18
,11-03 11:54:18.591   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:54:19.591   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:54:20.592   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:54:21.593   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:54:22.595   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:54:23.595   559   559 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 11:54:26.669  5514  5561 I jxcore-log: 2016-11-03 10:54:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-03 11:54:26.669  5514  5561 I jxcore-log: 
,11-03 11:54:26.671  5514  5561 I jxcore-log: 2016-11-03 10:54:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-03 11:54:26.671  5514  5561 I jxcore-log: 
,11-03 11:54:26.694  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:54:26.694  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:26.694  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:26.694  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:26.694  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:54:26.694  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:26.694  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:54:26.694  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:54:26.695  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 11:54:26.697  5514  5561 I jxcore-log: 2016-11-03 10:54:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-03 11:54:26.697  5514  5561 I jxcore-log: 
11-03 11:54:26.698  5514  5561 I jxcore-log: 2016-11-03 10:54:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-03 11:54:26.698  5514  5561 I jxcore-log: 
,11-03 11:54:26.743  3872  5562 W CronetSyncConnectionRcs: Upload content type not set.
,11-03 11:54:26.806  4770  4817 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-03 11:54:26.807  4770  4770 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-03 11:54:26.931  5514  5561 I jxcore-log: 2016-11-03 10:54:26 - DEBUG UnitTest_app: 'Running unit tests'
11-03 11:54:26.931  5514  5561 I jxcore-log: 
11-03 11:54:26.932  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 11:54:26.932  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@302e5 added. We now have 2 listener(s)
,11-03 11:54:26.933  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 11:54:26.933  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:54:26.933  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 11:54:26.933  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:54:26.933  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4831ba added. We now have 2 listener(s)
11-03 11:54:26.933  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:54:26.933  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 11:54:26.935  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 11:54:26.937  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:54:26.937  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:26.937  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:26.937  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:26.937  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:54:26.937  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:26.937  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:54:26.937  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:54:26.938  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 11:54:26.938  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 11:54:26.938  5514  5561 D executeNativeTests: Running unit tests
,11-03 11:54:26.940  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:26.943  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:26.972  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 11:54:26.972  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 added. We now have 3 listener(s)
11-03 11:54:26.973  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 11:54:26.973  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:54:26.973  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 11:54:26.973  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:54:26.973  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 added. We now have 3 listener(s)
11-03 11:54:26.973  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:54:26.973  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 11:54:26.975  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 11:54:26.977  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:54:26.977  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:26.977  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:26.977  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:26.977  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:54:26.977  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:26.977  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:54:26.977  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:54:26.978  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:26.978  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 11:54:26.979  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 11:54:26.979  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 11:54:26.979  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 11:54:26.979  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 11:54:26.980  5514  5561 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-03 11:54:26.980  5514  5561 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 11:54:26.980  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 11:54:26.980  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 11:54:26.980  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 11:54:26.980  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 11:54:26.980  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:26.981  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 11:54:26.981  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:26.981  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:26.981  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:26.981  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:54:26.981  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:26.982  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 11:54:26.982  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 removed from the list
11-03 11:54:26.982  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:26.982  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 removed from the list
,11-03 11:54:26.982  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:26.983  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:26.983  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:26.984  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:26.984  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:26.985  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:26.988  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:26.988  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:26.988  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:26.988  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:26.988  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 11:54:26.988  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:26.988  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:26.988  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
,11-03 11:54:26.990  5514  5561 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-03 11:54:26.991  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:26.991  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:26.991  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:26.991  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:26.991  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:26.991  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:26.991  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:26.991  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
,11-03 11:54:26.991  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:26.991  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:26.991  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:26.991  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:26.991  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:26.991  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:26.991  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:26.991  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:26.992  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:26.992  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:26.992  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:26.992  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:26.992  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:26.992  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:26.992  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
,11-03 11:54:26.994  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 11:54:26.995  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-03 11:54:26.995  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:26.995  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:26.996  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:26.996  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:26.996  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:26.996  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:26.996  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:26.996  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:26.996  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:26.996  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:26.996  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:26.996  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:26.996  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:26.996  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:26.996  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:26.996  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:26.997  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:26.997  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:26.997  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:26.997  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:26.997  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:26.997  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:26.997  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:26.997  5514  5561 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 11:54:26.998  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 11:54:27.000  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:54:27.000  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:27.000  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:27.000  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:27.000  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:54:27.000  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:27.000  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:54:27.000  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:54:27.001  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:27.001  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 11:54:27.001  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 11:54:27.001  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 11:54:27.001  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 11:54:27.001  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 11:54:27.001  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 11:54:27.003  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 11:54:27.003  5514  5561 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 11:54:27.003  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 11:54:27.003  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:27.005  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:27.005  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:27.005  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 11:54:27.006  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 11:54:27.006  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 11:54:27.007  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 11:54:27.007  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-03 11:54:27.008  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-03 11:54:27.009  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:27.009  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 11:54:27.009  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 11:54:27.009  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 11:54:27.009  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 11:54:27.009  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:27.010  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:54:27.012  4573  4786 D BtGatt.GattService: registerClient() - UUID=0e7ffc33-5c78-4bc0-8f08-3fe70e0a388c
11-03 11:54:27.012  4573  4638 D BtGatt.GattService: onClientRegistered() - UUID=0e7ffc33-5c78-4bc0-8f08-3fe70e0a388c, clientIf=5
11-03 11:54:27.013  5514  5525 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 11:54:27.014  4573  4586 D BtGatt.GattService: start scan with filters
11-03 11:54:27.018  4573  4641 D BtGatt.ScanManager: handling starting scan
11-03 11:54:27.018  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 11:54:27.018  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:27.018  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 11:54:27.018  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:27.018  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 11:54:27.018  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 11:54:27.018  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:54:27.018  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 11:54:27.018  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 11:54:27.019  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 11:54:27.019  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 11:54:27.019  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 11:54:27.019  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:27.019  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 11:54:27.019  4573  4641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
11-03 11:54:27.020  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:27.020  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:54:27.020  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:27.020  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:27.020  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:54:27.020  5514  5561 I io.jxcore.node.ConnectionHelper: start: OK
11-03 11:54:27.022  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 11:54:27.022  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:27.022  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:27.022  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:54:27.022  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:54:27.026  4573  4638 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 11:54:27.026  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:27.027  4573  4641 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 11:54:27.032  4573  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 11:54:27.032  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:27.032  4573  4641 D BtGatt.ScanManager: Starting BLE batch scan
11-03 11:54:27.032  4573  4641 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 11:54:27.040  4573  4638 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 11:54:27.041  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:27.045  4573  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 11:54:27.045  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:54:27.524  5514  5514 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-03 11:54:27.525  5514  5514 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 11:54:27.525  5514  5514 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 11:54:32.024  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 11:54:32.025  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:32.025  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 11:54:32.025  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:54:32.025  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-03 11:54:32.025  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:32.025  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 11:54:32.025  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-03 11:54:32.025  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 11:54:32.025  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 11:54:32.026  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:32.026  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:32.026  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.027  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 11:54:32.027  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.028  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:54:32.028  4573  4587 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 11:54:32.029  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-03 11:54:32.030  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:54:32.031  4573  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 11:54:32.031  4573  4786 D BtGatt.GattService: stopScan() - queue size =1
11-03 11:54:32.032  4573  4586 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 11:54:32.032  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 11:54:32.032  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.032  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-03 11:54:32.033  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.033  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:32.033  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.033  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.034  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 11:54:32.034  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.034  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.034  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.034  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 11:54:32.035  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 11:54:32.036  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:54:32.036  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:32.037  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.038  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 11:54:32.038  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.038  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:32.038  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:32.038  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:32.038  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:54:32.038  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:32.038  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:32.038  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:54:32.039  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:32.039  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:32.039  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:32.039  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:54:32.039  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:32.039  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 11:54:32.040  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:54:32.040  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 11:54:32.040  4573  4573 D BtGatt.ScanManager: awakened up at time 97887
11-03 11:54:32.040  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 11:54:32.041  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 11:54:32.041  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 11:54:32.041  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 11:54:32.041  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:54:32.047  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 11:54:32.047  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:32.049  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:32.050  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:54:32.050  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 11:54:32.057  4573  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-03 11:54:32.057  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:32.058  4573  4638 D BtGatt.GattService: current time is 97904658944
11-03 11:54:32.058  4573  4638 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -95, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -76, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 11:54:32.060  4573  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 11:54:32.061  4573  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 11:54:32.062  4573  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 11:54:32.070  4573  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 11:54:32.070  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:32.071  4573  4641 D BtGatt.ScanManager: stopping BLe Batch
,11-03 11:54:32.077  4573  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 11:54:32.077  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:54:32.077  4573  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 11:54:32.083  4573  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 11:54:32.083  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:54:32.551  5514  5514 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 11:54:37.041  5514  5561 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-03 11:54:37.044  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 11:54:37.050  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:54:37.050  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:37.050  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:37.050  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:37.050  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:54:37.050  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:37.050  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:54:37.050  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:54:37.053  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 11:54:37.054  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 11:54:37.054  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 11:54:37.054  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 11:54:37.055  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-03 11:54:37.055  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 11:54:37.055  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 11:54:37.060  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:37.064  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 11:54:37.065  5514  5561 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 11:54:37.065  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 11:54:37.069  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:37.074  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.074  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 11:54:37.076  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-03 11:54:37.076  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 11:54:37.076  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 11:54:37.082  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.082  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 11:54:37.082  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 11:54:37.083  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 11:54:37.083  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 11:54:37.083  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.084  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:54:37.089  4573  4796 D BtGatt.GattService: registerClient() - UUID=72ef55d1-76a3-4b6e-9a2e-0c1d0702b9a2
,11-03 11:54:37.089  4573  4638 D BtGatt.GattService: onClientRegistered() - UUID=72ef55d1-76a3-4b6e-9a2e-0c1d0702b9a2, clientIf=5
11-03 11:54:37.091  5514  5524 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 11:54:37.091  4573  4786 D BtGatt.GattService: start scan with filters
,11-03 11:54:37.095  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 11:54:37.095  4573  4641 D BtGatt.ScanManager: handling starting scan
11-03 11:54:37.095  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.095  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-03 11:54:37.095  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.096  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 11:54:37.096  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 11:54:37.096  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.096  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 11:54:37.096  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 11:54:37.096  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-03 11:54:37.096  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.096  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 11:54:37.097  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 11:54:37.098  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.100  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.101  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:54:37.101  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:37.101  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.101  5514  5561 I io.jxcore.node.ConnectionHelper: start: OK
11-03 11:54:37.101  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.103  4573  4638 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 11:54:37.103  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:37.104  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:37.104  5514  5561 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-03 11:54:37.104  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:37.104  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 11:54:37.104  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:54:37.105  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-03 11:54:37.105  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 11:54:37.105  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 11:54:37.108  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 11:54:37.108  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.108  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.108  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-03 11:54:37.108  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:54:37.108  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 11:54:37.108  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 11:54:37.109  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-03 11:54:37.109  4573  4641 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 11:54:37.109  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.109  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.109  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:37.109  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 11:54:37.109  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:37.110  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:54:37.110  4573  4786 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 11:54:37.110  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 11:54:37.111  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:54:37.111  4573  4586 D BtGatt.GattService: stopScan() - queue size =1
11-03 11:54:37.112  4573  4587 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 11:54:37.112  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 11:54:37.112  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.112  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 11:54:37.112  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.113  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.113  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.113  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.113  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 11:54:37.113  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:37.113  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.113  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.113  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 11:54:37.113  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 11:54:37.114  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:54:37.114  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.114  4573  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 11:54:37.114  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:37.115  4573  4641 D BtGatt.ScanManager: Starting BLE batch scan
11-03 11:54:37.115  4573  4641 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 11:54:37.115  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:37.115  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 11:54:37.116  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.116  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.116  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:37.116  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:37.116  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:54:37.116  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:54:37.116  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 11:54:37.116  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:54:37.116  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:37.116  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:37.116  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 11:54:37.116  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.116  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 11:54:37.116  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 11:54:37.116  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.117  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.116  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:37.117  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 11:54:37.117  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:37.117  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.117  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:37.118  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.118  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.118  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.118  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.118  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 11:54:37.118  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:37.118  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:37.118  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:37.120  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.121  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.121  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.121  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:37.121  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 11:54:37.121  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:37.121  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:37.122  5514  5561 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 11:54:37.124  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 11:54:37.128  4573  4638 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-03 11:54:37.128  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:54:37.129  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:54:37.129  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:37.129  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:37.129  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:37.129  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:54:37.129  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:37.129  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:54:37.129  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:54:37.131  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:37.131  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 11:54:37.131  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 11:54:37.131  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 11:54:37.131  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 11:54:37.131  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 11:54:37.131  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 11:54:37.133  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:37.135  4573  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 11:54:37.135  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 11:54:37.135  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:54:37.135  5514  5561 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 11:54:37.135  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 11:54:37.137  4573  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 11:54:37.138  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:37.138  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.138  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 11:54:37.139  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 11:54:37.139  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 11:54:37.139  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 11:54:37.141  4573  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 11:54:37.141  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:37.141  4573  4638 E BtGatt.ContextMap: Context not found for ID 5
11-03 11:54:37.142  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:37.142  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 11:54:37.142  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 11:54:37.142  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-03 11:54:37.142  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 11:54:37.142  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.142  5514  5561 D BluetoothAdapter: STATE_ON
,11-03 11:54:37.144  4573  4794 D BtGatt.GattService: registerClient() - UUID=7fa8f990-e2e5-4798-b731-5c76dac6c3ab
11-03 11:54:37.145  4573  4638 D BtGatt.GattService: onClientRegistered() - UUID=7fa8f990-e2e5-4798-b731-5c76dac6c3ab, clientIf=5
11-03 11:54:37.145  5514  5525 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 11:54:37.145  4573  4587 D BtGatt.GattService: start scan with filters
,11-03 11:54:37.148  4573  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 11:54:37.148  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:37.148  4573  4641 D BtGatt.ScanManager: stopping BLe Batch
,11-03 11:54:37.148  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 11:54:37.149  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.149  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 11:54:37.149  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.149  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 11:54:37.149  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 11:54:37.149  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.149  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 11:54:37.149  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 11:54:37.149  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-03 11:54:37.149  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.149  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 11:54:37.150  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 11:54:37.150  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.152  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.152  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:54:37.152  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.152  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:37.152  5514  5561 I io.jxcore.node.ConnectionHelper: start: OK
11-03 11:54:37.152  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.154  4573  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 11:54:37.154  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:54:37.154  4573  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 11:54:37.155  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.155  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.156  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.156  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:54:37.156  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 11:54:37.159  4573  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 11:54:37.159  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:37.160  4573  4641 D BtGatt.ScanManager: handling starting scan
11-03 11:54:37.165  4573  4638 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 11:54:37.165  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:37.165  4573  4641 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 11:54:37.170  4573  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 11:54:37.170  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:37.170  4573  4641 D BtGatt.ScanManager: Starting BLE batch scan
11-03 11:54:37.170  4573  4641 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 11:54:37.178  4573  4638 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 11:54:37.179  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:54:37.183  4573  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 11:54:37.184  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:54:37.657  5514  5514 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-03 11:54:37.657  5514  5514 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 11:54:37.658  5514  5514 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 11:54:39.110   927  2890 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 11:54:39.115   927  2890 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-03 11:54:42.138   927  2890 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 11:54:42.144   927  2890 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-03 11:54:42.153  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 11:54:42.154  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:42.154  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 11:54:42.154  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:42.154  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-03 11:54:42.154  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:42.154  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 11:54:42.154  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-03 11:54:42.155  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-03 11:54:42.155  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-03 11:54:42.155  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:42.155  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.155  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.155  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-03 11:54:42.156  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.157  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:54:42.158  4573  4587 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 11:54:42.158  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 11:54:42.159  4573  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 11:54:42.159  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:54:42.161  4573  4786 D BtGatt.GattService: stopScan() - queue size =1
11-03 11:54:42.162  4573  4796 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 11:54:42.163  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 11:54:42.163  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.163  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-03 11:54:42.163  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.164  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.164  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.164  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.164  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 11:54:42.164  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.165  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.165  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.165  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-03 11:54:42.165  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 11:54:42.165  4573  4573 D BtGatt.ScanManager: awakened up at time 108012
11-03 11:54:42.167  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:54:42.167  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.168   927  3729 I ActivityManager: Killing 5308:com.android.chrome/u0a39 (adj 15): empty #17
11-03 11:54:42.169  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:42.169  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 11:54:42.170  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.170  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:42.170  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:54:42.172  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:54:42.172  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 11:54:42.173  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:54:42.173  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 11:54:42.173  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 11:54:42.173  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 11:54:42.175  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 11:54:42.175  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 11:54:42.175  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:54:42.178  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 11:54:42.178  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 11:54:42.178  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:54:42.178  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:54:42.178  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 11:54:42.206  4573  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-03 11:54:42.206  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:42.206  4573  4638 D BtGatt.GattService: current time is 108053204958
11-03 11:54:42.206  4573  4638 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -95, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 11:54:42.207  4573  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 11:54:42.207  4573  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 11:54:42.207  4573  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 11:54:42.207  4573  4638 E BtGatt.ContextMap: Context not found for ID 5
,11-03 11:54:42.213  4573  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 11:54:42.213  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:42.213  4573  4641 D BtGatt.ScanManager: stopping BLe Batch
,11-03 11:54:42.218  4573  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 11:54:42.219  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:54:42.219  4573  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 11:54:42.224  4573  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 11:54:42.224  4573  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:54:42.679  5514  5514 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 11:54:42.679  5514  5514 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:42.680  5514  5514 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 11:54:47.172  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 11:54:47.172  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:47.172  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:47.172  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:47.173  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.173  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-03 11:54:47.173  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.173  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:47.173  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.174  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.174  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 11:54:47.174  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.175  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.176  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.176  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:47.179  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.179  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.179  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.180  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:47.180  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 11:54:47.180  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.180  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.181  5514  5561 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-03 11:54:47.183  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:47.183  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 11:54:47.184  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:47.184  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:47.184  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.184  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.184  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.184  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:47.185  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:54:47.185  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.185  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:47.185  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.185  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.185  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.185  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:47.186  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.189  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.190  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.190  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.190  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:47.190  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:47.190  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:54:47.191  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
,11-03 11:54:47.192  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 11:54:47.192  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 11:54:47.192  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:47.192  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:47.192  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:47.192  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:54:47.192  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.193  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.193  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:47.193  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:54:47.193  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.193  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:47.193  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:54:47.193  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.193  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.193  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.193  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:47.195  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.195  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.195  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.195  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:47.195  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:47.195  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.195  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.196  5514  5561 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-03 11:54:47.196  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:47.196  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:47.196  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 11:54:47.197  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:47.197  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.197  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.197  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.197  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:47.197  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.197  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.197  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:47.197  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.197  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.197  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.197  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:47.197  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.198  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.199  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.199  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.199  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:47.199  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:47.199  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.199  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.200  5514  5561 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-03 11:54:47.200  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 11:54:47.200  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:47.200  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:47.200  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:47.200  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.200  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.200  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.200  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
,11-03 11:54:47.200  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.201  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.201  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:47.201  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.201  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.201  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.201  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:47.201  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:47.202  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.203  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.203  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:47.203  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:47.203  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:47.203  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.203  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.204  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 11:54:47.204  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 11:54:47.204  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 11:54:47.204  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 11:54:47.204  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 11:54:47.204  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 11:54:47.204  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 11:54:47.205  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 11:54:47.205  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 11:54:47.205  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:47.205  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:47.205  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:47.205  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:47.205  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.205  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.205  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.205  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
,11-03 11:54:47.205  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.205  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.206  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:47.206  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.206  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.206  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.206  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.206  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.207  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.207  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.207  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:47.208  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:47.208  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:47.208  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.208  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.209  5514  5561 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 11:54:47.209  5514  5561 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 11:54:47.209  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-03 11:54:47.212  5514  5561 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 11:54:47.212  5514  5561 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,11-03 11:54:47.212  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 11:54:47.212  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 11:54:47.212  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 11:54:47.212  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-03 11:54:47.212  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 11:54:47.212  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 11:54:47.212  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-03 11:54:47.213  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-03 11:54:47.214  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 11:54:47.214  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 11:54:47.214  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 11:54:47.214  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 11:54:47.214  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-03 11:54:47.214  5514  5561 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-03 11:54:47.214  5514  5561 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 11:54:47.214  5514  5561 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-03 11:54:47.214  5514  5561 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 11:54:47.214  5514  5561 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 11:54:47.215  5514  5561 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-03 11:54:47.215  5514  5561 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-03 11:54:47.215  5514  5561 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 11:54:47.215  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-03 11:54:47.218  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-03 11:54:47.219  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-03 11:54:47.219  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-03 11:54:47.220  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-03 11:54:47.220  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-03 11:54:47.220  5514  5561 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-03 11:54:47.220  5514  5561 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 11:54:47.220  5514  5561 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-03 11:54:47.221  5514  5567 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
11-03 11:54:47.221  5514  5567 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-03 11:54:47.221  5514  5567 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-03 11:54:47.221  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:47.221  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 11:54:47.221  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:47.221  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:47.221  5514  5567 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-03 11:54:47.221  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.221  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.222  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.222  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-03 11:54:47.222  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
,11-03 11:54:47.223  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.223  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.223  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:47.223  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.223  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.223  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.223  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.223  5514  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
11-03 11:54:47.224  5514  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,11-03 11:54:47.224  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.225  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:47.225  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.225  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.225  5514  5567 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,11-03 11:54:47.225  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:47.225  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:47.225  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.225  5514  5567 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 11:54:47.225  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.226  5514  5561 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-03 11:54:47.227  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:47.227  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:47.227  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:47.227  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:47.227  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.227  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.227  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.227  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:47.227  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.228  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.228  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:47.228  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.228  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.228  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.228  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.228  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.224  4786  4786 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33916]" dev="sockfs" ino=33916 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 11:54:47.224  4786  4786 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33916]" dev="sockfs" ino=33916 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 11:54:47.229  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.230  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.230  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.230  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:47.230  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:47.230  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:54:47.231  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.231  5514  5561 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-03 11:54:47.232  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:47.232  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:47.232  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:47.232  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 11:54:47.232  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.232  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.232  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.232  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:47.232  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.232  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.232  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:47.232  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.232  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:47.232  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.232  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.232  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.234  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.234  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.234  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.234  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:47.234  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:47.234  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.234  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
,11-03 11:54:47.235  5514  5561 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-03 11:54:47.235  5514  5561 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-03 11:54:47.235  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 11:54:47.235  5514  5561 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-03 11:54:47.235  5514  5561 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 11:54:47.235  5514  5561 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-03 11:54:47.235  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 11:54:47.235  5514  5561 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-03 11:54:47.235  5514  5561 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 11:54:47.235  5514  5561 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 11:54:47.235  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 11:54:47.235  5514  5561 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-03 11:54:47.236  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 11:54:47.236  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:47.236  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:47.236  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:47.236  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.236  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.236  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.236  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:47.236  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.236  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
,11-03 11:54:47.236  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:47.236  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.236  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.236  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.236  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:47.236  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:47.238  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.238  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.238  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:47.238  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 11:54:47.238  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:47.238  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.238  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.238  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:47.239  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:47.239  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:47.239  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:47.239  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:47.239  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:47.239  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:47.239  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:47.239  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:54:47.239  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:48.596   559   559 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-03 11:54:48.597   559   559 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 11:54:52.240  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:52.240  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.240  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:52.241  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:54:52.241  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.241  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 11:54:52.241  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:52.241  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:52.242  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 11:54:52.242  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:52.242  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:52.242  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.242  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.243  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:52.243  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:52.243  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:54:52.243  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.243  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:52.244  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.244  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.245  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.245  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.246  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:52.250  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.251  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.251  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:52.251  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:52.251  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:52.251  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:54:52.251  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.256  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-03 11:54:52.257  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 11:54:52.259  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-03 11:54:52.260  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 11:54:52.260  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-03 11:54:52.261  5514  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-03 11:54:52.261  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 11:54:52.262  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 11:54:52.262  5514  5514 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-03 11:54:52.262  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-03 11:54:52.263  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:52.263  5514  5569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 11:54:52.263  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 11:54:52.263  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 11:54:52.264  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 11:54:52.264  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.264  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 11:54:52.264  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-03 11:54:52.261  4794  4794 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[30354]" dev="sockfs" ino=30354 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 11:54:52.261  4794  4794 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30354]" dev="sockfs" ino=30354 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 11:54:52.264  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
,11-03 11:54:52.264  5514  5514 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 11:54:52.264  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:54:52.265  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 11:54:52.265  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 11:54:52.265  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 11:54:52.265  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.265  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:52.265  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.267  5514  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 11:54:52.267  5514  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 11:54:52.267  5514  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 11:54:52.268  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.268  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 11:54:52.268  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.268  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.268  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.268  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:54:52.269  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 11:54:52.269  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:54:52.269  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:52.269  5514  5514 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 11:54:52.269  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 11:54:52.269  5514  5514 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:52.269  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:52.269  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 11:54:52.269  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.269  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.269  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:52.269  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:52.269  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:52.270  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.270  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:52.270  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.270  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:52.270  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.270  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.271  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:52.273  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.273  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.273  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.274  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:52.274  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 11:54:52.274  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:52.274  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.276  5514  5561 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-03 11:54:52.276  5514  5561 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 11:54:52.277  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-03 11:54:52.277  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 11:54:52.277  5514  5561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 11:54:52.277  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:52.277  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:52.277  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:52.277  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:52.277  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.278  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:52.278  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:52.278  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:52.278  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:52.278  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.278  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:54:52.278  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:54:52.278  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.278  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.278  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.279  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.283  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.283  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:52.283  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.283  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:52.283  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:52.283  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:52.283  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
,11-03 11:54:52.289  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 11:54:52.289  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:52.289  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:52.289  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:54:52.289  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.289  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:52.289  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:52.289  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
11-03 11:54:52.289  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:52.290  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.290  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 11:54:52.290  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.290  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.290  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.290  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:52.290  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.292  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.292  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.292  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:54:52.292  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:54:52.292  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:52.293  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:52.293  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.294  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:54:52.294  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:54:52.294  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:54:52.294  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 11:54:52.294  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.294  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.294  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:54:52.294  5514  5561 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054af8 not in the list
,11-03 11:54:52.294  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:52.295  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.295  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 11:54:52.295  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.295  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:52.295  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:52.295  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:54:52.295  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.296  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.297  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.297  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:54:52.297  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 11:54:52.297  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:54:52.297  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:54:52.297  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e8abd1 not in the list
11-03 11:54:52.299  5514  5561 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-03 11:54:52.299  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 11:54:52.299  5514  5561 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-03 11:54:52.299  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 11:54:52.299  5514  5561 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-03 11:54:52.300  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 11:54:52.302  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 11:54:52.302  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-03 11:54:52.302  5514  5561 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-03 11:54:52.302  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 11:54:52.302  5514  5561 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-03 11:54:52.303  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 11:54:52.303  5514  5561 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-03 11:54:52.303  5514  5561 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-03 11:54:52.303  5514  5561 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-03 11:54:52.303  5514  5561 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-03 11:54:52.304  5514  5561 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-03 11:54:52.304  5514  5561 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-03 11:54:52.304  5514  5561 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-03 11:54:52.304  5514  5561 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-03 11:54:52.306  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:54:52.306  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d2184b added. We now have 3 listener(s)
11-03 11:54:52.306  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:54:52.308  5514  5561 D BluetoothAdapter: enable(): BT is already enabled..!
,11-03 11:54:52.308   927  4880 D WifiService: setWifiEnabled: true pid=5514, uid=10077
11-03 11:54:52.308   927  4880 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 11:54:52.355  4573  4777 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-03 11:54:52.355  5514  5567 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-03 11:54:52.355  5514  5567 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
,11-03 11:54:52.356  4573  4784 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-03 11:54:52.356  5514  5567 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,11-03 11:54:52.770  5514  5514 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 11:54:53.597   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:54:54.598   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:54:55.599   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:54:55.875   927  2888 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 11:54:56.600   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:54:57.314  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 11:54:57.314  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5dd6228 added. We now have 4 listener(s)
,11-03 11:54:57.314  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 11:54:57.328  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:54:57.328  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5dd6228 removed from the list
,11-03 11:54:57.328  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 11:54:57.328  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:54:57.329  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:57.331  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 11:54:57.332  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61b2b41 added. We now have 4 listener(s)
,11-03 11:54:57.332  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:54:57.335  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:54:57.335  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61b2b41 removed from the list
11-03 11:54:57.336  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 11:54:57.336  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:54:57.336  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:54:57.338  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:54:57.338  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60568e6 added. We now have 4 listener(s)
11-03 11:54:57.338  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:54:57.344   927  4880 D WifiService: setWifiEnabled: false pid=5514, uid=10077
11-03 11:54:57.344   927  4880 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 11:54:57.352   927  2888 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-03 11:54:57.352   927  2888 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-03 11:54:57.353   927  2888 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 11:54:57.353   927  2888 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 11:54:57.359  4573  4634 D BluetoothAdapterState: Current state: ON, message: 23
11-03 11:54:57.359  4573  4634 D BluetoothAdapterProperties: Setting state to 13
11-03 11:54:57.359  4573  4634 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-03 11:54:57.361  4573  4634 D BluetoothAdapterProperties: onBluetoothDisable()
,11-03 11:54:57.360  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 11:54:57.363  4573  4634 I BluetoothAdapterState: Entering PendingCommandState
,11-03 11:54:57.366  4573  4638 D BluetoothAdapterProperties: Scan Mode:20
,11-03 11:54:57.366  4573  4634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-03 11:54:57.368  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.368  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:54:57.368  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.368  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.368  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:57.368  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.368  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:57.368  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:54:57.368  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:54:57.370  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.370  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:57.371  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 11:54:57.374  4573  4573 D BluetoothMapService: onReceive
11-03 11:54:57.374  4573  4573 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 11:54:57.374  4573  4573 D BluetoothMapService: STATE_TURNING_OFF
11-03 11:54:57.374  4573  4573 D BluetoothMapService: MAP Service closeService in
,11-03 11:54:57.374  4573  4573 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 11:54:57.374  4573  4573 D ObexServerSockets0: shutdown(block = true)
11-03 11:54:57.375  4573  4573 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 11:54:57.375  4573  4797 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-03 11:54:57.375  4573  4573 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-03 11:54:57.376  4573  4784 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 11:54:57.376  4573  4798 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 11:54:57.377  4573  4573 I BtOppRfcommListener: stopping Accept Thread
11-03 11:54:57.377  4573  5222 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-03 11:54:57.377   927  5270 D DhcpClient: Clearing IP address
11-03 11:54:57.378   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-03 11:54:57.378  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:57.383  4573  5222 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-03 11:54:57.383  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:57.388  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.388  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.388  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.388  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.388  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:57.388  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.388  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:57.388  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:54:57.388  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:54:57.389  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.389  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 11:54:57.390   507   920 D CommandListener: Setting iface cfg
11-03 11:54:57.391   927   940 I ActivityManager: Start proc 5574:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-03 11:54:57.393   927  5271 D DhcpClient: Receive thread stopped
11-03 11:54:57.394  4573  4573 D HeadsetService: Received stop request...Stopping profile...
,11-03 11:54:57.396   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-03 11:54:57.396  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.397  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.397  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.397  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.397  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:57.397  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.397  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:54:57.397  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:54:57.397  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:54:57.397   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-03 11:54:57.397  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 11:54:57.397  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 11:54:57.399   927   927 D RttService: SCAN_AVAILABLE : 1
,11-03 11:54:57.400  3517  5321 V NativeCrypto: Read error: ssl=0x7f816a0e00: I/O error during system call, Connection timed out
11-03 11:54:57.400   927  2995 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 11:54:57.400   555   555 E Parcel  : Reading a NULL string not supported here.
,11-03 11:54:57.400  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.400  3685  3715 D BluetoothHeadset: Proxy object disconnected
11-03 11:54:57.400  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.400  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.400  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.400  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:57.400  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.400  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:54:57.400  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:54:57.400  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:54:57.400   927   927 D BluetoothHeadset: Proxy object disconnected
11-03 11:54:57.401   927   927 D BluetoothHeadset: Proxy object disconnected
11-03 11:54:57.401   927   927 D BluetoothHeadset: Proxy object disconnected
11-03 11:54:57.401  3067  3079 D BluetoothHeadset: Proxy object disconnected
11-03 11:54:57.401  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.401  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:54:57.402  3517  5321 V NativeCrypto: SSL shutdown failed: ssl=0x7f816a0e00: I/O error during system call, Broken pipe
11-03 11:54:57.402  4573  4573 D A2dpService: Received stop request...Stopping profile...
11-03 11:54:57.402  4573  4789 D A2dpStateMachine: Exit Disconnected: -1
11-03 11:54:57.404   927   927 D BluetoothA2dp: Proxy object disconnected
,11-03 11:54:57.404  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-03 11:54:57.404  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-03 11:54:57.404  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:54:57.405  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 11:54:57.405  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-03 11:54:57.405  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-03 11:54:57.405  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:54:57.405  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 11:54:57.405  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 11:54:57.405  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.405  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.405  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.405  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:57.405  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.405  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:54:57.405  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:54:57.405  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:54:57.406  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.406  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:54:57.407  4573  4573 D HidService: Received stop request...Stopping profile...
11-03 11:54:57.408  4573  4573 D HidService: Stopping Bluetooth HidService
11-03 11:54:57.408  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.408  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.408  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.408  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.408  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:57.408  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.408  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:54:57.408  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:54:57.408  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:54:57.409  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.409  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:54:57.409   927  2890 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-03 11:54:57.411  3650  3772 W QCNEJ   : |CORE| network lost: 100
11-03 11:54:57.412  3650  3772 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-03 11:54:57.412   927  2888 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-03 11:54:57.413  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:57.413  4573  4573 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-03 11:54:57.413  4573  4573 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 11:54:57.414  4573  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 11:54:57.414  4573  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 11:54:57.414  4573  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 11:54:57.414  4573  4573 D HealthService: Received stop request...Stopping profile...
11-03 11:54:57.414  4573  4638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 11:54:57.415  4573  4638 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 11:54:57.415  3067  3067 D HeadsetProfile: Bluetooth service disconnected
11-03 11:54:57.416  4573  4573 D PanService: Received stop request...Stopping profile...
11-03 11:54:57.418  4573  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 11:54:57.418  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-03 11:54:57.418  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-03 11:54:57.418  4573  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 11:54:57.418  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:54:57.418  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:54:57.419  4573  4573 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-03 11:54:57.419  4573  4573 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 11:54:57.419  3067  3067 D BluetoothA2dp: Proxy object disconnected
11-03 11:54:57.419  4573  4777 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 11:54:57.419  4573  4573 D BluetoothMapService: Received stop request...Stopping profile...
11-03 11:54:57.419  4573  4777 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-03 11:54:57.419  4573  4777 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-03 11:54:57.419  4573  4573 D BluetoothMapService: stop()
,11-03 11:54:57.419  4573  4777 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-03 11:54:57.419   927  2888 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 11:54:57.419  4573  4638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 11:54:57.420  4573  4638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 11:54:57.419  3067  3067 D BluetoothInputDevice: Proxy object disconnected
,11-03 11:54:57.420  3067  3067 D HidProfile: Bluetooth service disconnected
11-03 11:54:57.420  4573  4573 D BluetoothMapAppObserver: deinitObservers()
11-03 11:54:57.420  4573  4573 D BluetoothMapAppObserver: removeReceiver()
,11-03 11:54:57.422  4573  4573 D SapService: Received stop request...Stopping profile...
,11-03 11:54:57.422  4573  4573 V SapService: stop()
,11-03 11:54:57.424  4573  4573 V BluetoothAdapterState: isTurningOff()=true
,11-03 11:54:57.424  4573  4573 V BluetoothAdapterState: isTurningOn()=false
,11-03 11:54:57.424  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 11:54:57.424  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:54:57.424  4573  4573 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-03 11:54:57.424  4573  4638 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-03 11:54:57.424  4573  4573 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 11:54:57.424  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-03 11:54:57.424  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-03 11:54:57.424  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:54:57.424  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:54:57.425  4573  4573 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 11:54:57.425  4573  4573 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 11:54:57.426  4573  4573 D BluetoothMapService: MAP Service closeService in
,11-03 11:54:57.426  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-03 11:54:57.426  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-03 11:54:57.426  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:54:57.426  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:54:57.426  4573  4573 D BluetoothMapService: cleanup()
11-03 11:54:57.426  4573  4573 D BluetoothMapService: MAP Service closeService in
11-03 11:54:57.426  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-03 11:54:57.427  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-03 11:54:57.427  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:54:57.427  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:54:57.427  4573  4634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 11:54:57.427  4573  4634 D BluetoothAdapterProperties: Setting state to 15
11-03 11:54:57.427  4573  4634 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 11:54:57.427  4573  4634 I BluetoothAdapterState: Entering BleOnState
11-03 11:54:57.428  3067  3079 D BluetoothMap: onBluetoothStateChange: up=false
11-03 11:54:57.429   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 11:54:57.429   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 11:54:57.429  3067  3082 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 11:54:57.430  3067  3259 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 11:54:57.430   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-03 11:54:57.430  3067  5513 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 11:54:57.431  3685  3916 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 11:54:57.432  3067  3079 D BluetoothPan: onBluetoothStateChange on: false
11-03 11:54:57.433   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 11:54:57.434  3067  3259 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-03 11:54:57.438  4573  4634 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 11:54:57.438  4573  4634 D BluetoothAdapterProperties: Setting state to 16
11-03 11:54:57.438  4573  4634 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 11:54:57.438  4573  4634 D BluetoothAdapterProperties: onBleDisable
11-03 11:54:57.439  4573  4634 I BluetoothAdapterState: Entering PendingCommandState
11-03 11:54:57.439  4573  4635 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 11:54:57.440  4573  4777 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-03 11:54:57.440  4573  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 11:54:57.440  4573  4638 D BluetoothAdapterProperties: Scan Mode:20
11-03 11:54:57.440  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.440  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.440  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.440  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.440  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:57.440  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.440  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:54:57.440  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:54:57.440  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:54:57.441  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.441  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.441  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.441  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.441  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:57.441  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.441  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:54:57.441  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:54:57.441  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 11:54:57.443  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.443  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.443  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.443  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.443  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:54:57.443  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.443  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:54:57.443  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:54:57.443  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:54:57.444  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:57.445  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:57.445   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 11:54:57.446  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:57.459  5574  5574 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-03 11:54:57.472  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 11:54:57.473   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 11:54:57.473   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-03 11:54:57.474   507   920 D TetherController: Setting IP forward enable = 0
,11-03 11:54:57.476   927  2890 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-03 11:54:57.476   927  2888 D DhcpClient: doQuit
11-03 11:54:57.476   927  2888 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 11:54:57.476   927  2890 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 11:54:57.477  3386  3386 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-03 11:54:57.477   927  5270 D DhcpClient: onQuitting
,11-03 11:54:57.479  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 11:54:57.480   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5fde90d:true
11-03 11:54:57.482  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.482  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.482  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.482  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.482  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:54:57.482  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.482  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:54:57.482  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:54:57.482  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:54:57.482  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 11:54:57.482  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:54:57.485  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.485  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.485  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.485  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.485  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:54:57.485  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.485  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:54:57.485  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:54:57.485  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:54:57.486  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.486  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:54:57.487  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.487  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:54:57.487  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:54:57.487  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:54:57.487  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:54:57.487  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:54:57.487  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:54:57.487  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:54:57.487  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:54:57.488  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:54:57.488  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:54:57.495   927   937 I ActivityManager: Start proc 5596:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-03 11:54:57.497  3386  3386 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-03 11:54:57.499   927   944 D Tethering: MasterInitialState.processMessage what=3
11-03 11:54:57.499  5157  5157 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8edbc0b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-03 11:54:57.499  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:57.501  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:57.503  3386  3386 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-03 11:54:57.507  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:57.507  4933  4952 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-03 11:54:57.507  4933  4952 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-03 11:54:57.507  4933  4952 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-03 11:54:57.507  4933  4952 E SarControlService: no key has been found,reset the power
,11-03 11:54:57.507  4933  4984 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-03 11:54:57.507  4933  4984 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-03 11:54:57.508  4933  4984 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-03 11:54:57.508  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 11:54:57.508  4967  4967 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-03 11:54:57.509  4933  4984 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-03 11:54:57.509  4933  4984 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-03 11:54:57.502  3872  3872 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-03 11:54:57.512  4933  4984 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-03 11:54:57.513  4967  4987 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@43dd809 HexData = [00000000ea03000000000000ffffffff]
11-03 11:54:57.514  4967  4987 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-03 11:54:57.514  4967  4987 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-03 11:54:57.514  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 11:54:57.515  4967  4967 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-03 11:54:57.517  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-03 11:54:57.518  4933  4949 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-03 11:54:57.520  4967  4987 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@43dd809 HexData = [00000000eb03000000000000ffffffff]
11-03 11:54:57.520  4967  4987 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-03 11:54:57.520  4967  4987 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-03 11:54:57.522  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-03 11:54:57.523  4933  4947 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-03 11:54:57.538  5574  5574 D LocalBluetoothProfileManager: Adding local MAP profile
,11-03 11:54:57.538  3386  3386 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-03 11:54:57.540  5574  5574 D BluetoothMap: Create BluetoothMap proxy object
,11-03 11:54:57.545   507   920 E Netd    : netlink response contains error (No such file or directory)
,11-03 11:54:57.546   507   920 D TetherController: Setting IP forward enable = 0
,11-03 11:54:57.548  3386  3386 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 11:54:57.555  5574  5574 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-03 11:54:57.556  5596  5596 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-03 11:54:57.568  5574  5574 D DockEventReceiver: finishStartingService: stopping service
,11-03 11:54:57.578   927  3729 I ActivityManager: Killing 4352:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-03 11:54:57.601   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:54:57.644  4573  4638 I bt_hci  : shut_down
,11-03 11:54:57.649  4573  4642 D bt_hwcfg: hw_epilog_process
,11-03 11:54:57.649  4573  4642 I bt_vendor: low_power_mode_cb
,11-03 11:54:57.651   927  2888 D wifi    : In wifi stop Hal
11-03 11:54:57.652   927  2888 D wifi    : halHandle = 0x7f7fd9b400, mVM = 0x7f9c34d140, mCls = 0x100a02
11-03 11:54:57.652   927  3385 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 11:54:57.652   927  3385 D WifiHAL : Got a signal to exit!!!
11-03 11:54:57.652   927  3385 I WifiHAL : Exit wifi_event_loop
11-03 11:54:57.652  4418  4418 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 11:54:57.652  4573  4642 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-03 11:54:57.652   927  2888 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 11:54:57.653  4573  4642 I bt_vendor: epilog_cb
11-03 11:54:57.653   927  2888 E WifiHAL : Event processing terminated
11-03 11:54:57.653  4573  4642 I bt_hci  : epilog_finished_callback
11-03 11:54:57.653   927  2888 D wifi    : In wifi cleaned up handler
,11-03 11:54:57.653   927  2888 I WifiHAL : Internal cleanup completed
11-03 11:54:57.654  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:54:57.656  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:57.656  4573  4638 I bt_hci_h4: hal_close
11-03 11:54:57.656  4573  4638 I bt_userial_vendor: device fd = 54 close
,11-03 11:54:57.657  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:54:57.659  3888  4112 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 11:54:57.675   927  3385 D wifi    : set interface wlan0 flags (DOWN)
,11-03 11:54:57.676   927  2888 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 11:54:57.743  5596  5596 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at java.io.File.exists(File.java:361)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-03 11:54:57.743  5596  5596 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 11:54:57.743  5596  5596 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 11:54:57.743  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-03 11:54:57.744  5596  5596 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.e.b(PG:170)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-03 11:54:57.744  5596  5596 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.k.d(PG:583)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.e.b(PG:170)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-03 11:54:57.744  5596  5596 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.File.exists(File.java:361)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 11:54:57.744  5596  5596 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.File.exists(File.java:361)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 11:54:57.744,  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 11:54:57.744  5596  5596 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 11:54:57.744  5596  5596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-03 11:54:57.750  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 11:54:57.756  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 11:54:57.756  5574  5574 D DockEventReceiver: finishStartingService: stopping service
,11-03 11:54:57.758   927   937 I ActivityManager: Killing 5021:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-03 11:54:57.789  4573  4635 D bt_stack_manager: event_shut_down_stack finished.
,11-03 11:54:57.789  4573  4634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 11:54:57.791  4573  4634 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-03 11:54:57.791  4573  4573 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 11:54:57.792  4573  4573 D BtGatt.GattService: Received stop request...Stopping profile...
11-03 11:54:57.792  4573  4573 D BtGatt.GattService: stop()
,11-03 11:54:57.792  4573  4573 D BtGatt.AdvertiseManager: advertise clients cleared
,11-03 11:54:57.793  4573  4573 V BluetoothAdapterState: isTurningOff()=false
,11-03 11:54:57.793  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-03 11:54:57.794  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:54:57.794  4573  4573 V BluetoothAdapterState: isBleTurningOff()=true
11-03 11:54:57.794  4573  4634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-03 11:54:57.794  4573  4634 D BluetoothAdapterProperties: Setting state to 10
11-03 11:54:57.794  4573  4634 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 11:54:57.794  4573  4634 I BluetoothAdapterState: Entering OffState
,11-03 11:54:57.795   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-03 11:54:57.801  4573  4573 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 11:54:57.802  4573  4573 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 11:54:57.802  4573  4573 I BluetoothServiceJni: cleanupNative: return from cleanup
11-03 11:54:57.803  4573  4635 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 11:54:57.808  4573  4573 I art     : System.exit called, status: 0
,11-03 11:54:57.808  4573  4573 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 11:54:57.818   927  3729 I ActivityManager: Start proc 5637:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-03 11:54:57.851  5637  5637 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-03 11:54:57.854   927   938 I ActivityManager: Process com.android.bluetooth (pid 4573) has died
,11-03 11:54:57.859   927  3533 I ActivityManager: Killing 5341:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-03 11:54:57.878   927   944 D Tethering: InitialState.processMessage what=4
,11-03 11:54:57.886   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 11:54:57.895  3986  3986 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 11:54:57.898  3986  3986 D SystemUpdateService: onCreate
,11-03 11:54:57.901  3986  3986 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 11:54:57.908  3986  3986 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 11:54:57.917  3986  5293 I iu.UploadsManager: num queued entries: 0
,11-03 11:54:57.917  3986  5293 I iu.UploadsManager: num updated entries: 0
11-03 11:54:57.918  3986  5293 I iu.SyncManager: NEXT; no task
,11-03 11:54:57.921  3986  5650 I SystemUpdateService: active receiver: enabled
,11-03 11:54:57.924  3986  3986 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 11:54:57.925  3986  3986 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 11:54:57.933  3986  5650 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 11:54:57.935  3986  5650 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-03 11:54:57.936  3986  5650 I SystemUpdateService: now status is 0 (complete)
11-03 11:54:57.936  3986  5650 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-03 11:54:57.936  3986  5650 I SystemUpdateService: file has been verified
11-03 11:54:57.936  3986  5650 I SystemUpdateService: OTA package size = 21989297
11-03 11:54:57.937   927  3695 I ActivityManager: Start proc 5652:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-03 11:54:57.950  3986  5650 I SystemUpdateService: showing system update notification
,11-03 11:54:57.977  5652  5652 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-03 11:54:57.980  5652  5652 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 11:54:57.987  5652  5652 D SprintDMHelper: simOperator: 
,11-03 11:54:57.987  5652  5652 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 11:54:57.998   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 11:54:58.000   927  3093 I ActivityManager: Start proc 5664:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-03 11:54:58.011  3986  3986 D SystemUpdateService: onDestroy
,11-03 11:54:58.013   927  4880 I ActivityManager: Killing 5157:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-03 11:54:58.123  4418  5679 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-03 11:54:58.125   927  3533 I ActivityManager: Killing 3774:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-03 11:54:58.197  5596  5631 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-03 11:54:58.206   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af25896:true
,11-03 11:54:58.601   559   559 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 11:55:02.374   927  3674 D WifiService: setWifiEnabled: true pid=5514, uid=10077
11-03 11:55:02.374   927  3674 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 11:55:02.386   507   920 D SoftapController: Softap fwReload - Ok
,11-03 11:55:02.392   507   920 D CommandListener: Setting iface cfg
,11-03 11:55:02.392   507   920 D CommandListener: Trying to bring down wlan0
,11-03 11:55:02.394   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-03 11:55:02.401   927  2888 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 11:55:02.963   927  2888 D wifi    : set interface wlan0 flags (UP)
,11-03 11:55:02.968   927  2888 I WifiHAL : Initializing wifi
,11-03 11:55:02.968   927  2888 I WifiHAL : Creating socket
,11-03 11:55:02.972   927  2888 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-03 11:55:02.973   927  2888 D wifi    : Did set static halHandle = 0x7f7fd9b400
,11-03 11:55:02.973   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 11:55:02.973   927  2888 D wifi    : halHandle = 0x7f7fd9b400, mVM = 0x7f9c34d140, mCls = 0x20196a
,11-03 11:55:02.973   927  2888 D wifi    : array field set
11-03 11:55:02.973   927  2888 I WifiNative-HAL: interface[0] = wlan0
11-03 11:55:02.976   927  5684 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547605820416
11-03 11:55:02.976   927  5684 D wifi    : waitForHalEvents called, vm = 0x7f9c34d140, obj = 0x20196a, env = 0x7f7d9d6bc0
,11-03 11:55:03.053  5685  5685 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 11:55:03.082   927  2888 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 11:55:03.085  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:03.086  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:03.087  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:03.115  5685  5685 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 11:55:03.142  5685  5685 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 11:55:03.142  5685  5685 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 11:55:03.155   927  2888 D WifiConfigStore: Loading config and enabling all networks 
,11-03 11:55:03.162  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:03.162  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:03.162  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:03.162  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:03.162  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:03.162  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:03.162  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:03.162  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:03.162  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:03.163  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:03.163  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:03.164  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:03.164  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:03.164  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:03.164  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:03.164  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:03.164  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:03.164  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:03.164  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:03.164  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:03.164  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:03.164  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 11:55:03.165  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:03.165  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:03.165  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:03.165  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:03.165  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:03.165  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:03.165  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:03.165  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:03.165  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:03.165  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 11:55:03.165  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 11:55:03.179   927  2888 D WifiConfigStore: loaded 0 passpoint configs
,11-03 11:55:03.180   927  2888 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 11:55:03.180   927  2888 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-03 11:55:03.181   927  2888 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-03 11:55:03.181   927  2888 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-03 11:55:03.181   927  2888 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 11:55:03.182   927  2888 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-03 11:55:03.182   927  2888 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 11:55:03.182   927  2888 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 11:55:03.182   927  2888 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 11:55:03.182   927  2888 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 11:55:03.183   927  2888 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 11:55:03.183   927  2888 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 11:55:03.185   927  2888 D WifiNative-HAL: Setting external_sim to 1
,11-03 11:55:03.185   927  2888 D wifi    : setting dfs flag to true, 0x7f7daadb00
,11-03 11:55:03.185  4418  4418 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 11:55:03.185   927  2888 D WifiStateMachine: Setting OUI to DA-A1-19
,11-03 11:55:03.185   927  2888 D wifi    : setting scan oui 0x7f7daadb00
11-03 11:55:03.186   927  2888 D WifiHAL : Sending mac address OUI
,11-03 11:55:03.189   927  2888 E native  : do suspend false
,11-03 11:55:03.196   927  2888 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-03 11:55:03.197   927   927 D RttService: SCAN_AVAILABLE : 3
11-03 11:55:03.197   927  2995 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 11:55:03.202   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 11:55:03.204   507   920 D CommandListener: Setting iface cfg
,11-03 11:55:03.209   927  2887 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,11-03 11:55:03.209   927  2887 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 11:55:03.218   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129064 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-03 11:55:03.221   927  2887 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 11:55:03.222   927  2887 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 11:55:03.602   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:04.604   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:05.605   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:06.319  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 11:55:06.327  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 11:55:06.333  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 11:55:06.338  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 11:55:06.362   927  2888 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 11:55:06.364   927  2888 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-03 11:55:06.364   927  2888 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 11:55:06.374   927  2888 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 11:55:06.402   927  2888 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 11:55:06.408  5685  5685 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 11:55:06.606   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:06.830  5685  5685 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 11:55:06.862  5685  5685 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 11:55:06.863  5685  5685 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 11:55:06.870   927  2888 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-03 11:55:06.870   927  2888 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 11:55:06.871   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 11:55:06.892   927  2888 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 11:55:06.913   507   920 D CommandListener: Setting iface cfg
,11-03 11:55:06.920   927  2888 D WifiStateMachine: Start Dhcp Watchdog 2
,11-03 11:55:06.927   927  5691 D DhcpClient: Receive thread started
,11-03 11:55:06.933   927  2888 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 11:55:06.933   927  2890 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-03 11:55:06.934   927  2890 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-03 11:55:07.013   927  2888 E native  : do suspend false
,11-03 11:55:07.031   927  5690 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 11:55:07.046   927  5691 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-03 11:55:07.047   927  5690 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-03 11:55:07.051   927  5690 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 11:55:07.064   927  5691 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 11:55:07.064   927  5690 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-03 11:55:07.069   507   920 D CommandListener: Setting iface cfg
,11-03 11:55:07.074   927  2888 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 11:55:07.078   927  5690 D DhcpClient: Scheduling renewal in 86399s
,11-03 11:55:07.092   927  2888 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-03 11:55:07.093   927  2888 D WifiConfigStore: No blacklist allowed without epno enabled
11-03 11:55:07.095   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-03 11:55:07.097   927  2890 D ConnectivityService: Adding iface wlan0 to network 101
,11-03 11:55:07.115   927  2888 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-03 11:55:07.151   927  2890 E ConnectivityService: Unexpected mtu value: 0, wlan0,
11-03 11:55:07.151   927  2890 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-03 11:55:07.153   927  2890 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
11-03 11:55:07.155   927  2890 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-03 11:55:07.156   927  2890 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-03 11:55:07.164   927  2890 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 11:55:07.167   927  2890 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-03 11:55:07.168   927  2890 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-03 11:55:07.168   927  2890 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-03 11:55:07.168   927  2890 D ConnectivityService:    accepting network in place of null
11-03 11:55:07.168   927  2888 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 11:55:07.168   927  2888 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 11:55:07.168   927  2890 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 11:55:07.187   927  5689 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133033, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 11:55:07.189   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 11:55:07.214   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 11:55:07.220  3650  3772 W QCNEJ   : |CORE| network available: 101
,11-03 11:55:07.221   927  2890 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-03 11:55:07.221   927  2890 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 11:55:07.222  3650  3772 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-03 11:55:07.223   927  2890 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-03 11:55:07.223  3650  3772 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 11:55:07.223   927   944 D Tethering: MasterInitialState.processMessage what=3
11-03 11:55:07.228  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.228  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:07.228  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:07.228  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:07.228  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:07.228  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:07.228  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:07.228  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:07.228  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:55:07.228  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.228  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 11:55:07.227  3650  3772 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-03 11:55:07.231  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.232  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:07.232  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:07.232  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:07.232  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:07.232  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:07.232  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:07.232  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:07.232  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:55:07.232  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.232  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:07.235  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.235  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:07.235  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:07.235  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:07.235  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:07.235  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:07.235  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:07.235  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:07.235  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:55:07.235  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.235  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 11:55:07.239  4933  4952 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-03 11:55:07.239  4933  4952 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-03 11:55:07.239  4933  4952 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-03 11:55:07.240  4933  4952 E SarControlService: no key has been found,reset the power
11-03 11:55:07.240  4933  4984 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-03 11:55:07.240  4933  4984 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-03 11:55:07.240  4933  4984 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-03 11:55:07.241  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 11:55:07.241  4967  4967 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-03 11:55:07.245  4933  4984 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-03 11:55:07.245  4933  4984 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-03 11:55:07.245  4933  4984 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-03 11:55:07.246  3872  3872 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-03 11:55:07.247  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 11:55:07.247  4967  4967 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-03 11:55:07.249  3986  3986 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 11:55:07.252  4967  4987 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@43dd809 HexData = [00000000ec03000000000000ffffffff]
11-03 11:55:07.252  4967  4987 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-03 11:55:07.252  4967  4987 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-03 11:55:07.252  4967  4987 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@43dd809 HexData = [00000000ed03000000000000ffffffff]
11-03 11:55:07.252  4967  4987 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-03 11:55:07.252  4967  4987 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-03 11:55:07.253  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-03 11:55:07.253  4933  4949 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-03 11:55:07.254  3986  3986 D SystemUpdateService: onCreate
11-03 11:55:07.255  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-03 11:55:07.257   927  5688 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 11:55:07.258  4933  4947 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-03 11:55:07.260  3986  3986 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 11:55:07.271  3986  3986 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-03 11:55:07.281  3986  3986 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 11:55:07.282  3986  3986 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-03 11:55:07.284  5652  5652 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 11:55:07.288  5652  5652 D SprintDMHelper: simOperator: 
11-03 11:55:07.288  5652  5652 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 11:55:07.298  3986  5701 I SystemUpdateService: active receiver: enabled
,11-03 11:55:07.298  3986  5293 I iu.UploadsManager: num queued entries: 0
,11-03 11:55:07.301   927  5688 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 10:55:07 GMT], X-Android-Received-Millis=[1478170507300], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478170507280]}
11-03 11:55:07.301   927  2890 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 11:55:07.302   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-03 11:55:07.302   927  2890 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-03 11:55:07.303   927  2890 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-03 11:55:07.314  3986  5293 I iu.UploadsManager: num updated entries: 0
,11-03 11:55:07.315  3986  5293 I iu.SyncManager: NEXT; no task
,11-03 11:55:07.330  3986  5701 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 11:55:07.332  3986  5701 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-03 11:55:07.332  3986  5701 I SystemUpdateService: now status is 0 (complete)
11-03 11:55:07.333  3986  5701 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 11:55:07.333  3986  5701 I SystemUpdateService: file has been verified
,11-03 11:55:07.334  3986  5701 I SystemUpdateService: OTA package size = 21989297
,11-03 11:55:07.340  3986  5701 I SystemUpdateService: showing system update notification
,11-03 11:55:07.349   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 11:55:07.350  3986  3986 D SystemUpdateService: onDestroy
,11-03 11:55:07.385   927  3493 D WifiService: setWifiEnabled: false pid=5514, uid=10077
,11-03 11:55:07.385   927  3493 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 11:55:07.386   927  2888 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 11:55:07.386   927  2888 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 11:55:07.386   927  2888 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 11:55:07.387   927  2888 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 11:55:07.394  4418  5706 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-03 11:55:07.395   927  5690 D DhcpClient: Clearing IP address
11-03 11:55:07.395   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-03 11:55:07.397   507   920 D CommandListener: Setting iface cfg
,11-03 11:55:07.402  3517  5712 V NativeCrypto: Read error: ssl=0x7f819a9000: I/O error during system call, Connection timed out
,11-03 11:55:07.403  3517  5712 V NativeCrypto: SSL shutdown failed: ssl=0x7f819a9000: I/O error during system call, Broken pipe
,11-03 11:55:07.405   927  5691 D DhcpClient: Receive thread stopped
,11-03 11:55:07.406   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-03 11:55:07.406   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-03 11:55:07.411   555   555 E Parcel  : Reading a NULL string not supported here.
11-03 11:55:07.411   927  2890 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-03 11:55:07.416  3650  3772 W QCNEJ   : |CORE| network lost: 101
11-03 11:55:07.416   927   927 D RttService: SCAN_AVAILABLE : 1
11-03 11:55:07.417   927  2995 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 11:55:07.418  3650  3772 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-03 11:55:07.418   927  2888 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 11:55:07.421   927  2888 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 11:55:07.434   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 11:55:07.452   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 11:55:07.452   927  2890 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-03 11:55:07.452   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-03 11:55:07.452   927  2890 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 11:55:07.454   927  2888 D DhcpClient: doQuit
,11-03 11:55:07.454   927  2888 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 11:55:07.454   927   944 D Tethering: MasterInitialState.processMessage what=3
11-03 11:55:07.455   927  5690 D DhcpClient: onQuitting
11-03 11:55:07.455  5685  5685 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-03 11:55:07.457  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 11:55:07.457  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:07.457  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:07.457  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:07.457  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:07.457  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:07.457  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:07.457  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:07.457  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:07.457  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.457  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:07.458  3872  3872 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-03 11:55:07.458  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.459  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:07.459  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:07.459  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:07.459  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:07.459  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:07.459  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:07.459  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:07.459  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:07.459  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.459  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:07.459  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.460  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:07.460  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:07.460  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:07.460  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:07.460  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:07.460  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:07.460  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:07.460  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 11:55:07.460  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:07.460  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 11:55:07.464  4933  4952 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-03 11:55:07.464  4933  4952 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-03 11:55:07.464  4933  4952 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-03 11:55:07.464  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:07.464  4933  4952 E SarControlService: no key has been found,reset the power
11-03 11:55:07.465  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:07.465  4933  4984 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-03 11:55:07.465  4933  4984 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-03 11:55:07.466  4933  4984 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-03 11:55:07.466  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:07.467  3986  3986 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 11:55:07.468  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-03 11:55:07.468  4967  4967 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-03 11:55:07.469  4933  4984 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-03 11:55:07.469  4933  4984 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-03 11:55:07.469  4933  4984 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-03 11:55:07.470  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 11:55:07.470  4967  4967 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-03 11:55:07.473  3986  3986 D SystemUpdateService: onCreate
11-03 11:55:07.474  4967  4987 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@43dd809 HexData = [00000000ee03000000000000ffffffff]
11-03 11:55:07.474  4967  4987 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-03 11:55:07.474  4967  4987 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-03 11:55:07.474  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-03 11:55:07.474  4933  4947 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-03 11:55:07.477  4967  4987 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@43dd809 HexData = [00000000ef03000000000000ffffffff]
,11-03 11:55:07.477  4967  4987 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-03 11:55:07.477  4967  4987 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-03 11:55:07.477  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-03 11:55:07.478  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-03 11:55:07.478  4933  4949 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-03 11:55:07.479  3986  3986 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 11:55:07.483  3986  5721 I SystemUpdateService: active receiver: enabled
,11-03 11:55:07.484  5685  5685 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 11:55:07.489  3986  3986 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 11:55:07.493  3986  5293 I iu.UploadsManager: num queued entries: 0
,11-03 11:55:07.494  3986  5293 I iu.UploadsManager: num updated entries: 0
11-03 11:55:07.495  3986  5293 I iu.SyncManager: NEXT; no task
,11-03 11:55:07.497  3986  3986 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 11:55:07.499  3986  3986 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 11:55:07.501  5652  5652 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 11:55:07.505  5652  5652 D SprintDMHelper: simOperator: 
11-03 11:55:07.505  5652  5652 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 11:55:07.510   507   920 E Netd    : netlink response contains error (No such file or directory)
,11-03 11:55:07.511   927  2890 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-03 11:55:07.511  3986  5721 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 11:55:07.516  4418  5725 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-03 11:55:07.521  3986  5721 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-03 11:55:07.521  3986  5721 I SystemUpdateService: now status is 0 (complete)
11-03 11:55:07.521  3986  5721 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 11:55:07.521  3986  5721 I SystemUpdateService: file has been verified
11-03 11:55:07.521  3986  5721 I SystemUpdateService: OTA package size = 21989297
11-03 11:55:07.524  5685  5685 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 11:55:07.530  5685  5685 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 11:55:07.536  3986  5721 I SystemUpdateService: showing system update notification
,11-03 11:55:07.542   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 11:55:07.544  3986  3986 D SystemUpdateService: onDestroy
,11-03 11:55:07.606   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:07.635   927  2888 D wifi    : In wifi stop Hal
,11-03 11:55:07.636   927  2888 D wifi    : halHandle = 0x7f7fd9b400, mVM = 0x7f9c34d140, mCls = 0x20196a
11-03 11:55:07.636   927  5684 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 11:55:07.636   927  5684 D WifiHAL : Got a signal to exit!!!
11-03 11:55:07.636   927  5684 I WifiHAL : Exit wifi_event_loop
11-03 11:55:07.636   927  2888 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-03 11:55:07.636   927  2888 E WifiHAL : Event processing terminated
11-03 11:55:07.636   927  2888 D wifi    : In wifi cleaned up handler
11-03 11:55:07.637   927  2888 I WifiHAL : Internal cleanup completed
11-03 11:55:07.639  3888  4112 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 11:55:07.640  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:07.641  4418  4418 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 11:55:07.641  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:07.642  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:07.661   927  5684 D wifi    : set interface wlan0 flags (DOWN)
,11-03 11:55:07.662   927  2888 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 11:55:07.869   927   944 D Tethering: InitialState.processMessage what=4
,11-03 11:55:07.875   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 11:55:08.220   927  2890 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-03 11:55:08.607   559   559 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 11:55:12.421   927   944 I ActivityManager: Start proc 5727:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 11:55:12.515  5727  5727 D AdapterServiceConfig: Adding HeadsetService
,11-03 11:55:12.516  5727  5727 D AdapterServiceConfig: Adding A2dpService
11-03 11:55:12.516  5727  5727 D AdapterServiceConfig: Adding HidService
11-03 11:55:12.516  5727  5727 D AdapterServiceConfig: Adding HealthService
11-03 11:55:12.516  5727  5727 D AdapterServiceConfig: Adding PanService
11-03 11:55:12.516  5727  5727 D AdapterServiceConfig: Adding GattService
11-03 11:55:12.517  5727  5727 D AdapterServiceConfig: Adding BluetoothMapService
,11-03 11:55:12.517  5727  5727 D AdapterServiceConfig: Adding SapService
,11-03 11:55:12.527   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10dcb65:true
,11-03 11:55:12.527  5727  5727 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 11:55:12.530  5727  5727 I bt_bluedroid: init
,11-03 11:55:12.530  5727  5739 I BluetoothAdapterState: Entering OffState
,11-03 11:55:12.532  5727  5740 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 11:55:12.532  5727  5740 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 11:55:12.532  5727  5740 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 11:55:12.533  5727  5740 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-03 11:55:12.533  5727  5727 I bt_bluedroid: get_profile_interface socket
,11-03 11:55:12.535  5727  5727 I bt_bluedroid: get_profile_interface sdp
11-03 11:55:12.535  5727  5743 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 11:55:12.539  5727  5743 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 11:55:12.540  5727  5738 I bt_bluedroid: config_hci_snoop_log
,11-03 11:55:12.541   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 11:55:12.545  5727  5739 D BluetoothAdapterState: Current state: OFF, message: 0
11-03 11:55:12.545  5727  5739 D BluetoothAdapterProperties: Setting state to 14
11-03 11:55:12.545  5727  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 11:55:12.547  5727  5739 D BluetoothBondStateMachine: make
,11-03 11:55:12.549  5727  5744 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 11:55:12.551  5727  5739 I BluetoothAdapterState: Entering PendingCommandState
,11-03 11:55:12.552  5727  5727 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 11:55:12.555  5727  5727 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:12.555  5727  5727 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 11:55:12.556  5727  5727 D BtGatt.GattService: Received start request. Starting profile...
11-03 11:55:12.556  5727  5727 D BtGatt.GattService: start()
11-03 11:55:12.556  5727  5727 I bt_bluedroid: get_profile_interface gatt
,11-03 11:55:12.558  5727  5727 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:12.558  5727  5727 D BtGatt.AdvertiseManager: advertise manager created
,11-03 11:55:12.563  5727  5727 V BluetoothAdapterState: isTurningOff()=false
,11-03 11:55:12.563  5727  5727 V BluetoothAdapterState: isTurningOn()=false
11-03 11:55:12.563  5727  5727 V BluetoothAdapterState: isBleTurningOn()=true
11-03 11:55:12.563  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 11:55:12.564  5727  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-03 11:55:12.566  5727  5739 I bt_bluedroid: bt_bluedroid
11-03 11:55:12.566  5727  5740 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-03 11:55:12.566  5727  5740 I bt_hci  : start_up
,11-03 11:55:12.571  5727  5740 I bt_vendor: alloc value 0xf3cc9871
11-03 11:55:12.571  5727  5740 I bt_vendor: init
11-03 11:55:12.571  5727  5740 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 11:55:12.571  5727  5740 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 11:55:12.681  5727  5740 D bt_hci  : start_up starting async portion
,11-03 11:55:12.681  5727  5747 I bt_hci  : event_finish_startup
11-03 11:55:12.682  5727  5747 I bt_hci_h4: hal_open
,11-03 11:55:12.682  5727  5747 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 11:55:12.686  5727  5747 I bt_userial_vendor: device fd = 54 open
,11-03 11:55:12.680  5748  5748 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 11:55:12.700  5727  5747 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 11:55:12.702  5727  5747 D bt_hwcfg: Chipset BCM4358A3
,11-03 11:55:12.703  5727  5747 D bt_hwcfg: Target name = [BCM4358A3]
11-03 11:55:12.703  5727  5747 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 11:55:13.099  5727  5747 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 11:55:13.099  5727  5747 D bt_hwcfg: Settlement delay -- 100 ms
11-03 11:55:13.100  5727  5747 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 11:55:13.233  5727  5747 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 11:55:13.233  5727  5747 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 11:55:13.235  5727  5747 I bt_hwcfg: vendor lib fwcfg completed
11-03 11:55:13.235  5727  5747 I bt_vendor: firmware callback
,11-03 11:55:13.235  5727  5747 I bt_hci  : firmware_config_callback
,11-03 11:55:13.244  5727  5750 I bt_btu  : btu_task pending for preload complete event
,11-03 11:55:13.244  5727  5750 I bt_btu_task: Bluetooth chip preload is complete
11-03 11:55:13.244  5727  5750 I bt_btu  : btu_task received preload complete event
,11-03 11:55:13.252  5727  5750 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 11:55:13.252  5727  5750 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 11:55:13.252  5727  5750 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 11:55:13.252  5727  5750 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 11:55:13.252  5727  5750 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-03 11:55:13.252  5727  5750 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 11:55:13.252  5727  5750 I         : BTE_InitTraceLevels -- TRC_BNEP
11-03 11:55:13.253  5727  5750 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 11:55:13.253  5727  5750 I         : BTE_InitTraceLevels -- TRC_GAP
,11-03 11:55:13.253  5727  5750 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 11:55:13.253  5727  5750 I         : BTE_InitTraceLevels -- TRC_SDP
11-03 11:55:13.253  5727  5750 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 11:55:13.253  5727  5750 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 11:55:13.253  5727  5750 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-03 11:55:13.254  5727  5750 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 11:55:13.334  5727  5750 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c47549
,11-03 11:55:13.335  5727  5750 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c47549 
,11-03 11:55:13.348  5727  5743 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 11:55:13.350  5727  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 11:55:13.351  5727  5743 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 11:55:13.352  5727  5743 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 11:55:13.355  5727  5743 D BluetoothAdapterProperties: Scan Mode:20
,11-03 11:55:13.355  5727  5743 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-03 11:55:13.356  5727  5743 D bt_hci  : do_postload posting postload work item
,11-03 11:55:13.356  5727  5747 I bt_hci  : event_postload
11-03 11:55:13.356  5727  5747 I bt_vendor: sco_config_cb
11-03 11:55:13.356  5727  5747 I bt_hci  : sco_config_callback postload finished.
,11-03 11:55:13.359  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:13.362  5727  5747 I bt_vendor: low_power_mode_cb
,11-03 11:55:13.364  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:13.366  5727  5743 D bt_bte_conf: Device ID record 1 : primary
11-03 11:55:13.366  5727  5743 D bt_bte_conf:   vendorId            = 000f
,11-03 11:55:13.366  5727  5743 D bt_bte_conf:   vendorIdSource      = 0001
11-03 11:55:13.366  5727  5743 D bt_bte_conf:   product             = 1200
11-03 11:55:13.367  5727  5743 D bt_bte_conf:   version             = 1436
,11-03 11:55:13.367  5727  5743 D bt_bte_conf:   clientExecutableURL = 
11-03 11:55:13.367  5727  5743 D bt_bte_conf:   serviceDescription  = 
11-03 11:55:13.367  5727  5743 D bt_bte_conf:   documentationURL    = 
11-03 11:55:13.367  5727  5743 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-03 11:55:13.367  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:13.367  5727  5740 D bt_stack_manager: event_start_up_stack finished
,11-03 11:55:13.368  5727  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 11:55:13.368  5727  5739 D BluetoothAdapterProperties: Setting state to 15
11-03 11:55:13.369  5727  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 11:55:13.370  5727  5739 I BluetoothAdapterState: Entering BleOnState
,11-03 11:55:13.375  5727  5739 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 11:55:13.375  5727  5739 D BluetoothAdapterProperties: Setting state to 11
,11-03 11:55:13.376  5727  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 11:55:13.387  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:13.387  5727  5727 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:13.390  5727  5727 D HeadsetService: Received start request. Starting profile...
,11-03 11:55:13.390  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:13.393  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:13.395  5727  5727 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 11:55:13.395  5727  5727 D HeadsetStateMachine: make
,11-03 11:55:13.400  5727  5739 I BluetoothAdapterState: Entering PendingCommandState
,11-03 11:55:13.405  5727  5727 D HeadsetStateMachine: max_hf_connections = 1
,11-03 11:55:13.405  5727  5727 I bt_bluedroid: get_profile_interface handsfree
11-03 11:55:13.405  5727  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 11:55:13.406  5727  5743 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-03 11:55:13.409  5727  5727 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:13.410  5727  5727 D A2dpService: Received start request. Starting profile...
,11-03 11:55:13.411  5727  5727 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 11:55:13.411  5727  5727 I bt_bluedroid: get_profile_interface avrcp
,11-03 11:55:13.419  5727  5727 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 11:55:13.420  5727  5727 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-03 11:55:13.420  5727  5727 D A2dpStateMachine: make
,11-03 11:55:13.422  5727  5727 I bt_bluedroid: get_profile_interface a2dp
,11-03 11:55:13.424  5727  5760 D A2dpStateMachine: Enter Disconnected: -2
,11-03 11:55:13.422  5727  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 11:55:13.427  5727  5727 I BluetoothHidServiceJni: classInitNative: succeeds
,11-03 11:55:13.428  5727  5727 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
11-03 11:55:13.429  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 11:55:13.431  5727  5727 D HidService: Received start request. Starting profile...
11-03 11:55:13.431  5727  5727 I bt_bluedroid: get_profile_interface hidhost
11-03 11:55:13.431  5727  5727 D HidService: setHidService(): set to: null
11-03 11:55:13.431  5727  5743 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c2856d
11-03 11:55:13.431  5727  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 11:55:13.432  5727  5727 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-03 11:55:13.432  5727  5727 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:13.434  5727  5727 D HealthService: Received start request. Starting profile...
11-03 11:55:13.434  5574  5574 D BluetoothInputDevice: Proxy object connected
11-03 11:55:13.434  5574  5574 D HidProfile: Bluetooth service connected
11-03 11:55:13.435  5727  5727 I bt_bluedroid: get_profile_interface health
11-03 11:55:13.436  5727  5727 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-03 11:55:13.437  5727  5727 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:13.438  5727  5727 D PanService: Received start request. Starting profile...
,11-03 11:55:13.438  5727  5727 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 11:55:13.438  5727  5727 I bt_bluedroid: get_profile_interface pan
11-03 11:55:13.439  5727  5743 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 11:55:13.440  5727  5727 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:13.441  5574  5574 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 11:55:13.442  5727  5727 D BluetoothMapService: Received start request. Starting profile...
11-03 11:55:13.442  5727  5727 D BluetoothMapService: start()
11-03 11:55:13.442  5574  5574 D PanProfile: Bluetooth service connected
11-03 11:55:13.442  5574  5574 D BluetoothMap: Proxy object connected
,11-03 11:55:13.442  5574  5574 D MapProfile: Bluetooth service connected
11-03 11:55:13.442  5574  5574 D BluetoothMap: getConnectedDevices()
11-03 11:55:13.443  5574  5574 D BluetoothMap: Bluetooth is Not enabled
,11-03 11:55:13.444  5727  5727 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-03 11:55:13.445  5727  5727 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 11:55:13.445  5727  5727 D BluetoothMapAppObserver: createReceiver()
11-03 11:55:13.446  5727  5727 D BluetoothMapAppObserver: initObservers()
11-03 11:55:13.447  5727  5727 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 11:55:13.452  5727  5727 V SapService: SapBinder()
,11-03 11:55:13.452  5727  5727 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:13.453  5727  5727 D SapService: Received start request. Starting profile...
,11-03 11:55:13.453  5727  5727 V SapService: start()
,11-03 11:55:13.456  5727  5727 V BluetoothAdapterState: isTurningOff()=false
,11-03 11:55:13.456  5727  5727 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:13.456  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:13.456  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:13.457  5727  5727 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:13.457  5727  5727 V BluetoothAdapterState: isTurningOn()=true
,11-03 11:55:13.457  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:13.457  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:13.457  5727  5758 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,11-03 11:55:13.457  5727  5727 V BluetoothAdapterState: isTurningOff()=false
,11-03 11:55:13.457  5727  5727 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:13.457  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:13.457  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isTurningOff()=false
,11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:13.458  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:13.459  5727  5727 V BluetoothAdapterState: isTurningOff()=false
,11-03 11:55:13.459  5727  5727 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:13.459  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:13.459  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:13.459  5727  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 11:55:13.459  5727  5739 D BluetoothAdapterProperties: ScanMode =  20
11-03 11:55:13.459  5727  5739 D BluetoothAdapterProperties: State =  11
11-03 11:55:13.462  5727  5743 D BluetoothAdapterProperties: Scan Mode:21
11-03 11:55:13.462  5727  5739 D BluetoothAdapterProperties: Setting state to 12
11-03 11:55:13.463  5727  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 11:55:13.463  5727  5743 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 11:55:13.463  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 11:55:13.463  5727  5739 I BluetoothAdapterState: Entering OnState
11-03 11:55:13.463  3067  3259 D BluetoothMap: onBluetoothStateChange: up=true
11-03 11:55:13.465  3067  3067 D BluetoothMap: Proxy object connected
11-03 11:55:13.465   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:13.465  3067  3067 D MapProfile: Bluetooth service connected
11-03 11:55:13.465   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:13.465  3067  3067 D BluetoothMap: getConnectedDevices()
11-03 11:55:13.466  3067  5513 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 11:55:13.467  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:13.467  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:13.467  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:13.467  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:13.467  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:13.467  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:13.467  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:13.467  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:13.467  3067  3259 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:13.468  5574  5586 D BluetoothPan: onBluetoothStateChange on: true
11-03 11:55:13.469  3067  3067 D BluetoothA2dp: Proxy object connected
11-03 11:55:13.469   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 11:55:13.469   927   927 D BluetoothA2dp: Proxy object connected
11-03 11:55:13.469  3067  3079 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 11:55:13.471  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:13.471  3685  3715 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:13.472  5574  5584 D BluetoothMap: onBluetoothStateChange: up=true
11-03 11:55:13.472  5727  5727 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 11:55:13.472  3067  3259 D BluetoothPan: onBluetoothStateChange on: true
11-03 11:55:13.473  5727  5727 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 11:55:13.474   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:13.474  5727  5727 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 11:55:13.475  3067  3067 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 11:55:13.475  3067  3067 D PanProfile: Bluetooth service connected
11-03 11:55:13.475  5574  5586 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 11:55:13.475  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:13.475  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:13.475  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:13.475  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:13.475  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:13.475  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:13.475  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:13.475  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:13.476  5574  5584 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 11:55:13.476  5727  5727 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 11:55:13.476  3067  5513 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 11:55:13.477  5727  5727 D ObexServerSockets: Succeed to create listening sockets 
11-03 11:55:13.478  5727  5727 D ObexServerSockets0: startAccept()
11-03 11:55:13.478  5727  5727 D ObexServerSockets0: prepareForNewConnect()
11-03 11:55:13.478  3067  3067 D BluetoothInputDevice: Proxy object connected
11-03 11:55:13.478  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:13.478  3067  3067 D HidProfile: Bluetooth service connected
11-03 11:55:13.480  5727  5727 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 11:55:13.480  5727  5727 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 11:55:13.481   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 11:55:13.481  5574  5574 D LocalBluetoothProfileManager: Adding local A2DP profile
11-03 11:55:13.483  5727  5727 D BluetoothMapService: onReceive
11-03 11:55:13.483  5727  5727 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 11:55:13.483  5727  5765 D ObexServerSockets0: Accepting socket connection...
11-03 11:55:13.483  5727  5727 D BluetoothMapService: STATE_ON
11-03 11:55:13.483  5727  5766 D ObexServerSockets0: Accepting socket connection...
11-03 11:55:13.483  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:13.483  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:13.483  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:13.483  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:13.483  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:13.483  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:13.483  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:13.483  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:13.486  5727  5768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 11:55:13.486  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:13.486  5574  5574 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-03 11:55:13.486  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 11:55:13.488  5727  5768 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 11:55:13.488  5727  5768 D BluetoothSdpJni: SDP Create record success - handle: 1
11-03 11:55:13.488  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:13.491  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:13.493  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:13.493  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 11:55:13.495  5574  5574 D BluetoothA2dp: Proxy object connected
11-03 11:55:13.500  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 11:55:13.511  3067  3067 D BluetoothPbap: Proxy object connected
11-03 11:55:13.511  3067  3067 D PbapServerProfile: Bluetooth service connected
11-03 11:55:13.511  5727  5727 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 11:55:13.511  5727  5727 D ObexServerSockets0: prepareForNewConnect()
11-03 11:55:13.514  5574  5574 D DockEventReceiver: finishStartingService: stopping service
11-03 11:55:13.514  5574  5574 D BluetoothPbap: Proxy object connected
11-03 11:55:13.515  5574  5574 D PbapServerProfile: Bluetooth service connected
11-03 11:55:13.520  5727  5772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 11:55:13.534  5727  5776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 11:55:13.536  5727  5776 I BtOppRfcommListener: Accept thread started.
,11-03 11:55:13.567  3685  3722 D BluetoothHeadset: Proxy object connected
,11-03 11:55:13.568   927   927 D BluetoothHeadset: Proxy object connected
11-03 11:55:13.568  3067  3259 D BluetoothHeadset: Proxy object connected
,11-03 11:55:13.568   927   927 D BluetoothHeadset: Proxy object connected
11-03 11:55:13.568   927   927 D BluetoothHeadset: Proxy object connected
11-03 11:55:13.568  3067  3067 D HeadsetProfile: Bluetooth service connected
11-03 11:55:13.568  3067  3082 D BluetoothHeadset: Proxy object connected
,11-03 11:55:13.571  3067  3067 D HeadsetProfile: Bluetooth service connected
,11-03 11:55:13.572  3685  3916 D BluetoothHeadset: Proxy object connected
,11-03 11:55:13.575   927   944 D BluetoothHeadset: Proxy object connected
,11-03 11:55:13.588  5574  5584 D BluetoothHeadset: Proxy object connected
,11-03 11:55:13.589  5574  5574 D HeadsetProfile: Bluetooth service connected
,11-03 11:55:14.097  3579  3754 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-03 11:55:14.098  3579  3754 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-03 11:55:14.127  3517  3517 I ConfigService: onCreate
,11-03 11:55:15.175   927  2890 D ConnectivityService: handlePromptUnvalidated 101
,11-03 11:55:17.402  5727  5739 D BluetoothAdapterState: Current state: ON, message: 23
,11-03 11:55:17.402  5727  5739 D BluetoothAdapterProperties: Setting state to 13
,11-03 11:55:17.402  5727  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-03 11:55:17.404  5727  5739 D BluetoothAdapterProperties: onBluetoothDisable()
11-03 11:55:17.406  5727  5739 I BluetoothAdapterState: Entering PendingCommandState
11-03 11:55:17.408  5727  5727 D BluetoothMapService: onReceive
11-03 11:55:17.408  5727  5727 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-03 11:55:17.408  5727  5727 D BluetoothMapService: STATE_TURNING_OFF
11-03 11:55:17.409  5727  5727 D BluetoothMapService: MAP Service closeService in
11-03 11:55:17.409  5727  5727 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 11:55:17.409  5727  5727 D ObexServerSockets0: shutdown(block = true)
,11-03 11:55:17.411  5727  5727 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-03 11:55:17.411  5727  5752 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 11:55:17.411  5727  5727 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 11:55:17.412  5727  5766 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 11:55:17.415  5727  5743 D BluetoothAdapterProperties: Scan Mode:20
11-03 11:55:17.415  5727  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-03 11:55:17.416  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:17.416  5727  5765 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-03 11:55:17.416  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:17.416  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:17.416  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:17.416  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:17.416  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:17.416  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:17.416  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:17.416  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:17.419  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 11:55:17.419  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 11:55:17.419  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:17.426  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:17.426  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:17.426  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:17.426  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:17.426  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:17.426  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:17.426  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:17.426  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:17.426  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:17.428  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:17.428  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:17.425  5727  5727 I BtOppRfcommListener: stopping Accept Thread
,11-03 11:55:17.430  5727  5776 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 11:55:17.431  5727  5776 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-03 11:55:17.431  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:17.431  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:17.431  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:17.431  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:17.431  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:17.431  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 11:55:17.431  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:17.431  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:17.431  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:17.432  5514  5514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 11:55:17.433  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:17.435  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:17.436  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:17.438  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:17.438  5727  5727 D HeadsetService: Received stop request...Stopping profile...
11-03 11:55:17.440  5574  5574 D DockEventReceiver: finishStartingService: stopping service
,11-03 11:55:17.441  3685  3927 D BluetoothHeadset: Proxy object disconnected
11-03 11:55:17.441   927   927 D BluetoothHeadset: Proxy object disconnected
11-03 11:55:17.441   927   927 D BluetoothHeadset: Proxy object disconnected
11-03 11:55:17.441   927   927 D BluetoothHeadset: Proxy object disconnected
11-03 11:55:17.442  3067  3082 D BluetoothHeadset: Proxy object disconnected
11-03 11:55:17.442  5574  5586 D BluetoothHeadset: Proxy object disconnected
11-03 11:55:17.442  5727  5727 D A2dpService: Received stop request...Stopping profile...
11-03 11:55:17.443  5727  5760 D A2dpStateMachine: Exit Disconnected: -1
11-03 11:55:17.443  5574  5574 D HeadsetProfile: Bluetooth service disconnected
,11-03 11:55:17.444   927   927 D BluetoothA2dp: Proxy object disconnected
11-03 11:55:17.445  3067  3067 D HeadsetProfile: Bluetooth service disconnected
11-03 11:55:17.445  3067  3067 D BluetoothA2dp: Proxy object disconnected
,11-03 11:55:17.446  5727  5727 D HidService: Received stop request...Stopping profile...
11-03 11:55:17.446  5727  5727 D HidService: Stopping Bluetooth HidService
11-03 11:55:17.447  3067  3067 D BluetoothInputDevice: Proxy object disconnected
11-03 11:55:17.447  3067  3067 D HidProfile: Bluetooth service disconnected
11-03 11:55:17.449  5727  5727 D HealthService: Received stop request...Stopping profile...
,11-03 11:55:17.450  5574  5574 D BluetoothA2dp: Proxy object disconnected
11-03 11:55:17.451  5574  5574 D BluetoothInputDevice: Proxy object disconnected
11-03 11:55:17.451  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 11:55:17.451  5574  5574 D HidProfile: Bluetooth service disconnected
11-03 11:55:17.451  5727  5727 D PanService: Received stop request...Stopping profile...
11-03 11:55:17.453  3067  3067 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 11:55:17.454  3067  3067 D PanProfile: Bluetooth service disconnected
11-03 11:55:17.454  5574  5574 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 11:55:17.454  5574  5574 D PanProfile: Bluetooth service disconnected
11-03 11:55:17.454  5727  5727 D BluetoothMapService: Received stop request...Stopping profile...
11-03 11:55:17.455  5727  5727 D BluetoothMapService: stop()
,11-03 11:55:17.455  5727  5727 D BluetoothMapAppObserver: deinitObservers()
11-03 11:55:17.455  5727  5727 D BluetoothMapAppObserver: removeReceiver()
11-03 11:55:17.456  5574  5574 D BluetoothMap: Proxy object disconnected
11-03 11:55:17.456  5574  5574 D MapProfile: Bluetooth service disconnected
11-03 11:55:17.457  3067  3067 D BluetoothMap: Proxy object disconnected
11-03 11:55:17.457  3067  3067 D MapProfile: Bluetooth service disconnected
,11-03 11:55:17.457  5727  5727 D SapService: Received stop request...Stopping profile...
,11-03 11:55:17.457  5727  5727 V SapService: stop()
,11-03 11:55:17.460  5727  5727 V BluetoothAdapterState: isTurningOff()=true
11-03 11:55:17.460  5727  5727 V BluetoothAdapterState: isTurningOn()=false
11-03 11:55:17.460  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 11:55:17.460  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:17.461  5727  5727 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 11:55:17.461  5727  5727 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 11:55:17.461  5727  5750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 11:55:17.461  5727  5727 V BluetoothAdapterState: isTurningOff()=true
11-03 11:55:17.461  5727  5750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 11:55:17.461  5727  5727 V BluetoothAdapterState: isTurningOn()=false
,11-03 11:55:17.461  5727  5750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 11:55:17.461  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:17.462  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:17.462  5727  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 11:55:17.462  5727  5743 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 11:55:17.462  5727  5750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 11:55:17.463  5727  5727 V BluetoothAdapterState: isTurningOff()=true
11-03 11:55:17.463  5727  5750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 11:55:17.463  5727  5727 V BluetoothAdapterState: isTurningOn()=false
11-03 11:55:17.463  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 11:55:17.463  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:17.463  5727  5750 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 11:55:17.463  5727  5750 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 11:55:17.463  5727  5727 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 11:55:17.463  5727  5750 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 11:55:17.463  5727  5750 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 11:55:17.463  5727  5727 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 11:55:17.463  5727  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 11:55:17.464  5727  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 11:55:17.465  5574  5574 D BluetoothPbap: Proxy object disconnected
11-03 11:55:17.465  5727  5727 V BluetoothAdapterState: isTurningOff()=true
11-03 11:55:17.465  5727  5727 V BluetoothAdapterState: isTurningOn()=false
11-03 11:55:17.465  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:17.465  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 11:55:17.465  5727  5727 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-03 11:55:17.465  3067  3067 D BluetoothPbap: Proxy object disconnected
11-03 11:55:17.465  3067  3067 D PbapServerProfile: Bluetooth service disconnected
11-03 11:55:17.466  5727  5743 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 11:55:17.466  5727  5727 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-03 11:55:17.466  5727  5727 V BluetoothAdapterState: isTurningOff()=true
11-03 11:55:17.466  5727  5727 V BluetoothAdapterState: isTurningOn()=false
11-03 11:55:17.466  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:17.466  5574  5574 D PbapServerProfile: Bluetooth service disconnected
11-03 11:55:17.466  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:17.467  5727  5727 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-03 11:55:17.467  5727  5727 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 11:55:17.467  5727  5727 D BluetoothMapService: MAP Service closeService in
11-03 11:55:17.468  5727  5727 V BluetoothAdapterState: isTurningOff()=true
11-03 11:55:17.468  5727  5727 V BluetoothAdapterState: isTurningOn()=false
11-03 11:55:17.468  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:17.468  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:17.468  5727  5727 D BluetoothMapService: cleanup()
11-03 11:55:17.468  5727  5727 D BluetoothMapService: MAP Service closeService in
11-03 11:55:17.468  5727  5727 V BluetoothAdapterState: isTurningOff()=true
11-03 11:55:17.468  5727  5727 V BluetoothAdapterState: isTurningOn()=false
11-03 11:55:17.468  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:17.468  5727  5727 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:17.468  5727  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 11:55:17.468  5727  5739 D BluetoothAdapterProperties: Setting state to 15
11-03 11:55:17.468  5727  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 11:55:17.469  5727  5739 I BluetoothAdapterState: Entering BleOnState
,11-03 11:55:17.470  3067  3082 D BluetoothMap: onBluetoothStateChange: up=false
11-03 11:55:17.472   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 11:55:17.472   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 11:55:17.472  3067  3079 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 11:55:17.473  3067  3259 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 11:55:17.473  5574  5584 D BluetoothPan: onBluetoothStateChange on: false
11-03 11:55:17.474   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 11:55:17.475  3067  5513 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 11:55:17.477  3685  3715 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-03 11:55:17.477  5574  5586 D BluetoothMap: onBluetoothStateChange: up=false
11-03 11:55:17.478  3067  3082 D BluetoothPan: onBluetoothStateChange on: false
11-03 11:55:17.478  5574  5584 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 11:55:17.479   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 11:55:17.479  5574  5586 D BluetoothPbap: onBluetoothStateChange: up=false
,11-03 11:55:17.479  5574  5584 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 11:55:17.480  5574  5586 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 11:55:17.480  3067  3079 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 11:55:17.481  5727  5739 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 11:55:17.481  5727  5739 D BluetoothAdapterProperties: Setting state to 16
11-03 11:55:17.481  5727  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 11:55:17.482  5727  5739 D BluetoothAdapterProperties: onBleDisable
11-03 11:55:17.482  5727  5739 I BluetoothAdapterState: Entering PendingCommandState
11-03 11:55:17.482  5727  5740 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 11:55:17.484  5727  5750 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 11:55:17.484  5727  5750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 11:55:17.484  5727  5743 D BluetoothAdapterProperties: Scan Mode:20
,11-03 11:55:17.485  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 11:55:17.486  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:17.487  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:17.489  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:17.490  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 11:55:17.491  5574  5574 D DockEventReceiver: finishStartingService: stopping service
11-03 11:55:17.493  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:17.494  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:17.495  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:17.696  5727  5743 I bt_hci  : shut_down
,11-03 11:55:17.702  5727  5747 D bt_hwcfg: hw_epilog_process
,11-03 11:55:17.703  5727  5747 I bt_vendor: low_power_mode_cb
,11-03 11:55:17.706  5727  5747 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-03 11:55:17.707  5727  5747 I bt_vendor: epilog_cb
11-03 11:55:17.707  5727  5747 I bt_hci  : epilog_finished_callback
,11-03 11:55:17.710  5727  5743 I bt_hci_h4: hal_close
,11-03 11:55:17.711  5727  5743 I bt_userial_vendor: device fd = 54 close
,11-03 11:55:17.819  5727  5740 D bt_stack_manager: event_shut_down_stack finished.
,11-03 11:55:17.820  5727  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 11:55:17.825  5727  5739 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-03 11:55:17.825  5727  5727 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 11:55:17.826  5727  5727 D BtGatt.GattService: Received stop request...Stopping profile...
,11-03 11:55:17.826  5727  5727 D BtGatt.GattService: stop()
11-03 11:55:17.827  5727  5727 D BtGatt.AdvertiseManager: advertise clients cleared
11-03 11:55:17.829  5727  5727 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:17.830  5727  5727 V BluetoothAdapterState: isTurningOn()=false
11-03 11:55:17.830  5727  5727 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:17.830  5727  5727 V BluetoothAdapterState: isBleTurningOff()=true
11-03 11:55:17.830  5727  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-03 11:55:17.831  5727  5739 D BluetoothAdapterProperties: Setting state to 10
11-03 11:55:17.831  5727  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 11:55:17.832  5727  5739 I BluetoothAdapterState: Entering OffState
,11-03 11:55:17.833   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 11:55:17.847  5727  5727 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 11:55:17.847  5727  5727 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-03 11:55:17.847  5727  5727 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-03 11:55:17.850  5727  5740 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 11:55:17.857  5727  5727 I art     : System.exit called, status: 0
,11-03 11:55:17.858  5727  5727 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 11:55:17.886   927   937 I ActivityManager: Process com.android.bluetooth (pid 5727) has died
,11-03 11:55:18.608   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:19.160  3517  3517 I ConfigService: onDestroy
,11-03 11:55:19.609   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:20.609   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:21.611   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:22.399  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:55:22.400  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:22.405  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:55:22.405  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60568e6 removed from the list
11-03 11:55:22.406  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:55:22.406  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:22.406  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:22.408  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:22.408  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aba78d4 added. We now have 4 listener(s)
11-03 11:55:22.408  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 11:55:22.411  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:55:22.411  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aba78d4 removed from the list
,11-03 11:55:22.411  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 11:55:22.411  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:22.412  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:55:22.414  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:22.415  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2e3a7d added. We now have 4 listener(s)
,11-03 11:55:22.415  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 11:55:22.612   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:23.612   559   559 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 11:55:27.427  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:27.459   927   944 I ActivityManager: Start proc 5785:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 11:55:27.540  5785  5785 D AdapterServiceConfig: Adding HeadsetService
,11-03 11:55:27.540  5785  5785 D AdapterServiceConfig: Adding A2dpService
,11-03 11:55:27.540  5785  5785 D AdapterServiceConfig: Adding HidService
11-03 11:55:27.540  5785  5785 D AdapterServiceConfig: Adding HealthService
11-03 11:55:27.540  5785  5785 D AdapterServiceConfig: Adding PanService
11-03 11:55:27.541  5785  5785 D AdapterServiceConfig: Adding GattService
11-03 11:55:27.541  5785  5785 D AdapterServiceConfig: Adding BluetoothMapService
11-03 11:55:27.541  5785  5785 D AdapterServiceConfig: Adding SapService
,11-03 11:55:27.553   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@99eaea1:true
,11-03 11:55:27.554  5785  5785 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 11:55:27.556  5785  5785 I bt_bluedroid: init
11-03 11:55:27.556  5785  5797 I BluetoothAdapterState: Entering OffState
,11-03 11:55:27.558  5785  5798 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 11:55:27.558  5785  5798 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 11:55:27.558  5785  5798 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-03 11:55:27.558  5785  5798 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-03 11:55:27.559  5785  5785 I bt_bluedroid: get_profile_interface socket
,11-03 11:55:27.561  5785  5801 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 11:55:27.561  5785  5785 I bt_bluedroid: get_profile_interface sdp
11-03 11:55:27.563  5785  5801 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 11:55:27.566  5785  5796 I bt_bluedroid: config_hci_snoop_log
,11-03 11:55:27.567   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 11:55:27.571  5785  5797 D BluetoothAdapterState: Current state: OFF, message: 0
11-03 11:55:27.571  5785  5797 D BluetoothAdapterProperties: Setting state to 14
11-03 11:55:27.571  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 11:55:27.572  5785  5797 D BluetoothBondStateMachine: make
,11-03 11:55:27.574  5785  5802 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 11:55:27.577  5785  5797 I BluetoothAdapterState: Entering PendingCommandState
,11-03 11:55:27.578  5785  5785 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 11:55:27.580  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
11-03 11:55:27.581  5785  5785 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 11:55:27.581  5785  5785 D BtGatt.GattService: Received start request. Starting profile...
11-03 11:55:27.581  5785  5785 D BtGatt.GattService: start()
11-03 11:55:27.581  5785  5785 I bt_bluedroid: get_profile_interface gatt
11-03 11:55:27.582  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
11-03 11:55:27.582  5785  5785 D BtGatt.AdvertiseManager: advertise manager created
,11-03 11:55:27.588  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:27.588  5785  5785 V BluetoothAdapterState: isTurningOn()=false
11-03 11:55:27.588  5785  5785 V BluetoothAdapterState: isBleTurningOn()=true
,11-03 11:55:27.588  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:27.588  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-03 11:55:27.589  5785  5797 I bt_bluedroid: bt_bluedroid
11-03 11:55:27.589  5785  5798 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-03 11:55:27.590  5785  5798 I bt_hci  : start_up
,11-03 11:55:27.594  5785  5798 I bt_vendor: alloc value 0xf3cc9871
11-03 11:55:27.594  5785  5798 I bt_vendor: init
11-03 11:55:27.594  5785  5798 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,11-03 11:55:27.594  5785  5798 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 11:55:27.704  5785  5798 D bt_hci  : start_up starting async portion
,11-03 11:55:27.704  5785  5805 I bt_hci  : event_finish_startup
11-03 11:55:27.704  5785  5805 I bt_hci_h4: hal_open
11-03 11:55:27.704  5785  5805 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 11:55:27.701  5806  5806 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 11:55:27.707  5785  5805 I bt_userial_vendor: device fd = 54 open
,11-03 11:55:27.724  5785  5805 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 11:55:27.727  5785  5805 D bt_hwcfg: Chipset BCM4358A3
,11-03 11:55:27.727  5785  5805 D bt_hwcfg: Target name = [BCM4358A3]
11-03 11:55:27.728  5785  5805 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 11:55:28.123  5785  5805 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 11:55:28.124  5785  5805 D bt_hwcfg: Settlement delay -- 100 ms
11-03 11:55:28.124  5785  5805 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 11:55:28.258  5785  5805 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 11:55:28.259  5785  5805 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 11:55:28.260  5785  5805 I bt_hwcfg: vendor lib fwcfg completed
11-03 11:55:28.260  5785  5805 I bt_vendor: firmware callback
,11-03 11:55:28.260  5785  5805 I bt_hci  : firmware_config_callback
,11-03 11:55:28.270  5785  5808 I bt_btu  : btu_task pending for preload complete event
,11-03 11:55:28.270  5785  5808 I bt_btu_task: Bluetooth chip preload is complete
11-03 11:55:28.270  5785  5808 I bt_btu  : btu_task received preload complete event
,11-03 11:55:28.277  5785  5808 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 11:55:28.277  5785  5808 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-03 11:55:28.277  5785  5808 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-03 11:55:28.277  5785  5808 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-03 11:55:28.277  5785  5808 I         : BTE_InitTraceLevels -- TRC_AVRC
11-03 11:55:28.277  5785  5808 I         : BTE_InitTraceLevels -- TRC_A2D
,11-03 11:55:28.277  5785  5808 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-03 11:55:28.278  5785  5808 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 11:55:28.278  5785  5808 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 11:55:28.278  5785  5808 I         : BTE_InitTraceLevels -- TRC_PAN
,11-03 11:55:28.278  5785  5808 I         : BTE_InitTraceLevels -- TRC_SDP
,11-03 11:55:28.278  5785  5808 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 11:55:28.278  5785  5808 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 11:55:28.278  5785  5808 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-03 11:55:28.278  5785  5808 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 11:55:28.364  5785  5808 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c47549
11-03 11:55:28.364  5785  5808 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c47549 
,11-03 11:55:28.391  5785  5801 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 11:55:28.392  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 11:55:28.393  5785  5801 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 11:55:28.395  5785  5801 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 11:55:28.397  5785  5801 D BluetoothAdapterProperties: Scan Mode:20
,11-03 11:55:28.397  5785  5801 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 11:55:28.397  5785  5801 D bt_hci  : do_postload posting postload work item
11-03 11:55:28.398  5785  5805 I bt_hci  : event_postload
,11-03 11:55:28.398  5785  5805 I bt_vendor: sco_config_cb
11-03 11:55:28.398  5785  5805 I bt_hci  : sco_config_callback postload finished.
11-03 11:55:28.399  5785  5801 D bt_bte_conf: Device ID record 1 : primary
,11-03 11:55:28.400  5785  5801 D bt_bte_conf:   vendorId            = 000f
11-03 11:55:28.400  5785  5801 D bt_bte_conf:   vendorIdSource      = 0001
11-03 11:55:28.400  5785  5801 D bt_bte_conf:   product             = 1200
,11-03 11:55:28.400  5785  5801 D bt_bte_conf:   version             = 1436
11-03 11:55:28.400  5785  5801 D bt_bte_conf:   clientExecutableURL = 
11-03 11:55:28.400  5785  5801 D bt_bte_conf:   serviceDescription  = 
11-03 11:55:28.400  5785  5801 D bt_bte_conf:   documentationURL    = 
11-03 11:55:28.400  5785  5801 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 11:55:28.400  5785  5798 D bt_stack_manager: event_start_up_stack finished
,11-03 11:55:28.401  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 11:55:28.401  5785  5797 D BluetoothAdapterProperties: Setting state to 15
11-03 11:55:28.401  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 11:55:28.402  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:28.402  5785  5797 I BluetoothAdapterState: Entering BleOnState
,11-03 11:55:28.408  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:28.410  5785  5797 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 11:55:28.410  5785  5797 D BluetoothAdapterProperties: Setting state to 11
,11-03 11:55:28.410  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-03 11:55:28.411  5785  5805 I bt_vendor: low_power_mode_cb
11-03 11:55:28.414  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:28.415  5785  5785 D HeadsetService: Received start request. Starting profile...
,11-03 11:55:28.418  5785  5785 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 11:55:28.418  5785  5785 D HeadsetStateMachine: make
,11-03 11:55:28.422  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:28.424  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:28.428  5785  5797 I BluetoothAdapterState: Entering PendingCommandState
,11-03 11:55:28.431  5785  5785 D HeadsetStateMachine: max_hf_connections = 1
,11-03 11:55:28.431  5785  5785 I bt_bluedroid: get_profile_interface handsfree
11-03 11:55:28.431  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 11:55:28.431  5785  5801 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-03 11:55:28.434  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:28.435  5785  5785 D A2dpService: Received start request. Starting profile...
,11-03 11:55:28.435  5785  5785 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 11:55:28.436  5785  5785 I bt_bluedroid: get_profile_interface avrcp
,11-03 11:55:28.441  5785  5785 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-03 11:55:28.441  5785  5785 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 11:55:28.441  5785  5785 D A2dpStateMachine: make
,11-03 11:55:28.443  5785  5785 I bt_bluedroid: get_profile_interface a2dp
,11-03 11:55:28.443  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 11:55:28.445  5785  5817 D A2dpStateMachine: Enter Disconnected: -2
11-03 11:55:28.445  5785  5785 I BluetoothHidServiceJni: classInitNative: succeeds
11-03 11:55:28.446  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:28.447  5785  5785 D HidService: Received start request. Starting profile...
11-03 11:55:28.447  5785  5785 I bt_bluedroid: get_profile_interface hidhost
11-03 11:55:28.447  5785  5785 D HidService: setHidService(): set to: null
11-03 11:55:28.447  5785  5801 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c2856d
11-03 11:55:28.447  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 11:55:28.448  5785  5785 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-03 11:55:28.448  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:28.449  5785  5785 D HealthService: Received start request. Starting profile...
,11-03 11:55:28.451  5785  5785 I bt_bluedroid: get_profile_interface health
,11-03 11:55:28.452  5785  5785 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-03 11:55:28.453  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
11-03 11:55:28.453  5785  5785 D PanService: Received start request. Starting profile...
11-03 11:55:28.453  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 11:55:28.453  5785  5785 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 11:55:28.453  5785  5785 I bt_bluedroid: get_profile_interface pan
11-03 11:55:28.455  5785  5801 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-03 11:55:28.455  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:28.456  5785  5785 D BluetoothMapService: Received start request. Starting profile...
11-03 11:55:28.457  5785  5785 D BluetoothMapService: start()
11-03 11:55:28.459  5785  5785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-03 11:55:28.460  5785  5785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 11:55:28.460  5785  5785 D BluetoothMapAppObserver: createReceiver()
11-03 11:55:28.461  5785  5785 D BluetoothMapAppObserver: initObservers()
11-03 11:55:28.462  5785  5785 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 11:55:28.470  5785  5785 V SapService: SapBinder()
11-03 11:55:28.470  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
,11-03 11:55:28.471  5785  5785 D SapService: Received start request. Starting profile...
11-03 11:55:28.471  5785  5785 V SapService: start()
,11-03 11:55:28.473  5785  5785 V BluetoothAdapterState: isTurningOff()=false
,11-03 11:55:28.473  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:28.473  5785  5814 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 11:55:28.473  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:28.473  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:28.473  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:28.474  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:28.474  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 11:55:28.474  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:28.474  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:28.474  5785  5785 V BluetoothAdapterState: isTurningOn()=true
,11-03 11:55:28.474  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 11:55:28.485  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:28.485  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:28.485  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:28.485  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:28.485  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:28.486  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:28.486  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:28.486  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 11:55:28.486  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:28.486  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:28.486  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:28.486  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-03 11:55:28.487  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:28.487  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-03 11:55:28.487  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-03 11:55:28.487  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 11:55:28.488  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-03 11:55:28.488  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 11:55:28.488  5785  5797 D BluetoothAdapterProperties: ScanMode =  20
11-03 11:55:28.488  5785  5797 D BluetoothAdapterProperties: State =  11
11-03 11:55:28.490  5785  5801 D BluetoothAdapterProperties: Scan Mode:21
11-03 11:55:28.490  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 11:55:28.490  5785  5797 D BluetoothAdapterProperties: Setting state to 12
11-03 11:55:28.490  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 11:55:28.490  5785  5801 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 11:55:28.491  3067  3082 D BluetoothMap: onBluetoothStateChange: up=true
11-03 11:55:28.492  5785  5797 I BluetoothAdapterState: Entering OnState
11-03 11:55:28.494  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:28.494  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:28.494  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:28.494  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:28.494  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:28.494  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:28.494  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:28.494  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:28.494   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:28.494   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:28.494  3067  3079 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 11:55:28.496  3067  3259 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:28.497  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:28.497  5574  5584 D BluetoothPan: onBluetoothStateChange on: true
11-03 11:55:28.499  3067  3067 D BluetoothMap: Proxy object connected
11-03 11:55:28.499  3067  3067 D MapProfile: Bluetooth service connected
11-03 11:55:28.499  3067  3067 D BluetoothMap: getConnectedDevices()
11-03 11:55:28.500  5574  5574 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 11:55:28.500   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 11:55:28.500  5574  5574 D PanProfile: Bluetooth service connected
11-03 11:55:28.501  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:28.501  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:28.501  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:28.501  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:28.501  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:28.501  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:28.501  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:28.501  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 11:55:28.501   927   927 D BluetoothA2dp: Proxy object connected
11-03 11:55:28.501  3067  3259 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 11:55:28.501  3067  3067 D BluetoothA2dp: Proxy object connected
11-03 11:55:28.503  3685  3715 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:28.503  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 11:55:28.503  5574  5586 D BluetoothMap: onBluetoothStateChange: up=true
11-03 11:55:28.505  5574  5574 D BluetoothMap: Proxy object connected
11-03 11:55:28.505  5574  5574 D MapProfile: Bluetooth service connected
11-03 11:55:28.505  5574  5574 D BluetoothMap: getConnectedDevices()
11-03 11:55:28.506  3067  3082 D BluetoothPan: onBluetoothStateChange on: true
11-03 11:55:28.508  3067  3067 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 11:55:28.508  5574  5584 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:28.508  3067  3067 D PanProfile: Bluetooth service connected
11-03 11:55:28.508   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 11:55:28.508  5574  5586 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 11:55:28.510  5574  5584 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 11:55:28.512  5574  5586 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 11:55:28.513  3067  3079 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 11:55:28.515  3067  3067 D BluetoothInputDevice: Proxy object connected
11-03 11:55:28.515  3067  3067 D HidProfile: Bluetooth service connected
11-03 11:55:28.516   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 11:55:28.517  5574  5574 D BluetoothA2dp: Proxy object connected
11-03 11:55:28.517  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 11:55:28.517  5785  5785 D BluetoothMapService: onReceive
11-03 11:55:28.517  5785  5785 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 11:55:28.518  5785  5785 D BluetoothMapService: STATE_ON
11-03 11:55:28.519  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:28.520  5574  5574 D BluetoothInputDevice: Proxy object connected
11-03 11:55:28.520  5574  5574 D HidProfile: Bluetooth service connected
,11-03 11:55:28.521  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:28.523  5785  5824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 11:55:28.524  5785  5824 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 11:55:28.524  5785  5824 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 11:55:28.526  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 11:55:28.533  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 11:55:28.535  5574  5574 D DockEventReceiver: finishStartingService: stopping service
11-03 11:55:28.538  5574  5574 D BluetoothPbap: Proxy object connected
11-03 11:55:28.538  5574  5574 D PbapServerProfile: Bluetooth service connected
11-03 11:55:28.544  5785  5785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 11:55:28.545  5785  5785 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 11:55:28.546  5785  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 11:55:28.546  5785  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 11:55:28.549  3067  3067 D BluetoothPbap: Proxy object connected
11-03 11:55:28.549  3067  3067 D PbapServerProfile: Bluetooth service connected
11-03 11:55:28.550  5785  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 11:55:28.552  5785  5785 D ObexServerSockets: Succeed to create listening sockets 
11-03 11:55:28.552  5785  5785 D ObexServerSockets0: startAccept()
11-03 11:55:28.552  5785  5785 D ObexServerSockets0: prepareForNewConnect()
11-03 11:55:28.554  5785  5785 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 11:55:28.554  5785  5785 D BluetoothSdpJni: SDP Create record success - handle: 1
11-03 11:55:28.557  5785  5830 D ObexServerSockets0: Accepting socket connection...
11-03 11:55:28.557  5785  5831 D ObexServerSockets0: Accepting socket connection...
,11-03 11:55:28.568  5785  5835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 11:55:28.569  5785  5835 I BtOppRfcommListener: Accept thread started.
,11-03 11:55:28.595  3685  3722 D BluetoothHeadset: Proxy object connected
11-03 11:55:28.595   927   927 D BluetoothHeadset: Proxy object connected
11-03 11:55:28.595   927   944 D BluetoothHeadset: Proxy object connected
,11-03 11:55:28.595   927   927 D BluetoothHeadset: Proxy object connected
11-03 11:55:28.595   927   927 D BluetoothHeadset: Proxy object connected
11-03 11:55:28.595  3067  3079 D BluetoothHeadset: Proxy object connected
11-03 11:55:28.595  3067  3067 D HeadsetProfile: Bluetooth service connected
,11-03 11:55:28.596  5574  5823 D BluetoothHeadset: Proxy object connected
11-03 11:55:28.596  3067  3259 D BluetoothHeadset: Proxy object connected
,11-03 11:55:28.598  3067  3067 D HeadsetProfile: Bluetooth service connected
,11-03 11:55:28.600  5574  5574 D HeadsetProfile: Bluetooth service connected
,11-03 11:55:28.603  3685  3916 D BluetoothHeadset: Proxy object connected
,11-03 11:55:28.608  5574  5586 D BluetoothHeadset: Proxy object connected
,11-03 11:55:28.609   927   944 D BluetoothHeadset: Proxy object connected
,11-03 11:55:28.609  5574  5574 D HeadsetProfile: Bluetooth service connected
,11-03 11:55:30.860  3888  4345 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-03 11:55:32.443  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:32.443  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:32.443  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:32.443  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 11:55:32.443  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:32.443  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:32.443  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:32.443  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 11:55:32.449  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 11:55:32.450  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:55:32.450  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2e3a7d removed from the list
,11-03 11:55:32.450  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 11:55:32.450  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:55:32.450  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:55:32.452  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 11:55:32.452  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@52f2d72 added. We now have 4 listener(s)
11-03 11:55:32.453  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 11:55:32.456   927  3493 D WifiService: setWifiEnabled: false pid=5514, uid=10077
11-03 11:55:32.456   927  3493 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 11:55:37.466  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:37.467   927   938 D WifiService: setWifiEnabled: true pid=5514, uid=10077
11-03 11:55:37.467   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 11:55:37.474   507   920 D SoftapController: Softap fwReload - Ok
,11-03 11:55:37.480   507   920 D CommandListener: Setting iface cfg
,11-03 11:55:37.481   507   920 D CommandListener: Trying to bring down wlan0
,11-03 11:55:37.482   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-03 11:55:37.487   927  2888 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 11:55:38.158   927  2888 D wifi    : set interface wlan0 flags (UP)
,11-03 11:55:38.159   927  2888 I WifiHAL : Initializing wifi
11-03 11:55:38.159   927  2888 I WifiHAL : Creating socket
,11-03 11:55:38.166   927  2888 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 11:55:38.167   927  2888 D wifi    : Did set static halHandle = 0x7f7fd9b400
,11-03 11:55:38.167   927  2888 D wifi    : halHandle = 0x7f7fd9b400, mVM = 0x7f9c34d140, mCls = 0x201856
,11-03 11:55:38.167   927  2888 D wifi    : array field set
11-03 11:55:38.167   927  2888 I WifiNative-HAL: interface[0] = wlan0
11-03 11:55:38.168   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-03 11:55:38.170   927  5840 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547605820416
,11-03 11:55:38.170   927  5840 D wifi    : waitForHalEvents called, vm = 0x7f9c34d140, obj = 0x201856, env = 0x7f7d9d6e00
,11-03 11:55:38.233  5841  5841 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 11:55:38.272   927  2888 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 11:55:38.279  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:38.283  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:38.310  5841  5841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 11:55:38.380  5841  5841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 11:55:38.380  5841  5841 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 11:55:38.403   927  2888 D WifiConfigStore: Loading config and enabling all networks 
,11-03 11:55:38.406  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:38.406  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:38.406  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:38.406  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:38.406  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:38.406  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:38.406  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:38.406  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 11:55:38.409  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 11:55:38.413  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:38.413  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:38.413  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:38.413  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:38.413  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:38.413  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 11:55:38.413  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 11:55:38.413  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 11:55:38.415  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 11:55:38.436   927  2888 D WifiConfigStore: loaded 0 passpoint configs
,11-03 11:55:38.437   927  2888 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 11:55:38.438   927  2888 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-03 11:55:38.439   927  2888 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-03 11:55:38.440   927  2888 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-03 11:55:38.440   927  2888 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 11:55:38.441   927  2888 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-03 11:55:38.442   927  2888 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 11:55:38.442   927  2888 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 11:55:38.442   927  2888 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 11:55:38.442   927  2888 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 11:55:38.442   927  2888 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 11:55:38.442   927  2888 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 11:55:38.446   927  2888 D WifiNative-HAL: Setting external_sim to 1
,11-03 11:55:38.447  4418  4418 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 11:55:38.447   927  2888 D wifi    : setting dfs flag to true, 0x7f7daadc80
,11-03 11:55:38.447   927  2888 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 11:55:38.448   927  2888 D wifi    : setting scan oui 0x7f7daadc80
11-03 11:55:38.448   927  2888 D WifiHAL : Sending mac address OUI
,11-03 11:55:38.452   927  2888 E native  : do suspend false
,11-03 11:55:38.464   927  2888 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-03 11:55:38.464   927   927 D RttService: SCAN_AVAILABLE : 3
11-03 11:55:38.464   927  2995 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 11:55:38.464   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-03 11:55:38.466   507   920 D CommandListener: Setting iface cfg
,11-03 11:55:38.471   927  2887 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
,11-03 11:55:38.471   927  2887 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 11:55:38.482   927  2887 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 11:55:38.488   927  2887 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 11:55:38.488   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164334 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,11-03 11:55:38.613   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:39.614   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:40.616   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:41.575  5841  5841 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 11:55:41.584  5841  5841 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 11:55:41.589  5841  5841 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 11:55:41.595  5841  5841 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 11:55:41.616   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:41.618   927  2888 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 11:55:41.619   927  2888 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-03 11:55:41.619   927  2888 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 11:55:41.629   927  2888 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 11:55:41.663   927  2888 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 11:55:41.668  5841  5841 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 11:55:42.093  5841  5841 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 11:55:42.125  5841  5841 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 11:55:42.125  5841  5841 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 11:55:42.132   927  2888 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 11:55:42.132   927  2888 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 11:55:42.132   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 11:55:42.147   927  2888 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 11:55:42.158   507   920 D CommandListener: Setting iface cfg
,11-03 11:55:42.164   927  2888 D WifiStateMachine: Start Dhcp Watchdog 3
,11-03 11:55:42.169   927  5846 D DhcpClient: Receive thread started
,11-03 11:55:42.173   927  2890 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-03 11:55:42.173   927  2888 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-03 11:55:42.174   927  2890 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-03 11:55:42.254   927  2888 E native  : do suspend false
,11-03 11:55:42.264   927  5845 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 11:55:42.284   927  5846 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-03 11:55:42.285   927  5845 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-03 11:55:42.286   927  5845 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 11:55:42.299   927  5846 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 11:55:42.299   927  5845 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-03 11:55:42.302   507   920 D CommandListener: Setting iface cfg
,11-03 11:55:42.306   927  2888 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 11:55:42.313   927  5845 D DhcpClient: Scheduling renewal in 86399s
,11-03 11:55:42.325   927  2888 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-03 11:55:42.327   927  2888 D WifiConfigStore: No blacklist allowed without epno enabled
11-03 11:55:42.329   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-03 11:55:42.337   927  2890 D ConnectivityService: Adding iface wlan0 to network 102
,11-03 11:55:42.343   927  2888 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-03 11:55:42.385   927  2890 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-03 11:55:42.385   927  2890 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-03 11:55:42.391   927  2890 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-03 11:55:42.394   927  2890 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-03 11:55:42.395   927  2890 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-03 11:55:42.403   927  2890 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 11:55:42.408   927  2890 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-03 11:55:42.408   927  2890 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-03 11:55:42.408   927  2890 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-03 11:55:42.408   927  2890 D ConnectivityService:    accepting network in place of null
11-03 11:55:42.408   927  2888 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 11:55:42.408   927  2888 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 11:55:42.409   927  2890 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 11:55:42.421   927  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168267, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 11:55:42.429   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 11:55:42.449   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 11:55:42.453   927  2890 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-03 11:55:42.453   927  2890 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 11:55:42.453  3650  3772 W QCNEJ   : |CORE| network available: 102
11-03 11:55:42.454   927  2890 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-03 11:55:42.455   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-03 11:55:42.458  3650  3772 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-03 11:55:42.459  3650  3772 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 11:55:42.459  3650  3772 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-03 11:55:42.465  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:42.465  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:42.465  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:42.465  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:42.465  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:42.465  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.465  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:42.465  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:55:42.467  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 11:55:42.471  4933  4952 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-03 11:55:42.471  4933  4952 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-03 11:55:42.471  4933  4952 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-03 11:55:42.472  4933  4952 E SarControlService: no key has been found,reset the power
11-03 11:55:42.472  4933  4984 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-03 11:55:42.472  4933  4984 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-03 11:55:42.472  4933  4984 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-03 11:55:42.472  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 11:55:42.473  4967  4967 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-03 11:55:42.473  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:42.473  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:42.473  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:42.473  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:42.473  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:42.473  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.473  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:42.473  5514  5514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:55:42.473  4933  4984 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-03 11:55:42.474  4933  4984 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-03 11:55:42.474  4933  4984 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-03 11:55:42.474  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 11:55:42.474  4967  4967 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-03 11:55:42.477  3986  3986 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 11:55:42.477  5514  5514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.478  3872  3872 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-03 11:55:42.481  3986  3986 D SystemUpdateService: onCreate
,11-03 11:55:42.481  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 11:55:42.481  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:42.481  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:42.481  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:42.481  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:42.481  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.481  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:42.481  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:55:42.482  4967  4987 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@43dd809 HexData = [00000000f003000000000000ffffffff]
,11-03 11:55:42.482  4967  4987 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-03 11:55:42.483  4967  4987 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,11-03 11:55:42.483  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-03 11:55:42.483  4933  4947 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-03 11:55:42.484  4967  4987 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@43dd809 HexData = [00000000f103000000000000ffffffff]
11-03 11:55:42.484  4967  4987 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-03 11:55:42.485  4967  4987 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-03 11:55:42.486  4967  4967 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-03 11:55:42.486  4933  4949 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-03 11:55:42.486  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.487  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.487  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@52f2d72 removed from the list
11-03 11:55:42.487  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:55:42.487  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.487  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.488  3986  3986 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-03 11:55:42.490  5514  5561 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-03 11:55:42.491  5514  5561 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-03 11:55:42.493  5514  5561 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3cfce7d Bundle[{}]
11-03 11:55:42.494  5514  5561 I io.jxcore.node.LifeCycleMonitor: start: OK
11-03 11:55:42.494  5514  5561 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-03 11:55:42.495  5514  5561 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-03 11:55:42.495  5514  5561 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-03 11:55:42.496  5514  5561 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-03 11:55:42.496  5514  5561 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 11:55:42.504  5514  5561 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
11-03 11:55:42.504  5514  5561 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-03 11:55:42.504  3986  5856 I SystemUpdateService: active receiver: enabled
11-03 11:55:42.504  5514  5561 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
,11-03 11:55:42.506  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 11:55:42.506  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1b45c3 added. We now have 3 listener(s)
11-03 11:55:42.507  3986  3986 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-03 11:55:42.508  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 11:55:42.508  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:55:42.508  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 11:55:42.508  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:42.508  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb04e40 added. We now have 4 listener(s)
11-03 11:55:42.508  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:55:42.509  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 11:55:42.511  3986  5293 I iu.UploadsManager: num queued entries: 0
,11-03 11:55:42.511  3986  5293 I iu.UploadsManager: num updated entries: 0
11-03 11:55:42.512  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 11:55:42.512  3986  5293 I iu.SyncManager: NEXT; no task
,11-03 11:55:42.516  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:55:42.516  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:42.516  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:42.516  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:42.516  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:42.516  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.516  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:42.516  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:55:42.518  3986  3986 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 11:55:42.518  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 11:55:42.518  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 11:55:42.518  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 11:55:42.518  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2beaebe added. We now have 4 listener(s)
11-03 11:55:42.519  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 11:55:42.520  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:55:42.520  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 11:55:42.520  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:42.520  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9627b1f added. We now have 5 listener(s)
11-03 11:55:42.520  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:55:42.520  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:55:42.520  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:55:42.520  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:55:42.520  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:55:42.520  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.520  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:55:42.520  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:55:42.520  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 11:55:42.520  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1b45c3 removed from the list
11-03 11:55:42.520  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.520  3986  3986 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-03 11:55:42.520  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb04e40 removed from the list
,11-03 11:55:42.523  5652  5652 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 11:55:42.523  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:42.523  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:55:42.523  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.524  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.524  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:55:42.524  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.525  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.525  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.525  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.525  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:55:42.525  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:55:42.525  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.525  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb04e40 not in the list
11-03 11:55:42.525  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.525  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.525  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.526  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:42.527  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.527  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.527  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.527  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:55:42.527  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:55:42.527  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.527  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9627b1f removed from the list
11-03 11:55:42.527  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:55:42.527  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.527  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:55:42.527  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:55:42.527  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 11:55:42.527  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2beaebe removed from the list
11-03 11:55:42.528  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 11:55:42.528  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c0e6c added. We now have 3 listener(s)
11-03 11:55:42.528  5652  5652 D SprintDMHelper: simOperator: 
11-03 11:55:42.529  5652  5652 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-03 11:55:42.529  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 11:55:42.529  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:55:42.529  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 11:55:42.529  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:42.529  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ef3c35 added. We now have 4 listener(s)
,11-03 11:55:42.529  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 11:55:42.534  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 11:55:42.537  3986  5856 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-03 11:55:42.538  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 11:55:42.545  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:55:42.545  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:42.545  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:42.545  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:42.545  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:42.545  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.545  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:42.545  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:55:42.546  3986  5856 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-03 11:55:42.546  3986  5856 I SystemUpdateService: now status is 0 (complete)
,11-03 11:55:42.546  3986  5856 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 11:55:42.546  3986  5856 I SystemUpdateService: file has been verified
11-03 11:55:42.546  3986  5856 I SystemUpdateService: OTA package size = 21989297
,11-03 11:55:42.547  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.547  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 11:55:42.547  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 11:55:42.547  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bdaa3b added. We now have 4 listener(s)
11-03 11:55:42.548  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 11:55:42.548  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:55:42.548  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 11:55:42.548  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:42.548  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41a558 added. We now have 5 listener(s)
11-03 11:55:42.548  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:55:42.549  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 11:55:42.549  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 11:55:42.549  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 11:55:42.549  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 11:55:42.549  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 11:55:42.549  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:42.552  3986  5856 I SystemUpdateService: showing system update notification
11-03 11:55:42.552  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 11:55:42.552  5514  5561 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 11:55:42.552  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 11:55:42.552  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:42.557  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.557  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 11:55:42.558  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 11:55:42.558  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 11:55:42.558  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 11:55:42.563  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.563  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 11:55:42.563  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 11:55:42.563  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 11:55:42.563  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 11:55:42.563  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.564  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:55:42.566  5785  5822 D BtGatt.GattService: registerClient() - UUID=20c37d28-99b8-4d3b-8108-b1689ffab528
11-03 11:55:42.567  5785  5801 D BtGatt.GattService: onClientRegistered() - UUID=20c37d28-99b8-4d3b-8108-b1689ffab528, clientIf=5
,11-03 11:55:42.568  5514  5525 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 11:55:42.569  5785  5815 D BtGatt.GattService: start scan with filters
,11-03 11:55:42.572  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 11:55:42.572  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.572  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 11:55:42.572  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.572  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 11:55:42.573  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 11:55:42.573  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.573  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-03 11:55:42.573  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 11:55:42.573  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-03 11:55:42.573  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-03 11:55:42.573  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 11:55:42.574  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 11:55:42.574  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.574  5785  5804 D BtGatt.ScanManager: handling starting scan
11-03 11:55:42.575  5785  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f12ce6
11-03 11:55:42.576  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.576  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:55:42.576  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.576  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.576  5514  5561 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 11:55:42.576  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 11:55:42.576  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 11:55:42.576  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.576  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-03 11:55:42.576  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.576  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:55:42.576  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 11:55:42.579  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.579  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 11:55:42.579  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.579  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.579  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 11:55:42.579  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 11:55:42.579  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 11:55:42.579  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:55:42.579  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.579  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.579  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.579  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 11:55:42.579  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.580  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:55:42.580  5785  5822 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 11:55:42.580  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 11:55:42.581  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:55:42.581  5785  5812 D BtGatt.GattService: stopScan() - queue size =1
,11-03 11:55:42.582  5785  5801 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 11:55:42.582  5785  5796 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 11:55:42.582  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.582  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 11:55:42.582  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.582  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 11:55:42.582  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.582  5785  5804 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 11:55:42.582  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.582  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.583  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.583  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 11:55:42.583  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.583  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.583  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.583  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 11:55:42.583  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 11:55:42.583  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:55:42.583  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.584  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.584  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 11:55:42.585  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.585  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.585  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:55:42.585  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:55:42.585  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 11:55:42.585  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.585  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-03 11:55:42.585  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-03 11:55:42.585  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-03 11:55:42.585  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.585  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 11:55:42.585  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.586   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-03 11:55:42.587  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:55:42.587  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:55:42.587  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:55:42.587  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 11:55:42.587  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.587  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.587  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:55:42.587  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.587  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:55:42.587  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.587  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 11:55:42.587  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.587  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c0e6c removed from the list
11-03 11:55:42.587  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:55:42.587  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 11:55:42.587  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ef3c35 removed from the list
11-03 11:55:42.587  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:55:42.587  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.588  5785  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 11:55:42.588  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.588  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:55:42.588  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.588  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.588  5785  5804 D BtGatt.ScanManager: Starting BLE batch scan
11-03 11:55:42.588  3986  3986 D SystemUpdateService: onDestroy
11-03 11:55:42.588  5785  5804 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 11:55:42.590  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.590  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.590  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.590  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:55:42.590  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:55:42.590  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.590  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ef3c35 not in the list
11-03 11:55:42.590  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.590  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.590  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.591  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.591  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.591  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.591  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:55:42.591  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:55:42.591  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.591  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41a558 removed from the list
11-03 11:55:42.592  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:55:42.592  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:55:42.592  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.592  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:55:42.592  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 11:55:42.592  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bdaa3b removed from the list
11-03 11:55:42.592  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 11:55:42.592  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd7bf04 added. We now have 3 listener(s)
11-03 11:55:42.594  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 11:55:42.594  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:55:42.594  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 11:55:42.594  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:42.594  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@827bced added. We now have 4 listener(s)
,11-03 11:55:42.594  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:55:42.595  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 11:55:42.597  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 11:55:42.598  5785  5801 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 11:55:42.598  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.602  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:55:42.602  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:42.602  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:42.602  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:42.602  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:42.602  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.602  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:42.602  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 11:55:42.604  5785  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 11:55:42.604  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.605  3517  5866 I VacuumService: Vacuum at: now=1478170542605 tag=VacuumService
11-03 11:55:42.605  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.605  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 11:55:42.605  5785  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 11:55:42.605  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 11:55:42.606  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc925b3 added. We now have 4 listener(s)
11-03 11:55:42.607  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 11:55:42.607  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:55:42.607  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 11:55:42.607  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:42.607  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@993c770 added. We now have 5 listener(s)
11-03 11:55:42.607  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:55:42.607  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 11:55:42.608  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening ,to advertisements only
11-03 11:55:42.608  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 11:55:42.608  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 11:55:42.608  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 11:55:42.608  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 11:55:42.608  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:42.611  5785  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 11:55:42.611  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.611  5785  5801 E BtGatt.ContextMap: Context not found for ID 5
11-03 11:55:42.612  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:42.614  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 11:55:42.615  5514  5561 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-03 11:55:42.615  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 11:55:42.617   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:55:42.622  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.622  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 11:55:42.623  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 11:55:42.623  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 11:55:42.623  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 11:55:42.625  5785  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 11:55:42.626  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.626  5785  5804 D BtGatt.ScanManager: stopping BLe Batch
,11-03 11:55:42.627  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.627  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 11:55:42.627  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 11:55:42.627  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 11:55:42.627  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 11:55:42.628  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.628  5514  5561 D BluetoothAdapter: STATE_ON
,11-03 11:55:42.630  5785  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 11:55:42.630  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.631  5785  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 11:55:42.631  5785  5812 D BtGatt.GattService: registerClient() - UUID=a35db6d2-b14a-4a48-aa4d-ba6f6d98f1d6
11-03 11:55:42.631  5785  5801 D BtGatt.GattService: onClientRegistered() - UUID=a35db6d2-b14a-4a48-aa4d-ba6f6d98f1d6, clientIf=5
,11-03 11:55:42.632  5514  5524 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 11:55:42.632  5785  5796 D BtGatt.GattService: start scan with filters
,11-03 11:55:42.635  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 11:55:42.636  5785  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 11:55:42.636  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.635  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.636  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 11:55:42.636  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.636  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 11:55:42.636  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 11:55:42.636  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.636  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 11:55:42.636  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 11:55:42.636  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.636  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.637  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 11:55:42.638  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-03 11:55:42.638  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.639  5785  5804 D BtGatt.ScanManager: handling starting scan
11-03 11:55:42.640  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.640  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:55:42.640  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.640  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.640  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 11:55:42.641  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.641  5514  5561 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-03 11:55:42.641  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:55:42.641  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:55:42.641  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:55:42.641  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:55:42.641  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.641  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-03 11:55:42.641  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:55:42.641  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 11:55:42.641  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd7bf04 removed from the list
11-03 11:55:42.641  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.641  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@827bced removed from the list
11-03 11:55:42.641  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:55:42.641  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:55:42.641  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.642  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-03 11:55:42.642  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.642  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:55:42.642  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateS,tate: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.644  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.644  5785  5801 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 11:55:42.644  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.644  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.644  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.644  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:55:42.644  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:55:42.644  5785  5804 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 11:55:42.644  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.644  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@827bced not in the list
11-03 11:55:42.645  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.645  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.645  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.645  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.645  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 11:55:42.645  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 11:55:42.645  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 11:55:42.645  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:55:42.645  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.645  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.645  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.645  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 11:55:42.645  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.646  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:55:42.646  5785  5812 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 11:55:42.646  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 11:55:42.647  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:55:42.647  5785  5815 D BtGatt.GattService: stopScan() - queue size =1
11-03 11:55:42.648  5785  5825 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 11:55:42.648  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 11:55:42.648  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.648  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 11:55:42.648  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.649  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.649  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.649  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.649  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 11:55:42.649  5785  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 11:55:42.649  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.649  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.649  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.649  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.649  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 11:55:42.649  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 11:55:42.649  5785  5804 D BtGatt.ScanManager: Starting BLE batch scan
11-03 11:55:42.649  5785  5804 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 11:55:42.650  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.650  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.651  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.651  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 11:55:42.651  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.651  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.651  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 11:55:42.651  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 11:55:42.652  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.652  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 11:55:42.652  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@993c770 removed from the list
11-03 11:55:42.652  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:55:42.652  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:55:42.652  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.652  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 11:55:42.652  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.652  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:55:42.652  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.652  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-03 11:55:42.652  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 11:55:42.652  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc925b3 removed from the list
11-03 11:55:42.652  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 11:55:42.652  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.652  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.652  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 11:55:42.652  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.652  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 11:55:42.653  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c5ea9c added. We now have 3 listener(s)
11-03 11:55:42.654  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.654  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 11:55:42.654  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.654  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 11:55:42.654  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.654  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:55:42.654  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 11:55:42.654  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 11:55:42.654  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:42.654  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3689ca5 added. We now have 4 listener(s)
11-03 11:55:42.655  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:55:42.655  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 11:55:42.658  5785  5801 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 11:55:42.658  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.658  3517  5869 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-03 11:55:42.659  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 11:55:42.664  5785  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 11:55:42.664  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.665  5785  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 11:55:42.666  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:55:42.666  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:42.666  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:42.666  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:42.666  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:42.666  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.666  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:42.666  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:55:42.669  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.669  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 11:55:42.669  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 11:55:42.669  5785  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 11:55:42.669  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.669  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269982b added. We now have 4 listener(s)
11-03 11:55:42.669  5785  5801 E BtGatt.ContextMap: Context not found for ID 5
11-03 11:55:42.670  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 11:55:42.671  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:55:42.671  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 11:55:42.671  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:42.671  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f951488 added. We now have 5 listener(s)
11-03 11:55:42.671  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:55:42.671  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 11:55:42.671  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 11:55:42.671  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 11:55:42.671  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 11:55:42.671  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 11:55:42.671  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 11:55:42.674  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 11:55:42.674  5514  5561 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 11:55:42.674  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 11:55:42.675  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:42.678  5785  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 11:55:42.678  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:55:42.678  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.678  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 11:55:42.679  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 11:55:42.679  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 11:55:42.679  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 11:55:42.679  5785  5804 D BtGatt.ScanManager: stopping BLe Batch
,11-03 11:55:42.683  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.683  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 11:55:42.683  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 11:55:42.683  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 11:55:42.683  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 11:55:42.683  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.683  5514  5561 D BluetoothAdapter: STATE_ON
,11-03 11:55:42.686  5785  5795 D BtGatt.GattService: registerClient() - UUID=2b29f0c7-4b91-4a5c-9433-ca29cad0c671
,11-03 11:55:42.686  5785  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 11:55:42.686  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.687  5785  5801 D BtGatt.GattService: onClientRegistered() - UUID=2b29f0c7-4b91-4a5c-9433-ca29cad0c671, clientIf=5
11-03 11:55:42.687  5785  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 11:55:42.687  5514  5525 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 11:55:42.687  5785  5822 D BtGatt.GattService: start scan with filters
,11-03 11:55:42.690  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 11:55:42.690  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.690  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 11:55:42.690  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.691  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 11:55:42.691  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 11:55:42.691  5785  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 11:55:42.691  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.691  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.691  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-03 11:55:42.691  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 11:55:42.691  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.691  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.691  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 11:55:42.692  5785  5804 D BtGatt.ScanManager: handling starting scan
11-03 11:55:42.693  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 11:55:42.693  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.695  3517  5867 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-03 11:55:42.696  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.696  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:55:42.696  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.696  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.696  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.697  5785  5801 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 11:55:42.697  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.698  5785  5804 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 11:55:42.698  3517  5867 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-03 11:55:42.702  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 11:55:42.702  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.702  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.702  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.702  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 11:55:42.703  5785  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 11:55:42.703  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.703  5785  5804 D BtGatt.ScanManager: Starting BLE batch scan
11-03 11:55:42.703  5785  5804 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 11:55:42.704  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 11:55:42.704  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:55:42.704  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:55:42.704  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:55:42.704  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.704  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-03 11:55:42.704  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:55:42.704  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 11:55:42.704  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c5ea9c removed from the list
11-03 11:55:42.704  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 11:55:42.704  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3689ca5 removed from the list
11-03 11:55:42.704  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
11-03 11:55:42.704  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:55:42.705  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:55:42.705  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-03 11:55:42.705  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.705  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:55:42.705  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.706  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.706  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.706  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.706  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 11:55:42.706  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:55:42.706  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.706  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3689ca5 not in the list
11-03 11:55:42.706  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 11:55:42.706  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 11:55:42.706  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 11:55:42.707  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.707  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.707  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.707  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 11:55:42.707  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.707  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:55:42.707  5785  5822 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 11:55:42.708  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 11:55:42.709  5514  5561 D BluetoothAdapter: STATE_ON
11-03 11:55:42.709  5785  5825 D BtGatt.GattService: stopScan() - queue size =1
11-03 11:55:42.710  5785  5796 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 11:55:42.710  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
,11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.711  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 11:55:42.711  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-03 11:55:42.712  5785  5801 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 11:55:42.712  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.712  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.712  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.713  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.713  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 11:55:42.713  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.713  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.713  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:55:42.713  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 11:55:42.713  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.713  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:55:42.713  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f951488 removed from the list
11-03 11:55:42.713  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:55:42.713  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 11:55:42.713  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.713  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.713  5514  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 11:55:42.714  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 11:55:42.714  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-03 11:55:42.714  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 11:55:42.714  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 11:55:42.714  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269982b removed from the list
11-03 11:55:42.714  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 11:55:42.714  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.714  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.714  5514  5514 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 11:55:42.714  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.714  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 11:55:42.714  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@faaf134 added. We now have 3 listener(s)
11-03 11:55:42.715  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.715  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.715  5514  5514 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.715  5514  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 11:55:42.715  5514  5514 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 11:55:42.715  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 11:55:42.715  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:55:42.715  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 11:55:42.715  5785  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 11:55:42.716  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:42.716  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 11:55:42.716  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37ebb5d added. We now have 4 listener(s)
11-03 11:55:42.716  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 11:55:42.716  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 11:55:42.717  5785  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 11:55:42.719  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 11:55:42.722  5785  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 11:55:42.722  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.722  5785  5801 E BtGatt.ContextMap: Context not found for ID 5
,11-03 11:55:42.723  5514  5561 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 11:55:42.723  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 11:55:42.723  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 11:55:42.723  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 11:55:42.723  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 11:55:42.723  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 11:55:42.723  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 11:55:42.723  5514  5561 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 11:55:42.725  5514  5561 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 11:55:42.726  5514  5561 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 11:55:42.726  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 11:55:42.726  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a66e1a3 added. We now have 4 listener(s)
,11-03 11:55:42.727  5785  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 11:55:42.727  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.727  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 11:55:42.727  5785  5804 D BtGatt.ScanManager: stopping BLe Batch
11-03 11:55:42.727  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 11:55:42.728  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 11:55:42.728  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 11:55:42.728  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:42.728  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9feca0 added. We now have 5 listener(s)
11-03 11:55:42.728  5514  5561 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 11:55:42.728  5514  5561 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 11:55:42.728  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:55:42.728  5514  5561 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 11:55:42.728  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:55:42.728  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.728  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 11:55:42.728  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:55:42.728  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 11:55:42.728  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@faaf134 removed from the list
11-03 11:55:42.729  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.729  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37ebb5d removed from the list
,11-03 11:55:42.730  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 11:55:42.730  5514  5561 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 11:55:42.730  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 11:55:42.731  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 11:55:42.731  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.731  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.732  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.732  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.732  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.732  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 11:55:42.732  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 11:55:42.732  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.732  5514  5561 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37ebb5d not in the list
,11-03 11:55:42.732  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.732  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.732  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.732  3517  5867 W Uploader:  no longer exists, so no auth token.
11-03 11:55:42.733  5785  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 11:55:42.733  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.733  5785  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 11:55:42.733  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.734  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.734  5514  5561 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 11:55:42.734  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 11:55:42.734  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 11:55:42.734  5514  5561 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 11:55:42.734  5514  5561 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9feca0 removed from the list
11-03 11:55:42.734  5514  5561 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 11:55:42.734  5514  5561 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 11:55:42.734  5514  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 11:55:42.734  5514  5561 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 11:55:42.734  5514  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 11:55:42.734  5514  5561 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a66e1a3 removed from the list
11-03 11:55:42.735  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-03 11:55:42.735  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 11:55:42.735  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-03 11:55:42.735  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 11:55:42.735  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-03 11:55:42.735  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 11:55:42.738  5785  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 11:55:42.738  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 11:55:42.738  3517  5869 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 11:55:43.028  4418  5862 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-03 11:55:43.088  5514  5514 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 11:55:43.155  5514  5514 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 11:55:43.176   927   938 D ConnectivityService: reportNetworkConnectivity(102, true) by 10012
,11-03 11:55:43.188   927   937 D ConnectivityService: reportNetworkConnectivity(102, true) by 10012
,11-03 11:55:43.192   927   938 D ConnectivityService: reportNetworkConnectivity(102, true) by 10012
,11-03 11:55:43.210  3517  5871 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 11:55:43.215  5514  5514 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 11:55:43.348  3517  5869 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 11:55:43.423  3517  5867 W Uploader:  no longer exists, so no auth token.
,11-03 11:55:43.432  3517  5871 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 11:55:43.511  3517  5869 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 11:55:43.596  3517  5871 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 11:55:43.618   559   559 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 11:55:44.889  5514  5878 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 11:55:44.889  5514  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 11:55:45.678  5514  5878 W !!      : call onHalfStreamCopied
,11-03 11:55:45.678  5514  5878 I testCopyDataAndClose: closing input stream
,11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 11:55:46.453  5514  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 11:55:47.491   927  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 11:55:47.574   927  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 10:55:47 GMT], X-Android-Received-Millis=[1478170547572], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478170547540]}
,11-03 11:55:47.576   927  2890 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 11:55:47.576   927  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Forcing reevaluation for UID 10012
11-03 11:55:47.577   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-03 11:55:47.577   927  2890 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 11:55:47.579   927  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-03 11:55:47.581   927  2890 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-03 11:55:47.609   927  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 10:55:47 GMT], X-Android-Received-Millis=[1478170547608], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478170547585]}
,11-03 11:55:47.610   927  2890 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 11:55:47.610   927  2890 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-03 11:55:50.411   927  2890 D ConnectivityService: handlePromptUnvalidated 102
,11-03 11:55:50.888  5514  5880 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
11-03 11:55:50.888  5514  5880 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 11:55:52.888  5514  5561 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 177. Connection data: Peer properties: [null null].
11-03 11:55:52.888  5514  5561 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 11:55:52.888  5514  5561 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 177, name: My test thread name)
,11-03 11:55:53.026  5514  5881 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 11:55:53.026  5514  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 11:55:53.084  5514  5880 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-03 11:55:53.085  5514  5880 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
11-03 11:55:53.085  5514  5880 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-03 11:55:53.485   927  2888 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-03 11:55:54.639  5514  5881 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 11:55:54.639  5514  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 11:55:54.639  5514  5881 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 11:55:54.639  5514  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 11:55:54.639  5514  5881 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 11:55:54.639  5514  5881 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 11:55:54.639  5514  5881 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-03 11:55:54.639  5514  5881 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 11:55:54.639  5514  5881 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 11:55:54.640  5514  5881 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 11:55:54.640  5514  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 11:55:59.005  5514  5882 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-03 11:55:59.005  5514  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 11:55:59.005  5514  5882 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: My test thread name). Connection data: Peer properties: [null null].
11-03 11:55:59.005  5514  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 11:55:59.006  5514  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 11:55:59.006  5514  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 11:55:59.006  5514  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 11:55:59.006  5514  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 11:55:59.006  5514  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-03 11:55:59.006  5514  5882 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 11:55:59.006  5514  5882 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 11:55:59.007  5514  5882 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-03 11:55:59.007  5514  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-03 11:55:59.008  5514  5561 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-03 11:55:59.012  5514  5883 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-03 11:55:59.012  5514  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 11:55:59.012  5514  5883 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 185, thread name: My test thread name): Test exception.
11-03 11:55:59.012  5514  5883 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-03 11:55:59.012  5514  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-03 11:55:59.013  5514  5883 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-03 11:55:59.013  5514  5883 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-03 11:55:59.013  5514  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-03 11:55:59.018  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-03 11:55:59.018  5514  5561 I jxcore-log: 
,11-03 11:55:59.018  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-03 11:55:59.018  5514  5561 I jxcore-log: 
11-03 11:55:59.019  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-03 11:55:59.019  5514  5561 I jxcore-log: 
11-03 11:55:59.019  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-03 11:55:59.019  5514  5561 I jxcore-log: 
,11-03 11:55:59.019  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG UnitTest_app: 'Total duration:  92043'
11-03 11:55:59.019  5514  5561 I jxcore-log: 
11-03 11:55:59.021  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-03 11:55:59.021  5514  5561 I jxcore-log: 
,11-03 11:55:59.024  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.024  5514  5561 I jxcore-log: 
,11-03 11:55:59.025  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.025  5514  5561 I jxcore-log: 
11-03 11:55:59.026  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.026  5514  5561 I jxcore-log: 
,11-03 11:55:59.026  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.026  5514  5561 I jxcore-log: 
,11-03 11:55:59.026  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 11:55:59.026  5514  5561 I jxcore-log: 
11-03 11:55:59.027  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-03 11:55:59.027  5514  5561 I jxcore-log: 
11-03 11:55:59.027  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 11:55:59.027  5514  5561 I jxcore-log: 
,11-03 11:55:59.027  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 11:55:59.027  5514  5561 I jxcore-log: 
11-03 11:55:59.027  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 11:55:59.027  5514  5561 I jxcore-log: 
11-03 11:55:59.028  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.028  5514  5561 I jxcore-log: 
,11-03 11:55:59.028  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.028  5514  5561 I jxcore-log: 
11-03 11:55:59.028  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 11:55:59.028  5514  5561 I jxcore-log: 
11-03 11:55:59.028  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-03 11:55:59.028  5514  5561 I jxcore-log: 
11-03 11:55:59.028  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 11:55:59.028  5514  5561 I jxcore-log: 
,11-03 11:55:59.029  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 11:55:59.029  5514  5561 I jxcore-log: 
11-03 11:55:59.029  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 11:55:59.029  5514  5561 I jxcore-log: 
11-03 11:55:59.029  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 11:55:59.029  5514  5561 I jxcore-log: 
11-03 11:55:59.029  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 11:55:59.029  5514  5561 I jxcore-log: 
,11-03 11:55:59.029  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.029  5514  5561 I jxcore-log: 
11-03 11:55:59.030  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.030  5514  5561 I jxcore-log: 
11-03 11:55:59.030  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.030  5514  5561 I jxcore-log: 
11-03 11:55:59.030  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 11:55:59.030  5514  5561 I jxcore-log: 
,11-03 11:55:59.031  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 11:55:59.031  5514  5561 I jxcore-log: 
11-03 11:55:59.031  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 11:55:59.031  5514  5561 I jxcore-log: 
11-03 11:55:59.032  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.032  5514  5561 I jxcore-log: 
11-03 11:55:59.032  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.032  5514  5561 I jxcore-log: 
11-03 11:55:59.033  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.033  5514  5561 I jxcore-log: 
,11-03 11:55:59.033  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 11:55:59.033  5514  5561 I jxcore-log: 
11-03 11:55:59.033  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 11:55:59.033  5514  5561 I jxcore-log: 
11-03 11:55:59.034  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 11:55:59.034  5514  5561 I jxcore-log: 
11-03 11:55:59.034  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.034  5514  5561 I jxcore-log: 
11-03 11:55:59.034  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.034  5514  5561 I jxcore-log: 
,11-03 11:55:59.034  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.034  5514  5561 I jxcore-log: 
11-03 11:55:59.035  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.035  5514  5561 I jxcore-log: 
11-03 11:55:59.035  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.035  5514  5561 I jxcore-log: 
11-03 11:55:59.035  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.035  5514  5561 I jxcore-log: 
11-03 11:55:59.035  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.035  5514  5561 I jxcore-log: 
,11-03 11:55:59.035  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.035  5514  5561 I jxcore-log: 
11-03 11:55:59.036  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.036  5514  5561 I jxcore-log: 
11-03 11:55:59.036  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.036  5514  5561 I jxcore-log: 
,11-03 11:55:59.036  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.036  5514  5561 I jxcore-log: 
11-03 11:55:59.036  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.036  5514  5561 I jxcore-log: 
11-03 11:55:59.037  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.037  5514  5561 I jxcore-log: 
11-03 11:55:59.037  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.037  5514  5561 I jxcore-log: 
11-03 11:55:59.037  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 11:55:59.037  5514  5561 I jxcore-log: 
,11-03 11:55:59.037  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 11:55:59.037  5514  5561 I jxcore-log: 
11-03 11:55:59.037  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 11:55:59.037  5514  5561 I jxcore-log: 
11-03 11:55:59.038  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.038  5514  5561 I jxcore-log: 
11-03 11:55:59.038  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.038  5514  5561 I jxcore-log: 
,11-03 11:55:59.038  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.038  5514  5561 I jxcore-log: 
11-03 11:55:59.038  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.038  5514  5561 I jxcore-log: 
11-03 11:55:59.039  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.039  5514  5561 I jxcore-log: 
11-03 11:55:59.039  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 11:55:59.039  5514  5561 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-03 11:55:59.039  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.039  5514  5561 I jxcore-log: 
11-03 11:55:59.039  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.039  5514  5561 I jxcore-log: 
11-03 11:55:59.039  5514  5561 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 11:55:59.039  5514  5561 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-03 11:55:59.040  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 11:55:59.040  5514  5561 I jxcore-log: 
,11-03 11:55:59.040  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 11:55:59.040  5514  5561 I jxcore-log: 
11-03 11:55:59.040  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 11:55:59.040  5514  5561 I jxcore-log: 
11-03 11:55:59.040  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 11:55:59.040  5514  5561 I jxcore-log: 
11-03 11:55:59.040  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 11:55:59.040  5514  5561 I jxcore-log: 
11-03 11:55:59.041  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 11:55:59.041  5514  5561 I jxcore-log: 
11-03 11:55:59.041  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 11:55:59.041  5514  5561 I jxcore-log: 
11-03 11:55:59.045  5514  5514 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-03 11:55:59.046  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-03 11:55:59.046  5514  5561 I jxcore-log: 
11-03 11:55:59.046  5514  5561 I jxcore-log: 2016-11-03 10:55:59 - WARN testUtils: 'myNameCallback not set!'
11-03 11:55:59.046  5514  5561 I jxcore-log: 
,11-03 11:56:01.065  5514  5561 I jxcore-log: 2016-11-03 10:56:01 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-03 11:56:01.065  5514  5561 I jxcore-log: 
,11-03 11:56:01.067  5514  5561 I jxcore-log: 2016-11-03 10:56:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-03 11:56:01.067  5514  5561 I jxcore-log: 
,11-03 11:56:01.404  5514  5561 I jxcore-log: 2016-11-03 10:56:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-03 11:56:01.404  5514  5561 I jxcore-log: 
,11-03 11:56:01.417  5514  5561 I jxcore-log: 2016-11-03 10:56:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-03 11:56:01.417  5514  5561 I jxcore-log: 
,11-03 11:56:02.527  5514  5561 I jxcore-log: 2016-11-03 10:56:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-03 11:56:02.527  5514  5561 I jxcore-log: 
,11-03 11:56:02.714  5514  5561 I jxcore-log: 2016-11-03 10:56:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-03 11:56:02.714  5514  5561 I jxcore-log: 
,11-03 11:56:02.719  5514  5561 I jxcore-log: 2016-11-03 10:56:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-03 11:56:02.719  5514  5561 I jxcore-log: 
,11-03 11:56:02.724  5514  5561 I jxcore-log: 2016-11-03 10:56:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-03 11:56:02.724  5514  5561 I jxcore-log: 
,11-03 11:56:03.206  5514  5561 I jxcore-log: 2016-11-03 10:56:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-03 11:56:03.206  5514  5561 I jxcore-log: 
,11-03 11:56:03.250  5514  5561 I jxcore-log: 2016-11-03 10:56:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-03 11:56:03.250  5514  5561 I jxcore-log: 
,11-03 11:56:03.263  5514  5561 I jxcore-log: 2016-11-03 10:56:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-03 11:56:03.263  5514  5561 I jxcore-log: 
,11-03 11:56:03.267  5514  5561 I jxcore-log: 2016-11-03 10:56:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-03 11:56:03.267  5514  5561 I jxcore-log: 
,11-03 11:56:03.553  5514  5561 I jxcore-log: 2016-11-03 10:56:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-03 11:56:03.553  5514  5561 I jxcore-log: 
,11-03 11:56:03.618   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:56:03.678  5514  5561 I jxcore-log: 2016-11-03 10:56:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-03 11:56:03.678  5514  5561 I jxcore-log: 
,11-03 11:56:04.050  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-03 11:56:04.050  5514  5561 I jxcore-log: 
,11-03 11:56:04.059  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-03 11:56:04.059  5514  5561 I jxcore-log: 
,11-03 11:56:04.063  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-03 11:56:04.063  5514  5561 I jxcore-log: 
,11-03 11:56:04.069  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-03 11:56:04.069  5514  5561 I jxcore-log: 
,11-03 11:56:04.074  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-03 11:56:04.074  5514  5561 I jxcore-log: 
,11-03 11:56:04.103  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-03 11:56:04.103  5514  5561 I jxcore-log: 
,11-03 11:56:04.141  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-03 11:56:04.141  5514  5561 I jxcore-log: 
,11-03 11:56:04.148  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-03 11:56:04.148  5514  5561 I jxcore-log: 
,11-03 11:56:04.155  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-03 11:56:04.155  5514  5561 I jxcore-log: 
,11-03 11:56:04.170  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-03 11:56:04.170  5514  5561 I jxcore-log: 
,11-03 11:56:04.174  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-03 11:56:04.174  5514  5561 I jxcore-log: 
,11-03 11:56:04.180  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-03 11:56:04.180  5514  5561 I jxcore-log: 
,11-03 11:56:04.185  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-03 11:56:04.185  5514  5561 I jxcore-log: 
,11-03 11:56:04.198  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-03 11:56:04.198  5514  5561 I jxcore-log: 
,11-03 11:56:04.204  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-03 11:56:04.204  5514  5561 I jxcore-log: 
,11-03 11:56:04.226  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-03 11:56:04.226  5514  5561 I jxcore-log: 
,11-03 11:56:04.237  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-03 11:56:04.237  5514  5561 I jxcore-log: 
,11-03 11:56:04.260  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-03 11:56:04.260  5514  5561 I jxcore-log: 
,11-03 11:56:04.270  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-03 11:56:04.270  5514  5561 I jxcore-log: 
,11-03 11:56:04.284  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-03 11:56:04.284  5514  5561 I jxcore-log: 
,11-03 11:56:04.294  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-03 11:56:04.294  5514  5561 I jxcore-log: 
,11-03 11:56:04.301  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-03 11:56:04.301  5514  5561 I jxcore-log: 
,11-03 11:56:04.323  5514  5561 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-03 11:56:04.324  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - INFO testUtils: 'BLE multiple advertisement supported'
11-03 11:56:04.324  5514  5561 I jxcore-log: 
,11-03 11:56:04.512  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:04.512  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:04.512  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:04.512  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:04.512  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:04.512  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:04.512  5514  5561 I jxcore-log: 
,11-03 11:56:04.619   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:56:04.672  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:04.672  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:04.672  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:04.672  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:04.672  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:04.672  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:04.672  5514  5561 I jxcore-log: 
,11-03 11:56:04.677  5514  5561 I jxcore-log: 2016-11-03 10:56:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:04.677  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:04.677  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:04.677  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:04.677  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:04.677  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:04.677  5514  5561 I jxcore-log: 
,11-03 11:56:05.187  5514  5561 I jxcore-log: 2016-11-03 10:56:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:05.187  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:05.187  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:05.187  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:05.187  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:05.187  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:05.187  5514  5561 I jxcore-log: 
,11-03 11:56:05.193  5514  5561 I jxcore-log: 2016-11-03 10:56:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:05.193  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:05.193  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:05.193  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:05.193  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:05.193  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:05.193  5514  5561 I jxcore-log: 
,11-03 11:56:05.620   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:56:06.033  5514  5561 I jxcore-log: 2016-11-03 10:56:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:06.033  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:06.033  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:06.033  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:06.033  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:06.033  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:06.033  5514  5561 I jxcore-log: 
,11-03 11:56:06.040  5514  5561 I jxcore-log: 2016-11-03 10:56:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:06.040  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:06.040  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:06.040  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:06.040  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:06.040  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:06.040  5514  5561 I jxcore-log: 
,11-03 11:56:06.622   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:56:07.071  5514  5561 I jxcore-log: 2016-11-03 10:56:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:07.071  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:07.071  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:07.071  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:07.071  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:07.071  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:07.071  5514  5561 I jxcore-log: 
,11-03 11:56:07.075  5514  5561 I jxcore-log: 2016-11-03 10:56:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:07.075  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:07.075  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:07.075  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:07.075  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:07.075  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:07.075  5514  5561 I jxcore-log: 
,11-03 11:56:07.623   559   559 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 11:56:08.129  5514  5561 I jxcore-log: 2016-11-03 10:56:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:08.129  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:08.129  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:08.129  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:08.129  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:08.129  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:08.129  5514  5561 I jxcore-log: 
,11-03 11:56:08.134  5514  5561 I jxcore-log: 2016-11-03 10:56:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:08.134  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:08.134  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:08.134  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:08.134  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:08.134  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:08.134  5514  5561 I jxcore-log: 
,11-03 11:56:08.623   559   559 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 11:56:09.174  5514  5561 I jxcore-log: 2016-11-03 10:56:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:09.174  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:09.174  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:09.174  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:09.174  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:09.174  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:09.174  5514  5561 I jxcore-log: 
,11-03 11:56:09.180  5514  5561 I jxcore-log: 2016-11-03 10:56:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:09.180  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:09.180  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:09.180  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:09.180  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:09.180  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:09.180  5514  5561 I jxcore-log: 
,11-03 11:56:10.214  5514  5561 I jxcore-log: 2016-11-03 10:56:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:10.214  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:10.214  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:10.214  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:10.214  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:10.214  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:10.214  5514  5561 I jxcore-log: 
,11-03 11:56:10.220  5514  5561 I jxcore-log: 2016-11-03 10:56:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:10.220  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:10.220  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:10.220  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:10.220  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:10.220  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:10.220  5514  5561 I jxcore-log: 
,11-03 11:56:11.252  5514  5561 I jxcore-log: 2016-11-03 10:56:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:11.252  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:11.252  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:11.252  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:11.252  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:11.252  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:11.252  5514  5561 I jxcore-log: 
,11-03 11:56:11.258  5514  5561 I jxcore-log: 2016-11-03 10:56:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:11.258  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:11.258  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:11.258  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:11.258  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:11.258  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:11.258  5514  5561 I jxcore-log: 
,11-03 11:56:12.298  5514  5561 I jxcore-log: 2016-11-03 10:56:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:12.298  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:12.298  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:12.298  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:12.298  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:12.298  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:12.298  5514  5561 I jxcore-log: 
,11-03 11:56:12.304  5514  5561 I jxcore-log: 2016-11-03 10:56:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:12.304  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:12.304  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:12.304  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:12.304  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:12.304  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:12.304  5514  5561 I jxcore-log: 
,11-03 11:56:13.375  5514  5561 I jxcore-log: 2016-11-03 10:56:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:13.375  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:13.375  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:13.375  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:13.375  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:13.375  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:13.375  5514  5561 I jxcore-log: 
,11-03 11:56:13.380  5514  5561 I jxcore-log: 2016-11-03 10:56:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:13.380  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:13.380  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:13.380  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:13.380  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:13.380  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:13.380  5514  5561 I jxcore-log: 
,11-03 11:56:14.419  5514  5561 I jxcore-log: 2016-11-03 10:56:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:14.419  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:14.419  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:14.419  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:14.419  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:14.419  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:14.419  5514  5561 I jxcore-log: 
,11-03 11:56:14.425  5514  5561 I jxcore-log: 2016-11-03 10:56:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:14.425  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:14.425  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:14.425  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:14.425  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:14.425  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:14.425  5514  5561 I jxcore-log: 
,11-03 11:56:15.472  5514  5561 I jxcore-log: 2016-11-03 10:56:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:15.472  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:15.472  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:15.472  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:15.472  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:15.472  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:15.472  5514  5561 I jxcore-log: 
,11-03 11:56:15.479  5514  5561 I jxcore-log: 2016-11-03 10:56:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:15.479  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:15.479  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:15.479  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:15.479  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:15.479  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:15.479  5514  5561 I jxcore-log: 
,11-03 11:56:16.507  5514  5561 I jxcore-log: 2016-11-03 10:56:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:16.507  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:16.507  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:16.507  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:16.507  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:16.507  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:16.507  5514  5561 I jxcore-log: 
,11-03 11:56:16.512  5514  5561 I jxcore-log: 2016-11-03 10:56:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:16.512  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:16.512  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:16.512  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:16.512  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:16.512  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:16.512  5514  5561 I jxcore-log: 
,11-03 11:56:17.544  5514  5561 I jxcore-log: 2016-11-03 10:56:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:17.544  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:17.544  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:17.544  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:17.544  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:17.544  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:17.544  5514  5561 I jxcore-log: 
,11-03 11:56:17.548  5514  5561 I jxcore-log: 2016-11-03 10:56:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:17.548  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:17.548  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:17.548  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:17.548  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:17.548  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:17.548  5514  5561 I jxcore-log: 
,11-03 11:56:18.587  5514  5561 I jxcore-log: 2016-11-03 10:56:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 11:56:18.587  5514  5561 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 11:56:18.587  5514  5561 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 11:56:18.587  5514  5561 I jxcore-log: emit@events.js:82:1
11-03 11:56:18.587  5514  5561 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 11:56:18.587  5514  5561 I jxcore-log: emit@events.js:82:1'
11-03 11:56:18.587  5514  5561 I jxcore-log: 
,11-03 11:56:18.598  5514  5561 E jxcore  : Error!: error is undefined
11-03 11:56:18.598  5514  5561 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-03 11:56:18.601  5514  5561 I jxcore-log: 2016-11-03 10:56:18 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-03 11:56:18.601  5514  5561 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-03 11:56:18.601  5514  5561 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-03 11:56:18.601  5514  5561 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-03 11:56:18.601  5514  5561 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-03 11:56:18.601  5514  5561 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-03 11:56:18.601  5514  5561 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-03 11:56:18.601  5514  5561 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-03 11:56:18.604  5514  5561 I jxcore-log: 2016-11-03 10:56:18 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-03 11:56:18.604  5514  5561 I jxcore-log: 
,11-03 11:56:18.605  5514  5561 E jxcore-log: TypeError: 
11-03 11:56:18.605  5514  5561 E jxcore-log: error is undefined
11-03 11:56:18.606  5514  5561 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-03 11:56:18.606  5514  5561 E jxcore-log: 
,11-03 11:56:18.700   927  3533 I WindowState: WIN DEATH: Window{1716726 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-03 11:56:18.699   927  3674 D GraphicsStats: Buffer count: 2
,11-03 11:56:18.701   927  2889 D WifiService: Client connection lost with reason: 4
,11-03 11:56:18.718   527   527 I Zygote  : Process 5514 exited cleanly (139)
,11-03 11:56:18.721   927   937 I ActivityManager: Process com.test.thalitest (pid 5514) has died
,11-03 11:56:18.722   927   937 W ActivityManager: Force removing ActivityRecord{5cd8f8f u0 com.test.thalitest/.MainActivity t68}: app died, no saved state
,11-03 11:56:18.767  3656  3656 W Binder_7: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[29026]" dev="sockfs" ino=29026 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 11:56:18.767  3656  3656 W Binder_7: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[29026]" dev="sockfs" ino=29026 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 11:56:18.772   927  3656 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5514 uid 10077
11-03 11:56:18.773  3579  3579 I Keyboard.Facilitator: onFinishInput()
,11-03 11:56:18.828  3872  5890 I MicroRecognitionRnrImpl: Starting detection.
,11-03 11:56:18.829  3872  5891 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@e961a74
,11-03 11:56:18.831   512  5893 I AudioFlinger: AudioFlinger's thread 0xf2240000 ready to run
,11-03 11:56:18.836   512  2933 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-03 11:56:18.837  3872  5891 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@e961a74
,11-03 11:56:18.848   512  5893 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-03 11:56:18.848   512  5893 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-03 11:56:18.848   512  5893 I ACDB-LOADER: ACDB AFE returned = -19
11-03 11:56:18.848   512  5893 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-03 11:56:18.848   512  5893 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-03 11:56:18.848   512  5893 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-03 11:56:18.856   512  5893 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-03 11:56:18.930  3872  3872 I HotwordWorkerImpl: onReady
,11-03 11:56:19.036  5885  5885 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-03 11:56:19.050  5885  5885 D AndroidRuntime: CheckJNI is OFF
,11-03 11:56:19.073  5885  5885 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-03 11:56:19.100  5885  5885 I Radio-JNI: register_android_hardware_Radio DONE
,11-03 11:56:19.115  5885  5885 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-03 11:56:19.124   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-03 11:56:19.272   927   950 I art     : Starting a blocking GC Explicit
,11-03 11:56:19.304  3725  3957 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-03 11:56:19.367   927   950 I art     : Explicit concurrent mark sweep GC freed 66352(4MB) AllocSpace objects, 15(468KB) LOS objects, 33% free, 28MB/43MB, paused 1.624ms total 95.229ms
,11-03 11:56:19.389   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-03 11:56:19.392  5885  5885 I art     : System.exit called, status: 0
,11-03 11:56:19.392  5885  5885 I AndroidRuntime: VM exiting with result code 0.
,11-03 11:56:19.397   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-03 11:56:19.404  5785  5785 D BluetoothMapAppObserver: onReceive
,11-03 11:56:19.404  5785  5785 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-03 11:56:19.413  3579  3579 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-03 11:56:19.415   927  2877 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-03 11:56:19.421  3888  4054 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-03 11:56:19.425  3579  5905 I Keyboard.Facilitator.DecoderInitializer: run()
,11-03 11:56:19.429  3579  5905 I Decoder : createOrResetDecoder
,11-03 11:56:19.432  3338  5906 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-03 11:56:19.480  3685  3685 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-03 11:56:19.484   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-03 11:56:19.487  5571  5571 W kworker/3:3: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 11:56:19.494  5571  5571 W kworker/3:3: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 11:56:19.500  3517  3517 I ConfigService: onCreate
,11-03 11:56:19.503  3725  3805 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-03 11:56:19.507  5571  5571 W kworker/3:3: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 11:56:19.517   927  3093 I ActivityManager: Start proc 5911:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-03 11:56:19.518  3725  3805 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-03 11:56:19.518  3725  3805 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3725
11-03 11:56:19.518  3725  3805 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:56:19.518  3725  3805 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-03 11:56:19.523   927  5918 E DropBoxManagerService: Can't write: system_app_crash
11-03 11:56:19.523   927  5918 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 11:56:19.523   927  5918 E DropBoxManagerService: 	... 5 more
11-03 11:56:19.523   927  3533 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-03 11:56:19.525  3517  3517 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-03 11:56:19.526  3517  3517 D AndroidRuntime: Shutting down VM
11-03 11:56:19.527  3872  3887 W SearchService: Abort, client detached.
11-03 11:56:19.527  3517  3517 E AndroidRuntime: FATAL EXCEPTION: main
11-03 11:56:19.527  3517  3517 E AndroidRuntime: Process: com.google.process.gapps, PID: 3517
11-03 11:56:19.527  3517  3517 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-03 11:56:19.527  3517  3517 E AndroidRuntime: 	... 8 more
,11-03 11:56:19.529  3872  3872 I HotwordDetector: Closing mic
,11-03 11:56:19.529  3872  4115 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e961a74
,11-03 11:56:19.532  3579  5905 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-03 11:56:19.537  3338  5906 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-03 11:56:19.538  3338  5906 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-03 11:56:19.538  3338  5906 E AndroidRuntime: Process: android.process.acore, PID: 3338
11-03 11:56:19.538  3338  5906 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 11:56:19.538  3338  5906 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-03 11:56:19.551   752   752 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[28408]" dev="sockfs" ino=28408 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 11:56:19.551   752   752 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[28408]" dev="sockfs" ino=28408 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 11:56:19.556   927  5925 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 11:56:19.551   405   405 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[32523]" dev="sockfs" ino=32523 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 11:56:19.551   405   405 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32523]" dev="sockfs" ino=32523 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 11:56:19.571   927  5926 E DropBoxManagerService: Can't write: system_app_crash
11-03 11:56:19.571   927  5926 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 11:56:19.571   927  5926 E DropBoxManagerService: 	... 5 more
,11-03 11:56:19.578   927  5927 E DropBoxManagerService: Can't write: system_app_crash
11-03 11:56:19.578   927  5927 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 11:56:19.578   927  5927 E DropBoxManagerService: 	... 5 more
,11-03 11:56:19.596   381   481 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Cannot send after transport endpoint shutdown
11-03 11:56:19.596   381   481 E SurfaceFlinger: eventControl(0, 1) failed Cannot send after transport endpoint shutdown
11-03 11:56:19.598   927  5925 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 11:56:19.598   927  5925 I Adreno  : Build Date                       : 12/06/15
11-03 11:56:19.598   927  5925 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 11:56:19.598   927  5925 I Adreno  : Local Branch                     : mybranch17112971
11-03 11:56:19.598   927  5925 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 11:56:19.598   927  5925 I Adreno  : Remote Branch                    : NONE
11-03 11:56:19.598   927  5925 I Adreno  : Reconstruct Branch               : NOTHING
11-03 11:56:19.608   512  5893 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-03 11:56:19.612   927  4880 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-03 11:56:19.614   512  5893 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-03 11:56:19.625   512  5893 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-03 11:56:19.625   512  5893 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-03 11:56:19.627   512  2933 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-03 11:56:19.630  3872  5890 I MicroRecognitionRnrImpl: Detection finished
,11-03 11:56:19.632  3872  4117 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-03 11:56:19.922   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
