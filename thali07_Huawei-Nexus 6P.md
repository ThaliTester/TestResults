#### Test 909164151d8f644_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-26 22:38:49.540  3883  4139 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,10-26 22:38:49.622  3883  4139 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
10-26 22:38:50.001  5466  5466 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-26 22:38:50.006  5466  5466 D AndroidRuntime: CheckJNI is OFF
10-26 22:38:50.034  5466  5466 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-26 22:38:50.066  5466  5466 I Radio-JNI: register_android_hardware_Radio DONE
10-26 22:38:50.081  5466  5466 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-26 22:38:50.084   928   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-26 22:38:50.104  5466  5466 D AndroidRuntime: Shutting down VM
10-26 22:38:50.114  3864  3876 W SearchService: Abort, client detached.
10-26 22:38:50.124  3864  3864 I HotwordDetector: Closing mic
10-26 22:38:50.124  3864  4132 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c6170c2
10-26 22:38:50.125  3864  4137 E AudioRecord-JNI: Error -4 during AudioRecord native read
10-26 22:38:50.140   928  3316 I ActivityManager: Start proc 5475:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-26 22:38:50.193   515  4140 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
10-26 22:38:50.194   515  4140 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
10-26 22:38:50.200   515  4140 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
10-26 22:38:50.200   515  4140 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
10-26 22:38:50.201   515  2900 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
10-26 22:38:50.203  3864  4134 I MicroRecognitionRnrImpl: Stopping hotword detection.
10-26 22:38:50.204  3864  4136 I MicroRecognitionRnrImpl: Detection finished
10-26 22:38:50.248  5475  5475 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
10-26 22:38:50.266  5475  5475 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-26 22:38:50.333  5475  5475 I LibraryLoader: Time to load native libraries: 59 ms (timestamps 230-289)
,10-26 22:38:50.333  5475  5475 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 22:38:50.369  5475  5475 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2b2e674}
,10-26 22:38:50.369  5475  5475 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-26 22:38:50.369  5475  5475 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-26 22:38:50.372  5475  5475 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-26 22:38:50.373  5475  5475 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-26 22:38:50.432  5475  5475 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-26 22:38:50.449  5475  5475 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 22:38:50.450  5475  5475 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 22:38:50.450  5475  5475 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 22:38:50.450  5475  5475 I Adreno  : Build Date                       : 12/06/15
10-26 22:38:50.450  5475  5475 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 22:38:50.450  5475  5475 I Adreno  : Local Branch                     : mybranch17112971
10-26 22:38:50.450  5475  5475 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 22:38:50.450  5475  5475 I Adreno  : Remote Branch                    : NONE
10-26 22:38:50.450  5475  5475 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 22:38:50.499   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10b8dfa:true
,10-26 22:38:50.538   402   402 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[32804]" dev="sockfs" ino=32804 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:38:50.538   402   402 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32804]" dev="sockfs" ino=32804 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:38:50.555  5475  5475 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-26 22:38:50.564  5475  5475 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-26 22:38:50.595  5475  5512 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-26 22:38:50.591  4113  4113 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32412]" dev="sockfs" ino=32412 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-26 22:38:50.591  4113  4113 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32412]" dev="sockfs" ino=32412 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:38:50.605  5475  5499 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-26 22:38:50.598   938   938 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30572]" dev="sockfs" ino=30572 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:38:50.598   938   938 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30572]" dev="sockfs" ino=30572 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:38:50.638  5475  5512 I OpenGLRenderer: Initialized EGL, version 1.4
,10-26 22:38:50.718  3783  3783 W Binder_C: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32417]" dev="sockfs" ino=32417 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:38:50.718  3783  3783 W Binder_C: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32417]" dev="sockfs" ino=32417 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:38:50.718  3783  3783 W Binder_C: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32416]" dev="sockfs" ino=32416 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:38:50.718  3783  3783 W Binder_C: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32416]" dev="sockfs" ino=32416 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:38:50.723   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +607ms
,10-26 22:38:50.725  3548  3548 I Keyboard.Facilitator: onFinishInput()
,10-26 22:38:50.758  5475  5475 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5475
,10-26 22:38:50.857  5475  5475 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-26 22:38:51.065  5475  5515 D jxcore_app_log: JniHelper::setJavaVM(0xf507c000), pthread_self() = -583530192
,10-26 22:38:51.069  5475  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-26 22:38:51.069  5475  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-26 22:38:51.069  5475  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-26 22:38:51.069  5475  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-26 22:38:51.069  5475  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-26 22:38:51.069  5475  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@809d01b added. We now have 1 listener(s)
,10-26 22:38:51.073  5475  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,10-26 22:38:51.074  5475  5515 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 22:38:51.074  5475  5515 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-26 22:38:51.075  5475  5515 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-26 22:38:51.077  5475  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f71ef6 added. We now have 1 listener(s)
10-26 22:38:51.077  5475  5515 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:38:51.082   928  2857 D WifiService: New client listening to asynchronous messages
,10-26 22:38:51.089  5475  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 22:38:51.089  5475  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,10-26 22:38:51.093  5475  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,10-26 22:38:51.093  5475  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-26 22:38:51.093  5475  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-26 22:38:51.098  5475  5515 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:38:51.099  5475  5515 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,10-26 22:38:51.103  5475  5515 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-26 22:38:51.103  5475  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:38:51.103  5475  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:38:51.103  5475  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:38:51.103  5475  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:38:51.103  5475  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:38:51.103  5475  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:38:51.103  5475  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:38:51.103  5475  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:38:51.103  5475  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-26 22:38:51.103  5475  5515 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:38:51.104  5475  5515 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-26 22:38:51.221  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:38:51.226  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:38:51.233  5475  5475 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-26 22:38:51.580  5475  5484 I art     : Background sticky concurrent mark sweep GC freed 76758(7MB) AllocSpace objects, 17(1096KB) LOS objects, 24% free, 24MB/32MB, paused 1.376ms total 269.251ms
,10-26 22:38:51.739   928  2855 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 22:38:52.251  5475  5484 I art     : Background partial concurrent mark sweep GC freed 59749(6MB) AllocSpace objects, 3(2MB) LOS objects, 37% free, 26MB/42MB, paused 2.060ms total 112.874ms
,10-26 22:38:52.356  5475  5522 W jxcore-log: Initializing JXcore engine
10-26 22:38:52.356  5475  5522 W jxcore-log: JXcore engine is ready
,10-26 22:38:52.381  5522  5522 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11826 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
10-26 22:38:52.381  5522  5522 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15389]" dev="sockfs" ino=15389 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-26 22:38:52.381  5522  5522 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=6259 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-26 22:38:52.381  5522  5522 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30552]" dev="sockfs" ino=30552 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-26 22:38:52.392  5475  5522 W jxcore-log: Starting JXcore engine
,10-26 22:38:52.441  5475  5522 W jxcore-log: Platform android
10-26 22:38:52.441  5475  5522 W jxcore-log: 
,10-26 22:38:52.441  5475  5522 W jxcore-log: Process ARCH arm
10-26 22:38:52.441  5475  5522 W jxcore-log: 
,10-26 22:38:52.618  5475  5522 I jxcore-log: JXcore Cordova bridge is ready!
10-26 22:38:52.618  5475  5522 I jxcore-log: 
,10-26 22:38:52.618  5475  5522 W jxcore-log: JXcore engine is started
,10-26 22:38:52.626  5475  5515 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-26 22:38:52.632  5475  5475 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-26 22:38:53.659  3488  3488 I ConfigService: onDestroy
,10-26 22:38:54.642   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:38:55.135   928  3525 I ActivityManager: Killing 5112:org.codeaurora.ims/1001 (adj 15): empty #17
,10-26 22:38:55.174   928  3525 I ActivityManager: Killing 5022:com.google.android.youtube/u0a75 (adj 15): empty #18
,10-26 22:38:55.643   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:38:56.644   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:38:57.646   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:38:58.647   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:38:59.648   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-26 22:39:02.522  5475  5522 I jxcore-log: 2016-10-26 20:39:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-26 22:39:02.522  5475  5522 I jxcore-log: 
,10-26 22:39:02.524  5475  5522 I jxcore-log: 2016-10-26 20:39:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-26 22:39:02.524  5475  5522 I jxcore-log: 
,10-26 22:39:02.529  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:39:02.529  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:02.529  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:02.529  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:02.529  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:39:02.529  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:02.529  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:02.529  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:39:02.531  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:39:02.534  5475  5522 I jxcore-log: 2016-10-26 20:39:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-26 22:39:02.534  5475  5522 I jxcore-log: 
,10-26 22:39:02.535  5475  5522 I jxcore-log: 2016-10-26 20:39:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-26 22:39:02.535  5475  5522 I jxcore-log: 
,10-26 22:39:02.793  5475  5522 I jxcore-log: 2016-10-26 20:39:02 - DEBUG UnitTest_app: 'Running unit tests'
10-26 22:39:02.793  5475  5522 I jxcore-log: 
,10-26 22:39:02.794  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:39:02.794  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@137df6a added. We now have 2 listener(s)
10-26 22:39:02.795  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:39:02.795  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:39:02.795  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:39:02.795  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:39:02.795  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d89c5b added. We now have 2 listener(s)
10-26 22:39:02.795  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:39:02.796  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 22:39:02.798  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:39:02.801  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:39:02.801  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:02.801  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:02.801  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:02.801  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:39:02.801  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:02.801  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:02.801  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:39:02.802  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:02.802  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:39:02.803  5475  5522 D executeNativeTests: Running unit tests
,10-26 22:39:02.809  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:02.816  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:02.837  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 22:39:02.837  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 added. We now have 3 listener(s)
10-26 22:39:02.838  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:39:02.838  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-26 22:39:02.838  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:39:02.838  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:39:02.838  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 added. We now have 3 listener(s)
10-26 22:39:02.838  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:39:02.838  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 22:39:02.840  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:39:02.842  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:39:02.842  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:02.842  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:02.842  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:02.842  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:39:02.842  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:02.842  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:02.842  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:39:02.843  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:02.843  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-26 22:39:02.845  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 22:39:02.845  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:39:02.845  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:39:02.845  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:39:02.846  5475  5522 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-26 22:39:02.846  5475  5522 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-26 22:39:02.846  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 22:39:02.846  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:39:02.846  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-26 22:39:02.846  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:39:02.846  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:02.847  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:39:02.847  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:02.847  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 22:39:02.847  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:02.847  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-26 22:39:02.847  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:02.847  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-26 22:39:02.847  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 removed from the list
,10-26 22:39:02.847  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:02.847  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 removed from the list
,10-26 22:39:02.850  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:02.850  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:02.850  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:02.850  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:02.850  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:02.850  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.851  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.851  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:02.851  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.851  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:02.851  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:02.851  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:02.851  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:02.852  5475  5522 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-26 22:39:02.852  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:02.852  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:02.853  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:02.853  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 22:39:02.853  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:02.853  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:02.853  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:02.853  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:02.853  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:02.853  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:02.855  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:02.855  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:02.855  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:02.855  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:02.855  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:02.855  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:02.855  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.856  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.856  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.856  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.856  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:02.856  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:02.856  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:02.856  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:02.858  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-26 22:39:02.859  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-26 22:39:02.859  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:02.859  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:02.860  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:02.860  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:02.860  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:02.860  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:02.860  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:02.860  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:02.860  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:02.860  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:02.860  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:02.860  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:02.860  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:02.860  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:02.860  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:02.860  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.860  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.861  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.861  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.861  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:02.861  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:02.861  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:02.861  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:02.861  5475  5522 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-26 22:39:02.862  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:39:02.864  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:39:02.864  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:02.864  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:02.864  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:02.864  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:39:02.864  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:02.864  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:02.864  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:39:02.865  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:02.865  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:39:02.865  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:39:02.865  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 22:39:02.865  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:39:02.865  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:39:02.865  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 22:39:02.869  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 22:39:02.869  5475  5522 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:39:02.869  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 22:39:02.870  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:02.873  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:02.873  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 22:39:02.874  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 22:39:02.874  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 22:39:02.875  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-26 22:39:02.876  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-26 22:39:02.876  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.876  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:39:02.876  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:39:02.876  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:39:02.877  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:39:02.877  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.877  5475  5522 D BluetoothAdapter: STATE_ON
10-26 22:39:02.879  4533  4760 D BtGatt.GattService: registerClient() - UUID=5a9bc3eb-1445-41a6-a432-b2f0dfd2f45e
10-26 22:39:02.880  4533  4612 D BtGatt.GattService: onClientRegistered() - UUID=5a9bc3eb-1445-41a6-a432-b2f0dfd2f45e, clientIf=5
10-26 22:39:02.881  5475  5485 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 22:39:02.882  4533  4546 D BtGatt.GattService: start scan with filters
10-26 22:39:02.888  4533  4617 D BtGatt.ScanManager: handling starting scan
10-26 22:39:02.888  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 22:39:02.888  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.888  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 22:39:02.888  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.888  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.888  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:39:02.888  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:39:02.888  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.888  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.888  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:39:02.888  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.890  4533  4617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
10-26 22:39:02.894  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.894  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:39:02.894  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.894  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.894  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.894  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:39:02.894  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:39:02.895  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:39:02.895  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.897  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.897  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.897  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:02.897  5475  5522 I io.jxcore.node.ConnectionHelper: start: OK
10-26 22:39:02.897  4533  4612 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 22:39:02.898  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:02.898  4533  4617 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 22:39:02.903  4533  4612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-26 22:39:02.904  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:02.904  4533  4617 D BtGatt.ScanManager: Starting BLE batch scan
10-26 22:39:02.904  4533  4617 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 22:39:02.913  4533  4612 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:39:02.913  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:02.919  4533  4612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 22:39:02.919  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:39:03.260  3864  5523 W CronetSyncConnectionRcs: Upload content type not set.
,10-26 22:39:03.323  4733  4790 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-26 22:39:03.324  4733  4733 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-26 22:39:03.396  5475  5475 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-26 22:39:03.396  5475  5475 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:39:03.396  5475  5475 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 22:39:07.901  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 22:39:07.902  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:07.902  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-26 22:39:07.902  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:07.902  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-26 22:39:07.902  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:07.902  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-26 22:39:07.902  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-26 22:39:07.902  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:39:07.902  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-26 22:39:07.904  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.904  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.904  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 22:39:07.905  5475  5522 D BluetoothAdapter: STATE_ON
10-26 22:39:07.906  4533  4546 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:39:07.907  4533  4768 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-26 22:39:07.908  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 22:39:07.909  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.909  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:39:07.909  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.909  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.909  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:39:07.910  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 22:39:07.910  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.910  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.910  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:39:07.911  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:07.914  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.914  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:39:07.914  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.914  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:07.915  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.915  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.915  4533  4533 D BtGatt.ScanManager: awakened up at time 97871
10-26 22:39:07.915  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.916  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 22:39:07.916  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.916  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.916  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:07.916  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 22:39:07.917  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 22:39:07.918  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:39:07.919  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.921  4533  4612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 22:39:07.921  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:39:07.921  4533  4617 D BtGatt.ScanManager: stopping BLe Batch
10-26 22:39:07.922  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.922  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.922  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:07.923  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:39:07.923  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:07.923  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:07.923  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:39:07.923  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:39:07.923  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:39:07.923  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:07.923  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:07.923  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:07.923  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:07.923  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:07.924  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:07.930  4533  4612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 22:39:07.930  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:39:07.931  4533  4617 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 22:39:07.952  4533  4612 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-26 22:39:07.952  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:07.953  4533  4612 D BtGatt.GattService: current time is 97909241009
10-26 22:39:07.953  4533  4612 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -79, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -81, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -75, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-26 22:39:07.955  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-26 22:39:07.956  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-26 22:39:07.956  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
10-26 22:39:07.956  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-26 22:39:07.956  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-26 22:39:08.424  5475  5475 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:39:12.926  5475  5522 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-26 22:39:12.933  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:39:12.943  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:39:12.943  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:12.943  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:12.943  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:12.943  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:39:12.943  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:12.943  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:12.943  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:39:12.948  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:39:12.948  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:39:12.948  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:39:12.949  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-26 22:39:12.949  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:39:12.949  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:39:12.949  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 22:39:12.954  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:12.957  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-26 22:39:12.958  5475  5522 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-26 22:39:12.958  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 22:39:12.959  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:12.966  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 22:39:12.967  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 22:39:12.967  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 22:39:12.972  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:12.973  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:39:12.973  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:39:12.973  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:39:12.973  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:39:12.973  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:12.974  5475  5522 D BluetoothAdapter: STATE_ON
,10-26 22:39:12.978  4533  4768 D BtGatt.GattService: registerClient() - UUID=02bab826-262a-41d0-a8c2-f85364a54e9e
,10-26 22:39:12.979  4533  4612 D BtGatt.GattService: onClientRegistered() - UUID=02bab826-262a-41d0-a8c2-f85364a54e9e, clientIf=5
,10-26 22:39:12.980  5475  5485 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-26 22:39:12.980  4533  4548 D BtGatt.GattService: start scan with filters
,10-26 22:39:12.985  4533  4617 D BtGatt.ScanManager: handling starting scan
10-26 22:39:12.985  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 22:39:12.986  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:12.986  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-26 22:39:12.986  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:12.986  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:12.986  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:39:12.986  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:39:12.986  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:12.987  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:12.987  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:39:12.987  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:12.993  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:12.993  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:39:12.993  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-26 22:39:12.994  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:12.994  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:12.994  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:12.994  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:39:12.996  4533  4612 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 22:39:12.996  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:12.996  4533  4617 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-26 22:39:12.997  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:39:12.997  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.002  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.002  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.002  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.002  5475  5522 I io.jxcore.node.ConnectionHelper: start: OK
10-26 22:39:13.005  4533  4612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 22:39:13.005  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:39:13.005  4533  4617 D BtGatt.ScanManager: Starting BLE batch scan
10-26 22:39:13.005  4533  4617 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 22:39:13.006  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:13.006  5475  5522 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-26 22:39:13.006  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:13.006  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-26 22:39:13.006  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:13.006  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 22:39:13.006  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:13.006  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 22:39:13.006  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:39:13.007  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:39:13.007  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:39:13.007  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.008  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.008  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 22:39:13.009  5475  5522 D BluetoothAdapter: STATE_ON
10-26 22:39:13.009  4533  4768 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:39:13.010  4533  4548 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 22:39:13.011  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 22:39:13.011  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.011  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:39:13.011  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.011  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.011  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:39:13.011  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 22:39:13.011  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.011  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.011  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:39:13.012  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.013  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.013  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-26 22:39:13.014  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.014  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.014  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.014  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.014  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.014  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 22:39:13.014  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.014  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.014  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.014  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 22:39:13.014  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 22:39:13.015  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-26 22:39:13.015  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.016  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.017  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.017  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.017  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 22:39:13.017  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:13.017  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:39:13.017  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:13.017  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
,10-26 22:39:13.017  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:13.017  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:39:13.017  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:13.017  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:39:13.017  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:39:13.017  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:13.018  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:39:13.018  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:13.018  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:13.018  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.020  4533  4612 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:39:13.020  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:39:13.020  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.020  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.021  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.021  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 22:39:13.021  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:13.021  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:13.021  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:13.022  5475  5522 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-26 22:39:13.025  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:39:13.028  4533  4612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-26 22:39:13.028  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:39:13.030  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:39:13.030  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:13.030  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:13.030  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:13.030  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:39:13.030  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:13.030  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:13.030  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:39:13.032  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:13.033  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:39:13.033  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:39:13.033  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 22:39:13.033  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:39:13.033  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:39:13.033  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 22:39:13.035  4533  4612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 22:39:13.035  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:39:13.035  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:13.036  4533  4617 D BtGatt.ScanManager: stopping BLe Batch
10-26 22:39:13.039  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 22:39:13.039  5475  5522 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:39:13.040  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 22:39:13.041  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:13.042  4533  4612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 22:39:13.042  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:13.042  4533  4617 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 22:39:13.046  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 22:39:13.047  4533  4612 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 22:39:13.047  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 22:39:13.048  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:13.048  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 22:39:13.051  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.051  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-26 22:39:13.051  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:39:13.051  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:39:13.051  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:39:13.051  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.051  5475  5522 D BluetoothAdapter: STATE_ON
10-26 22:39:13.053  4533  4768 D BtGatt.GattService: registerClient() - UUID=d42e930f-4b8c-478d-993a-62a5dce66fa5
10-26 22:39:13.053  4533  4612 D BtGatt.GattService: onClientRegistered() - UUID=d42e930f-4b8c-478d-993a-62a5dce66fa5, clientIf=5
10-26 22:39:13.054  5475  5485 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-26 22:39:13.054  4533  4546 D BtGatt.GattService: start scan with filters
,10-26 22:39:13.056  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 22:39:13.056  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.056  4533  4617 D BtGatt.ScanManager: handling starting scan
10-26 22:39:13.056  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 22:39:13.057  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.057  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.057  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:39:13.057  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:39:13.057  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.057  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.057  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-26 22:39:13.057  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.060  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.061  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:39:13.061  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.061  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.061  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.061  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:39:13.061  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:39:13.062  4533  4612 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 22:39:13.062  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:13.062  4533  4617 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 22:39:13.062  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:39:13.062  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:13.064  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.065  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.065  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:13.065  5475  5522 I io.jxcore.node.ConnectionHelper: start: OK
10-26 22:39:13.068  4533  4612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 22:39:13.068  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:13.068  4533  4617 D BtGatt.ScanManager: Starting BLE batch scan
10-26 22:39:13.068  4533  4617 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 22:39:13.076  4533  4612 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:39:13.076  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:39:13.081  4533  4612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-26 22:39:13.081  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:39:13.562  5475  5475 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-26 22:39:13.563  5475  5475 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:39:13.563  5475  5475 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 22:39:18.065  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 22:39:18.065  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:18.066  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 22:39:18.066  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:18.066  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 22:39:18.066  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:18.066  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 22:39:18.066  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-26 22:39:18.067  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-26 22:39:18.067  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:39:18.067  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.068  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:18.068  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 22:39:18.070  5475  5522 D BluetoothAdapter: STATE_ON
10-26 22:39:18.072  4533  4546 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:39:18.074  4533  4760 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-26 22:39:18.075  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-26 22:39:18.075  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.076  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:39:18.076  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.076  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.076  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:39:18.076  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-26 22:39:18.076  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.077  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.078  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:39:18.078  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.079  4533  4533 D BtGatt.ScanManager: awakened up at time 108035
10-26 22:39:18.080   928  3524 I ActivityManager: Killing 5151:com.android.settings/1000 (adj 15): empty #17
,10-26 22:39:18.081  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.081  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:39:18.081  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.082  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.082  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.082  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.082  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.082  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-26 22:39:18.083  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.083  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.083  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.083  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 22:39:18.083  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-26 22:39:18.105  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-26 22:39:18.105  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.106  4533  4612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 22:39:18.106  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:18.106  4533  4617 D BtGatt.ScanManager: stopping BLe Batch
,10-26 22:39:18.109  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.109  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:18.109  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:18.109  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:39:18.109  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:39:18.109  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-26 22:39:18.114  4533  4612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-26 22:39:18.114  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:18.114  4533  4617 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 22:39:18.128  4533  4612 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-26 22:39:18.128  4533  4612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:39:18.128  4533  4612 D BtGatt.GattService: current time is 108084612111
10-26 22:39:18.128  4533  4612 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -77, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -76, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -79, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -79, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-26 22:39:18.128  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-26 22:39:18.129  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-26 22:39:18.129  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-26 22:39:18.129  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-26 22:39:18.129  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-26 22:39:18.129  4533  4612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-26 22:39:18.610  5475  5475 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:39:18.611  5475  5475 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:18.611  5475  5475 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 22:39:23.111  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 22:39:23.111  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:23.111  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 22:39:23.111  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.112  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.112  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:39:23.112  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:39:23.112  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.112  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.112  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:23.113  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.113  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.116  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.116  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:39:23.116  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.122  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.122  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.122  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.123  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:23.123  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:23.123  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.124  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:23.126  5475  5522 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-26 22:39:23.128  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:23.128  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:39:23.128  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:23.128  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.129  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.129  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.129  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:39:23.129  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.129  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.129  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.129  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.129  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.129  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.129  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.130  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:39:23.130  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.132  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.133  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.133  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.133  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:23.133  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:23.133  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.133  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:23.135  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-26 22:39:23.135  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:23.136  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:23.136  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 22:39:23.136  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.136  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.136  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.136  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:23.136  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.136  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.136  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.136  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.136  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.137  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:39:23.137  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.137  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.137  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.139  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.139  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.139  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.139  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:23.139  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 22:39:23.139  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.139  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:23.141  5475  5522 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-26 22:39:23.141  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:23.142  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:39:23.142  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:23.142  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.142  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.142  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.142  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:23.142  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.142  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.142  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.143  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.143  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:23.143  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.143  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.143  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.143  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.146  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.146  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.146  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.146  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:23.146  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:23.146  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.147  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.148  5475  5522 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-26 22:39:23.148  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 22:39:23.148  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:23.148  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:23.149  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.149  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.149  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.149  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:39:23.149  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.149  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.149  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:23.149  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.149  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.149  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.149  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.149  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.150  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.152  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.152  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.152  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.152  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:23.152  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:23.152  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.152  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.153  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 22:39:23.153  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:39:23.153  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-26 22:39:23.153  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 22:39:23.153  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:39:23.153  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:39:23.153  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 22:39:23.154  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:39:23.154  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:39:23.154  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:23.154  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:39:23.154  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:23.154  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.154  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.154  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.154  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:23.154  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.154  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.154  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:23.154  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.154  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.154  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.155  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.155  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.155  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.156  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.156  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.156  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.156  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:23.156  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:23.156  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.156  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.158  5475  5522 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-26 22:39:23.158  5475  5522 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-26 22:39:23.158  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-26 22:39:23.163  5475  5522 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 22:39:23.163  5475  5522 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-26 22:39:23.164  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-26 22:39:23.165  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-26 22:39:23.165  5475  5522 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-26 22:39:23.166  5475  5522 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 22:39:23.166  5475  5522 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-26 22:39:23.166  5475  5522 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 22:39:23.166  5475  5522 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 22:39:23.166  5475  5522 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,10-26 22:39:23.166  5475  5522 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 22:39:23.166  5475  5522 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 22:39:23.166  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-26 22:39:23.170  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-26 22:39:23.172  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-26 22:39:23.172  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-26 22:39:23.173  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-26 22:39:23.173  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-26 22:39:23.173  5475  5522 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-26 22:39:23.173  5475  5522 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 22:39:23.173  5475  5522 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-26 22:39:23.173  5475  5527 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
10-26 22:39:23.173  5475  5527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-26 22:39:23.173  5475  5527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,10-26 22:39:23.173  5475  5527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-26 22:39:23.175  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:23.175  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:23.175  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:23.175  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.175  5475  5527 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-26 22:39:23.175  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.175  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.175  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:23.175  5475  5527 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:39:23.175  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-26 22:39:23.177  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.177  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.177  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.177  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.177  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.177  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.177  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.177  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.178  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.174  4548  4548 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29398]" dev="sockfs" ino=29398 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 22:39:23.174  4548  4548 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29398]" dev="sockfs" ino=29398 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 22:39:23.180  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.180  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.180  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.180  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:23.180  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:23.180  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:39:23.180  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.180  5475  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
,10-26 22:39:23.181  5475  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
10-26 22:39:23.181  5475  5527 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-26 22:39:23.181  5475  5527 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-26 22:39:23.181  5475  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
10-26 22:39:23.181  5475  5527 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,10-26 22:39:23.181  4533  4757 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
10-26 22:39:23.181  5475  5522 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-26 22:39:23.182  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:23.183  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:23.183  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:23.183  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.183  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.183  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.183  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:23.183  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.183  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:39:23.183  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.183  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.183  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.183  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.183  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:23.183  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.184  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.185  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:23.185  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.185  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.185  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:23.185  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:23.185  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.185  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.186  5475  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-26 22:39:23.186  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:23.186  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:23.186  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 22:39:23.186  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.186  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.186  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.186  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:23.186  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.186  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.186  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.186  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.186  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.187  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.187  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:23.187  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.187  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.188  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.188  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.188  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.188  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:23.188  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:23.188  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.188  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.188  5475  5522 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-26 22:39:23.188  5475  5522 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,10-26 22:39:23.189  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 22:39:23.189  5475  5522 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-26 22:39:23.189  5475  5522 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-26 22:39:23.189  5475  5522 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-26 22:39:23.189  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 22:39:23.189  5475  5522 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-26 22:39:23.189  5475  5522 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-26 22:39:23.189  5475  5522 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-26 22:39:23.189  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 22:39:23.189  5475  5522 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-26 22:39:23.189  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:23.189  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:39:23.189  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:23.189  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.189  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.189  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.189  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:23.189  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.189  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.189  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.189  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.190  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.190  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.190  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.190  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.190  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.191  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.191  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.191  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:23.191  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:23.191  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:23.191  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.191  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:23.192  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:23.192  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.192  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:23.192  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:23.192  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:23.192  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:23.192  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:23.192  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:23.192  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:23.192  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:39:24.649   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-26 22:39:24.649   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-26 22:39:28.193  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.193  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:28.194  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:28.194  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.194  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.194  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:28.194  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
,10-26 22:39:28.194  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:28.195  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:28.195  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:28.195  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 22:39:28.195  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.195  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.195  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:28.196  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
,10-26 22:39:28.196  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.196  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:28.196  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:28.196  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:28.196  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.197  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.197  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.197  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:28.200  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:28.201  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.201  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:28.201  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:28.201  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 22:39:28.201  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.202  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:28.207  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-26 22:39:28.208  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:39:28.210  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-26 22:39:28.214  4760  4760 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29400]" dev="sockfs" ino=29400 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 22:39:28.214  4760  4760 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[29400]" dev="sockfs" ino=29400 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-26 22:39:28.211  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-26 22:39:28.212  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-26 22:39:28.212  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-26 22:39:28.212  5475  5529 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-26 22:39:28.213  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-26 22:39:28.213  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 22:39:28.213  5475  5475 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-26 22:39:28.214  5475  5529 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:39:28.214  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:28.214  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-26 22:39:28.215  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-26 22:39:28.215  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-26 22:39:28.215  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:39:28.215  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-26 22:39:28.215  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-26 22:39:28.215  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:28.215  5475  5475 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-26 22:39:28.216  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.216  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:39:28.216  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:39:28.216  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-26 22:39:28.216  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.216  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.216  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.219  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.219  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:39:28.219  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:28.219  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.219  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
,10-26 22:39:28.219  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:39:28.219  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:28.219  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-26 22:39:28.220  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:28.220  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:39:28.220  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:28.220  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:28.220  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:28.220  5475  5529 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-26 22:39:28.220  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.220  5475  5529 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-26 22:39:28.220  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-26 22:39:28.220  5475  5529 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-26 22:39:28.220  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:28.220  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.220  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:28.221  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:28.221  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:28.221  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.221  5475  5475 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-26 22:39:28.221  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.221  5475  5475 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:28.221  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:39:28.221  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.224  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.224  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.224  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.224  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:28.224  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 22:39:28.224  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.225  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:28.226  5475  5522 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-26 22:39:28.227  5475  5522 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-26 22:39:28.227  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-26 22:39:28.227  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:39:28.227  5475  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:39:28.228  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:28.228  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:39:28.228  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 22:39:28.228  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:28.228  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.228  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.228  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:39:28.228  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:28.228  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:39:28.228  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:28.229  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:28.229  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.229  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.229  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:28.229  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.229  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.233  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.236  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.236  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.236  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 22:39:28.236  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:28.236  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.237  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:28.243  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:28.243  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:39:28.243  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:28.243  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:28.243  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.244  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.244  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:39:28.244  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
,10-26 22:39:28.244  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.244  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:28.244  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:28.244  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.244  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.244  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:28.244  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.244  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.246  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.246  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.246  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:39:28.246  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:39:28.246  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:28.246  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.246  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:28.248  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:39:28.248  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:39:28.248  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:39:28.248  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:39:28.248  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.248  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.249  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:39:28.249  5475  5522 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c31f541 not in the list
10-26 22:39:28.249  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.249  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:28.249  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:28.249  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.249  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:39:28.249  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:28.249  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:28.249  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.251  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.251  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.251  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:39:28.251  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 22:39:28.251  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:39:28.251  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:28.251  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b456ae6 not in the list
10-26 22:39:28.253  5475  5522 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-26 22:39:28.253  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 22:39:28.255  5475  5522 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,10-26 22:39:28.256  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 22:39:28.256  5475  5522 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-26 22:39:28.256  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 22:39:28.260  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-26 22:39:28.260  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,10-26 22:39:28.261  5475  5522 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-26 22:39:28.261  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-26 22:39:28.261  5475  5522 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-26 22:39:28.261  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-26 22:39:28.261  5475  5522 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-26 22:39:28.261  5475  5522 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-26 22:39:28.262  5475  5522 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-26 22:39:28.262  5475  5522 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,10-26 22:39:28.262  5475  5522 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-26 22:39:28.262  5475  5522 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-26 22:39:28.263  5475  5522 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-26 22:39:28.263  5475  5522 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-26 22:39:28.264  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:39:28.264  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ffdd758 added. We now have 3 listener(s)
,10-26 22:39:28.264  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:39:28.266  5475  5522 D BluetoothAdapter: enable(): BT is already enabled..!
10-26 22:39:28.266   928  3032 D WifiService: setWifiEnabled: true pid=5475, uid=10077
10-26 22:39:28.266   928  3032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:39:28.304  4533  4724 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-26 22:39:28.305  4533  4724 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-26 22:39:28.720  5475  5475 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:39:29.650   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:30.651   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:31.652   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:31.745   928  2855 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 22:39:32.653   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:32.921   928  5245 D NetlinkSocketObserver: NeighborEvent{elapsedMs=122877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-26 22:39:33.272  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:39:33.272  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc1b0b1 added. We now have 4 listener(s)
,10-26 22:39:33.272  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:39:33.285  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:39:33.285  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc1b0b1 removed from the list
,10-26 22:39:33.285  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:39:33.285  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:33.285  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:39:33.287  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:39:33.287  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c345996 added. We now have 4 listener(s)
,10-26 22:39:33.288  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:39:33.290  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:39:33.290  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c345996 removed from the list
,10-26 22:39:33.290  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:39:33.291  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:33.291  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:33.292  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:39:33.292  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59a0917 added. We now have 4 listener(s)
10-26 22:39:33.292  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:39:33.297   928  3060 D WifiService: setWifiEnabled: false pid=5475, uid=10077
10-26 22:39:33.297   928  3060 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:39:33.304   928  2855 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-26 22:39:33.304   928  2855 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-26 22:39:33.305   928  2855 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 22:39:33.305   928  2855 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-26 22:39:33.310  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:39:33.311  4533  4608 D BluetoothAdapterState: Current state: ON, message: 23
10-26 22:39:33.311  4533  4608 D BluetoothAdapterProperties: Setting state to 13
10-26 22:39:33.311  4533  4608 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-26 22:39:33.312  4533  4608 D BluetoothAdapterProperties: onBluetoothDisable()
10-26 22:39:33.315  4533  4608 I BluetoothAdapterState: Entering PendingCommandState
10-26 22:39:33.315  4533  4612 D BluetoothAdapterProperties: Scan Mode:20
10-26 22:39:33.317  4533  4608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-26 22:39:33.321  4533  4533 D BluetoothMapService: onReceive
,10-26 22:39:33.321  4533  4533 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 22:39:33.321  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.322  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:39:33.322  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.322  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.322  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:33.322  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.322  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:33.322  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:33.322  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:39:33.321  4533  4533 D BluetoothMapService: STATE_TURNING_OFF
10-26 22:39:33.323  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.324  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:33.324  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:39:33.325  4533  4533 D BluetoothMapService: MAP Service closeService in
10-26 22:39:33.325  4533  4533 D BluetoothMapMasInstance0: MAP Service shutdown
10-26 22:39:33.325  4533  4533 D ObexServerSockets0: shutdown(block = true)
10-26 22:39:33.326  4533  4533 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 22:39:33.326  4533  4533 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 22:39:33.326  4533  4757 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-26 22:39:33.327  4533  4771 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-26 22:39:33.327  4533  4770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-26 22:39:33.329  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:33.329   928  5246 D DhcpClient: Clearing IP address
10-26 22:39:33.329   510   921 D CommandListener: Clearing all IP addresses on wlan0
,10-26 22:39:33.330  4533  4533 I BtOppRfcommListener: stopping Accept Thread
10-26 22:39:33.331  4533  5171 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-26 22:39:33.331  4533  5171 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-26 22:39:33.333  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:33.337   510   921 D CommandListener: Setting iface cfg
10-26 22:39:33.338  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:39:33.338  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:33.338  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.338  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.338  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:33.338  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.338  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:33.338  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:33.338  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:39:33.339  3488  5299 V NativeCrypto: Read error: ssl=0x7f8bd82000: I/O error during system call, Connection timed out
10-26 22:39:33.341  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.341  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:33.342  3488  5299 V NativeCrypto: SSL shutdown failed: ssl=0x7f8bd82000: I/O error during system call, Broken pipe
10-26 22:39:33.342   928  5247 D DhcpClient: Receive thread stopped
10-26 22:39:33.344   928  3060 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-26 22:39:33.344   928  5244 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-26 22:39:33.345  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.345  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:33.345  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.345  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.345  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:33.345  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.345  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:33.345  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:33.345  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:39:33.346  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.346  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:33.348   928  5244 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-26 22:39:33.349   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-26 22:39:33.349   928  2863 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-26 22:39:33.349  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:33.351   928  2863 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-26 22:39:33.354  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:33.358  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:39:33.359  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:33.359  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.359  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.359  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:33.359  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.359  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:33.359  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:33.359  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:39:33.361  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.361  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:33.361   928   941 I ActivityManager: Start proc 5533:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-26 22:39:33.362  4533  4533 D HeadsetService: Received stop request...Stopping profile...
,10-26 22:39:33.368  3677  3915 D BluetoothHeadset: Proxy object disconnected
10-26 22:39:33.368   928   928 D BluetoothHeadset: Proxy object disconnected
10-26 22:39:33.368   928   928 D BluetoothHeadset: Proxy object disconnected
10-26 22:39:33.368   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-26 22:39:33.368  3034  3046 D BluetoothHeadset: Proxy object disconnected
10-26 22:39:33.368   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,10-26 22:39:33.368   536   536 E Parcel  : Reading a NULL string not supported here.
10-26 22:39:33.368   928   928 D BluetoothHeadset: Proxy object disconnected
10-26 22:39:33.369   928   928 D RttService: SCAN_AVAILABLE : 1
10-26 22:39:33.369  3034  3034 D HeadsetProfile: Bluetooth service disconnected
10-26 22:39:33.369   928  2967 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-26 22:39:33.370  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.371  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:33.371  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.371  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.371  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:33.371  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.371  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:33.371  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:33.371  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:39:33.371  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.372  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:33.372  4533  4533 D A2dpService: Received stop request...Stopping profile...
,10-26 22:39:33.373  4533  4763 D A2dpStateMachine: Exit Disconnected: -1
,10-26 22:39:33.374   928   928 D BluetoothA2dp: Proxy object disconnected
,10-26 22:39:33.374   928  2863 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-26 22:39:33.374  4533  4533 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:39:33.374  4533  4533 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:33.375  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:33.375  3034  3034 D BluetoothA2dp: Proxy object disconnected
10-26 22:39:33.375  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:33.376  3637  3776 W QCNEJ   : |CORE| network lost: 100
10-26 22:39:33.377  3637  3776 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-26 22:39:33.378  4533  4533 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-26 22:39:33.378  4533  4533 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-26 22:39:33.378  4533  4612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-26 22:39:33.378  4533  4724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:33.378  4533  4724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:33.378  4533  4724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:33.378  4533  4612 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-26 22:39:33.378  4533  4533 D HidService: Received stop request...Stopping profile...
10-26 22:39:33.378  4533  4533 D HidService: Stopping Bluetooth HidService
10-26 22:39:33.379  4533  4533 D HealthService: Received stop request...Stopping profile...
10-26 22:39:33.381  4533  4533 D PanService: Received stop request...Stopping profile...
10-26 22:39:33.382  4533  4533 V BluetoothAdapterState: isTurningOff()=true
10-26 22:39:33.382  4533  4533 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:33.382  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:33.382  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:39:33.383  4533  4612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-26 22:39:33.383  4533  4533 D BluetoothMapService: Received stop request...Stopping profile...
10-26 22:39:33.383  4533  4533 D BluetoothMapService: stop()
,10-26 22:39:33.383  4533  4724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:33.384  4533  4724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:33.384  4533  4724 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 22:39:33.384  4533  4724 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 22:39:33.384  4533  4724 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 22:39:33.384  4533  4724 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 22:39:33.384  4533  4533 D BluetoothMapAppObserver: deinitObservers()
10-26 22:39:33.384  4533  4533 D BluetoothMapAppObserver: removeReceiver()
10-26 22:39:33.385  3034  3034 D BluetoothInputDevice: Proxy object disconnected
,10-26 22:39:33.385  3034  3034 D HidProfile: Bluetooth service disconnected
10-26 22:39:33.385  3034  3034 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 22:39:33.385  3034  3034 D PanProfile: Bluetooth service disconnected
10-26 22:39:33.386  4533  4533 D SapService: Received stop request...Stopping profile...
10-26 22:39:33.386  4533  4533 V SapService: stop()
,10-26 22:39:33.389  4533  4533 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:39:33.389  4533  4533 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:33.389  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:33.389  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:33.390  4533  4533 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-26 22:39:33.390  4533  4533 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,10-26 22:39:33.390  4533  4612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-26 22:39:33.390  4533  4533 V BluetoothAdapterState: isTurningOff()=true
10-26 22:39:33.390  4533  4533 V BluetoothAdapterState: isTurningOn()=false
,10-26 22:39:33.390  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:33.390  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:33.390  4533  4533 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-26 22:39:33.391  4533  4612 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-26 22:39:33.391  4533  4533 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-26 22:39:33.391  4533  4533 V BluetoothAdapterState: isTurningOff()=true
10-26 22:39:33.391  4533  4533 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:33.391  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:33.391  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:39:33.391  4533  4533 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-26 22:39:33.391  4533  4533 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-26 22:39:33.392  4533  4533 D BluetoothMapService: MAP Service closeService in
10-26 22:39:33.392  4533  4533 V BluetoothAdapterState: isTurningOff()=true
10-26 22:39:33.392  4533  4533 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:33.392  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:33.392  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:33.393  4533  4533 D BluetoothMapService: cleanup()
10-26 22:39:33.393  4533  4533 D BluetoothMapService: MAP Service closeService in
10-26 22:39:33.393  4533  4533 V BluetoothAdapterState: isTurningOff()=true
10-26 22:39:33.393  4533  4533 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:33.393  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:33.393  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:33.393  4533  4608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-26 22:39:33.393  4533  4608 D BluetoothAdapterProperties: Setting state to 15
10-26 22:39:33.393  4533  4608 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-26 22:39:33.394  4533  4608 I BluetoothAdapterState: Entering BleOnState
,10-26 22:39:33.394   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:39:33.394   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:39:33.394  3034  3048 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 22:39:33.395   928  2855 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-26 22:39:33.396   928  2855 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 22:39:33.396  3677  4115 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:39:33.396  3034  3046 D BluetoothMap: onBluetoothStateChange: up=false
,10-26 22:39:33.397  3034  3802 D BluetoothPan: onBluetoothStateChange on: false
10-26 22:39:33.398  3034  3048 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:39:33.398   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 22:39:33.398  3034  3046 D BluetoothPbap: onBluetoothStateChange: up=false
,10-26 22:39:33.399   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:39:33.400  3034  3802 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 22:39:33.403  4533  4608 D BluetoothAdapterState: Current state: BLE ON, message: 20
,10-26 22:39:33.403  4533  4608 D BluetoothAdapterProperties: Setting state to 16
,10-26 22:39:33.403  4533  4608 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-26 22:39:33.404  4533  4608 D BluetoothAdapterProperties: onBleDisable
,10-26 22:39:33.404  4533  4608 I BluetoothAdapterState: Entering PendingCommandState
10-26 22:39:33.404  4533  4609 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-26 22:39:33.406  4533  4724 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-26 22:39:33.406  4533  4724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:33.406  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.406  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:33.406  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.406  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.406  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:33.406  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.406  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:33.406  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:33.406  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:33.407  4533  4612 D BluetoothAdapterProperties: Scan Mode:20
,10-26 22:39:33.407  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.407  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:33.410  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.410  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:33.410  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.410  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.410  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:33.410  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.410  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:33.410  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:33.410  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:33.412  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.412  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:33.412  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.412  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.412  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:33.412  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.412  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:33.412  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:33.412  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:33.413  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:33.413   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:39:33.414  5533  5533 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-26 22:39:33.414  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:33.416  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:33.429   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:39:33.429   510   921 D CommandListener: Clearing all IP addresses on wlan0
,10-26 22:39:33.429   510   921 D TetherController: Setting IP forward enable = 0
10-26 22:39:33.430   928  2863 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-26 22:39:33.430   928  2863 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-26 22:39:33.432  5533  5533 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 22:39:33.433   928   945 D Tethering: MasterInitialState.processMessage what=3
10-26 22:39:33.433   928  2855 D DhcpClient: doQuit
10-26 22:39:33.434   928  2855 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-26 22:39:33.434  5128  5128 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a6082a0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-26 22:39:33.434   928  5246 D DhcpClient: onQuitting
,10-26 22:39:33.435  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:33.436  3864  3864 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-26 22:39:33.436  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:33.436  3355  3355 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-26 22:39:33.438  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.438  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:33.438  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.438  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.438  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:33.438  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.438  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:33.438  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:33.438  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:33.439  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.439  4894  4918 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-26 22:39:33.439  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:33.440  4894  4918 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,10-26 22:39:33.440  4894  4918 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-26 22:39:33.440  4894  4918 E SarControlService: no key has been found,reset the power
10-26 22:39:33.440  4894  4954 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 22:39:33.440  4894  4954 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 22:39:33.440  4894  4954 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-26 22:39:33.441  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 22:39:33.441  4937  4937 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 22:39:33.442  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.442  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:33.442  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.442  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.442  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:33.442  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.442  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:33.442  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:33.442  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 22:39:33.442  4894  4954 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-26 22:39:33.442  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.442  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:33.442  4894  4954 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 22:39:33.442  4894  4954 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-26 22:39:33.444  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:39:33.444  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 22:39:33.444  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:33.444  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:33.444  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:33.444  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:33.444  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:33.444  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:33.444  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:33.444  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:33.444  4937  4937 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-26 22:39:33.444  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:33.444  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:33.446  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:33.446  4937  4956 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ee87586 HexData = [00000000ea03000000000000ffffffff]
,10-26 22:39:33.446  4937  4956 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 22:39:33.446  4937  4956 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-26 22:39:33.446  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 22:39:33.447  4894  4904 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-26 22:39:33.451   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b2dab74:true
,10-26 22:39:33.451  3488  3488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 22:39:33.456  4937  4956 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ee87586 HexData = [00000000eb03000000000000ffffffff]
10-26 22:39:33.456  4937  4956 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 22:39:33.456  4937  4956 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-26 22:39:33.458  3355  3355 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-26 22:39:33.459  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 22:39:33.459  4894  4905 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 22:39:33.463  3355  3355 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-26 22:39:33.475  5533  5533 D LocalBluetoothProfileManager: Adding local MAP profile
10-26 22:39:33.478  5533  5533 D BluetoothMap: Create BluetoothMap proxy object
10-26 22:39:33.483   510   921 E Netd    : netlink response contains error (No such file or directory)
10-26 22:39:33.483   928  2863 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-26 22:39:33.484   510   921 D TetherController: Setting IP forward enable = 0
10-26 22:39:33.487  5533  5533 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
10-26 22:39:33.489  3355  3355 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-26 22:39:33.492  5533  5533 D DockEventReceiver: finishStartingService: stopping service
10-26 22:39:33.496  5533  5533 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 22:39:33.500  3488  3488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 22:39:33.502  3355  3355 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-26 22:39:33.505  5533  5533 D DockEventReceiver: finishStartingService: stopping service
,10-26 22:39:33.509  3883  3883 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-26 22:39:33.512  3883  3883 D SystemUpdateService: onCreate
,10-26 22:39:33.516  3883  3883 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 22:39:33.524  3883  5571 I SystemUpdateService: active receiver: enabled
,10-26 22:39:33.525  3883  3883 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-26 22:39:33.531  3883  5271 I iu.UploadsManager: num queued entries: 0
,10-26 22:39:33.531  3883  5271 I iu.UploadsManager: num updated entries: 0
10-26 22:39:33.532  3883  5271 I iu.SyncManager: NEXT; no task
,10-26 22:39:33.534  3883  3883 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-26 22:39:33.535  3883  3883 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-26 22:39:33.537  5274  5274 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:39:33.540  5274  5274 D SprintDMHelper: simOperator: 
,10-26 22:39:33.540  5274  5274 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 22:39:33.551  3883  5571 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 22:39:33.552  4347  5573 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-26 22:39:33.554  3883  5571 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-26 22:39:33.554  3883  5571 I SystemUpdateService: now status is 0 (complete)
10-26 22:39:33.554  3883  5571 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 22:39:33.555  3883  5571 I SystemUpdateService: file has been verified
10-26 22:39:33.555  3883  5571 I SystemUpdateService: OTA package size = 21989297
,10-26 22:39:33.559  3883  5571 I SystemUpdateService: showing system update notification
,10-26 22:39:33.564   928  3715 I ActivityManager: Start proc 5574:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-26 22:39:33.576   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 22:39:33.577  3883  3883 D SystemUpdateService: onDestroy
,10-26 22:39:33.578   928   938 I ActivityManager: Killing 5128:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-26 22:39:33.611  4347  4347 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 22:39:33.612   928  2855 D wifi    : In wifi stop Hal
10-26 22:39:33.612   928  2855 D wifi    : halHandle = 0x7f8a19b180, mVM = 0x7fa634d140, mCls = 0x100a02
10-26 22:39:33.612   928  3353 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-26 22:39:33.612   928  3353 D WifiHAL : Got a signal to exit!!!
10-26 22:39:33.612   928  3353 I WifiHAL : Exit wifi_event_loop
10-26 22:39:33.613   928  2855 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-26 22:39:33.613  4533  4612 I bt_hci  : shut_down
10-26 22:39:33.613   928  2855 E WifiHAL : Event processing terminated
10-26 22:39:33.613   928  2855 D wifi    : In wifi cleaned up handler
10-26 22:39:33.613   928  2855 I WifiHAL : Internal cleanup completed
10-26 22:39:33.615  3607  4096 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 22:39:33.615  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:33.618  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:33.618  4533  4618 D bt_hwcfg: hw_epilog_process
,10-26 22:39:33.618  4533  4618 I bt_vendor: low_power_mode_cb
,10-26 22:39:33.619  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:33.621  4533  4618 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-26 22:39:33.621  4533  4618 I bt_vendor: epilog_cb
10-26 22:39:33.621  4533  4618 I bt_hci  : epilog_finished_callback
10-26 22:39:33.624  4533  4612 I bt_hci_h4: hal_close
10-26 22:39:33.624  4533  4612 I bt_userial_vendor: device fd = 54 close
,10-26 22:39:33.628  5574  5574 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-26 22:39:33.635   928  3782 I ActivityManager: Killing 3784:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-26 22:39:33.636   928  3353 D wifi    : set interface wlan0 flags (DOWN)
,10-26 22:39:33.636   928  2855 D WifiNative-HAL: HAL event thread stopped successfully
,10-26 22:39:33.653   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:33.732  4533  4609 D bt_stack_manager: event_shut_down_stack finished.
,10-26 22:39:33.732  4533  4608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-26 22:39:33.735  4533  4608 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-26 22:39:33.735  4533  4533 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-26 22:39:33.736  4533  4533 D BtGatt.GattService: Received stop request...Stopping profile...
,10-26 22:39:33.736  4533  4533 D BtGatt.GattService: stop()
,10-26 22:39:33.736  4533  4533 D BtGatt.AdvertiseManager: advertise clients cleared
10-26 22:39:33.737  4533  4533 V BluetoothAdapterState: isTurningOff()=false
10-26 22:39:33.738  4533  4533 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:33.738  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:33.738  4533  4533 V BluetoothAdapterState: isBleTurningOff()=true
10-26 22:39:33.738  4533  4608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-26 22:39:33.738  4533  4608 D BluetoothAdapterProperties: Setting state to 10
10-26 22:39:33.738  4533  4608 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-26 22:39:33.739  4533  4608 I BluetoothAdapterState: Entering OffState
,10-26 22:39:33.740   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
10-26 22:39:33.748  4533  4533 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-26 22:39:33.748  4533  4533 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,10-26 22:39:33.748  4533  4533 I BluetoothServiceJni: cleanupNative: return from cleanup
10-26 22:39:33.749  4533  4609 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-26 22:39:33.751  4533  4533 I art     : System.exit called, status: 0
10-26 22:39:33.751  4533  4533 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-26 22:39:33.774   928  3523 I ActivityManager: Process com.android.bluetooth (pid 4533) has died
,10-26 22:39:33.839   928   945 D Tethering: InitialState.processMessage what=4
,10-26 22:39:33.843   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-26 22:39:34.653   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-26 22:39:38.326   928   939 D WifiService: setWifiEnabled: true pid=5475, uid=10077
10-26 22:39:38.326   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:39:38.333   510   921 D SoftapController: Softap fwReload - Ok
,10-26 22:39:38.340   510   921 D CommandListener: Setting iface cfg
,10-26 22:39:38.341   510   921 D CommandListener: Trying to bring down wlan0
,10-26 22:39:38.343   510   921 D CommandListener: Clearing all IP addresses on wlan0
,10-26 22:39:38.348   928  2855 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 22:39:38.955   928  2855 D wifi    : set interface wlan0 flags (UP)
,10-26 22:39:38.959   928  2855 I WifiHAL : Initializing wifi
10-26 22:39:38.959   928  2855 I WifiHAL : Creating socket
10-26 22:39:38.962   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-26 22:39:38.965   928  2855 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-26 22:39:38.966   928  2855 D wifi    : Did set static halHandle = 0x7f8a19b180
,10-26 22:39:38.966   928  2855 D wifi    : halHandle = 0x7f8a19b180, mVM = 0x7fa634d140, mCls = 0x101a1a
,10-26 22:39:38.966   928  2855 D wifi    : array field set
10-26 22:39:38.966   928  2855 I WifiNative-HAL: interface[0] = wlan0
10-26 22:39:38.970   928  5590 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547777786240
,10-26 22:39:38.970   928  5590 D wifi    : waitForHalEvents called, vm = 0x7fa634d140, obj = 0x101a1a, env = 0x7f8dcb8300
,10-26 22:39:39.045  5591  5591 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-26 22:39:39.070   928  2855 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-26 22:39:39.078  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:39.080  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:39.081  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:39.118  5591  5591 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 22:39:39.162  5591  5591 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 22:39:39.162  5591  5591 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-26 22:39:39.181   928  2855 D WifiConfigStore: Loading config and enabling all networks 
10-26 22:39:39.187  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:39:39.187  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:39.187  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:39.187  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:39.187  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:39.187  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:39.187  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:39.187  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:39.187  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:39.188  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:39.188  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:39:39.190  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:39:39.190  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:39.190  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:39.190  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:39.190  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:39.190  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:39.190  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:39.190  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:39.190  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:39.190  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:39.190  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:39.191  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:39:39.191  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:39.191  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:39.191  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:39.191  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:39.191  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:39.191  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:39.191  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:39.191  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:39.191  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:39.191  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:39:39.206   928  2855 D WifiConfigStore: loaded 0 passpoint configs
,10-26 22:39:39.208   928  2855 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,10-26 22:39:39.208   928  2855 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-26 22:39:39.209   928  2855 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-26 22:39:39.209   928  2855 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-26 22:39:39.209   928  2855 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,10-26 22:39:39.210   928  2855 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-26 22:39:39.210   928  2855 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-26 22:39:39.210   928  2855 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
10-26 22:39:39.210   928  2855 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,10-26 22:39:39.210   928  2855 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-26 22:39:39.211   928  2855 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-26 22:39:39.211   928  2855 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-26 22:39:39.213   928  2855 D WifiNative-HAL: Setting external_sim to 1
,10-26 22:39:39.213   928  2855 D wifi    : setting dfs flag to true, 0x7f90cff580
,10-26 22:39:39.213  4347  4347 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 22:39:39.213   928  2855 D WifiStateMachine: Setting OUI to DA-A1-19
10-26 22:39:39.213   928  2855 D wifi    : setting scan oui 0x7f90cff580
10-26 22:39:39.213   928  2855 D WifiHAL : Sending mac address OUI
,10-26 22:39:39.216   928  2855 E native  : do suspend false
,10-26 22:39:39.223   928  2855 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-26 22:39:39.223   928   928 D RttService: SCAN_AVAILABLE : 3
10-26 22:39:39.223   928  2967 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-26 22:39:39.227   510   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-26 22:39:39.229   510   921 D CommandListener: Setting iface cfg
,10-26 22:39:39.229   928  2854 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,10-26 22:39:39.230   928  2854 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-26 22:39:39.239   928  2854 D WifiNative-HAL: p2pGetDeviceAddress
,10-26 22:39:39.239   928  2854 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-26 22:39:39.244   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129200 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,10-26 22:39:39.655   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:39.995  3883  5595 I EventLogService: Aggregate from 1477512575813 (log), 1477512575813 (data)
,10-26 22:39:40.656   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:41.657   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:42.330  5591  5591 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 22:39:42.338  5591  5591 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 22:39:42.344  5591  5591 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 22:39:42.350  5591  5591 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 22:39:42.378   928  2855 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-26 22:39:42.379   928  2855 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-26 22:39:42.379   928  2855 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:39:42.391   928  2855 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-26 22:39:42.424   928  2855 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-26 22:39:42.430  5591  5591 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-26 22:39:42.658   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:42.852  5591  5591 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-26 22:39:42.893  5591  5591 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-26 22:39:42.895  5591  5591 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-26 22:39:42.905   928  2855 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 22:39:42.905   928  2855 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-26 22:39:42.905   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-26 22:39:42.922   928  2855 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:39:42.937   510   921 D CommandListener: Setting iface cfg
,10-26 22:39:42.942   928  2855 D WifiStateMachine: Start Dhcp Watchdog 2
,10-26 22:39:42.949   928  5602 D DhcpClient: Receive thread started
,10-26 22:39:42.952   928  2863 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 22:39:42.952   928  2863 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
10-26 22:39:42.953   928  2855 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-26 22:39:43.034   928  2855 E native  : do suspend false
,10-26 22:39:43.052   928  5601 D DhcpClient: Broadcasting DHCPDISCOVER
,10-26 22:39:43.066   928  5602 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172708, domain null
10-26 22:39:43.066   928  5601 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172708 seconds
,10-26 22:39:43.069   928  5601 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-26 22:39:43.096   928  5602 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-26 22:39:43.097   928  5601 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-26 22:39:43.102   510   921 D CommandListener: Setting iface cfg
,10-26 22:39:43.107   928  2855 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-26 22:39:43.112   928  5601 D DhcpClient: Scheduling renewal in 86399s
,10-26 22:39:43.123   928  2855 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-26 22:39:43.124   928  2855 D WifiConfigStore: No blacklist allowed without epno enabled
10-26 22:39:43.124   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-26 22:39:43.126   928  2863 D ConnectivityService: Adding iface wlan0 to network 101
10-26 22:39:43.134   928  2855 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-26 22:39:43.171   928  2863 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-26 22:39:43.171   928  2863 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-26 22:39:43.173   928  2863 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-26 22:39:43.176   928  2863 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-26 22:39:43.179   928  2863 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-26 22:39:43.184   928  2863 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 22:39:43.188   928  2863 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-26 22:39:43.188   928  2863 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-26 22:39:43.188   928  2863 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-26 22:39:43.189   928  2863 D ConnectivityService:    accepting network in place of null
10-26 22:39:43.189   928  2863 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-26 22:39:43.189   928  2855 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-26 22:39:43.190   928  2855 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-26 22:39:43.202   928  5600 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133158, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-26 22:39:43.211   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:39:43.231   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:39:43.235   928  2863 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-26 22:39:43.235   928  2863 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:39:43.235  3637  3776 W QCNEJ   : |CORE| network available: 101
10-26 22:39:43.236   928  2863 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-26 22:39:43.237   928   945 D Tethering: MasterInitialState.processMessage what=3
10-26 22:39:43.240  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.240  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:43.240  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:43.240  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:43.240  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:43.240  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:43.240  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:43.240  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:43.240  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:39:43.240  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.241  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:43.241  3637  3776 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-26 22:39:43.243  3637  3776 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-26 22:39:43.243  3637  3776 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-26 22:39:43.244  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:39:43.245  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:43.245  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:43.245  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:43.245  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:43.245  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:43.245  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:43.245  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:43.245  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:39:43.245  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.245  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:43.248  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.248  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:43.248  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:43.248  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:43.248  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:43.248  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:43.248  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:39:43.248  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:39:43.248  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:39:43.248  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.248  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:39:43.252  4894  4918 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-26 22:39:43.252  4894  4918 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 22:39:43.252  4894  4918 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-26 22:39:43.252  4894  4918 E SarControlService: no key has been found,reset the power
10-26 22:39:43.252  4894  4954 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 22:39:43.252  4894  4954 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 22:39:43.253  4894  4954 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-26 22:39:43.253  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 22:39:43.253  4937  4937 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 22:39:43.255  3864  3864 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-26 22:39:43.256  4894  4954 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-26 22:39:43.256  4894  4954 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 22:39:43.256  4894  4954 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-26 22:39:43.256  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 22:39:43.256  4937  4937 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-26 22:39:43.259  3883  3883 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-26 22:39:43.260  4937  4956 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ee87586 HexData = [00000000ec03000000000000ffffffff]
10-26 22:39:43.260  4937  4956 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 22:39:43.260  4937  4956 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-26 22:39:43.263  4937  4956 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ee87586 HexData = [00000000ed03000000000000ffffffff]
10-26 22:39:43.263  4937  4956 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 22:39:43.263  4937  4956 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,10-26 22:39:43.264  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-26 22:39:43.264  4894  4904 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-26 22:39:43.264  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 22:39:43.265  4894  4905 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 22:39:43.265  3883  3883 D SystemUpdateService: onCreate
10-26 22:39:43.269  3883  3883 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 22:39:43.281  3883  3883 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-26 22:39:43.286  3883  5271 I iu.UploadsManager: num queued entries: 0
,10-26 22:39:43.286  3883  5271 I iu.UploadsManager: num updated entries: 0
,10-26 22:39:43.288  3883  5614 I SystemUpdateService: active receiver: enabled
,10-26 22:39:43.291  3883  3883 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-26 22:39:43.292  3883  3883 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-26 22:39:43.294  5274  5274 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-26 22:39:43.297  5274  5274 D SprintDMHelper: simOperator: 
10-26 22:39:43.297  5274  5274 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 22:39:43.309   928  5599 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-26 22:39:43.316  3883  5271 I iu.SyncManager: NEXT; no task
,10-26 22:39:43.316  3883  5614 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 22:39:43.330   928  3782 D WifiService: setWifiEnabled: false pid=5475, uid=10077
,10-26 22:39:43.330   928  3782 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:39:43.332   928  2855 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-26 22:39:43.332   928  2855 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-26 22:39:43.332   928  2855 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 22:39:43.332   928  2855 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:39:43.334  3883  5614 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-26 22:39:43.335  3883  5614 I SystemUpdateService: now status is 0 (complete)
,10-26 22:39:43.335  3883  5614 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 22:39:43.335  3883  5614 I SystemUpdateService: file has been verified
,10-26 22:39:43.336  3883  5614 I SystemUpdateService: OTA package size = 21989297
,10-26 22:39:43.342  3883  5614 I SystemUpdateService: showing system update notification
,10-26 22:39:43.343   928  5601 D DhcpClient: Clearing IP address
,10-26 22:39:43.343   510   921 D CommandListener: Clearing all IP addresses on wlan0
,10-26 22:39:43.345   510   921 D CommandListener: Setting iface cfg
,10-26 22:39:43.350   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 22:39:43.351  3883  3883 D SystemUpdateService: onDestroy
10-26 22:39:43.354   928  5599 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
10-26 22:39:43.354   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,10-26 22:39:43.358   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-26 22:39:43.358   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,10-26 22:39:43.361   536   536 E Parcel  : Reading a NULL string not supported here.
,10-26 22:39:43.363   928   928 D RttService: SCAN_AVAILABLE : 1
10-26 22:39:43.364   928  2967 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-26 22:39:43.364   928  2863 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-26 22:39:43.366  3637  3776 W QCNEJ   : |CORE| network lost: 101
10-26 22:39:43.367   928  2855 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-26 22:39:43.367  3637  3776 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-26 22:39:43.369   928  2855 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-26 22:39:43.370   928  5602 D DhcpClient: Receive thread stopped
,10-26 22:39:43.386   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:39:43.404   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:39:43.405   928  2863 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-26 22:39:43.405   510   921 D CommandListener: Clearing all IP addresses on wlan0
10-26 22:39:43.405   928  2863 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:39:43.407   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-26 22:39:43.409   928  2855 D DhcpClient: doQuit
,10-26 22:39:43.409   928  2855 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-26 22:39:43.409   928  5601 D DhcpClient: onQuitting
10-26 22:39:43.409  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.409  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:43.409  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:43.409  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:43.409  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:39:43.409  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:43.409  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:43.409  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:43.409  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:43.409  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.409  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:43.409  5591  5591 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-26 22:39:43.410  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.411  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:43.411  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:43.411  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:43.411  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:43.411  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:43.411  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:43.411  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:43.411  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:43.411  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.411  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:43.414  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.414  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:43.414  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:43.414  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:43.414  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:43.414  5475  5475 V io.jxcore.node.ConnectivityMonitor,:     - is Bluetooth enabled: false
10-26 22:39:43.414  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:43.414  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:43.414  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:43.414  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.414  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:43.415  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.415  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:43.415  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:43.415  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:43.415  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:43.415  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:43.415  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:43.415  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:43.415  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:43.415  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:43.415  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:39:43.416  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:43.416  3864  3864 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-26 22:39:43.416  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:43.419  3883  3883 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-26 22:39:43.421  4894  4918 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-26 22:39:43.421  4894  4918 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 22:39:43.421  4894  4918 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-26 22:39:43.421  4894  4918 E SarControlService: no key has been found,reset the power
10-26 22:39:43.421  4894  4954 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 22:39:43.421  5591  5591 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-26 22:39:43.421  4894  4954 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 22:39:43.421  4894  4954 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-26 22:39:43.422  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 22:39:43.422  4937  4937 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-26 22:39:43.424  5591  5591 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-26 22:39:43.424  4894  4954 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-26 22:39:43.424  4894  4954 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 22:39:43.424  4894  4954 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-26 22:39:43.425  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 22:39:43.425  4937  4937 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-26 22:39:43.429  4937  4956 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ee87586 HexData = [00000000ee03000000000000ffffffff]
10-26 22:39:43.429  4937  4956 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 22:39:43.429  4937  4956 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,10-26 22:39:43.429  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 22:39:43.429  4894  4905 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-26 22:39:43.431  3883  3883 D SystemUpdateService: onCreate
,10-26 22:39:43.434  4937  4956 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ee87586 HexData = [00000000ef03000000000000ffffffff]
,10-26 22:39:43.434  4937  4956 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 22:39:43.435  4937  4956 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-26 22:39:43.435  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 22:39:43.435  4894  4904 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 22:39:43.436  3883  3883 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 22:39:43.443  3883  5633 I SystemUpdateService: active receiver: enabled
10-26 22:39:43.445  3883  3883 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-26 22:39:43.449  3883  5271 I iu.UploadsManager: num queued entries: 0
,10-26 22:39:43.450  3883  5271 I iu.UploadsManager: num updated entries: 0
,10-26 22:39:43.451  5591  5591 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-26 22:39:43.453  3883  3883 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-26 22:39:43.454  3883  3883 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-26 22:39:43.456  5274  5274 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:39:43.460  5274  5274 D SprintDMHelper: simOperator: 
10-26 22:39:43.460  5274  5274 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 22:39:43.461   510   921 E Netd    : netlink response contains error (No such file or directory)
,10-26 22:39:43.462   928  2863 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-26 22:39:43.463   928  2863 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-26 22:39:43.464  5591  5591 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-26 22:39:43.468  3883  5633 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 22:39:43.473  3883  5271 I iu.SyncManager: NEXT; no task
,10-26 22:39:43.473  3883  5633 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-26 22:39:43.473  3883  5633 I SystemUpdateService: now status is 0 (complete)
,10-26 22:39:43.474  3883  5633 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 22:39:43.474  3883  5633 I SystemUpdateService: file has been verified
10-26 22:39:43.475  3883  5633 I SystemUpdateService: OTA package size = 21989297
,10-26 22:39:43.489  3883  5633 I SystemUpdateService: showing system update notification
,10-26 22:39:43.495   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 22:39:43.496  3883  3883 D SystemUpdateService: onDestroy
,10-26 22:39:43.566   928  2855 D wifi    : In wifi stop Hal
,10-26 22:39:43.566   928  2855 D wifi    : halHandle = 0x7f8a19b180, mVM = 0x7fa634d140, mCls = 0x101a1a
,10-26 22:39:43.567   928  5590 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-26 22:39:43.567   928  5590 D WifiHAL : Got a signal to exit!!!
10-26 22:39:43.567   928  5590 I WifiHAL : Exit wifi_event_loop
10-26 22:39:43.568   928  2855 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-26 22:39:43.568   928  2855 E WifiHAL : Event processing terminated
10-26 22:39:43.568   928  2855 D wifi    : In wifi cleaned up handler
,10-26 22:39:43.568   928  2855 I WifiHAL : Internal cleanup completed
,10-26 22:39:43.573  4347  4347 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 22:39:43.574  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:43.575  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:43.575  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:43.576  3607  4096 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 22:39:43.594   928  5590 D wifi    : set interface wlan0 flags (DOWN)
,10-26 22:39:43.594   928  2855 D WifiNative-HAL: HAL event thread stopped successfully
,10-26 22:39:43.658   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:43.799   928   945 D Tethering: InitialState.processMessage what=4
,10-26 22:39:43.806   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-26 22:39:44.236   928  2863 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-26 22:39:44.659   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-26 22:39:48.331  4347  5618 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,10-26 22:39:48.331  4347  5618 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-26 22:39:48.337  4347  5618 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-26 22:39:48.367   928   945 I ActivityManager: Start proc 5640:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-26 22:39:48.450  5640  5640 D AdapterServiceConfig: Adding HeadsetService
,10-26 22:39:48.450  5640  5640 D AdapterServiceConfig: Adding A2dpService
10-26 22:39:48.451  5640  5640 D AdapterServiceConfig: Adding HidService
10-26 22:39:48.451  5640  5640 D AdapterServiceConfig: Adding HealthService
10-26 22:39:48.451  5640  5640 D AdapterServiceConfig: Adding PanService
10-26 22:39:48.451  5640  5640 D AdapterServiceConfig: Adding GattService
10-26 22:39:48.451  5640  5640 D AdapterServiceConfig: Adding BluetoothMapService
,10-26 22:39:48.451  5640  5640 D AdapterServiceConfig: Adding SapService
,10-26 22:39:48.461   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f5920e7:true
,10-26 22:39:48.462  5640  5640 D BluetoothAdapterState: make() - Creating AdapterState
,10-26 22:39:48.465  5640  5640 I bt_bluedroid: init
,10-26 22:39:48.465  5640  5652 I BluetoothAdapterState: Entering OffState
,10-26 22:39:48.467  5640  5653 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-26 22:39:48.467  5640  5653 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-26 22:39:48.467  5640  5653 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,10-26 22:39:48.468  5640  5653 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-26 22:39:48.468  5640  5640 I bt_bluedroid: get_profile_interface socket
,10-26 22:39:48.470  5640  5656 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 22:39:48.470  5640  5640 I bt_bluedroid: get_profile_interface sdp
,10-26 22:39:48.471  5640  5656 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 22:39:48.474  5640  5651 I bt_bluedroid: config_hci_snoop_log
10-26 22:39:48.475   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-26 22:39:48.480  5640  5652 D BluetoothAdapterState: Current state: OFF, message: 0
10-26 22:39:48.480  5640  5652 D BluetoothAdapterProperties: Setting state to 14
,10-26 22:39:48.480  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-26 22:39:48.482  5640  5652 D BluetoothBondStateMachine: make
,10-26 22:39:48.483  5640  5657 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-26 22:39:48.486  5640  5652 I BluetoothAdapterState: Entering PendingCommandState
,10-26 22:39:48.487  5640  5640 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-26 22:39:48.489  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
10-26 22:39:48.489  5640  5640 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 22:39:48.490  5640  5640 D BtGatt.GattService: Received start request. Starting profile...
10-26 22:39:48.490  5640  5640 D BtGatt.GattService: start()
10-26 22:39:48.490  5640  5640 I bt_bluedroid: get_profile_interface gatt
10-26 22:39:48.491  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
10-26 22:39:48.491  5640  5640 D BtGatt.AdvertiseManager: advertise manager created
,10-26 22:39:48.495  5640  5640 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:39:48.496  5640  5640 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:48.496  5640  5640 V BluetoothAdapterState: isBleTurningOn()=true
10-26 22:39:48.496  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:48.496  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-26 22:39:48.497  5640  5652 I bt_bluedroid: bt_bluedroid
,10-26 22:39:48.498  5640  5653 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-26 22:39:48.498  5640  5653 I bt_hci  : start_up
,10-26 22:39:48.503  5640  5653 I bt_vendor: alloc value 0xf3d4b871
10-26 22:39:48.503  5640  5653 I bt_vendor: init
10-26 22:39:48.503  5640  5653 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-26 22:39:48.503  5640  5653 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-26 22:39:48.614  5640  5653 D bt_hci  : start_up starting async portion
10-26 22:39:48.614  5640  5660 I bt_hci  : event_finish_startup
10-26 22:39:48.614  5640  5660 I bt_hci_h4: hal_open
10-26 22:39:48.615  5640  5660 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-26 22:39:48.611  5661  5661 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 22:39:48.618  5640  5660 I bt_userial_vendor: device fd = 54 open
,10-26 22:39:48.632  5640  5660 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 22:39:48.635  5640  5660 D bt_hwcfg: Chipset BCM4358A3
,10-26 22:39:48.635  5640  5660 D bt_hwcfg: Target name = [BCM4358A3]
,10-26 22:39:48.635  5640  5660 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-26 22:39:49.026  5640  5660 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-26 22:39:49.027  5640  5660 D bt_hwcfg: Settlement delay -- 100 ms
10-26 22:39:49.027  5640  5660 I bt_hwcfg: Setting fw settlement delay to 100 
,10-26 22:39:49.162  5640  5660 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 22:39:49.163  5640  5660 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,10-26 22:39:49.164  5640  5660 I bt_hwcfg: vendor lib fwcfg completed
10-26 22:39:49.165  5640  5660 I bt_vendor: firmware callback
,10-26 22:39:49.165  5640  5660 I bt_hci  : firmware_config_callback
10-26 22:39:49.173  5640  5663 I bt_btu  : btu_task pending for preload complete event
10-26 22:39:49.173  5640  5663 I bt_btu_task: Bluetooth chip preload is complete
10-26 22:39:49.174  5640  5663 I bt_btu  : btu_task received preload complete event
,10-26 22:39:49.179  5640  5663 I         : BTE_InitTraceLevels -- TRC_HCI
,10-26 22:39:49.179  5640  5663 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-26 22:39:49.179  5640  5663 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-26 22:39:49.180  5640  5663 I         : BTE_InitTraceLevels -- TRC_AVDT
10-26 22:39:49.180  5640  5663 I         : BTE_InitTraceLevels -- TRC_AVRC
10-26 22:39:49.180  5640  5663 I         : BTE_InitTraceLevels -- TRC_A2D
10-26 22:39:49.180  5640  5663 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-26 22:39:49.180  5640  5663 I         : BTE_InitTraceLevels -- TRC_BTM
10-26 22:39:49.180  5640  5663 I         : BTE_InitTraceLevels -- TRC_GAP
10-26 22:39:49.180  5640  5663 I         : BTE_InitTraceLevels -- TRC_PAN
,10-26 22:39:49.180  5640  5663 I         : BTE_InitTraceLevels -- TRC_SDP
10-26 22:39:49.181  5640  5663 I         : BTE_InitTraceLevels -- TRC_GATT
10-26 22:39:49.181  5640  5663 I         : BTE_InitTraceLevels -- TRC_SMP
10-26 22:39:49.181  5640  5663 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-26 22:39:49.181  5640  5663 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-26 22:39:49.265  5640  5663 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cc9549
10-26 22:39:49.266  5640  5663 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cc9549 
,10-26 22:39:49.286  5640  5656 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-26 22:39:49.288  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 22:39:49.288  5640  5656 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
10-26 22:39:49.290  5640  5656 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 22:39:49.292  5640  5656 D BluetoothAdapterProperties: Scan Mode:20
,10-26 22:39:49.293  5640  5656 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 22:39:49.293  5640  5656 D bt_hci  : do_postload posting postload work item
10-26 22:39:49.293  5640  5660 I bt_hci  : event_postload
10-26 22:39:49.293  5640  5660 I bt_vendor: sco_config_cb
,10-26 22:39:49.293  5640  5660 I bt_hci  : sco_config_callback postload finished.
10-26 22:39:49.297  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:49.297  5640  5656 D bt_bte_conf: Device ID record 1 : primary
10-26 22:39:49.297  5640  5656 D bt_bte_conf:   vendorId            = 000f
10-26 22:39:49.297  5640  5656 D bt_bte_conf:   vendorIdSource      = 0001
10-26 22:39:49.298  5640  5656 D bt_bte_conf:   product             = 1200
10-26 22:39:49.298  5640  5656 D bt_bte_conf:   version             = 1436
10-26 22:39:49.298  5640  5656 D bt_bte_conf:   clientExecutableURL = 
10-26 22:39:49.298  5640  5656 D bt_bte_conf:   serviceDescription  = 
10-26 22:39:49.298  5640  5656 D bt_bte_conf:   documentationURL    = 
10-26 22:39:49.298  5640  5656 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-26 22:39:49.298  5640  5653 D bt_stack_manager: event_start_up_stack finished
10-26 22:39:49.299  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-26 22:39:49.300  5640  5652 D BluetoothAdapterProperties: Setting state to 15
10-26 22:39:49.300  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-26 22:39:49.301  5640  5652 I BluetoothAdapterState: Entering BleOnState
,10-26 22:39:49.304  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:49.305  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:49.306  5640  5652 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-26 22:39:49.306  5640  5652 D BluetoothAdapterProperties: Setting state to 11
10-26 22:39:49.306  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-26 22:39:49.307  5640  5660 I bt_vendor: low_power_mode_cb
,10-26 22:39:49.310  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
,10-26 22:39:49.311  5640  5640 D HeadsetService: Received start request. Starting profile...
,10-26 22:39:49.313  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:49.314  5640  5640 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-26 22:39:49.314  5640  5640 D HeadsetStateMachine: make
,10-26 22:39:49.319  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:49.320  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:49.329  5640  5652 I BluetoothAdapterState: Entering PendingCommandState
,10-26 22:39:49.329  5640  5640 D HeadsetStateMachine: max_hf_connections = 1
,10-26 22:39:49.329  5640  5640 I bt_bluedroid: get_profile_interface handsfree
10-26 22:39:49.330  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-26 22:39:49.330  5640  5656 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-26 22:39:49.333  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
,10-26 22:39:49.333  5640  5640 D A2dpService: Received start request. Starting profile...
,10-26 22:39:49.334  5640  5640 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-26 22:39:49.334  5640  5640 I bt_bluedroid: get_profile_interface avrcp
,10-26 22:39:49.340  5640  5640 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-26 22:39:49.340  5640  5640 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-26 22:39:49.340  5640  5640 D A2dpStateMachine: make
,10-26 22:39:49.341  5640  5640 I bt_bluedroid: get_profile_interface a2dp
,10-26 22:39:49.342  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-26 22:39:49.343  5640  5671 D A2dpStateMachine: Enter Disconnected: -2
,10-26 22:39:49.345  5640  5640 I BluetoothHidServiceJni: classInitNative: succeeds
,10-26 22:39:49.345  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
,10-26 22:39:49.347  5640  5640 D HidService: Received start request. Starting profile...
,10-26 22:39:49.347  5533  5533 D BluetoothInputDevice: Proxy object connected
10-26 22:39:49.347  5640  5640 I bt_bluedroid: get_profile_interface hidhost
10-26 22:39:49.347  5640  5640 D HidService: setHidService(): set to: null
10-26 22:39:49.347  5533  5533 D HidProfile: Bluetooth service connected
10-26 22:39:49.347  5640  5640 I BluetoothHealthServiceJni: classInitNative: succeeds
10-26 22:39:49.347  5640  5656 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3caa56d
10-26 22:39:49.348  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-26 22:39:49.348  3488  3488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 22:39:49.348  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
10-26 22:39:49.349  5640  5640 D HealthService: Received start request. Starting profile...
,10-26 22:39:49.350  5640  5640 I bt_bluedroid: get_profile_interface health
,10-26 22:39:49.350  5640  5640 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-26 22:39:49.351  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
,10-26 22:39:49.352  5640  5640 D PanService: Received start request. Starting profile...
10-26 22:39:49.352  5640  5640 D BluetoothPanServiceJni: initializeNative(L110): pan
10-26 22:39:49.353  5640  5640 I bt_bluedroid: get_profile_interface pan
10-26 22:39:49.353  5640  5656 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-26 22:39:49.355  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
10-26 22:39:49.357  5640  5640 D BluetoothMapService: Received start request. Starting profile...
10-26 22:39:49.357  5640  5640 D BluetoothMapService: start()
10-26 22:39:49.357  5533  5533 D BluetoothMap: Proxy object connected
10-26 22:39:49.357  5533  5533 D MapProfile: Bluetooth service connected
,10-26 22:39:49.359  5533  5533 D BluetoothMap: getConnectedDevices()
,10-26 22:39:49.360  5640  5640 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-26 22:39:49.360  5533  5533 D BluetoothMap: Bluetooth is Not enabled
10-26 22:39:49.360  5533  5533 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 22:39:49.360  5640  5640 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-26 22:39:49.361  5640  5640 D BluetoothMapAppObserver: createReceiver()
10-26 22:39:49.361  5533  5533 D PanProfile: Bluetooth service connected
10-26 22:39:49.362  5640  5640 D BluetoothMapAppObserver: initObservers()
10-26 22:39:49.362  5640  5640 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-26 22:39:49.371  5640  5640 V SapService: SapBinder()
,10-26 22:39:49.371  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
10-26 22:39:49.371  5640  5640 D SapService: Received start request. Starting profile...
10-26 22:39:49.371  5640  5640 V SapService: start()
,10-26 22:39:49.373  5640  5640 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:39:49.373  5640  5640 V BluetoothAdapterState: isTurningOn()=true
10-26 22:39:49.373  5640  5669 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=1
10-26 22:39:49.373  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:49.374  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:49.374  5640  5640 V BluetoothAdapterState: isTurningOff()=false
10-26 22:39:49.374  5640  5640 V BluetoothAdapterState: isTurningOn()=true
10-26 22:39:49.374  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:49.374  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:49.374  5640  5640 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:39:49.374  5640  5640 V BluetoothAdapterState: isTurningOn()=true
10-26 22:39:49.374  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:49.374  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:39:49.375  5640  5640 V BluetoothAdapterState: isTurningOff()=false
10-26 22:39:49.375  5640  5640 V BluetoothAdapterState: isTurningOn()=true
10-26 22:39:49.375  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:49.375  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:49.376  5640  5640 V BluetoothAdapterState: isTurningOff()=false
10-26 22:39:49.376  5640  5640 V BluetoothAdapterState: isTurningOn()=true
10-26 22:39:49.376  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:49.376  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:49.376  5640  5640 V BluetoothAdapterState: isTurningOff()=false
10-26 22:39:49.376  5640  5640 V BluetoothAdapterState: isTurningOn()=true
,10-26 22:39:49.376  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:49.376  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:39:49.377  5640  5640 V BluetoothAdapterState: isTurningOff()=false
10-26 22:39:49.377  5640  5640 V BluetoothAdapterState: isTurningOn()=true
10-26 22:39:49.377  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:49.377  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:39:49.378  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-26 22:39:49.378  5640  5652 D BluetoothAdapterProperties: ScanMode =  20
10-26 22:39:49.378  5640  5652 D BluetoothAdapterProperties: State =  11
10-26 22:39:49.378  5640  5652 D BluetoothAdapterProperties: Setting state to 12
10-26 22:39:49.378  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-26 22:39:49.378   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:39:49.378  5640  5652 I BluetoothAdapterState: Entering OnState
10-26 22:39:49.378   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:39:49.379  3034  3048 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-26 22:39:49.380  3677  3706 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:39:49.381  5640  5656 D BluetoothAdapterProperties: Scan Mode:21
10-26 22:39:49.381  5640  5656 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 22:39:49.381  5533  5544 D BluetoothPan: onBluetoothStateChange on: true
10-26 22:39:49.381  3034  3034 D BluetoothA2dp: Proxy object connected
10-26 22:39:49.381  5475  5475 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-26 22:39:49.381  3034  3802 D BluetoothMap: onBluetoothStateChange: up=true
,10-26 22:39:49.384  3034  3034 D BluetoothMap: Proxy object connected
,10-26 22:39:49.384  3034  3034 D MapProfile: Bluetooth service connected
10-26 22:39:49.384  3034  3034 D BluetoothMap: getConnectedDevices()
10-26 22:39:49.385  5533  5545 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 22:39:49.386  3034  3046 D BluetoothPan: onBluetoothStateChange on: true
10-26 22:39:49.386  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:49.386  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:49.386  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:49.386  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:49.386  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:39:49.386  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:49.386  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:49.386  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 22:39:49.387  3034  3802 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 22:39:49.387  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:39:49.388  5533  5676 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 22:39:49.388  3034  3034 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 22:39:49.388  3034  3034 D PanProfile: Bluetooth service connected
10-26 22:39:49.389   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 22:39:49.390  3034  3048 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 22:39:49.390   928   928 D BluetoothA2dp: Proxy object connected
10-26 22:39:49.391  5640  5640 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 22:39:49.391  5533  5544 D BluetoothMap: onBluetoothStateChange: up=true
10-26 22:39:49.391   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 22:39:49.391  5640  5640 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-26 22:39:49.391  3034  3046 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 22:39:49.392  5640  5640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:39:49.393  3034  3034 D BluetoothInputDevice: Proxy object connected
10-26 22:39:49.393  3034  3034 D HidProfile: Bluetooth service connected
10-26 22:39:49.394  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:49.394  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:49.394  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:49.394  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:49.394  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:39:49.394  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:49.394  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:49.394  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:49.394   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,10-26 22:39:49.396  5640  5640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:39:49.397  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:39:49.398  5640  5640 D ObexServerSockets: Succeed to create listening sockets 
,10-26 22:39:49.398  5640  5640 D ObexServerSockets0: startAccept()
,10-26 22:39:49.398  5640  5640 D ObexServerSockets0: prepareForNewConnect()
10-26 22:39:49.400  5640  5640 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-26 22:39:49.401  5640  5640 D BluetoothSdpJni: SDP Create record success - handle: 0
10-26 22:39:49.401  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:49.401  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:49.401  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:49.401  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:49.401  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:39:49.401  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:49.401  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:49.401  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:49.401  5640  5680 D ObexServerSockets0: Accepting socket connection...
10-26 22:39:49.401  5640  5640 D BluetoothMapService: onReceive
10-26 22:39:49.401  5640  5640 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-26 22:39:49.401  5640  5640 D BluetoothMapService: STATE_ON
10-26 22:39:49.402  5640  5679 D ObexServerSockets0: Accepting socket connection...
,10-26 22:39:49.403  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:39:49.403  5475  5475 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 22:39:49.404  5640  5681 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:39:49.404  5533  5533 D LocalBluetoothProfileManager: Adding local A2DP profile
10-26 22:39:49.404  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:49.404  5640  5681 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-26 22:39:49.405  5640  5681 D BluetoothSdpJni: SDP Create record success - handle: 1
10-26 22:39:49.406  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:49.407  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:49.407  5533  5533 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-26 22:39:49.412  5533  5533 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 22:39:49.414  5533  5533 D BluetoothA2dp: Proxy object connected
,10-26 22:39:49.418  3488  3488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 22:39:49.421  5533  5533 D DockEventReceiver: finishStartingService: stopping service
,10-26 22:39:49.424  5533  5533 D BluetoothPbap: Proxy object connected
,10-26 22:39:49.425  3034  3034 D BluetoothPbap: Proxy object connected
10-26 22:39:49.425  3034  3034 D PbapServerProfile: Bluetooth service connected
10-26 22:39:49.425  5533  5533 D PbapServerProfile: Bluetooth service connected
,10-26 22:39:49.426  5640  5640 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 22:39:49.426  5640  5640 D ObexServerSockets0: prepareForNewConnect()
,10-26 22:39:49.432  5640  5685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:39:49.446  5640  5689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:39:49.448  5640  5689 I BtOppRfcommListener: Accept thread started.
,10-26 22:39:49.480  3677  3915 D BluetoothHeadset: Proxy object connected
,10-26 22:39:49.481   928   928 D BluetoothHeadset: Proxy object connected
10-26 22:39:49.481   928   928 D BluetoothHeadset: Proxy object connected
,10-26 22:39:49.482  3034  3046 D BluetoothHeadset: Proxy object connected
10-26 22:39:49.482  3677  4115 D BluetoothHeadset: Proxy object connected
10-26 22:39:49.482  3034  3034 D HeadsetProfile: Bluetooth service connected
10-26 22:39:49.482   928   928 D BluetoothHeadset: Proxy object connected
,10-26 22:39:49.488  3034  3802 D BluetoothHeadset: Proxy object connected
,10-26 22:39:49.488  3034  3034 D HeadsetProfile: Bluetooth service connected
,10-26 22:39:49.491   928   945 D BluetoothHeadset: Proxy object connected
,10-26 22:39:49.510  5533  5676 D BluetoothHeadset: Proxy object connected
,10-26 22:39:49.513  5533  5533 D HeadsetProfile: Bluetooth service connected
,10-26 22:39:50.726  3548  3644 I Keyboard.Facilitator.LanguageModelFlusher: run()
,10-26 22:39:50.726  3548  3644 I Keyboard.Facilitator: flushDynamicLanguageModels()
,10-26 22:39:50.753  3488  3488 I ConfigService: onCreate
,10-26 22:39:51.195   928  2863 D ConnectivityService: handlePromptUnvalidated 101
,10-26 22:39:53.347  5640  5652 D BluetoothAdapterState: Current state: ON, message: 23
10-26 22:39:53.347  5640  5652 D BluetoothAdapterProperties: Setting state to 13
10-26 22:39:53.347  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-26 22:39:53.348  5640  5652 D BluetoothAdapterProperties: onBluetoothDisable()
,10-26 22:39:53.350  5640  5652 I BluetoothAdapterState: Entering PendingCommandState
,10-26 22:39:53.357  5640  5656 D BluetoothAdapterProperties: Scan Mode:20
10-26 22:39:53.358  5640  5640 D BluetoothMapService: onReceive
10-26 22:39:53.358  5640  5640 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 22:39:53.358  5640  5640 D BluetoothMapService: STATE_TURNING_OFF
10-26 22:39:53.358  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-26 22:39:53.359  5640  5640 D BluetoothMapService: MAP Service closeService in
10-26 22:39:53.359  5640  5640 D BluetoothMapMasInstance0: MAP Service shutdown
10-26 22:39:53.359  5640  5640 D ObexServerSockets0: shutdown(block = true)
10-26 22:39:53.361  5640  5640 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 22:39:53.361  5640  5679 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-26 22:39:53.361  5640  5640 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-26 22:39:53.362  5640  5680 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-26 22:39:53.363  5640  5665 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-26 22:39:53.365  5640  5640 I BtOppRfcommListener: stopping Accept Thread
,10-26 22:39:53.365  5640  5689 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-26 22:39:53.365  5640  5689 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-26 22:39:53.367  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:39:53.367  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:53.367  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:53.367  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:53.367  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:53.367  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:53.367  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:53.367  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:53.367  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:53.368  5533  5533 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 22:39:53.369  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:53.369  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:53.369  5640  5640 D HeadsetService: Received stop request...Stopping profile...
10-26 22:39:53.375  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:53.376  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:53.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:53.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:53.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:53.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:53.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:53.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:53.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:53.376  3677  3702 D BluetoothHeadset: Proxy object disconnected
,10-26 22:39:53.376   928   928 D BluetoothHeadset: Proxy object disconnected
10-26 22:39:53.377  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:53.377  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:53.378  5533  5544 D BluetoothHeadset: Proxy object disconnected
10-26 22:39:53.378   928   928 D BluetoothHeadset: Proxy object disconnected
,10-26 22:39:53.379  3034  3048 D BluetoothHeadset: Proxy object disconnected
10-26 22:39:53.379   928   928 D BluetoothHeadset: Proxy object disconnected
10-26 22:39:53.379  5533  5533 D DockEventReceiver: finishStartingService: stopping service
10-26 22:39:53.380  5533  5533 D HeadsetProfile: Bluetooth service disconnected
10-26 22:39:53.380  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:53.381  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:39:53.381  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:39:53.381  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:39:53.381  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:39:53.381  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:39:53.381  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:39:53.381  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:39:53.381  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:39:53.381  3034  3034 D HeadsetProfile: Bluetooth service disconnected
10-26 22:39:53.381  5640  5640 D A2dpService: Received stop request...Stopping profile...
10-26 22:39:53.381  5640  5671 D A2dpStateMachine: Exit Disconnected: -1
10-26 22:39:53.381  5475  5475 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:39:53.381  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:39:53.385   928   928 D BluetoothA2dp: Proxy object disconnected
,10-26 22:39:53.385  3034  3034 D BluetoothA2dp: Proxy object disconnected
10-26 22:39:53.385  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:53.386  5533  5533 D BluetoothA2dp: Proxy object disconnected
,10-26 22:39:53.386  5640  5640 D HidService: Received stop request...Stopping profile...
10-26 22:39:53.386  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:53.387  5640  5640 D HidService: Stopping Bluetooth HidService
10-26 22:39:53.387  3034  3034 D BluetoothInputDevice: Proxy object disconnected
10-26 22:39:53.387  3034  3034 D HidProfile: Bluetooth service disconnected
10-26 22:39:53.388  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:53.389  5640  5640 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:39:53.389  5640  5640 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:53.389  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:53.389  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:53.390  5640  5640 D HealthService: Received stop request...Stopping profile...
10-26 22:39:53.390  3488  3488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 22:39:53.392  5533  5533 D BluetoothInputDevice: Proxy object disconnected
,10-26 22:39:53.392  5533  5533 D HidProfile: Bluetooth service disconnected
,10-26 22:39:53.393  5640  5640 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-26 22:39:53.393  5640  5640 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-26 22:39:53.393  5640  5663 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:53.393  5640  5663 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:53.393  5640  5663 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 22:39:53.393  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-26 22:39:53.393  5640  5656 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-26 22:39:53.393  5640  5640 D PanService: Received stop request...Stopping profile...
10-26 22:39:53.394  3034  3034 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 22:39:53.394  3034  3034 D PanProfile: Bluetooth service disconnected
,10-26 22:39:53.395  5640  5640 D BluetoothMapService: Received stop request...Stopping profile...
10-26 22:39:53.395  5640  5640 D BluetoothMapService: stop()
10-26 22:39:53.395  5640  5640 D BluetoothMapAppObserver: deinitObservers()
10-26 22:39:53.395  5640  5640 D BluetoothMapAppObserver: removeReceiver()
,10-26 22:39:53.395  5533  5533 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 22:39:53.395  5533  5533 D PanProfile: Bluetooth service disconnected
10-26 22:39:53.396  3034  3034 D BluetoothMap: Proxy object disconnected
10-26 22:39:53.396  3034  3034 D MapProfile: Bluetooth service disconnected
10-26 22:39:53.397  5533  5533 D BluetoothMap: Proxy object disconnected
10-26 22:39:53.397  5640  5640 D SapService: Received stop request...Stopping profile...
10-26 22:39:53.397  5533  5533 D MapProfile: Bluetooth service disconnected
10-26 22:39:53.397  5640  5640 V SapService: stop()
10-26 22:39:53.399  5640  5640 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:39:53.399  5640  5640 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:53.399  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:53.399  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:53.400  5640  5663 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:53.400  5640  5663 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:53.400  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-26 22:39:53.400  5640  5663 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 22:39:53.400  5640  5663 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 22:39:53.400  5640  5663 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-26 22:39:53.400  5640  5663 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-26 22:39:53.403  5640  5640 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:39:53.404  5640  5640 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:53.404  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:53.404  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:53.404  5640  5640 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-26 22:39:53.404  5640  5640 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,10-26 22:39:53.406  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 22:39:53.407  3034  3034 D BluetoothPbap: Proxy object disconnected
10-26 22:39:53.407  3034  3034 D PbapServerProfile: Bluetooth service disconnected
,10-26 22:39:53.408  5640  5640 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:39:53.408  5640  5640 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:53.408  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:53.408  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:39:53.408  5640  5640 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-26 22:39:53.408  5640  5656 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-26 22:39:53.409  5640  5640 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-26 22:39:53.409  5640  5640 V BluetoothAdapterState: isTurningOff()=true
10-26 22:39:53.409  5640  5640 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:53.409  5533  5533 D BluetoothPbap: Proxy object disconnected
,10-26 22:39:53.409  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:53.409  5533  5533 D PbapServerProfile: Bluetooth service disconnected
10-26 22:39:53.409  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:53.409  5640  5640 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-26 22:39:53.409  5640  5640 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-26 22:39:53.411  5640  5640 D BluetoothMapService: MAP Service closeService in
10-26 22:39:53.411  5640  5640 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:39:53.411  5640  5640 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:53.411  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:53.411  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:53.411  5640  5640 D BluetoothMapService: cleanup()
10-26 22:39:53.412  5640  5640 D BluetoothMapService: MAP Service closeService in
10-26 22:39:53.412  5640  5640 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:39:53.412  5640  5640 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:53.412  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:53.412  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:39:53.412  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-26 22:39:53.412  5640  5652 D BluetoothAdapterProperties: Setting state to 15
10-26 22:39:53.412  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,10-26 22:39:53.413  5640  5652 I BluetoothAdapterState: Entering BleOnState
,10-26 22:39:53.413   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 22:39:53.413   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:39:53.413  3034  3048 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 22:39:53.414  3677  3706 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:39:53.414  5533  5544 D BluetoothPan: onBluetoothStateChange on: false
10-26 22:39:53.415  5533  5545 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-26 22:39:53.415  3034  3046 D BluetoothMap: onBluetoothStateChange: up=false
10-26 22:39:53.416  5533  5676 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 22:39:53.417  3034  3802 D BluetoothPan: onBluetoothStateChange on: false
10-26 22:39:53.417  5533  5544 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:39:53.418  3034  3048 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:39:53.418  5533  5545 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 22:39:53.418   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 22:39:53.419  3034  3046 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 22:39:53.419  5533  5676 D BluetoothMap: onBluetoothStateChange: up=false
,10-26 22:39:53.419   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 22:39:53.420  3034  3802 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 22:39:53.420  5640  5652 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-26 22:39:53.420  5640  5652 D BluetoothAdapterProperties: Setting state to 16
10-26 22:39:53.420  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-26 22:39:53.421  5640  5652 D BluetoothAdapterProperties: onBleDisable
10-26 22:39:53.421  5640  5652 I BluetoothAdapterState: Entering PendingCommandState
,10-26 22:39:53.421  5640  5653 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-26 22:39:53.422  5640  5663 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-26 22:39:53.422  5640  5663 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:39:53.422  5640  5656 D BluetoothAdapterProperties: Scan Mode:20
10-26 22:39:53.423  5533  5533 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 22:39:53.424  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:53.426  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:53.427  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:53.428  3488  3488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 22:39:53.429  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:53.431  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:39:53.432  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:39:53.435  5533  5533 D DockEventReceiver: finishStartingService: stopping service
,10-26 22:39:53.630  5640  5656 I bt_hci  : shut_down
,10-26 22:39:53.634  5640  5660 D bt_hwcfg: hw_epilog_process
,10-26 22:39:53.635  5640  5660 I bt_vendor: low_power_mode_cb
,10-26 22:39:53.639  5640  5660 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-26 22:39:53.639  5640  5660 I bt_vendor: epilog_cb
10-26 22:39:53.639  5640  5660 I bt_hci  : epilog_finished_callback
,10-26 22:39:53.645  5640  5656 I bt_hci_h4: hal_close
,10-26 22:39:53.646  5640  5656 I bt_userial_vendor: device fd = 54 close
,10-26 22:39:53.758  5640  5653 D bt_stack_manager: event_shut_down_stack finished.
,10-26 22:39:53.759  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-26 22:39:53.763  5640  5652 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-26 22:39:53.763  5640  5640 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-26 22:39:53.764  5640  5640 D BtGatt.GattService: Received stop request...Stopping profile...
,10-26 22:39:53.765  5640  5640 D BtGatt.GattService: stop()
10-26 22:39:53.765  5640  5640 D BtGatt.AdvertiseManager: advertise clients cleared
10-26 22:39:53.768  5640  5640 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:39:53.768  5640  5640 V BluetoothAdapterState: isTurningOn()=false
10-26 22:39:53.768  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:39:53.768  5640  5640 V BluetoothAdapterState: isBleTurningOff()=true
10-26 22:39:53.769  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-26 22:39:53.769  5640  5652 D BluetoothAdapterProperties: Setting state to 10
10-26 22:39:53.769  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-26 22:39:53.770  5640  5652 I BluetoothAdapterState: Entering OffState
10-26 22:39:53.771   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-26 22:39:53.786  5640  5640 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-26 22:39:53.786  5640  5640 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-26 22:39:53.786  5640  5640 I BluetoothServiceJni: cleanupNative: return from cleanup
10-26 22:39:53.789  5640  5653 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-26 22:39:53.795  5640  5640 I art     : System.exit called, status: 0
,10-26 22:39:53.796  5640  5640 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-26 22:39:53.828   928   939 I ActivityManager: Process com.android.bluetooth (pid 5640) has died
,10-26 22:39:54.660   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:55.661   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:55.780  3488  3488 I ConfigService: onDestroy
,10-26 22:39:56.662   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:57.663   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:58.345  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:39:58.345  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:39:58.350  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:39:58.350  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59a0917 removed from the list
,10-26 22:39:58.350  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:39:58.350  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:39:58.350  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:39:58.353  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:39:58.353  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80fa6ed added. We now have 4 listener(s)
,10-26 22:39:58.353  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:39:58.355  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:39:58.355  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80fa6ed removed from the list
,10-26 22:39:58.356  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:39:58.356  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:39:58.356  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:39:58.358  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:39:58.358  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd47922 added. We now have 4 listener(s)
10-26 22:39:58.358  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:39:58.664   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:39:59.664   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-26 22:40:02.725   928   948 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,10-26 22:40:02.731  3715  3715 W Binder_A: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32416]" dev="sockfs" ino=32416 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:40:02.737  3548  3548 I Keyboard.Facilitator: onFinishInput()
,10-26 22:40:02.731  3715  3715 W Binder_A: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32416]" dev="sockfs" ino=32416 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:40:02.753   928   948 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 22:40:02.753   928   948 I Adreno  : Build Date                       : 12/06/15
10-26 22:40:02.753   928   948 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 22:40:02.753   928   948 I Adreno  : Local Branch                     : mybranch17112971
10-26 22:40:02.753   928   948 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 22:40:02.753   928   948 I Adreno  : Remote Branch                    : NONE
10-26 22:40:02.753   928   948 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 22:40:02.789   381   402 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (152 us)
,10-26 22:40:03.371  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:03.406   928   945 I ActivityManager: Start proc 5699:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-26 22:40:03.466  5475  5475 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-26 22:40:03.466  5475  5475 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,10-26 22:40:03.497   928   948 I sensors : batch
,10-26 22:40:03.498   928   948 V KeyguardServiceDelegate: onScreenTurnedOff()
,10-26 22:40:03.503   928   948 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,10-26 22:40:03.504   928   948 I sensors : activate
10-26 22:40:03.504   381   381 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f95443c00
10-26 22:40:03.505   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
10-26 22:40:03.505   928   946 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
10-26 22:40:03.506   928  2638 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,10-26 22:40:03.507  5475  5475 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3e6636a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@8ac1fb3, 16908290=android.view.AbsSavedState$1@8ac1fb3}, android:focusedViewId=100}]}]
10-26 22:40:03.507  5475  5475 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
10-26 22:40:03.507  5475  5475 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-26 22:40:03.507  5475  5475 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
10-26 22:40:03.510   928  2638 I hubconnection: sensorhub said: 'activate 7 enable:0'
,10-26 22:40:03.542  5699  5699 D AdapterServiceConfig: Adding HeadsetService
,10-26 22:40:03.542  5699  5699 D AdapterServiceConfig: Adding A2dpService
10-26 22:40:03.542  5699  5699 D AdapterServiceConfig: Adding HidService
10-26 22:40:03.542  5699  5699 D AdapterServiceConfig: Adding HealthService
10-26 22:40:03.542  5699  5699 D AdapterServiceConfig: Adding PanService
10-26 22:40:03.542  5699  5699 D AdapterServiceConfig: Adding GattService
10-26 22:40:03.542  5699  5699 D AdapterServiceConfig: Adding BluetoothMapService
10-26 22:40:03.543  5699  5699 D AdapterServiceConfig: Adding SapService
,10-26 22:40:03.548  5699  5699 D BluetoothAdapterState: make() - Creating AdapterState
,10-26 22:40:03.548   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41e473e:true
,10-26 22:40:03.550  5699  5699 I bt_bluedroid: init
10-26 22:40:03.550  5699  5711 I BluetoothAdapterState: Entering OffState
,10-26 22:40:03.552  5699  5712 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-26 22:40:03.552  5699  5712 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-26 22:40:03.552  5699  5712 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-26 22:40:03.552  5699  5712 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-26 22:40:03.553  5699  5699 I bt_bluedroid: get_profile_interface socket
,10-26 22:40:03.555  5699  5699 I bt_bluedroid: get_profile_interface sdp
,10-26 22:40:03.555  5699  5715 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
10-26 22:40:03.555  5699  5715 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 22:40:03.557  5699  5709 I bt_bluedroid: config_hci_snoop_log
10-26 22:40:03.558   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-26 22:40:03.561  5699  5711 D BluetoothAdapterState: Current state: OFF, message: 0
,10-26 22:40:03.561  5699  5711 D BluetoothAdapterProperties: Setting state to 14
10-26 22:40:03.561  5699  5711 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-26 22:40:03.563  5699  5711 D BluetoothBondStateMachine: make
,10-26 22:40:03.565  5699  5716 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-26 22:40:03.567  5699  5711 I BluetoothAdapterState: Entering PendingCommandState
,10-26 22:40:03.567  5699  5699 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-26 22:40:03.569  5699  5699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
,10-26 22:40:03.569  5699  5699 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 22:40:03.569  5699  5699 D BtGatt.GattService: Received start request. Starting profile...
10-26 22:40:03.569  5699  5699 D BtGatt.GattService: start()
10-26 22:40:03.569  5699  5699 I bt_bluedroid: get_profile_interface gatt
,10-26 22:40:03.570  5699  5699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
10-26 22:40:03.570  5699  5699 D BtGatt.AdvertiseManager: advertise manager created
,10-26 22:40:03.573  5699  5699 V BluetoothAdapterState: isTurningOff()=false
10-26 22:40:03.573  5699  5699 V BluetoothAdapterState: isTurningOn()=false
10-26 22:40:03.573  5699  5699 V BluetoothAdapterState: isBleTurningOn()=true
10-26 22:40:03.573  5699  5699 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:40:03.574  5699  5711 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-26 22:40:03.575  5699  5711 I bt_bluedroid: bt_bluedroid
10-26 22:40:03.575  5699  5712 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-26 22:40:03.575  5699  5712 I bt_hci  : start_up
,10-26 22:40:03.580  5699  5712 I bt_vendor: alloc value 0xf3d4b871
10-26 22:40:03.580  5699  5712 I bt_vendor: init
10-26 22:40:03.580  5699  5712 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-26 22:40:03.580  5699  5712 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-26 22:40:03.689  5699  5712 D bt_hci  : start_up starting async portion
10-26 22:40:03.690  5699  5719 I bt_hci  : event_finish_startup
10-26 22:40:03.690  5699  5719 I bt_hci_h4: hal_open
,10-26 22:40:03.690  5699  5719 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-26 22:40:03.688  5720  5720 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-26 22:40:03.692  5699  5719 I bt_userial_vendor: device fd = 54 open
,10-26 22:40:03.706  5699  5719 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 22:40:03.709  5699  5719 D bt_hwcfg: Chipset BCM4358A3
,10-26 22:40:03.709  5699  5719 D bt_hwcfg: Target name = [BCM4358A3]
10-26 22:40:03.709  5699  5719 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-26 22:40:03.798   381   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,10-26 22:40:03.800   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,10-26 22:40:03.801   928  2990 D SurfaceControl: Excessive delay in setPowerMode(): 296ms
,10-26 22:40:03.821   928   948 I DreamManagerService: Entering dreamland.
10-26 22:40:03.823   928   948 I PowerManagerService: Dozing...
,10-26 22:40:03.823   928   943 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,10-26 22:40:03.838   938   938 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[31331]" dev="sockfs" ino=31331 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:40:03.838   938   938 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[31331]" dev="sockfs" ino=31331 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:40:03.841   928  3524 I sensors : batch
10-26 22:40:03.841   928  3524 I sensors : activate
,10-26 22:40:03.846   928  2638 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,10-26 22:40:03.846   928  2638 I hubconnection: sensorhub said: 'activate 21 enable:1'
,10-26 22:40:03.848   515  2903 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,10-26 22:40:03.868  3677  4624 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
10-26 22:40:03.868  3677  4624 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,10-26 22:40:03.868  3677  4624 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-26 22:40:03.868   528  1264 D         : oem-qmi: Connection accepted
10-26 22:40:03.868   528  1264 D         : oem-qmi: Waiting to accept connection
,10-26 22:40:03.870   928   928 I sensors : activate
10-26 22:40:03.870   515   515 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,10-26 22:40:03.873   928  2638 I hubconnection: sensorhub said: 'activate 31 enable:0'
,10-26 22:40:03.874  3677  4624 D         : oem_qmi_lib:output 0
10-26 22:40:03.875  3677  4624 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-26 22:40:03.892  3677  4624 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,10-26 22:40:03.892  3677  4624 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-26 22:40:03.892  3677  4624 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-26 22:40:03.892   528  1264 D         : oem-qmi: Connection accepted
10-26 22:40:03.893   528  1264 D         : oem-qmi: Waiting to accept connection
,10-26 22:40:03.899  3677  4624 D         : oem_qmi_lib:output 0
,10-26 22:40:03.899  3677  4624 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-26 22:40:04.183  5699  5719 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-26 22:40:04.184  5699  5719 D bt_hwcfg: Settlement delay -- 100 ms
10-26 22:40:04.184  5699  5719 I bt_hwcfg: Setting fw settlement delay to 100 
,10-26 22:40:04.318  5699  5719 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-26 22:40:04.319  5699  5719 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,10-26 22:40:04.320  5699  5719 I bt_hwcfg: vendor lib fwcfg completed
10-26 22:40:04.320  5699  5719 I bt_vendor: firmware callback
10-26 22:40:04.321  5699  5719 I bt_hci  : firmware_config_callback
,10-26 22:40:04.330  5699  5726 I bt_btu  : btu_task pending for preload complete event
,10-26 22:40:04.330  5699  5726 I bt_btu_task: Bluetooth chip preload is complete
,10-26 22:40:04.331  5699  5726 I bt_btu  : btu_task received preload complete event
,10-26 22:40:04.337  5699  5726 I         : BTE_InitTraceLevels -- TRC_HCI
,10-26 22:40:04.338  5699  5726 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-26 22:40:04.338  5699  5726 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-26 22:40:04.338  5699  5726 I         : BTE_InitTraceLevels -- TRC_AVDT
10-26 22:40:04.338  5699  5726 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-26 22:40:04.338  5699  5726 I         : BTE_InitTraceLevels -- TRC_A2D
10-26 22:40:04.338  5699  5726 I         : BTE_InitTraceLevels -- TRC_BNEP
10-26 22:40:04.338  5699  5726 I         : BTE_InitTraceLevels -- TRC_BTM
10-26 22:40:04.338  5699  5726 I         : BTE_InitTraceLevels -- TRC_GAP
,10-26 22:40:04.338  5699  5726 I         : BTE_InitTraceLevels -- TRC_PAN
10-26 22:40:04.339  5699  5726 I         : BTE_InitTraceLevels -- TRC_SDP
10-26 22:40:04.339  5699  5726 I         : BTE_InitTraceLevels -- TRC_GATT
10-26 22:40:04.339  5699  5726 I         : BTE_InitTraceLevels -- TRC_SMP
10-26 22:40:04.339  5699  5726 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-26 22:40:04.339  5699  5726 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-26 22:40:04.434  5699  5726 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cc9549
,10-26 22:40:04.434  5699  5726 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cc9549 
,10-26 22:40:04.454  5699  5715 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-26 22:40:04.457  5699  5715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 22:40:04.458  5699  5715 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 22:40:04.460  5699  5715 D BluetoothAdapterProperties: Name is: Nexus 6P
10-26 22:40:04.462  5699  5715 D BluetoothAdapterProperties: Scan Mode:20
10-26 22:40:04.463  5699  5715 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 22:40:04.463  5699  5715 D bt_hci  : do_postload posting postload work item
10-26 22:40:04.463  5699  5719 I bt_hci  : event_postload
10-26 22:40:04.463  5699  5719 I bt_vendor: sco_config_cb
,10-26 22:40:04.464  5699  5719 I bt_hci  : sco_config_callback postload finished.
10-26 22:40:04.466  5699  5715 D bt_bte_conf: Device ID record 1 : primary
10-26 22:40:04.466  5699  5715 D bt_bte_conf:   vendorId            = 000f
10-26 22:40:04.466  5699  5715 D bt_bte_conf:   vendorIdSource      = 0001
10-26 22:40:04.466  5699  5715 D bt_bte_conf:   product             = 1200
10-26 22:40:04.466  5699  5715 D bt_bte_conf:   version             = 1436
10-26 22:40:04.466  5699  5715 D bt_bte_conf:   clientExecutableURL = 
,10-26 22:40:04.466  5699  5715 D bt_bte_conf:   serviceDescription  = 
10-26 22:40:04.466  5699  5715 D bt_bte_conf:   documentationURL    = 
10-26 22:40:04.467  5699  5715 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-26 22:40:04.467  5699  5712 D bt_stack_manager: event_start_up_stack finished
10-26 22:40:04.468  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:40:04.468  5699  5711 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-26 22:40:04.469  5699  5711 D BluetoothAdapterProperties: Setting state to 15
10-26 22:40:04.469  5699  5711 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-26 22:40:04.470  5699  5711 I BluetoothAdapterState: Entering BleOnState
,10-26 22:40:04.476  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:04.477  5699  5711 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-26 22:40:04.478  5699  5711 D BluetoothAdapterProperties: Setting state to 11
,10-26 22:40:04.478  5699  5711 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-26 22:40:04.479  5699  5719 I bt_vendor: low_power_mode_cb
10-26 22:40:04.482  5699  5699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
10-26 22:40:04.483  5699  5699 D HeadsetService: Received start request. Starting profile...
10-26 22:40:04.485  5699  5699 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-26 22:40:04.486  5699  5699 D HeadsetStateMachine: make
10-26 22:40:04.489  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:04.491  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:04.497  5699  5699 D HeadsetStateMachine: max_hf_connections = 1
10-26 22:40:04.497  5699  5699 I bt_bluedroid: get_profile_interface handsfree
,10-26 22:40:04.497  5699  5715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-26 22:40:04.498  5699  5715 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-26 22:40:04.503  5699  5699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
,10-26 22:40:04.504  5699  5699 D A2dpService: Received start request. Starting profile...
,10-26 22:40:04.504  5699  5711 I BluetoothAdapterState: Entering PendingCommandState
10-26 22:40:04.504  5699  5699 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-26 22:40:04.505  5699  5699 I bt_bluedroid: get_profile_interface avrcp
,10-26 22:40:04.510  5699  5699 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-26 22:40:04.511  5699  5699 I BluetoothA2dpServiceJni: classInitNative: succeeds
,10-26 22:40:04.511  5699  5699 D A2dpStateMachine: make
,10-26 22:40:04.512  5699  5699 I bt_bluedroid: get_profile_interface a2dp
,10-26 22:40:04.513  5699  5715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-26 22:40:04.514  5699  5735 D A2dpStateMachine: Enter Disconnected: -2
10-26 22:40:04.514  5699  5699 I BluetoothHidServiceJni: classInitNative: succeeds
,10-26 22:40:04.515  5699  5699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
10-26 22:40:04.516  5699  5699 D HidService: Received start request. Starting profile...
,10-26 22:40:04.516  5699  5699 I bt_bluedroid: get_profile_interface hidhost
10-26 22:40:04.516  5699  5699 D HidService: setHidService(): set to: null
10-26 22:40:04.516  5699  5715 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3caa56d
10-26 22:40:04.516  5699  5715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-26 22:40:04.517  5699  5699 I BluetoothHealthServiceJni: classInitNative: succeeds
10-26 22:40:04.517  5699  5699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
,10-26 22:40:04.518  5699  5699 D HealthService: Received start request. Starting profile...
,10-26 22:40:04.519  5699  5699 I bt_bluedroid: get_profile_interface health
,10-26 22:40:04.522  5699  5699 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-26 22:40:04.523  5699  5699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
,10-26 22:40:04.523  3488  3488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 22:40:04.524  5699  5699 D PanService: Received start request. Starting profile...
10-26 22:40:04.524  5699  5699 D BluetoothPanServiceJni: initializeNative(L110): pan
10-26 22:40:04.524  5699  5699 I bt_bluedroid: get_profile_interface pan
10-26 22:40:04.525  5699  5715 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-26 22:40:04.526  5699  5699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
,10-26 22:40:04.527  5699  5699 D BluetoothMapService: Received start request. Starting profile...
,10-26 22:40:04.527  5699  5699 D BluetoothMapService: start()
10-26 22:40:04.529  5699  5699 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-26 22:40:04.530  5699  5699 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-26 22:40:04.530  5699  5699 D BluetoothMapAppObserver: createReceiver()
10-26 22:40:04.531  5699  5699 D BluetoothMapAppObserver: initObservers()
10-26 22:40:04.531  5699  5699 D BluetoothMapAppObserver: getEnabledAccountItems()
10-26 22:40:04.536  5699  5699 V BluetoothAdapterState: isTurningOff()=false
10-26 22:40:04.536  5699  5699 V BluetoothAdapterState: isTurningOn()=true
10-26 22:40:04.536  5699  5699 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:40:04.536  5699  5699 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:40:04.537  5699  5731 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=1
10-26 22:40:04.538  5699  5699 V SapService: SapBinder()
10-26 22:40:04.538  5699  5699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
10-26 22:40:04.538  5699  5699 D SapService: Received start request. Starting profile...
10-26 22:40:04.538  5699  5699 V SapService: start()
10-26 22:40:04.539  5699  5699 V BluetoothAdapterState: isTurningOff()=false
10-26 22:40:04.539  5699  5699 V BluetoothAdapterState: isTurningOn()=true
10-26 22:40:04.539  5699  5699 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:40:04.539  5699  5699 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:40:04.539  5699  5699 V BluetoothAdapterState: isTurningOff()=false
10-26 22:40:04.539  5699  5699 V BluetoothAdapterState: isTurningOn()=true
10-26 22:40:04.539  5699  5699 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:40:04.539  5699  5699 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:40:04.540  5699  5699 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:40:04.540  5699  5699 V BluetoothAdapterState: isTurningOn()=true
10-26 22:40:04.540  5699  5699 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:40:04.540  5699  5699 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:40:04.541  5699  5699 V BluetoothAdapterState: isTurningOff()=false
10-26 22:40:04.541  5699  5699 V BluetoothAdapterState: isTurningOn()=true
10-26 22:40:04.541  5699  5699 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:40:04.541  5699  5699 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:40:04.541  5699  5699 V BluetoothAdapterState: isTurningOff()=false
10-26 22:40:04.541  5699  5699 V BluetoothAdapterState: isTurningOn()=true
10-26 22:40:04.541  5699  5699 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:40:04.541  5699  5699 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:40:04.542  5699  5699 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:40:04.542  5699  5699 V BluetoothAdapterState: isTurningOn()=true
10-26 22:40:04.542  5699  5699 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:40:04.542  5699  5699 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:40:04.542  5699  5711 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-26 22:40:04.542  5699  5711 D BluetoothAdapterProperties: ScanMode =  20
10-26 22:40:04.542  5699  5711 D BluetoothAdapterProperties: State =  11
10-26 22:40:04.543  5699  5715 D BluetoothAdapterProperties: Scan Mode:21
10-26 22:40:04.544  5699  5715 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 22:40:04.544  5699  5711 D BluetoothAdapterProperties: Setting state to 12
10-26 22:40:04.544  5699  5711 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-26 22:40:04.544  5475  5475 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 22:40:04.544  5699  5711 I BluetoothAdapterState: Entering OnState
10-26 22:40:04.544   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:40:04.544   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:40:04.545  3034  3046 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-26 22:40:04.548  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:40:04.548  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:04.548  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:04.548  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:40:04.548  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:04.548  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:40:04.548  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:40:04.548  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:40:04.548  3677  3702 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:40:04.548  3034  3034 D BluetoothA2dp: Proxy object connected
10-26 22:40:04.549  5533  5676 D BluetoothPan: onBluetoothStateChange on: true
,10-26 22:40:04.550  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:40:04.552  5533  5544 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-26 22:40:04.554  3034  3048 D BluetoothMap: onBluetoothStateChange: up=true
10-26 22:40:04.555  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:40:04.555  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:04.555  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:04.555  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:40:04.555  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:04.555  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:40:04.555  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:40:04.555  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:40:04.555  5533  5545 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-26 22:40:04.556  3034  3034 D BluetoothMap: Proxy object connected
10-26 22:40:04.556  3034  3034 D MapProfile: Bluetooth service connected
10-26 22:40:04.556  3034  3034 D BluetoothMap: getConnectedDevices()
10-26 22:40:04.556  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:40:04.557  5699  5699 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 22:40:04.557  3034  3802 D BluetoothPan: onBluetoothStateChange on: true
10-26 22:40:04.557  5699  5699 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-26 22:40:04.558  5533  5533 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 22:40:04.558  5533  5533 D PanProfile: Bluetooth service connected
10-26 22:40:04.558  3034  3034 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 22:40:04.558  5533  5533 D BluetoothA2dp: Proxy object connected
,10-26 22:40:04.558  5699  5699 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:40:04.558  3034  3034 D PanProfile: Bluetooth service connected
10-26 22:40:04.559  5533  5544 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:40:04.559  3034  3046 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:40:04.560  5699  5699 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:40:04.560  5533  5676 D BluetoothPbap: onBluetoothStateChange: up=true
,10-26 22:40:04.561  5699  5699 D ObexServerSockets: Succeed to create listening sockets 
,10-26 22:40:04.561  5699  5699 D ObexServerSockets0: startAccept()
10-26 22:40:04.561  5699  5699 D ObexServerSockets0: prepareForNewConnect()
10-26 22:40:04.561   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 22:40:04.562   928   928 D BluetoothA2dp: Proxy object connected
10-26 22:40:04.562  3034  3802 D BluetoothPbap: onBluetoothStateChange: up=true
,10-26 22:40:04.564  5533  5545 D BluetoothMap: onBluetoothStateChange: up=true
10-26 22:40:04.564  5699  5699 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-26 22:40:04.564  5699  5699 D BluetoothSdpJni: SDP Create record success - handle: 0
10-26 22:40:04.565  5699  5740 D ObexServerSockets0: Accepting socket connection...
,10-26 22:40:04.565  5699  5741 D ObexServerSockets0: Accepting socket connection...
10-26 22:40:04.566  5533  5533 D BluetoothInputDevice: Proxy object connected
10-26 22:40:04.566  5533  5533 D HidProfile: Bluetooth service connected
,10-26 22:40:04.567   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 22:40:04.567  3034  3048 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 22:40:04.569  3034  3034 D BluetoothInputDevice: Proxy object connected
10-26 22:40:04.569  3034  3034 D HidProfile: Bluetooth service connected
,10-26 22:40:04.570  5475  5475 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 22:40:04.571   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,10-26 22:40:04.571  5699  5699 D BluetoothMapService: onReceive
10-26 22:40:04.571  5699  5699 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 22:40:04.571  5699  5699 D BluetoothMapService: STATE_ON
10-26 22:40:04.572  5533  5533 D BluetoothMap: Proxy object connected
10-26 22:40:04.572  5533  5533 D MapProfile: Bluetooth service connected
10-26 22:40:04.572  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:40:04.572  5533  5533 D BluetoothMap: getConnectedDevices()
10-26 22:40:04.573  5699  5743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:40:04.575  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:04.575  5699  5743 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-26 22:40:04.575  5699  5743 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-26 22:40:04.579  5533  5533 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 22:40:04.585  3488  3488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 22:40:04.585  5533  5533 D DockEventReceiver: finishStartingService: stopping service
,10-26 22:40:04.592  5533  5533 D BluetoothPbap: Proxy object connected
,10-26 22:40:04.592  5533  5533 D PbapServerProfile: Bluetooth service connected
,10-26 22:40:04.596  5699  5699 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 22:40:04.596  5699  5699 D ObexServerSockets0: prepareForNewConnect()
,10-26 22:40:04.598  3034  3034 D BluetoothPbap: Proxy object connected
,10-26 22:40:04.599  3034  3034 D PbapServerProfile: Bluetooth service connected
,10-26 22:40:04.600  5699  5747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:40:04.612  5699  5751 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:40:04.613  5699  5751 I BtOppRfcommListener: Accept thread started.
,10-26 22:40:04.648  3677  3706 D BluetoothHeadset: Proxy object connected
,10-26 22:40:04.648   928   928 D BluetoothHeadset: Proxy object connected
,10-26 22:40:04.649  5533  5676 D BluetoothHeadset: Proxy object connected
,10-26 22:40:04.649   928   928 D BluetoothHeadset: Proxy object connected
10-26 22:40:04.649  3034  3802 D BluetoothHeadset: Proxy object connected
10-26 22:40:04.649  3034  3034 D HeadsetProfile: Bluetooth service connected
,10-26 22:40:04.650   928   928 D BluetoothHeadset: Proxy object connected
10-26 22:40:04.650  3677  4115 D BluetoothHeadset: Proxy object connected
10-26 22:40:04.650  5533  5533 D HeadsetProfile: Bluetooth service connected
,10-26 22:40:04.660  5533  5544 D BluetoothHeadset: Proxy object connected
,10-26 22:40:04.660  3034  3048 D BluetoothHeadset: Proxy object connected
,10-26 22:40:04.660  5533  5533 D HeadsetProfile: Bluetooth service connected
10-26 22:40:04.660  3034  3034 D HeadsetProfile: Bluetooth service connected
,10-26 22:40:04.668   928   945 D BluetoothHeadset: Proxy object connected
,10-26 22:40:07.188  3607  4319 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,10-26 22:40:08.386  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:40:08.386  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:08.386  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:08.386  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:40:08.386  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:08.386  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:40:08.386  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:40:08.386  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 22:40:08.392  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:40:08.393  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:40:08.393  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd47922 removed from the list
10-26 22:40:08.393  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:40:08.393  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:40:08.393  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:08.396  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:08.396  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a643970 added. We now have 4 listener(s)
10-26 22:40:08.396  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:40:08.400   928   938 D WifiService: setWifiEnabled: false pid=5475, uid=10077
,10-26 22:40:08.400   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:40:13.409  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:13.411   928  3032 D WifiService: setWifiEnabled: true pid=5475, uid=10077
10-26 22:40:13.411   928  3032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:40:13.420   510   921 D SoftapController: Softap fwReload - Ok
,10-26 22:40:13.426   510   921 D CommandListener: Setting iface cfg
,10-26 22:40:13.426   510   921 D CommandListener: Trying to bring down wlan0
,10-26 22:40:13.428   510   921 D CommandListener: Clearing all IP addresses on wlan0
,10-26 22:40:13.435   928  2855 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 22:40:14.112   928  2855 D wifi    : set interface wlan0 flags (UP)
,10-26 22:40:14.114   928  2855 I WifiHAL : Initializing wifi
,10-26 22:40:14.114   928  2855 I WifiHAL : Creating socket
,10-26 22:40:14.121   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-26 22:40:14.125   928  2855 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-26 22:40:14.125   928  2855 D wifi    : Did set static halHandle = 0x7f8a19b180
10-26 22:40:14.125   928  2855 D wifi    : halHandle = 0x7f8a19b180, mVM = 0x7fa634d140, mCls = 0x20164a
10-26 22:40:14.126   928  2855 D wifi    : array field set
10-26 22:40:14.126   928  2855 I WifiNative-HAL: interface[0] = wlan0
10-26 22:40:14.128   928  5756 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547777786240
10-26 22:40:14.128   928  5756 D wifi    : waitForHalEvents called, vm = 0x7fa634d140, obj = 0x20164a, env = 0x7f8dcb9f80
,10-26 22:40:14.190  5757  5757 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-26 22:40:14.230   928  2855 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-26 22:40:14.241  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:14.243  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:14.269  5757  5757 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 22:40:14.296  5757  5757 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 22:40:14.296  5757  5757 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-26 22:40:14.320   928  2855 D WifiConfigStore: Loading config and enabling all networks 
,10-26 22:40:14.326  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:40:14.326  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:14.326  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:14.326  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:40:14.326  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:14.326  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:40:14.326  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:40:14.326  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 22:40:14.329  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:40:14.332  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:40:14.332  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:14.332  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:14.332  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:40:14.332  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:14.332  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:40:14.332  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:40:14.332  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:40:14.333  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:40:14.349   928  2855 D WifiConfigStore: loaded 0 passpoint configs
,10-26 22:40:14.350   928  2855 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,10-26 22:40:14.350   928  2855 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-26 22:40:14.351   928  2855 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-26 22:40:14.351   928  2855 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-26 22:40:14.352   928  2855 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,10-26 22:40:14.353   928  2855 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-26 22:40:14.353   928  2855 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-26 22:40:14.353   928  2855 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
10-26 22:40:14.353   928  2855 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-26 22:40:14.353   928  2855 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-26 22:40:14.353   928  2855 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-26 22:40:14.354   928  2855 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-26 22:40:14.356   928  2855 D WifiNative-HAL: Setting external_sim to 1
,10-26 22:40:14.357   928  2855 D wifi    : setting dfs flag to true, 0x7f8c1da7e0
10-26 22:40:14.357  4347  4347 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 22:40:14.357   928  2855 D WifiStateMachine: Setting OUI to DA-A1-19
10-26 22:40:14.357   928  2855 D wifi    : setting scan oui 0x7f8c1da7e0
10-26 22:40:14.357   928  2855 D WifiHAL : Sending mac address OUI
,10-26 22:40:14.362   928  2855 E native  : do suspend true
,10-26 22:40:14.371   928  2855 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-26 22:40:14.371   928   928 D RttService: SCAN_AVAILABLE : 3
10-26 22:40:14.371   928  2967 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-26 22:40:14.371   510   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-26 22:40:14.372   510   921 D CommandListener: Setting iface cfg
,10-26 22:40:14.383   928  2854 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
10-26 22:40:14.383   928  2854 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-26 22:40:14.386   928  2854 D WifiNative-HAL: p2pGetDeviceAddress
,10-26 22:40:14.386   928  2854 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-26 22:40:14.399   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164355 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,10-26 22:40:14.666   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:40:15.667   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:40:16.669   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:40:17.543  5757  5757 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-26 22:40:17.574   928  2855 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-26 22:40:17.583   928  2855 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,10-26 22:40:17.583   928  2855 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:40:17.598   928  2855 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-26 22:40:17.636   928  2855 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-26 22:40:17.669   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:40:17.974  5757  5757 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-26 22:40:18.005  5757  5757 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-26 22:40:18.005  5757  5757 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-26 22:40:18.015   928  2855 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 22:40:18.016   928  2855 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:40:18.016   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-26 22:40:18.035   928  2855 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:40:18.047   510   921 D CommandListener: Setting iface cfg
,10-26 22:40:18.052   928  2855 D WifiStateMachine: Start Dhcp Watchdog 3
,10-26 22:40:18.056   928  2855 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-26 22:40:18.060   928  5762 D DhcpClient: Receive thread started
,10-26 22:40:18.142   928  2855 E native  : do suspend false
,10-26 22:40:18.158   928  5761 D DhcpClient: Broadcasting DHCPDISCOVER
,10-26 22:40:18.171   928  5762 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-26 22:40:18.172   928  5761 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-26 22:40:18.174   928  5761 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-26 22:40:18.193   928  5762 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-26 22:40:18.195   928  5761 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-26 22:40:18.199   510   921 D CommandListener: Setting iface cfg
,10-26 22:40:18.204   928  2855 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-26 22:40:18.207   928  2855 E native  : do suspend true
,10-26 22:40:18.207   928  5761 D DhcpClient: Scheduling renewal in 86399s
,10-26 22:40:18.226   928  2855 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-26 22:40:18.228   928  2855 D WifiConfigStore: No blacklist allowed without epno enabled
10-26 22:40:18.229   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-26 22:40:18.231   928  2863 D ConnectivityService: Adding iface wlan0 to network 102
10-26 22:40:18.234   928  2855 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-26 22:40:18.284   928  2863 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-26 22:40:18.284   928  2863 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-26 22:40:18.286   928  2863 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-26 22:40:18.288   928  2863 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-26 22:40:18.292   928  2863 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-26 22:40:18.300   928  2863 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-26 22:40:18.305   928  2863 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-26 22:40:18.305   928  2863 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-26 22:40:18.305   928  2863 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-26 22:40:18.305   928  2855 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,10-26 22:40:18.305   928  2863 D ConnectivityService:    accepting network in place of null
10-26 22:40:18.306   928  2855 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 22:40:18.306   928  2863 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 22:40:18.327   928  5760 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168283, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-26 22:40:18.337   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:40:18.361   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:40:18.364   928  2863 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-26 22:40:18.365   928  2863 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-26 22:40:18.365  3637  3776 W QCNEJ   : |CORE| network available: 102
,10-26 22:40:18.366   928  2863 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,10-26 22:40:18.367   928   945 D Tethering: MasterInitialState.processMessage what=3
10-26 22:40:18.371  3637  3776 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-26 22:40:18.372  3637  3776 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-26 22:40:18.372  3637  3776 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-26 22:40:18.376  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:40:18.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:18.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:18.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:40:18.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:18.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:40:18.376  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:40:18.378  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.378  4894  4918 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-26 22:40:18.378  4894  4918 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 22:40:18.378  4894  4918 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-26 22:40:18.379  4894  4918 E SarControlService: no key has been found,reset the power
10-26 22:40:18.379  4894  4954 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 22:40:18.379  4894  4954 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 22:40:18.379  4894  4954 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-26 22:40:18.379  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 22:40:18.379  4937  4937 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 22:40:18.380  4894  4954 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-26 22:40:18.380  4894  4954 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 22:40:18.381  4894  4954 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-26 22:40:18.382  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:40:18.382  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:18.382  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:18.382  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:40:18.382  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:18.382  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.382  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:40:18.382  5475  5475 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:40:18.382  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 22:40:18.383  4937  4937 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-26 22:40:18.384  3864  3864 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-26 22:40:18.384  5475  5475 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:40:18.387  3883  3883 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-26 22:40:18.389  4937  4956 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ee87586 HexData = [00000000f003000000000000ffffffff]
10-26 22:40:18.390  4937  4956 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 22:40:18.390  4937  4956 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-26 22:40:18.390  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 22:40:18.390  4894  4904 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-26 22:40:18.391  3883  3883 D SystemUpdateService: onCreate
,10-26 22:40:18.396   928  5759 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-26 22:40:18.399  3883  3883 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-26 22:40:18.400  4937  4956 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ee87586 HexData = [00000000f103000000000000ffffffff]
10-26 22:40:18.400  4937  4956 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 22:40:18.400  4937  4956 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-26 22:40:18.401  4937  4937 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-26 22:40:18.401  4894  4905 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-26 22:40:18.411  3883  3883 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-26 22:40:18.416  3883  5271 I iu.UploadsManager: num queued entries: 0
,10-26 22:40:18.416  3883  5271 I iu.UploadsManager: num updated entries: 0
,10-26 22:40:18.419  3883  5774 I SystemUpdateService: active receiver: enabled
,10-26 22:40:18.422  3883  3883 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-26 22:40:18.423  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:40:18.423  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:18.423  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:18.423  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:40:18.423  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:18.423  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.423  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:40:18.423  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:40:18.424  3883  3883 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-26 22:40:18.425  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:40:18.426  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.426  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a643970 removed from the list
,10-26 22:40:18.426  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:40:18.426  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:40:18.426  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.426  5274  5274 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:40:18.429  5475  5522 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-26 22:40:18.429  5475  5522 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-26 22:40:18.430  5274  5274 D SprintDMHelper: simOperator: 
10-26 22:40:18.430  5274  5274 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-26 22:40:18.431  5475  5522 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3e6636a Bundle[{}]
10-26 22:40:18.432  5475  5522 I io.jxcore.node.LifeCycleMonitor: start: OK
10-26 22:40:18.432  5475  5522 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-26 22:40:18.432  5475  5522 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-26 22:40:18.433  5475  5522 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-26 22:40:18.433  5475  5522 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-26 22:40:18.434  5475  5522 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-26 22:40:18.440  5475  5522 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
10-26 22:40:18.441  5475  5522 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-26 22:40:18.441  5475  5522 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
10-26 22:40:18.443  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:40:18.443  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ccc4e9 added. We now have 3 listener(s)
,10-26 22:40:18.445  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 22:40:18.445  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:40:18.445  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:40:18.445  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:18.446  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a65056e added. We now have 4 listener(s)
10-26 22:40:18.446  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:40:18.446  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 22:40:18.448  3883  5774 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 22:40:18.449  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:40:18.452  3883  5271 I iu.SyncManager: NEXT; no task
,10-26 22:40:18.453  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:40:18.453  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:18.453  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:18.453  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:40:18.453  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:18.453  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.453  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:40:18.453  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:40:18.455  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.455  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:40:18.455  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:40:18.455  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82b7c9c added. We now have 4 listener(s)
,10-26 22:40:18.456   928  5759 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 26 Oct 2016 20:40:18 GMT], X-Android-Received-Millis=[1477514418455], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477514418418]}
10-26 22:40:18.456   928  2863 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-26 22:40:18.456   928  2863 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-26 22:40:18.456   928  2863 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-26 22:40:18.456  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:40:18.456  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:40:18.456  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:40:18.457  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:18.457  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@723c6a5 added. We now have 5 listener(s)
10-26 22:40:18.457  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:40:18.457  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:40:18.457  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:40:18.457  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:40:18.457  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:40:18.457  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.457  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:40:18.457  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:40:18.457  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:40:18.457  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ccc4e9 removed from the list
10-26 22:40:18.457  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.457  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a65056e removed from the list
10-26 22:40:18.457   928  2863 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-26 22:40:18.459  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:18.459  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:40:18.459  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.460  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.460  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.460  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.462  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:18.463  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.463  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.463  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.463  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:40:18.463  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:40:18.463  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.463  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a65056e not in the list
10-26 22:40:18.463  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.463  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.463  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.464  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.464  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.464  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.465  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:40:18.465  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:40:18.465  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.465  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@723c6a5 removed from the list
10-26 22:40:18.465  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:40:18.465  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.465  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:40:18.465  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:40:18.465  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:40:18.465  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82b7c9c removed from the list
10-26 22:40:18.466  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:40:18.466  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9600a7a added. We now have 3 listener(s)
10-26 22:40:18.469  3883  5774 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-26 22:40:18.469  3883  5774 I SystemUpdateService: now status is 0 (complete)
10-26 22:40:18.469  3883  5774 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 22:40:18.469  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:40:18.469  3883  5774 I SystemUpdateService: file has been verified
,10-26 22:40:18.469  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:40:18.469  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:40:18.469  3883  5774 I SystemUpdateService: OTA package size = 21989297
10-26 22:40:18.469  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:18.470  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571d22b added. We now have 4 listener(s)
10-26 22:40:18.470  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:40:18.470  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 22:40:18.472  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:40:18.476  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:40:18.476  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:18.476  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:18.476  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:40:18.476  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:18.476  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.476  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:40:18.476  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:40:18.476  3883  5774 I SystemUpdateService: showing system update notification
,10-26 22:40:18.477  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:40:18.478  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:40:18.478  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:40:18.478  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2f2821 added. We now have 4 listener(s)
10-26 22:40:18.479  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:40:18.479  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-26 22:40:18.479  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:40:18.479  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:18.480  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d45446 added. We now have 5 listener(s)
10-26 22:40:18.480  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:40:18.480  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:40:18.480  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 22:40:18.480  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:40:18.480  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:40:18.480  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 22:40:18.480  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:18.483  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 22:40:18.483  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:40:18.483  5475  5522 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:40:18.483  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-26 22:40:18.486  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 22:40:18.486  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 22:40:18.486  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 22:40:18.488   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 22:40:18.490  3883  3883 D SystemUpdateService: onDestroy
10-26 22:40:18.490  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.490  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:40:18.490  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-26 22:40:18.490  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:40:18.490  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:40:18.490  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.492  5475  5522 D BluetoothAdapter: STATE_ON
,10-26 22:40:18.495  5699  5742 D BtGatt.GattService: registerClient() - UUID=da79de6a-bed0-4ac6-9460-afde1c21a902
,10-26 22:40:18.496  5699  5715 D BtGatt.GattService: onClientRegistered() - UUID=da79de6a-bed0-4ac6-9460-afde1c21a902, clientIf=5
,10-26 22:40:18.496  5475  5486 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-26 22:40:18.497  5699  5732 D BtGatt.GattService: start scan with filters
10-26 22:40:18.500  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 22:40:18.500  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.500  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 22:40:18.500  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.500  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.501  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:40:18.501  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:40:18.501  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.501  5699  5718 D BtGatt.ScanManager: handling starting scan
10-26 22:40:18.501  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.501  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:40:18.501  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.502  5699  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee77f3f
,10-26 22:40:18.503  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.503  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:40:18.503  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.503  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:40:18.503  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.503  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.503  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:40:18.504  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:40:18.504  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.506  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.506  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.506  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.507  5475  5522 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-26 22:40:18.507  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 22:40:18.507  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 22:40:18.507  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.507  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 22:40:18.507  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:40:18.507  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 22:40:18.507  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:40:18.507  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:40:18.507  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:40:18.507  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.507  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.507  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 22:40:18.508  5475  5522 D BluetoothAdapter: STATE_ON
,10-26 22:40:18.509  5699  5715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-26 22:40:18.509  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.509  5699  5742 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:40:18.509  5699  5718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 22:40:18.510  5699  5732 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 22:40:18.510  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 22:40:18.510  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.510  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:40:18.510  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.510  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.510  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:40:18.510  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 22:40:18.511  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.511  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.511  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:40:18.511  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.512  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.512  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:40:18.512  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.512  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.512  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.512  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.512  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.512  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 22:40:18.512  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.512  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.513  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.513  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 22:40:18.513  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 22:40:18.513  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:40:18.513  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.514  5699  5715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 22:40:18.514  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.514  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.514  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.514  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.514  5699  5718 D BtGatt.ScanManager: Starting BLE batch scan
10-26 22:40:18.515  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:40:18.515  5699  5718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 22:40:18.515  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:40:18.515  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:40:18.516  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:40:18.516  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:40:18.516  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:40:18.516  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:40:18.516  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.517  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:40:18.517  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:40:18.517  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:40:18.517  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9600a7a removed from the list
,10-26 22:40:18.517  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.517  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571d22b removed from the list
10-26 22:40:18.517  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:40:18.517  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.518  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.518  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.518  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.521  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.521  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.521  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.521  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:40:18.521  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 22:40:18.521  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.521  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571d22b not in the list
10-26 22:40:18.521  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.521  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.521  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.522  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.522  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.522  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.522  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 22:40:18.522  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:40:18.522  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.522  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d45446 removed from the list
10-26 22:40:18.523  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:40:18.523  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.523  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.523  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:40:18.523  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:40:18.523  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2f2821 removed from the list
10-26 22:40:18.523  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:40:18.523  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf16ed2 added. We now have 3 listener(s)
,10-26 22:40:18.524  5699  5715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:40:18.524  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.524  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:40:18.525  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:40:18.525  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:40:18.525  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:18.525  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afc5ba3 added. We now have 4 listener(s)
10-26 22:40:18.525  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:40:18.525  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 22:40:18.527  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:40:18.529  5699  5715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 22:40:18.529  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:40:18.531  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:40:18.531  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:18.531  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:18.531  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:40:18.531  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:18.531  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.531  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:40:18.531  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:40:18.533  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.533  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:40:18.533  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:40:18.533  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3ba59 added. We now have 4 listener(s)
10-26 22:40:18.534  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 22:40:18.535  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:40:18.535  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:40:18.535  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:18.535  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d53a61e added. We now have 5 listener(s)
10-26 22:40:18.535  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:40:18.535  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:40:18.535  5699  5715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 22:40:18.535  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.535  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:40:18.535  5699  5718 D BtGatt.ScanManager: stopping BLe Batch
10-26 22:40:18.535  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 22:40:18.536  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 22:40:18.536  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:40:18.536  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:40:18.536  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 22:40:18.538  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:40:18.540  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 22:40:18.540  5699  5715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 22:40:18.540  5475  5522 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:40:18.540  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.540  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 22:40:18.540  5699  5718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 22:40:18.544  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 22:40:18.544  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 22:40:18.544  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 22:40:18.545  5699  5715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 22:40:18.545  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.545  4347  5779 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-26 22:40:18.550  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.550  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:40:18.550  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:40:18.550  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:40:18.550  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:40:18.550  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.551  5475  5522 D BluetoothAdapter: STATE_ON
,10-26 22:40:18.552  5699  5709 D BtGatt.GattService: registerClient() - UUID=ffc52d5a-6a6a-4c5e-ae74-dfb5367960d2
,10-26 22:40:18.553  5699  5715 D BtGatt.GattService: onClientRegistered() - UUID=ffc52d5a-6a6a-4c5e-ae74-dfb5367960d2, clientIf=5
,10-26 22:40:18.553  5475  5597 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-26 22:40:18.553  5699  5742 D BtGatt.GattService: start scan with filters
10-26 22:40:18.555  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 22:40:18.555  5699  5718 D BtGatt.ScanManager: handling starting scan
10-26 22:40:18.555  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.555  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 22:40:18.555  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.555  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.555  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:40:18.556  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-26 22:40:18.556  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.556  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.556  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:40:18.556  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.558  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.558  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:40:18.558  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.558  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:40:18.558  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.558  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.558  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:40:18.559  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:40:18.560  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.560  5699  5715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 22:40:18.560  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.560  5699  5718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-26 22:40:18.561  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.562  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.562  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.562  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:40:18.562  5475  5522 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-26 22:40:18.562  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:40:18.562  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:40:18.562  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:40:18.562  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 22:40:18.562  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.562  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 22:40:18.562  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:40:18.562  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:40:18.562  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf16ed2 removed from the list
10-26 22:40:18.562  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.562  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afc5ba3 removed from the list
10-26 22:40:18.562  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:40:18.563  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:40:18.563  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.563  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-26 22:40:18.563  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.563  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:40:18.563  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.565  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.565  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.565  5699  5715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 22:40:18.565  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.565  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:40:18.565  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.565  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:40:18.565  5699  5718 D BtGatt.ScanManager: Starting BLE batch scan
10-26 22:40:18.565  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.565  5699  5718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 22:40:18.565  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afc5ba3 not in the list
10-26 22:40:18.565  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-26 22:40:18.565  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:40:18.565  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:40:18.565  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.565  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.565  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-26 22:40:18.566  5475  5522 D BluetoothAdapter: STATE_ON
,10-26 22:40:18.567  5699  5732 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:40:18.568  5699  5733 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-26 22:40:18.568  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-26 22:40:18.568  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.568  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:40:18.568  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.568  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.568  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:40:18.568  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 22:40:18.569  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.569  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.569  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-26 22:40:18.569  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.570  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.570  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:40:18.570  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.571  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.571  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.571  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.571  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.571  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 22:40:18.571  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.571  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.571  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.571  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 22:40:18.571  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 22:40:18.572  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.572  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.573  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.573  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.573  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.573  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:40:18.573  5699  5715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:40:18.573  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:40:18.573  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.573  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.573  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:40:18.574  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d53a61e removed from the list
10-26 22:40:18.574  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:40:18.574  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:40:18.574  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:40:18.574  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.574  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:40:18.574  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:40:18.574  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:40:18.574  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3ba59 removed from the list
10-26 22:40:18.575  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:40:18.575  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@110062a added. We now have 3 listener(s)
,10-26 22:40:18.576  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 22:40:18.577  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:40:18.577  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:40:18.577  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:18.577  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42f9c1b added. We now have 4 listener(s)
10-26 22:40:18.577  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:40:18.578  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 22:40:18.578  5699  5715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 22:40:18.579  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:40:18.580  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:40:18.584  5699  5715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-26 22:40:18.584  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.584  5699  5718 D BtGatt.ScanManager: stopping BLe Batch
10-26 22:40:18.585  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:40:18.585  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:18.585  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:18.585  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:40:18.585  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:18.585  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.585  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:40:18.585  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:40:18.588  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:40:18.588  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:40:18.588  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:40:18.588  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e615b91 added. We now have 4 listener(s)
10-26 22:40:18.589  5699  5715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 22:40:18.589  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.589  5699  5718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 22:40:18.589  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:40:18.589  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:40:18.589  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:40:18.589  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:18.589  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c805af6 added. We now have 5 listener(s)
10-26 22:40:18.589  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:40:18.589  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:40:18.589  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 22:40:18.589  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:40:18.589  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:40:18.590  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 22:40:18.590  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:18.592  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:18.594  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-26 22:40:18.594  5475  5522 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:40:18.594  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 22:40:18.596  5699  5715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 22:40:18.596  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:40:18.597  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 22:40:18.597  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-26 22:40:18.597  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 22:40:18.599  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.599  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:40:18.599  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:40:18.599  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:40:18.600  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:40:18.600  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.600  5475  5522 D BluetoothAdapter: STATE_ON
10-26 22:40:18.601  5699  5733 D BtGatt.GattService: registerClient() - UUID=04d2579f-bedf-4ddd-bef3-f92329a153c1
10-26 22:40:18.602  5699  5715 D BtGatt.GattService: onClientRegistered() - UUID=04d2579f-bedf-4ddd-bef3-f92329a153c1, clientIf=5
,10-26 22:40:18.602  5475  5486 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 22:40:18.602  5699  5732 D BtGatt.GattService: start scan with filters
10-26 22:40:18.604  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 22:40:18.604  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.604  5699  5718 D BtGatt.ScanManager: handling starting scan
,10-26 22:40:18.604  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 22:40:18.604  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.604  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.604  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:40:18.604  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:40:18.604  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.604  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.604  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:40:18.604  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.606  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.607  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:40:18.607  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:40:18.607  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.607  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.607  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.607  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:40:18.608  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:40:18.608  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.609  5699  5715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 22:40:18.609  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.610  5699  5718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-26 22:40:18.610  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.610  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.610  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.612  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:40:18.612  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:40:18.612  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:40:18.612  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:40:18.612  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.612  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 22:40:18.612  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:40:18.613  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-26 22:40:18.613  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@110062a removed from the list
10-26 22:40:18.613  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.613  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42f9c1b removed from the list
10-26 22:40:18.613  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:40:18.613  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:40:18.613  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.613  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-26 22:40:18.613  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.613  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:40:18.613  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.614  5699  5715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 22:40:18.614  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.614  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.614  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.614  5699  5718 D BtGatt.ScanManager: Starting BLE batch scan
,10-26 22:40:18.614  5699  5718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 22:40:18.614  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.614  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:40:18.614  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:40:18.614  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.614  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42f9c1b not in the list
10-26 22:40:18.614  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:40:18.614  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:40:18.614  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:40:18.615  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.615  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.615  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 22:40:18.615  5475  5522 D BluetoothAdapter: STATE_ON
,10-26 22:40:18.616  5699  5733 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:40:18.616  5699  5732 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 22:40:18.616  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 22:40:18.616  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.616  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:40:18.616  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.616  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.617  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:40:18.617  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 22:40:18.617  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.617  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.617  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:40:18.617  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.619  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.619  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:40:18.619  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.619  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.619  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.619  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.619  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.619  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-26 22:40:18.620  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.620  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.620  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.620  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 22:40:18.620  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-26 22:40:18.620  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.621  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.621  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.622  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.622  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.622  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:40:18.622  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 22:40:18.622  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.622  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:40:18.622  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c805af6 removed from the list
10-26 22:40:18.622  5475  5475 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:40:18.622  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:40:18.622  5475  5475 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:40:18.622  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.622  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.622  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:40:18.622  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:40:18.622  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e615b91 removed from the list
10-26 22:40:18.623  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:40:18.623  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcf3082 added. We now have 3 listener(s)
10-26 22:40:18.624  5699  5715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:40:18.624  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.624  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:40:18.624  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:40:18.625  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 22:40:18.625  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:18.625  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88b7393 added. We now have 4 listener(s)
10-26 22:40:18.625  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:40:18.625  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 22:40:18.628  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:40:18.630  5699  5715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-26 22:40:18.630  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:40:18.632  5475  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:40:18.632  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:40:18.632  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:40:18.632  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:40:18.632  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:40:18.632  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.632  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:40:18.632  5475  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:40:18.634  5475  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:40:18.634  5475  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:40:18.634  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:40:18.634  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19aebc9 added. We now have 4 listener(s)
10-26 22:40:18.635  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:40:18.635  5699  5715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 22:40:18.635  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.635  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:40:18.635  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:40:18.635  5699  5718 D BtGatt.ScanManager: stopping BLe Batch
10-26 22:40:18.636  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:40:18.636  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@943d2ce added. We now have 5 listener(s)
10-26 22:40:18.636  5475  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:40:18.636  5475  5522 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:40:18.636  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:40:18.636  5475  5522 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:40:18.636  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:40:18.636  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.636  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:40:18.636  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:40:18.636  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:40:18.636  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcf3082 removed from the list
10-26 22:40:18.636  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.636  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88b7393 removed from the list
10-26 22:40:18.637  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:40:18.639  5475  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:40:18.639  5475  5522 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:40:18.639  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:40:18.640  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.640  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.640  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.641  5699  5715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 22:40:18.641  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:40:18.641  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.641  5699  5718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 22:40:18.641  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.641  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.641  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:40:18.641  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:40:18.641  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.641  5475  5522 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88b7393 not in the list
,10-26 22:40:18.641  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.641  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.641  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.642  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:40:18.642  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.642  5475  5522 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:40:18.642  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:40:18.642  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:40:18.642  5475  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:40:18.643  5475  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@943d2ce removed from the list
10-26 22:40:18.643  5475  5522 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:40:18.643  5475  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:40:18.643  5475  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:40:18.643  5475  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:40:18.643  5475  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:40:18.643  5475  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19aebc9 removed from the list
10-26 22:40:18.644  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-26 22:40:18.644  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-26 22:40:18.644  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-26 22:40:18.644  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:40:18.644  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-26 22:40:18.644  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 22:40:18.645  5699  5715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 22:40:18.645  5699  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:40:18.670   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:40:19.016  5475  5475 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:40:19.074  5475  5475 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:40:19.122  5475  5475 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:40:19.670   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-26 22:40:20.825  5475  5786 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 22:40:20.825  5475  5786 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:40:21.621  5475  5786 W !!      : call onHalfStreamCopied
,10-26 22:40:21.621  5475  5786 I testCopyDataAndClose: closing input stream
,10-26 22:40:21.767  3488  5788 I VacuumService: Vacuum at: now=1477514421767 tag=VacuumService
,10-26 22:40:21.795  3488  5791 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-26 22:40:21.833  3488  5789 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-26 22:40:21.836  3488  5789 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-26 22:40:21.859  3488  5789 W Uploader:  no longer exists, so no auth token.
,10-26 22:40:21.865  3488  5791 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:40:22.143  3488  5793 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:40:22.231  3488  5791 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:40:22.300  3488  5789 W Uploader:  no longer exists, so no auth token.
,10-26 22:40:22.310  3488  5793 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:40:22.384  5475  5786 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 22:40:22.384  5475  5786 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:40:22.384  5475  5786 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 22:40:22.384  5475  5786 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:40:22.384  5475  5786 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-26 22:40:22.384  5475  5786 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 22:40:22.384  5475  5786 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 22:40:22.384  5475  5786 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-26 22:40:22.385  5475  5786 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-26 22:40:22.385  5475  5786 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 22:40:22.385  5475  5786 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-26 22:40:22.402  3488  5791 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:40:22.467  3488  5793 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:40:26.313   928  2863 D ConnectivityService: handlePromptUnvalidated 102
,10-26 22:40:26.523  5475  5798 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:40:26.523  5475  5798 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:40:28.523  5475  5522 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 177. Connection data: Peer properties: [null null].
10-26 22:40:28.523  5475  5522 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:40:28.523  5475  5522 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 177, name: My test thread name)
,10-26 22:40:28.630  5475  5798 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-26 22:40:28.630  5475  5798 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:40:28.630  5475  5798 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,10-26 22:40:28.665  5475  5799 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 22:40:28.665  5475  5799 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:40:30.294  5475  5799 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 22:40:30.294  5475  5799 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:40:30.294  5475  5799 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 22:40:30.294  5475  5799 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:40:30.294  5475  5799 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-26 22:40:30.294  5475  5799 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 22:40:30.295  5475  5799 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 22:40:30.295  5475  5799 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-26 22:40:30.295  5475  5799 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-26 22:40:30.295  5475  5799 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 22:40:30.295  5475  5799 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-26 22:40:34.425  5475  5800 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:40:34.425  5475  5800 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:40:34.425  5475  5800 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:40:34.425  5475  5800 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:40:34.426  5475  5800 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 22:40:34.426  5475  5800 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:40:34.426  5475  5800 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-26 22:40:34.426  5475  5800 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 22:40:34.426  5475  5800 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 22:40:34.426  5475  5800 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-26 22:40:34.426  5475  5800 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-26 22:40:34.426  5475  5800 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:40:34.426  5475  5800 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-26 22:40:34.428  5475  5522 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-26 22:40:34.431  5475  5801 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:40:34.431  5475  5801 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:40:34.432  5475  5801 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 185, thread name: My test thread name): Test exception.
,10-26 22:40:34.432  5475  5801 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:40:34.432  5475  5801 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-26 22:40:34.432  5475  5801 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-26 22:40:34.432  5475  5801 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:40:34.432  5475  5801 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-26 22:40:34.437  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-26 22:40:34.437  5475  5522 I jxcore-log: 
10-26 22:40:34.438  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-26 22:40:34.438  5475  5522 I jxcore-log: 
,10-26 22:40:34.438  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-26 22:40:34.438  5475  5522 I jxcore-log: 
10-26 22:40:34.438  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-26 22:40:34.438  5475  5522 I jxcore-log: 
10-26 22:40:34.439  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG UnitTest_app: 'Total duration:  91598'
10-26 22:40:34.439  5475  5522 I jxcore-log: 
,10-26 22:40:34.441  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-26 22:40:34.441  5475  5522 I jxcore-log: 
,10-26 22:40:34.445  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.445  5475  5522 I jxcore-log: 
10-26 22:40:34.446  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.446  5475  5522 I jxcore-log: 
,10-26 22:40:34.446  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.446  5475  5522 I jxcore-log: 
10-26 22:40:34.446  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.446  5475  5522 I jxcore-log: 
10-26 22:40:34.446  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-26 22:40:34.446  5475  5522 I jxcore-log: 
,10-26 22:40:34.447  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:40:34.447  5475  5522 I jxcore-log: 
10-26 22:40:34.447  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.447  5475  5522 I jxcore-log: 
,10-26 22:40:34.447  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.447  5475  5522 I jxcore-log: 
10-26 22:40:34.448  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-26 22:40:34.448  5475  5522 I jxcore-log: 
10-26 22:40:34.448  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:40:34.448  5475  5522 I jxcore-log: 
,10-26 22:40:34.448  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:40:34.448  5475  5522 I jxcore-log: 
,10-26 22:40:34.448  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.448  5475  5522 I jxcore-log: 
10-26 22:40:34.449  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.449  5475  5522 I jxcore-log: 
10-26 22:40:34.449  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:40:34.449  5475  5522 I jxcore-log: 
,10-26 22:40:34.449  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:40:34.449  5475  5522 I jxcore-log: 
10-26 22:40:34.449  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.449  5475  5522 I jxcore-log: 
,10-26 22:40:34.450  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:40:34.450  5475  5522 I jxcore-log: 
10-26 22:40:34.450  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.450  5475  5522 I jxcore-log: 
10-26 22:40:34.450  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.450  5475  5522 I jxcore-log: 
,10-26 22:40:34.450  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.450  5475  5522 I jxcore-log: 
10-26 22:40:34.451  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:40:34.451  5475  5522 I jxcore-log: 
10-26 22:40:34.451  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:40:34.451  5475  5522 I jxcore-log: 
,10-26 22:40:34.451  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:40:34.451  5475  5522 I jxcore-log: 
10-26 22:40:34.453  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.453  5475  5522 I jxcore-log: 
,10-26 22:40:34.453  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.453  5475  5522 I jxcore-log: 
10-26 22:40:34.453  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.453  5475  5522 I jxcore-log: 
,10-26 22:40:34.453  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:40:34.453  5475  5522 I jxcore-log: 
10-26 22:40:34.454  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.454  5475  5522 I jxcore-log: 
10-26 22:40:34.454  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.454  5475  5522 I jxcore-log: 
,10-26 22:40:34.454  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.454  5475  5522 I jxcore-log: 
10-26 22:40:34.454  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.454  5475  5522 I jxcore-log: 
10-26 22:40:34.455  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.455  5475  5522 I jxcore-log: 
10-26 22:40:34.455  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.455  5475  5522 I jxcore-log: 
,10-26 22:40:34.455  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.455  5475  5522 I jxcore-log: 
10-26 22:40:34.455  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.455  5475  5522 I jxcore-log: 
10-26 22:40:34.455  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.455  5475  5522 I jxcore-log: 
,10-26 22:40:34.456  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.456  5475  5522 I jxcore-log: 
10-26 22:40:34.456  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.456  5475  5522 I jxcore-log: 
10-26 22:40:34.456  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:40:34.456  5475  5522 I jxcore-log: 
10-26 22:40:34.456  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 22:40:34.456  5475  5522 I jxcore-log: 
10-26 22:40:34.457  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 22:40:34.457  5475  5522 I jxcore-log: 
10-26 22:40:34.457  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.457  5475  5522 I jxcore-log: 
,10-26 22:40:34.457  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.457  5475  5522 I jxcore-log: 
10-26 22:40:34.457  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.457  5475  5522 I jxcore-log: 
10-26 22:40:34.458  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.458  5475  5522 I jxcore-log: 
10-26 22:40:34.458  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.458  5475  5522 I jxcore-log: 
10-26 22:40:34.458  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:40:34.458  5475  5522 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-26 22:40:34.458  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.458  5475  5522 I jxcore-log: 
10-26 22:40:34.459  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.459  5475  5522 I jxcore-log: 
10-26 22:40:34.459  5475  5522 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 22:40:34.459  5475  5522 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-26 22:40:34.459  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:40:34.459  5475  5522 I jxcore-log: 
10-26 22:40:34.459  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:40:34.459  5475  5522 I jxcore-log: 
10-26 22:40:34.459  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:40:34.459  5475  5522 I jxcore-log: 
,10-26 22:40:34.459  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:40:34.459  5475  5522 I jxcore-log: 
10-26 22:40:34.465  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-26 22:40:34.465  5475  5522 I jxcore-log: 
10-26 22:40:34.465  5475  5475 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-26 22:40:34.465  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - WARN testUtils: 'myNameCallback not set!'
10-26 22:40:34.465  5475  5522 I jxcore-log: 
10-26 22:40:34.466  5475  5522 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-26 22:40:34.466  5475  5522 I jxcore-log: 2016-10-26 20:40:34 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-26 22:40:34.466  5475  5522 I jxcore-log: 
,10-26 22:40:36.529  5475  5522 I jxcore-log: 2016-10-26 20:40:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-26 22:40:36.529  5475  5522 I jxcore-log: 
,10-26 22:40:36.866  5475  5522 I jxcore-log: 2016-10-26 20:40:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-26 22:40:36.866  5475  5522 I jxcore-log: 
,10-26 22:40:36.879  5475  5522 I jxcore-log: 2016-10-26 20:40:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-26 22:40:36.879  5475  5522 I jxcore-log: 
,10-26 22:40:38.001  5475  5522 I jxcore-log: 2016-10-26 20:40:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-26 22:40:38.001  5475  5522 I jxcore-log: 
,10-26 22:40:38.186  5475  5522 I jxcore-log: 2016-10-26 20:40:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-26 22:40:38.186  5475  5522 I jxcore-log: 
,10-26 22:40:38.191  5475  5522 I jxcore-log: 2016-10-26 20:40:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-26 22:40:38.191  5475  5522 I jxcore-log: 
,10-26 22:40:38.196  5475  5522 I jxcore-log: 2016-10-26 20:40:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-26 22:40:38.196  5475  5522 I jxcore-log: 
,10-26 22:40:38.670  5475  5522 I jxcore-log: 2016-10-26 20:40:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-26 22:40:38.670  5475  5522 I jxcore-log: 
,10-26 22:40:38.714  5475  5522 I jxcore-log: 2016-10-26 20:40:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-26 22:40:38.714  5475  5522 I jxcore-log: 
,10-26 22:40:38.726  5475  5522 I jxcore-log: 2016-10-26 20:40:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-26 22:40:38.726  5475  5522 I jxcore-log: 
,10-26 22:40:38.731  5475  5522 I jxcore-log: 2016-10-26 20:40:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-26 22:40:38.731  5475  5522 I jxcore-log: 
,10-26 22:40:39.012  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-26 22:40:39.012  5475  5522 I jxcore-log: 
,10-26 22:40:39.137  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-26 22:40:39.137  5475  5522 I jxcore-log: 
,10-26 22:40:39.535  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-26 22:40:39.535  5475  5522 I jxcore-log: 
,10-26 22:40:39.542  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-26 22:40:39.542  5475  5522 I jxcore-log: 
,10-26 22:40:39.545  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-26 22:40:39.545  5475  5522 I jxcore-log: 
,10-26 22:40:39.550  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-26 22:40:39.550  5475  5522 I jxcore-log: 
,10-26 22:40:39.555  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-26 22:40:39.555  5475  5522 I jxcore-log: 
,10-26 22:40:39.582  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-26 22:40:39.582  5475  5522 I jxcore-log: 
,10-26 22:40:39.617  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-26 22:40:39.617  5475  5522 I jxcore-log: 
,10-26 22:40:39.625  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-26 22:40:39.625  5475  5522 I jxcore-log: 
,10-26 22:40:39.631  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-26 22:40:39.631  5475  5522 I jxcore-log: 
,10-26 22:40:39.646  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-26 22:40:39.646  5475  5522 I jxcore-log: 
,10-26 22:40:39.651  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-26 22:40:39.651  5475  5522 I jxcore-log: 
,10-26 22:40:39.657  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-26 22:40:39.657  5475  5522 I jxcore-log: 
,10-26 22:40:39.662  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-26 22:40:39.662  5475  5522 I jxcore-log: 
,10-26 22:40:39.671   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:40:39.675  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-26 22:40:39.675  5475  5522 I jxcore-log: 
,10-26 22:40:39.681  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-26 22:40:39.681  5475  5522 I jxcore-log: 
,10-26 22:40:39.703  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-26 22:40:39.703  5475  5522 I jxcore-log: 
,10-26 22:40:39.714  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-26 22:40:39.714  5475  5522 I jxcore-log: 
,10-26 22:40:39.726  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-26 22:40:39.726  5475  5522 I jxcore-log: 
,10-26 22:40:39.736  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-26 22:40:39.736  5475  5522 I jxcore-log: 
,10-26 22:40:39.749  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-26 22:40:39.749  5475  5522 I jxcore-log: 
,10-26 22:40:39.759  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-26 22:40:39.759  5475  5522 I jxcore-log: 
,10-26 22:40:39.766  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-26 22:40:39.766  5475  5522 I jxcore-log: 
,10-26 22:40:39.787  5475  5522 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-26 22:40:39.788  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - INFO testUtils: 'BLE multiple advertisement supported'
10-26 22:40:39.788  5475  5522 I jxcore-log: 
,10-26 22:40:39.876  5475  5522 I jxcore-log: 2016-10-26 20:40:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:39.876  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:39.876  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:39.876  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:39.876  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:39.876  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:39.876  5475  5522 I jxcore-log: 
,10-26 22:40:40.234  5475  5522 I jxcore-log: 2016-10-26 20:40:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:40.234  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:40.234  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:40.234  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:40.234  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:40.234  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:40.234  5475  5522 I jxcore-log: 
,10-26 22:40:40.240  5475  5522 I jxcore-log: 2016-10-26 20:40:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:40.240  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:40.240  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:40.240  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:40.240  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:40.240  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:40.240  5475  5522 I jxcore-log: 
,10-26 22:40:40.672   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:40:40.784  5475  5522 I jxcore-log: 2016-10-26 20:40:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:40.784  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:40.784  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:40.784  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:40.784  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:40.784  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:40.784  5475  5522 I jxcore-log: 
,10-26 22:40:40.787  5475  5522 I jxcore-log: 2016-10-26 20:40:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:40.787  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:40.787  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:40.787  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:40.787  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:40.787  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:40.787  5475  5522 I jxcore-log: 
,10-26 22:40:41.667  5475  5522 I jxcore-log: 2016-10-26 20:40:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:41.667  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:41.667  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:41.667  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:41.667  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:41.667  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:41.667  5475  5522 I jxcore-log: 
,10-26 22:40:41.670  5475  5522 I jxcore-log: 2016-10-26 20:40:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:41.670  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:41.670  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:41.670  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:41.670  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:41.670  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:41.670  5475  5522 I jxcore-log: 
,10-26 22:40:41.673   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:40:42.674   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:40:42.719  5475  5522 I jxcore-log: 2016-10-26 20:40:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:42.719  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:42.719  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:42.719  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:42.719  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:42.719  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:42.719  5475  5522 I jxcore-log: 
,10-26 22:40:42.724  5475  5522 I jxcore-log: 2016-10-26 20:40:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:42.724  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:42.724  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:42.724  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:42.724  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:42.724  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:42.724  5475  5522 I jxcore-log: 
,10-26 22:40:43.675   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:40:43.767  5475  5522 I jxcore-log: 2016-10-26 20:40:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:43.767  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:43.767  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:43.767  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:43.767  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:43.767  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:43.767  5475  5522 I jxcore-log: 
,10-26 22:40:43.772  5475  5522 I jxcore-log: 2016-10-26 20:40:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:43.772  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:43.772  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:43.772  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:43.772  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:43.772  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:43.772  5475  5522 I jxcore-log: 
,10-26 22:40:44.676   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-26 22:40:44.810  5475  5522 I jxcore-log: 2016-10-26 20:40:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:44.810  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:44.810  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:44.810  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:44.810  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:44.810  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:44.810  5475  5522 I jxcore-log: 
,10-26 22:40:44.814  5475  5522 I jxcore-log: 2016-10-26 20:40:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:44.814  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:44.814  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:44.814  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:44.814  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:44.814  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:44.814  5475  5522 I jxcore-log: 
,10-26 22:40:45.846  5475  5522 I jxcore-log: 2016-10-26 20:40:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:45.846  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:45.846  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:45.846  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:45.846  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:45.846  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:45.846  5475  5522 I jxcore-log: 
,10-26 22:40:45.850  5475  5522 I jxcore-log: 2016-10-26 20:40:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:45.850  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:45.850  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:45.850  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:45.850  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:45.850  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:45.850  5475  5522 I jxcore-log: 
,10-26 22:40:46.882  5475  5522 I jxcore-log: 2016-10-26 20:40:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:46.882  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:46.882  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:46.882  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:46.882  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:46.882  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:46.882  5475  5522 I jxcore-log: 
,10-26 22:40:46.885  5475  5522 I jxcore-log: 2016-10-26 20:40:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:46.885  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:46.885  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:46.885  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:46.885  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:46.885  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:46.885  5475  5522 I jxcore-log: 
,10-26 22:40:47.914  5475  5522 I jxcore-log: 2016-10-26 20:40:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:47.914  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:47.914  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:47.914  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:47.914  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:47.914  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:47.914  5475  5522 I jxcore-log: 
,10-26 22:40:47.919  5475  5522 I jxcore-log: 2016-10-26 20:40:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:47.919  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:47.919  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:47.919  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:47.919  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:47.919  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:47.919  5475  5522 I jxcore-log: 
,10-26 22:40:48.985  5475  5522 I jxcore-log: 2016-10-26 20:40:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:48.985  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:48.985  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:48.985  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:48.985  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:48.985  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:48.985  5475  5522 I jxcore-log: 
,10-26 22:40:48.990  5475  5522 I jxcore-log: 2016-10-26 20:40:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:48.990  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:48.990  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:48.990  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:48.990  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:48.990  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:48.990  5475  5522 I jxcore-log: 
,10-26 22:40:50.028  5475  5522 I jxcore-log: 2016-10-26 20:40:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:50.028  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:50.028  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:50.028  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:50.028  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:50.028  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:50.028  5475  5522 I jxcore-log: 
,10-26 22:40:50.033  5475  5522 I jxcore-log: 2016-10-26 20:40:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:50.033  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:50.033  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:50.033  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:50.033  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:50.033  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:50.033  5475  5522 I jxcore-log: 
,10-26 22:40:51.060  5475  5522 I jxcore-log: 2016-10-26 20:40:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:51.060  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:51.060  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:51.060  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:51.060  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:51.060  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:51.060  5475  5522 I jxcore-log: 
,10-26 22:40:51.065  5475  5522 I jxcore-log: 2016-10-26 20:40:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:51.065  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:51.065  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:51.065  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:51.065  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:51.065  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:51.065  5475  5522 I jxcore-log: 
,10-26 22:40:52.100  5475  5522 I jxcore-log: 2016-10-26 20:40:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:52.100  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:52.100  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:52.100  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:52.100  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:52.100  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:52.100  5475  5522 I jxcore-log: 
,10-26 22:40:52.104  5475  5522 I jxcore-log: 2016-10-26 20:40:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:52.104  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:52.104  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:52.104  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:52.104  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:52.104  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:52.104  5475  5522 I jxcore-log: 
,10-26 22:40:53.137  5475  5522 I jxcore-log: 2016-10-26 20:40:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:53.137  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:53.137  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:53.137  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:53.137  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:53.137  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:53.137  5475  5522 I jxcore-log: 
,10-26 22:40:53.141  5475  5522 I jxcore-log: 2016-10-26 20:40:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:53.141  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:53.141  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:53.141  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:53.141  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:53.141  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:53.141  5475  5522 I jxcore-log: 
,10-26 22:40:54.185  5475  5522 I jxcore-log: 2016-10-26 20:40:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:40:54.185  5475  5522 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:40:54.185  5475  5522 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:40:54.185  5475  5522 I jxcore-log: emit@events.js:82:1
10-26 22:40:54.185  5475  5522 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:40:54.185  5475  5522 I jxcore-log: emit@events.js:82:1'
10-26 22:40:54.185  5475  5522 I jxcore-log: 
,10-26 22:40:54.196  5475  5522 E jxcore  : Error!: error is undefined
10-26 22:40:54.196  5475  5522 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-26 22:40:54.199  5475  5522 I jxcore-log: 2016-10-26 20:40:54 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-26 22:40:54.199  5475  5522 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
10-26 22:40:54.199  5475  5522 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-26 22:40:54.199  5475  5522 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-26 22:40:54.199  5475  5522 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-26 22:40:54.199  5475  5522 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-26 22:40:54.199  5475  5522 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-26 22:40:54.199  5475  5522 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-26 22:40:54.201  5475  5522 I jxcore-log: 2016-10-26 20:40:54 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-26 22:40:54.201  5475  5522 I jxcore-log: 
,10-26 22:40:54.203  5475  5522 E jxcore-log: TypeError: 
10-26 22:40:54.203  5475  5522 E jxcore-log: error is undefined
10-26 22:40:54.204  5475  5522 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
10-26 22:40:54.204  5475  5522 E jxcore-log: 
,10-26 22:40:54.288   928  3523 I WindowState: WIN DEATH: Window{e8b511 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-26 22:40:54.289   928  3032 D GraphicsStats: Buffer count: 2
,10-26 22:40:54.290   928  2857 D WifiService: Client connection lost with reason: 4
,10-26 22:40:54.304   928  3715 I ActivityManager: Process com.test.thalitest (pid 5475) has died
10-26 22:40:54.300   530   530 I Zygote  : Process 5475 exited cleanly (139)
,10-26 22:40:54.316   928  3715 I ActivityManager: Start proc 5804:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-26 22:40:54.395  5804  5804 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-26 22:40:54.416  5804  5804 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-26 22:40:54.421  5804  5804 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4375-4377)
,10-26 22:40:54.421  5804  5804 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 22:40:54.431  5804  5804 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {86d0e47}
,10-26 22:40:54.432  5804  5804 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-26 22:40:54.432  5804  5804 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-26 22:40:54.436  5804  5804 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-26 22:40:54.436  5804  5804 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-26 22:40:54.447  5804  5804 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-26 22:40:54.455  5804  5804 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-26 22:40:54.455  5804  5804 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 22:40:54.455  5804  5804 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 22:40:54.455  5804  5804 I Adreno  : Build Date                       : 12/06/15
10-26 22:40:54.455  5804  5804 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 22:40:54.455  5804  5804 I Adreno  : Local Branch                     : mybranch17112971
10-26 22:40:54.455  5804  5804 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 22:40:54.455  5804  5804 I Adreno  : Remote Branch                    : NONE
10-26 22:40:54.455  5804  5804 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 22:40:54.487   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a9bc82:true
,10-26 22:40:54.498   402   402 W Binder_2: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33056]" dev="sockfs" ino=33056 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-26 22:40:54.498   402   402 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33056]" dev="sockfs" ino=33056 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:40:54.511  5804  5804 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-26 22:40:54.519  5804  5804 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-26 22:40:54.544   402   402 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34034]" dev="sockfs" ino=34034 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:40:54.548  5804  5840 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-26 22:40:54.544   402   402 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34034]" dev="sockfs" ino=34034 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:40:54.548  3525  3525 W Binder_9: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[15744]" dev="sockfs" ino=15744 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:40:54.548  3525  3525 W Binder_9: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[15744]" dev="sockfs" ino=15744 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:40:54.553  5804  5827 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-26 22:40:54.583  5804  5840 I OpenGLRenderer: Initialized EGL, version 1.4
,10-26 22:40:54.597   928  3715 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5475 uid 10077
,10-26 22:40:54.599  3548  3548 I Keyboard.Facilitator: onFinishInput()
,10-26 22:40:54.594  3715  3715 W Binder_A: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[31456]" dev="sockfs" ino=31456 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:40:54.594  3715  3715 W Binder_A: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[31456]" dev="sockfs" ino=31456 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:40:54.594  3782  3782 W Binder_B: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[31455]" dev="sockfs" ino=31455 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:40:54.594  3782  3782 W Binder_B: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[31455]" dev="sockfs" ino=31455 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:40:54.618   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +284ms (total +312ms)
,10-26 22:40:54.619  5804  5804 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5804
,10-26 22:40:54.685  5804  5804 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-26 22:40:54.741  5802  5802 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-26 22:40:54.756  5802  5802 D AndroidRuntime: CheckJNI is OFF
,10-26 22:40:54.776  5802  5802 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-26 22:40:54.803  5802  5802 I Radio-JNI: register_android_hardware_Radio DONE
,10-26 22:40:54.818  5802  5802 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-26 22:40:54.825   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-26 22:40:54.825   928   941 I ActivityManager: Killing 5804:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-26 22:40:54.869   928  3524 D GraphicsStats: Buffer count: 2
,10-26 22:40:54.869   928  3523 I WindowState: WIN DEATH: Window{8c55539 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-26 22:40:54.925   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-26 22:40:54.925   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-26 22:40:54.926   928   941 E ActivityManager: Failure starting process com.test.thalitest
10-26 22:40:54.926   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-26 22:40:54.926   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 22:40:54.926   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-26 22:40:54.926   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-26 22:40:54.926   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-26 22:40:54.927   928   941 I ActivityManager:   Force finishing activity ActivityRecord{51d5c3e u0 com.test.thalitest/.MainActivity t66}
,10-26 22:40:54.928   928   953 I art     : Starting a blocking GC Explicit
,10-26 22:40:54.937   928  3782 W ActivityManager: Spurious death for ProcessRecord{22254df 0:com.test.thalitest/u0a77}, curProc for 5804: null
,10-26 22:40:55.011   928   953 I art     : Explicit concurrent mark sweep GC freed 12770(852KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.591ms total 82.279ms
,10-26 22:40:55.029   928   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-26 22:40:55.033  5802  5802 I art     : System.exit called, status: 0
,10-26 22:40:55.033  5802  5802 I AndroidRuntime: VM exiting with result code 0.
,10-26 22:40:55.038   928   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-26 22:40:55.049   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-26 22:40:55.051  3548  3548 I Keyboard.Facilitator: resetDictionaries() : en_US
10-26 22:40:55.053  5699  5699 D BluetoothMapAppObserver: onReceive
10-26 22:40:55.053  5699  5699 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-26 22:40:55.056  3607  4022 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-26 22:40:55.063   928  2844 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-26 22:40:55.084  3302  5856 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-26 22:40:55.086  3548  5855 I Keyboard.Facilitator.DecoderInitializer: run()
,10-26 22:40:55.111  3677  3677 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-26 22:40:55.116  3548  5855 I Decoder : createOrResetDecoder
,10-26 22:40:55.122  3488  3488 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-26 22:40:55.122  3488  3488 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-26 22:40:55.124   411   411 W kworker/4:1: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 22:40:55.128   411   411 W kworker/4:1: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 22:40:55.134   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-26 22:40:55.144   411   411 W kworker/4:1: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 22:40:55.147  3883  5861 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
10-26 22:40:55.147  3883  5861 D AccountUtils: Clearing selected account for com.test.thalitest
,10-26 22:40:55.155   928  3782 I ActivityManager: Start proc 5863:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-26 22:40:55.156  3716  3841 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-26 22:40:55.156  3716  3841 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3716
10-26 22:40:55.156  3716  3841 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-26 22:40:55.156  3716  3841 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-26 22:40:55.162   928  3060 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-26 22:40:55.162   928  5870 E DropBoxManagerService: Can't write: system_app_crash
10-26 22:40:55.162   928  5870 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-26 22:40:55.162   928  5870 E DropBoxManagerService: 	... 5 more
,10-26 22:40:55.166  3883  5861 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-26 22:40:55.171  3716  3841 I Process : Sending signal. PID: 3716 SIG: 9
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-26 22:40:55.178  3883  5861 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQ,LiteDatabase.open(SQLiteDatabase.java:791)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-26 22:40:55.178  3883  5861 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-26 22:40:55.179  3883  5861 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
10-26 22:40:55.220  3883  5879 I GMPM-SVC: App measurement is starting up
10-26 22:40:55.222  3883  5879 E GMPM-SVC: AppMeasurementService not registered/enabled
10-26 22:40:55.223  3883  5879 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-26 22:40:55.230   381   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,10-26 22:40:55.230  3883  5879 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
10-26 22:40:55.230  3883  5879 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
10-26 22:40:55.230   381   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
10-26 22:40:55.230  3883  5879 E GMPM-SVC: Opening the database failed, dropping and recreating it

```
