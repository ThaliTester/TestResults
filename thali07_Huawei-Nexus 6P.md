#### Test 912434548f3f6c6_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-01 12:07:45.195  3999  4254 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-01 12:07:45.272  3999  4254 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-01 12:07:45.627  5591  5591 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-01 12:07:45.633  5591  5591 D AndroidRuntime: CheckJNI is OFF
11-01 12:07:45.666  5591  5591 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-01 12:07:45.705  5591  5591 I Radio-JNI: register_android_hardware_Radio DONE
11-01 12:07:45.720  5591  5591 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-01 12:07:45.723   926  3838 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-01 12:07:45.741  5591  5591 D AndroidRuntime: Shutting down VM
11-01 12:07:45.741  3972  3986 W SearchService: Abort, client detached.
11-01 12:07:45.748  3972  3972 I HotwordDetector: Closing mic
11-01 12:07:45.748  3972  4242 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@82d0ff
11-01 12:07:45.749  3972  4251 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-01 12:07:45.782   926  3858 I ActivityManager: Start proc 5600:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-01 12:07:45.828   514  4253 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-01 12:07:45.830   514  4253 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-01 12:07:45.836   514  4253 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-01 12:07:45.836   514  4253 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-01 12:07:45.838   514  3014 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-01 12:07:45.841  3972  4250 I MicroRecognitionRnrImpl: Detection finished
11-01 12:07:45.841  3972  4244 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-01 12:07:45.888  5600  5600 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-01 12:07:45.909  5600  5600 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-01 12:07:45.971  5600  5600 I LibraryLoader: Time to load native libraries: 59 ms (timestamps 9925-9984)
,11-01 12:07:45.971  5600  5600 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-01 12:07:46.004  5600  5600 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5db8fdd}
,11-01 12:07:46.005  5600  5600 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-01 12:07:46.005  5600  5600 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-01 12:07:46.011  5600  5600 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-01 12:07:46.012  5600  5600 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-01 12:07:46.064  5600  5600 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-01 12:07:46.077  5600  5600 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-01 12:07:46.077  5600  5600 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-01 12:07:46.077  5600  5600 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-01 12:07:46.077  5600  5600 I Adreno  : Build Date                       : 12/06/15
11-01 12:07:46.077  5600  5600 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-01 12:07:46.077  5600  5600 I Adreno  : Local Branch                     : mybranch17112971
11-01 12:07:46.077  5600  5600 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-01 12:07:46.077  5600  5600 I Adreno  : Remote Branch                    : NONE
11-01 12:07:46.077  5600  5600 I Adreno  : Reconstruct Branch               : NOTHING
,11-01 12:07:46.116   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@87ed1fe:true
,11-01 12:07:46.138   404   404 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[21094]" dev="sockfs" ino=21094 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-01 12:07:46.138   404   404 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21094]" dev="sockfs" ino=21094 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-01 12:07:46.151  5600  5600 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-01 12:07:46.160  5600  5600 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-01 12:07:46.184  5600  5637 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-01 12:07:46.181   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32262]" dev="sockfs" ino=32262 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-01 12:07:46.181   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32262]" dev="sockfs" ino=32262 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-01 12:07:46.184  3172  3172 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31016]" dev="sockfs" ino=31016 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-01 12:07:46.184  3172  3172 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31016]" dev="sockfs" ino=31016 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-01 12:07:46.190  5600  5624 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-01 12:07:46.213  5600  5637 I OpenGLRenderer: Initialized EGL, version 1.4
,11-01 12:07:46.291  3803  3803 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32266]" dev="sockfs" ino=32266 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-01 12:07:46.291  3803  3803 W Binder_9: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32266]" dev="sockfs" ino=32266 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-01 12:07:46.294  3838  3838 W Binder_C: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32265]" dev="sockfs" ino=32265 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-01 12:07:46.294  3838  3838 W Binder_C: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32265]" dev="sockfs" ino=32265 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-01 12:07:46.296   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +542ms
11-01 12:07:46.300  3655  3655 I Keyboard.Facilitator: onFinishInput()
,11-01 12:07:46.350  5600  5600 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5600
,11-01 12:07:46.437  5600  5600 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-01 12:07:46.641  5600  5639 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -594806480
,11-01 12:07:46.646  5600  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-01 12:07:46.646  5600  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-01 12:07:46.646  5600  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-01 12:07:46.646  5600  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-01 12:07:46.646  5600  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-01 12:07:46.647  5600  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dee2f8 added. We now have 1 listener(s)
,11-01 12:07:46.650  5600  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-01 12:07:46.651  5600  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:07:46.651  5600  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:07:46.652  5600  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-01 12:07:46.654  5600  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f60c137 added. We now have 1 listener(s)
11-01 12:07:46.654  5600  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-01 12:07:46.660   926  2993 D WifiService: New client listening to asynchronous messages
,11-01 12:07:46.661  5600  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-01 12:07:46.661  5600  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-01 12:07:46.661  5600  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-01 12:07:46.661  5600  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-01 12:07:46.661  5600  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-01 12:07:46.662  5600  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-01 12:07:46.662  5600  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-01 12:07:46.663  5600  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:07:46.664  5600  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-01 12:07:46.669  5600  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-01 12:07:46.669  5600  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:07:46.669  5600  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:07:46.669  5600  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:07:46.669  5600  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:07:46.669  5600  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:07:46.669  5600  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:07:46.669  5600  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:07:46.669  5600  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:07:46.669  5600  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-01 12:07:46.670  5600  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:07:46.670  5600  5639 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-01 12:07:46.794  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:07:46.799  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:07:46.803  5600  5600 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-01 12:07:47.165  5600  5609 I art     : Background sticky concurrent mark sweep GC freed 82424(8MB) AllocSpace objects, 17(1096KB) LOS objects, 22% free, 25MB/32MB, paused 4.896ms total 294.816ms
,11-01 12:07:47.896   926  2992 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-01 12:07:48.289  5600  5609 I art     : Background partial concurrent mark sweep GC freed 48056(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.346ms total 160.920ms
,11-01 12:07:48.845  5600  5649 W jxcore-log: Initializing JXcore engine
11-01 12:07:48.845  5600  5649 W jxcore-log: JXcore engine is ready
,11-01 12:07:48.868  5649  5649 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11580 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-01 12:07:48.868  5649  5649 W Thread-58: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[11914]" dev="sockfs" ino=11914 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-01 12:07:48.868  5649  5649 W Thread-58: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-01 12:07:48.868  5649  5649 W Thread-58: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32915]" dev="sockfs" ino=32915 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-01 12:07:48.877  5600  5649 W jxcore-log: Starting JXcore engine
,11-01 12:07:48.927  5600  5649 W jxcore-log: Platform android
11-01 12:07:48.927  5600  5649 W jxcore-log: 
,11-01 12:07:48.927  5600  5649 W jxcore-log: Process ARCH arm
11-01 12:07:48.927  5600  5649 W jxcore-log: 
,11-01 12:07:49.109  5600  5649 I jxcore-log: JXcore Cordova bridge is ready!
11-01 12:07:49.109  5600  5649 I jxcore-log: 
11-01 12:07:49.109  5600  5649 W jxcore-log: JXcore engine is started
,11-01 12:07:49.122  5600  5639 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-01 12:07:49.125  5600  5600 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-01 12:07:49.328  3598  3598 I ConfigService: onDestroy
,11-01 12:07:50.427   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:07:50.754   926  3177 I ActivityManager: Killing 5240:org.codeaurora.ims/1001 (adj 15): empty #17
,11-01 12:07:50.792   926  3177 I ActivityManager: Killing 5152:com.google.android.youtube/u0a75 (adj 15): empty #18
,11-01 12:07:51.428   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:07:52.430   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:07:53.431   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:07:54.432   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:07:55.433   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-01 12:07:58.753  5600  5649 I jxcore-log: 2016-11-01 11:07:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-01 12:07:58.753  5600  5649 I jxcore-log: 
,11-01 12:07:58.755  5600  5649 I jxcore-log: 2016-11-01 11:07:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-01 12:07:58.755  5600  5649 I jxcore-log: 
,11-01 12:07:58.759  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:07:58.759  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:07:58.759  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:07:58.759  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:07:58.759  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:07:58.759  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:07:58.759  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:07:58.759  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:07:58.761  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-01 12:07:58.763  5600  5649 I jxcore-log: 2016-11-01 11:07:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-01 12:07:58.763  5600  5649 I jxcore-log: 
,11-01 12:07:58.764  5600  5649 I jxcore-log: 2016-11-01 11:07:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-01 12:07:58.764  5600  5649 I jxcore-log: 
,11-01 12:07:58.960  3972  5651 W CronetSyncConnectionRcs: Upload content type not set.
,11-01 12:07:58.999  5600  5649 I jxcore-log: 2016-11-01 11:07:58 - DEBUG UnitTest_app: 'Running unit tests'
11-01 12:07:58.999  5600  5649 I jxcore-log: 
,11-01 12:07:58.999  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:07:58.999  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86963f2 added. We now have 2 listener(s)
,11-01 12:07:59.000  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:07:59.000  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:07:59.000  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:07:59.000  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-01 12:07:59.000  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f7a43 added. We now have 2 listener(s)
,11-01 12:07:59.000  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:07:59.000  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-01 12:07:59.001  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:07:59.005  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:07:59.005  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:07:59.005  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:07:59.005  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:07:59.005  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:07:59.005  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:07:59.005  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:07:59.005  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:07:59.006  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:07:59.007  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:07:59.007  5600  5649 D executeNativeTests: Running unit tests
,11-01 12:07:59.010  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:07:59.012  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:07:59.038  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:07:59.038  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 added. We now have 3 listener(s)
,11-01 12:07:59.038  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:07:59.038  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:07:59.039  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:07:59.039  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:07:59.039  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee added. We now have 3 listener(s)
11-01 12:07:59.039  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:07:59.039  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-01 12:07:59.042  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:07:59.045  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:07:59.045  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:07:59.045  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:07:59.045  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:07:59.045  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:07:59.045  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:07:59.045  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:07:59.045  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:07:59.046  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:07:59.046  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:07:59.048  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-01 12:07:59.048  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-01 12:07:59.048  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-01 12:07:59.048  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:07:59.048  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-01 12:07:59.049  5600  5649 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-01 12:07:59.049  5600  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-01 12:07:59.049  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-01 12:07:59.049  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-01 12:07:59.049  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-01 12:07:59.049  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-01 12:07:59.049  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:07:59.049  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:07:59.049  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:07:59.049  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:07:59.050  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:07:59.050  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:07:59.050  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-01 12:07:59.050  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:07:59.050  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 removed from the list
11-01 12:07:59.050  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:07:59.050  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee removed from the list
11-01 12:07:59.050  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:07:59.051  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:07:59.051  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:07:59.051  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:07:59.051  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:07:59.051  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:07:59.052  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.052  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.052  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.052  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:07:59.052  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:07:59.052  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:07:59.052  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:07:59.053  5600  5649 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-01 12:07:59.053  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:07:59.053  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:07:59.053  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:07:59.053  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:07:59.053  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:07:59.053  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:07:59.053  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:07:59.053  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
,11-01 12:07:59.053  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:07:59.053  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:07:59.053  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:07:59.053  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:07:59.053  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:07:59.053  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:07:59.053  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:07:59.054  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.054  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.054  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.054  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.054  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:07:59.054  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:07:59.054  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:07:59.054  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-01 12:07:59.057  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-01 12:07:59.058  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:07:59.058  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:07:59.058  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:07:59.058  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:07:59.058  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:07:59.058  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:07:59.058  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:07:59.058  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:07:59.058  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:07:59.058  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:07:59.058  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:07:59.058  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:07:59.058  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:07:59.058  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:07:59.058  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:07:59.058  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.059  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.059  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.059  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.059  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:07:59.059  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:07:59.059  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:07:59.059  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:07:59.059  5600  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-01 12:07:59.060  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:07:59.062  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:07:59.062  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:07:59.062  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:07:59.062  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:07:59.062  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:07:59.062  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:07:59.062  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:07:59.062  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:07:59.064  4834  4904 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
11-01 12:07:59.065  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:07:59.065  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:07:59.065  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:07:59.065  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-01 12:07:59.065  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-01 12:07:59.065  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:07:59.065  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-01 12:07:59.065  4834  4834 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
11-01 12:07:59.067  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:07:59.070  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:07:59.071  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-01 12:07:59.071  5600  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-01 12:07:59.071  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-01 12:07:59.075  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.075  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-01 12:07:59.076  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-01 12:07:59.076  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-01 12:07:59.077  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-01 12:07:59.078  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-01 12:07:59.078  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.078  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-01 12:07:59.078  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-01 12:07:59.078  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-01 12:07:59.078  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-01 12:07:59.078  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.079  5600  5649 D BluetoothAdapter: STATE_ON
11-01 12:07:59.081  4633  4646 D BtGatt.GattService: registerClient() - UUID=fb82b473-d769-4b87-84fd-938e5e95b586
11-01 12:07:59.081  4633  4722 D BtGatt.GattService: onClientRegistered() - UUID=fb82b473-d769-4b87-84fd-938e5e95b586, clientIf=5
11-01 12:07:59.082  5600  5611 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-01 12:07:59.082  4633  4723 D BtGatt.GattService: start scan with filters
11-01 12:07:59.086  4633  4726 D BtGatt.ScanManager: handling starting scan
11-01 12:07:59.087  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-01 12:07:59.087  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.087  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-01 12:07:59.087  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.087  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-01 12:07:59.087  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-01 12:07:59.087  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:07:59.087  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-01 12:07:59.087  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-01 12:07:59.087  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:07:59.087  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-01 12:07:59.088  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-01 12:07:59.088  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-01 12:07:59.088  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.088  4633  4726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
11-01 12:07:59.088  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.089  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:07:59.089  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.089  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:07:59.089  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:07:59.089  5600  5649 I io.jxcore.node.ConnectionHelper: start: OK
11-01 12:07:59.091  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:07:59.091  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:07:59.091  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:07:59.092  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:07:59.092  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:07:59.095  4633  4722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-01 12:07:59.095  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:07:59.095  4633  4726 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-01 12:07:59.100  4633  4722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-01 12:07:59.100  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:07:59.101  4633  4726 D BtGatt.ScanManager: Starting BLE batch scan
11-01 12:07:59.101  4633  4726 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-01 12:07:59.109  4633  4722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-01 12:07:59.109  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:07:59.115  4633  4722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-01 12:07:59.115  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-01 12:07:59.593  5600  5600 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-01 12:07:59.594  5600  5600 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-01 12:07:59.594  5600  5600 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-01 12:08:04.093  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:04.094  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-01 12:08:04.094  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-01 12:08:04.094  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:04.094  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-01 12:08:04.094  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:04.094  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-01 12:08:04.094  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-01 12:08:04.094  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-01 12:08:04.094  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-01 12:08:04.095  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.095  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:04.096  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.096  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-01 12:08:04.096  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.097  5600  5649 D BluetoothAdapter: STATE_ON
11-01 12:08:04.098  4633  4881 D BtGatt.GattService: stopScan() - queue size =1
11-01 12:08:04.099  4633  4648 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-01 12:08:04.100  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-01 12:08:04.101  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.101  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-01 12:08:04.101  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.101  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.102  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.102  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:04.102  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-01 12:08:04.103  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:04.103  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.103  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.103  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-01 12:08:04.104  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-01 12:08:04.105  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:08:04.106  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:04.108  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.109  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:08:04.109  4633  4633 D BtGatt.ScanManager: awakened up at time 98122
11-01 12:08:04.109  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:04.109  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:04.110  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:04.110  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:08:04.110  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:04.110  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:08:04.110  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:04.111  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:04.111  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:04.111  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
,11-01 12:08:04.111  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:04.111  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:08:04.111  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:04.111  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-01 12:08:04.111  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:08:04.112  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-01 12:08:04.112  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-01 12:08:04.112  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:08:04.112  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-01 12:08:04.112  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,11-01 12:08:04.113  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:08:04.117  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:08:04.117  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:08:04.117  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:08:04.118  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:08:04.118  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:08:04.122  4633  4722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-01 12:08:04.122  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:04.122  4633  4726 D BtGatt.ScanManager: stopping BLe Batch
,11-01 12:08:04.132  4633  4722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-01 12:08:04.132  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:04.132  4633  4726 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-01 12:08:04.155  4633  4722 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-01 12:08:04.155  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:04.155  4633  4722 D BtGatt.GattService: current time is 98168538898
11-01 12:08:04.156  4633  4722 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -85, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -75, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -81, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -77, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-01 12:08:04.159  4633  4722 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-01 12:08:04.160  4633  4722 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-01 12:08:04.160  4633  4722 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-01 12:08:04.160  4633  4722 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-01 12:08:04.161  4633  4722 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-01 12:08:04.619  5600  5600 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-01 12:08:09.121  5600  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-01 12:08:09.127  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:08:09.138  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:08:09.138  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:09.138  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:09.138  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:09.138  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:08:09.138  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:09.138  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:08:09.138  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:08:09.144  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-01 12:08:09.145  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:08:09.145  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-01 12:08:09.145  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-01 12:08:09.145  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-01 12:08:09.145  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:08:09.145  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-01 12:08:09.153  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:09.155  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-01 12:08:09.155  5600  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-01 12:08:09.155  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-01 12:08:09.164  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.164  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-01 12:08:09.164  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:09.165  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-01 12:08:09.166  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-01 12:08:09.172  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.172  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-01 12:08:09.172  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-01 12:08:09.172  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-01 12:08:09.173  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-01 12:08:09.173  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:09.174  5600  5649 D BluetoothAdapter: STATE_ON
,11-01 12:08:09.178  4633  4723 D BtGatt.GattService: registerClient() - UUID=f854f3c8-105c-435a-ab5f-c5b8546a5583
,11-01 12:08:09.179  4633  4722 D BtGatt.GattService: onClientRegistered() - UUID=f854f3c8-105c-435a-ab5f-c5b8546a5583, clientIf=5
11-01 12:08:09.180  5600  5610 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-01 12:08:09.181  4633  4881 D BtGatt.GattService: start scan with filters
,11-01 12:08:09.185  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-01 12:08:09.186  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.186  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-01 12:08:09.186  4633  4726 D BtGatt.ScanManager: handling starting scan
11-01 12:08:09.186  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.186  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-01 12:08:09.186  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-01 12:08:09.186  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.186  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-01 12:08:09.187  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-01 12:08:09.187  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.187  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-01 12:08:09.187  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-01 12:08:09.188  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-01 12:08:09.188  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.192  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:09.192  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:08:09.192  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.192  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.193  5600  5649 I io.jxcore.node.ConnectionHelper: start: OK
11-01 12:08:09.193  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.196  4633  4722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-01 12:08:09.196  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:09.196  4633  4726 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-01 12:08:09.196  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:09.196  5600  5649 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-01 12:08:09.197  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:09.197  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-01 12:08:09.197  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:09.197  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-01 12:08:09.197  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:09.197  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-01 12:08:09.202  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-01 12:08:09.202  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.203  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.203  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.203  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:08:09.203  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-01 12:08:09.203  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-01 12:08:09.203  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-01 12:08:09.204  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:09.204  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.204  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:09.204  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-01 12:08:09.204  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.205  5600  5649 D BluetoothAdapter: STATE_ON
11-01 12:08:09.205  4633  4722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-01 12:08:09.205  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:09.206  4633  4726 D BtGatt.ScanManager: Starting BLE batch scan
11-01 12:08:09.206  4633  4726 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-01 12:08:09.206  4633  4646 D BtGatt.GattService: stopScan() - queue size =1
11-01 12:08:09.207  4633  4723 D BtGatt.GattService: unregisterClient() - clientIf=5
11-01 12:08:09.207  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-01 12:08:09.208  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.208  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-01 12:08:09.208  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.208  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.208  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.208  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.208  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-01 12:08:09.208  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.209  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.209  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.209  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-01 12:08:09.209  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-01 12:08:09.210  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:08:09.210  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:09.213  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:09.214  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:08:09.214  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.214  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.214  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:09.214  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:09.214  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:08:09.214  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:08:09.214  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:09.214  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:08:09.214  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:09.214  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-01 12:08:09.214  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:09.214  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.214  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:09.214  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:09.214  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-01 12:08:09.214  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:09.214  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-01 12:08:09.215  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.215  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.215  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-01 12:08:09.215  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.216  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.217  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.217  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.217  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.217  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:09.217  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:08:09.217  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:09.217  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.221  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.221  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.221  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.221  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-01 12:08:09.221  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:09.221  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:09.221  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:09.222  5600  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-01 12:08:09.224  4633  4722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-01 12:08:09.224  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:09.225  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:08:09.230  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:08:09.230  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:09.230  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:09.230  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:09.230  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:08:09.230  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:09.230  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:08:09.230  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:08:09.231  4633  4722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-01 12:08:09.231  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-01 12:08:09.232  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:09.233  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:08:09.233  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:08:09.233  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-01 12:08:09.233  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-01 12:08:09.233  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:08:09.233  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-01 12:08:09.237  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:09.238  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-01 12:08:09.238  5600  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-01 12:08:09.238  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-01 12:08:09.239  4633  4722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-01 12:08:09.239  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:09.239  4633  4726 D BtGatt.ScanManager: stopping BLe Batch
,11-01 12:08:09.243  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:09.245  4633  4722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-01 12:08:09.245  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:09.245  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-01 12:08:09.245  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-01 12:08:09.245  4633  4726 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-01 12:08:09.246  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-01 12:08:09.246  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-01 12:08:09.252  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.252  4633  4722 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-01 12:08:09.252  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-01 12:08:09.252  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-01 12:08:09.252  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-01 12:08:09.252  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-01 12:08:09.252  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-01 12:08:09.252  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.253  5600  5649 D BluetoothAdapter: STATE_ON
11-01 12:08:09.254  4633  4646 D BtGatt.GattService: registerClient() - UUID=8b3c7371-db4a-474a-b91e-44aec2eab136
11-01 12:08:09.255  4633  4722 D BtGatt.GattService: onClientRegistered() - UUID=8b3c7371-db4a-474a-b91e-44aec2eab136, clientIf=5
11-01 12:08:09.255  5600  5611 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-01 12:08:09.255  4633  4723 D BtGatt.GattService: start scan with filters
,11-01 12:08:09.258  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-01 12:08:09.258  4633  4726 D BtGatt.ScanManager: handling starting scan
11-01 12:08:09.258  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.258  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-01 12:08:09.258  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.258  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-01 12:08:09.258  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-01 12:08:09.258  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.258  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-01 12:08:09.258  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-01 12:08:09.258  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.258  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.259  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-01 12:08:09.259  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-01 12:08:09.259  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.262  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.262  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:08:09.262  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:09.263  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:09.263  5600  5649 I io.jxcore.node.ConnectionHelper: start: OK
11-01 12:08:09.263  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.264  4633  4722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-01 12:08:09.264  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:09.264  4633  4726 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-01 12:08:09.265  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.265  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.265  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.265  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:08:09.265  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:08:09.269  4633  4722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-01 12:08:09.270  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:09.270  4633  4726 D BtGatt.ScanManager: Starting BLE batch scan
11-01 12:08:09.270  4633  4726 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-01 12:08:09.279  4633  4722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-01 12:08:09.279  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-01 12:08:09.284  4633  4722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-01 12:08:09.284  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-01 12:08:09.767  5600  5600 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-01 12:08:09.767  5600  5600 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-01 12:08:09.767  5600  5600 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-01 12:08:14.263  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:14.264  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:14.264  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-01 12:08:14.264  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:14.264  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-01 12:08:14.264  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:14.264  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-01 12:08:14.265  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-01 12:08:14.265  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-01 12:08:14.265  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-01 12:08:14.265  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:14.265  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.266  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:14.266  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-01 12:08:14.266  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:14.271  5600  5649 D BluetoothAdapter: STATE_ON
11-01 12:08:14.272  4633  4646 D BtGatt.GattService: stopScan() - queue size =1
,11-01 12:08:14.274  4633  4723 D BtGatt.GattService: unregisterClient() - clientIf=5
11-01 12:08:14.275  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-01 12:08:14.275  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.275  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-01 12:08:14.276  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.276  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.276  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.276  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.276  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-01 12:08:14.277  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.277  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:14.277  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.277  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-01 12:08:14.277  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-01 12:08:14.279  4633  4633 D BtGatt.ScanManager: awakened up at time 108292
11-01 12:08:14.279  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:08:14.279  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.280   926  3831 I ActivityManager: Killing 5301:com.android.settings/1000 (adj 15): empty #17
,11-01 12:08:14.283  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.283  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:08:14.283  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.283  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:14.283  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-01 12:08:14.283  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:08:14.283  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-01 12:08:14.283  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:08:14.284  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-01 12:08:14.284  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-01 12:08:14.284  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:08:14.284  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-01 12:08:14.284  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,11-01 12:08:14.284  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:08:14.285  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:08:14.285  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:08:14.285  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:08:14.285  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:08:14.286  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-01 12:08:14.315  4633  4722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-01 12:08:14.315  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:14.316  4633  4726 D BtGatt.ScanManager: stopping BLe Batch
11-01 12:08:14.322  4633  4722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-01 12:08:14.322  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:14.322  4633  4726 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-01 12:08:14.339  4633  4722 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-01 12:08:14.339  4633  4722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:08:14.339  4633  4722 D BtGatt.GattService: current time is 108352644952
11-01 12:08:14.339  4633  4722 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -77, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -79, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-01 12:08:14.340  4633  4722 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-01 12:08:14.340  4633  4722 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-01 12:08:14.340  4633  4722 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-01 12:08:14.341  4633  4722 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-01 12:08:14.787  5600  5600 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-01 12:08:14.787  5600  5600 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-01 12:08:14.787  5600  5600 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-01 12:08:16.174   926  5368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110187, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-01 12:08:19.284  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-01 12:08:19.285  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:19.285  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:19.285  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.285  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.285  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:08:19.286  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-01 12:08:19.286  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:19.286  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.286  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.286  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:19.286  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:19.288  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.288  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.289  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.293  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.294  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.294  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.294  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-01 12:08:19.294  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:19.295  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.295  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
,11-01 12:08:19.297  5600  5649 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-01 12:08:19.300  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:19.300  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:19.300  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:19.300  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.300  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.301  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:19.301  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:19.301  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:19.301  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.301  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.301  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-01 12:08:19.301  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.302  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.302  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.302  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.302  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.305  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.305  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.305  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.305  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:19.305  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:19.305  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:08:19.305  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.307  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-01 12:08:19.307  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:19.307  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-01 12:08:19.307  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:19.308  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.308  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.308  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:19.308  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:19.308  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:19.308  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.308  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.308  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:19.308  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:19.308  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.308  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.309  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.309  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.311  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.311  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.311  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.311  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:19.312  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:19.312  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.312  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
,11-01 12:08:19.314  5600  5649 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-01 12:08:19.315  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:19.315  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:19.315  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:19.315  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.315  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:19.315  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.316  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:19.316  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:19.316  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.316  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.316  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-01 12:08:19.316  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.316  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.317  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.317  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.317  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.320  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.321  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.321  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.321  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:19.321  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:19.321  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:08:19.321  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.323  5600  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-01 12:08:19.323  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:19.323  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:19.324  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:19.324  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.324  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:19.324  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.324  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:19.324  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
,11-01 12:08:19.324  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.325  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.325  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:19.325  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.325  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.325  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.325  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:19.325  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.328  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.328  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.328  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.328  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:19.328  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:19.328  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.328  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
,11-01 12:08:19.330  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-01 12:08:19.330  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-01 12:08:19.331  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-01 12:08:19.331  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-01 12:08:19.331  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-01 12:08:19.331  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-01 12:08:19.331  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-01 12:08:19.331  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-01 12:08:19.331  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-01 12:08:19.331  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:19.331  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:19.332  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-01 12:08:19.332  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.332  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.332  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.332  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:19.332  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:19.332  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:08:19.332  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.332  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:19.332  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.332  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.332  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.333  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:19.333  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.337  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.337  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.337  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.337  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:19.337  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:19.337  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.337  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
,11-01 12:08:19.338  5600  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-01 12:08:19.339  5600  5649 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-01 12:08:19.339  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-01 12:08:19.343  5600  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-01 12:08:19.344  5600  5649 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-01 12:08:19.344  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-01 12:08:19.344  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-01 12:08:19.344  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-01 12:08:19.344  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-01 12:08:19.344  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-01 12:08:19.344  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-01 12:08:19.345  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-01 12:08:19.346  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-01 12:08:19.346  5600  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,11-01 12:08:19.348  5600  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-01 12:08:19.348  5600  5649 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-01 12:08:19.349  5600  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-01 12:08:19.349  5600  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-01 12:08:19.349  5600  5649 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-01 12:08:19.349  5600  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-01 12:08:19.349  5600  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-01 12:08:19.350  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-01 12:08:19.355  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-01 12:08:19.356  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-01 12:08:19.356  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-01 12:08:19.357  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-01 12:08:19.357  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-01 12:08:19.357  5600  5649 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-01 12:08:19.357  5600  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-01 12:08:19.357  5600  5649 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-01 12:08:19.358  5600  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 122)
11-01 12:08:19.358  5600  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-01 12:08:19.358  5600  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-01 12:08:19.358  5600  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-01 12:08:19.358  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:19.359  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:19.359  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:19.359  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.359  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.359  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.359  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:19.359  5600  5649 D org.thaliproje,ct.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-01 12:08:19.361  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:19.361  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.361  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.361  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:19.361  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:19.361  4646  4646 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[28489]" dev="sockfs" ino=28489 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-01 12:08:19.361  4646  4646 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[28489]" dev="sockfs" ino=28489 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-01 12:08:19.362  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:19.362  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:19.362  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.362  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.362  5600  5654 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-01 12:08:19.362  5600  5654 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-01 12:08:19.363  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.363  5600  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 122
11-01 12:08:19.363  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.363  5600  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-01 12:08:19.364  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.364  5600  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 122)
11-01 12:08:19.364  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:19.364  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:19.364  5600  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 122)
11-01 12:08:19.364  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:08:19.364  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.365  5600  5649 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-01 12:08:19.365  5600  5654 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-01 12:08:19.365  5600  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-01 12:08:19.365  5600  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 122)
11-01 12:08:19.365  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:19.366  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:19.366  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:19.366  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.366  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:19.366  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.366  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:19.366  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:19.366  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.366  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.366  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:19.366  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.366  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.366  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:19.367  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.367  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.368  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.368  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.368  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.368  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:19.368  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:19.368  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.369  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.369  5600  5649 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-01 12:08:19.370  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:19.370  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:19.370  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:19.370  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.370  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.370  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.370  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:19.370  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:19.370  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.370  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
,11-01 12:08:19.370  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:19.371  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.371  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.371  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.371  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.371  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.373  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.373  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.373  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.373  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-01 12:08:19.373  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:19.373  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.373  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.374  5600  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-01 12:08:19.374  5600  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-01 12:08:19.375  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-01 12:08:19.375  5600  5649 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-01 12:08:19.375  5600  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-01 12:08:19.375  5600  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-01 12:08:19.375  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-01 12:08:19.375  5600  5649 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,11-01 12:08:19.375  5600  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-01 12:08:19.375  5600  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-01 12:08:19.375  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-01 12:08:19.375  5600  5649 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-01 12:08:19.375  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:19.375  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:19.375  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:19.375  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.375  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:19.375  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.376  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:19.376  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:19.376  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.376  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.376  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:19.376  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.376  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.376  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.376  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.376  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.377  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:19.377  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.377  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:19.377  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:19.377  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:19.378  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.378  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.378  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:19.378  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.378  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:19.378  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-01 12:08:19.378  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:19.378  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:19.379  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:19.379  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:19.379  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:19.379  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:20.434   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-01 12:08:20.434   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-01 12:08:23.278   926  2994 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-01 12:08:24.379  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:24.380  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
,11-01 12:08:24.380  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:24.380  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.381  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:24.381  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:24.381  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:24.382  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:24.382  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-01 12:08:24.382  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:24.382  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:24.382  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.383  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:24.383  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:24.383  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:24.383  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:08:24.383  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:24.384  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:24.384  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.384  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:24.384  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.384  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.385  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.388  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:24.388  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:24.390  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:24.390  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-01 12:08:24.391  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:24.391  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:08:24.391  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:24.394  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-01 12:08:24.395  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:08:24.396  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-01 12:08:24.398  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-01 12:08:24.398  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-01 12:08:24.398  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-01 12:08:24.399  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-01 12:08:24.399  5600  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-01 12:08:24.399  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-01 12:08:24.399  5600  5600 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-01 12:08:24.399  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:24.399  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-01 12:08:24.399  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-01 12:08:24.399  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-01 12:08:24.399  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.399  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-01 12:08:24.400  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-01 12:08:24.400  5600  5656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-01 12:08:24.400  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:24.400  5600  5600 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-01 12:08:24.400  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:08:24.400  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-01 12:08:24.400  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-01 12:08:24.400  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-01 12:08:24.400  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.400  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.400  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:24.398  4882  4882 W Binder_5: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32979]" dev="sockfs" ino=32979 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-01 12:08:24.398  4882  4882 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32979]" dev="sockfs" ino=32979 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-01 12:08:24.402  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.402  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:08:24.402  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.402  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:24.403  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:24.403  5600  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-01 12:08:24.403  5600  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-01 12:08:24.403  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:24.403  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:08:24.403  5600  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-01 12:08:24.403  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:24.403  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:08:24.403  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:24.403  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:08:24.403  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:24.403  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:24.403  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.403  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-01 12:08:24.403  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:24.403  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:24.403  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:24.403  5600  5600 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-01 12:08:24.403  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:24.404  5600  5600 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-01 12:08:24.404  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.404  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.404  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.404  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.404  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.405  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.405  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.405  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.405  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:24.405  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:24.405  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:24.406  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:24.407  5600  5649 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-01 12:08:24.407  5600  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-01 12:08:24.407  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-01 12:08:24.408  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-01 12:08:24.408  5600  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-01 12:08:24.408  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:24.408  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:24.408  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:24.408  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:24.408  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.408  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.408  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-01 12:08:24.408  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:24.408  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:24.408  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:24.409  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:24.409  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.409  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.409  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:24.409  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.409  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.410  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.410  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.411  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.411  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:24.411  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-01 12:08:24.411  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:24.411  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
,11-01 12:08:24.417  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:24.417  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:24.417  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:24.417  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:08:24.417  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:24.417  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.417  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:24.417  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:24.417  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:24.417  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:24.417  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:24.417  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:24.417  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.418  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.418  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.418  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.419  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.419  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:24.419  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.419  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:24.419  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:24.419  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:24.419  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
,11-01 12:08:24.420  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:08:24.420  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:08:24.420  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:08:24.420  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-01 12:08:24.420  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.421  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.421  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:08:24.421  5600  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1e369 not in the list
11-01 12:08:24.421  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:24.421  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
11-01 12:08:24.421  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:24.421  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:24.421  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.421  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:24.421  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:24.421  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:24.422  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:08:24.422  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.422  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:08:24.422  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:08:24.422  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:08:24.422  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:24.422  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e01ee not in the list
,11-01 12:08:24.424  5600  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-01 12:08:24.425  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-01 12:08:24.425  5600  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-01 12:08:24.425  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-01 12:08:24.425  5600  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-01 12:08:24.425  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-01 12:08:24.427  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-01 12:08:24.427  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-01 12:08:24.427  5600  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-01 12:08:24.427  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-01 12:08:24.427  5600  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-01 12:08:24.427  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-01 12:08:24.428  5600  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-01 12:08:24.428  5600  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-01 12:08:24.428  5600  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-01 12:08:24.428  5600  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-01 12:08:24.429  5600  5649 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-01 12:08:24.429  5600  5649 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-01 12:08:24.429  5600  5649 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-01 12:08:24.429  5600  5649 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-01 12:08:24.430  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:08:24.430  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5088720 added. We now have 3 listener(s)
11-01 12:08:24.430  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-01 12:08:24.432  5600  5649 D BluetoothAdapter: enable(): BT is already enabled..!
,11-01 12:08:24.432   926  3803 D WifiService: setWifiEnabled: true pid=5600, uid=10077
11-01 12:08:24.432   926  3803 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-01 12:08:24.492  4633  4832 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-01 12:08:24.492  4633  4854 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-01 12:08:24.904  5600  5600 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-01 12:08:25.435   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:26.312   926  2994 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-01 12:08:26.436   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:27.437   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:27.902   926  2992 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-01 12:08:28.438   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:29.438  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-01 12:08:29.438  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d78d9 added. We now have 4 listener(s)
11-01 12:08:29.438  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-01 12:08:29.439   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:29.452  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:08:29.453  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d78d9 removed from the list
11-01 12:08:29.453  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:29.453  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:29.453  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:29.455  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:08:29.456  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e4c29e added. We now have 4 listener(s)
,11-01 12:08:29.456  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-01 12:08:29.460  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:08:29.461  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e4c29e removed from the list
11-01 12:08:29.461  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:29.461  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:29.461  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:29.462  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:08:29.462  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e7317f added. We now have 4 listener(s)
,11-01 12:08:29.462  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-01 12:08:29.466   926  3172 D WifiService: setWifiEnabled: false pid=5600, uid=10077
,11-01 12:08:29.466   926  3172 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-01 12:08:29.469   926  2992 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-01 12:08:29.469   926  2992 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-01 12:08:29.470   926  2992 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-01 12:08:29.470   926  2992 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-01 12:08:29.477  4633  4716 D BluetoothAdapterState: Current state: ON, message: 23
11-01 12:08:29.476  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:08:29.477  4633  4716 D BluetoothAdapterProperties: Setting state to 13
11-01 12:08:29.477  4633  4716 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-01 12:08:29.479  4633  4716 D BluetoothAdapterProperties: onBluetoothDisable()
11-01 12:08:29.480  4633  4716 I BluetoothAdapterState: Entering PendingCommandState
11-01 12:08:29.482  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.482  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:08:29.482  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.482  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.482  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:29.482  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.482  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:29.482  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:08:29.482  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:08:29.483  4633  4633 D BluetoothMapService: onReceive
11-01 12:08:29.483  4633  4633 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-01 12:08:29.484  4633  4633 D BluetoothMapService: STATE_TURNING_OFF
11-01 12:08:29.484  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.484  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:29.484  4633  4633 D BluetoothMapService: MAP Service closeService in
11-01 12:08:29.484  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:08:29.484  4633  4633 D BluetoothMapMasInstance0: MAP Service shutdown
11-01 12:08:29.484  4633  4633 D ObexServerSockets0: shutdown(block = true)
11-01 12:08:29.485  4633  4722 D BluetoothAdapterProperties: Scan Mode:20
11-01 12:08:29.485  4633  4633 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-01 12:08:29.485  4633  4884 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-01 12:08:29.485  4633  4633 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-01 12:08:29.486  4633  4854 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-01 12:08:29.486  4633  4885 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-01 12:08:29.487   926  5369 D DhcpClient: Clearing IP address
,11-01 12:08:29.488   509   920 D CommandListener: Clearing all IP addresses on wlan0
11-01 12:08:29.488  4633  4633 I BtOppRfcommListener: stopping Accept Thread
11-01 12:08:29.489  4633  5323 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-01 12:08:29.489  4633  5323 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-01 12:08:29.491   509   920 D CommandListener: Setting iface cfg
,11-01 12:08:29.496  4633  4716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-01 12:08:29.497  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:29.499  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:29.501  3598  5421 V NativeCrypto: Read error: ssl=0x7f75b9a000: I/O error during system call, Connection timed out
11-01 12:08:29.503  3598  5421 V NativeCrypto: SSL shutdown failed: ssl=0x7f75b9a000: I/O error during system call, Broken pipe
,11-01 12:08:29.504  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-01 12:08:29.504   926  5370 D DhcpClient: Receive thread stopped
11-01 12:08:29.504  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.504  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.504  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.504  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:29.504  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.504  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:29.504  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:08:29.504  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:08:29.505  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.505  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:29.505   926  3177 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-01 12:08:29.506   926  5367 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-01 12:08:29.508  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.508  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:29.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:29.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:08:29.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:08:29.508   926  5367 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-01 12:08:29.508   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-01 12:08:29.508  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.508   926  2994 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-01 12:08:29.509  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:29.510   926  2994 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-01 12:08:29.512  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.512  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.512  5600  5600 V io.jxcore.node.ConnectivityMonitor:    , - is Wi-Fi Direct supported: true
11-01 12:08:29.512  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.512  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:29.512  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.512  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:29.512  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:08:29.512  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:08:29.512   926   939 I ActivityManager: Start proc 5660:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-01 12:08:29.513  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.513  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:29.516  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.516  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.516  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.516  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.516  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:29.516  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.516  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:29.516  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:08:29.516  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:08:29.517  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.517  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:29.518   926   926 D RttService: SCAN_AVAILABLE : 1
11-01 12:08:29.518   542   542 E Parcel  : Reading a NULL string not supported here.
11-01 12:08:29.519   926  3089 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-01 12:08:29.519  4633  4633 D HeadsetService: Received stop request...Stopping profile...
,11-01 12:08:29.520   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-01 12:08:29.520   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-01 12:08:29.521  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:29.525   926  2994 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-01 12:08:29.526   926   926 D BluetoothHeadset: Proxy object disconnected
,11-01 12:08:29.526  3765  3786 D BluetoothHeadset: Proxy object disconnected
11-01 12:08:29.526  3742  3886 W QCNEJ   : |CORE| network lost: 100
11-01 12:08:29.526   926   926 D BluetoothHeadset: Proxy object disconnected
11-01 12:08:29.526   926   926 D BluetoothHeadset: Proxy object disconnected
11-01 12:08:29.527  3148  3159 D BluetoothHeadset: Proxy object disconnected
11-01 12:08:29.527  3742  3886 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-01 12:08:29.527  4633  4633 D A2dpService: Received stop request...Stopping profile...
11-01 12:08:29.527  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.527  4633  4873 D A2dpStateMachine: Exit Disconnected: -1
11-01 12:08:29.528  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.528  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.528  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.528  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:29.528  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.528  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:29.528  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:29.528  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:08:29.529  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:29.529   926   926 D BluetoothA2dp: Proxy object disconnected
11-01 12:08:29.529  4633  4633 V BluetoothAdapterState: isTurningOn()=false
,11-01 12:08:29.529  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:29.529  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:29.530  4633  4633 D HidService: Received stop request...Stopping profile...
11-01 12:08:29.530  4633  4633 D HidService: Stopping Bluetooth HidService
11-01 12:08:29.531  4633  4633 D HealthService: Received stop request...Stopping profile...
11-01 12:08:29.533  3148  3148 D HeadsetProfile: Bluetooth service disconnected
11-01 12:08:29.533  3148  3148 D BluetoothA2dp: Proxy object disconnected
11-01 12:08:29.533  3148  3148 D BluetoothInputDevice: Proxy object disconnected
11-01 12:08:29.533  3148  3148 D HidProfile: Bluetooth service disconnected
11-01 12:08:29.536  4633  4633 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-01 12:08:29.536  4633  4633 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-01 12:08:29.537  4633  4633 D PanService: Received stop request...Stopping profile...
11-01 12:08:29.537  4633  4722 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-01 12:08:29.537  4633  4832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:29.537  4633  4832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:29.537  4633  4832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:29.537  4633  4722 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-01 12:08:29.539  3148  3148 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-01 12:08:29.539  3148  3148 D PanProfile: Bluetooth service disconnected
11-01 12:08:29.540  4633  4633 D BluetoothMapService: Received stop request...Stopping profile...
11-01 12:08:29.540  4633  4633 D BluetoothMapService: stop()
11-01 12:08:29.541  4633  4633 D BluetoothMapAppObserver: deinitObservers()
11-01 12:08:29.541  4633  4633 D BluetoothMapAppObserver: removeReceiver()
11-01 12:08:29.542  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:29.542  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:29.542  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:29.542  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:29.542   926  2992 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-01 12:08:29.543  3148  3148 D BluetoothMap: Proxy object disconnected
11-01 12:08:29.543  3148  3148 D MapProfile: Bluetooth service disconnected
11-01 12:08:29.543   926  2992 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-01 12:08:29.544  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:29.544  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:29.544  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
,11-01 12:08:29.544  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:29.544  4633  4633 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-01 12:08:29.544  4633  4633 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-01 12:08:29.544  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:29.544  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:29.544  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:29.545  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:29.545  4633  4633 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-01 12:08:29.545  4633  4633 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-01 12:08:29.545  4633  4722 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-01 12:08:29.545  4633  4832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:29.545  4633  4722 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-01 12:08:29.545  4633  4832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:29.546  4633  4832 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-01 12:08:29.546  4633  4722 E bt_btif : L2CAP - PSM: 0x0017 not found for deregistration
11-01 12:08:29.546  4633  4832 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-01 12:08:29.546  4633  4832 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-01 12:08:29.546  4633  4832 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-01 12:08:29.546  4633  4633 D SapService: Received stop request...Stopping profile...
11-01 12:08:29.546  4633  4633 V SapService: stop()
11-01 12:08:29.547  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:29.548  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:29.548  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:29.548  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:29.548  4633  4633 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-01 12:08:29.548  4633  4633 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-01 12:08:29.549  4633  4633 D BluetoothMapService: MAP Service closeService in
11-01 12:08:29.549  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:29.549  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:29.549  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:29.549  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:29.549  4633  4633 D BluetoothMapService: cleanup()
11-01 12:08:29.549  4633  4633 D BluetoothMapService: MAP Service closeService in
11-01 12:08:29.549  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:29.549  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:29.550  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:29.550  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:29.550  4633  4716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-01 12:08:29.550  4633  4716 D BluetoothAdapterProperties: Setting state to 15
11-01 12:08:29.550  4633  4716 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-01 12:08:29.551  4633  4716 I BluetoothAdapterState: Entering BleOnState
,11-01 12:08:29.552  3148  3997 D BluetoothPbap: onBluetoothStateChange: up=false
11-01 12:08:29.554   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-01 12:08:29.554   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-01 12:08:29.554   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-01 12:08:29.554  3765  3787 D BluetoothHeadset: onBluetoothStateChange: up=false
11-01 12:08:29.554   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-01 12:08:29.555  3148  3159 D BluetoothA2dp: onBluetoothStateChange: up=false
11-01 12:08:29.555  3148  3160 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-01 12:08:29.555  3148  3997 D BluetoothPan: onBluetoothStateChange on: false
11-01 12:08:29.556  3148  3159 D BluetoothMap: onBluetoothStateChange: up=false
11-01 12:08:29.556  3148  3160 D BluetoothHeadset: onBluetoothStateChange: up=false
11-01 12:08:29.557  4633  4716 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-01 12:08:29.557  4633  4716 D BluetoothAdapterProperties: Setting state to 16
11-01 12:08:29.557  4633  4716 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-01 12:08:29.558  4633  4716 D BluetoothAdapterProperties: onBleDisable
11-01 12:08:29.558  4633  4716 I BluetoothAdapterState: Entering PendingCommandState
,11-01 12:08:29.558  4633  4718 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-01 12:08:29.560   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-01 12:08:29.561  4633  4832 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-01 12:08:29.561  4633  4832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:29.561  4633  4722 D BluetoothAdapterProperties: Scan Mode:20
11-01 12:08:29.561  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.561  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.561  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.561  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.561  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:29.561  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.561  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:29.561  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:29.561  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-01 12:08:29.564  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.564  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.564  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.564  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.564  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:29.564  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.564  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:29.564  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:29.564  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-01 12:08:29.566  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.566  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.566  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.566  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.566  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:29.566  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.566  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:29.566  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:29.566  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:29.568  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:29.569  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:29.570  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:29.578  5660  5660 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-01 12:08:29.582   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-01 12:08:29.582   509   920 D CommandListener: Clearing all IP addresses on wlan0
11-01 12:08:29.583   509   920 D TetherController: Setting IP forward enable = 0
11-01 12:08:29.584   926  2994 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-01 12:08:29.584   926  2994 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-01 12:08:29.586   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-01 12:08:29.589   926  2992 D DhcpClient: doQuit
,11-01 12:08:29.589   926  2992 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-01 12:08:29.590   926  5369 D DhcpClient: onQuitting
,11-01 12:08:29.590  3972  3972 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-01 12:08:29.590  3467  3467 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-01 12:08:29.589  5256  5256 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@feca248 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-01 12:08:29.592  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:29.592  5006  5042 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-01 12:08:29.593  5006  5042 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-01 12:08:29.593  5006  5042 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-01 12:08:29.593  5006  5042 E SarControlService: no key has been found,reset the power
,11-01 12:08:29.593  5006  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-01 12:08:29.593  5006  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-01 12:08:29.594  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.594  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.594  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.594  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.594  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:29.594  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.594  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:29.594  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:29.594  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:29.593  5006  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-01 12:08:29.595  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-01 12:08:29.595  5063  5063 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-01 12:08:29.595  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.595  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:29.597  5006  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-01 12:08:29.597  5006  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-01 12:08:29.597  5006  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-01 12:08:29.598  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-01 12:08:29.598  5063  5063 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-01 12:08:29.599  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.599  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.599  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.599  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.599  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:29.599  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.599  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:29.599  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:29.599  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:29.599  5063  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@be0646e HexData = [00000000ea03000000000000ffffffff]
11-01 12:08:29.599  5063  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-01 12:08:29.599  5063  5082 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-01 12:08:29.599  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-01 12:08:29.599  5006  5028 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-01 12:08:29.600  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.600  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:29.603  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.603  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:29.603  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:29.603  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:29.603  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:29.603  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:29.603  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:29.603  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:29.603  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-01 12:08:29.605  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:29.605  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-01 12:08:29.605  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:29.607  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:29.607  5063  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@be0646e HexData = [00000000eb03000000000000ffffffff]
11-01 12:08:29.608  5063  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-01 12:08:29.608  5063  5082 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-01 12:08:29.608  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-01 12:08:29.608  5006  5023 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-01 12:08:29.608  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:29.612   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eb8d235:true
11-01 12:08:29.612  3467  3467 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-01 12:08:29.613  3598  3598 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-01 12:08:29.621  3467  3467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-01 12:08:29.631  5660  5660 D LocalBluetoothProfileManager: Adding local MAP profile
,11-01 12:08:29.633  5660  5660 D BluetoothMap: Create BluetoothMap proxy object
,11-01 12:08:29.637   509   920 E Netd    : netlink response contains error (No such file or directory)
,11-01 12:08:29.637   509   920 D TetherController: Setting IP forward enable = 0
11-01 12:08:29.638   926  2994 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-01 12:08:29.640  5660  5660 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-01 12:08:29.645  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,11-01 12:08:29.649  3467  3467 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-01 12:08:29.649  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-01 12:08:29.653  5660  5660 D DockEventReceiver: finishStartingService: stopping service
11-01 12:08:29.654  3598  3598 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-01 12:08:29.655   926  3800 I ActivityManager: Killing 5395:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-01 12:08:29.664  3467  3467 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-01 12:08:29.673  3999  3999 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-01 12:08:29.678  3999  3999 D SystemUpdateService: onCreate
11-01 12:08:29.681  3999  3999 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-01 12:08:29.688  3999  3999 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-01 12:08:29.693  3999  5392 I iu.UploadsManager: num queued entries: 0
,11-01 12:08:29.693  3999  5392 I iu.UploadsManager: num updated entries: 0
,11-01 12:08:29.694  3999  5696 I SystemUpdateService: active receiver: enabled
,11-01 12:08:29.696  3999  3999 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-01 12:08:29.698  3999  3999 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-01 12:08:29.702  3999  5392 I iu.SyncManager: NEXT; no task
,11-01 12:08:29.704  3999  5696 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-01 12:08:29.705  3999  5696 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-01 12:08:29.705  3999  5696 I SystemUpdateService: now status is 0 (complete)
11-01 12:08:29.705  3999  5696 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-01 12:08:29.705  3999  5696 I SystemUpdateService: file has been verified
11-01 12:08:29.706  3999  5696 I SystemUpdateService: OTA package size = 21989297
,11-01 12:08:29.709   926  3838 I ActivityManager: Start proc 5698:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-01 12:08:29.715  3999  5696 I SystemUpdateService: showing system update notification
,11-01 12:08:29.724   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-01 12:08:29.727  3999  3999 D SystemUpdateService: onDestroy
,11-01 12:08:29.741  5698  5698 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
11-01 12:08:29.744  5698  5698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-01 12:08:29.751  5698  5698 D SprintDMHelper: simOperator: 
11-01 12:08:29.751  5698  5698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-01 12:08:29.761  4500  5710 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-01 12:08:29.764   926  3838 I ActivityManager: Killing 5256:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-01 12:08:29.787   926  2992 D wifi    : In wifi stop Hal
,11-01 12:08:29.787   926  2992 D wifi    : halHandle = 0x7f5f58f0c0, mVM = 0x7f7bc0d140, mCls = 0x100a02
,11-01 12:08:29.787  4500  4500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-01 12:08:29.787   926  3466 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-01 12:08:29.787   926  3466 D WifiHAL : Got a signal to exit!!!
11-01 12:08:29.787   926  3466 I WifiHAL : Exit wifi_event_loop
11-01 12:08:29.788   926  2992 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-01 12:08:29.788   926  2992 E WifiHAL : Event processing terminated
11-01 12:08:29.788   926  2992 D wifi    : In wifi cleaned up handler
,11-01 12:08:29.788   926  2992 I WifiHAL : Internal cleanup completed
11-01 12:08:29.789  3714  4203 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-01 12:08:29.789  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:29.790  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:29.791  4633  4722 I bt_hci  : shut_down
11-01 12:08:29.792  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:29.801   926  3803 I ActivityManager: Start proc 5711:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-01 12:08:29.805  4633  4727 D bt_hwcfg: hw_epilog_process
,11-01 12:08:29.805  4633  4727 I bt_vendor: low_power_mode_cb
,11-01 12:08:29.809   926  3466 D wifi    : set interface wlan0 flags (DOWN)
,11-01 12:08:29.808  4633  4727 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-01 12:08:29.809  4633  4727 I bt_vendor: epilog_cb
11-01 12:08:29.809  4633  4727 I bt_hci  : epilog_finished_callback
11-01 12:08:29.810   926  2992 D WifiNative-HAL: HAL event thread stopped successfully
11-01 12:08:29.812  4633  4722 I bt_hci_h4: hal_close
11-01 12:08:29.813  4633  4722 I bt_userial_vendor: device fd = 54 close
,11-01 12:08:29.830  5711  5711 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-01 12:08:29.837   926   937 I ActivityManager: Killing 5472:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-01 12:08:29.922  4633  4718 D bt_stack_manager: event_shut_down_stack finished.
,11-01 12:08:29.923  4633  4716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-01 12:08:29.925  4633  4716 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-01 12:08:29.925  4633  4633 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-01 12:08:29.925  4633  4633 D BtGatt.GattService: Received stop request...Stopping profile...
11-01 12:08:29.925  4633  4633 D BtGatt.GattService: stop()
,11-01 12:08:29.926  4633  4633 D BtGatt.AdvertiseManager: advertise clients cleared
,11-01 12:08:29.927  4633  4633 V BluetoothAdapterState: isTurningOff()=false
11-01 12:08:29.928  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:29.928  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:29.928  4633  4633 V BluetoothAdapterState: isBleTurningOff()=true
11-01 12:08:29.928  4633  4716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-01 12:08:29.928  4633  4716 D BluetoothAdapterProperties: Setting state to 10
11-01 12:08:29.928  4633  4716 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-01 12:08:29.929  4633  4716 I BluetoothAdapterState: Entering OffState
11-01 12:08:29.929   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-01 12:08:29.939  4633  4633 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-01 12:08:29.939  4633  4633 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-01 12:08:29.939  4633  4633 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-01 12:08:29.940  4633  4718 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-01 12:08:29.944  4633  4633 I art     : System.exit called, status: 0
11-01 12:08:29.945  4633  4633 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-01 12:08:29.965   926  3614 I ActivityManager: Process com.android.bluetooth (pid 4633) has died
,11-01 12:08:30.012   926   943 D Tethering: InitialState.processMessage what=4
,11-01 12:08:30.015   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-01 12:08:30.439   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-01 12:08:34.487   926  3807 D WifiService: setWifiEnabled: true pid=5600, uid=10077
11-01 12:08:34.487   926  3807 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-01 12:08:34.494   509   920 D SoftapController: Softap fwReload - Ok
,11-01 12:08:34.502   509   920 D CommandListener: Setting iface cfg
11-01 12:08:34.502   509   920 D CommandListener: Trying to bring down wlan0
11-01 12:08:34.503   509   920 D CommandListener: Clearing all IP addresses on wlan0
,11-01 12:08:34.507   926  2992 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-01 12:08:35.097   926  2992 D wifi    : set interface wlan0 flags (UP)
,11-01 12:08:35.101   926  2992 I WifiHAL : Initializing wifi
11-01 12:08:35.102   926  2992 I WifiHAL : Creating socket
11-01 12:08:35.106   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-01 12:08:35.108   926  2992 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-01 12:08:35.108   926  2992 D wifi    : Did set static halHandle = 0x7f5f58f0c0
11-01 12:08:35.108   926  2992 D wifi    : halHandle = 0x7f5f58f0c0, mVM = 0x7f7bc0d140, mCls = 0x19c6
11-01 12:08:35.109   926  2992 D wifi    : array field set
11-01 12:08:35.109   926  2992 I WifiNative-HAL: interface[0] = wlan0
11-01 12:08:35.111   926  5730 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547060510912
11-01 12:08:35.111   926  5730 D wifi    : waitForHalEvents called, vm = 0x7f7bc0d140, obj = 0x19c6, env = 0x7f5ff86bc0
,11-01 12:08:35.188  5731  5731 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-01 12:08:35.213   926  2992 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-01 12:08:35.220  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:35.222  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:35.224  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:35.263  5731  5731 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-01 12:08:35.295  5731  5731 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-01 12:08:35.295  5731  5731 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-01 12:08:35.310   926  2992 D WifiConfigStore: Loading config and enabling all networks 
,11-01 12:08:35.315  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:35.315  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:35.315  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:35.315  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:35.315  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:35.315  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:35.315  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:35.315  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:35.315  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:35.315  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:35.316  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-01 12:08:35.318  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:35.318  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:35.318  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:35.318  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:35.318  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:35.318  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:35.318  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:35.318  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:35.318  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:35.318  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:35.318  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-01 12:08:35.319  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:35.319  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:35.319  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:35.319  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:35.319  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:35.319  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:35.319  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:35.319  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:35.319  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:35.319  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:35.319  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:35.340   926  2992 D WifiConfigStore: loaded 0 passpoint configs
11-01 12:08:35.341   926  2992 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-01 12:08:35.341   926  2992 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-01 12:08:35.341   926  2992 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-01 12:08:35.342   926  2992 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-01 12:08:35.342   926  2992 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-01 12:08:35.343   926  2992 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-01 12:08:35.343   926  2992 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-01 12:08:35.343   926  2992 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-01 12:08:35.343   926  2992 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-01 12:08:35.344   926  2992 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-01 12:08:35.344   926  2992 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-01 12:08:35.344   926  2992 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-01 12:08:35.346   926  2992 D WifiNative-HAL: Setting external_sim to 1
11-01 12:08:35.346   926  2992 D wifi    : setting dfs flag to true, 0x7f5c2efe40
11-01 12:08:35.347   926  2992 D WifiStateMachine: Setting OUI to DA-A1-19
11-01 12:08:35.347   926  2992 D wifi    : setting scan oui 0x7f5c2efe40
11-01 12:08:35.347   926  2992 D WifiHAL : Sending mac address OUI
11-01 12:08:35.349  4500  4500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-01 12:08:35.350   926  2992 E native  : do suspend false
,11-01 12:08:35.361   926  2992 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-01 12:08:35.361   926   926 D RttService: SCAN_AVAILABLE : 3
11-01 12:08:35.361   926  3089 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-01 12:08:35.361   509   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-01 12:08:35.363   509   920 D CommandListener: Setting iface cfg
11-01 12:08:35.367   926  2969 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
11-01 12:08:35.367   926  2969 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
11-01 12:08:35.379   926  2969 D WifiNative-HAL: p2pGetDeviceAddress
11-01 12:08:35.385   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129397 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
11-01 12:08:35.385   926  2969 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-01 12:08:35.440   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:36.441   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:37.442   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:38.443   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:38.457  5731  5731 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-01 12:08:38.480  5731  5731 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-01 12:08:38.489  5731  5731 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-01 12:08:38.493  5731  5731 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-01 12:08:38.522   926  2992 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-01 12:08:38.523   926  2992 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-01 12:08:38.523   926  2992 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-01 12:08:38.534   926  2992 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-01 12:08:38.562   926  2992 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-01 12:08:38.568  5731  5731 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-01 12:08:38.989  5731  5731 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-01 12:08:39.026  5731  5731 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-01 12:08:39.028  5731  5731 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-01 12:08:39.036   926  2992 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-01 12:08:39.037   926  2992 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-01 12:08:39.037   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-01 12:08:39.055   926  2992 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-01 12:08:39.068   509   920 D CommandListener: Setting iface cfg
,11-01 12:08:39.073   926  2992 D WifiStateMachine: Start Dhcp Watchdog 2
,11-01 12:08:39.079   926  5737 D DhcpClient: Receive thread started
,11-01 12:08:39.084   926  2994 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-01 12:08:39.084   926  2992 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-01 12:08:39.084   926  2994 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-01 12:08:39.165   926  2992 E native  : do suspend false
,11-01 12:08:39.180   926  5736 D DhcpClient: Broadcasting DHCPDISCOVER
,11-01 12:08:39.194   926  5737 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-01 12:08:39.195   926  5736 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-01 12:08:39.197   926  5736 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-01 12:08:39.209   926  5737 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-01 12:08:39.210   926  5736 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-01 12:08:39.213   509   920 D CommandListener: Setting iface cfg
11-01 12:08:39.218   926  2992 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-01 12:08:39.223   926  5736 D DhcpClient: Scheduling renewal in 86399s
,11-01 12:08:39.235   926  2992 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-01 12:08:39.237   926  2992 D WifiConfigStore: No blacklist allowed without epno enabled
,11-01 12:08:39.240   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-01 12:08:39.242   926  2994 D ConnectivityService: Adding iface wlan0 to network 101
,11-01 12:08:39.251   926  2992 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-01 12:08:39.301   926  2994 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-01 12:08:39.301   926  2994 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-01 12:08:39.306   926  2994 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-01 12:08:39.308   926  2994 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-01 12:08:39.310   926  2994 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-01 12:08:39.317   926  2994 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-01 12:08:39.321   926  2994 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-01 12:08:39.322   926  2994 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-01 12:08:39.322   926  2994 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-01 12:08:39.322   926  2992 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-01 12:08:39.322   926  2994 D ConnectivityService:    accepting network in place of null
11-01 12:08:39.322   926  2992 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-01 12:08:39.323   926  2994 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-01 12:08:39.334   926  5735 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133347, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-01 12:08:39.347   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-01 12:08:39.369   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-01 12:08:39.373   926  2994 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-01 12:08:39.373   926  2994 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-01 12:08:39.373  3742  3886 W QCNEJ   : |CORE| network available: 101
11-01 12:08:39.374   926  2994 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-01 12:08:39.375   926   943 D Tethering: MasterInitialState.processMessage what=3
11-01 12:08:39.379  3742  3886 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-01 12:08:39.382  3742  3886 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-01 12:08:39.383  3742  3886 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-01 12:08:39.383  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.383  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:39.383  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:39.383  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:39.383  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:39.383  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:39.383  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:39.383  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:08:39.383  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:08:39.383  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.383  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:39.385  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.385  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:39.385  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:39.385  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:39.385  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:39.385  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:39.385  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:39.385  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:08:39.385  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:08:39.385  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.385  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:39.387  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.387  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:39.387  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:39.387  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:39.387  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:08:39.387  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:39.387  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:39.387  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:08:39.387  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:08:39.387  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.387  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:08:39.389  3972  3972 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-01 12:08:39.392  3999  3999 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-01 12:08:39.395  3999  3999 D SystemUpdateService: onCreate
,11-01 12:08:39.400  5006  5042 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-01 12:08:39.400  5006  5042 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-01 12:08:39.400  5006  5042 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-01 12:08:39.400  5006  5042 E SarControlService: no key has been found,reset the power
11-01 12:08:39.400  5006  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-01 12:08:39.401  5006  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-01 12:08:39.401  5006  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-01 12:08:39.401  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-01 12:08:39.401  5063  5063 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-01 12:08:39.402  5006  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-01 12:08:39.402  5006  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-01 12:08:39.403  5006  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-01 12:08:39.403  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-01 12:08:39.403  5063  5063 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-01 12:08:39.404  3999  3999 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-01 12:08:39.405   926  5734 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-01 12:08:39.408  5063  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@be0646e HexData = [00000000ec03000000000000ffffffff]
,11-01 12:08:39.408  5063  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-01 12:08:39.408  5063  5082 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-01 12:08:39.408  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-01 12:08:39.408  5006  5028 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-01 12:08:39.409  5063  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@be0646e HexData = [00000000ed03000000000000ffffffff]
11-01 12:08:39.410  5063  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-01 12:08:39.410  5063  5082 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-01 12:08:39.411  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-01 12:08:39.411  5006  5023 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-01 12:08:39.415  3999  3999 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-01 12:08:39.420  3999  5392 I iu.UploadsManager: num queued entries: 0
,11-01 12:08:39.421  3999  3999 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-01 12:08:39.422  3999  3999 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-01 12:08:39.424  5698  5698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-01 12:08:39.427  5698  5698 D SprintDMHelper: simOperator: 
11-01 12:08:39.427  5698  5698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-01 12:08:39.443   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:39.450  3999  5748 I SystemUpdateService: active receiver: enabled
,11-01 12:08:39.457   926  5734 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 01 Nov 2016 11:08:39 GMT], X-Android-Received-Millis=[1477998519457], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477998519432]}
,11-01 12:08:39.458   926  2994 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-01 12:08:39.458   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-01 12:08:39.458   926  2994 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-01 12:08:39.459   926  2994 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-01 12:08:39.461  3999  5392 I iu.UploadsManager: num updated entries: 0
,11-01 12:08:39.462  3999  5392 I iu.SyncManager: NEXT; no task
,11-01 12:08:39.470  3999  5748 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-01 12:08:39.472  3999  5748 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-01 12:08:39.472  3999  5748 I SystemUpdateService: now status is 0 (complete)
11-01 12:08:39.472  3999  5748 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-01 12:08:39.472  3999  5748 I SystemUpdateService: file has been verified
11-01 12:08:39.472  3999  5748 I SystemUpdateService: OTA package size = 21989297
,11-01 12:08:39.478  3999  5748 I SystemUpdateService: showing system update notification
,11-01 12:08:39.486   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-01 12:08:39.489  3999  3999 D SystemUpdateService: onDestroy
,11-01 12:08:39.492   926  3807 D WifiService: setWifiEnabled: false pid=5600, uid=10077
11-01 12:08:39.492   926  3807 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-01 12:08:39.495   926  2992 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-01 12:08:39.495   926  2992 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-01 12:08:39.495   926  2992 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-01 12:08:39.495   926  2992 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-01 12:08:39.503   926  5736 D DhcpClient: Clearing IP address
11-01 12:08:39.503   509   920 D CommandListener: Clearing all IP addresses on wlan0
11-01 12:08:39.505   509   920 D CommandListener: Setting iface cfg
,11-01 12:08:39.506   926  5737 D DhcpClient: Receive thread stopped
,11-01 12:08:39.512  3598  5749 V NativeCrypto: SSL handshake aborted: ssl=0x7f60199000: I/O error during system call, Connection timed out
,11-01 12:08:39.516   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-01 12:08:39.516   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-01 12:08:39.518   542   542 E Parcel  : Reading a NULL string not supported here.
11-01 12:08:39.521   926   926 D RttService: SCAN_AVAILABLE : 1
11-01 12:08:39.522   926  3089 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-01 12:08:39.525   926  2992 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-01 12:08:39.525   926  2994 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-01 12:08:39.525  4500  5752 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,11-01 12:08:39.526  3742  3886 W QCNEJ   : |CORE| network lost: 101
,11-01 12:08:39.529  3742  3886 W QCNEJ   : |CORE| onLost: unbind the process to WIFI,
11-01 12:08:39.530   926  2992 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.214.238 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
11-01 12:08:39.538  4500  5752 W Babel_NetworkConnectionCheckingService: 	... 23 more
11-01 12:08:39.538  4500  5752 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-01 12:08:39.548   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-01 12:08:39.566   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-01 12:08:39.566   509   920 D CommandListener: Clearing all IP addresses on wlan0
11-01 12:08:39.567   926  2994 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-01 12:08:39.567   926  2994 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-01 12:08:39.569   926  2992 D DhcpClient: doQuit
,11-01 12:08:39.569   926  2992 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-01 12:08:39.569   926  5736 D DhcpClient: onQuitting
11-01 12:08:39.569   926   943 D Tethering: MasterInitialState.processMessage what=3
11-01 12:08:39.570  5731  5731 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-01 12:08:39.576  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-01 12:08:39.576  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:39.576  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:39.576  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:39.576  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:39.576  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:39.576  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:39.576  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:39.576  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:39.576  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.576  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:39.578  3972  3972 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-01 12:08:39.581  3999  3999 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-01 12:08:39.582  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.582  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:39.582  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:39.582  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:39.582  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:39.582  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:39.582  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:39.582  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:39.582  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:39.582  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.582  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:39.582  5006  5042 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-01 12:08:39.582  5006  5042 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-01 12:08:39.583  5006  5042 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-01 12:08:39.583  5006  5042 E SarControlService: no key has been found,reset the power
11-01 12:08:39.583  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.583  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:39.583  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:39.583  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:39.583  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:39.583  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:39.583  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:39.583  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:39.583  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:39.583  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:39.583  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:39.584  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:39.584  5731  5731 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-01 12:08:39.585  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:39.586  5006  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-01 12:08:39.586  5006  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-01 12:08:39.586  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:39.586  5006  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-01 12:08:39.587  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-01 12:08:39.587  5063  5063 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-01 12:08:39.588  5006  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-01 12:08:39.588  5006  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-01 12:08:39.588  5731  5731 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-01 12:08:39.588  5006  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-01 12:08:39.589  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-01 12:08:39.589  5063  5063 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-01 12:08:39.590  3999  3999 D SystemUpdateService: onCreate
11-01 12:08:39.593  5063  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@be0646e HexData = [00000000ee03000000000000ffffffff]
11-01 12:08:39.593  5063  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-01 12:08:39.593  5063  5082 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-01 12:08:39.594  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-01 12:08:39.594  5006  5023 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-01 12:08:39.594  3999  3999 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-01 12:08:39.595  5063  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@be0646e HexData = [00000000ef03000000000000ffffffff]
11-01 12:08:39.596  5063  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-01 12:08:39.596  5063  5082 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-01 12:08:39.596  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-01 12:08:39.597  5006  5028 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-01 12:08:39.601  3999  5767 I SystemUpdateService: active receiver: enabled
11-01 12:08:39.604  3999  3999 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-01 12:08:39.608  3999  5392 I iu.UploadsManager: num queued entries: 0
,11-01 12:08:39.608  3999  5392 I iu.UploadsManager: num updated entries: 0
11-01 12:08:39.609  3999  5392 I iu.SyncManager: NEXT; no task
,11-01 12:08:39.612  3999  3999 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-01 12:08:39.614  3999  3999 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-01 12:08:39.616  5698  5698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-01 12:08:39.621  5698  5698 D SprintDMHelper: simOperator: 
11-01 12:08:39.621  5698  5698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-01 12:08:39.625   509   920 E Netd    : netlink response contains error (No such file or directory)
11-01 12:08:39.626   926  2994 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-01 12:08:39.628  3999  5767 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-01 12:08:39.629  5731  5731 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-01 12:08:39.631  4500  5771 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-01 12:08:39.635  3999  5767 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-01 12:08:39.635  3999  5767 I SystemUpdateService: now status is 0 (complete)
11-01 12:08:39.635  3999  5767 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-01 12:08:39.635  3999  5767 I SystemUpdateService: file has been verified
11-01 12:08:39.635  3999  5767 I SystemUpdateService: OTA package size = 21989297
,11-01 12:08:39.640  5731  5731 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-01 12:08:39.651  3999  5767 I SystemUpdateService: showing system update notification
,11-01 12:08:39.656   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-01 12:08:39.658  3999  3999 D SystemUpdateService: onDestroy
,11-01 12:08:39.742   926  2992 D wifi    : In wifi stop Hal
,11-01 12:08:39.742  4500  4500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-01 12:08:39.742   926  2992 D wifi    : halHandle = 0x7f5f58f0c0, mVM = 0x7f7bc0d140, mCls = 0x19c6
,11-01 12:08:39.742   926  5730 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-01 12:08:39.742   926  5730 D WifiHAL : Got a signal to exit!!!
11-01 12:08:39.742   926  5730 I WifiHAL : Exit wifi_event_loop
11-01 12:08:39.743   926  2992 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-01 12:08:39.743   926  2992 E WifiHAL : Event processing terminated
11-01 12:08:39.743   926  2992 D wifi    : In wifi cleaned up handler
11-01 12:08:39.743   926  2992 I WifiHAL : Internal cleanup completed
,11-01 12:08:39.745  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:39.745  3714  4203 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-01 12:08:39.747  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:39.749  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:39.773   926  5730 D wifi    : set interface wlan0 flags (DOWN)
,11-01 12:08:39.774   926  2992 D WifiNative-HAL: HAL event thread stopped successfully
,11-01 12:08:39.981   926   943 D Tethering: InitialState.processMessage what=4
,11-01 12:08:39.990   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-01 12:08:40.374   926  2994 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-01 12:08:40.443   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-01 12:08:44.533   926   943 I ActivityManager: Start proc 5773:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-01 12:08:44.623  5773  5773 D AdapterServiceConfig: Adding HeadsetService
,11-01 12:08:44.624  5773  5773 D AdapterServiceConfig: Adding A2dpService
11-01 12:08:44.624  5773  5773 D AdapterServiceConfig: Adding HidService
11-01 12:08:44.624  5773  5773 D AdapterServiceConfig: Adding HealthService
11-01 12:08:44.624  5773  5773 D AdapterServiceConfig: Adding PanService
11-01 12:08:44.624  5773  5773 D AdapterServiceConfig: Adding GattService
,11-01 12:08:44.624  5773  5773 D AdapterServiceConfig: Adding BluetoothMapService
11-01 12:08:44.625  5773  5773 D AdapterServiceConfig: Adding SapService
,11-01 12:08:44.635   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dee5cde:true
,11-01 12:08:44.636  5773  5773 D BluetoothAdapterState: make() - Creating AdapterState
,11-01 12:08:44.639  5773  5773 I bt_bluedroid: init
,11-01 12:08:44.639  5773  5785 I BluetoothAdapterState: Entering OffState
,11-01 12:08:44.641  5773  5786 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-01 12:08:44.641  5773  5786 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-01 12:08:44.641  5773  5786 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-01 12:08:44.641  5773  5786 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-01 12:08:44.642  5773  5773 I bt_bluedroid: get_profile_interface socket
,11-01 12:08:44.643  5773  5789 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-01 12:08:44.644  5773  5773 I bt_bluedroid: get_profile_interface sdp
,11-01 12:08:44.645  5773  5789 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-01 12:08:44.648  5773  5784 I bt_bluedroid: config_hci_snoop_log
,11-01 12:08:44.648   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-01 12:08:44.652  5773  5785 D BluetoothAdapterState: Current state: OFF, message: 0
,11-01 12:08:44.652  5773  5785 D BluetoothAdapterProperties: Setting state to 14
11-01 12:08:44.652  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-01 12:08:44.653  5773  5785 D BluetoothBondStateMachine: make
,11-01 12:08:44.655  5773  5790 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-01 12:08:44.657  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
,11-01 12:08:44.658  5773  5773 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-01 12:08:44.660  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
11-01 12:08:44.660  5773  5773 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-01 12:08:44.661  5773  5773 D BtGatt.GattService: Received start request. Starting profile...
11-01 12:08:44.661  5773  5773 D BtGatt.GattService: start()
11-01 12:08:44.661  5773  5773 I bt_bluedroid: get_profile_interface gatt
,11-01 12:08:44.662  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
,11-01 12:08:44.662  5773  5773 D BtGatt.AdvertiseManager: advertise manager created
,11-01 12:08:44.666  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-01 12:08:44.666  5773  5773 V BluetoothAdapterState: isTurningOn()=false
,11-01 12:08:44.667  5773  5773 V BluetoothAdapterState: isBleTurningOn()=true
11-01 12:08:44.667  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:44.667  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-01 12:08:44.668  5773  5785 I bt_bluedroid: bt_bluedroid
,11-01 12:08:44.668  5773  5786 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-01 12:08:44.669  5773  5786 I bt_hci  : start_up
,11-01 12:08:44.674  5773  5786 I bt_vendor: alloc value 0xf41eb871
11-01 12:08:44.674  5773  5786 I bt_vendor: init
11-01 12:08:44.674  5773  5786 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-01 12:08:44.674  5773  5786 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-01 12:08:44.784  5773  5786 D bt_hci  : start_up starting async portion
,11-01 12:08:44.784  5773  5793 I bt_hci  : event_finish_startup
,11-01 12:08:44.784  5773  5793 I bt_hci_h4: hal_open
11-01 12:08:44.784  5773  5793 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-01 12:08:44.788  5773  5793 I bt_userial_vendor: device fd = 54 open
,11-01 12:08:44.781  5794  5794 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-01 12:08:44.802  5773  5793 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-01 12:08:44.805  5773  5793 D bt_hwcfg: Chipset BCM4358A3
,11-01 12:08:44.805  5773  5793 D bt_hwcfg: Target name = [BCM4358A3]
11-01 12:08:44.805  5773  5793 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-01 12:08:45.208  5773  5793 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-01 12:08:45.208  5773  5793 D bt_hwcfg: Settlement delay -- 100 ms
,11-01 12:08:45.208  5773  5793 I bt_hwcfg: Setting fw settlement delay to 100 
,11-01 12:08:45.344  5773  5793 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-01 12:08:45.344  5773  5793 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-01 12:08:45.346  5773  5793 I bt_hwcfg: vendor lib fwcfg completed
11-01 12:08:45.346  5773  5793 I bt_vendor: firmware callback
11-01 12:08:45.346  5773  5793 I bt_hci  : firmware_config_callback
,11-01 12:08:45.356  5773  5796 I bt_btu  : btu_task pending for preload complete event
,11-01 12:08:45.356  5773  5796 I bt_btu_task: Bluetooth chip preload is complete
,11-01 12:08:45.356  5773  5796 I bt_btu  : btu_task received preload complete event
,11-01 12:08:45.362  5773  5796 I         : BTE_InitTraceLevels -- TRC_HCI
,11-01 12:08:45.362  5773  5796 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-01 12:08:45.363  5773  5796 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-01 12:08:45.363  5773  5796 I         : BTE_InitTraceLevels -- TRC_AVDT
11-01 12:08:45.363  5773  5796 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-01 12:08:45.363  5773  5796 I         : BTE_InitTraceLevels -- TRC_A2D
11-01 12:08:45.363  5773  5796 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-01 12:08:45.363  5773  5796 I         : BTE_InitTraceLevels -- TRC_BTM
11-01 12:08:45.363  5773  5796 I         : BTE_InitTraceLevels -- TRC_GAP
,11-01 12:08:45.364  5773  5796 I         : BTE_InitTraceLevels -- TRC_PAN
11-01 12:08:45.364  5773  5796 I         : BTE_InitTraceLevels -- TRC_SDP
,11-01 12:08:45.364  5773  5796 I         : BTE_InitTraceLevels -- TRC_GATT
11-01 12:08:45.364  5773  5796 I         : BTE_InitTraceLevels -- TRC_SMP
,11-01 12:08:45.364  5773  5796 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-01 12:08:45.364  5773  5796 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-01 12:08:45.449  5773  5796 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4169549
11-01 12:08:45.449  5773  5796 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4169549 
,11-01 12:08:45.460  5773  5789 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-01 12:08:45.462  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-01 12:08:45.462  5773  5789 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-01 12:08:45.466  5773  5789 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-01 12:08:45.472  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
,11-01 12:08:45.472  5773  5789 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-01 12:08:45.472  5773  5789 D bt_hci  : do_postload posting postload work item
11-01 12:08:45.472  5773  5793 I bt_hci  : event_postload
11-01 12:08:45.473  5773  5793 I bt_vendor: sco_config_cb
11-01 12:08:45.473  5773  5793 I bt_hci  : sco_config_callback postload finished.
,11-01 12:08:45.477  5773  5789 D bt_bte_conf: Device ID record 1 : primary
,11-01 12:08:45.477  5773  5789 D bt_bte_conf:   vendorId            = 000f
11-01 12:08:45.477  5773  5789 D bt_bte_conf:   vendorIdSource      = 0001
11-01 12:08:45.477  5773  5789 D bt_bte_conf:   product             = 1200
,11-01 12:08:45.477  5773  5789 D bt_bte_conf:   version             = 1436
11-01 12:08:45.477  5773  5789 D bt_bte_conf:   clientExecutableURL = 
,11-01 12:08:45.477  5773  5789 D bt_bte_conf:   serviceDescription  = 
11-01 12:08:45.477  5773  5789 D bt_bte_conf:   documentationURL    = 
11-01 12:08:45.477  5773  5789 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-01 12:08:45.478  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:45.478  5773  5786 D bt_stack_manager: event_start_up_stack finished
11-01 12:08:45.479  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-01 12:08:45.479  5773  5785 D BluetoothAdapterProperties: Setting state to 15
11-01 12:08:45.479  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-01 12:08:45.480  5773  5785 I BluetoothAdapterState: Entering BleOnState
11-01 12:08:45.483  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:45.487  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:45.488  5773  5785 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-01 12:08:45.488  5773  5785 D BluetoothAdapterProperties: Setting state to 11
11-01 12:08:45.488  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-01 12:08:45.490  5773  5793 I bt_vendor: low_power_mode_cb
,11-01 12:08:45.493  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
11-01 12:08:45.494  5773  5773 D HeadsetService: Received start request. Starting profile...
11-01 12:08:45.495  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:45.498  5773  5773 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-01 12:08:45.498  5773  5773 D HeadsetStateMachine: make
,11-01 12:08:45.500  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:45.502  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:45.510  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
,11-01 12:08:45.510  5773  5773 D HeadsetStateMachine: max_hf_connections = 1
11-01 12:08:45.511  5773  5773 I bt_bluedroid: get_profile_interface handsfree
11-01 12:08:45.511  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-01 12:08:45.511  5773  5789 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
,11-01 12:08:45.514  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
,11-01 12:08:45.515  5773  5773 D A2dpService: Received start request. Starting profile...
,11-01 12:08:45.515  5773  5773 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-01 12:08:45.516  5773  5773 I bt_bluedroid: get_profile_interface avrcp
,11-01 12:08:45.521  5773  5773 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-01 12:08:45.521  5773  5773 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-01 12:08:45.521  5773  5773 D A2dpStateMachine: make
,11-01 12:08:45.522  5773  5773 I bt_bluedroid: get_profile_interface a2dp
,11-01 12:08:45.523  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-01 12:08:45.524  5773  5804 D A2dpStateMachine: Enter Disconnected: -2
,11-01 12:08:45.526  5773  5773 I BluetoothHidServiceJni: classInitNative: succeeds
11-01 12:08:45.527  3598  3598 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-01 12:08:45.527  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
,11-01 12:08:45.529  5660  5660 D BluetoothInputDevice: Proxy object connected
,11-01 12:08:45.530  5773  5773 D HidService: Received start request. Starting profile...
11-01 12:08:45.530  5773  5773 I bt_bluedroid: get_profile_interface hidhost
11-01 12:08:45.530  5773  5773 D HidService: setHidService(): set to: null
11-01 12:08:45.530  5660  5660 D HidProfile: Bluetooth service connected
11-01 12:08:45.531  5773  5773 I BluetoothHealthServiceJni: classInitNative: succeeds
11-01 12:08:45.531  5773  5789 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf414a56d
11-01 12:08:45.531  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-01 12:08:45.531  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
,11-01 12:08:45.532  5773  5773 D HealthService: Received start request. Starting profile...
,11-01 12:08:45.534  5773  5773 I bt_bluedroid: get_profile_interface health
,11-01 12:08:45.534  5773  5773 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-01 12:08:45.535  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
,11-01 12:08:45.536  5660  5660 D BluetoothPan: BluetoothPAN Proxy object connected
,11-01 12:08:45.537  5773  5773 D PanService: Received start request. Starting profile...
11-01 12:08:45.537  5773  5773 D BluetoothPanServiceJni: initializeNative(L110): pan
11-01 12:08:45.537  5773  5773 I bt_bluedroid: get_profile_interface pan
,11-01 12:08:45.538  5773  5789 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-01 12:08:45.542  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
11-01 12:08:45.543  5660  5660 D PanProfile: Bluetooth service connected
11-01 12:08:45.543  5660  5660 D BluetoothMap: Proxy object connected
,11-01 12:08:45.543  5773  5773 D BluetoothMapService: Received start request. Starting profile...
11-01 12:08:45.544  5773  5773 D BluetoothMapService: start()
11-01 12:08:45.544  5660  5660 D MapProfile: Bluetooth service connected
11-01 12:08:45.545  5660  5660 D BluetoothMap: getConnectedDevices()
11-01 12:08:45.545  5660  5660 D BluetoothMap: Bluetooth is Not enabled
,11-01 12:08:45.546  5773  5773 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-01 12:08:45.547  5773  5773 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-01 12:08:45.547  5773  5773 D BluetoothMapAppObserver: createReceiver()
,11-01 12:08:45.548  5773  5773 D BluetoothMapAppObserver: initObservers()
,11-01 12:08:45.549  5773  5773 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-01 12:08:45.554  5773  5773 V SapService: SapBinder()
,11-01 12:08:45.554  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
,11-01 12:08:45.555  5773  5773 D SapService: Received start request. Starting profile...
,11-01 12:08:45.555  5773  5773 V SapService: start()
,11-01 12:08:45.557  5773  5773 V BluetoothAdapterState: isTurningOff()=false
,11-01 12:08:45.557  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-01 12:08:45.557  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:45.557  5773  5802 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
11-01 12:08:45.557  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:45.557  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-01 12:08:45.557  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-01 12:08:45.557  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:45.557  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
,11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isTurningOn()=true
,11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
,11-01 12:08:45.558  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:45.559  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-01 12:08:45.559  5773  5773 V BluetoothAdapterState: isTurningOn()=true
11-01 12:08:45.559  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:45.559  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:45.559  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-01 12:08:45.559  5773  5785 D BluetoothAdapterProperties: ScanMode =  20
11-01 12:08:45.559  5773  5785 D BluetoothAdapterProperties: State =  11
,11-01 12:08:45.560  5773  5789 D BluetoothAdapterProperties: Scan Mode:21
,11-01 12:08:45.561  5773  5789 D BluetoothAdapterProperties: Discoverable Timeout:120
11-01 12:08:45.561  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-01 12:08:45.561  5773  5785 D BluetoothAdapterProperties: Setting state to 12
11-01 12:08:45.561  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-01 12:08:45.562  3148  3160 D BluetoothPbap: onBluetoothStateChange: up=true
11-01 12:08:45.563  5773  5785 I BluetoothAdapterState: Entering OnState
11-01 12:08:45.564  5660  5675 D BluetoothMap: onBluetoothStateChange: up=true
11-01 12:08:45.564  5660  5672 D BluetoothPbap: onBluetoothStateChange: up=true
11-01 12:08:45.565  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:45.565  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:45.565  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:45.565  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:45.565  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:08:45.565  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:45.565  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:45.565  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:45.565   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-01 12:08:45.565   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-01 12:08:45.566   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-01 12:08:45.566  5660  5675 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-01 12:08:45.566  5660  5672 D BluetoothPan: onBluetoothStateChange on: true
11-01 12:08:45.566  3765  3787 D BluetoothHeadset: onBluetoothStateChange: up=true
11-01 12:08:45.566  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:45.567   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-01 12:08:45.567  3148  3159 D BluetoothA2dp: onBluetoothStateChange: up=true
11-01 12:08:45.568   926   926 D BluetoothA2dp: Proxy object connected
,11-01 12:08:45.569  3148  3148 D BluetoothA2dp: Proxy object connected
11-01 12:08:45.569  3148  5738 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-01 12:08:45.571  3148  3997 D BluetoothPan: onBluetoothStateChange on: true
11-01 12:08:45.571  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:45.571  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:45.571  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:45.571  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:45.571  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:08:45.571  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:45.571  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:45.571  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:45.571  3148  3148 D BluetoothInputDevice: Proxy object connected
11-01 12:08:45.571  3148  3148 D HidProfile: Bluetooth service connected
11-01 12:08:45.574  3148  5738 D BluetoothMap: onBluetoothStateChange: up=true
11-01 12:08:45.574  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:45.574  5773  5773 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-01 12:08:45.574  5773  5773 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-01 12:08:45.576  3148  3148 D BluetoothPan: BluetoothPAN Proxy object connected
11-01 12:08:45.576  3148  3148 D PanProfile: Bluetooth service connected
11-01 12:08:45.576  3148  3148 D BluetoothMap: Proxy object connected
11-01 12:08:45.576  3148  3160 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-01 12:08:45.576  3148  3148 D MapProfile: Bluetooth service connected
11-01 12:08:45.576  3148  3148 D BluetoothMap: getConnectedDevices()
11-01 12:08:45.576  5773  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-01 12:08:45.579   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
,11-01 12:08:45.581  5773  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-01 12:08:45.581  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:45.581  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:45.581  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:45.581  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:45.581  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:08:45.581  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:45.581  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:45.581  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:45.582  5773  5773 D ObexServerSockets: Succeed to create listening sockets 
11-01 12:08:45.583  5773  5773 D ObexServerSockets0: startAccept()
11-01 12:08:45.583  5773  5773 D ObexServerSockets0: prepareForNewConnect()
,11-01 12:08:45.583  5660  5660 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-01 12:08:45.583  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:45.583  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-01 12:08:45.584  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:45.585  5773  5773 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-01 12:08:45.585  5773  5773 D BluetoothSdpJni: SDP Create record success - handle: 0
11-01 12:08:45.585  5773  5773 D BluetoothMapService: onReceive
11-01 12:08:45.585  5773  5812 D ObexServerSockets0: Accepting socket connection...
11-01 12:08:45.585  5773  5773 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-01 12:08:45.586  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:45.586  5773  5813 D ObexServerSockets0: Accepting socket connection...
11-01 12:08:45.586  5773  5773 D BluetoothMapService: STATE_ON
11-01 12:08:45.588  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:45.588  5660  5660 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-01 12:08:45.588  5773  5814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-01 12:08:45.589  5773  5814 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-01 12:08:45.589  5773  5814 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-01 12:08:45.594  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-01 12:08:45.597  5660  5660 D BluetoothA2dp: Proxy object connected
,11-01 12:08:45.601  3598  3598 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-01 12:08:45.602  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,11-01 12:08:45.609  5660  5660 D BluetoothPbap: Proxy object connected
11-01 12:08:45.609  5660  5660 D PbapServerProfile: Bluetooth service connected
11-01 12:08:45.610  3148  3148 D BluetoothPbap: Proxy object connected
11-01 12:08:45.610  3148  3148 D PbapServerProfile: Bluetooth service connected
,11-01 12:08:45.612  5773  5773 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-01 12:08:45.612  5773  5773 D ObexServerSockets0: prepareForNewConnect()
,11-01 12:08:45.614  5773  5818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-01 12:08:45.628  5773  5822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-01 12:08:45.629  5773  5822 I BtOppRfcommListener: Accept thread started.
,11-01 12:08:45.667   926   926 D BluetoothHeadset: Proxy object connected
,11-01 12:08:45.667  3765  4021 D BluetoothHeadset: Proxy object connected
11-01 12:08:45.667   926   926 D BluetoothHeadset: Proxy object connected
,11-01 12:08:45.667   926   926 D BluetoothHeadset: Proxy object connected
11-01 12:08:45.667  3148  3997 D BluetoothHeadset: Proxy object connected
,11-01 12:08:45.668  3148  3148 D HeadsetProfile: Bluetooth service connected
,11-01 12:08:45.676  3148  5738 D BluetoothHeadset: Proxy object connected
,11-01 12:08:45.676  3148  3148 D HeadsetProfile: Bluetooth service connected
,11-01 12:08:45.692  5660  5672 D BluetoothHeadset: Proxy object connected
,11-01 12:08:45.693  5660  5660 D HeadsetProfile: Bluetooth service connected
,11-01 12:08:46.301  3655  3852 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-01 12:08:46.301  3655  3852 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-01 12:08:46.329  3598  3598 I ConfigService: onCreate
,11-01 12:08:47.329   926  2994 D ConnectivityService: handlePromptUnvalidated 101
,11-01 12:08:49.507  5773  5785 D BluetoothAdapterState: Current state: ON, message: 23
,11-01 12:08:49.508  5773  5785 D BluetoothAdapterProperties: Setting state to 13
11-01 12:08:49.508  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-01 12:08:49.509  5773  5785 D BluetoothAdapterProperties: onBluetoothDisable()
11-01 12:08:49.510  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
,11-01 12:08:49.515  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
,11-01 12:08:49.515  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-01 12:08:49.518  5773  5773 D BluetoothMapService: onReceive
,11-01 12:08:49.518  5773  5773 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-01 12:08:49.519  5773  5773 D BluetoothMapService: STATE_TURNING_OFF
11-01 12:08:49.519  5773  5773 D BluetoothMapService: MAP Service closeService in
11-01 12:08:49.520  5773  5773 D BluetoothMapMasInstance0: MAP Service shutdown
11-01 12:08:49.520  5773  5773 D ObexServerSockets0: shutdown(block = true)
11-01 12:08:49.521  5773  5812 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-01 12:08:49.521  5773  5773 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-01 12:08:49.522  5773  5773 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-01 12:08:49.522  5773  5798 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-01 12:08:49.522  5773  5813 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-01 12:08:49.526  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:49.526  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:49.526  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:49.526  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:49.526  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:49.526  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:49.526  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:49.526  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:49.526  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-01 12:08:49.530  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:49.531  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-01 12:08:49.535  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-01 12:08:49.535  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:49.535  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:49.535  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:49.535  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:49.535  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:49.535  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:49.535  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:49.535  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:08:49.536  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:49.536  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:08:49.540  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-01 12:08:49.540  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:08:49.540  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:08:49.540  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:08:49.540  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:08:49.540  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-01 12:08:49.540  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:08:49.540  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:08:49.540  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-01 12:08:49.542  5600  5600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-01 12:08:49.542  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-01 12:08:49.544  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:49.546  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:49.548  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:49.549  5773  5773 I BtOppRfcommListener: stopping Accept Thread
11-01 12:08:49.549  5773  5822 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-01 12:08:49.549  5773  5822 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-01 12:08:49.551  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-01 12:08:49.551  5773  5773 D HeadsetService: Received stop request...Stopping profile...
,11-01 12:08:49.555  5660  5675 D BluetoothHeadset: Proxy object disconnected
11-01 12:08:49.555   926   926 D BluetoothHeadset: Proxy object disconnected
11-01 12:08:49.555  3765  3786 D BluetoothHeadset: Proxy object disconnected
11-01 12:08:49.555   926   926 D BluetoothHeadset: Proxy object disconnected
11-01 12:08:49.555   926   926 D BluetoothHeadset: Proxy object disconnected
11-01 12:08:49.555  5773  5773 D A2dpService: Received stop request...Stopping profile...
11-01 12:08:49.556  3148  5738 D BluetoothHeadset: Proxy object disconnected
11-01 12:08:49.556  5773  5804 D A2dpStateMachine: Exit Disconnected: -1
11-01 12:08:49.557  3148  3148 D HeadsetProfile: Bluetooth service disconnected
11-01 12:08:49.558   926   926 D BluetoothA2dp: Proxy object disconnected
11-01 12:08:49.558  3148  3148 D BluetoothA2dp: Proxy object disconnected
,11-01 12:08:49.560  5773  5773 D HidService: Received stop request...Stopping profile...
,11-01 12:08:49.560  5773  5773 D HidService: Stopping Bluetooth HidService
11-01 12:08:49.561  3148  3148 D BluetoothInputDevice: Proxy object disconnected
11-01 12:08:49.561  3148  3148 D HidProfile: Bluetooth service disconnected
,11-01 12:08:49.562  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,11-01 12:08:49.562  5773  5773 D HealthService: Received stop request...Stopping profile...
11-01 12:08:49.563  5660  5660 D HeadsetProfile: Bluetooth service disconnected
11-01 12:08:49.563  5660  5660 D BluetoothA2dp: Proxy object disconnected
11-01 12:08:49.563  5660  5660 D BluetoothInputDevice: Proxy object disconnected
11-01 12:08:49.563  5660  5660 D HidProfile: Bluetooth service disconnected
11-01 12:08:49.563  5773  5773 D PanService: Received stop request...Stopping profile...
11-01 12:08:49.565  5660  5660 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-01 12:08:49.565  5660  5660 D PanProfile: Bluetooth service disconnected
11-01 12:08:49.566  3148  3148 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-01 12:08:49.566  3148  3148 D PanProfile: Bluetooth service disconnected
11-01 12:08:49.566  5773  5773 D BluetoothMapService: Received stop request...Stopping profile...
11-01 12:08:49.566  5773  5773 D BluetoothMapService: stop()
,11-01 12:08:49.567  5773  5773 D BluetoothMapAppObserver: deinitObservers()
,11-01 12:08:49.567  5773  5773 D BluetoothMapAppObserver: removeReceiver()
11-01 12:08:49.569  3148  3148 D BluetoothMap: Proxy object disconnected
11-01 12:08:49.569  3148  3148 D MapProfile: Bluetooth service disconnected
11-01 12:08:49.569  5660  5660 D BluetoothMap: Proxy object disconnected
11-01 12:08:49.569  5660  5660 D MapProfile: Bluetooth service disconnected
,11-01 12:08:49.569  5773  5773 D SapService: Received stop request...Stopping profile...
,11-01 12:08:49.569  5773  5773 V SapService: stop()
11-01 12:08:49.571  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:49.572  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:49.572  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:49.572  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:49.573  5773  5773 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-01 12:08:49.573  5773  5773 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-01 12:08:49.573  5773  5796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:49.573  5773  5796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:49.573  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:49.574  5773  5796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:49.574  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:49.574  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:49.574  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
,11-01 12:08:49.576  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:49.576  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:49.576  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:49.576  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:49.573  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-01 12:08:49.577  5773  5773 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-01 12:08:49.577  5773  5773 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-01 12:08:49.577  5773  5789 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-01 12:08:49.577  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-01 12:08:49.577  5773  5796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:49.577  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:49.577  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-01 12:08:49.577  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:49.577  5773  5796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:49.577  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:49.577  5773  5796 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-01 12:08:49.577  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:49.577  5773  5796 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-01 12:08:49.577  5773  5796 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-01 12:08:49.577  5773  5796 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-01 12:08:49.577  5773  5773 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-01 12:08:49.578  5773  5789 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-01 12:08:49.578  5773  5773 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-01 12:08:49.578  5773  5773 V BluetoothAdapterState: isTurningOff()=true
,11-01 12:08:49.578  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:49.578  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:49.578  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:49.578  3598  3598 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-01 12:08:49.578  5773  5773 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-01 12:08:49.579  5773  5773 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-01 12:08:49.579  5773  5773 D BluetoothMapService: MAP Service closeService in
11-01 12:08:49.579  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:49.579  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:49.579  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
,11-01 12:08:49.579  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:49.580  5773  5773 D BluetoothMapService: cleanup()
11-01 12:08:49.580  5773  5773 D BluetoothMapService: MAP Service closeService in
11-01 12:08:49.580  5773  5773 V BluetoothAdapterState: isTurningOff()=true
11-01 12:08:49.580  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:49.580  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:49.580  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:49.580  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-01 12:08:49.581  5773  5785 D BluetoothAdapterProperties: Setting state to 15
11-01 12:08:49.581  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-01 12:08:49.582  5773  5785 I BluetoothAdapterState: Entering BleOnState
11-01 12:08:49.583  5660  5660 D BluetoothPbap: Proxy object disconnected
11-01 12:08:49.583  5660  5660 D PbapServerProfile: Bluetooth service disconnected
11-01 12:08:49.583  3148  5738 D BluetoothPbap: onBluetoothStateChange: up=false
,11-01 12:08:49.590  5660  5672 D BluetoothMap: onBluetoothStateChange: up=false
11-01 12:08:49.591  5660  5675 D BluetoothPbap: onBluetoothStateChange: up=false
11-01 12:08:49.591   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-01 12:08:49.591  5660  5672 D BluetoothHeadset: onBluetoothStateChange: up=false
11-01 12:08:49.592   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-01 12:08:49.592   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-01 12:08:49.592  5660  5675 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-01 12:08:49.592  5660  5672 D BluetoothPan: onBluetoothStateChange on: false
11-01 12:08:49.593  3765  3787 D BluetoothHeadset: onBluetoothStateChange: up=false
11-01 12:08:49.593   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-01 12:08:49.593  3148  3159 D BluetoothA2dp: onBluetoothStateChange: up=false
11-01 12:08:49.594  3148  3160 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-01 12:08:49.594  3148  3997 D BluetoothPan: onBluetoothStateChange on: false
11-01 12:08:49.595  5660  5675 D BluetoothA2dp: onBluetoothStateChange: up=false
11-01 12:08:49.595  3148  5738 D BluetoothMap: onBluetoothStateChange: up=false
11-01 12:08:49.596  3148  3159 D BluetoothHeadset: onBluetoothStateChange: up=false
11-01 12:08:49.596  5773  5785 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-01 12:08:49.596  5773  5785 D BluetoothAdapterProperties: Setting state to 16
11-01 12:08:49.596  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-01 12:08:49.597  5773  5785 D BluetoothAdapterProperties: onBleDisable
11-01 12:08:49.598  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
11-01 12:08:49.598  5773  5786 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-01 12:08:49.599  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
11-01 12:08:49.599  5773  5796 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-01 12:08:49.599  5773  5796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-01 12:08:49.599  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:49.600  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-01 12:08:49.601  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:49.602  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:49.604  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:49.608  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:49.610  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:08:49.611  3598  3598 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-01 12:08:49.612  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,11-01 12:08:49.805  5773  5789 I bt_hci  : shut_down
,11-01 12:08:49.809  5773  5793 D bt_hwcfg: hw_epilog_process
11-01 12:08:49.809  5773  5793 I bt_vendor: low_power_mode_cb
,11-01 12:08:49.812  5773  5793 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-01 12:08:49.812  5773  5793 I bt_vendor: epilog_cb
11-01 12:08:49.812  5773  5793 I bt_hci  : epilog_finished_callback
,11-01 12:08:49.814  5773  5789 I bt_hci_h4: hal_close
,11-01 12:08:49.814  5773  5789 I bt_userial_vendor: device fd = 54 close
,11-01 12:08:49.924  5773  5786 D bt_stack_manager: event_shut_down_stack finished.
,11-01 12:08:49.925  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-01 12:08:49.929  5773  5785 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-01 12:08:49.930  5773  5773 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-01 12:08:49.931  5773  5773 D BtGatt.GattService: Received stop request...Stopping profile...
,11-01 12:08:49.931  5773  5773 D BtGatt.GattService: stop()
11-01 12:08:49.931  5773  5773 D BtGatt.AdvertiseManager: advertise clients cleared
11-01 12:08:49.934  5773  5773 V BluetoothAdapterState: isTurningOff()=false
11-01 12:08:49.934  5773  5773 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:49.934  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:08:49.934  5773  5773 V BluetoothAdapterState: isBleTurningOff()=true
11-01 12:08:49.934  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-01 12:08:49.935  5773  5785 D BluetoothAdapterProperties: Setting state to 10
11-01 12:08:49.935  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-01 12:08:49.936  5773  5785 I BluetoothAdapterState: Entering OffState
11-01 12:08:49.937   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-01 12:08:49.950  5773  5773 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-01 12:08:49.950  5773  5773 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-01 12:08:49.950  5773  5773 I BluetoothServiceJni: cleanupNative: return from cleanup
11-01 12:08:49.952  5773  5786 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-01 12:08:49.960  5773  5773 I art     : System.exit called, status: 0
,11-01 12:08:49.960  5773  5773 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-01 12:08:49.991   926   937 I ActivityManager: Process com.android.bluetooth (pid 5773) has died
,11-01 12:08:50.444   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:51.356  3598  3598 I ConfigService: onDestroy
,11-01 12:08:51.445   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:52.446   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:53.447   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:54.448   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:08:54.505  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-01 12:08:54.505  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:08:54.509  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:08:54.510  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e7317f removed from the list
,11-01 12:08:54.510  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:54.510  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:08:54.510  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:54.513  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-01 12:08:54.513  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d3c995 added. We now have 4 listener(s)
11-01 12:08:54.513  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:08:54.515  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:08:54.515  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d3c995 removed from the list
,11-01 12:08:54.515  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:08:54.515  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:08:54.515  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:08:54.518  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:08:54.518  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd66aaa added. We now have 4 listener(s)
,11-01 12:08:54.518  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-01 12:08:55.448   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-01 12:08:59.531  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:08:59.564   926   943 I ActivityManager: Start proc 5831:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-01 12:08:59.652  5831  5831 D AdapterServiceConfig: Adding HeadsetService
,11-01 12:08:59.652  5831  5831 D AdapterServiceConfig: Adding A2dpService
11-01 12:08:59.653  5831  5831 D AdapterServiceConfig: Adding HidService
11-01 12:08:59.653  5831  5831 D AdapterServiceConfig: Adding HealthService
11-01 12:08:59.653  5831  5831 D AdapterServiceConfig: Adding PanService
,11-01 12:08:59.653  5831  5831 D AdapterServiceConfig: Adding GattService
11-01 12:08:59.653  5831  5831 D AdapterServiceConfig: Adding BluetoothMapService
11-01 12:08:59.654  5831  5831 D AdapterServiceConfig: Adding SapService
,11-01 12:08:59.664   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bbd0faa:true
,11-01 12:08:59.664  5831  5831 D BluetoothAdapterState: make() - Creating AdapterState
,11-01 12:08:59.667  5831  5831 I bt_bluedroid: init
,11-01 12:08:59.669  5831  5843 I BluetoothAdapterState: Entering OffState
,11-01 12:08:59.671  5831  5844 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-01 12:08:59.671  5831  5844 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-01 12:08:59.671  5831  5844 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-01 12:08:59.671  5831  5844 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-01 12:08:59.672  5831  5831 I bt_bluedroid: get_profile_interface socket
,11-01 12:08:59.674  5831  5847 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-01 12:08:59.674  5831  5831 I bt_bluedroid: get_profile_interface sdp
11-01 12:08:59.675  5831  5847 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-01 12:08:59.679  5831  5842 I bt_bluedroid: config_hci_snoop_log
11-01 12:08:59.680   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-01 12:08:59.684  5831  5843 D BluetoothAdapterState: Current state: OFF, message: 0
11-01 12:08:59.684  5831  5843 D BluetoothAdapterProperties: Setting state to 14
11-01 12:08:59.684  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-01 12:08:59.686  5831  5843 D BluetoothBondStateMachine: make
,11-01 12:08:59.688  5831  5848 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-01 12:08:59.690  5831  5843 I BluetoothAdapterState: Entering PendingCommandState
,11-01 12:08:59.691  5831  5831 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-01 12:08:59.693  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
11-01 12:08:59.694  5831  5831 D BtGatt.DebugUtils: handleDebugAction() action=null
11-01 12:08:59.695  5831  5831 D BtGatt.GattService: Received start request. Starting profile...
11-01 12:08:59.695  5831  5831 D BtGatt.GattService: start()
11-01 12:08:59.695  5831  5831 I bt_bluedroid: get_profile_interface gatt
11-01 12:08:59.696  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
11-01 12:08:59.696  5831  5831 D BtGatt.AdvertiseManager: advertise manager created
,11-01 12:08:59.705  5831  5831 V BluetoothAdapterState: isTurningOff()=false
,11-01 12:08:59.705  5831  5831 V BluetoothAdapterState: isTurningOn()=false
11-01 12:08:59.705  5831  5831 V BluetoothAdapterState: isBleTurningOn()=true
11-01 12:08:59.705  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:08:59.705  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-01 12:08:59.706  5831  5843 I bt_bluedroid: bt_bluedroid
11-01 12:08:59.706  5831  5844 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-01 12:08:59.707  5831  5844 I bt_hci  : start_up
,11-01 12:08:59.712  5831  5844 I bt_vendor: alloc value 0xf41eb871
,11-01 12:08:59.712  5831  5844 I bt_vendor: init
11-01 12:08:59.712  5831  5844 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-01 12:08:59.712  5831  5844 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-01 12:08:59.821  5831  5844 D bt_hci  : start_up starting async portion
,11-01 12:08:59.822  5831  5851 I bt_hci  : event_finish_startup
11-01 12:08:59.822  5831  5851 I bt_hci_h4: hal_open
11-01 12:08:59.822  5831  5851 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-01 12:08:59.821  5852  5852 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-01 12:08:59.825  5831  5851 I bt_userial_vendor: device fd = 54 open
,11-01 12:08:59.840  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-01 12:08:59.843  5831  5851 D bt_hwcfg: Chipset BCM4358A3
,11-01 12:08:59.843  5831  5851 D bt_hwcfg: Target name = [BCM4358A3]
11-01 12:08:59.844  5831  5851 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-01 12:09:00.185  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-01 12:09:00.185  5831  5851 D bt_hwcfg: Settlement delay -- 100 ms
11-01 12:09:00.186  5831  5851 I bt_hwcfg: Setting fw settlement delay to 100 
,11-01 12:09:00.320  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-01 12:09:00.320  5831  5851 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-01 12:09:00.322  5831  5851 I bt_hwcfg: vendor lib fwcfg completed
,11-01 12:09:00.322  5831  5851 I bt_vendor: firmware callback
,11-01 12:09:00.322  5831  5851 I bt_hci  : firmware_config_callback
,11-01 12:09:00.331  5831  5854 I bt_btu  : btu_task pending for preload complete event
,11-01 12:09:00.331  5831  5854 I bt_btu_task: Bluetooth chip preload is complete
11-01 12:09:00.331  5831  5854 I bt_btu  : btu_task received preload complete event
,11-01 12:09:00.338  5831  5854 I         : BTE_InitTraceLevels -- TRC_HCI
,11-01 12:09:00.338  5831  5854 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-01 12:09:00.338  5831  5854 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-01 12:09:00.338  5831  5854 I         : BTE_InitTraceLevels -- TRC_AVDT
11-01 12:09:00.338  5831  5854 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-01 12:09:00.338  5831  5854 I         : BTE_InitTraceLevels -- TRC_A2D
11-01 12:09:00.338  5831  5854 I         : BTE_InitTraceLevels -- TRC_BNEP
11-01 12:09:00.339  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTM
11-01 12:09:00.339  5831  5854 I         : BTE_InitTraceLevels -- TRC_GAP
11-01 12:09:00.339  5831  5854 I         : BTE_InitTraceLevels -- TRC_PAN
,11-01 12:09:00.339  5831  5854 I         : BTE_InitTraceLevels -- TRC_SDP
11-01 12:09:00.339  5831  5854 I         : BTE_InitTraceLevels -- TRC_GATT
11-01 12:09:00.339  5831  5854 I         : BTE_InitTraceLevels -- TRC_SMP
,11-01 12:09:00.339  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-01 12:09:00.339  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-01 12:09:00.424  5831  5854 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4169549
,11-01 12:09:00.424  5831  5854 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4169549 
,11-01 12:09:00.441  5831  5847 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-01 12:09:00.443  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-01 12:09:00.444  5831  5847 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-01 12:09:00.446  5831  5847 D BluetoothAdapterProperties: Name is: Nexus 6P
11-01 12:09:00.449  5831  5847 D BluetoothAdapterProperties: Scan Mode:20
11-01 12:09:00.449  5831  5847 D BluetoothAdapterProperties: Discoverable Timeout:120
11-01 12:09:00.450  5831  5847 D bt_hci  : do_postload posting postload work item
11-01 12:09:00.450  5831  5851 I bt_hci  : event_postload
11-01 12:09:00.450  5831  5851 I bt_vendor: sco_config_cb
11-01 12:09:00.450  5831  5851 I bt_hci  : sco_config_callback postload finished.
11-01 12:09:00.454  5831  5847 D bt_bte_conf: Device ID record 1 : primary
11-01 12:09:00.454  5831  5847 D bt_bte_conf:   vendorId            = 000f
11-01 12:09:00.454  5831  5847 D bt_bte_conf:   vendorIdSource      = 0001
11-01 12:09:00.455  5831  5847 D bt_bte_conf:   product             = 1200
11-01 12:09:00.455  5831  5847 D bt_bte_conf:   version             = 1436
11-01 12:09:00.455  5831  5847 D bt_bte_conf:   clientExecutableURL = 
11-01 12:09:00.455  5831  5847 D bt_bte_conf:   serviceDescription  = 
11-01 12:09:00.455  5831  5847 D bt_bte_conf:   documentationURL    = 
11-01 12:09:00.455  5831  5847 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-01 12:09:00.455  5831  5844 D bt_stack_manager: event_start_up_stack finished
,11-01 12:09:00.456  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-01 12:09:00.457  5831  5851 I bt_vendor: low_power_mode_cb
,11-01 12:09:00.457  5831  5843 D BluetoothAdapterProperties: Setting state to 15
11-01 12:09:00.457  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-01 12:09:00.459  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:00.463  5831  5843 I BluetoothAdapterState: Entering BleOnState
,11-01 12:09:00.465  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:00.466  5831  5843 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-01 12:09:00.467  5831  5843 D BluetoothAdapterProperties: Setting state to 11
11-01 12:09:00.467  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-01 12:09:00.474  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
11-01 12:09:00.475  5831  5831 D HeadsetService: Received start request. Starting profile...
11-01 12:09:00.476  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:00.478  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:00.478  5831  5831 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-01 12:09:00.479  5831  5831 D HeadsetStateMachine: make
,11-01 12:09:00.488  5831  5843 I BluetoothAdapterState: Entering PendingCommandState
,11-01 12:09:00.489  5831  5831 D HeadsetStateMachine: max_hf_connections = 1
11-01 12:09:00.489  5831  5831 I bt_bluedroid: get_profile_interface handsfree
11-01 12:09:00.489  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-01 12:09:00.489  5831  5847 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,11-01 12:09:00.493  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
,11-01 12:09:00.494  5831  5831 D A2dpService: Received start request. Starting profile...
,11-01 12:09:00.494  5831  5831 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-01 12:09:00.495  5831  5831 I bt_bluedroid: get_profile_interface avrcp
,11-01 12:09:00.501  5831  5831 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-01 12:09:00.501  5831  5831 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-01 12:09:00.501  5831  5831 D A2dpStateMachine: make
11-01 12:09:00.502  5831  5831 I bt_bluedroid: get_profile_interface a2dp
,11-01 12:09:00.503  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-01 12:09:00.504  5831  5862 D A2dpStateMachine: Enter Disconnected: -2
,11-01 12:09:00.505  5831  5831 I BluetoothHidServiceJni: classInitNative: succeeds
,11-01 12:09:00.506  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
,11-01 12:09:00.506  5831  5831 D HidService: Received start request. Starting profile...
,11-01 12:09:00.506  5831  5831 I bt_bluedroid: get_profile_interface hidhost
11-01 12:09:00.507  5831  5831 D HidService: setHidService(): set to: null
11-01 12:09:00.507  5831  5847 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf414a56d
,11-01 12:09:00.507  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-01 12:09:00.508  5831  5831 I BluetoothHealthServiceJni: classInitNative: succeeds
11-01 12:09:00.509  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
11-01 12:09:00.509  5831  5831 D HealthService: Received start request. Starting profile...
11-01 12:09:00.510  3598  3598 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-01 12:09:00.511  5831  5831 I bt_bluedroid: get_profile_interface health
11-01 12:09:00.511  5831  5831 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-01 12:09:00.512  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
,11-01 12:09:00.513  5831  5831 D PanService: Received start request. Starting profile...
,11-01 12:09:00.513  5831  5831 D BluetoothPanServiceJni: initializeNative(L110): pan
11-01 12:09:00.513  5831  5831 I bt_bluedroid: get_profile_interface pan
11-01 12:09:00.514  5831  5847 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-01 12:09:00.516  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
,11-01 12:09:00.520  5831  5831 D BluetoothMapService: Received start request. Starting profile...
,11-01 12:09:00.521  5831  5831 D BluetoothMapService: start()
,11-01 12:09:00.524  5831  5831 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-01 12:09:00.524  5831  5831 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-01 12:09:00.525  5831  5831 D BluetoothMapAppObserver: createReceiver()
11-01 12:09:00.526  5831  5831 D BluetoothMapAppObserver: initObservers()
11-01 12:09:00.526  5831  5831 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-01 12:09:00.532  5831  5831 V SapService: SapBinder()
,11-01 12:09:00.532  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
11-01 12:09:00.533  5831  5831 D SapService: Received start request. Starting profile...
11-01 12:09:00.533  5831  5831 V SapService: start()
,11-01 12:09:00.535  5831  5831 V BluetoothAdapterState: isTurningOff()=false
,11-01 12:09:00.535  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-01 12:09:00.535  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:09:00.535  5831  5860 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
11-01 12:09:00.535  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:09:00.535  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-01 12:09:00.535  5831  5831 V BluetoothAdapterState: isTurningOn()=true
,11-01 12:09:00.535  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:09:00.535  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:09:00.536  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-01 12:09:00.536  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-01 12:09:00.536  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:09:00.536  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:09:00.536  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-01 12:09:00.536  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-01 12:09:00.536  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:09:00.536  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:09:00.537  5831  5831 V BluetoothAdapterState: isTurningOff()=false
,11-01 12:09:00.537  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-01 12:09:00.537  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:09:00.537  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:09:00.537  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-01 12:09:00.537  5831  5831 V BluetoothAdapterState: isTurningOn()=true
,11-01 12:09:00.537  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:09:00.537  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:09:00.538  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-01 12:09:00.538  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-01 12:09:00.538  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-01 12:09:00.538  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-01 12:09:00.539  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-01 12:09:00.539  5831  5843 D BluetoothAdapterProperties: ScanMode =  20
11-01 12:09:00.539  5831  5843 D BluetoothAdapterProperties: State =  11
11-01 12:09:00.540  5831  5847 D BluetoothAdapterProperties: Scan Mode:21
11-01 12:09:00.540  5831  5847 D BluetoothAdapterProperties: Discoverable Timeout:120
11-01 12:09:00.541  5831  5843 D BluetoothAdapterProperties: Setting state to 12
11-01 12:09:00.541  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-01 12:09:00.541  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-01 12:09:00.541  5831  5843 I BluetoothAdapterState: Entering OnState
11-01 12:09:00.542  3148  3159 D BluetoothPbap: onBluetoothStateChange: up=true
,11-01 12:09:00.545  5660  5672 D BluetoothMap: onBluetoothStateChange: up=true
,11-01 12:09:00.546  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:09:00.546  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:00.546  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:00.546  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:09:00.546  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:00.546  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:09:00.546  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:09:00.546  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:09:00.546  5660  5675 D BluetoothPbap: onBluetoothStateChange: up=true
11-01 12:09:00.548  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:09:00.548   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-01 12:09:00.548  5660  5672 D BluetoothHeadset: onBluetoothStateChange: up=true
11-01 12:09:00.549   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-01 12:09:00.549   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-01 12:09:00.549  5660  5675 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-01 12:09:00.551  5660  5672 D BluetoothPan: onBluetoothStateChange on: true
11-01 12:09:00.551  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:09:00.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:00.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:00.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:09:00.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:00.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:09:00.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:09:00.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-01 12:09:00.552  5831  5831 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-01 12:09:00.552  3765  4021 D BluetoothHeadset: onBluetoothStateChange: up=true
11-01 12:09:00.552  5831  5831 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-01 12:09:00.553   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-01 12:09:00.553  3148  3160 D BluetoothA2dp: onBluetoothStateChange: up=true
11-01 12:09:00.554  5831  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-01 12:09:00.554  5660  5660 D BluetoothMap: Proxy object connected
11-01 12:09:00.554  5660  5660 D MapProfile: Bluetooth service connected
11-01 12:09:00.554  5660  5660 D BluetoothMap: getConnectedDevices()
11-01 12:09:00.555  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-01 12:09:00.555  3148  3997 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-01 12:09:00.556  5831  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-01 12:09:00.557  3148  3148 D BluetoothInputDevice: Proxy object connected
11-01 12:09:00.557  3148  5738 D BluetoothPan: onBluetoothStateChange on: true
11-01 12:09:00.557  3148  3148 D HidProfile: Bluetooth service connected
11-01 12:09:00.557  5831  5831 D ObexServerSockets: Succeed to create listening sockets 
11-01 12:09:00.558  5831  5831 D ObexServerSockets0: startAccept()
,11-01 12:09:00.558  5831  5831 D ObexServerSockets0: prepareForNewConnect()
11-01 12:09:00.558  5660  5675 D BluetoothA2dp: onBluetoothStateChange: up=true
11-01 12:09:00.560  5831  5831 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-01 12:09:00.560  5831  5831 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-01 12:09:00.561  3148  3160 D BluetoothMap: onBluetoothStateChange: up=true
,11-01 12:09:00.561  5831  5869 D ObexServerSockets0: Accepting socket connection...
11-01 12:09:00.562  5831  5870 D ObexServerSockets0: Accepting socket connection...
11-01 12:09:00.562  5660  5660 D BluetoothInputDevice: Proxy object connected
11-01 12:09:00.562  5660  5660 D HidProfile: Bluetooth service connected
11-01 12:09:00.562  3148  3148 D BluetoothPan: BluetoothPAN Proxy object connected
11-01 12:09:00.562  3148  3148 D PanProfile: Bluetooth service connected
,11-01 12:09:00.566  3148  3148 D BluetoothMap: Proxy object connected
11-01 12:09:00.566  3148  3148 D MapProfile: Bluetooth service connected
11-01 12:09:00.566  3148  3148 D BluetoothMap: getConnectedDevices()
,11-01 12:09:00.566  3148  3997 D BluetoothHeadset: onBluetoothStateChange: up=true
11-01 12:09:00.567  5660  5660 D BluetoothPan: BluetoothPAN Proxy object connected
11-01 12:09:00.567  5660  5660 D PanProfile: Bluetooth service connected
,11-01 12:09:00.570   926   926 D BluetoothA2dp: Proxy object connected
,11-01 12:09:00.571  5660  5660 D BluetoothA2dp: Proxy object connected
11-01 12:09:00.571  3148  3148 D BluetoothA2dp: Proxy object connected
11-01 12:09:00.572  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-01 12:09:00.573  5831  5831 D BluetoothMapService: onReceive
,11-01 12:09:00.573  5831  5831 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-01 12:09:00.573  5831  5831 D BluetoothMapService: STATE_ON
11-01 12:09:00.575   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-01 12:09:00.575  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:00.577  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:00.578  5831  5873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-01 12:09:00.579  5831  5873 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-01 12:09:00.581  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-01 12:09:00.579  5831  5873 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-01 12:09:00.594  5831  5831 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-01 12:09:00.594  5831  5831 D ObexServerSockets0: prepareForNewConnect()
11-01 12:09:00.595  3598  3598 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-01 12:09:00.600  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,11-01 12:09:00.605  5660  5660 D BluetoothPbap: Proxy object connected
,11-01 12:09:00.605  3148  3148 D BluetoothPbap: Proxy object connected
11-01 12:09:00.605  5660  5660 D PbapServerProfile: Bluetooth service connected
11-01 12:09:00.605  3148  3148 D PbapServerProfile: Bluetooth service connected
,11-01 12:09:00.612  5831  5877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-01 12:09:00.627  5831  5881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-01 12:09:00.629  5831  5881 I BtOppRfcommListener: Accept thread started.
,11-01 12:09:00.649  5660  5675 D BluetoothHeadset: Proxy object connected
,11-01 12:09:00.649   926   926 D BluetoothHeadset: Proxy object connected
11-01 12:09:00.649   926   943 D BluetoothHeadset: Proxy object connected
11-01 12:09:00.649   926   943 D BluetoothHeadset: Proxy object connected
11-01 12:09:00.649  3765  3786 D BluetoothHeadset: Proxy object connected
11-01 12:09:00.650   926   926 D BluetoothHeadset: Proxy object connected
11-01 12:09:00.650   926   926 D BluetoothHeadset: Proxy object connected
11-01 12:09:00.650  3148  3160 D BluetoothHeadset: Proxy object connected
11-01 12:09:00.650  3148  3148 D HeadsetProfile: Bluetooth service connected
,11-01 12:09:00.651  5660  5660 D HeadsetProfile: Bluetooth service connected
,11-01 12:09:00.653  3765  3787 D BluetoothHeadset: Proxy object connected
,11-01 12:09:00.666  3148  3159 D BluetoothHeadset: Proxy object connected
,11-01 12:09:00.667  3148  3148 D HeadsetProfile: Bluetooth service connected
,11-01 12:09:02.881  3714  4418 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-01 12:09:04.546  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:09:04.546  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:04.546  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:04.546  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-01 12:09:04.546  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:04.546  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:09:04.546  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:09:04.546  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-01 12:09:04.552  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-01 12:09:04.553  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-01 12:09:04.553  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd66aaa removed from the list
,11-01 12:09:04.553  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-01 12:09:04.553  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:09:04.554  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:04.556  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:04.556  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@547669b added. We now have 4 listener(s)
,11-01 12:09:04.557  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-01 12:09:04.561   926  3614 D WifiService: setWifiEnabled: false pid=5600, uid=10077
,11-01 12:09:04.561   926  3614 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-01 12:09:09.570  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:09.571   926  3762 D WifiService: setWifiEnabled: true pid=5600, uid=10077
11-01 12:09:09.571   926  3762 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-01 12:09:09.584   509   920 D SoftapController: Softap fwReload - Ok
,11-01 12:09:09.588   509   920 D CommandListener: Setting iface cfg
11-01 12:09:09.588   509   920 D CommandListener: Trying to bring down wlan0
11-01 12:09:09.590   509   920 D CommandListener: Clearing all IP addresses on wlan0
,11-01 12:09:09.596   926  2992 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-01 12:09:10.264   926  2992 D wifi    : set interface wlan0 flags (UP)
,11-01 12:09:10.265   926  2992 I WifiHAL : Initializing wifi
11-01 12:09:10.266   926  2992 I WifiHAL : Creating socket
,11-01 12:09:10.273   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-01 12:09:10.276   926  2992 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-01 12:09:10.276   926  2992 D wifi    : Did set static halHandle = 0x7f5f58f0c0
,11-01 12:09:10.276   926  2992 D wifi    : halHandle = 0x7f5f58f0c0, mVM = 0x7f7bc0d140, mCls = 0x187e
,11-01 12:09:10.276   926  2992 D wifi    : array field set
11-01 12:09:10.277   926  2992 I WifiNative-HAL: interface[0] = wlan0
11-01 12:09:10.279   926  5886 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547060510912
,11-01 12:09:10.279   926  5886 D wifi    : waitForHalEvents called, vm = 0x7f7bc0d140, obj = 0x187e, env = 0x7f711aa8c0
,11-01 12:09:10.338  5887  5887 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-01 12:09:10.380   926  2992 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-01 12:09:10.392  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:10.394  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:10.411  5887  5887 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-01 12:09:10.449   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:09:10.470  5887  5887 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-01 12:09:10.471  5887  5887 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-01 12:09:10.491   926  2992 D WifiConfigStore: Loading config and enabling all networks 
11-01 12:09:10.499  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:09:10.499  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:10.499  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:10.499  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:10.499  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:10.499  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:09:10.499  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:09:10.499  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-01 12:09:10.502  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-01 12:09:10.508  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:09:10.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:10.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:10.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:10.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:10.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-01 12:09:10.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-01 12:09:10.508  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-01 12:09:10.512  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-01 12:09:10.520   926  2992 D WifiConfigStore: loaded 0 passpoint configs
,11-01 12:09:10.522   926  2992 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-01 12:09:10.523   926  2992 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-01 12:09:10.524   926  2992 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-01 12:09:10.524   926  2992 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-01 12:09:10.525   926  2992 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-01 12:09:10.526   926  2992 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-01 12:09:10.526   926  2992 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-01 12:09:10.526   926  2992 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-01 12:09:10.526   926  2992 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-01 12:09:10.526   926  2992 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-01 12:09:10.526   926  2992 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-01 12:09:10.526   926  2992 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-01 12:09:10.529   926  2992 D WifiNative-HAL: Setting external_sim to 1
,11-01 12:09:10.529  4500  4500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-01 12:09:10.530   926  2992 D wifi    : setting dfs flag to true, 0x7f5d9db340
11-01 12:09:10.531   926  2992 D WifiStateMachine: Setting OUI to DA-A1-19
11-01 12:09:10.531   926  2992 D wifi    : setting scan oui 0x7f5d9db340
11-01 12:09:10.531   926  2992 D WifiHAL : Sending mac address OUI
,11-01 12:09:10.535   926  2992 E native  : do suspend false
,11-01 12:09:10.547   926  2992 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-01 12:09:10.547   509   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-01 12:09:10.547   926   926 D RttService: SCAN_AVAILABLE : 3
,11-01 12:09:10.548   926  3089 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-01 12:09:10.548   509   920 D CommandListener: Setting iface cfg
,11-01 12:09:10.553   926  2969 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
11-01 12:09:10.553   926  2969 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-01 12:09:10.563   926  2969 D WifiNative-HAL: p2pGetDeviceAddress
,11-01 12:09:10.563   926  2969 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-01 12:09:10.568   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164581 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-01 12:09:11.450   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:09:12.452   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:09:13.453   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:09:13.636  5887  5887 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-01 12:09:13.641  5887  5887 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-01 12:09:13.646  5887  5887 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-01 12:09:13.652  5887  5887 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-01 12:09:13.712   926  2992 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-01 12:09:13.714   926  2992 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-01 12:09:13.715   926  2992 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-01 12:09:13.725   926  2992 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-01 12:09:13.759   926  2992 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-01 12:09:13.765  5887  5887 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-01 12:09:14.188  5887  5887 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-01 12:09:14.230  5887  5887 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-01 12:09:14.231  5887  5887 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-01 12:09:14.239   926  2992 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-01 12:09:14.239   926  2992 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-01 12:09:14.239   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-01 12:09:14.256   926  2992 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-01 12:09:14.268   509   920 D CommandListener: Setting iface cfg
,11-01 12:09:14.273   926  2992 D WifiStateMachine: Start Dhcp Watchdog 3
,11-01 12:09:14.283   926  5892 D DhcpClient: Receive thread started
,11-01 12:09:14.283   926  2994 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-01 12:09:14.284   926  2992 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-01 12:09:14.284   926  2994 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-01 12:09:14.364   926  2992 E native  : do suspend false
,11-01 12:09:14.379   926  5891 D DhcpClient: Broadcasting DHCPDISCOVER
,11-01 12:09:14.393   926  5892 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-01 12:09:14.393   926  5891 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-01 12:09:14.395   926  5891 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-01 12:09:14.408   926  5892 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-01 12:09:14.409   926  5891 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-01 12:09:14.412   509   920 D CommandListener: Setting iface cfg
11-01 12:09:14.416   926  2992 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-01 12:09:14.421   926  5891 D DhcpClient: Scheduling renewal in 86399s
,11-01 12:09:14.429   926  2992 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-01 12:09:14.429   926  2992 D WifiConfigStore: No blacklist allowed without epno enabled
,11-01 12:09:14.430   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-01 12:09:14.433   926  2994 D ConnectivityService: Adding iface wlan0 to network 102
,11-01 12:09:14.444   926  2992 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-01 12:09:14.454   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:09:14.474   926  2994 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-01 12:09:14.474   926  2994 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-01 12:09:14.475   926  2994 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-01 12:09:14.477   926  2994 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-01 12:09:14.478   926  2994 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-01 12:09:14.488   926  2994 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-01 12:09:14.492   926  2994 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-01 12:09:14.492   926  2994 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-01 12:09:14.493   926  2994 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-01 12:09:14.493   926  2992 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-01 12:09:14.493   926  2994 D ConnectivityService:    accepting network in place of null
11-01 12:09:14.493   926  2992 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-01 12:09:14.493   926  2994 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-01 12:09:14.516   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-01 12:09:14.537   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-01 12:09:14.540   926  2994 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-01 12:09:14.540   926  2994 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-01 12:09:14.540  3742  3886 W QCNEJ   : |CORE| network available: 102
11-01 12:09:14.541   926  2994 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-01 12:09:14.542   926   943 D Tethering: MasterInitialState.processMessage what=3
11-01 12:09:14.543  3742  3886 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-01 12:09:14.544  3742  3886 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-01 12:09:14.544  3742  3886 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-01 12:09:14.551  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:09:14.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:14.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:14.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:14.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:14.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:14.551  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:09:14.553  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-01 12:09:14.556  5006  5042 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-01 12:09:14.556  5006  5042 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-01 12:09:14.556  5006  5042 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-01 12:09:14.556  5006  5042 E SarControlService: no key has been found,reset the power
,11-01 12:09:14.556  5006  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-01 12:09:14.557  5006  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-01 12:09:14.557  5006  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-01 12:09:14.557  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-01 12:09:14.557  5063  5063 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-01 12:09:14.558  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:09:14.558  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:14.558  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:14.558  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:14.558  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:14.558  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.558  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:14.558  5600  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:09:14.559  3972  3972 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-01 12:09:14.561  5006  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-01 12:09:14.561  5600  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.561  3999  3999 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-01 12:09:14.566  5063  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@be0646e HexData = [00000000f003000000000000ffffffff]
11-01 12:09:14.566  5063  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-01 12:09:14.566  5063  5082 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,11-01 12:09:14.567  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-01 12:09:14.567  5006  5023 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-01 12:09:14.567  5006  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-01 12:09:14.568  5006  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-01 12:09:14.568  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-01 12:09:14.568  5063  5063 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-01 12:09:14.569  3999  3999 D SystemUpdateService: onCreate
11-01 12:09:14.572  5063  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@be0646e HexData = [00000000f103000000000000ffffffff]
11-01 12:09:14.572  5063  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-01 12:09:14.572  5063  5082 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-01 12:09:14.572  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-01 12:09:14.572  5006  5028 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-01 12:09:14.575  3999  3999 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-01 12:09:14.580   926  5890 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168593, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-01 12:09:14.587  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-01 12:09:14.587  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:14.587  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:14.587  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:14.587  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:14.587  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.587  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:14.587  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:09:14.588  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.589  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.589  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@547669b removed from the list
11-01 12:09:14.589  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:09:14.589  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.589  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:09:14.591  5600  5649 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-01 12:09:14.592  5600  5649 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-01 12:09:14.593  5600  5649 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1599a9b Bundle[{}]
11-01 12:09:14.593  5600  5649 I io.jxcore.node.LifeCycleMonitor: start: OK
11-01 12:09:14.594  5600  5649 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-01 12:09:14.594  5600  5649 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-01 12:09:14.594  5600  5649 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-01 12:09:14.595  5600  5649 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-01 12:09:14.595  5600  5649 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-01 12:09:14.599  5600  5649 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
,11-01 12:09:14.600  5600  5649 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-01 12:09:14.600  5600  5649 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 167)
11-01 12:09:14.602  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:09:14.602  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78c1a38 added. We now have 3 listener(s)
11-01 12:09:14.604  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:09:14.604  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:14.604  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:14.604  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-01 12:09:14.604  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f46a11 added. We now have 4 listener(s)
11-01 12:09:14.604  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:09:14.605  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-01 12:09:14.608  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:09:14.610  3999  3999 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-01 12:09:14.614  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:09:14.614  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:14.614  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:14.614  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:14.614  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:14.614  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.614  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:14.614  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:09:14.620  3999  5902 I SystemUpdateService: active receiver: enabled
11-01 12:09:14.621  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-01 12:09:14.621  3999  5392 I iu.UploadsManager: num queued entries: 0
11-01 12:09:14.621  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:09:14.621  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:09:14.621  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dabd177 added. We now have 4 listener(s)
11-01 12:09:14.621  3999  5392 I iu.UploadsManager: num updated entries: 0
,11-01 12:09:14.622  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:09:14.622  3999  5392 I iu.SyncManager: NEXT; no task
11-01 12:09:14.622  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:14.623  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:14.623  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:14.623  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@504a1e4 added. We now have 5 listener(s)
11-01 12:09:14.623  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:09:14.623  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-01 12:09:14.623  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:14.623  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:09:14.623  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:14.623  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.623  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:09:14.623  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.623  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:14.623  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:14.623  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78c1a38 removed from the list
11-01 12:09:14.623  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.623  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f46a11 removed from the list
,11-01 12:09:14.625  3999  3999 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-01 12:09:14.626  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:14.627  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:09:14.627  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.627  3999  3999 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-01 12:09:14.627  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.627  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.628  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.629  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.629  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.629  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.629  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:14.629  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:14.629  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.629  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f46a11 not in the list
,11-01 12:09:14.629  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.629  5698  5698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-01 12:09:14.630  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.630  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.631  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.631  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.631  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.631  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:14.631  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:14.631  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.631  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@504a1e4 removed from the list
11-01 12:09:14.631  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-01 12:09:14.631  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.631  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.631  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.631  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:14.631  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dabd177 removed from the list
11-01 12:09:14.632  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:09:14.632  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a4964d added. We now have 3 listener(s)
11-01 12:09:14.633  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:09:14.633  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-01 12:09:14.633  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:14.633  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:14.633  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66da502 added. We now have 4 listener(s)
11-01 12:09:14.633  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:09:14.635  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-01 12:09:14.636  5698  5698 D SprintDMHelper: simOperator: 
,11-01 12:09:14.636  5698  5698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-01 12:09:14.639  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:09:14.644  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:09:14.644  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:14.644  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:14.644  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:14.644  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:14.644  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.644  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:14.644  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:09:14.647  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-01 12:09:14.647  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:09:14.647  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:09:14.647  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5bf850 added. We now have 4 listener(s)
,11-01 12:09:14.648  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:09:14.648  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:14.648  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:14.648  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:14.649  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b14a49 added. We now have 5 listener(s)
11-01 12:09:14.649  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-01 12:09:14.649  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:09:14.649  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-01 12:09:14.649  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-01 12:09:14.649  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:09:14.649  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-01 12:09:14.649  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:14.652  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:14.648  3999  5902 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-01 12:09:14.655  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-01 12:09:14.655  5600  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-01 12:09:14.655  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-01 12:09:14.656  3999  5902 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-01 12:09:14.656  3999  5902 I SystemUpdateService: now status is 0 (complete)
11-01 12:09:14.656  3999  5902 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-01 12:09:14.656  3999  5902 I SystemUpdateService: file has been verified
11-01 12:09:14.656  3999  5902 I SystemUpdateService: OTA package size = 21989297
11-01 12:09:14.658  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.658  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-01 12:09:14.659  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-01 12:09:14.659  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-01 12:09:14.662  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.662  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-01 12:09:14.662  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-01 12:09:14.662  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-01 12:09:14.662  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-01 12:09:14.662  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.663  5600  5649 D BluetoothAdapter: STATE_ON
11-01 12:09:14.666   926  5889 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-01 12:09:14.666  5831  5842 D BtGatt.GattService: registerClient() - UUID=ae5d3ba4-7773-4d94-9e7b-dea874886d85
11-01 12:09:14.667  5831  5847 D BtGatt.GattService: onClientRegistered() - UUID=ae5d3ba4-7773-4d94-9e7b-dea874886d85, clientIf=5
11-01 12:09:14.667  5600  5611 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-01 12:09:14.668  5831  5871 D BtGatt.GattService: start scan with filters
,11-01 12:09:14.671  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-01 12:09:14.671  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.672  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-01 12:09:14.672  5831  5850 D BtGatt.ScanManager: handling starting scan
11-01 12:09:14.672  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.672  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-01 12:09:14.672  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-01 12:09:14.672  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.672  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-01 12:09:14.672  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-01 12:09:14.672  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.672  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.672  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-01 12:09:14.673  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-01 12:09:14.673  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.675  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.676  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:09:14.676  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.676  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.676  5600  5649 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-01 12:09:14.676  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-01 12:09:14.676  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:14.676  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-01 12:09:14.676  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.676  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-01 12:09:14.676  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.676  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-01 12:09:14.677  5831  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35cd94c
11-01 12:09:14.679  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.679  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.679  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.679  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.679  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-01 12:09:14.679  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-01 12:09:14.679  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:09:14.679  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-01 12:09:14.679  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.679  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.679  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.679  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-01 12:09:14.679  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.682  5600  5649 D BluetoothAdapter: STATE_ON
,11-01 12:09:14.683  3999  5902 I SystemUpdateService: showing system update notification
,11-01 12:09:14.684  5831  5858 D BtGatt.GattService: stopScan() - queue size =1
,11-01 12:09:14.685  5831  5842 D BtGatt.GattService: unregisterClient() - clientIf=5
11-01 12:09:14.685  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-01 12:09:14.685  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.685  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-01 12:09:14.685  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.685  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.685  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.685  5831  5847 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-01 12:09:14.685  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.685  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.685  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-01 12:09:14.685  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.685  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.686  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.686  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-01 12:09:14.686  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-01 12:09:14.686  5831  5850 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-01 12:09:14.686  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-01 12:09:14.686  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.687  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.687  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:09:14.688  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.688  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.688  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-01 12:09:14.688  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:09:14.688  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-01 12:09:14.688  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-01 12:09:14.688  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-01 12:09:14.688  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-01 12:09:14.688  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.688  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.688  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-01 12:09:14.688  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-01 12:09:14.690  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:09:14.690  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:14.690  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:09:14.690  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:14.690  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.690  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:09:14.690  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.690  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:14.690  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a4964d removed from the list
11-01 12:09:14.690  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.690  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-01 12:09:14.690  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66da502 removed from the list
11-01 12:09:14.690  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.690  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:09:14.690  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.690  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.690  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.690  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:09:14.691  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.691  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.691  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-01 12:09:14.691  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.691  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.691  5831  5850 D BtGatt.ScanManager: Starting BLE batch scan
11-01 12:09:14.691  5831  5850 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-01 12:09:14.692  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.692  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.692  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.692  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:14.692  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:14.692  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.692  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66da502 not in the list
11-01 12:09:14.692  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.692  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.692  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.694  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.694  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.694  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.694  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:14.694  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-01 12:09:14.694  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.694  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b14a49 removed from the list
11-01 12:09:14.694  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:14.694  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.694  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.694  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.694  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:14.694  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5bf850 removed from the list
11-01 12:09:14.695  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:09:14.695  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abb4205 added. We now have 3 listener(s)
11-01 12:09:14.696  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:09:14.696  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:14.696  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:14.696  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:14.697  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b6d25a added. We now have 4 listener(s)
11-01 12:09:14.697  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:09:14.697  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-01 12:09:14.697   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-01 12:09:14.701  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:09:14.701  5831  5847 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-01 12:09:14.701  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-01 12:09:14.705  3999  3999 D SystemUpdateService: onDestroy
11-01 12:09:14.707  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-01 12:09:14.707  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.709  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:09:14.709  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:14.709  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:14.709  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:14.709  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:14.709  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.709  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:14.709  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:09:14.711  3598  5912 I VacuumService: Vacuum at: now=1477998554711 tag=VacuumService
,11-01 12:09:14.713  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-01 12:09:14.713  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:09:14.713  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-01 12:09:14.713  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e568168 added. We now have 4 listener(s)
11-01 12:09:14.714  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-01 12:09:14.714  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.714  5831  5850 D BtGatt.ScanManager: stopping BLe Batch
11-01 12:09:14.715  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:09:14.715  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:14.715  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:14.715  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:14.715  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b2f981 added. We now have 5 listener(s)
11-01 12:09:14.716  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:09:14.716  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:09:14.716  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:09:14.716  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-01 12:09:14.716  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-01 12:09:14.717  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:09:14.717  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-01 12:09:14.717  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:14.720  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-01 12:09:14.720  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-01 12:09:14.720  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-01 12:09:14.721  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:14.723  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-01 12:09:14.723  5600  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-01 12:09:14.723  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-01 12:09:14.724   926  5889 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 01 Nov 2016 11:09:14 GMT], X-Android-Received-Millis=[1477998554723], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477998554695]}
11-01 12:09:14.724   926  2994 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-01 12:09:14.725   926  2994 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-01 12:09:14.725   926  2994 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-01 12:09:14.726  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-01 12:09:14.726  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.726   926  2994 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-01 12:09:14.728  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.728  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-01 12:09:14.729  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-01 12:09:14.729  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-01 12:09:14.734  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.734  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-01 12:09:14.735  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-01 12:09:14.735  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-01 12:09:14.735  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-01 12:09:14.735  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.736  5600  5649 D BluetoothAdapter: STATE_ON
11-01 12:09:14.738  5831  5867 D BtGatt.GattService: registerClient() - UUID=1ed84fc7-d66d-4965-9b22-ed886934dc37
11-01 12:09:14.739  5831  5847 D BtGatt.GattService: onClientRegistered() - UUID=1ed84fc7-d66d-4965-9b22-ed886934dc37, clientIf=5
11-01 12:09:14.739  5600  5611 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-01 12:09:14.739  5831  5842 D BtGatt.GattService: start scan with filters
,11-01 12:09:14.741  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-01 12:09:14.742  5831  5850 D BtGatt.ScanManager: handling starting scan
11-01 12:09:14.742  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.742  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-01 12:09:14.742  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.742  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-01 12:09:14.742  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-01 12:09:14.742  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-01 12:09:14.742  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-01 12:09:14.742  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-01 12:09:14.742  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.742  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.742  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-01 12:09:14.743  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-01 12:09:14.743  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.745  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.745  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:09:14.745  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.745  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.745  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.745  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:09:14.746  5600  5649 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-01 12:09:14.746  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:09:14.746  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:14.746  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:09:14.746  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:14.746  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.746  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-01 12:09:14.746  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.746  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:14.746  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abb4205 removed from the list
11-01 12:09:14.746  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.746  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b6d25a removed from the list
,11-01 12:09:14.746  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-01 12:09:14.746  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:09:14.750  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.750  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.750  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-01 12:09:14.750  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.750  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:09:14.751  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.751  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-01 12:09:14.751  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.751  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-01 12:09:14.751  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.751  3598  5917 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-01 12:09:14.751  5831  5847 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-01 12:09:14.752  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.752  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.752  5831  5850 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-01 12:09:14.752  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.752  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.752  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:14.752  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:14.752  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.752  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b6d25a not in the list
11-01 12:09:14.752  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-01 12:09:14.752  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-01 12:09:14.752  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-01 12:09:14.752  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.752  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.753  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.753  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-01 12:09:14.753  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.753  5600  5649 D BluetoothAdapter: STATE_ON
,11-01 12:09:14.754  5831  5858 D BtGatt.GattService: stopScan() - queue size =1
11-01 12:09:14.755  5831  5871 D BtGatt.GattService: unregisterClient() - clientIf=5
11-01 12:09:14.755  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-01 12:09:14.755  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-01 12:09:14.755  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-01 12:09:14.755  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.755  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.756  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.756  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.756  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-01 12:09:14.756  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.756  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.756  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.756  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-01 12:09:14.756  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-01 12:09:14.757  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.757  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.757  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-01 12:09:14.757  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.757  5831  5850 D BtGatt.ScanManager: Starting BLE batch scan
11-01 12:09:14.757  5831  5850 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-01 12:09:14.758  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.758  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:09:14.758  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.758  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.758  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:14.758  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:14.758  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.759  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b2f981 removed from the list
11-01 12:09:14.759  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:14.759  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.759  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.759  5600  5649, D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.759  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:14.759  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e568168 removed from the list
11-01 12:09:14.760  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:09:14.760  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@714acbd added. We now have 3 listener(s)
11-01 12:09:14.760  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:09:14.760  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:09:14.760  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-01 12:09:14.760  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.760  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-01 12:09:14.760  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-01 12:09:14.761  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.761  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.761  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-01 12:09:14.761  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.761  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:09:14.761  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:14.761  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:14.761  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:14.761  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79d52b2 added. We now have 4 listener(s)
11-01 12:09:14.762  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:09:14.762  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.762  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-01 12:09:14.762  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.762  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.762  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.762  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:09:14.764  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:09:14.771  5831  5847 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-01 12:09:14.771  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.774  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:09:14.774  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:14.774  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:14.774  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:14.774  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:14.774  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.774  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:14.774  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:09:14.775  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-01 12:09:14.775  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.777  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.777  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:09:14.777  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:09:14.777  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc61580 added. We now have 4 listener(s)
11-01 12:09:14.778  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:09:14.778  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:14.778  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:14.778  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:14.778  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e457b9 added. We now have 5 listener(s)
11-01 12:09:14.778  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:14.778  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:09:14.779  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:09:14.779  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-01 12:09:14.779  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-01 12:09:14.779  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:09:14.779  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-01 12:09:14.780  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:14.782  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-01 12:09:14.782  5600  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-01 12:09:14.782  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-01 12:09:14.785  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-01 12:09:14.785  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.786  5831  5850 D BtGatt.ScanManager: stopping BLe Batch
11-01 12:09:14.786  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.786  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-01 12:09:14.787  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-01 12:09:14.787  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-01 12:09:14.790  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.790  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-01 12:09:14.790  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-01 12:09:14.790  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-01 12:09:14.790  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-01 12:09:14.790  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.790  5600  5649 D BluetoothAdapter: STATE_ON
11-01 12:09:14.795  5831  5842 D BtGatt.GattService: registerClient() - UUID=db830dc2-dda3-4d5c-a7b2-e1e3f55953ab
11-01 12:09:14.795  5831  5847 D BtGatt.GattService: onClientRegistered() - UUID=db830dc2-dda3-4d5c-a7b2-e1e3f55953ab, clientIf=5
11-01 12:09:14.795  5600  5610 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-01 12:09:14.796  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-01 12:09:14.796  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.796  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-01 12:09:14.797  3598  5913 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-01 12:09:14.797  5831  5872 D BtGatt.GattService: start scan with filters
11-01 12:09:14.799  3598  5913 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-01 12:09:14.801  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-01 12:09:14.801  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.802  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-01 12:09:14.802  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.802  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-01 12:09:14.802  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.802  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-01 12:09:14.802  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-01 12:09:14.802  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.802  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-01 12:09:14.802  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-01 12:09:14.802  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.802  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.802  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-01 12:09:14.803  5831  5850 D BtGatt.ScanManager: handling starting scan
11-01 12:09:14.804  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-01 12:09:14.804  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.804  4500  5908 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-01 12:09:14.807  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.808  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:09:14.808  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.808  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.808  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.809  5831  5847 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-01 12:09:14.809  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.809  5831  5850 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-01 12:09:14.810  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:09:14.810  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:14.810  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:09:14.810  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:14.810  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.810  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-01 12:09:14.810  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.810  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:14.810  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@714acbd removed from the list
11-01 12:09:14.810  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.810  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79d52b2 removed from the list
11-01 12:09:14.810  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:09:14.810  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:09:14.811  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.811  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-01 12:09:14.811  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.811  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:09:14.811  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.811  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.811  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.811  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.811  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.811  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-01 12:09:14.813  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.813  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.813  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.813  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:14.813  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:14.813  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.813  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79d52b2 not in the list
11-01 12:09:14.813  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-01 12:09:14.813  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-01 12:09:14.813  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-01 12:09:14.814  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.814  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.814  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-01 12:09:14.814  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.814  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.814  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-01 12:09:14.814  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.814  5831  5850 D BtGatt.ScanManager: Starting BLE batch scan
11-01 12:09:14.814  5831  5850 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-01 12:09:14.815  5600  5649 D BluetoothAdapter: STATE_ON
11-01 12:09:14.815  5831  5871 D BtGatt.GattService: stopScan() - queue size =1
11-01 12:09:14.816  5831  5841 D BtGatt.GattService: unregisterClient() - clientIf=5
11-01 12:09:14.816  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-01 12:09:14.816  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.816  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-01 12:09:14.817  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.817  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.817  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.817  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.817  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-01 12:09:14.817  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.817  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.817  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.817  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-01 12:09:14.817  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-01 12:09:14.818  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.818  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.818  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.819  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:09:14.819  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.819  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.819  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:14.819  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:14.819  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.819  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:09:14.819  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e457b9 removed from the list
11-01 12:09:14.819  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:14.819  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:09:14.819  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.819  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.819  5600  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-01 12:09:14.819  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.819  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.819  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:14.819  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-01 12:09:14.819  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc61580 removed from the list
11-01 12:09:14.819  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-01 12:09:14.819  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.819  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.819  5600  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-01 12:09:14.819  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.820  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:09:14.820  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b69b675 added. We now have 3 listener(s)
11-01 12:09:14.820  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.821  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.821  5600  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.821  5600  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:09:14.821  5600  5600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:09:14.821  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:09:14.821  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:14.821  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:14.821  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:14.821  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@518860a added. We now have 4 listener(s)
11-01 12:09:14.821  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:09:14.822  5831  5847 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-01 12:09:14.822  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.823  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-01 12:09:14.826  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:09:14.827  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-01 12:09:14.827  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.833  5600  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:09:14.833  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:14.833  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:14.833  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:14.833  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:14.833  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:14.833  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:14.833  5600  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:09:14.834  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-01 12:09:14.834  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.834  3598  5917 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-01 12:09:14.834  5831  5850 D BtGatt.ScanManager: stopping BLe Batch
11-01 12:09:14.835  5600  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-01 12:09:14.835  5600  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:09:14.836  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:09:14.836  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e11498 added. We now have 4 listener(s)
11-01 12:09:14.838  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-01 12:09:14.838  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:14.838  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:14.838  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:14.838  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:14.838  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ac44f1 added. We now have 5 listener(s)
11-01 12:09:14.838  5600  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:09:14.838  5600  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:09:14.838  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:14.839  5600  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:09:14.839  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:14.839  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.839  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:09:14.839  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.839  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:14.839  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b69b675 removed from the list
11-01 12:09:14.839  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.839  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@518860a removed from the list
11-01 12:09:14.840  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-01 12:09:14.840  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-01 12:09:14.840  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-01 12:09:14.840  5600  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:14.841  5600  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:09:14.841  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.841  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.841  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.841  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.842  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.843  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.843  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.843  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:14.843  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:14.843  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.843  5600  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@518860a not in the list
11-01 12:09:14.843  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.843  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.843  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.844  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.844  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.844  5600  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-01 12:09:14.844  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:14.844  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:14.844  5600  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:14.844  5600  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ac44f1 removed from the list
11-01 12:09:14.844  5600  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:14.844  5600  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:14.844  5600  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:14.844  5600  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:14.844  5600  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:14.845  5600  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e11498 removed from the list
11-01 12:09:14.845  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-01 12:09:14.845  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-01 12:09:14.845  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-01 12:09:14.845  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:09:14.845  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-01 12:09:14.845  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:14.847  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-01 12:09:14.847  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-01 12:09:15.190  5600  5600 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-01 12:09:15.192  3598  5913 W Uploader:  no longer exists, so no auth token.
,11-01 12:09:15.199  3598  5918 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-01 12:09:15.262  5600  5600 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-01 12:09:15.322  5600  5600 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-01 12:09:15.358  3598  5913 W Uploader:  no longer exists, so no auth token.
,11-01 12:09:15.365  3598  5917 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-01 12:09:15.454   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-01 12:09:15.464  3598  5918 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-01 12:09:15.549  3598  5917 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-01 12:09:15.637  3598  5918 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-01 12:09:17.014  5600  5925 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 175, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-01 12:09:17.014  5600  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:17.014  5600  5925 D io.jxcore.node.StreamCopyingThread:  id: 81
,11-01 12:09:17.306   926  2994 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-01 12:09:17.818  5600  5925 W !!      : call onHalfStreamCopied
,11-01 12:09:17.818  5600  5925 I testCopyDataAndClose: closing input stream
,11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 175, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread:  id: 81
,11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread:  id: 81
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 175, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:18.593  5600  5925 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-01 12:09:22.498   926  2994 D ConnectivityService: handlePromptUnvalidated 102
,11-01 12:09:23.142  5600  5926 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: My test thread name). Connection data: Peer properties: [null null].
11-01 12:09:23.142  5600  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:23.142  5600  5926 D io.jxcore.node.StreamCopyingThread:  id: 83
,11-01 12:09:25.142  5600  5649 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 178. Connection data: Peer properties: [null null].
11-01 12:09:25.142  5600  5649 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:25.142  5600  5649 I io.jxcore.node.StreamCopyingThread:  id: 83
11-01 12:09:25.142  5600  5649 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 178, name: My test thread name)
,11-01 12:09:25.214  5600  5926 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
11-01 12:09:25.214  5600  5926 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: My test thread name). Connection data: Peer properties: [null null].
11-01 12:09:25.214  5600  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:25.214  5600  5926 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-01 12:09:25.292  5600  5927 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-01 12:09:25.292  5600  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:25.292  5600  5927 D io.jxcore.node.StreamCopyingThread:  id: 85
,11-01 12:09:25.565   926  2992 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread:  id: 85
,11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread:  id: 85
,11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:26.927  5600  5927 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-01 12:09:31.482  5600  5928 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: My test thread name). Connection data: Peer properties: [null null].
11-01 12:09:31.482  5600  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:31.482  5600  5928 D io.jxcore.node.StreamCopyingThread:  id: 86
,11-01 12:09:31.482  5600  5928 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: My test thread name). Connection data: Peer properties: [null null].
11-01 12:09:31.482  5600  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:31.482  5600  5928 D io.jxcore.node.StreamCopyingThread:  id: 86
11-01 12:09:31.483  5600  5928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-01 12:09:31.483  5600  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:31.483  5600  5928 D io.jxcore.node.StreamCopyingThread:  id: 86
11-01 12:09:31.483  5600  5928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-01 12:09:31.483  5600  5928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-01 12:09:31.483  5600  5928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-01 12:09:31.483  5600  5928 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-01 12:09:31.483  5600  5928 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-01 12:09:31.484  5600  5928 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: My test thread name). Connection data: Peer properties: [null null].
11-01 12:09:31.484  5600  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:31.484  5600  5928 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-01 12:09:31.485  5600  5649 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-01 12:09:31.488  5600  5929 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-01 12:09:31.488  5600  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:31.488  5600  5929 D io.jxcore.node.StreamCopyingThread:  id: 89
,11-01 12:09:31.489  5600  5929 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 186, thread name: My test thread name): Test exception.
11-01 12:09:31.489  5600  5929 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-01 12:09:31.489  5600  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:31.489  5600  5929 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-01 12:09:31.489  5600  5929 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-01 12:09:31.489  5600  5929 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-01 12:09:31.489  5600  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
11-01 12:09:31.489  5600  5929 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-01 12:09:31.493  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-01 12:09:31.493  5600  5649 I jxcore-log: 
11-01 12:09:31.493  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-01 12:09:31.493  5600  5649 I jxcore-log: 
11-01 12:09:31.494  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-01 12:09:31.494  5600  5649 I jxcore-log: 
11-01 12:09:31.494  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-01 12:09:31.494  5600  5649 I jxcore-log: 
,11-01 12:09:31.494  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG UnitTest_app: 'Total duration:  92453'
11-01 12:09:31.494  5600  5649 I jxcore-log: 
,11-01 12:09:31.496  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-01 12:09:31.496  5600  5649 I jxcore-log: 
,11-01 12:09:31.500  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.500  5600  5649 I jxcore-log: 
11-01 12:09:31.501  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.501  5600  5649 I jxcore-log: 
11-01 12:09:31.502  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.502  5600  5649 I jxcore-log: 
11-01 12:09:31.502  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.502  5600  5649 I jxcore-log: 
11-01 12:09:31.502  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-01 12:09:31.502  5600  5649 I jxcore-log: 
,11-01 12:09:31.503  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-01 12:09:31.503  5600  5649 I jxcore-log: 
11-01 12:09:31.503  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-01 12:09:31.503  5600  5649 I jxcore-log: 
11-01 12:09:31.504  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-01 12:09:31.504  5600  5649 I jxcore-log: 
11-01 12:09:31.504  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-01 12:09:31.504  5600  5649 I jxcore-log: 
11-01 12:09:31.504  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.504  5600  5649 I jxcore-log: 
11-01 12:09:31.504  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.504  5600  5649 I jxcore-log: 
,11-01 12:09:31.505  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-01 12:09:31.505  5600  5649 I jxcore-log: 
11-01 12:09:31.505  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-01 12:09:31.505  5600  5649 I jxcore-log: 
11-01 12:09:31.505  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-01 12:09:31.505  5600  5649 I jxcore-log: 
11-01 12:09:31.505  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-01 12:09:31.505  5600  5649 I jxcore-log: 
11-01 12:09:31.505  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-01 12:09:31.505  5600  5649 I jxcore-log: 
,11-01 12:09:31.506  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-01 12:09:31.506  5600  5649 I jxcore-log: 
11-01 12:09:31.506  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-01 12:09:31.506  5600  5649 I jxcore-log: 
,11-01 12:09:31.506  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.506  5600  5649 I jxcore-log: 
11-01 12:09:31.506  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-01 12:09:31.506  5600  5649 I jxcore-log: 
11-01 12:09:31.507  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-01 12:09:31.507  5600  5649 I jxcore-log: 
,11-01 12:09:31.507  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-01 12:09:31.507  5600  5649 I jxcore-log: 
11-01 12:09:31.507  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.507  5600  5649 I jxcore-log: 
11-01 12:09:31.508  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.508  5600  5649 I jxcore-log: 
,11-01 12:09:31.509  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.509  5600  5649 I jxcore-log: 
11-01 12:09:31.510  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.510  5600  5649 I jxcore-log: 
11-01 12:09:31.511  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-01 12:09:31.511  5600  5649 I jxcore-log: 
,11-01 12:09:31.511  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-01 12:09:31.511  5600  5649 I jxcore-log: 
11-01 12:09:31.511  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-01 12:09:31.511  5600  5649 I jxcore-log: 
11-01 12:09:31.511  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.511  5600  5649 I jxcore-log: 
11-01 12:09:31.512  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.512  5600  5649 I jxcore-log: 
11-01 12:09:31.512  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.512  5600  5649 I jxcore-log: 
11-01 12:09:31.512  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.512  5600  5649 I jxcore-log: 
,11-01 12:09:31.512  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.512  5600  5649 I jxcore-log: 
11-01 12:09:31.512  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.512  5600  5649 I jxcore-log: 
11-01 12:09:31.513  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.513  5600  5649 I jxcore-log: 
11-01 12:09:31.513  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.513  5600  5649 I jxcore-log: 
11-01 12:09:31.513  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.513  5600  5649 I jxcore-log: 
,11-01 12:09:31.513  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.513  5600  5649 I jxcore-log: 
11-01 12:09:31.514  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.514  5600  5649 I jxcore-log: 
11-01 12:09:31.514  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.514  5600  5649 I jxcore-log: 
11-01 12:09:31.514  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.514  5600  5649 I jxcore-log: 
11-01 12:09:31.514  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.514  5600  5649 I jxcore-log: 
,11-01 12:09:31.514  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-01 12:09:31.514  5600  5649 I jxcore-log: 
11-01 12:09:31.515  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-01 12:09:31.515  5600  5649 I jxcore-log: 
11-01 12:09:31.515  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-01 12:09:31.515  5600  5649 I jxcore-log: 
11-01 12:09:31.515  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.515  5600  5649 I jxcore-log: 
11-01 12:09:31.515  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.515  5600  5649 I jxcore-log: 
11-01 12:09:31.515  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.515  5600  5649 I jxcore-log: 
11-01 12:09:31.516  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.516  5600  5649 I jxcore-log: 
11-01 12:09:31.516  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.516  5600  5649 I jxcore-log: 
,11-01 12:09:31.516  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:31.516  5600  5649 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-01 12:09:31.516  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.516  5600  5649 I jxcore-log: 
11-01 12:09:31.517  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.517  5600  5649 I jxcore-log: 
11-01 12:09:31.517  5600  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:09:31.517  5600  5649 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-01 12:09:31.517  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-01 12:09:31.517  5600  5649 I jxcore-log: 
11-01 12:09:31.517  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-01 12:09:31.517  5600  5649 I jxcore-log: 
,11-01 12:09:31.518  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-01 12:09:31.518  5600  5649 I jxcore-log: 
11-01 12:09:31.518  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-01 12:09:31.518  5600  5649 I jxcore-log: 
11-01 12:09:31.518  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-01 12:09:31.518  5600  5649 I jxcore-log: 
11-01 12:09:31.518  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-01 12:09:31.518  5600  5649 I jxcore-log: 
11-01 12:09:31.518  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-01 12:09:31.518  5600  5649 I jxcore-log: 
11-01 12:09:31.524  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-01 12:09:31.524  5600  5649 I jxcore-log: 
,11-01 12:09:31.524  5600  5649 I jxcore-log: 2016-11-01 11:09:31 - WARN testUtils: 'myNameCallback not set!'
11-01 12:09:31.524  5600  5649 I jxcore-log: 
11-01 12:09:31.524  5600  5600 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-01 12:09:32.474   926  5890 D NetlinkSocketObserver: NeighborEvent{elapsedMs=186487, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-01 12:09:33.535  5600  5649 I jxcore-log: 2016-11-01 11:09:33 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-01 12:09:33.535  5600  5649 I jxcore-log: 
,11-01 12:09:33.537  5600  5649 I jxcore-log: 2016-11-01 11:09:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-01 12:09:33.537  5600  5649 I jxcore-log: 
,11-01 12:09:33.863  5600  5649 I jxcore-log: 2016-11-01 11:09:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-01 12:09:33.863  5600  5649 I jxcore-log: 
,11-01 12:09:33.876  5600  5649 I jxcore-log: 2016-11-01 11:09:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-01 12:09:33.876  5600  5649 I jxcore-log: 
,11-01 12:09:34.986  5600  5649 I jxcore-log: 2016-11-01 11:09:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-01 12:09:34.986  5600  5649 I jxcore-log: 
,11-01 12:09:35.172  5600  5649 I jxcore-log: 2016-11-01 11:09:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-01 12:09:35.172  5600  5649 I jxcore-log: 
,11-01 12:09:35.177  5600  5649 I jxcore-log: 2016-11-01 11:09:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-01 12:09:35.177  5600  5649 I jxcore-log: 
,11-01 12:09:35.182  5600  5649 I jxcore-log: 2016-11-01 11:09:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-01 12:09:35.182  5600  5649 I jxcore-log: 
,11-01 12:09:35.455   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:09:35.663  5600  5649 I jxcore-log: 2016-11-01 11:09:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-01 12:09:35.663  5600  5649 I jxcore-log: 
,11-01 12:09:35.707  5600  5649 I jxcore-log: 2016-11-01 11:09:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-01 12:09:35.707  5600  5649 I jxcore-log: 
,11-01 12:09:35.720  5600  5649 I jxcore-log: 2016-11-01 11:09:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-01 12:09:35.720  5600  5649 I jxcore-log: 
,11-01 12:09:35.724  5600  5649 I jxcore-log: 2016-11-01 11:09:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-01 12:09:35.724  5600  5649 I jxcore-log: 
,11-01 12:09:36.009  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-01 12:09:36.009  5600  5649 I jxcore-log: 
,11-01 12:09:36.135  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-01 12:09:36.135  5600  5649 I jxcore-log: 
,11-01 12:09:36.456   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:09:36.499  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-01 12:09:36.499  5600  5649 I jxcore-log: 
,11-01 12:09:36.508  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-01 12:09:36.508  5600  5649 I jxcore-log: 
,11-01 12:09:36.512  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-01 12:09:36.512  5600  5649 I jxcore-log: 
,11-01 12:09:36.517  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-01 12:09:36.517  5600  5649 I jxcore-log: 
,11-01 12:09:36.523  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-01 12:09:36.523  5600  5649 I jxcore-log: 
,11-01 12:09:36.551  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-01 12:09:36.551  5600  5649 I jxcore-log: 
,11-01 12:09:36.589  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-01 12:09:36.589  5600  5649 I jxcore-log: 
,11-01 12:09:36.596  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-01 12:09:36.596  5600  5649 I jxcore-log: 
,11-01 12:09:36.603  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-01 12:09:36.603  5600  5649 I jxcore-log: 
,11-01 12:09:36.618  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-01 12:09:36.618  5600  5649 I jxcore-log: 
,11-01 12:09:36.622  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-01 12:09:36.622  5600  5649 I jxcore-log: 
,11-01 12:09:36.628  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-01 12:09:36.628  5600  5649 I jxcore-log: 
,11-01 12:09:36.633  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-01 12:09:36.633  5600  5649 I jxcore-log: 
,11-01 12:09:36.646  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-01 12:09:36.646  5600  5649 I jxcore-log: 
,11-01 12:09:36.652  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-01 12:09:36.652  5600  5649 I jxcore-log: 
,11-01 12:09:36.675  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-01 12:09:36.675  5600  5649 I jxcore-log: 
,11-01 12:09:36.685  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-01 12:09:36.685  5600  5649 I jxcore-log: 
,11-01 12:09:36.697  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-01 12:09:36.697  5600  5649 I jxcore-log: 
,11-01 12:09:36.707  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-01 12:09:36.707  5600  5649 I jxcore-log: 
,11-01 12:09:36.721  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-01 12:09:36.721  5600  5649 I jxcore-log: 
,11-01 12:09:36.731  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-01 12:09:36.731  5600  5649 I jxcore-log: 
,11-01 12:09:36.738  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-01 12:09:36.738  5600  5649 I jxcore-log: 
,11-01 12:09:36.760  5600  5649 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-01 12:09:36.761  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - INFO testUtils: 'BLE multiple advertisement supported'
11-01 12:09:36.761  5600  5649 I jxcore-log: 
,11-01 12:09:36.830  5600  5649 I jxcore-log: 2016-11-01 11:09:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:36.830  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:36.830  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:36.830  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:36.830  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:36.830  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:36.830  5600  5649 I jxcore-log: 
,11-01 12:09:37.140  5600  5649 I jxcore-log: 2016-11-01 11:09:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:37.140  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:37.140  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:37.140  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:37.140  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:37.140  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:37.140  5600  5649 I jxcore-log: 
,11-01 12:09:37.143  5600  5649 I jxcore-log: 2016-11-01 11:09:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:37.143  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:37.143  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:37.143  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:37.143  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:37.143  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:37.143  5600  5649 I jxcore-log: 
,11-01 12:09:37.457   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:09:37.769  5600  5649 I jxcore-log: 2016-11-01 11:09:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:37.769  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:37.769  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:37.769  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:37.769  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:37.769  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:37.769  5600  5649 I jxcore-log: 
,11-01 12:09:37.773  5600  5649 I jxcore-log: 2016-11-01 11:09:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:37.773  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:37.773  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:37.773  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:37.773  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:37.773  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:37.773  5600  5649 I jxcore-log: 
,11-01 12:09:38.458   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:09:38.726  5600  5649 I jxcore-log: 2016-11-01 11:09:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:38.726  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:38.726  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:38.726  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:38.726  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:38.726  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:38.726  5600  5649 I jxcore-log: 
,11-01 12:09:38.731  5600  5649 I jxcore-log: 2016-11-01 11:09:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:38.731  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:38.731  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:38.731  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:38.731  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:38.731  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:38.731  5600  5649 I jxcore-log: 
,11-01 12:09:39.459   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-01 12:09:39.769  5600  5649 I jxcore-log: 2016-11-01 11:09:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:39.769  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:39.769  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:39.769  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:39.769  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:39.769  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:39.769  5600  5649 I jxcore-log: 
,11-01 12:09:39.777  5600  5649 I jxcore-log: 2016-11-01 11:09:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:39.777  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:39.777  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:39.777  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:39.777  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:39.777  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:39.777  5600  5649 I jxcore-log: 
,11-01 12:09:40.460   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-01 12:09:40.821  5600  5649 I jxcore-log: 2016-11-01 11:09:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:40.821  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:40.821  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:40.821  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:40.821  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:40.821  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:40.821  5600  5649 I jxcore-log: 
,11-01 12:09:40.824  5600  5649 I jxcore-log: 2016-11-01 11:09:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:40.824  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:40.824  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:40.824  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:40.824  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:40.824  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:40.824  5600  5649 I jxcore-log: 
,11-01 12:09:41.827   926  5890 D NetlinkSocketObserver: NeighborEvent{elapsedMs=195840, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-01 12:09:43.551  5600  5649 I jxcore-log: 2016-11-01 11:09:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:43.551  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:43.551  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:43.551  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:43.551  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:43.551  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:43.551  5600  5649 I jxcore-log: 
,11-01 12:09:43.556  5600  5649 I jxcore-log: 2016-11-01 11:09:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:43.556  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:43.556  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:43.556  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:43.556  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:43.556  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:43.556  5600  5649 I jxcore-log: 
,11-01 12:09:44.591  5600  5649 I jxcore-log: 2016-11-01 11:09:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:44.591  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:44.591  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:44.591  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:44.591  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:44.591  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:44.591  5600  5649 I jxcore-log: 
,11-01 12:09:44.593  5600  5649 I jxcore-log: 2016-11-01 11:09:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:44.593  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:44.593  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:44.593  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:44.593  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:44.593  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:44.593  5600  5649 I jxcore-log: 
,11-01 12:09:45.633  5600  5649 I jxcore-log: 2016-11-01 11:09:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:45.633  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:45.633  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:45.633  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:45.633  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:45.633  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:45.633  5600  5649 I jxcore-log: 
,11-01 12:09:45.637  5600  5649 I jxcore-log: 2016-11-01 11:09:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:45.637  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:45.637  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:45.637  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:45.637  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:45.637  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:45.637  5600  5649 I jxcore-log: 
,11-01 12:09:46.673  5600  5649 I jxcore-log: 2016-11-01 11:09:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:46.673  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:46.673  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:46.673  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:46.673  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:46.673  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:46.673  5600  5649 I jxcore-log: 
,11-01 12:09:46.677  5600  5649 I jxcore-log: 2016-11-01 11:09:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:46.677  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:46.677  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:46.677  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:46.677  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:46.677  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:46.677  5600  5649 I jxcore-log: 
,11-01 12:09:47.750  5600  5649 I jxcore-log: 2016-11-01 11:09:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:47.750  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:47.750  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:47.750  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:47.750  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:47.750  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:47.750  5600  5649 I jxcore-log: 
,11-01 12:09:47.755  5600  5649 I jxcore-log: 2016-11-01 11:09:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:47.755  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:47.755  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:47.755  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:47.755  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:47.755  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:47.755  5600  5649 I jxcore-log: 
,11-01 12:09:48.801  5600  5649 I jxcore-log: 2016-11-01 11:09:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:48.801  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:48.801  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:48.801  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:48.801  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:48.801  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:48.801  5600  5649 I jxcore-log: 
,11-01 12:09:48.807  5600  5649 I jxcore-log: 2016-11-01 11:09:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:48.807  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:48.807  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:48.807  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:48.807  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:48.807  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:48.807  5600  5649 I jxcore-log: 
,11-01 12:09:49.861  5600  5649 I jxcore-log: 2016-11-01 11:09:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:49.861  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:49.861  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:49.861  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:49.861  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:49.861  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:49.861  5600  5649 I jxcore-log: 
,11-01 12:09:49.864  5600  5649 I jxcore-log: 2016-11-01 11:09:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:49.864  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:49.864  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:49.864  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:49.864  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:49.864  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:49.864  5600  5649 I jxcore-log: 
,11-01 12:09:50.909  5600  5649 I jxcore-log: 2016-11-01 11:09:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:50.909  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:50.909  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:50.909  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:50.909  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:50.909  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:50.909  5600  5649 I jxcore-log: 
,11-01 12:09:50.914  5600  5649 I jxcore-log: 2016-11-01 11:09:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:50.914  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:50.914  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:50.914  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:50.914  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:50.914  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:50.914  5600  5649 I jxcore-log: 
,11-01 12:09:51.946  5600  5649 I jxcore-log: 2016-11-01 11:09:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:51.946  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:51.946  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:51.946  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:51.946  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:51.946  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:51.946  5600  5649 I jxcore-log: 
,11-01 12:09:51.949  5600  5649 I jxcore-log: 2016-11-01 11:09:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:51.949  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:51.949  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:51.949  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:51.949  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:51.949  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:51.949  5600  5649 I jxcore-log: 
,11-01 12:09:53.479  5600  5649 I jxcore-log: 2016-11-01 11:09:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-01 12:09:53.479  5600  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-01 12:09:53.479  5600  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-01 12:09:53.479  5600  5649 I jxcore-log: emit@events.js:82:1
11-01 12:09:53.479  5600  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-01 12:09:53.479  5600  5649 I jxcore-log: emit@events.js:82:1'
11-01 12:09:53.479  5600  5649 I jxcore-log: 
,11-01 12:09:53.491  5600  5649 E jxcore  : Error!: error is undefined
11-01 12:09:53.491  5600  5649 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-01 12:09:53.494  5600  5649 I jxcore-log: 2016-11-01 11:09:53 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-01 12:09:53.494  5600  5649 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-01 12:09:53.494  5600  5649 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-01 12:09:53.494  5600  5649 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-01 12:09:53.494  5600  5649 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-01 12:09:53.494  5600  5649 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-01 12:09:53.494  5600  5649 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-01 12:09:53.494  5600  5649 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
11-01 12:09:53.495  5600  5649 I jxcore-log: 2016-11-01 11:09:53 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-01 12:09:53.495  5600  5649 I jxcore-log: 
,11-01 12:09:53.497  5600  5649 E jxcore-log: TypeError: 
11-01 12:09:53.497  5600  5649 E jxcore-log: error is undefined
11-01 12:09:53.498  5600  5649 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-01 12:09:53.498  5600  5649 E jxcore-log: 
,11-01 12:09:53.602   926  3762 D GraphicsStats: Buffer count: 2
,11-01 12:09:53.602   926   936 I WindowState: WIN DEATH: Window{d01b6ae u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-01 12:09:53.604   926  2993 D WifiService: Client connection lost with reason: 4
,11-01 12:09:53.620   529   529 I Zygote  : Process 5600 exited cleanly (139)
,11-01 12:09:53.624   926  3614 I ActivityManager: Process com.test.thalitest (pid 5600) has died
,11-01 12:09:53.625   926  3614 W ActivityManager: Force removing ActivityRecord{538b377 u0 com.test.thalitest/.MainActivity t68}: app died, no saved state
,11-01 12:09:53.664   937   937 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28767]" dev="sockfs" ino=28767 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-01 12:09:53.664   937   937 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[28767]" dev="sockfs" ino=28767 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-01 12:09:53.666   926   937 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5600 uid 10077
11-01 12:09:53.669  3655  3655 I Keyboard.Facilitator: onFinishInput()
,11-01 12:09:53.721  3972  5935 I MicroRecognitionRnrImpl: Starting detection.
,11-01 12:09:53.724  3972  5936 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@44a13d2
11-01 12:09:53.726   514  5938 I AudioFlinger: AudioFlinger's thread 0xf1c40000 ready to run
,11-01 12:09:53.733   514  3014 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-01 12:09:53.735  3972  5936 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@44a13d2
,11-01 12:09:53.745   514  5938 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-01 12:09:53.745   514  5938 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
,11-01 12:09:53.745   514  5938 I ACDB-LOADER: ACDB AFE returned = -19
11-01 12:09:53.745   514  5938 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-01 12:09:53.745   514  5938 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-01 12:09:53.745   514  5938 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-01 12:09:53.752   514  5938 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-01 12:09:53.830  3972  3972 I HotwordWorkerImpl: onReady
,11-01 12:09:53.922  5930  5930 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-01 12:09:53.942  5930  5930 D AndroidRuntime: CheckJNI is OFF
,11-01 12:09:53.966  5930  5930 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-01 12:09:53.993  5930  5930 I Radio-JNI: register_android_hardware_Radio DONE
,11-01 12:09:54.008  5930  5930 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-01 12:09:54.016   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-01 12:09:54.146   926   951 I art     : Starting a blocking GC Explicit
,11-01 12:09:54.198  3789  4075 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-01 12:09:54.252   926   951 I art     : Explicit concurrent mark sweep GC freed 65425(4MB) AllocSpace objects, 15(504KB) LOS objects, 33% free, 28MB/43MB, paused 1.507ms total 105.514ms
,11-01 12:09:54.271   926   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-01 12:09:54.273  5930  5930 I art     : System.exit called, status: 0
,11-01 12:09:54.273  5930  5930 I AndroidRuntime: VM exiting with result code 0.
,11-01 12:09:54.294   926   951 I ActivityManager: Start proc 5948:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-01 12:09:54.294   926   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-01 12:09:54.303  5831  5831 D BluetoothMapAppObserver: onReceive
,11-01 12:09:54.303  5831  5831 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-01 12:09:54.305  3655  3655 I Keyboard.Facilitator: resetDictionaries() : en_US
11-01 12:09:54.307  3714  4142 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-01 12:09:54.308   926  2958 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-01 12:09:54.322  3655  5960 I Keyboard.Facilitator.DecoderInitializer: run()
,11-01 12:09:54.336  3421  5961 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-01 12:09:54.337  3655  5960 I Decoder : createOrResetDecoder
,11-01 12:09:54.372  3765  3765 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-01 12:09:54.373   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-01 12:09:54.383  3598  3598 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-01 12:09:54.383  3598  3598 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-01 12:09:54.394    29    29 W kworker/3:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-01 12:09:54.400  3598  3598 I ConfigService: onCreate
,11-01 12:09:54.401    29    29 W kworker/3:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-01 12:09:54.411  3999  5968 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-01 12:09:54.411  3999  5968 D AccountUtils: Clearing selected account for com.test.thalitest
,11-01 12:09:54.421  3999  5968 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-01 12:09:54.418    29    29 W kworker/3:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-01 12:09:54.422  3655  5960 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-01 12:09:54.441  3999  5968 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-01 12:09:54.441  3999  5968 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-01 12:09:54.441  3999  5968 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-01 12:09:54.441  3999  5968 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-01 12:09:54.441  3421  5961 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-01 12:09:54.443  3999  5968 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-01 12:09:54.445  3999  3999 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-01 12:09:54.445  3999  3999 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-01 12:09:54.451  3999  5973 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
11-01 12:09:54.451  3421  5961 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-01 12:09:54.451  3421  5961 E AndroidRuntime: Process: android.process.acore, PID: 3421
11-01 12:09:54.451  3421  5961 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-01 12:09:54.451  3421  5961 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-01 12:09:54.451  3999  5973 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-01 12:09:54.453  3999  5973 W SQLiteOpenHelper: Opened metrics.db in read-only mode
11-01 12:09:54.453  3999  5973 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-01 12:09:54.455  3999  5973 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-01 12:09:54.456  3999  5973 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-01 12:09:54.456  3999  3999 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-01 12:09:54.456  3999  3999 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-01 12:09:54.456  3999  5973 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-01 12:09:54.457  3999  5973 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-01 12:09:54.457  3999  5973 E AndroidRuntime: Process: com.google.android.gms, PID: 3999
11-01 12:09:54.457  3999  5973 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-01 12:09:54.457  3999  5973 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: Can't write: system_app_crash
11-01 12:09:54.458   926  5977 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-01 12:09:54.458   926  5977 E DropBoxManagerService: 	... 5 more
11-01 12:09:54.471   950   950 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[31235]" dev="sockfs" ino=31235 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-01 12:09:54.471   950   950 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[31235]" dev="sockfs" ino=31235 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-01 12:09:54.477   926  5980 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-01 12:09:54.474   950   950 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33359]" dev="sockfs" ino=33359 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-01 12:09:54.474   950   950 W Binder_4: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33359]" dev="sockfs" ino=33359 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-01 12:09:54.477   926  2992 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-01 12:09:54.482  3655  5960 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-01 12:09:54.485  3655  5960 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-01 12:09:54.485  3655  5960 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-01 12:09:54.486   926  5981 E DropBoxManagerService: Can't write: system_app_crash
11-01 12:09:54.486   926  5981 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-01 12:09:54.486   926  5981 E DropBoxManagerService: 	... 5 more
11-01 12:09:54.489  3655  5960 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-01 12:09:54.489  3655  5960 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-01 12:09:54.489  3655  5960 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-01 12:09:54.489  3655  5960 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-01 12:09:54.490  3655  5960 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-01 12:09:54.490  3655  5960 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-01 12:09:54.490  3655  5960 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-01 12:09:54.491  3655  5960 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-01 12:09:54.491  3655  5960 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-01 12:09:54.491  3655  5960 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-01 12:09:54.511  3972  5982 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-01 12:09:54.528  3999  5975 W BaseAppContext: Using Auth Proxy for data requests.
,11-01 12:09:54.529  3999  5968 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
,11-01 12:09:54.539   926  3614 I ActivityManager: Start proc 5984:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-01 12:09:54.545  3999  5975 W BaseAppContext: Using Auth Proxy for data requests.
,11-01 12:09:54.547  3999  5989 I GMPM-SVC: App measurement is starting up
,11-01 12:09:54.555  3999  3999 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-01 12:09:54.555  3999  4918 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml.bak
,11-01 12:09:54.556  3999  5989 E GMPM-SVC: AppMeasurementService not registered/enabled
11-01 12:09:54.557  3999  5989 E GMPM-SVC: Uploading is not possible. App measurement disabled
11-01 12:09:54.558  3999  3999 I ConfigFetchService: service connected
11-01 12:09:54.559  3999  5993 I PeopleContactsSync: CP2 sync disabled
11-01 12:09:54.559  3999  5989 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
11-01 12:09:54.560  3999  5989 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
,11-01 12:09:54.560  3999  5989 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-01 12:09:54.560  3999  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-01 12:09:54.561  3999  5989 E GMPM-SVC: Opening the database failed, dropping and recreating it
11-01 12:09:54.561  3999  4254 I Icing   : doRemovePackageData com.test.thalitest
11-01 12:09:54.561  3999  5989 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
11-01 12:09:54.561  3999  5989 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
,11-01 12:09:54.564  3999  5989 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-01 12:09:54.564  3999  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
,11-01 12:09:54.565  3999  5989 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-01 12:09:54.565  3999  5989 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-01 12:09:54.566  3999  5989 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-01 12:09:54.567  3999  4918 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-01 12:09:54.568  3999  4918 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,11-01 12:09:54.568  3999  4918 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-01 12:09:54.568  3999  4918 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-01 12:09:54.568  3999  4918 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-01 12:09:54.568  3999  4918 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-01 12:09:54.569  3999  4918 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,11-01 12:09:54.578   926   939 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{14eff2d u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{5a91757 3999 com.google.android.gms/10012/u0 remote:79b8d6}: process crashing
,11-01 12:09:54.584   926  3807 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3999 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-01 12:09:54.641  3999  5972 W DriveInitializer: Awaiting to be initialized
,11-01 12:09:54.642  3999  5995 W DriveInitializer: Background init thread started
,11-01 12:09:54.806   381   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
