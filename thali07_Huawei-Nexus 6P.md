#### Test 90916415f4fe0a6_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-26 22:53:37.596  4110  4255 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
10-26 22:53:37.675  4110  4255 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,10-26 22:53:38.085  5576  5576 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-26 22:53:38.091  5576  5576 D AndroidRuntime: CheckJNI is OFF
10-26 22:53:38.119  5576  5576 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-26 22:53:38.152  5576  5576 I Radio-JNI: register_android_hardware_Radio DONE
10-26 22:53:38.167  5576  5576 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-26 22:53:38.170   927  3866 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-26 22:53:38.201  5576  5576 D AndroidRuntime: Shutting down VM
10-26 22:53:38.201  3973  3983 W SearchService: Abort, client detached.
10-26 22:53:38.209  3973  3973 I HotwordDetector: Closing mic
10-26 22:53:38.210  3973  4245 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@4b0e074
10-26 22:53:38.210  3973  4252 E AudioRecord-JNI: Error -4 during AudioRecord native read
10-26 22:53:38.230   927  3186 I ActivityManager: Start proc 5586:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-26 22:53:38.276   512  4254 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
10-26 22:53:38.278   512  4254 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
10-26 22:53:38.284   512  4254 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
10-26 22:53:38.284   512  4254 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
10-26 22:53:38.285   512  3030 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
10-26 22:53:38.286  3973  4248 I MicroRecognitionRnrImpl: Stopping hotword detection.
10-26 22:53:38.287  3973  4251 I MicroRecognitionRnrImpl: Detection finished
10-26 22:53:38.343  5586  5586 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
10-26 22:53:38.362  5586  5586 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
10-26 22:53:38.420  5586  5586 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 8827-8882)
10-26 22:53:38.421  5586  5586 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 22:53:38.451  5586  5586 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {85042d}
10-26 22:53:38.451  5586  5586 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 22:53:38.451  5586  5586 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-26 22:53:38.454  5586  5586 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-26 22:53:38.455  5586  5586 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-26 22:53:38.516  5586  5586 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-26 22:53:38.530  5586  5586 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-26 22:53:38.530  5586  5586 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 22:53:38.530  5586  5586 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 22:53:38.530  5586  5586 I Adreno  : Build Date                       : 12/06/15
10-26 22:53:38.530  5586  5586 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 22:53:38.530  5586  5586 I Adreno  : Local Branch                     : mybranch17112971
10-26 22:53:38.530  5586  5586 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 22:53:38.530  5586  5586 I Adreno  : Remote Branch                    : NONE
10-26 22:53:38.530  5586  5586 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 22:53:38.572   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f50299a:true
,10-26 22:53:38.597   403   403 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[14229]" dev="sockfs" ino=14229 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:53:38.597   403   403 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14229]" dev="sockfs" ino=14229 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:53:38.609  5586  5586 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-26 22:53:38.617  5586  5586 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-26 22:53:38.653  2577  2577 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[30634]" dev="sockfs" ino=30634 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:53:38.653  2577  2577 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30634]" dev="sockfs" ino=30634 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-26 22:53:38.656  5586  5623 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-26 22:53:38.657   938   938 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[20476]" dev="sockfs" ino=20476 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:53:38.657   938   938 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[20476]" dev="sockfs" ino=20476 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:53:38.661  5586  5610 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-26 22:53:38.693  5586  5623 I OpenGLRenderer: Initialized EGL, version 1.4
,10-26 22:53:38.772   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +566ms
,10-26 22:53:38.770   938   938 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32042]" dev="sockfs" ino=32042 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:53:38.770   938   938 W Binder_2: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32042]" dev="sockfs" ino=32042 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:53:38.770  3609  3609 W Binder_5: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32041]" dev="sockfs" ino=32041 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:53:38.770  3609  3609 W Binder_5: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32041]" dev="sockfs" ino=32041 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:53:38.777  3682  3682 I Keyboard.Facilitator: onFinishInput()
,10-26 22:53:38.815  5586  5586 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5586
,10-26 22:53:38.908  5586  5586 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-26 22:53:39.115  5586  5625 D jxcore_app_log: JniHelper::setJavaVM(0xf55fc000), pthread_self() = -559941328
,10-26 22:53:39.120  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-26 22:53:39.120  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-26 22:53:39.120  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-26 22:53:39.120  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-26 22:53:39.120  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-26 22:53:39.120  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@322f188 added. We now have 1 listener(s)
,10-26 22:53:39.128  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,10-26 22:53:39.129  5586  5625 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:53:39.129  5586  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-26 22:53:39.129  5586  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-26 22:53:39.131  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@780cd07 added. We now have 1 listener(s)
,10-26 22:53:39.132  5586  5625 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:53:39.139   927  3009 D WifiService: New client listening to asynchronous messages
,10-26 22:53:39.139  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 22:53:39.139  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,10-26 22:53:39.143  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,10-26 22:53:39.143  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-26 22:53:39.143  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-26 22:53:39.145  5586  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:53:39.145  5586  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,10-26 22:53:39.149  5586  5625 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-26 22:53:39.149  5586  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:53:39.149  5586  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:53:39.149  5586  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:53:39.149  5586  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:53:39.149  5586  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:53:39.149  5586  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:53:39.149  5586  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:53:39.149  5586  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:53:39.149  5586  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-26 22:53:39.149  5586  5625 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:53:39.150  5586  5625 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-26 22:53:39.267  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:53:39.271  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:53:39.273  5586  5586 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-26 22:53:39.710  5586  5595 I art     : Background sticky concurrent mark sweep GC freed 85039(8MB) AllocSpace objects, 17(1096KB) LOS objects, 22% free, 25MB/32MB, paused 8.149ms total 351.975ms
,10-26 22:53:40.248   927  3008 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 22:53:41.026  5586  5595 I art     : Background partial concurrent mark sweep GC freed 48327(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.512ms total 349.170ms
,10-26 22:53:41.371  5586  5633 W jxcore-log: Initializing JXcore engine
,10-26 22:53:41.372  5586  5633 W jxcore-log: JXcore engine is ready
,10-26 22:53:41.393  5633  5633 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11836 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-26 22:53:41.393  5633  5633 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[17595]" dev="sockfs" ino=17595 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-26 22:53:41.393  5633  5633 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-26 22:53:41.393  5633  5633 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32809]" dev="sockfs" ino=32809 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
10-26 22:53:41.404  5586  5633 W jxcore-log: Starting JXcore engine
,10-26 22:53:41.454  5586  5633 W jxcore-log: Platform android
10-26 22:53:41.454  5586  5633 W jxcore-log: 
10-26 22:53:41.455  5586  5633 W jxcore-log: Process ARCH arm
10-26 22:53:41.455  5586  5633 W jxcore-log: 
,10-26 22:53:41.631  5586  5633 I jxcore-log: JXcore Cordova bridge is ready!
10-26 22:53:41.631  5586  5633 I jxcore-log: 
,10-26 22:53:41.631  5586  5633 W jxcore-log: JXcore engine is started
,10-26 22:53:41.634  5586  5625 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-26 22:53:41.636  5586  5586 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-26 22:53:41.750  3615  3615 I ConfigService: onDestroy
,10-26 22:53:43.217   927  4039 I ActivityManager: Killing 5224:org.codeaurora.ims/1001 (adj 15): empty #17
,10-26 22:53:43.248   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:53:43.255   927  4039 I ActivityManager: Killing 5147:com.google.android.youtube/u0a75 (adj 15): empty #18
,10-26 22:53:44.249   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:53:45.250   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:53:46.251   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:53:47.252   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:53:48.252   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-26 22:53:51.404   927  3009 D WifiService: New client listening to asynchronous messages
,10-26 22:53:51.407  3973  5634 W CronetSyncConnectionRcs: Upload content type not set.
,10-26 22:53:51.486  4874  4918 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-26 22:53:51.488  4874  4874 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-26 22:53:51.540  5586  5633 I jxcore-log: 2016-10-26 20:53:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-26 22:53:51.540  5586  5633 I jxcore-log: 
,10-26 22:53:51.541  5586  5633 I jxcore-log: 2016-10-26 20:53:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-26 22:53:51.541  5586  5633 I jxcore-log: 
,10-26 22:53:51.545  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:53:51.545  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:53:51.545  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:53:51.545  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:53:51.545  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:53:51.545  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:53:51.545  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:53:51.545  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:53:51.547  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:53:51.549  5586  5633 I jxcore-log: 2016-10-26 20:53:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-26 22:53:51.549  5586  5633 I jxcore-log: 
,10-26 22:53:51.550  5586  5633 I jxcore-log: 2016-10-26 20:53:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-26 22:53:51.550  5586  5633 I jxcore-log: 
,10-26 22:53:51.802  5586  5633 I jxcore-log: 2016-10-26 20:53:51 - DEBUG UnitTest_app: 'Running unit tests'
10-26 22:53:51.802  5586  5633 I jxcore-log: 
10-26 22:53:51.803  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 22:53:51.803  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39d056b added. We now have 2 listener(s)
10-26 22:53:51.803  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:53:51.803  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:53:51.803  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:53:51.803  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:53:51.803  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4418c8 added. We now have 2 listener(s)
10-26 22:53:51.803  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:53:51.804  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 22:53:51.805  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:53:51.807  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:53:51.807  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:53:51.807  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:53:51.807  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:53:51.807  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:53:51.807  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:53:51.807  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:53:51.807  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:53:51.808  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:53:51.808  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-26 22:53:51.809  5586  5633 D executeNativeTests: Running unit tests
,10-26 22:53:51.811  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:53:51.814  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:53:51.842  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 22:53:51.842  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 added. We now have 3 listener(s)
10-26 22:53:51.843  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 22:53:51.843  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:53:51.843  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:53:51.843  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:53:51.843  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 added. We now have 3 listener(s)
,10-26 22:53:51.843  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:53:51.843  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 22:53:51.845  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:53:51.847  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:53:51.847  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:53:51.847  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:53:51.847  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:53:51.847  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:53:51.847  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:53:51.847  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:53:51.847  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:53:51.847  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:53:51.848  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:53:51.849  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 22:53:51.849  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-26 22:53:51.849  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:53:51.849  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:53:51.849  5586  5633 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-26 22:53:51.850  5586  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-26 22:53:51.850  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 22:53:51.850  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:53:51.850  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-26 22:53:51.850  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:53:51.850  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:53:51.850  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:53:51.850  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:53:51.850  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 22:53:51.850  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:53:51.850  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:53:51.851  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:53:51.851  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:53:51.851  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 removed from the list
10-26 22:53:51.851  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:53:51.851  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 removed from the list
,10-26 22:53:51.853  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:53:51.857  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:53:51.857  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:53:51.858  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:53:51.858  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:53:51.858  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:53:51.858  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.859  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:53:51.859  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.859  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.859  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:53:51.859  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 22:53:51.859  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:53:51.859  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:53:51.860  5586  5633 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-26 22:53:51.860  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:53:51.860  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:53:51.860  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:53:51.860  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:53:51.860  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:53:51.860  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:53:51.860  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:53:51.860  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:53:51.860  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:53:51.861  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:53:51.861  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:53:51.861  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:53:51.861  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:53:51.861  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:53:51.861  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:53:51.861  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.861  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:53:51.861  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.861  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.861  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:53:51.861  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:53:51.861  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:53:51.861  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
,10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,10-26 22:53:51.864  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-26 22:53:51.865  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-26 22:53:51.865  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-26 22:53:51.865  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-26 22:53:51.865  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-26 22:53:51.865  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:53:51.865  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:53:51.865  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 22:53:51.865  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:53:51.865  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:53:51.865  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:53:51.865  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:53:51.865  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:53:51.865  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:53:51.865  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
,10-26 22:53:51.865  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:53:51.865  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:53:51.865  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:53:51.865  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:53:51.865  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:53:51.865  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.866  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:53:51.866  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.866  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.866  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:53:51.866  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:53:51.866  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:53:51.866  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:53:51.867  5586  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-26 22:53:51.868  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:53:51.870  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:53:51.870  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:53:51.870  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:53:51.870  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:53:51.870  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:53:51.870  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:53:51.870  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:53:51.870  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:53:51.870  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:53:51.871  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:53:51.871  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:53:51.871  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 22:53:51.871  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:53:51.871  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:53:51.871  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 22:53:51.874  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:53:51.876  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:53:51.879  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 22:53:51.879  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:53:51.879  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 22:53:51.881  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 22:53:51.882  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 22:53:51.882  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 22:53:51.883  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-26 22:53:51.884  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-26 22:53:51.884  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.884  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:53:51.884  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:53:51.884  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:53:51.884  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:53:51.885  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.885  5586  5633 D BluetoothAdapter: STATE_ON
10-26 22:53:51.887  4675  4687 D BtGatt.GattService: registerClient() - UUID=e51497db-32b7-4aaf-83fd-ff6507110f22
10-26 22:53:51.888  4675  4738 D BtGatt.GattService: onClientRegistered() - UUID=e51497db-32b7-4aaf-83fd-ff6507110f22, clientIf=5
10-26 22:53:51.888  5586  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 22:53:51.889  4675  4896 D BtGatt.GattService: start scan with filters
10-26 22:53:51.893  4675  4742 D BtGatt.ScanManager: handling starting scan
10-26 22:53:51.894  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 22:53:51.894  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.894  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 22:53:51.894  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.894  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.894  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:53:51.894  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:53:51.894  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.894  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.894  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:53:51.894  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.895  4675  4742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
10-26 22:53:51.896  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.896  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:53:51.896  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.896  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.896  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.896  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:53:51.896  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:53:51.896  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:53:51.897  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.898  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.898  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.898  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:51.898  5586  5633 I io.jxcore.node.ConnectionHelper: start: OK
,10-26 22:53:51.903  4675  4738 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 22:53:51.903  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:53:51.904  4675  4742 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 22:53:51.911  4675  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 22:53:51.911  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:53:51.912  4675  4742 D BtGatt.ScanManager: Starting BLE batch scan
10-26 22:53:51.912  4675  4742 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 22:53:51.921  4675  4738 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:53:51.922  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:53:51.927  4675  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 22:53:51.927  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:53:52.397  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-26 22:53:52.398  5586  5586 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:53:52.398  5586  5586 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 22:53:56.902  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,10-26 22:53:56.902  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:53:56.902  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-26 22:53:56.902  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:53:56.903  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 22:53:56.903  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:53:56.903  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 22:53:56.903  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:53:56.903  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:53:56.903  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:53:56.904  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.904  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.904  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 22:53:56.905  5586  5633 D BluetoothAdapter: STATE_ON
10-26 22:53:56.906  4675  4687 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:53:56.907  4675  4896 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 22:53:56.908  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 22:53:56.908  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.908  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:53:56.908  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.908  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.908  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:53:56.908  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 22:53:56.908  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.909  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.909  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:53:56.909  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:53:56.910  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.910  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:53:56.910  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.911  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.911  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.911  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.911  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.912  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 22:53:56.912  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.912  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.912  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.912  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 22:53:56.912  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 22:53:56.913  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:53:56.913  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.916  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:53:56.916  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.916  4675  4675 D BtGatt.ScanManager: awakened up at time 97377
10-26 22:53:56.916  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:53:56.916  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:53:56.916  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-26 22:53:56.917  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:53:56.917  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:53:56.917  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:53:56.917  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:53:56.917  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:53:56.917  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:53:56.917  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:53:56.917  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:53:56.917  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:53:56.918  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:53:56.923  4675  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 22:53:56.924  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:53:56.924  4675  4742 D BtGatt.ScanManager: stopping BLe Batch
10-26 22:53:56.933  4675  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-26 22:53:56.933  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:53:56.933  4675  4742 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 22:53:56.955  4675  4738 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-26 22:53:56.955  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:53:56.955  4675  4738 D BtGatt.GattService: current time is 97417300008
10-26 22:53:56.956  4675  4738 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -75, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -78, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 50, -35, 86, -77, -92, -11, 1, 0, -97, 67, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 31, 47, 58, 3, 1, -33, 18, -106, 91, -98, 109, 28, 6, 8, 116, 105, 110, 54, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,10-26 22:53:56.957  4675  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-26 22:53:56.958  4675  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-26 22:53:56.959  4675  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-26 22:53:56.959  4675  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-26 22:53:56.959  4675  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 31, 47, 58, 3, 1, -33, 18, -106, 91, -98, 109, 6, 8, 116, 105, 110, 54, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,10-26 22:53:57.419  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:53:59.774   927  3186 I ActivityManager: Killing 5263:com.android.settings/1000 (adj 15): empty #17
,10-26 22:54:01.923  5586  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-26 22:54:01.929  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:54:01.940  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:54:01.940  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:01.940  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:01.940  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:01.940  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:54:01.940  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:01.940  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:54:01.940  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:54:01.945  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:54:01.946  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:54:01.946  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:54:01.946  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-26 22:54:01.946  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:54:01.946  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:54:01.947  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-26 22:54:01.953  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:01.958  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-26 22:54:01.959  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:54:01.959  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-26 22:54:01.959  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:01.967  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 22:54:01.969  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-26 22:54:01.969  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 22:54:01.975  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:01.975  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:54:01.975  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:54:01.975  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:54:01.975  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:54:01.975  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:01.977  5586  5633 D BluetoothAdapter: STATE_ON
10-26 22:54:01.980  4675  4896 D BtGatt.GattService: registerClient() - UUID=e0cf0479-ee90-499f-ad0c-4abc9389039d
,10-26 22:54:01.981  4675  4738 D BtGatt.GattService: onClientRegistered() - UUID=e0cf0479-ee90-499f-ad0c-4abc9389039d, clientIf=5
,10-26 22:54:01.982  5586  5597 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 22:54:01.983  4675  4888 D BtGatt.GattService: start scan with filters
,10-26 22:54:01.987  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 22:54:01.987  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:01.988  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-26 22:54:01.988  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:01.988  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:01.988  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-26 22:54:01.988  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:54:01.988  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:01.988  4675  4742 D BtGatt.ScanManager: handling starting scan
10-26 22:54:01.988  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:01.989  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:54:01.989  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:01.994  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:01.994  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:54:01.994  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:01.994  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:54:01.994  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:01.995  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:01.995  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:54:01.997  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:54:01.997  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:02.000  4675  4738 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-26 22:54:02.000  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:54:02.000  4675  4742 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-26 22:54:02.001  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.001  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:02.001  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.001  5586  5633 I io.jxcore.node.ConnectionHelper: start: OK
,10-26 22:54:02.007  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 22:54:02.007  5586  5633 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-26 22:54:02.007  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:02.007  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 22:54:02.008  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:02.008  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-26 22:54:02.008  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:54:02.008  4675  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 22:54:02.008  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 22:54:02.008  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:54:02.008  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:54:02.008  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:54:02.008  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-26 22:54:02.008  4675  4742 D BtGatt.ScanManager: Starting BLE batch scan
,10-26 22:54:02.008  4675  4742 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 22:54:02.010  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.011  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.011  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 22:54:02.014  5586  5633 D BluetoothAdapter: STATE_ON
,10-26 22:54:02.015  4675  4896 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:54:02.016  4675  4687 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 22:54:02.016  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 22:54:02.017  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.017  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:54:02.017  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.017  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:02.017  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:54:02.017  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 22:54:02.017  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.017  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.017  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:54:02.017  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.019  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.019  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-26 22:54:02.019  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.019  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.019  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.019  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.019  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.019  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 22:54:02.020  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.020  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:02.020  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.020  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 22:54:02.020  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 22:54:02.021  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:54:02.021  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.022  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.022  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.022  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.022  4675  4738 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:54:02.022  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:02.022  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:54:02.022  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:02.022  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:54:02.022  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-26 22:54:02.022  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:02.022  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:54:02.022  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:02.023  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:54:02.023  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:02.023  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:02.023  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:02.023  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:02.024  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:02.024  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:02.024  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.025  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.025  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.025  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.025  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:02.025  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:02.025  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:02.025  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:02.026  5586  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-26 22:54:02.028  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:54:02.028  4675  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 22:54:02.028  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:54:02.035  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:54:02.035  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:02.035  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:02.035  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:02.035  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:54:02.035  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:02.035  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:54:02.035  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:54:02.035  4675  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-26 22:54:02.036  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:54:02.036  4675  4742 D BtGatt.ScanManager: stopping BLe Batch
,10-26 22:54:02.038  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:54:02.038  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:54:02.038  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:54:02.038  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-26 22:54:02.039  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-26 22:54:02.039  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:54:02.039  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 22:54:02.041  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:02.042  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 22:54:02.042  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:54:02.042  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 22:54:02.042  4675  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 22:54:02.042  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:54:02.043  4675  4742 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 22:54:02.043  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:02.046  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 22:54:02.046  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-26 22:54:02.046  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 22:54:02.047  4675  4738 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 22:54:02.047  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:54:02.052  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:02.052  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:54:02.052  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:54:02.052  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:54:02.052  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:54:02.052  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.053  5586  5633 D BluetoothAdapter: STATE_ON
10-26 22:54:02.054  4675  4896 D BtGatt.GattService: registerClient() - UUID=751a4357-b7ac-4a4e-8f97-8fafc5a2890a
10-26 22:54:02.055  4675  4738 D BtGatt.GattService: onClientRegistered() - UUID=751a4357-b7ac-4a4e-8f97-8fafc5a2890a, clientIf=5
,10-26 22:54:02.056  5586  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 22:54:02.056  4675  4888 D BtGatt.GattService: start scan with filters
10-26 22:54:02.058  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 22:54:02.058  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.058  4675  4742 D BtGatt.ScanManager: handling starting scan
10-26 22:54:02.058  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 22:54:02.059  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.059  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.059  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:54:02.059  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:54:02.059  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.059  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.059  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:54:02.059  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.062  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.062  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:54:02.062  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.062  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.062  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.062  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:54:02.062  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:54:02.063  4675  4738 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 22:54:02.064  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:54:02.064  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:54:02.064  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.064  4675  4742 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 22:54:02.066  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.066  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.066  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:02.066  5586  5633 I io.jxcore.node.ConnectionHelper: start: OK
,10-26 22:54:02.068  4675  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 22:54:02.068  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:54:02.069  4675  4742 D BtGatt.ScanManager: Starting BLE batch scan
10-26 22:54:02.069  4675  4742 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 22:54:02.077  4675  4738 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-26 22:54:02.077  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:54:02.082  4675  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 22:54:02.082  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:54:02.564  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-26 22:54:02.564  5586  5586 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 22:54:02.564  5586  5586 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 22:54:07.067  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:07.067  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:54:07.067  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 22:54:07.068  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:07.068  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 22:54:07.068  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:07.068  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 22:54:07.068  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:54:07.069  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-26 22:54:07.069  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:54:07.069  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.069  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.070  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 22:54:07.072  5586  5633 D BluetoothAdapter: STATE_ON
10-26 22:54:07.074  4675  4888 D BtGatt.GattService: stopScan() - queue size =1
,10-26 22:54:07.076  4675  4688 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-26 22:54:07.077  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-26 22:54:07.077  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.077  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-26 22:54:07.077  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:07.077  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.078  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:54:07.078  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 22:54:07.078  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.078  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.079  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:54:07.079  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.081  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.081  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:54:07.082  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.082  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:07.082  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.082  4675  4675 D BtGatt.ScanManager: awakened up at time 107544
10-26 22:54:07.083  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.083  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.083  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 22:54:07.083  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.083  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.083  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.084  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 22:54:07.085  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 22:54:07.087  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:54:07.087  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:07.088  4675  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 22:54:07.088  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:54:07.088  4675  4742 D BtGatt.ScanManager: stopping BLe Batch
10-26 22:54:07.088  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.089  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.089  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:07.089  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:54:07.089  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:54:07.089  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-26 22:54:07.096  4675  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-26 22:54:07.096  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:54:07.096  4675  4742 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 22:54:07.109  4675  4738 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,10-26 22:54:07.109  4675  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:54:07.109  4675  4738 D BtGatt.GattService: current time is 107571226881
10-26 22:54:07.109  4675  4738 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -78, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -79, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -79, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-26 22:54:07.110  4675  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-26 22:54:07.110  4675  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
10-26 22:54:07.110  4675  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
10-26 22:54:07.110  4675  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-26 22:54:07.590  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:54:07.590  5586  5586 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:07.591  5586  5586 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 22:54:10.150   927  5354 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110611, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-26 22:54:12.090  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 22:54:12.091  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:12.091  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:12.091  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:12.091  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.091  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:54:12.092  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:12.092  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
,10-26 22:54:12.092  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:54:12.092  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
,10-26 22:54:12.092  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:54:12.092  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:12.094  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:54:12.094  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:12.094  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:12.097  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.097  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.098  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.098  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:12.098  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 22:54:12.098  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.098  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.099  5586  5633 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-26 22:54:12.101  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:12.101  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:12.102  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:12.102  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 22:54:12.102  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.102  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.102  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:12.102  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:12.103  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.103  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.103  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:12.103  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:54:12.103  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.103  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.103  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.104  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.107  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.107  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.107  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:12.108  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:12.108  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:12.108  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.108  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.111  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-26 22:54:12.111  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:12.111  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:12.111  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:12.111  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 22:54:12.111  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.112  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.112  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:12.112  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:12.112  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.112  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.112  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:12.112  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.112  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:12.112  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.112  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.112  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:12.114  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.114  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:12.114  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.114  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:12.114  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:12.114  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.115  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.115  5586  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-26 22:54:12.116  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:12.116  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:12.116  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:12.116  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:12.116  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.116  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.116  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:12.116  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
,10-26 22:54:12.116  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.116  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.116  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:12.116  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.117  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.117  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.117  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:12.117  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.118  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.118  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.118  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.118  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:12.118  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:12.119  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.119  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.119  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-26 22:54:12.119  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:12.120  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:12.120  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:12.120  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:12.120  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.120  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.120  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:12.120  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:12.120  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:54:12.120  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.120  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:12.120  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.120  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.120  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.120  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.121  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.122  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.122  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.122  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.122  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:12.123  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:12.123  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:54:12.123  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.124  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 22:54:12.124  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:54:12.124  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:54:12.125  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 22:54:12.125  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:54:12.125  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:54:12.125  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-26 22:54:12.125  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:54:12.125  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 22:54:12.125  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:12.125  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:12.126  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:12.126  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:12.126  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.126  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.126  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:54:12.126  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:12.126  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.126  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.126  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:12.126  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.126  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:12.127  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.127  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.127  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.129  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.129  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.129  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.129  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:12.130  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:12.130  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:54:12.130  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.131  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 22:54:12.131  5586  5633 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-26 22:54:12.131  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-26 22:54:12.134  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 22:54:12.134  5586  5633 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-26 22:54:12.134  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-26 22:54:12.135  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-26 22:54:12.135  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-26 22:54:12.136  5586  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 22:54:12.136  5586  5633 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-26 22:54:12.136  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 22:54:12.136  5586  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 22:54:12.136  5586  5633 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-26 22:54:12.136  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 22:54:12.136  5586  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-26 22:54:12.136  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-26 22:54:12.140  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-26 22:54:12.141  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-26 22:54:12.141  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,10-26 22:54:12.143  4688  4688 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32865]" dev="sockfs" ino=32865 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-26 22:54:12.143  4688  4688 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32865]" dev="sockfs" ino=32865 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-26 22:54:12.142  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-26 22:54:12.143  5586  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
10-26 22:54:12.143  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-26 22:54:12.143  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-26 22:54:12.143  5586  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-26 22:54:12.143  5586  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,10-26 22:54:12.143  5586  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-26 22:54:12.143  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 22:54:12.143  5586  5633 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-26 22:54:12.145  5586  5646 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-26 22:54:12.145  5586  5646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:54:12.145  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:12.145  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:12.145  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:12.145  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:12.145  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.145  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.146  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:12.146  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-26 22:54:12.146  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:12.147  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.147  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
,10-26 22:54:12.147  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:12.147  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.147  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.147  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.147  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.147  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.147  5586  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
10-26 22:54:12.147  5586  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
10-26 22:54:12.147  5586  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
,10-26 22:54:12.147  5586  5646 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-26 22:54:12.147  5586  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-26 22:54:12.147  5586  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
10-26 22:54:12.148  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.149  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.149  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.149  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:12.149  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:12.149  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:54:12.149  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.150  5586  5633 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-26 22:54:12.151  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:12.151  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:12.151  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:12.152  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:12.152  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.152  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.152  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:54:12.152  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:12.152  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.152  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.152  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:12.152  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.152  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.152  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.152  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.152  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:12.153  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:12.153  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.153  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.153  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:12.153  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:12.153  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.153  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.154  5586  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-26 22:54:12.154  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:12.154  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:12.154  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 22:54:12.154  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:12.155  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.155  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.155  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:12.155  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:12.155  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.155  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.155  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:12.155  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.155  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.155  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.155  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:12.155  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.156  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.156  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.156  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.156  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:12.156  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:12.156  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.156  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.157  5586  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-26 22:54:12.157  5586  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-26 22:54:12.157  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 22:54:12.157  5586  5633 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-26 22:54:12.157  5586  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,10-26 22:54:12.157  5586  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-26 22:54:12.158  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 22:54:12.158  5586  5633 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-26 22:54:12.158  5586  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-26 22:54:12.158  5586  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-26 22:54:12.158  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 22:54:12.158  5586  5633 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-26 22:54:12.158  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:12.158  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:12.158  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:12.159  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:12.159  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:54:12.159  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.159  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:12.159  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:12.159  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.159  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.159  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:12.159  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.159  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.160  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.160  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.160  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:12.161  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.161  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.161  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:12.162  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:12.162  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:12.162  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.162  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.162  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:12.163  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.163  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:12.163  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:54:12.163  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:12.163  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:12.163  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:12.163  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:12.163  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:12.163  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:13.253   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-26 22:54:13.254   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-26 22:54:17.164  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.164  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
,10-26 22:54:17.164  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:17.165  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.165  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.165  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:54:17.165  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:17.166  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:17.166  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 22:54:17.166  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:17.166  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:17.166  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.166  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.167  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:17.167  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:17.167  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.167  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
,10-26 22:54:17.167  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:17.167  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.168  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.168  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:54:17.168  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.169  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:17.173  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.173  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.173  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.173  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:17.173  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:17.174  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.174  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:17.177  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-26 22:54:17.178  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:54:17.180  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-26 22:54:17.182  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-26 22:54:17.182  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-26 22:54:17.182  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-26 22:54:17.183  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-26 22:54:17.183  5586  5586 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-26 22:54:17.183  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 22:54:17.183  5586  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-26 22:54:17.184  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 22:54:17.184  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-26 22:54:17.184  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-26 22:54:17.184  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-26 22:54:17.184  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:17.185  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-26 22:54:17.186  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-26 22:54:17.186  5586  5648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:54:17.186  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:17.186  5586  5586 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-26 22:54:17.186  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.186  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:54:17.186  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:54:17.186  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:54:17.187  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.187  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.187  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:17.190  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:17.187  4888  4888 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32072]" dev="sockfs" ino=32072 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 22:54:17.190  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:54:17.190  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:17.191  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.191  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:54:17.191  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
,10-26 22:54:17.191  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:54:17.187  4888  4888 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32072]" dev="sockfs" ino=32072 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 22:54:17.191  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:17.191  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:54:17.191  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:17.191  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:17.192  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:17.192  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.192  5586  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-26 22:54:17.192  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.192  5586  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-26 22:54:17.192  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-26 22:54:17.192  5586  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-26 22:54:17.192  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:17.193  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.193  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:17.193  5586  5586 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-26 22:54:17.193  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:17.193  5586  5586 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:17.193  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.193  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.193  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:54:17.193  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.194  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.195  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.196  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.196  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.196  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 22:54:17.196  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:17.196  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.196  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:17.198  5586  5633 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-26 22:54:17.199  5586  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-26 22:54:17.199  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-26 22:54:17.199  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:54:17.199  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 22:54:17.199  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:17.199  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:17.200  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:17.200  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:17.200  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.200  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.200  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:17.200  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:17.200  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.200  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:17.201  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:17.201  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:54:17.201  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.201  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.201  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.201  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:54:17.207  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.207  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.207  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.209  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:17.209  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:17.209  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:54:17.209  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
,10-26 22:54:17.215  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 22:54:17.215  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:17.215  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:17.215  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:17.215  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.215  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.215  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:17.215  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:17.215  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.216  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:17.216  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:17.216  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.216  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.216  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.216  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.216  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.217  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.217  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.217  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.217  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:17.217  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:17.217  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.218  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:17.219  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:54:17.219  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:54:17.219  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:54:17.219  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:54:17.219  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given list,ener does not exist in the list - probably already removed
10-26 22:54:17.219  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.219  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:54:17.219  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4162736 not in the list
10-26 22:54:17.219  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.219  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:17.219  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:17.219  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.220  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.220  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:17.220  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:17.220  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.221  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.221  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.221  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:54:17.221  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:54:17.221  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:54:17.222  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:17.222  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7255637 not in the list
10-26 22:54:17.223  5586  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-26 22:54:17.223  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 22:54:17.224  5586  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-26 22:54:17.224  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 22:54:17.224  5586  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-26 22:54:17.224  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-26 22:54:17.226  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-26 22:54:17.227  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-26 22:54:17.227  5586  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-26 22:54:17.227  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-26 22:54:17.227  5586  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-26 22:54:17.227  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-26 22:54:17.227  5586  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-26 22:54:17.227  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,10-26 22:54:17.228  5586  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-26 22:54:17.228  5586  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-26 22:54:17.228  5586  5633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-26 22:54:17.228  5586  5633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-26 22:54:17.228  5586  5633 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-26 22:54:17.228  5586  5633 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-26 22:54:17.229  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:54:17.230  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6377041 added. We now have 3 listener(s)
10-26 22:54:17.230  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:54:17.232  5586  5633 D BluetoothAdapter: enable(): BT is already enabled..!
,10-26 22:54:17.232   927  3866 D WifiService: setWifiEnabled: true pid=5586, uid=10077
10-26 22:54:17.232   927  3866 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:54:17.274  4675  4872 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-26 22:54:17.274  4675  4886 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-26 22:54:17.692  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:54:18.254   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:19.255   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:20.252   927  3008 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 22:54:20.257   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:21.260   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:22.237  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:54:22.238  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d14c9e6 added. We now have 4 listener(s)
,10-26 22:54:22.238  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:54:22.252  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:54:22.253  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d14c9e6 removed from the list
,10-26 22:54:22.253  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:54:22.253  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:54:22.253  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:22.255  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:54:22.256  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5423b27 added. We now have 4 listener(s)
,10-26 22:54:22.256  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:54:22.258  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:54:22.258  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5423b27 removed from the list
10-26 22:54:22.258  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:54:22.258  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:22.258  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:22.259  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:54:22.259  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26341d4 added. We now have 4 listener(s)
10-26 22:54:22.259  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:54:22.261   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:22.262   927  3609 D WifiService: setWifiEnabled: false pid=5586, uid=10077
10-26 22:54:22.263   927  3609 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:54:22.266   927  3008 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-26 22:54:22.266   927  3008 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-26 22:54:22.266   927  3008 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 22:54:22.267   927  3008 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:54:22.273  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:54:22.276  4675  4734 D BluetoothAdapterState: Current state: ON, message: 23
10-26 22:54:22.276  4675  4734 D BluetoothAdapterProperties: Setting state to 13
10-26 22:54:22.276  4675  4734 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-26 22:54:22.276  4675  4734 D BluetoothAdapterProperties: onBluetoothDisable()
,10-26 22:54:22.278  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.278  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:54:22.278  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.278  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.278  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:22.278  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:54:22.278  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:22.278  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:54:22.278  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:54:22.279  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.279  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:54:22.280   927  5355 D DhcpClient: Clearing IP address
10-26 22:54:22.280  4675  4675 D BluetoothMapService: onReceive
10-26 22:54:22.280  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:54:22.280  4675  4675 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 22:54:22.280  4675  4675 D BluetoothMapService: STATE_TURNING_OFF
10-26 22:54:22.280  4675  4675 D BluetoothMapService: MAP Service closeService in
10-26 22:54:22.280  4675  4675 D BluetoothMapMasInstance0: MAP Service shutdown
10-26 22:54:22.280  4675  4675 D ObexServerSockets0: shutdown(block = true)
,10-26 22:54:22.280   507   921 D CommandListener: Clearing all IP addresses on wlan0
10-26 22:54:22.281  4675  4675 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 22:54:22.281  4675  4675 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 22:54:22.281  4675  4886 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-26 22:54:22.281  4675  4899 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-26 22:54:22.282  4675  4898 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-26 22:54:22.283  4675  4675 I BtOppRfcommListener: stopping Accept Thread
,10-26 22:54:22.284  4675  5285 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-26 22:54:22.284  4675  5285 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-26 22:54:22.285  4675  4734 I BluetoothAdapterState: Entering PendingCommandState
,10-26 22:54:22.289  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.290  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.290  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.290  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.290  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:22.290  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.290  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:22.290  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:54:22.290  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:54:22.290  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:54:22.290  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:22.292   507   921 D CommandListener: Setting iface cfg
10-26 22:54:22.293  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:22.297  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:54:22.298  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.298  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.298  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.298  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:22.298  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.298  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:22.298  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:54:22.298  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:54:22.298  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:54:22.298  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:54:22.299  3615  5406 V NativeCrypto: Read error: ssl=0x7fa2461000: I/O error during system call, Connection timed out
10-26 22:54:22.301  3615  5406 V NativeCrypto: SSL shutdown failed: ssl=0x7fa2461000: I/O error during system call, Broken pipe
10-26 22:54:22.303   927   938 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-26 22:54:22.303   927  5353 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-26 22:54:22.306   927  5353 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-26 22:54:22.306  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.306  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.306  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.306  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.306  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:22.306  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.306  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:22.306  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:54:22.306  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:54:22.306   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,10-26 22:54:22.306   927  3010 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-26 22:54:22.306  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:54:22.307  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:22.307   927  3010 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-26 22:54:22.308   927   940 I ActivityManager: Start proc 5652:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-26 22:54:22.310  4675  4738 D BluetoothAdapterProperties: Scan Mode:20
10-26 22:54:22.311  4675  4734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-26 22:54:22.311  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.311  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.311  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.311  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.311  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:22.311  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.311  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:22.311  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:54:22.311  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:54:22.312  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.312  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:22.313   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-26 22:54:22.313   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-26 22:54:22.313  4675  4675 D HeadsetService: Received stop request...Stopping profile...
10-26 22:54:22.314   533   533 E Parcel  : Reading a NULL string not supported here.
10-26 22:54:22.315   927   927 D BluetoothHeadset: Proxy object disconnected
10-26 22:54:22.316  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.315  4675  4675 V BluetoothAdapterState: isTurningOff()=true
10-26 22:54:22.315  3163  3174 D BluetoothHeadset: Proxy object disconnected
10-26 22:54:22.316  4675  4675 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:22.316  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.316  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.316  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.316  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:22.316  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.316  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:22.316  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:22.316  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:54:22.316  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:22.316  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:54:22.317   927   927 D BluetoothHeadset: Proxy object disconnected
,10-26 22:54:22.317  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.317   927   927 D BluetoothHeadset: Proxy object disconnected
10-26 22:54:22.316   927  5356 D DhcpClient: Receive thread stopped
10-26 22:54:22.317  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:22.317  3805  3826 D BluetoothHeadset: Proxy object disconnected
10-26 22:54:22.318  3163  3163 D HeadsetProfile: Bluetooth service disconnected
10-26 22:54:22.319  4675  4675 D A2dpService: Received stop request...Stopping profile...
10-26 22:54:22.319   927   927 D RttService: SCAN_AVAILABLE : 1
10-26 22:54:22.319  4675  4891 D A2dpStateMachine: Exit Disconnected: -1
10-26 22:54:22.319   927  3010 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-26 22:54:22.320   927  3116 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-26 22:54:22.320  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.320  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.320  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.320  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.320  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:22.320  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.320  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:22.320  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:22.320  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:54:22.320   927   927 D BluetoothA2dp: Proxy object disconnected
10-26 22:54:22.320  3163  3163 D BluetoothA2dp: Proxy object disconnected
10-26 22:54:22.321  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.321  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:54:22.323  3771  3897 W QCNEJ   : |CORE| network lost: 100
10-26 22:54:22.324  3771  3897 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-26 22:54:22.325  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.325  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.325  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.325  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.325  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:22.325  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.325  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:22.325  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:22.325  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:22.326  4675  4675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-26 22:54:22.326  4675  4675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-26 22:54:22.326  4675  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:54:22.327  4675  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:54:22.327  4675  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:54:22.327  4675  4738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-26 22:54:22.327  4675  4738 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-26 22:54:22.327  4675  4675 D HidService: Received stop request...Stopping profile...
10-26 22:54:22.327  4675  4675 D HidService: Stopping Bluetooth HidService
10-26 22:54:22.329   927  3008 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-26 22:54:22.330  4675  4675 D HealthService: Received stop request...Stopping profile...
10-26 22:54:22.331  3163  3163 D BluetoothInputDevice: Proxy object disconnected
10-26 22:54:22.331  3163  3163 D HidProfile: Bluetooth service disconnected
10-26 22:54:22.331  4675  4675 V BluetoothAdapterState: isTurningOff()=true
10-26 22:54:22.331  4675  4675 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:22.331  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:22.331  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:54:22.332  4675  4738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-26 22:54:22.332  4675  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 22:54:22.333  4675  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:54:22.333  4675  4872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 22:54:22.333  4675  4872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 22:54:22.333  4675  4872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 22:54:22.333  4675  4872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 22:54:22.334  4675  4675 D PanService: Received stop request...Stopping profile...
,10-26 22:54:22.335  4675  4675 D BluetoothMapService: Received stop request...Stopping profile...
10-26 22:54:22.336  4675  4675 D BluetoothMapService: stop()
,10-26 22:54:22.339   927  3008 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-26 22:54:22.341  4675  4675 D BluetoothMapAppObserver: deinitObservers()
10-26 22:54:22.341  4675  4675 D BluetoothMapAppObserver: removeReceiver()
10-26 22:54:22.342  4675  4675 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:54:22.342  4675  4675 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:22.343  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:22.343  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:22.343  4675  4675 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-26 22:54:22.343  4675  4675 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-26 22:54:22.343  4675  4738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-26 22:54:22.343  4675  4675 D SapService: Received stop request...Stopping profile...
,10-26 22:54:22.344  4675  4675 V SapService: stop()
10-26 22:54:22.344  4675  4675 V BluetoothAdapterState: isTurningOff()=true
10-26 22:54:22.344  4675  4675 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:22.345  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:22.345  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:22.345  4675  4675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-26 22:54:22.345  4675  4738 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-26 22:54:22.345  4675  4675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-26 22:54:22.345  4675  4675 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:54:22.345  4675  4675 V BluetoothAdapterState: isTurningOn()=false
,10-26 22:54:22.345  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 22:54:22.345  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:22.346  4675  4675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-26 22:54:22.346  4675  4675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-26 22:54:22.346  4675  4675 D BluetoothMapService: MAP Service closeService in
10-26 22:54:22.346  4675  4675 V BluetoothAdapterState: isTurningOff()=true
10-26 22:54:22.346  4675  4675 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:22.347  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:22.347  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:22.347  4675  4675 D BluetoothMapService: cleanup()
10-26 22:54:22.347  4675  4675 D BluetoothMapService: MAP Service closeService in
10-26 22:54:22.347  4675  4675 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:54:22.347  4675  4675 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:22.347  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:22.347  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:22.347  4675  4734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-26 22:54:22.347  4675  4734 D BluetoothAdapterProperties: Setting state to 15
10-26 22:54:22.347  4675  4734 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-26 22:54:22.348  4675  4734 I BluetoothAdapterState: Entering BleOnState
10-26 22:54:22.348  3805  3826 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 22:54:22.349   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-26 22:54:22.350  3163  3163 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 22:54:22.350  3163  3163 D PanProfile: Bluetooth service disconnected
10-26 22:54:22.351  3163  3163 D BluetoothMap: Proxy object disconnected
10-26 22:54:22.351  3163  3163 D MapProfile: Bluetooth service disconnected
10-26 22:54:22.352   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:54:22.352   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:54:22.352  3163  3174 D BluetoothPan: onBluetoothStateChange on: false
10-26 22:54:22.353   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 22:54:22.353  3163  5585 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 22:54:22.353  3163  3400 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:54:22.354  3163  3175 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 22:54:22.354  3163  3174 D BluetoothMap: onBluetoothStateChange: up=false
10-26 22:54:22.355   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 22:54:22.355  3163  5585 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 22:54:22.357  4675  4734 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-26 22:54:22.357  4675  4734 D BluetoothAdapterProperties: Setting state to 16
,10-26 22:54:22.357  4675  4734 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-26 22:54:22.357  4675  4734 D BluetoothAdapterProperties: onBleDisable
10-26 22:54:22.358  4675  4734 I BluetoothAdapterState: Entering PendingCommandState
10-26 22:54:22.358  4675  4735 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-26 22:54:22.358  4675  4738 D BluetoothAdapterProperties: Scan Mode:20
10-26 22:54:22.359  4675  4872 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-26 22:54:22.359  4675  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:54:22.359  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.359  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.359  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.359  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.359  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:22.359  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.359  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:22.359  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:22.359  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:22.361  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.361  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.361  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.361  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.361  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:22.361  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.361  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:22.361  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:22.361  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:22.362  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:22.364  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:22.365  5652  5652 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-26 22:54:22.365  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:22.368  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:22.371   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:54:22.372   507   921 D CommandListener: Clearing all IP addresses on wlan0
10-26 22:54:22.372   507   921 D TetherController: Setting IP forward enable = 0
10-26 22:54:22.373   927  3010 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-26 22:54:22.373   927  3010 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-26 22:54:22.374   927   944 D Tethering: MasterInitialState.processMessage what=3
,10-26 22:54:22.376   927  3008 D DhcpClient: doQuit
10-26 22:54:22.376   927  3008 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-26 22:54:22.377   927  5355 D DhcpClient: onQuitting
,10-26 22:54:22.377  3483  3483 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-26 22:54:22.377  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:22.382  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.382  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.382  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.382  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.382  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:22.382  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.382  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:22.382  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:22.382  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:22.382  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.382  5240  5240 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f4733e9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-26 22:54:22.382  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:54:22.384  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:54:22.384  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.384  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.384  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.384  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:22.384  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.384  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:22.384  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:22.384  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:22.384  5028  5041 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-26 22:54:22.384  5028  5041 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 22:54:22.384  5028  5041 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-26 22:54:22.384  5028  5041 E SarControlService: no key has been found,reset the power
10-26 22:54:22.384  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.384  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:22.384  5028  5066 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 22:54:22.385  5028  5066 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,10-26 22:54:22.385  5028  5066 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-26 22:54:22.385  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 22:54:22.385  5054  5054 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 22:54:22.386  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.386  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:22.386  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:22.386  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:22.386  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:22.386  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:22.386  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:22.386  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:22.386  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:22.387  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:22.387  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:22.388  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:22.389  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:22.381  3973  3973 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-26 22:54:22.391  5028  5066 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-26 22:54:22.391  5028  5066 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 22:54:22.391  5028  5066 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-26 22:54:22.391  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 22:54:22.391  5054  5054 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-26 22:54:22.394  5054  5068 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@75c5457 HexData = [00000000ea03000000000000ffffffff]
,10-26 22:54:22.394  5054  5068 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 22:54:22.394  5054  5068 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-26 22:54:22.395  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 22:54:22.396  5028  5038 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-26 22:54:22.403  5054  5068 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@75c5457 HexData = [00000000eb03000000000000ffffffff]
,10-26 22:54:22.403  5054  5068 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 22:54:22.404  5054  5068 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-26 22:54:22.404  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 22:54:22.404  5028  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 22:54:22.405  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 22:54:22.406  3483  3483 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-26 22:54:22.410   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fe1f803:true
,10-26 22:54:22.411  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 22:54:22.413  3483  3483 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-26 22:54:22.428   507   921 E Netd    : netlink response contains error (No such file or directory)
,10-26 22:54:22.429   927  3010 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-26 22:54:22.429   927  3010 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-26 22:54:22.432  5652  5652 D LocalBluetoothProfileManager: Adding local MAP profile
,10-26 22:54:22.434  5652  5652 D BluetoothMap: Create BluetoothMap proxy object
,10-26 22:54:22.439  5652  5652 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-26 22:54:22.444  3483  3483 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-26 22:54:22.447  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,10-26 22:54:22.449  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 22:54:22.454  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,10-26 22:54:22.454  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 22:54:22.455  3483  3483 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-26 22:54:22.456   927  4042 I ActivityManager: Killing 5381:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-26 22:54:22.474  4110  4110 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-26 22:54:22.478  4110  4110 D SystemUpdateService: onCreate
10-26 22:54:22.481  4110  4110 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 22:54:22.489  4110  4110 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
10-26 22:54:22.493  4110  5378 I iu.UploadsManager: num queued entries: 0
10-26 22:54:22.493  4110  5378 I iu.UploadsManager: num updated entries: 0
10-26 22:54:22.494  4110  5378 I iu.SyncManager: NEXT; no task
10-26 22:54:22.496  4110  5683 I SystemUpdateService: active receiver: enabled
10-26 22:54:22.498  4110  4110 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-26 22:54:22.499  4110  4110 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-26 22:54:22.502  4110  5683 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-26 22:54:22.504  4110  5683 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-26 22:54:22.504  4110  5683 I SystemUpdateService: now status is 0 (complete)
10-26 22:54:22.504  4110  5683 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 22:54:22.504  4110  5683 I SystemUpdateService: file has been verified
10-26 22:54:22.505  4110  5683 I SystemUpdateService: OTA package size = 21989297
10-26 22:54:22.511   927   937 I ActivityManager: Start proc 5685:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
10-26 22:54:22.511  4110  5683 I SystemUpdateService: showing system update notification
,10-26 22:54:22.524   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 22:54:22.526  4110  4110 D SystemUpdateService: onDestroy
,10-26 22:54:22.553  5685  5685 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-26 22:54:22.555  5685  5685 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:54:22.559   927  3008 D wifi    : In wifi stop Hal
,10-26 22:54:22.559  4474  4474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 22:54:22.559   927  3008 D wifi    : halHandle = 0x7f90965900, mVM = 0x7facf0d140, mCls = 0x100a02
10-26 22:54:22.559   927  3482 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-26 22:54:22.559   927  3482 D WifiHAL : Got a signal to exit!!!
10-26 22:54:22.559   927  3482 I WifiHAL : Exit wifi_event_loop
10-26 22:54:22.560   927  3008 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-26 22:54:22.560   927  3008 E WifiHAL : Event processing terminated
10-26 22:54:22.560   927  3008 D wifi    : In wifi cleaned up handler
10-26 22:54:22.560   927  3008 I WifiHAL : Internal cleanup completed
10-26 22:54:22.561  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:22.562  3984  4239 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 22:54:22.563  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:22.564  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:22.565  5685  5685 D SprintDMHelper: simOperator: 
10-26 22:54:22.566  5685  5685 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 22:54:22.568  4675  4738 I bt_hci  : shut_down
,10-26 22:54:22.574  4675  4745 I bt_vendor: low_power_mode_cb
,10-26 22:54:22.579  4474  5697 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-26 22:54:22.581  4675  4745 D bt_hwcfg: hw_epilog_process
,10-26 22:54:22.581   927   937 I ActivityManager: Killing 5240:com.google.android.music:main/u0a59 (adj 15): empty #17
10-26 22:54:22.584   927  3482 D wifi    : set interface wlan0 flags (DOWN)
,10-26 22:54:22.584   927  3008 D WifiNative-HAL: HAL event thread stopped successfully
10-26 22:54:22.584  4675  4745 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-26 22:54:22.584  4675  4745 I bt_vendor: epilog_cb
10-26 22:54:22.584  4675  4745 I bt_hci  : epilog_finished_callback
,10-26 22:54:22.610   927   937 I ActivityManager: Start proc 5698:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-26 22:54:22.611  4675  4738 I bt_hci_h4: hal_close
10-26 22:54:22.611  4675  4738 I bt_userial_vendor: device fd = 54 close
,10-26 22:54:22.639  5698  5698 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-26 22:54:22.645   927  3629 I ActivityManager: Killing 3902:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-26 22:54:22.720  4675  4735 D bt_stack_manager: event_shut_down_stack finished.
,10-26 22:54:22.721  4675  4734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-26 22:54:22.722  4675  4734 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-26 22:54:22.723  4675  4675 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-26 22:54:22.723  4675  4675 D BtGatt.GattService: Received stop request...Stopping profile...
10-26 22:54:22.723  4675  4675 D BtGatt.GattService: stop()
10-26 22:54:22.723  4675  4675 D BtGatt.AdvertiseManager: advertise clients cleared
,10-26 22:54:22.725  4675  4675 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:54:22.725  4675  4675 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:22.725  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:22.725  4675  4675 V BluetoothAdapterState: isBleTurningOff()=true
10-26 22:54:22.725  4675  4734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-26 22:54:22.726  4675  4734 D BluetoothAdapterProperties: Setting state to 10
10-26 22:54:22.726  4675  4734 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-26 22:54:22.726  4675  4734 I BluetoothAdapterState: Entering OffState
,10-26 22:54:22.727   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-26 22:54:22.734  4675  4675 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-26 22:54:22.734  4675  4675 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-26 22:54:22.734  4675  4675 I BluetoothServiceJni: cleanupNative: return from cleanup
10-26 22:54:22.735  4675  4735 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-26 22:54:22.739  4675  4675 I art     : System.exit called, status: 0
,10-26 22:54:22.739  4675  4675 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-26 22:54:22.761   927  3192 I ActivityManager: Process com.android.bluetooth (pid 4675) has died
,10-26 22:54:22.787   927   944 D Tethering: InitialState.processMessage what=4
,10-26 22:54:22.790   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-26 22:54:23.262   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-26 22:54:23.443   507   921 D TetherController: Setting IP forward enable = 0
,10-26 22:54:27.284   927  4039 D WifiService: setWifiEnabled: true pid=5586, uid=10077
,10-26 22:54:27.285   927  4039 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:54:27.294   507   921 D SoftapController: Softap fwReload - Ok
,10-26 22:54:27.300   507   921 D CommandListener: Setting iface cfg
,10-26 22:54:27.300   507   921 D CommandListener: Trying to bring down wlan0
10-26 22:54:27.301   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-26 22:54:27.304   927  3008 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 22:54:27.901   927  3008 D wifi    : set interface wlan0 flags (UP)
,10-26 22:54:27.906   927  3008 I WifiHAL : Initializing wifi
10-26 22:54:27.906   927  3008 I WifiHAL : Creating socket
10-26 22:54:27.908   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-26 22:54:27.911   927  3008 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-26 22:54:27.911   927  3008 D wifi    : Did set static halHandle = 0x7f90965900
10-26 22:54:27.911   927  3008 D wifi    : halHandle = 0x7f90965900, mVM = 0x7facf0d140, mCls = 0x10194e
10-26 22:54:27.911   927  3008 D wifi    : array field set
,10-26 22:54:27.912   927  3008 I WifiNative-HAL: interface[0] = wlan0
10-26 22:54:27.915   927  5719 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547886618880
10-26 22:54:27.915   927  5719 D wifi    : waitForHalEvents called, vm = 0x7facf0d140, obj = 0x10194e, env = 0x7f8e543800
,10-26 22:54:27.990  5720  5720 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-26 22:54:28.016   927  3008 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-26 22:54:28.023  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:28.026  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:28.027  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:28.066  5720  5720 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 22:54:28.071  5720  5720 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 22:54:28.071  5720  5720 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-26 22:54:28.083   927  3008 D WifiConfigStore: Loading config and enabling all networks 
,10-26 22:54:28.088  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:54:28.088  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:28.088  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:28.088  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:28.088  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:28.088  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:28.088  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:28.088  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:28.088  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:28.088  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:28.088  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:54:28.091  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:54:28.091  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:28.091  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:28.091  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:28.091  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:28.091  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:28.091  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:28.091  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:28.091  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:28.091  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:28.091  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:28.093  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:28.093  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:28.093  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:28.093  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:28.093  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:28.093  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:28.093  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:28.093  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:28.093  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:28.093  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:28.094  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:54:28.100   927  3008 D WifiConfigStore: loaded 0 passpoint configs
,10-26 22:54:28.101   927  3008 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
10-26 22:54:28.101   927  3008 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-26 22:54:28.101   927  3008 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-26 22:54:28.102   927  3008 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-26 22:54:28.102   927  3008 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
10-26 22:54:28.102   927  3008 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-26 22:54:28.103   927  3008 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-26 22:54:28.103   927  3008 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,10-26 22:54:28.103   927  3008 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-26 22:54:28.103   927  3008 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-26 22:54:28.103   927  3008 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-26 22:54:28.103   927  3008 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-26 22:54:28.105   927  3008 D WifiNative-HAL: Setting external_sim to 1
,10-26 22:54:28.105   927  3008 D wifi    : setting dfs flag to true, 0x7f91c774a0
10-26 22:54:28.105   927  3008 D WifiStateMachine: Setting OUI to DA-A1-19
10-26 22:54:28.105  4474  4474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 22:54:28.105   927  3008 D wifi    : setting scan oui 0x7f91c774a0
10-26 22:54:28.105   927  3008 D WifiHAL : Sending mac address OUI
,10-26 22:54:28.108   927  3008 E native  : do suspend false
,10-26 22:54:28.114   927  3008 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-26 22:54:28.114   927   927 D RttService: SCAN_AVAILABLE : 3
10-26 22:54:28.114   927  3116 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-26 22:54:28.117   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-26 22:54:28.119   507   921 D CommandListener: Setting iface cfg
,10-26 22:54:28.120   927  3007 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '121 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 121 Failed to set address (No such device)'
,10-26 22:54:28.120   927  3007 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-26 22:54:28.126   927  3007 D WifiNative-HAL: p2pGetDeviceAddress
,10-26 22:54:28.129   927  3007 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-26 22:54:28.129   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128591 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,10-26 22:54:28.263   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:29.263   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:30.264   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:31.209  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 22:54:31.213  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 22:54:31.218  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 22:54:31.226  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 22:54:31.265   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:31.309   927  3008 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-26 22:54:31.310   927  3008 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-26 22:54:31.310   927  3008 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:54:31.321   927  3008 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-26 22:54:31.356   927  3008 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-26 22:54:31.363  5720  5720 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-26 22:54:31.794  5720  5720 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-26 22:54:31.828  5720  5720 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-26 22:54:31.829  5720  5720 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-26 22:54:31.838   927  3008 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-26 22:54:31.838   927  3008 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:54:31.839   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-26 22:54:31.855   927  3008 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:54:31.866   507   921 D CommandListener: Setting iface cfg
,10-26 22:54:31.871   927  3008 D WifiStateMachine: Start Dhcp Watchdog 2
,10-26 22:54:31.877   927  5728 D DhcpClient: Receive thread started
,10-26 22:54:31.881   927  3010 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 22:54:31.881   927  3008 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-26 22:54:31.881   927  3010 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-26 22:54:31.962   927  3008 E native  : do suspend false
,10-26 22:54:31.972   927  5727 D DhcpClient: Broadcasting DHCPDISCOVER
,10-26 22:54:32.000   927  5728 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,10-26 22:54:32.001   927  5727 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,10-26 22:54:32.003   927  5727 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-26 22:54:32.016   927  5728 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-26 22:54:32.017   927  5727 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-26 22:54:32.022   507   921 D CommandListener: Setting iface cfg
,10-26 22:54:32.027   927  3008 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-26 22:54:32.032   927  5727 D DhcpClient: Scheduling renewal in 86399s
,10-26 22:54:32.042   927  3008 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-26 22:54:32.043   927  3008 D WifiConfigStore: No blacklist allowed without epno enabled
,10-26 22:54:32.044   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-26 22:54:32.046   927  3010 D ConnectivityService: Adding iface wlan0 to network 101
,10-26 22:54:32.057   927  3008 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-26 22:54:32.092   927  3010 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-26 22:54:32.092   927  3010 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-26 22:54:32.095   927  3010 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-26 22:54:32.097   927  3010 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-26 22:54:32.099   927  3010 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-26 22:54:32.106   927  3010 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 22:54:32.110   927  3010 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-26 22:54:32.110   927  3010 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-26 22:54:32.111   927  3010 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-26 22:54:32.111   927  3008 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-26 22:54:32.111   927  3010 D ConnectivityService:    accepting network in place of null
,10-26 22:54:32.111   927  3008 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 22:54:32.112   927  3010 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 22:54:32.126   927  5726 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132587, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-26 22:54:32.135   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:54:32.158   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:54:32.162   927  3010 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-26 22:54:32.162   927  3010 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-26 22:54:32.162  3771  3897 W QCNEJ   : |CORE| network available: 101
10-26 22:54:32.163   927  3010 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-26 22:54:32.165   927   944 D Tethering: MasterInitialState.processMessage what=3
,10-26 22:54:32.167  3771  3897 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-26 22:54:32.168  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.169  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:32.169  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:32.169  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:32.169  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:32.169  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:32.169  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:32.169  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:54:32.169  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:54:32.169  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.169  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:32.169  3771  3897 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-26 22:54:32.169  3771  3897 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-26 22:54:32.172  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.172  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:32.172  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:32.172  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:32.172  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:32.172  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:32.172  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:32.172  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:54:32.172  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:54:32.172  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.172  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:32.172   927   938 D ConnectivityService: Returning blocked NetworkInfo to uid=10062
10-26 22:54:32.174  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.174  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:32.174  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:32.174  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:32.174  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:32.174  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:32.174  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:54:32.174  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:54:32.174  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:54:32.174  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.174  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:54:32.180  3973  3973 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-26 22:54:32.182  4110  4110 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-26 22:54:32.186  4110  4110 D SystemUpdateService: onCreate
,10-26 22:54:32.190  4110  4110 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 22:54:32.196   927  5725 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-26 22:54:32.202  4110  4110 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-26 22:54:32.207  4110  5378 I iu.UploadsManager: num queued entries: 0
,10-26 22:54:32.207  4110  5378 I iu.UploadsManager: num updated entries: 0
,10-26 22:54:32.209  4110  5737 I SystemUpdateService: active receiver: enabled
,10-26 22:54:32.211  4110  4110 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-26 22:54:32.212  4110  4110 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-26 22:54:32.214  5685  5685 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:54:32.219  5685  5685 D SprintDMHelper: simOperator: 
10-26 22:54:32.219  5685  5685 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 22:54:32.233   927  3609 D ConnectivityService: Returning blocked NetworkInfo to uid=10053
,10-26 22:54:32.246  4110  5737 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 22:54:32.245  4110  5378 I iu.SyncManager: NEXT; no task
,10-26 22:54:32.251  4110  5737 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-26 22:54:32.251  4110  5737 I SystemUpdateService: now status is 0 (complete)
10-26 22:54:32.252  4110  5737 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 22:54:32.252  4110  5737 I SystemUpdateService: file has been verified
10-26 22:54:32.252  4110  5737 I SystemUpdateService: OTA package size = 21989297
,10-26 22:54:32.257   927  5725 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 26 Oct 2016 20:54:32 GMT], X-Android-Received-Millis=[1477515272256], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477515272233]}
,10-26 22:54:32.257   927  3010 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-26 22:54:32.257   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-26 22:54:32.257   927  3010 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 22:54:32.258  4110  5737 I SystemUpdateService: showing system update notification
,10-26 22:54:32.260   927  3010 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-26 22:54:32.266   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 22:54:32.266   535   535 I ServiceManager: Waiting for service AtCmdFwd...
10-26 22:54:32.267  4110  4110 D SystemUpdateService: onDestroy
,10-26 22:54:32.290   927  3866 D WifiService: setWifiEnabled: false pid=5586, uid=10077
,10-26 22:54:32.290   927  3866 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-26 22:54:32.291   927  3008 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-26 22:54:32.291   927  3008 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-26 22:54:32.291   927  3008 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 22:54:32.291   927  3008 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:54:32.300   927  5727 D DhcpClient: Clearing IP address
,10-26 22:54:32.300   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-26 22:54:32.302   507   921 D CommandListener: Setting iface cfg
,10-26 22:54:32.304   927  5728 D DhcpClient: Receive thread stopped
,10-26 22:54:32.304  3615  5738 V NativeCrypto: SSL handshake aborted: ssl=0x7fa6cb9380: I/O error during system call, Connection timed out
,10-26 22:54:32.310   927  4039 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,10-26 22:54:32.310   927  5725 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,10-26 22:54:32.311   927  5725 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-26 22:54:32.313   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-26 22:54:32.314   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-26 22:54:32.316   927   927 D RttService: SCAN_AVAILABLE : 1
,10-26 22:54:32.316   927  3116 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-26 22:54:32.317   533   533 E Parcel  : Reading a NULL string not supported here.
10-26 22:54:32.320   927  5725 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
10-26 22:54:32.322   927  3010 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-26 22:54:32.324  3771  3897 W QCNEJ   : |CORE| network lost: 101
10-26 22:54:32.324  3771  3897 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-26 22:54:32.327   927  3008 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-26 22:54:32.327   927  3008 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-26 22:54:32.344   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:54:32.362   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-26 22:54:32.363   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-26 22:54:32.363   927  3010 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-26 22:54:32.363   927  3010 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:54:32.364   927   944 D Tethering: MasterInitialState.processMessage what=3
10-26 22:54:32.366  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:54:32.366  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:32.366  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:32.366  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:32.366  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:32.366  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:32.366  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:32.366  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:32.366  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 22:54:32.366  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.366  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:32.367   927  3008 D DhcpClient: doQuit
10-26 22:54:32.367   927  3008 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-26 22:54:32.367   927  5727 D DhcpClient: onQuitting
10-26 22:54:32.367  3973  3973 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-26 22:54:32.368  5720  5720 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-26 22:54:32.368  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.368  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:32.368  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:32.368  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:32.368  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:54:32.368  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:32.368  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:32.368  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:32.368  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:32.368  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.368  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:32.370  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.370  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:32.370  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:32.370  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:32.370  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:32.370  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:32.370  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:32.370  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:32.370  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:32.370  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.370  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:54:32.374  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:54:32.374  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:32.374  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:32.374  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:32.374  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:32.374  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:32.374  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:32.374  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:32.374  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:32.374  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.374  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:32.375  4110  4110 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-26 22:54:32.376  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.376  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:32.376  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:32.376  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:32.376  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:32.376  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:32.376  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:32.376  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:32.376  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:32.376  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:32.376  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:54:32.377  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:32.379  4110  4110 D SystemUpdateService: onCreate
,10-26 22:54:32.381  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-26 22:54:32.383  4110  4110 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-26 22:54:32.384  5720  5720 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-26 22:54:32.388  4110  5752 I SystemUpdateService: active receiver: enabled
,10-26 22:54:32.393  4110  4110 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-26 22:54:32.398  4110  5378 I iu.UploadsManager: num queued entries: 0
,10-26 22:54:32.399  4110  5378 I iu.UploadsManager: num updated entries: 0
,10-26 22:54:32.400  4110  5378 I iu.SyncManager: NEXT; no task
,10-26 22:54:32.402  4110  4110 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-26 22:54:32.403  4110  4110 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-26 22:54:32.405  5685  5685 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:54:32.410  5685  5685 D SprintDMHelper: simOperator: 
10-26 22:54:32.410  5685  5685 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 22:54:32.415  5720  5720 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-26 22:54:32.418  4110  5752 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-26 22:54:32.421   507   921 E Netd    : netlink response contains error (No such file or directory)
,10-26 22:54:32.422   927  3010 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-26 22:54:32.427  4110  5752 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-26 22:54:32.427  4110  5752 I SystemUpdateService: now status is 0 (complete)
10-26 22:54:32.427  4110  5752 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 22:54:32.427  4110  5752 I SystemUpdateService: file has been verified
10-26 22:54:32.427  4110  5752 I SystemUpdateService: OTA package size = 21989297
,10-26 22:54:32.442  5720  5720 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-26 22:54:32.442  4110  5752 I SystemUpdateService: showing system update notification
,10-26 22:54:32.449   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 22:54:32.450  4110  4110 D SystemUpdateService: onDestroy
,10-26 22:54:32.543   927  3008 D wifi    : In wifi stop Hal
,10-26 22:54:32.543   927  3008 D wifi    : halHandle = 0x7f90965900, mVM = 0x7facf0d140, mCls = 0x10194e
10-26 22:54:32.545   927  5719 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-26 22:54:32.545   927  5719 D WifiHAL : Got a signal to exit!!!
,10-26 22:54:32.545   927  5719 I WifiHAL : Exit wifi_event_loop
10-26 22:54:32.546  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:32.546  3984  4239 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 22:54:32.546   927  3008 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-26 22:54:32.547   927  3008 E WifiHAL : Event processing terminated
,10-26 22:54:32.547   927  3008 D wifi    : In wifi cleaned up handler
10-26 22:54:32.548   927  3008 I WifiHAL : Internal cleanup completed
10-26 22:54:32.548  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:32.549  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:32.547  4474  4474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 22:54:32.570   927  5719 D wifi    : set interface wlan0 flags (DOWN)
,10-26 22:54:32.570   927  3008 D WifiNative-HAL: HAL event thread stopped successfully
,10-26 22:54:32.775   927   944 D Tethering: InitialState.processMessage what=4
,10-26 22:54:32.783   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-26 22:54:33.164   927  3010 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-26 22:54:33.266   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-26 22:54:37.327   927   944 I ActivityManager: Start proc 5759:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-26 22:54:37.419  5759  5759 D AdapterServiceConfig: Adding HeadsetService
,10-26 22:54:37.419  5759  5759 D AdapterServiceConfig: Adding A2dpService
10-26 22:54:37.419  5759  5759 D AdapterServiceConfig: Adding HidService
10-26 22:54:37.420  5759  5759 D AdapterServiceConfig: Adding HealthService
10-26 22:54:37.420  5759  5759 D AdapterServiceConfig: Adding PanService
10-26 22:54:37.420  5759  5759 D AdapterServiceConfig: Adding GattService
10-26 22:54:37.420  5759  5759 D AdapterServiceConfig: Adding BluetoothMapService
,10-26 22:54:37.420  5759  5759 D AdapterServiceConfig: Adding SapService
,10-26 22:54:37.430  5759  5759 D BluetoothAdapterState: make() - Creating AdapterState
10-26 22:54:37.430   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@91c8607:true
,10-26 22:54:37.433  5759  5759 I bt_bluedroid: init
,10-26 22:54:37.433  5759  5771 I BluetoothAdapterState: Entering OffState
,10-26 22:54:37.435  5759  5772 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-26 22:54:37.435  5759  5772 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-26 22:54:37.435  5759  5772 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-26 22:54:37.435  5759  5772 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-26 22:54:37.436  5759  5759 I bt_bluedroid: get_profile_interface socket
,10-26 22:54:37.438  5759  5775 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 22:54:37.438  5759  5759 I bt_bluedroid: get_profile_interface sdp
10-26 22:54:37.439  5759  5775 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 22:54:37.442  5759  5770 I bt_bluedroid: config_hci_snoop_log
,10-26 22:54:37.443   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-26 22:54:37.447  5759  5771 D BluetoothAdapterState: Current state: OFF, message: 0
,10-26 22:54:37.447  5759  5771 D BluetoothAdapterProperties: Setting state to 14
10-26 22:54:37.447  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-26 22:54:37.449  5759  5771 D BluetoothBondStateMachine: make
,10-26 22:54:37.451  5759  5776 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-26 22:54:37.453  5759  5771 I BluetoothAdapterState: Entering PendingCommandState
,10-26 22:54:37.454  5759  5759 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-26 22:54:37.457  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
10-26 22:54:37.457  5759  5759 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 22:54:37.458  5759  5759 D BtGatt.GattService: Received start request. Starting profile...
10-26 22:54:37.458  5759  5759 D BtGatt.GattService: start()
10-26 22:54:37.458  5759  5759 I bt_bluedroid: get_profile_interface gatt
,10-26 22:54:37.459  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
,10-26 22:54:37.459  5759  5759 D BtGatt.AdvertiseManager: advertise manager created
,10-26 22:54:37.464  5759  5759 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:54:37.464  5759  5759 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:37.464  5759  5759 V BluetoothAdapterState: isBleTurningOn()=true
10-26 22:54:37.464  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:37.464  5759  5771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-26 22:54:37.465  5759  5771 I bt_bluedroid: bt_bluedroid
10-26 22:54:37.466  5759  5772 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-26 22:54:37.466  5759  5772 I bt_hci  : start_up
,10-26 22:54:37.471  5759  5772 I bt_vendor: alloc value 0xf42d5871
,10-26 22:54:37.471  5759  5772 I bt_vendor: init
10-26 22:54:37.471  5759  5772 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-26 22:54:37.471  5759  5772 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-26 22:54:37.580  5759  5772 D bt_hci  : start_up starting async portion
,10-26 22:54:37.581  5759  5779 I bt_hci  : event_finish_startup
10-26 22:54:37.581  5759  5779 I bt_hci_h4: hal_open
10-26 22:54:37.581  5759  5779 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-26 22:54:37.583  5759  5779 I bt_userial_vendor: device fd = 54 open
,10-26 22:54:37.580  5780  5780 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 22:54:37.596  5759  5779 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 22:54:37.598  5759  5779 D bt_hwcfg: Chipset BCM4358A3
,10-26 22:54:37.599  5759  5779 D bt_hwcfg: Target name = [BCM4358A3]
10-26 22:54:37.599  5759  5779 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-26 22:54:37.981  5759  5779 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-26 22:54:37.982  5759  5779 D bt_hwcfg: Settlement delay -- 100 ms
10-26 22:54:37.982  5759  5779 I bt_hwcfg: Setting fw settlement delay to 100 
,10-26 22:54:38.117  5759  5779 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 22:54:38.118  5759  5779 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
10-26 22:54:38.120  5759  5779 I bt_hwcfg: vendor lib fwcfg completed
10-26 22:54:38.120  5759  5779 I bt_vendor: firmware callback
10-26 22:54:38.120  5759  5779 I bt_hci  : firmware_config_callback
,10-26 22:54:38.130  5759  5782 I bt_btu  : btu_task pending for preload complete event
,10-26 22:54:38.130  5759  5782 I bt_btu_task: Bluetooth chip preload is complete
10-26 22:54:38.131  5759  5782 I bt_btu  : btu_task received preload complete event
,10-26 22:54:38.137  5759  5782 I         : BTE_InitTraceLevels -- TRC_HCI
,10-26 22:54:38.137  5759  5782 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-26 22:54:38.137  5759  5782 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-26 22:54:38.138  5759  5782 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-26 22:54:38.138  5759  5782 I         : BTE_InitTraceLevels -- TRC_AVRC
10-26 22:54:38.138  5759  5782 I         : BTE_InitTraceLevels -- TRC_A2D
10-26 22:54:38.138  5759  5782 I         : BTE_InitTraceLevels -- TRC_BNEP
10-26 22:54:38.138  5759  5782 I         : BTE_InitTraceLevels -- TRC_BTM
,10-26 22:54:38.138  5759  5782 I         : BTE_InitTraceLevels -- TRC_GAP
10-26 22:54:38.138  5759  5782 I         : BTE_InitTraceLevels -- TRC_PAN
10-26 22:54:38.139  5759  5782 I         : BTE_InitTraceLevels -- TRC_SDP
10-26 22:54:38.139  5759  5782 I         : BTE_InitTraceLevels -- TRC_GATT
10-26 22:54:38.139  5759  5782 I         : BTE_InitTraceLevels -- TRC_SMP
,10-26 22:54:38.139  5759  5782 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-26 22:54:38.139  5759  5782 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-26 22:54:38.221  5759  5782 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4253549
,10-26 22:54:38.221  5759  5782 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4253549 
,10-26 22:54:38.240  5759  5775 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
10-26 22:54:38.241  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 22:54:38.242  5759  5775 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 22:54:38.244  5759  5775 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 22:54:38.246  5759  5775 D BluetoothAdapterProperties: Scan Mode:20
10-26 22:54:38.247  5759  5775 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-26 22:54:38.247  5759  5775 D bt_hci  : do_postload posting postload work item
,10-26 22:54:38.247  5759  5779 I bt_hci  : event_postload
,10-26 22:54:38.247  5759  5779 I bt_vendor: sco_config_cb
10-26 22:54:38.247  5759  5779 I bt_hci  : sco_config_callback postload finished.
10-26 22:54:38.250  5759  5775 D bt_bte_conf: Device ID record 1 : primary
10-26 22:54:38.251  5759  5775 D bt_bte_conf:   vendorId            = 000f
10-26 22:54:38.251  5759  5775 D bt_bte_conf:   vendorIdSource      = 0001
10-26 22:54:38.251  5759  5775 D bt_bte_conf:   product             = 1200
10-26 22:54:38.251  5759  5775 D bt_bte_conf:   version             = 1436
10-26 22:54:38.251  5759  5775 D bt_bte_conf:   clientExecutableURL = 
10-26 22:54:38.251  5759  5775 D bt_bte_conf:   serviceDescription  = 
10-26 22:54:38.251  5759  5775 D bt_bte_conf:   documentationURL    = 
10-26 22:54:38.251  5759  5775 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-26 22:54:38.251  5759  5772 D bt_stack_manager: event_start_up_stack finished
10-26 22:54:38.252  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:38.252  5759  5771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-26 22:54:38.253  5759  5771 D BluetoothAdapterProperties: Setting state to 15
10-26 22:54:38.253  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-26 22:54:38.255  5759  5771 I BluetoothAdapterState: Entering BleOnState
10-26 22:54:38.257  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:38.260  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:38.260  5759  5771 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-26 22:54:38.261  5759  5771 D BluetoothAdapterProperties: Setting state to 11
10-26 22:54:38.261  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-26 22:54:38.261  5759  5779 I bt_vendor: low_power_mode_cb
,10-26 22:54:38.269  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:38.269  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
10-26 22:54:38.270  5759  5759 D HeadsetService: Received start request. Starting profile...
10-26 22:54:38.271  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:38.273  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:38.273  5759  5759 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-26 22:54:38.273  5759  5759 D HeadsetStateMachine: make
,10-26 22:54:38.279  5759  5771 I BluetoothAdapterState: Entering PendingCommandState
,10-26 22:54:38.284  5759  5759 D HeadsetStateMachine: max_hf_connections = 1
,10-26 22:54:38.284  5759  5759 I bt_bluedroid: get_profile_interface handsfree
10-26 22:54:38.284  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-26 22:54:38.284  5759  5775 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-26 22:54:38.287  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
,10-26 22:54:38.288  5759  5759 D A2dpService: Received start request. Starting profile...
,10-26 22:54:38.288  5759  5759 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-26 22:54:38.289  5759  5759 I bt_bluedroid: get_profile_interface avrcp
,10-26 22:54:38.294  5759  5759 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-26 22:54:38.294  5759  5759 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-26 22:54:38.294  5759  5759 D A2dpStateMachine: make
10-26 22:54:38.295  5759  5759 I bt_bluedroid: get_profile_interface a2dp
,10-26 22:54:38.295  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-26 22:54:38.297  5759  5791 D A2dpStateMachine: Enter Disconnected: -2
,10-26 22:54:38.297  5759  5759 I BluetoothHidServiceJni: classInitNative: succeeds
,10-26 22:54:38.298  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
,10-26 22:54:38.300  5759  5759 D HidService: Received start request. Starting profile...
,10-26 22:54:38.300  5759  5759 I bt_bluedroid: get_profile_interface hidhost
10-26 22:54:38.300  5652  5652 D BluetoothInputDevice: Proxy object connected
10-26 22:54:38.300  5759  5759 D HidService: setHidService(): set to: null
10-26 22:54:38.300  5759  5775 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf423456d
10-26 22:54:38.300  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-26 22:54:38.300  5652  5652 D HidProfile: Bluetooth service connected
,10-26 22:54:38.300  5759  5759 I BluetoothHealthServiceJni: classInitNative: succeeds
10-26 22:54:38.301  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
10-26 22:54:38.301  5759  5759 D HealthService: Received start request. Starting profile...
,10-26 22:54:38.303  5759  5759 I bt_bluedroid: get_profile_interface health
10-26 22:54:38.303  5759  5759 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-26 22:54:38.304  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
,10-26 22:54:38.305  5652  5652 D BluetoothPan: BluetoothPAN Proxy object connected
,10-26 22:54:38.305  5759  5759 D PanService: Received start request. Starting profile...
10-26 22:54:38.305  5759  5759 D BluetoothPanServiceJni: initializeNative(L110): pan
10-26 22:54:38.305  5759  5759 I bt_bluedroid: get_profile_interface pan
10-26 22:54:38.306  5652  5652 D PanProfile: Bluetooth service connected
10-26 22:54:38.306  5759  5775 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-26 22:54:38.309  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
,10-26 22:54:38.309  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 22:54:38.310  5759  5759 D BluetoothMapService: Received start request. Starting profile...
,10-26 22:54:38.310  5759  5759 D BluetoothMapService: start()
,10-26 22:54:38.313  5759  5759 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-26 22:54:38.314  5759  5759 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-26 22:54:38.314  5759  5759 D BluetoothMapAppObserver: createReceiver()
,10-26 22:54:38.315  5759  5759 D BluetoothMapAppObserver: initObservers()
,10-26 22:54:38.315  5759  5759 D BluetoothMapAppObserver: getEnabledAccountItems()
10-26 22:54:38.320  5759  5759 V SapService: SapBinder()
10-26 22:54:38.321  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
10-26 22:54:38.321  5652  5652 D BluetoothMap: Proxy object connected
10-26 22:54:38.322  5759  5759 D SapService: Received start request. Starting profile...
10-26 22:54:38.322  5759  5759 V SapService: start()
,10-26 22:54:38.324  5652  5652 D MapProfile: Bluetooth service connected
10-26 22:54:38.324  5652  5652 D BluetoothMap: getConnectedDevices()
10-26 22:54:38.324  5759  5759 V BluetoothAdapterState: isTurningOff()=false
10-26 22:54:38.324  5759  5759 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:38.324  5652  5652 D BluetoothMap: Bluetooth is Not enabled
10-26 22:54:38.324  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:38.324  5759  5789 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=1
10-26 22:54:38.324  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isTurningOff()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isTurningOff()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isTurningOff()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isTurningOn()=true
,10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isTurningOff()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:38.325  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:38.326  5759  5759 V BluetoothAdapterState: isTurningOff()=false
10-26 22:54:38.326  5759  5759 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:38.326  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:38.326  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:38.327  5759  5759 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:54:38.327  5759  5759 V BluetoothAdapterState: isTurningOn()=true
,10-26 22:54:38.327  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:38.327  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:38.327  5759  5771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-26 22:54:38.327  5759  5771 D BluetoothAdapterProperties: ScanMode =  20
10-26 22:54:38.327  5759  5771 D BluetoothAdapterProperties: State =  11
10-26 22:54:38.327  5759  5771 D BluetoothAdapterProperties: Setting state to 12
10-26 22:54:38.328  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-26 22:54:38.328  5759  5771 I BluetoothAdapterState: Entering OnState
10-26 22:54:38.328  3805  3826 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:54:38.329   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:54:38.329   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:54:38.329  3163  3175 D BluetoothPan: onBluetoothStateChange on: true
10-26 22:54:38.329  5759  5775 D BluetoothAdapterProperties: Scan Mode:21
10-26 22:54:38.330  5759  5775 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 22:54:38.330  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 22:54:38.330   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:54:38.330  3163  3163 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 22:54:38.330  3163  3163 D PanProfile: Bluetooth service connected
10-26 22:54:38.331  3163  5585 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-26 22:54:38.333  5652  5665 D BluetoothMap: onBluetoothStateChange: up=true
,10-26 22:54:38.333  3163  3163 D BluetoothA2dp: Proxy object connected
,10-26 22:54:38.334  3163  3175 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:54:38.335  3163  3174 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 22:54:38.335  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:38.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:38.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:38.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:38.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:54:38.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:38.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:38.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:38.336  5652  5663 D BluetoothPan: onBluetoothStateChange on: true
10-26 22:54:38.337  5652  5665 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 22:54:38.337  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:38.338  5652  5663 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 22:54:38.338  3163  5585 D BluetoothMap: onBluetoothStateChange: up=true
10-26 22:54:38.339  3163  3163 D BluetoothMap: Proxy object connected
10-26 22:54:38.339   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 22:54:38.339  3163  3163 D MapProfile: Bluetooth service connected
10-26 22:54:38.339  3163  3163 D BluetoothMap: getConnectedDevices()
10-26 22:54:38.340  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:38.340  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:38.340  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:38.340  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:38.340  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:54:38.340  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:38.340  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:38.340  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:38.340   927   927 D BluetoothA2dp: Proxy object connected
10-26 22:54:38.340  3163  3175 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 22:54:38.341  5759  5759 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 22:54:38.341  5759  5759 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-26 22:54:38.342  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:38.343   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-26 22:54:38.344  3163  3163 D BluetoothInputDevice: Proxy object connected
,10-26 22:54:38.344  3163  3163 D HidProfile: Bluetooth service connected
10-26 22:54:38.345  5759  5759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:54:38.345  5652  5652 D LocalBluetoothProfileManager: Adding local A2DP profile
10-26 22:54:38.345  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:38.345  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:38.345  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:38.345  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:38.345  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:54:38.345  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:38.345  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:38.345  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:38.347  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:54:38.347  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-26 22:54:38.348  5759  5759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:54:38.348  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:38.349  5759  5759 D ObexServerSockets: Succeed to create listening sockets 
10-26 22:54:38.349  5759  5759 D ObexServerSockets0: startAccept()
10-26 22:54:38.349  5759  5759 D ObexServerSockets0: prepareForNewConnect()
10-26 22:54:38.349  5652  5652 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-26 22:54:38.350  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:38.352  5759  5759 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-26 22:54:38.352  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:38.352  5759  5759 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-26 22:54:38.352  5759  5799 D ObexServerSockets0: Accepting socket connection...
10-26 22:54:38.352  5759  5759 D BluetoothMapService: onReceive
10-26 22:54:38.352  5759  5759 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 22:54:38.353  5759  5798 D ObexServerSockets0: Accepting socket connection...
10-26 22:54:38.353  5759  5759 D BluetoothMapService: STATE_ON
,10-26 22:54:38.354  5759  5800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:54:38.356  5759  5800 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-26 22:54:38.356  5759  5800 D BluetoothSdpJni: SDP Create record success - handle: 1
10-26 22:54:38.356  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 22:54:38.359  5652  5652 D BluetoothA2dp: Proxy object connected
,10-26 22:54:38.362  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 22:54:38.368  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,10-26 22:54:38.372  3163  3163 D BluetoothPbap: Proxy object connected
10-26 22:54:38.372  5652  5652 D BluetoothPbap: Proxy object connected
10-26 22:54:38.372  3163  3163 D PbapServerProfile: Bluetooth service connected
,10-26 22:54:38.372  5652  5652 D PbapServerProfile: Bluetooth service connected
,10-26 22:54:38.377  5759  5759 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-26 22:54:38.377  5759  5759 D ObexServerSockets0: prepareForNewConnect()
10-26 22:54:38.378  5759  5804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:54:38.391  5759  5808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:54:38.393  5759  5808 I BtOppRfcommListener: Accept thread started.
,10-26 22:54:38.430   927   927 D BluetoothHeadset: Proxy object connected
,10-26 22:54:38.430  3163  3400 D BluetoothHeadset: Proxy object connected
10-26 22:54:38.430  3163  3163 D HeadsetProfile: Bluetooth service connected
10-26 22:54:38.430   927   927 D BluetoothHeadset: Proxy object connected
10-26 22:54:38.430   927   927 D BluetoothHeadset: Proxy object connected
10-26 22:54:38.430  3805  3824 D BluetoothHeadset: Proxy object connected
10-26 22:54:38.431   927   944 D BluetoothHeadset: Proxy object connected
,10-26 22:54:38.435  3163  3174 D BluetoothHeadset: Proxy object connected
,10-26 22:54:38.436  3163  3163 D HeadsetProfile: Bluetooth service connected
,10-26 22:54:38.452  5652  5663 D BluetoothHeadset: Proxy object connected
,10-26 22:54:38.453  5652  5652 D HeadsetProfile: Bluetooth service connected
,10-26 22:54:38.778  3682  3878 I Keyboard.Facilitator.LanguageModelFlusher: run()
,10-26 22:54:38.778  3682  3878 I Keyboard.Facilitator: flushDynamicLanguageModels()
,10-26 22:54:38.803  3615  3615 I ConfigService: onCreate
,10-26 22:54:40.118   927  3010 D ConnectivityService: handlePromptUnvalidated 101
,10-26 22:54:42.305  5759  5771 D BluetoothAdapterState: Current state: ON, message: 23
,10-26 22:54:42.305  5759  5771 D BluetoothAdapterProperties: Setting state to 13
10-26 22:54:42.306  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-26 22:54:42.307  5759  5771 D BluetoothAdapterProperties: onBluetoothDisable()
,10-26 22:54:42.311  5759  5759 D BluetoothMapService: onReceive
10-26 22:54:42.312  5759  5759 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 22:54:42.312  5759  5759 D BluetoothMapService: STATE_TURNING_OFF
10-26 22:54:42.313  5759  5759 D BluetoothMapService: MAP Service closeService in
10-26 22:54:42.313  5759  5759 D BluetoothMapMasInstance0: MAP Service shutdown
10-26 22:54:42.313  5759  5759 D ObexServerSockets0: shutdown(block = true)
10-26 22:54:42.314  5759  5759 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-26 22:54:42.315  5759  5798 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-26 22:54:42.315  5759  5799 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-26 22:54:42.316  5759  5759 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 22:54:42.318  5759  5771 I BluetoothAdapterState: Entering PendingCommandState
10-26 22:54:42.319  5759  5784 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-26 22:54:42.321  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:42.321  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:42.321  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:42.321  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:42.321  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:42.321  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:42.321  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:42.321  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:42.321  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:42.323  5759  5759 I BtOppRfcommListener: stopping Accept Thread
,10-26 22:54:42.324  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:42.324  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:42.324  5759  5775 D BluetoothAdapterProperties: Scan Mode:20
10-26 22:54:42.325  5759  5771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-26 22:54:42.325  5759  5808 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-26 22:54:42.325  5759  5808 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-26 22:54:42.328  5759  5759 D HeadsetService: Received stop request...Stopping profile...
10-26 22:54:42.331  5652  5665 D BluetoothHeadset: Proxy object disconnected
10-26 22:54:42.332  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:42.332  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:42.332  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:42.332  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:42.332  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:42.332  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:42.332  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:42.332  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:42.332  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:42.332   927   927 D BluetoothHeadset: Proxy object disconnected
10-26 22:54:42.333  3163  3174 D BluetoothHeadset: Proxy object disconnected
,10-26 22:54:42.333   927   927 D BluetoothHeadset: Proxy object disconnected
,10-26 22:54:42.333  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:42.333   927   927 D BluetoothHeadset: Proxy object disconnected
10-26 22:54:42.333  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:42.334  3805  4017 D BluetoothHeadset: Proxy object disconnected
10-26 22:54:42.335  5759  5759 D A2dpService: Received stop request...Stopping profile...
10-26 22:54:42.336  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 22:54:42.336  3163  3163 D HeadsetProfile: Bluetooth service disconnected
10-26 22:54:42.337  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:42.337  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:42.337  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:42.337  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:42.337  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 22:54:42.337  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:42.337  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:42.337  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:42.336  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 22:54:42.338  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 22:54:42.338  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:42.339  5759  5791 D A2dpStateMachine: Exit Disconnected: -1
10-26 22:54:42.340  3163  3163 D BluetoothA2dp: Proxy object disconnected
10-26 22:54:42.340   927   927 D BluetoothA2dp: Proxy object disconnected
10-26 22:54:42.340  5759  5759 V BluetoothAdapterState: isTurningOff()=true
10-26 22:54:42.340  5759  5759 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:42.340  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:42.340  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:42.341  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:54:42.341  5759  5759 D HidService: Received stop request...Stopping profile...
10-26 22:54:42.341  5759  5759 D HidService: Stopping Bluetooth HidService
10-26 22:54:42.343  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:42.343  3163  3163 D BluetoothInputDevice: Proxy object disconnected
,10-26 22:54:42.343  3163  3163 D HidProfile: Bluetooth service disconnected
10-26 22:54:42.344  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:42.347  5652  5652 D HeadsetProfile: Bluetooth service disconnected
,10-26 22:54:42.347  5759  5759 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-26 22:54:42.347  5759  5759 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-26 22:54:42.347  5652  5652 D BluetoothA2dp: Proxy object disconnected
10-26 22:54:42.348  5652  5652 D BluetoothInputDevice: Proxy object disconnected
10-26 22:54:42.348  5652  5652 D HidProfile: Bluetooth service disconnected
10-26 22:54:42.348  5759  5759 D HealthService: Received stop request...Stopping profile...
10-26 22:54:42.348  5759  5782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 22:54:42.348  5759  5782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:54:42.348  5759  5782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:54:42.348  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-26 22:54:42.349  5759  5775 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-26 22:54:42.352  5759  5759 D PanService: Received stop request...Stopping profile...
,10-26 22:54:42.352  3163  3163 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 22:54:42.353  3163  3163 D PanProfile: Bluetooth service disconnected
10-26 22:54:42.353  5652  5652 D DockEventReceiver: finishStartingService: stopping service
10-26 22:54:42.353  5759  5759 D BluetoothMapService: Received stop request...Stopping profile...
10-26 22:54:42.353  5759  5759 D BluetoothMapService: stop()
10-26 22:54:42.354  5652  5652 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 22:54:42.354  5759  5759 D BluetoothMapAppObserver: deinitObservers()
10-26 22:54:42.354  5652  5652 D PanProfile: Bluetooth service disconnected
10-26 22:54:42.354  5759  5759 D BluetoothMapAppObserver: removeReceiver()
10-26 22:54:42.357  3163  3163 D BluetoothMap: Proxy object disconnected
10-26 22:54:42.357  3163  3163 D MapProfile: Bluetooth service disconnected
10-26 22:54:42.357  5759  5759 D SapService: Received stop request...Stopping profile...
10-26 22:54:42.357  5759  5759 V SapService: stop()
10-26 22:54:42.358  5652  5652 D BluetoothMap: Proxy object disconnected
10-26 22:54:42.358  5652  5652 D MapProfile: Bluetooth service disconnected
10-26 22:54:42.359  5759  5759 V BluetoothAdapterState: isTurningOff()=true
10-26 22:54:42.360  5759  5759 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:42.360  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:42.360  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:54:42.361  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,10-26 22:54:42.361  5759  5782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:54:42.361  5759  5759 V BluetoothAdapterState: isTurningOff()=true
10-26 22:54:42.361  5759  5759 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:42.361  5759  5782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:54:42.361  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:42.361  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:42.361  5759  5782 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 22:54:42.361  5759  5782 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 22:54:42.361  5759  5782 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 22:54:42.361  5759  5782 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 22:54:42.362  5759  5759 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-26 22:54:42.362  5759  5759 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-26 22:54:42.362  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-26 22:54:42.363  5759  5759 V BluetoothAdapterState: isTurningOff()=true
,10-26 22:54:42.363  5759  5759 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:42.363  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:42.363  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:42.363  5759  5759 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-26 22:54:42.363  5759  5775 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-26 22:54:42.364  5759  5759 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-26 22:54:42.364  5759  5759 V BluetoothAdapterState: isTurningOff()=true
10-26 22:54:42.364  5759  5759 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:42.364  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 22:54:42.364  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:42.364  5759  5759 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-26 22:54:42.365  5759  5759 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-26 22:54:42.365  5759  5759 D BluetoothMapService: MAP Service closeService in
10-26 22:54:42.366  5759  5759 V BluetoothAdapterState: isTurningOff()=true
10-26 22:54:42.366  5759  5759 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:42.366  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:42.366  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:54:42.366  5759  5759 D BluetoothMapService: cleanup()
10-26 22:54:42.366  5759  5759 D BluetoothMapService: MAP Service closeService in
10-26 22:54:42.367  5759  5759 V BluetoothAdapterState: isTurningOff()=true
10-26 22:54:42.367  5759  5759 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:42.367  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:42.367  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:42.367  5759  5771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-26 22:54:42.367  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 22:54:42.367  5759  5771 D BluetoothAdapterProperties: Setting state to 15
10-26 22:54:42.367  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-26 22:54:42.368  5759  5771 I BluetoothAdapterState: Entering BleOnState
10-26 22:54:42.369  3163  3163 D BluetoothPbap: Proxy object disconnected
10-26 22:54:42.369  3163  3163 D PbapServerProfile: Bluetooth service disconnected
,10-26 22:54:42.370  3805  3826 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 22:54:42.370   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:54:42.370   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:54:42.370  3163  3175 D BluetoothPan: onBluetoothStateChange on: false
10-26 22:54:42.370  5652  5652 D BluetoothPbap: Proxy object disconnected
,10-26 22:54:42.370  5652  5652 D PbapServerProfile: Bluetooth service disconnected
,10-26 22:54:42.372   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 22:54:42.372  3163  5585 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 22:54:42.372  5652  5665 D BluetoothMap: onBluetoothStateChange: up=false
10-26 22:54:42.374  3163  3400 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 22:54:42.374  5652  5663 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 22:54:42.375  5652  5665 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 22:54:42.375  3163  3174 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 22:54:42.376  5652  5663 D BluetoothPan: onBluetoothStateChange on: false
10-26 22:54:42.377  5652  5665 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 22:54:42.377  5652  5663 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 22:54:42.378  3163  3175 D BluetoothMap: onBluetoothStateChange: up=false
10-26 22:54:42.378   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 22:54:42.378  3163  5585 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 22:54:42.379  5759  5771 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-26 22:54:42.379  5759  5771 D BluetoothAdapterProperties: Setting state to 16
10-26 22:54:42.379  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-26 22:54:42.380  5759  5771 D BluetoothAdapterProperties: onBleDisable
10-26 22:54:42.380  5759  5771 I BluetoothAdapterState: Entering PendingCommandState
10-26 22:54:42.381  5759  5772 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-26 22:54:42.382  5759  5782 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-26 22:54:42.382  5759  5782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 22:54:42.382  5759  5775 D BluetoothAdapterProperties: Scan Mode:20
,10-26 22:54:42.383  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 22:54:42.383  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:42.385  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:42.386  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:42.388  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:42.389  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:42.391  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:42.391  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 22:54:42.393  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,10-26 22:54:42.592  5759  5775 I bt_hci  : shut_down
,10-26 22:54:42.603  5759  5779 D bt_hwcfg: hw_epilog_process
,10-26 22:54:42.603  5759  5779 I bt_vendor: low_power_mode_cb
,10-26 22:54:42.606  5759  5779 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-26 22:54:42.606  5759  5779 I bt_vendor: epilog_cb
10-26 22:54:42.606  5759  5779 I bt_hci  : epilog_finished_callback
,10-26 22:54:42.610  5759  5775 I bt_hci_h4: hal_close
,10-26 22:54:42.610  5759  5775 I bt_userial_vendor: device fd = 54 close
,10-26 22:54:42.728  5759  5772 D bt_stack_manager: event_shut_down_stack finished.
,10-26 22:54:42.730  5759  5771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-26 22:54:42.734  5759  5771 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-26 22:54:42.734  5759  5759 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 22:54:42.735  5759  5759 D BtGatt.GattService: Received stop request...Stopping profile...
10-26 22:54:42.736  5759  5759 D BtGatt.GattService: stop()
,10-26 22:54:42.736  5759  5759 D BtGatt.AdvertiseManager: advertise clients cleared
,10-26 22:54:42.740  5759  5759 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:54:42.741  5759  5759 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:42.741  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:42.741  5759  5759 V BluetoothAdapterState: isBleTurningOff()=true
,10-26 22:54:42.741  5759  5771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-26 22:54:42.742  5759  5771 D BluetoothAdapterProperties: Setting state to 10
10-26 22:54:42.742  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,10-26 22:54:42.745  5759  5771 I BluetoothAdapterState: Entering OffState
,10-26 22:54:42.745   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-26 22:54:42.758  5759  5759 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-26 22:54:42.759  5759  5759 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,10-26 22:54:42.759  5759  5759 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-26 22:54:42.761  5759  5772 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-26 22:54:42.767  5759  5759 I art     : System.exit called, status: 0
,10-26 22:54:42.767  5759  5759 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-26 22:54:42.797   927  3192 I ActivityManager: Process com.android.bluetooth (pid 5759) has died
,10-26 22:54:43.267   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:43.832  3615  3615 I ConfigService: onDestroy
,10-26 22:54:44.268   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:45.269   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:46.270   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:47.271   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:54:47.303  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:54:47.304  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:47.308  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:47.308  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26341d4 removed from the list
10-26 22:54:47.308  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:54:47.308  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:47.309  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:47.314  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:54:47.315  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4539e72 added. We now have 4 listener(s)
,10-26 22:54:47.315  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:54:47.317  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:47.317  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4539e72 removed from the list
10-26 22:54:47.318  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:54:47.318  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:47.318  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:54:47.320  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:54:47.321  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d62c3 added. We now have 4 listener(s)
10-26 22:54:47.321  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:54:48.272   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-26 22:54:51.103   927   947 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,10-26 22:54:51.110  3629  3629 W Binder_6: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32041]" dev="sockfs" ino=32041 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:54:51.110  3629  3629 W Binder_6: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32041]" dev="sockfs" ino=32041 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:54:51.114  3682  3682 I Keyboard.Facilitator: onFinishInput()
,10-26 22:54:51.126   927   947 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 22:54:51.126   927   947 I Adreno  : Build Date                       : 12/06/15
10-26 22:54:51.126   927   947 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 22:54:51.126   927   947 I Adreno  : Local Branch                     : mybranch17112971
10-26 22:54:51.126   927   947 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 22:54:51.126   927   947 I Adreno  : Remote Branch                    : NONE
10-26 22:54:51.126   927   947 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 22:54:51.167   382   403 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (186 us)
,10-26 22:54:51.869  5586  5586 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-26 22:54:51.869  5586  5586 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,10-26 22:54:51.909   927   947 I sensors : batch
,10-26 22:54:51.910   927   947 V KeyguardServiceDelegate: onScreenTurnedOff()
,10-26 22:54:51.912  5586  5586 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@77e396b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f9ca740, 16908290=android.view.AbsSavedState$1@f9ca740}, android:focusedViewId=100}]}]
,10-26 22:54:51.912  5586  5586 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
10-26 22:54:51.913  5586  5586 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-26 22:54:51.913  5586  5586 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,10-26 22:54:51.917   927  2775 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,10-26 22:54:51.919   927   947 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,10-26 22:54:51.919   927   947 I sensors : activate
,10-26 22:54:51.921   927   945 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,10-26 22:54:51.923   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fb5d83c00
,10-26 22:54:51.923   927  2775 I hubconnection: sensorhub said: 'activate 7 enable:0'
10-26 22:54:51.923   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,10-26 22:54:52.229   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,10-26 22:54:52.233   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,10-26 22:54:52.234   927  3119 D SurfaceControl: Excessive delay in setPowerMode(): 313ms
,10-26 22:54:52.244   927   947 I DreamManagerService: Entering dreamland.
,10-26 22:54:52.245   927   947 I PowerManagerService: Dozing...
,10-26 22:54:52.246   927   942 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,10-26 22:54:52.277  3186  3186 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[36106]" dev="sockfs" ino=36106 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:54:52.277  3186  3186 W Binder_3: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[36106]" dev="sockfs" ino=36106 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:54:52.279   927  3609 I sensors : batch
10-26 22:54:52.279   927  3609 I sensors : activate
,10-26 22:54:52.282   927  2775 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,10-26 22:54:52.284   927  2775 I hubconnection: sensorhub said: 'activate 21 enable:1'
,10-26 22:54:52.287   512  3032 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,10-26 22:54:52.312  3805  4763 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,10-26 22:54:52.312  3805  4763 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-26 22:54:52.312  3805  4763 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-26 22:54:52.312   525  1303 D         : oem-qmi: Connection accepted
10-26 22:54:52.313   525  1303 D         : oem-qmi: Waiting to accept connection
,10-26 22:54:52.315   927   927 I sensors : activate
,10-26 22:54:52.315   512  3031 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,10-26 22:54:52.318   927  2775 I hubconnection: sensorhub said: 'activate 31 enable:0'
,10-26 22:54:52.320  3805  4763 D         : oem_qmi_lib:output 0
10-26 22:54:52.320  3805  4763 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-26 22:54:52.329  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:52.347   927   944 I ActivityManager: Start proc 5823:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-26 22:54:52.359  3805  4763 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,10-26 22:54:52.359  3805  4763 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,10-26 22:54:52.359  3805  4763 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-26 22:54:52.360   525  1303 D         : oem-qmi: Connection accepted
10-26 22:54:52.360   525  1303 D         : oem-qmi: Waiting to accept connection
,10-26 22:54:52.366  3805  4763 D         : oem_qmi_lib:output 0
,10-26 22:54:52.366  3805  4763 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-26 22:54:52.408  5823  5823 D AdapterServiceConfig: Adding HeadsetService
,10-26 22:54:52.408  5823  5823 D AdapterServiceConfig: Adding A2dpService
10-26 22:54:52.409  5823  5823 D AdapterServiceConfig: Adding HidService
10-26 22:54:52.409  5823  5823 D AdapterServiceConfig: Adding HealthService
10-26 22:54:52.409  5823  5823 D AdapterServiceConfig: Adding PanService
10-26 22:54:52.409  5823  5823 D AdapterServiceConfig: Adding GattService
10-26 22:54:52.409  5823  5823 D AdapterServiceConfig: Adding BluetoothMapService
,10-26 22:54:52.409  5823  5823 D AdapterServiceConfig: Adding SapService
,10-26 22:54:52.419   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc88db6:true
,10-26 22:54:52.419  5823  5823 D BluetoothAdapterState: make() - Creating AdapterState
,10-26 22:54:52.422  5823  5823 I bt_bluedroid: init
,10-26 22:54:52.422  5823  5836 I BluetoothAdapterState: Entering OffState
,10-26 22:54:52.424  5823  5837 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-26 22:54:52.424  5823  5837 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-26 22:54:52.424  5823  5837 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-26 22:54:52.424  5823  5837 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-26 22:54:52.425  5823  5823 I bt_bluedroid: get_profile_interface socket
,10-26 22:54:52.426  5823  5840 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 22:54:52.427  5823  5823 I bt_bluedroid: get_profile_interface sdp
,10-26 22:54:52.428  5823  5840 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 22:54:52.431  5823  5834 I bt_bluedroid: config_hci_snoop_log
,10-26 22:54:52.432   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-26 22:54:52.436  5823  5836 D BluetoothAdapterState: Current state: OFF, message: 0
10-26 22:54:52.436  5823  5836 D BluetoothAdapterProperties: Setting state to 14
10-26 22:54:52.436  5823  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-26 22:54:52.437  5823  5836 D BluetoothBondStateMachine: make
,10-26 22:54:52.439  5823  5841 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-26 22:54:52.441  5823  5836 I BluetoothAdapterState: Entering PendingCommandState
,10-26 22:54:52.442  5823  5823 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-26 22:54:52.444  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
10-26 22:54:52.445  5823  5823 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-26 22:54:52.445  5823  5823 D BtGatt.GattService: Received start request. Starting profile...
,10-26 22:54:52.445  5823  5823 D BtGatt.GattService: start()
10-26 22:54:52.446  5823  5823 I bt_bluedroid: get_profile_interface gatt
10-26 22:54:52.447  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
10-26 22:54:52.447  5823  5823 D BtGatt.AdvertiseManager: advertise manager created
,10-26 22:54:52.451  5823  5823 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:54:52.451  5823  5823 V BluetoothAdapterState: isTurningOn()=false
10-26 22:54:52.451  5823  5823 V BluetoothAdapterState: isBleTurningOn()=true
10-26 22:54:52.451  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:52.451  5823  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-26 22:54:52.452  5823  5836 I bt_bluedroid: bt_bluedroid
10-26 22:54:52.453  5823  5837 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-26 22:54:52.453  5823  5837 I bt_hci  : start_up
,10-26 22:54:52.458  5823  5837 I bt_vendor: alloc value 0xf42d5871
,10-26 22:54:52.458  5823  5837 I bt_vendor: init
10-26 22:54:52.458  5823  5837 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-26 22:54:52.458  5823  5837 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-26 22:54:52.568  5823  5837 D bt_hci  : start_up starting async portion
,10-26 22:54:52.569  5823  5844 I bt_hci  : event_finish_startup
,10-26 22:54:52.569  5823  5844 I bt_hci_h4: hal_open
,10-26 22:54:52.569  5823  5844 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-26 22:54:52.571  5823  5844 I bt_userial_vendor: device fd = 54 open
10-26 22:54:52.567  5845  5845 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 22:54:52.586  5823  5844 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 22:54:52.589  5823  5844 D bt_hwcfg: Chipset BCM4358A3
,10-26 22:54:52.589  5823  5844 D bt_hwcfg: Target name = [BCM4358A3]
10-26 22:54:52.589  5823  5844 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-26 22:54:52.973  5823  5844 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-26 22:54:52.974  5823  5844 D bt_hwcfg: Settlement delay -- 100 ms
10-26 22:54:52.974  5823  5844 I bt_hwcfg: Setting fw settlement delay to 100 
,10-26 22:54:53.108  5823  5844 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 22:54:53.108  5823  5844 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
10-26 22:54:53.110  5823  5844 I bt_hwcfg: vendor lib fwcfg completed
10-26 22:54:53.110  5823  5844 I bt_vendor: firmware callback
10-26 22:54:53.110  5823  5844 I bt_hci  : firmware_config_callback
,10-26 22:54:53.119  5823  5847 I bt_btu  : btu_task pending for preload complete event
,10-26 22:54:53.119  5823  5847 I bt_btu_task: Bluetooth chip preload is complete
,10-26 22:54:53.119  5823  5847 I bt_btu  : btu_task received preload complete event
,10-26 22:54:53.126  5823  5847 I         : BTE_InitTraceLevels -- TRC_HCI
,10-26 22:54:53.126  5823  5847 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-26 22:54:53.126  5823  5847 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-26 22:54:53.126  5823  5847 I         : BTE_InitTraceLevels -- TRC_AVDT
10-26 22:54:53.126  5823  5847 I         : BTE_InitTraceLevels -- TRC_AVRC
10-26 22:54:53.126  5823  5847 I         : BTE_InitTraceLevels -- TRC_A2D
,10-26 22:54:53.127  5823  5847 I         : BTE_InitTraceLevels -- TRC_BNEP
10-26 22:54:53.127  5823  5847 I         : BTE_InitTraceLevels -- TRC_BTM
,10-26 22:54:53.127  5823  5847 I         : BTE_InitTraceLevels -- TRC_GAP
10-26 22:54:53.127  5823  5847 I         : BTE_InitTraceLevels -- TRC_PAN
,10-26 22:54:53.127  5823  5847 I         : BTE_InitTraceLevels -- TRC_SDP
10-26 22:54:53.127  5823  5847 I         : BTE_InitTraceLevels -- TRC_GATT
10-26 22:54:53.127  5823  5847 I         : BTE_InitTraceLevels -- TRC_SMP
10-26 22:54:53.127  5823  5847 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-26 22:54:53.128  5823  5847 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-26 22:54:53.211  5823  5847 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4253549
,10-26 22:54:53.212  5823  5847 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4253549 
,10-26 22:54:53.234  5823  5840 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-26 22:54:53.236  5823  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 22:54:53.236  5823  5840 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
10-26 22:54:53.238  5823  5840 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 22:54:53.241  5823  5840 D BluetoothAdapterProperties: Scan Mode:20
,10-26 22:54:53.242  5823  5840 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 22:54:53.242  5823  5840 D bt_hci  : do_postload posting postload work item
10-26 22:54:53.242  5823  5844 I bt_hci  : event_postload
,10-26 22:54:53.242  5823  5844 I bt_vendor: sco_config_cb
10-26 22:54:53.243  5823  5844 I bt_hci  : sco_config_callback postload finished.
,10-26 22:54:53.246  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:53.249  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:53.250  5823  5844 I bt_vendor: low_power_mode_cb
10-26 22:54:53.252  5823  5840 D bt_bte_conf: Device ID record 1 : primary
,10-26 22:54:53.252  5823  5840 D bt_bte_conf:   vendorId            = 000f
,10-26 22:54:53.252  5823  5840 D bt_bte_conf:   vendorIdSource      = 0001
10-26 22:54:53.252  5823  5840 D bt_bte_conf:   product             = 1200
10-26 22:54:53.252  5823  5840 D bt_bte_conf:   version             = 1436
10-26 22:54:53.252  5823  5840 D bt_bte_conf:   clientExecutableURL = 
10-26 22:54:53.252  5823  5840 D bt_bte_conf:   serviceDescription  = 
10-26 22:54:53.252  5823  5840 D bt_bte_conf:   documentationURL    = 
10-26 22:54:53.252  5823  5840 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-26 22:54:53.252  5823  5837 D bt_stack_manager: event_start_up_stack finished
10-26 22:54:53.253  5823  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-26 22:54:53.253  5823  5836 D BluetoothAdapterProperties: Setting state to 15
10-26 22:54:53.254  5823  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-26 22:54:53.255  5823  5836 I BluetoothAdapterState: Entering BleOnState
,10-26 22:54:53.260  5823  5836 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-26 22:54:53.260  5823  5836 D BluetoothAdapterProperties: Setting state to 11
10-26 22:54:53.260  5823  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-26 22:54:53.264  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
,10-26 22:54:53.265  5823  5823 D HeadsetService: Received start request. Starting profile...
10-26 22:54:53.267  5823  5823 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-26 22:54:53.267  5823  5823 D HeadsetStateMachine: make
10-26 22:54:53.268  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:53.273  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:54:53.276  5823  5823 D HeadsetStateMachine: max_hf_connections = 1
10-26 22:54:53.276  5823  5823 I bt_bluedroid: get_profile_interface handsfree
,10-26 22:54:53.276  5823  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-26 22:54:53.276  5823  5840 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
10-26 22:54:53.279  5823  5836 I BluetoothAdapterState: Entering PendingCommandState
10-26 22:54:53.280  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
10-26 22:54:53.280  5823  5823 D A2dpService: Received start request. Starting profile...
,10-26 22:54:53.281  5823  5823 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-26 22:54:53.281  5823  5823 I bt_bluedroid: get_profile_interface avrcp
,10-26 22:54:53.286  5823  5823 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-26 22:54:53.286  5823  5823 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-26 22:54:53.286  5823  5823 D A2dpStateMachine: make
10-26 22:54:53.287  5823  5823 I bt_bluedroid: get_profile_interface a2dp
,10-26 22:54:53.288  5823  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-26 22:54:53.292  5823  5855 D A2dpStateMachine: Enter Disconnected: -2
,10-26 22:54:53.292  5823  5823 I BluetoothHidServiceJni: classInitNative: succeeds
10-26 22:54:53.293  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
10-26 22:54:53.293  5823  5823 D HidService: Received start request. Starting profile...
10-26 22:54:53.293  5823  5823 I bt_bluedroid: get_profile_interface hidhost
10-26 22:54:53.293  5823  5823 D HidService: setHidService(): set to: null
10-26 22:54:53.293  5823  5840 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf423456d
10-26 22:54:53.293  5823  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-26 22:54:53.296  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 22:54:53.296  5823  5823 I BluetoothHealthServiceJni: classInitNative: succeeds
10-26 22:54:53.297  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
10-26 22:54:53.297  5823  5823 D HealthService: Received start request. Starting profile...
,10-26 22:54:53.298  5823  5823 I bt_bluedroid: get_profile_interface health
,10-26 22:54:53.299  5823  5823 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-26 22:54:53.299  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
,10-26 22:54:53.300  5823  5823 D PanService: Received start request. Starting profile...
10-26 22:54:53.300  5823  5823 D BluetoothPanServiceJni: initializeNative(L110): pan
10-26 22:54:53.300  5823  5823 I bt_bluedroid: get_profile_interface pan
10-26 22:54:53.301  5823  5840 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-26 22:54:53.303  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
,10-26 22:54:53.303  5823  5823 D BluetoothMapService: Received start request. Starting profile...
10-26 22:54:53.304  5823  5823 D BluetoothMapService: start()
,10-26 22:54:53.306  5823  5823 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-26 22:54:53.307  5823  5823 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-26 22:54:53.307  5823  5823 D BluetoothMapAppObserver: createReceiver()
10-26 22:54:53.308  5823  5823 D BluetoothMapAppObserver: initObservers()
10-26 22:54:53.308  5823  5823 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-26 22:54:53.313  5823  5823 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:54:53.313  5823  5823 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:53.313  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:53.313  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:53.313  5823  5853 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=1
10-26 22:54:53.314  5823  5823 V SapService: SapBinder()
,10-26 22:54:53.314  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
,10-26 22:54:53.315  5823  5823 D SapService: Received start request. Starting profile...
10-26 22:54:53.315  5823  5823 V SapService: start()
,10-26 22:54:53.316  5823  5823 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:54:53.316  5823  5823 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:53.316  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 22:54:53.316  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:53.316  5823  5823 V BluetoothAdapterState: isTurningOff()=false
10-26 22:54:53.316  5823  5823 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:53.316  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:53.316  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:53.317  5823  5823 V BluetoothAdapterState: isTurningOff()=false
10-26 22:54:53.317  5823  5823 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:53.317  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:53.317  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:53.317  5823  5823 V BluetoothAdapterState: isTurningOff()=false
10-26 22:54:53.317  5823  5823 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:53.318  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:53.318  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:53.318  5823  5823 V BluetoothAdapterState: isTurningOff()=false
10-26 22:54:53.318  5823  5823 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:53.319  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:53.319  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 22:54:53.320  5823  5823 V BluetoothAdapterState: isTurningOff()=false
,10-26 22:54:53.320  5823  5823 V BluetoothAdapterState: isTurningOn()=true
10-26 22:54:53.320  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
10-26 22:54:53.320  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
10-26 22:54:53.320  5823  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-26 22:54:53.320  5823  5836 D BluetoothAdapterProperties: ScanMode =  20
10-26 22:54:53.320  5823  5836 D BluetoothAdapterProperties: State =  11
10-26 22:54:53.321  5823  5840 D BluetoothAdapterProperties: Scan Mode:21
10-26 22:54:53.321  5823  5836 D BluetoothAdapterProperties: Setting state to 12
,10-26 22:54:53.321  5823  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-26 22:54:53.321  5823  5840 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 22:54:53.321  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-26 22:54:53.322  3805  3826 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 22:54:53.323  5823  5836 I BluetoothAdapterState: Entering OnState
10-26 22:54:53.323   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:54:53.323   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:54:53.323  3163  3174 D BluetoothPan: onBluetoothStateChange on: true
10-26 22:54:53.325   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:54:53.325  3163  3400 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 22:54:53.326  3163  3163 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 22:54:53.326  3163  3163 D PanProfile: Bluetooth service connected
,10-26 22:54:53.327  5652  5663 D BluetoothMap: onBluetoothStateChange: up=true
10-26 22:54:53.327  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:53.327  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:53.327  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:53.327  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:53.327  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:54:53.327  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:53.327  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:53.327  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 22:54:53.328  3163  3163 D BluetoothA2dp: Proxy object connected
,10-26 22:54:53.330  3163  5585 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 22:54:53.330  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:54:53.331  5652  5663 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 22:54:53.333  5652  5665 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 22:54:53.333  5823  5823 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 22:54:53.333  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:53.333  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:53.333  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:53.333  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:53.333  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:54:53.333  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:53.333  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:53.333  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:54:53.333  3163  3175 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 22:54:53.333  5823  5823 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-26 22:54:53.334  5823  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:54:53.335  5652  5663 D BluetoothPan: onBluetoothStateChange on: true
,10-26 22:54:53.335  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:54:53.336  5823  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:54:53.336  5652  5665 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 22:54:53.337  5823  5823 D ObexServerSockets: Succeed to create listening sockets 
10-26 22:54:53.337  5823  5823 D ObexServerSockets0: startAccept()
10-26 22:54:53.337  5823  5823 D ObexServerSockets0: prepareForNewConnect()
10-26 22:54:53.337  5652  5663 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 22:54:53.339  3163  3400 D BluetoothMap: onBluetoothStateChange: up=true
10-26 22:54:53.339  5823  5823 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-26 22:54:53.339  5823  5823 D BluetoothSdpJni: SDP Create record success - handle: 0
10-26 22:54:53.340  5823  5862 D ObexServerSockets0: Accepting socket connection...
10-26 22:54:53.340  5652  5652 D BluetoothMap: Proxy object connected
,10-26 22:54:53.340  5823  5863 D ObexServerSockets0: Accepting socket connection...
,10-26 22:54:53.341   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 22:54:53.341  3163  3163 D BluetoothMap: Proxy object connected
10-26 22:54:53.341  3163  3163 D MapProfile: Bluetooth service connected
10-26 22:54:53.341  3163  3163 D BluetoothMap: getConnectedDevices()
10-26 22:54:53.341   927   927 D BluetoothA2dp: Proxy object connected
,10-26 22:54:53.341  3163  3175 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 22:54:53.340  5652  5652 D MapProfile: Bluetooth service connected
10-26 22:54:53.342  5652  5652 D BluetoothMap: getConnectedDevices()
10-26 22:54:53.344  3163  3163 D BluetoothInputDevice: Proxy object connected
10-26 22:54:53.344  3163  3163 D HidProfile: Bluetooth service connected
,10-26 22:54:53.345  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-26 22:54:53.345  5823  5823 D BluetoothMapService: onReceive
,10-26 22:54:53.345  5823  5823 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 22:54:53.345  5823  5823 D BluetoothMapService: STATE_ON
10-26 22:54:53.345   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-26 22:54:53.346  5652  5652 D BluetoothA2dp: Proxy object connected
10-26 22:54:53.346  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:53.347  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:54:53.348  5823  5865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 22:54:53.349  5652  5652 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 22:54:53.349  5652  5652 D PanProfile: Bluetooth service connected
10-26 22:54:53.349  5652  5652 D BluetoothInputDevice: Proxy object connected
,10-26 22:54:53.349  5652  5652 D HidProfile: Bluetooth service connected
10-26 22:54:53.350  5823  5865 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-26 22:54:53.350  5823  5865 D BluetoothSdpJni: SDP Create record success - handle: 1
10-26 22:54:53.354  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 22:54:53.360  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 22:54:53.368  5652  5652 D DockEventReceiver: finishStartingService: stopping service
10-26 22:54:53.369  5652  5652 D BluetoothPbap: Proxy object connected
10-26 22:54:53.369  5652  5652 D PbapServerProfile: Bluetooth service connected
,10-26 22:54:53.372  5823  5823 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-26 22:54:53.372  5823  5823 D ObexServerSockets0: prepareForNewConnect()
10-26 22:54:53.373  3163  3163 D BluetoothPbap: Proxy object connected
10-26 22:54:53.373  3163  3163 D PbapServerProfile: Bluetooth service connected
,10-26 22:54:53.374  5823  5869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:54:53.388  5823  5873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 22:54:53.389  5823  5873 I BtOppRfcommListener: Accept thread started.
,10-26 22:54:53.424  5652  5663 D BluetoothHeadset: Proxy object connected
,10-26 22:54:53.425   927   944 D BluetoothHeadset: Proxy object connected
10-26 22:54:53.425   927   927 D BluetoothHeadset: Proxy object connected
10-26 22:54:53.425  3163  3174 D BluetoothHeadset: Proxy object connected
10-26 22:54:53.425  3163  3163 D HeadsetProfile: Bluetooth service connected
10-26 22:54:53.425   927   927 D BluetoothHeadset: Proxy object connected
10-26 22:54:53.425   927   927 D BluetoothHeadset: Proxy object connected
10-26 22:54:53.426  3805  3824 D BluetoothHeadset: Proxy object connected
10-26 22:54:53.428  5652  5652 D HeadsetProfile: Bluetooth service connected
,10-26 22:54:53.431  3163  5585 D BluetoothHeadset: Proxy object connected
10-26 22:54:53.431  3163  3163 D HeadsetProfile: Bluetooth service connected
,10-26 22:54:53.433  5652  5665 D BluetoothHeadset: Proxy object connected
,10-26 22:54:53.433  5652  5652 D HeadsetProfile: Bluetooth service connected
,10-26 22:54:55.673  3984  4447 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,10-26 22:54:57.344  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:54:57.344  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:54:57.344  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:54:57.344  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 22:54:57.344  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:54:57.344  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:54:57.344  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:54:57.344  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 22:54:57.349  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:54:57.350  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:54:57.350  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d62c3 removed from the list
10-26 22:54:57.351  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 22:54:57.351  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:54:57.351  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:54:57.353  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:54:57.353  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c28e679 added. We now have 4 listener(s)
10-26 22:54:57.353  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:54:57.357   927  4042 D WifiService: setWifiEnabled: false pid=5586, uid=10077
,10-26 22:54:57.357   927  4042 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:55:02.366  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:55:02.367   927  3186 D WifiService: setWifiEnabled: true pid=5586, uid=10077
10-26 22:55:02.367   927  3186 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 22:55:02.374   507   921 D SoftapController: Softap fwReload - Ok
,10-26 22:55:02.380   507   921 D CommandListener: Setting iface cfg
10-26 22:55:02.380   507   921 D CommandListener: Trying to bring down wlan0
,10-26 22:55:02.382   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-26 22:55:02.386   927  3008 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 22:55:03.048   927  3008 D wifi    : set interface wlan0 flags (UP)
,10-26 22:55:03.050   927  3008 I WifiHAL : Initializing wifi
10-26 22:55:03.050   927  3008 I WifiHAL : Creating socket
10-26 22:55:03.056   927  3008 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-26 22:55:03.056   927  3008 D wifi    : Did set static halHandle = 0x7f90965900
10-26 22:55:03.056   927  3008 D wifi    : halHandle = 0x7f90965900, mVM = 0x7facf0d140, mCls = 0x15ca
,10-26 22:55:03.056   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-26 22:55:03.056   927  3008 D wifi    : array field set
,10-26 22:55:03.057   927  3008 I WifiNative-HAL: interface[0] = wlan0
,10-26 22:55:03.059   927  5878 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547886618880
10-26 22:55:03.059   927  5878 D wifi    : waitForHalEvents called, vm = 0x7facf0d140, obj = 0x15ca, env = 0x7f9097d480
,10-26 22:55:03.118  5879  5879 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-26 22:55:03.161   927  3008 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-26 22:55:03.171  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:55:03.174  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 22:55:03.190  5879  5879 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 22:55:03.240  5879  5879 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 22:55:03.241  5879  5879 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-26 22:55:03.262   927  3008 D WifiConfigStore: Loading config and enabling all networks 
10-26 22:55:03.265  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:55:03.265  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:55:03.265  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:55:03.265  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:55:03.265  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:55:03.265  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:55:03.265  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:55:03.265  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:55:03.268  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 22:55:03.272   535   535 I ServiceManager: Waiting for service AtCmdFwd...
10-26 22:55:03.273  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:55:03.273  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:55:03.273  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:55:03.273  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:55:03.273  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:55:03.273  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 22:55:03.273  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 22:55:03.273  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 22:55:03.274  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 22:55:03.287   927  3008 D WifiConfigStore: loaded 0 passpoint configs
10-26 22:55:03.287   927  3008 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
10-26 22:55:03.288   927  3008 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-26 22:55:03.289   927  3008 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-26 22:55:03.289   927  3008 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-26 22:55:03.290   927  3008 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,10-26 22:55:03.291   927  3008 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-26 22:55:03.291   927  3008 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-26 22:55:03.291   927  3008 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
10-26 22:55:03.291   927  3008 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-26 22:55:03.291   927  3008 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-26 22:55:03.291   927  3008 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-26 22:55:03.291   927  3008 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-26 22:55:03.295   927  3008 D WifiNative-HAL: Setting external_sim to 1
,10-26 22:55:03.295   927  3008 D wifi    : setting dfs flag to true, 0x7f91ebe660
10-26 22:55:03.296   927  3008 D WifiStateMachine: Setting OUI to DA-A1-19
10-26 22:55:03.296   927  3008 D wifi    : setting scan oui 0x7f91ebe660
,10-26 22:55:03.296   927  3008 D WifiHAL : Sending mac address OUI
10-26 22:55:03.297  4474  4474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 22:55:03.301   927  3008 E native  : do suspend true
,10-26 22:55:03.309   927  3008 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-26 22:55:03.309   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-26 22:55:03.309   927   927 D RttService: SCAN_AVAILABLE : 3
,10-26 22:55:03.310   927  3116 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-26 22:55:03.310   507   921 D CommandListener: Setting iface cfg
,10-26 22:55:03.322   927  3007 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
10-26 22:55:03.322   927  3007 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-26 22:55:03.330   927  3007 D WifiNative-HAL: p2pGetDeviceAddress
,10-26 22:55:03.331   927  3007 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-26 22:55:03.335   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163797 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,10-26 22:55:04.274   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:55:05.275   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:55:06.276   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:55:06.466  5879  5879 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-26 22:55:06.496   927  3008 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-26 22:55:06.506   927  3008 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,10-26 22:55:06.507   927  3008 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:55:06.521   927  3008 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-26 22:55:06.572   927  3008 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-26 22:55:06.902  5879  5879 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-26 22:55:06.933  5879  5879 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-26 22:55:06.934  5879  5879 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-26 22:55:06.944   927  3008 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 22:55:06.944   927  3008 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-26 22:55:06.944   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-26 22:55:06.961   927  3008 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 22:55:06.973   507   921 D CommandListener: Setting iface cfg
,10-26 22:55:06.980   927  3008 D WifiStateMachine: Start Dhcp Watchdog 3
,10-26 22:55:06.984   927  3008 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-26 22:55:06.997   927  5884 D DhcpClient: Receive thread started
,10-26 22:55:07.081   927  3008 E native  : do suspend false
,10-26 22:55:07.099   927  5883 D DhcpClient: Broadcasting DHCPDISCOVER
,10-26 22:55:07.112   927  5884 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,10-26 22:55:07.112   927  5883 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,10-26 22:55:07.114   927  5883 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-26 22:55:07.129   927  5884 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-26 22:55:07.130   927  5883 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-26 22:55:07.133   507   921 D CommandListener: Setting iface cfg
,10-26 22:55:07.138   927  3008 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-26 22:55:07.142   927  3008 E native  : do suspend true
10-26 22:55:07.143   927  5883 D DhcpClient: Scheduling renewal in 86399s
,10-26 22:55:07.162   927  3008 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-26 22:55:07.166   927  3008 D WifiConfigStore: No blacklist allowed without epno enabled
10-26 22:55:07.167   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-26 22:55:07.173   927  3008 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
10-26 22:55:07.173   927  3010 D ConnectivityService: Adding iface wlan0 to network 102
,10-26 22:55:07.231   927  3010 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-26 22:55:07.231   927  3010 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-26 22:55:07.234   927  3010 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-26 22:55:07.237   927  3010 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-26 22:55:07.239   927  3010 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-26 22:55:07.249   927  3010 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-26 22:55:07.254   927  3010 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-26 22:55:07.254   927  3010 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-26 22:55:07.254   927  3010 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-26 22:55:07.254   927  3008 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,10-26 22:55:07.254   927  3010 D ConnectivityService:    accepting network in place of null
10-26 22:55:07.254   927  3008 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 22:55:07.255   927  3010 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 22:55:07.277   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:55:07.287   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:55:07.299   927  5882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167760, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-26 22:55:07.315   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 22:55:07.318   927  3010 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-26 22:55:07.318   927  3010 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:55:07.318  3771  3897 W QCNEJ   : |CORE| network available: 102
10-26 22:55:07.319   927  3010 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-26 22:55:07.321   927   944 D Tethering: MasterInitialState.processMessage what=3
10-26 22:55:07.323  3771  3897 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-26 22:55:07.324  3771  3897 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-26 22:55:07.325  3771  3897 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-26 22:55:07.330  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:55:07.330  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:55:07.330  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:55:07.330  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:55:07.330  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:55:07.330  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.330  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:55:07.330  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:55:07.332  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.335  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:55:07.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:55:07.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:55:07.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:55:07.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:55:07.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:55:07.335  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:55:07.337  3973  3973 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-26 22:55:07.337  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.339  4110  4110 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-26 22:55:07.342  4110  4110 D SystemUpdateService: onCreate
,10-26 22:55:07.346  4110  4110 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 22:55:07.355  4110  4110 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-26 22:55:07.361  4110  5893 I SystemUpdateService: active receiver: enabled
,10-26 22:55:07.362  4110  5378 I iu.UploadsManager: num queued entries: 0
,10-26 22:55:07.362  4110  5378 I iu.UploadsManager: num updated entries: 0
10-26 22:55:07.363  4110  5378 I iu.SyncManager: NEXT; no task
,10-26 22:55:07.367  4110  4110 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-26 22:55:07.368  4110  4110 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-26 22:55:07.371   927  5881 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-26 22:55:07.371  5685  5685 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 22:55:07.375  5685  5685 D SprintDMHelper: simOperator: 
,10-26 22:55:07.375  5685  5685 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 22:55:07.380  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 22:55:07.380  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:55:07.380  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:55:07.380  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:55:07.380  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:55:07.380  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.380  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:55:07.380  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:55:07.382  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.382  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 22:55:07.383  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c28e679 removed from the list
10-26 22:55:07.383  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:55:07.383  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.383  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.386  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-26 22:55:07.386  4110  5893 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-26 22:55:07.386  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-26 22:55:07.388  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@77e396b Bundle[{}]
10-26 22:55:07.388  5586  5633 I io.jxcore.node.LifeCycleMonitor: start: OK
10-26 22:55:07.389  5586  5633 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-26 22:55:07.389  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-26 22:55:07.390  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-26 22:55:07.390  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-26 22:55:07.391  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-26 22:55:07.397  5586  5633 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 164)
,10-26 22:55:07.398  5586  5633 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-26 22:55:07.398  5586  5633 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,10-26 22:55:07.399  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:55:07.400  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e392fbe added. We now have 3 listener(s)
,10-26 22:55:07.401  4110  5893 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-26 22:55:07.401  4110  5893 I SystemUpdateService: now status is 0 (complete)
10-26 22:55:07.401  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:55:07.401  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:55:07.402  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 22:55:07.402  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:55:07.402  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d9681f added. We now have 4 listener(s)
10-26 22:55:07.402  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:55:07.402  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 22:55:07.404  4110  5893 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,10-26 22:55:07.404  4110  5893 I SystemUpdateService: file has been verified
10-26 22:55:07.404  4110  5893 I SystemUpdateService: OTA package size = 21989297
10-26 22:55:07.405  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 22:55:07.410  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:55:07.410  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:55:07.410  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:55:07.410  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:55:07.410  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:55:07.410  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.410  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:55:07.410  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:55:07.412  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:55:07.412  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:55:07.412  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:55:07.413  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4487135 added. We now have 4 listener(s)
10-26 22:55:07.414  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:55:07.414  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-26 22:55:07.414  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:55:07.414  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:55:07.414  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95489ca added. We now have 5 listener(s)
10-26 22:55:07.414  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 22:55:07.414  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:55:07.414  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:55:07.414  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:55:07.414  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:55:07.414  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.414  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-26 22:55:07.414  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:55:07.414  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:55:07.415  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:55:07.415  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e392fbe removed from the list
10-26 22:55:07.415  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.415  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d9681f removed from the list
,10-26 22:55:07.417  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:55:07.417  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:55:07.417  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.417  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.417  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 22:55:07.418  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.418  4110  5893 I SystemUpdateService: showing system update notification
10-26 22:55:07.418  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.419  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.419  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.419  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:55:07.419  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:55:07.419  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.419  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d9681f not in the list
10-26 22:55:07.419  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:55:07.419  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.419  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.420  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.420  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.420  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.420  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 22:55:07.420  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:55:07.420  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.420  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95489ca removed from the list
10-26 22:55:07.420  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:55:07.420  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.420  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.420  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:55:07.420  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:55:07.420  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4487135 removed from the list
10-26 22:55:07.421  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:55:07.421  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@736673b added. We now have 3 listener(s)
,10-26 22:55:07.422  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 22:55:07.422  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:55:07.422  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:55:07.422  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:55:07.422  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8401e58 added. We now have 4 listener(s)
10-26 22:55:07.422  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:55:07.423  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 22:55:07.424   927  5881 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 26 Oct 2016 20:55:07 GMT], X-Android-Received-Millis=[1477515307423], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477515307402]}
10-26 22:55:07.424   927  3010 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-26 22:55:07.425   927  3010 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-26 22:55:07.425   927  3010 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-26 22:55:07.425  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:55:07.426   927  3010 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-26 22:55:07.427   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 22:55:07.428  4110  4110 D SystemUpdateService: onDestroy
,10-26 22:55:07.431  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:55:07.431  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:55:07.431  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:55:07.431  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:55:07.431  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:55:07.431  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.431  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:55:07.431  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:55:07.432  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:55:07.433  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:55:07.433  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:55:07.433  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c197896 added. We now have 4 listener(s)
10-26 22:55:07.434  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:55:07.434  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:55:07.434  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:55:07.434  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:55:07.434  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a3c17 added. We now have 5 listener(s)
10-26 22:55:07.434  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:55:07.434  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:55:07.434  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:55:07.434  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 22:55:07.434  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:55:07.434  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:55:07.435  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-26 22:55:07.437  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:55:07.437  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 22:55:07.438  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:55:07.438  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-26 22:55:07.441  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 22:55:07.441  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 22:55:07.442  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 22:55:07.444  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.444  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:55:07.444  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:55:07.444  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-26 22:55:07.444  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:55:07.444  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.445  5586  5633 D BluetoothAdapter: STATE_ON
,10-26 22:55:07.447  5823  5852 D BtGatt.GattService: registerClient() - UUID=ea8cb255-379e-4419-b160-099edd8610ec
,10-26 22:55:07.448  5823  5840 D BtGatt.GattService: onClientRegistered() - UUID=ea8cb255-379e-4419-b160-099edd8610ec, clientIf=5
,10-26 22:55:07.448  5586  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-26 22:55:07.449  5823  5834 D BtGatt.GattService: start scan with filters
,10-26 22:55:07.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-26 22:55:07.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.452  5823  5843 D BtGatt.ScanManager: handling starting scan
10-26 22:55:07.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 22:55:07.452  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:55:07.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:55:07.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.452  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:55:07.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.453  5823  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df20edc
,10-26 22:55:07.454  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.455  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:55:07.455  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.455  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:55:07.455  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.455  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.455  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:55:07.456  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:55:07.456  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.459  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.459  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.459  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.459  5586  5633 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-26 22:55:07.459  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 22:55:07.459  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 22:55:07.459  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:55:07.459  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 22:55:07.459  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:55:07.459  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 22:55:07.459  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:55:07.459  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:55:07.459  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:55:07.459  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.459  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.459  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-26 22:55:07.460  5586  5633 D BluetoothAdapter: STATE_ON
,10-26 22:55:07.461  5823  5852 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:55:07.461  5823  5840 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 22:55:07.461  5823  5834 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 22:55:07.461  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.462  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 22:55:07.462  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.462  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:55:07.462  5823  5843 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 22:55:07.462  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.462  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.462  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:55:07.462  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 22:55:07.462  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.462  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.462  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:55:07.462  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.463  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.463  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-26 22:55:07.463  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.463  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.463  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.463  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.463  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.464  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 22:55:07.464  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.464  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.464  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.464  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-26 22:55:07.464  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 22:55:07.464  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:55:07.464  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.466  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.466  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.466  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.466  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:55:07.466  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:55:07.466  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:55:07.466  5823  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-26 22:55:07.466  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.467  5823  5843 D BtGatt.ScanManager: Starting BLE batch scan
10-26 22:55:07.467  5823  5843 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 22:55:07.467  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:55:07.467  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:55:07.468  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:55:07.468  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:55:07.468  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.468  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:55:07.468  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:55:07.468  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:55:07.468  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@736673b removed from the list
10-26 22:55:07.468  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.468  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8401e58 removed from the list
10-26 22:55:07.468  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:55:07.468  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.469  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.469  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.469  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.470  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.470  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.470  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.471  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:55:07.471  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:55:07.471  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.471  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8401e58 not in the list
10-26 22:55:07.471  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.471  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.471  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: u,pdateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.472  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.472  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.472  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.473  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:55:07.473  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:55:07.473  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.473  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a3c17 removed from the list
10-26 22:55:07.473  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:55:07.473  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.473  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.473  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 22:55:07.473  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-26 22:55:07.473  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c197896 removed from the list
10-26 22:55:07.474  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:55:07.474  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc82b3 added. We now have 3 listener(s)
10-26 22:55:07.475  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:55:07.476  5823  5840 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:55:07.476  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:55:07.476  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.476  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:55:07.476  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 22:55:07.476  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c86070 added. We now have 4 listener(s)
10-26 22:55:07.476  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:55:07.477  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 22:55:07.480  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:55:07.480  5823  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-26 22:55:07.480  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:55:07.484  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:55:07.484  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:55:07.484  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:55:07.484  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:55:07.484  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:55:07.484  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.484  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:55:07.484  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 22:55:07.485  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 22:55:07.485  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:55:07.485  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:55:07.486  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fef046e added. We now have 4 listener(s)
10-26 22:55:07.486  5823  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 22:55:07.486  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.487  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:55:07.487  5823  5843 D BtGatt.ScanManager: stopping BLe Batch
10-26 22:55:07.487  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:55:07.487  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 22:55:07.487  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:55:07.487  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732970f added. We now have 5 listener(s)
10-26 22:55:07.487  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:55:07.487  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:55:07.487  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:55:07.488  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:55:07.488  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 22:55:07.488  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:55:07.488  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:55:07.488  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-26 22:55:07.489  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:55:07.490  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 22:55:07.490  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:55:07.490  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 22:55:07.491  5823  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 22:55:07.492  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.492  5823  5843 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 22:55:07.494  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 22:55:07.495  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-26 22:55:07.495  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 22:55:07.496  5823  5840 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 22:55:07.496  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.498  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.498  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:55:07.498  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:55:07.498  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:55:07.498  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:55:07.498  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.499  5586  5633 D BluetoothAdapter: STATE_ON
,10-26 22:55:07.500  5823  5864 D BtGatt.GattService: registerClient() - UUID=0b69f778-d7b2-40f4-9460-089d1dbb5f0d
10-26 22:55:07.501  5823  5840 D BtGatt.GattService: onClientRegistered() - UUID=0b69f778-d7b2-40f4-9460-089d1dbb5f0d, clientIf=5
,10-26 22:55:07.501  5586  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 22:55:07.501  5823  5834 D BtGatt.GattService: start scan with filters
,10-26 22:55:07.503  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-26 22:55:07.503  5823  5843 D BtGatt.ScanManager: handling starting scan
10-26 22:55:07.503  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.503  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-26 22:55:07.503  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.503  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.503  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:55:07.503  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:55:07.503  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.503  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.503  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:55:07.503  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.505  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.505  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:55:07.506  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.506  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-26 22:55:07.506  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.506  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.506  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:55:07.507  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:55:07.507  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.508  5823  5840 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 22:55:07.508  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.508  5823  5843 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 22:55:07.509  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.509  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.509  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.509  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:55:07.509  5586  5633 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-26 22:55:07.509  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:55:07.509  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:55:07.509  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:55:07.509  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 22:55:07.509  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.509  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 22:55:07.509  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:55:07.509  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:55:07.509  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc82b3 removed from the list
10-26 22:55:07.509  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.509  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c86070 removed from the list
10-26 22:55:07.509  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:55:07.509  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-26 22:55:07.510  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.510  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-26 22:55:07.510  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.510  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:55:07.510  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.511  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.512  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.512  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.512  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:55:07.512  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:55:07.512  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.512  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c86070 not in the list
,10-26 22:55:07.512  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:55:07.512  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:55:07.512  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:55:07.512  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.512  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 22:55:07.512  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 22:55:07.513  5586  5633 D BluetoothAdapter: STATE_ON
10-26 22:55:07.513  5823  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 22:55:07.513  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.513  5823  5833 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:55:07.513  5823  5843 D BtGatt.ScanManager: Starting BLE batch scan
10-26 22:55:07.513  5823  5843 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 22:55:07.514  5823  5860 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 22:55:07.514  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 22:55:07.514  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.514  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:55:07.514  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.514  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.514  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:55:07.514  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-26 22:55:07.514  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.514  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.514  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:55:07.514  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.515  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.515  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:55:07.515  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.515  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.515  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.515  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.515  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.516  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 22:55:07.516  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.516  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.516  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.516  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-26 22:55:07.516  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 22:55:07.516  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.516  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.517  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.517  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.517  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.517  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 22:55:07.517  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:55:07.517  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.517  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:55:07.517  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732970f removed from the list
10-26 22:55:07.517  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:55:07.517  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:55:07.517  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 22:55:07.517  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:55:07.517  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.517  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:55:07.517  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:55:07.517  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fef046e removed from the list
10-26 22:55:07.518  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:55:07.518  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60b952b added. We now have 3 listener(s)
10-26 22:55:07.519  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:55:07.519  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:55:07.519  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:55:07.519  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:55:07.519  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a3cd88 added. We now have 4 listener(s)
10-26 22:55:07.519  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:55:07.520  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 22:55:07.523  5823  5840 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:55:07.523  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.523  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:55:07.526  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:55:07.526  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:55:07.526  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:55:07.526  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:55:07.526  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:55:07.526  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.526  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:55:07.526  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:55:07.529  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.529  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:55:07.529  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:55:07.529  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bf3346 added. We now have 4 listener(s)
10-26 22:55:07.529  5823  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 22:55:07.529  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.530  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:55:07.530  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:55:07.530  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:55:07.531  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:55:07.531  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52c5907 added. We now have 5 listener(s)
10-26 22:55:07.531  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:55:07.531  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:55:07.531  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 22:55:07.531  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 22:55:07.531  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:55:07.531  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 22:55:07.531  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:55:07.533  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:55:07.535  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 22:55:07.535  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 22:55:07.535  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 22:55:07.536  5823  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 22:55:07.536  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.537  5823  5843 D BtGatt.ScanManager: stopping BLe Batch
10-26 22:55:07.538  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 22:55:07.538  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 22:55:07.538  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 22:55:07.540  5823  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 22:55:07.541  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.541  5823  5843 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 22:55:07.542  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.542  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 22:55:07.542  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 22:55:07.543  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 22:55:07.543  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 22:55:07.543  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.543  5586  5633 D BluetoothAdapter: STATE_ON
10-26 22:55:07.545  5823  5833 D BtGatt.GattService: registerClient() - UUID=b8037dc0-2b6a-42a6-b18a-706ab117b484
10-26 22:55:07.545  5823  5840 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 22:55:07.545  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.545  5823  5840 D BtGatt.GattService: onClientRegistered() - UUID=b8037dc0-2b6a-42a6-b18a-706ab117b484, clientIf=5
10-26 22:55:07.545  5586  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 22:55:07.546  5823  5864 D BtGatt.GattService: start scan with filters
10-26 22:55:07.548  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 22:55:07.548  5823  5843 D BtGatt.ScanManager: handling starting scan
10-26 22:55:07.548  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.548  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 22:55:07.548  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.548  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.548  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 22:55:07.548  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 22:55:07.548  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.548  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.548  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 22:55:07.548  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.550  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.550  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:55:07.550  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.550  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.550  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 22:55:07.550  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.550  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 22:55:07.551  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 22:55:07.551  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.552  5823  5840 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 22:55:07.552  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.552  5823  5843 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 22:55:07.553  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.553  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.553  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.556  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:55:07.556  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:55:07.556  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:55:07.557  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:55:07.557  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.557  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 22:55:07.557  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:55:07.557  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:55:07.557  5823  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 22:55:07.557  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60b952b removed from the list
10-26 22:55:07.557  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.557  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.557  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a3cd88 removed from the list
10-26 22:55:07.557  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:55:07.557  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:55:07.557  5823  5843 D BtGatt.ScanManager: Starting BLE batch scan
10-26 22:55:07.557  5823  5843 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 22:55:07.558  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.558  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-26 22:55:07.558  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.558  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:55:07.558  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.559  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.559  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.559  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.559  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:55:07.559  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:55:07.559  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.559  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a3cd88 not in the list
10-26 22:55:07.559  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 22:55:07.559  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 22:55:07.559  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 22:55:07.559  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.559  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.559  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 22:55:07.560  5586  5633 D BluetoothAdapter: STATE_ON
10-26 22:55:07.560  5823  5860 D BtGatt.GattService: stopScan() - queue size =1
10-26 22:55:07.561  5823  5833 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 22:55:07.561  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 22:55:07.561  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.561  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 22:55:07.561  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.562  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.562  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 22:55:07.562  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 22:55:07.562  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.562  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.562  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 22:55:07.562  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.563  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 22:55:07.563  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 22:55:07.564  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.564  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.565  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.565  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.565  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.565  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:55:07.565  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:55:07.565  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.565  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52c5907 removed from the list
10-26 22:55:07.565  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:55:07.565  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:55:07.565  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.565  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 22:55:07.565  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.565  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 22:55:07.565  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:55:07.565  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:55:07.565  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bf3346 removed from the list
10-26 22:55:07.566  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:55:07.566  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ab7ea3 added. We now have 3 listener(s)
10-26 22:55:07.566  5823  5840 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 22:55:07.566  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.567  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:55:07.567  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:55:07.567  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:55:07.567  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:55:07.567  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cacc5a0 added. We now have 4 listener(s)
10-26 22:55:07.567  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:55:07.568  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 22:55:07.570  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 22:55:07.571  5823  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 22:55:07.571  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.573  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 22:55:07.573  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 22:55:07.573  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 22:55:07.573  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 22:55:07.573  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 22:55:07.573  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.573  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 22:55:07.573  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 22:55:07.575  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 22:55:07.575  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 22:55:07.575  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 22:55:07.575  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4db651e added. We now have 4 listener(s)
10-26 22:55:07.577  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 22:55:07.577  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 22:55:07.577  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 22:55:07.577  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 22:55:07.577  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6d61ff added. We now have 5 listener(s)
10-26 22:55:07.577  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 22:55:07.577  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 22:55:07.577  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:55:07.577  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 22:55:07.577  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:55:07.577  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.577  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 22:55:07.577  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:55:07.577  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:55:07.577  5823  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 22:55:07.577  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ab7ea3 removed from the list
10-26 22:55:07.577  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.577  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.577  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:55:07.578  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cacc5a0 removed from the list
10-26 22:55:07.578  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
10-26 22:55:07.578  5823  5843 D BtGatt.ScanManager: stopping BLe Batch
10-26 22:55:07.578  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.578  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.578  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.578  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.579  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.579  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.579  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.579  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:55:07.579  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:55:07.579  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.579  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cacc5a0 not in the list
10-26 22:55:07.579  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.579  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.579  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.580  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 22:55:07.581  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.581  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.581  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 22:55:07.581  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 22:55:07.581  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 22:55:07.581  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 22:55:07.581  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6d61ff removed from the list
10-26 22:55:07.581  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 22:55:07.581  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 22:55:07.581  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 22:55:07.581  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 22:55:07.581  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 22:55:07.581  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4db651e removed from the list
10-26 22:55:07.582  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-26 22:55:07.582  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-26 22:55:07.582  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-26 22:55:07.582  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:55:07.582  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-26 22:55:07.582  5823  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 22:55:07.582  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 22:55:07.582  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 22:55:07.583  5823  5843 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 22:55:07.589  5823  5840 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 22:55:07.589  5823  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 22:55:07.967  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:55:08.018  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:55:08.066  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 22:55:08.277   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-26 22:55:09.755  5586  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 22:55:09.755  5586  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:55:10.571  5586  5901 W !!      : call onHalfStreamCopied
,10-26 22:55:10.571  5586  5901 I testCopyDataAndClose: closing input stream
,10-26 22:55:10.697  3615  5903 I VacuumService: Vacuum at: now=1477515310697 tag=VacuumService
,10-26 22:55:10.721  3615  5906 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-26 22:55:10.761  3615  5904 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-26 22:55:10.763  3615  5904 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-26 22:55:10.782  3615  5904 W Uploader:  no longer exists, so no auth token.
,10-26 22:55:10.788  3615  5906 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:55:11.170  3615  5908 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:55:11.226  3615  5904 W Uploader:  no longer exists, so no auth token.
,10-26 22:55:11.237  3615  5906 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:55:11.311  3615  5908 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 22:55:11.348  5586  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-26 22:55:11.391  3615  5906 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 22:55:15.262   927  3010 D ConnectivityService: handlePromptUnvalidated 102
,10-26 22:55:15.641  5586  5913 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:55:15.641  5586  5913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:55:17.640  5586  5633 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 176. Connection data: Peer properties: [null null].
10-26 22:55:17.640  5586  5633 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:55:17.641  5586  5633 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 176, name: My test thread name)
,10-26 22:55:17.665  5586  5913 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-26 22:55:17.665  5586  5913 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:55:17.665  5586  5913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,10-26 22:55:17.806  5586  5914 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 22:55:17.806  5586  5914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 22:55:19.417  5586  5914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-26 22:55:23.528  5586  5915 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:55:23.528  5586  5915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 22:55:23.528  5586  5915 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:55:23.528  5586  5915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:55:23.528  5586  5915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 22:55:23.528  5586  5915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:55:23.529  5586  5915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-26 22:55:23.529  5586  5915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-26 22:55:23.529  5586  5915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 22:55:23.529  5586  5915 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-26 22:55:23.529  5586  5915 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-26 22:55:23.529  5586  5915 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:55:23.529  5586  5915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,10-26 22:55:23.531  5586  5633 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-26 22:55:23.534  5586  5916 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:55:23.534  5586  5916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 22:55:23.534  5586  5916 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 184, thread name: My test thread name): Test exception.
,10-26 22:55:23.535  5586  5916 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:55:23.535  5586  5916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-26 22:55:23.535  5586  5916 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,10-26 22:55:23.535  5586  5916 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-26 22:55:23.535  5586  5916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-26 22:55:23.540  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-26 22:55:23.540  5586  5633 I jxcore-log: 
10-26 22:55:23.541  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-26 22:55:23.541  5586  5633 I jxcore-log: 
10-26 22:55:23.541  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-26 22:55:23.541  5586  5633 I jxcore-log: 
10-26 22:55:23.541  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-26 22:55:23.541  5586  5633 I jxcore-log: 
,10-26 22:55:23.542  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG UnitTest_app: 'Total duration:  91696'
10-26 22:55:23.542  5586  5633 I jxcore-log: 
10-26 22:55:23.544  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-26 22:55:23.544  5586  5633 I jxcore-log: 
,10-26 22:55:23.547  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.547  5586  5633 I jxcore-log: 
10-26 22:55:23.548  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.548  5586  5633 I jxcore-log: 
10-26 22:55:23.548  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.548  5586  5633 I jxcore-log: 
10-26 22:55:23.548  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.548  5586  5633 I jxcore-log: 
,10-26 22:55:23.549  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-26 22:55:23.549  5586  5633 I jxcore-log: 
10-26 22:55:23.549  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:55:23.549  5586  5633 I jxcore-log: 
10-26 22:55:23.549  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.549  5586  5633 I jxcore-log: 
10-26 22:55:23.550  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.550  5586  5633 I jxcore-log: 
,10-26 22:55:23.550  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-26 22:55:23.550  5586  5633 I jxcore-log: 
,10-26 22:55:23.550  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:55:23.550  5586  5633 I jxcore-log: 
10-26 22:55:23.550  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:55:23.550  5586  5633 I jxcore-log: 
10-26 22:55:23.551  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.551  5586  5633 I jxcore-log: 
10-26 22:55:23.551  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.551  5586  5633 I jxcore-log: 
10-26 22:55:23.551  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.551  5586  5633 I jxcore-log: 
,10-26 22:55:23.551  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:55:23.551  5586  5633 I jxcore-log: 
10-26 22:55:23.552  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.552  5586  5633 I jxcore-log: 
10-26 22:55:23.552  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:55:23.552  5586  5633 I jxcore-log: 
10-26 22:55:23.552  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:55:23.552  5586  5633 I jxcore-log: 
,10-26 22:55:23.552  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.552  5586  5633 I jxcore-log: 
10-26 22:55:23.553  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.553  5586  5633 I jxcore-log: 
10-26 22:55:23.553  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.553  5586  5633 I jxcore-log: 
10-26 22:55:23.553  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:55:23.553  5586  5633 I jxcore-log: 
10-26 22:55:23.553  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:55:23.553  5586  5633 I jxcore-log: 
,10-26 22:55:23.555  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:55:23.555  5586  5633 I jxcore-log: 
10-26 22:55:23.555  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.555  5586  5633 I jxcore-log: 
,10-26 22:55:23.555  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.555  5586  5633 I jxcore-log: 
10-26 22:55:23.555  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.555  5586  5633 I jxcore-log: 
10-26 22:55:23.556  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:55:23.556  5586  5633 I jxcore-log: 
10-26 22:55:23.556  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 22:55:23.556  5586  5633 I jxcore-log: 
,10-26 22:55:23.556  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.556  5586  5633 I jxcore-log: 
10-26 22:55:23.556  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.556  5586  5633 I jxcore-log: 
10-26 22:55:23.557  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.557  5586  5633 I jxcore-log: 
10-26 22:55:23.557  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.557  5586  5633 I jxcore-log: 
10-26 22:55:23.557  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.557  5586  5633 I jxcore-log: 
10-26 22:55:23.557  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.557  5586  5633 I jxcore-log: 
10-26 22:55:23.558  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.558  5586  5633 I jxcore-log: 
10-26 22:55:23.558  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.558  5586  5633 I jxcore-log: 
,10-26 22:55:23.558  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.558  5586  5633 I jxcore-log: 
10-26 22:55:23.558  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.558  5586  5633 I jxcore-log: 
10-26 22:55:23.558  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.558  5586  5633 I jxcore-log: 
,10-26 22:55:23.559  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 22:55:23.559  5586  5633 I jxcore-log: 
10-26 22:55:23.559  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 22:55:23.559  5586  5633 I jxcore-log: 
10-26 22:55:23.559  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 22:55:23.559  5586  5633 I jxcore-log: 
10-26 22:55:23.559  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.559  5586  5633 I jxcore-log: 
10-26 22:55:23.560  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.560  5586  5633 I jxcore-log: 
,10-26 22:55:23.560  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.560  5586  5633 I jxcore-log: 
10-26 22:55:23.560  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.560  5586  5633 I jxcore-log: 
10-26 22:55:23.560  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.560  5586  5633 I jxcore-log: 
10-26 22:55:23.560  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 22:55:23.560  5586  5633 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-26 22:55:23.561  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.561  5586  5633 I jxcore-log: 
10-26 22:55:23.561  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.561  5586  5633 I jxcore-log: 
10-26 22:55:23.561  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 22:55:23.561  5586  5633 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-26 22:55:23.561  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 22:55:23.561  5586  5633 I jxcore-log: 
10-26 22:55:23.561  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:55:23.561  5586  5633 I jxcore-log: 
10-26 22:55:23.562  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:55:23.562  5586  5633 I jxcore-log: 
,10-26 22:55:23.562  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 22:55:23.562  5586  5633 I jxcore-log: 
10-26 22:55:23.564  5586  5586 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-26 22:55:23.567  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-26 22:55:23.567  5586  5633 I jxcore-log: 
10-26 22:55:23.569  5586  5633 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-26 22:55:23.569  5586  5633 I jxcore-log: 2016-10-26 20:55:23 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-26 22:55:23.569  5586  5633 I jxcore-log: 
,10-26 22:55:25.611  5586  5633 I jxcore-log: 2016-10-26 20:55:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-26 22:55:25.611  5586  5633 I jxcore-log: 
,10-26 22:55:25.954  5586  5633 I jxcore-log: 2016-10-26 20:55:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-26 22:55:25.954  5586  5633 I jxcore-log: 
,10-26 22:55:25.967  5586  5633 I jxcore-log: 2016-10-26 20:55:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-26 22:55:25.967  5586  5633 I jxcore-log: 
,10-26 22:55:27.097  5586  5633 I jxcore-log: 2016-10-26 20:55:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-26 22:55:27.097  5586  5633 I jxcore-log: 
,10-26 22:55:27.288  5586  5633 I jxcore-log: 2016-10-26 20:55:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-26 22:55:27.288  5586  5633 I jxcore-log: 
,10-26 22:55:27.293  5586  5633 I jxcore-log: 2016-10-26 20:55:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-26 22:55:27.293  5586  5633 I jxcore-log: 
,10-26 22:55:27.298  5586  5633 I jxcore-log: 2016-10-26 20:55:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-26 22:55:27.298  5586  5633 I jxcore-log: 
,10-26 22:55:27.776  5586  5633 I jxcore-log: 2016-10-26 20:55:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-26 22:55:27.776  5586  5633 I jxcore-log: 
,10-26 22:55:27.820  5586  5633 I jxcore-log: 2016-10-26 20:55:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-26 22:55:27.820  5586  5633 I jxcore-log: 
,10-26 22:55:27.833  5586  5633 I jxcore-log: 2016-10-26 20:55:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-26 22:55:27.833  5586  5633 I jxcore-log: 
,10-26 22:55:27.838  5586  5633 I jxcore-log: 2016-10-26 20:55:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-26 22:55:27.838  5586  5633 I jxcore-log: 
,10-26 22:55:28.128  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-26 22:55:28.128  5586  5633 I jxcore-log: 
,10-26 22:55:28.255  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-26 22:55:28.255  5586  5633 I jxcore-log: 
,10-26 22:55:28.279   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:55:28.645  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-26 22:55:28.645  5586  5633 I jxcore-log: 
,10-26 22:55:28.652  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-26 22:55:28.652  5586  5633 I jxcore-log: 
,10-26 22:55:28.656  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-26 22:55:28.656  5586  5633 I jxcore-log: 
,10-26 22:55:28.660  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-26 22:55:28.660  5586  5633 I jxcore-log: 
,10-26 22:55:28.665  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-26 22:55:28.665  5586  5633 I jxcore-log: 
,10-26 22:55:28.692  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-26 22:55:28.692  5586  5633 I jxcore-log: 
,10-26 22:55:28.727  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-26 22:55:28.727  5586  5633 I jxcore-log: 
,10-26 22:55:28.734  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-26 22:55:28.734  5586  5633 I jxcore-log: 
,10-26 22:55:28.741  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-26 22:55:28.741  5586  5633 I jxcore-log: 
,10-26 22:55:28.756  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-26 22:55:28.756  5586  5633 I jxcore-log: 
,10-26 22:55:28.760  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-26 22:55:28.760  5586  5633 I jxcore-log: 
,10-26 22:55:28.766  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-26 22:55:28.766  5586  5633 I jxcore-log: 
,10-26 22:55:28.771  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-26 22:55:28.771  5586  5633 I jxcore-log: 
,10-26 22:55:28.784  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-26 22:55:28.784  5586  5633 I jxcore-log: 
,10-26 22:55:28.790  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-26 22:55:28.790  5586  5633 I jxcore-log: 
,10-26 22:55:28.812  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-26 22:55:28.812  5586  5633 I jxcore-log: 
,10-26 22:55:28.823  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-26 22:55:28.823  5586  5633 I jxcore-log: 
,10-26 22:55:28.835  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-26 22:55:28.835  5586  5633 I jxcore-log: 
,10-26 22:55:28.845  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-26 22:55:28.845  5586  5633 I jxcore-log: 
,10-26 22:55:28.858  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-26 22:55:28.858  5586  5633 I jxcore-log: 
,10-26 22:55:28.868  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-26 22:55:28.868  5586  5633 I jxcore-log: 
,10-26 22:55:28.874  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-26 22:55:28.874  5586  5633 I jxcore-log: 
,10-26 22:55:28.896  5586  5633 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-26 22:55:28.897  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - INFO testUtils: 'BLE multiple advertisement supported'
10-26 22:55:28.897  5586  5633 I jxcore-log: 
,10-26 22:55:28.968  5586  5633 I jxcore-log: 2016-10-26 20:55:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:28.968  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:28.968  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:28.968  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:28.968  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:28.968  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:28.968  5586  5633 I jxcore-log: 
,10-26 22:55:29.272  5586  5633 I jxcore-log: 2016-10-26 20:55:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:29.272  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:29.272  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:29.272  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:29.272  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:29.272  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:29.272  5586  5633 I jxcore-log: 
,10-26 22:55:29.277  5586  5633 I jxcore-log: 2016-10-26 20:55:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:29.277  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:29.277  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:29.277  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:29.277  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:29.277  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:29.277  5586  5633 I jxcore-log: 
,10-26 22:55:29.280   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:55:29.602  5586  5633 I jxcore-log: 2016-10-26 20:55:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:29.602  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:29.602  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:29.602  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:29.602  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:29.602  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:29.602  5586  5633 I jxcore-log: 
,10-26 22:55:29.606  5586  5633 I jxcore-log: 2016-10-26 20:55:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:29.606  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:29.606  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:29.606  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:29.606  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:29.606  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:29.606  5586  5633 I jxcore-log: 
,10-26 22:55:30.281   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:55:30.581  5586  5633 I jxcore-log: 2016-10-26 20:55:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:30.581  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:30.581  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:30.581  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:30.581  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:30.581  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:30.581  5586  5633 I jxcore-log: 
,10-26 22:55:30.584  5586  5633 I jxcore-log: 2016-10-26 20:55:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:30.584  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:30.584  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:30.584  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:30.584  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:30.584  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:30.584  5586  5633 I jxcore-log: 
,10-26 22:55:31.282   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:55:32.266  5586  5633 I jxcore-log: 2016-10-26 20:55:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:32.266  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:32.266  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:32.266  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:32.266  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:32.266  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:32.266  5586  5633 I jxcore-log: 
,10-26 22:55:32.275  5586  5633 I jxcore-log: 2016-10-26 20:55:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:32.275  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:32.275  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:32.275  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:32.275  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:32.275  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:32.275  5586  5633 I jxcore-log: 
,10-26 22:55:32.283   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 22:55:33.284   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-26 22:55:33.315  5586  5633 I jxcore-log: 2016-10-26 20:55:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:33.315  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:33.315  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:33.315  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:33.315  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:33.315  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:33.315  5586  5633 I jxcore-log: 
,10-26 22:55:33.318  5586  5633 I jxcore-log: 2016-10-26 20:55:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:33.318  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:33.318  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:33.318  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:33.318  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:33.318  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:33.318  5586  5633 I jxcore-log: 
,10-26 22:55:34.384  5586  5633 I jxcore-log: 2016-10-26 20:55:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:34.384  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:34.384  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:34.384  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:34.384  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:34.384  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:34.384  5586  5633 I jxcore-log: 
,10-26 22:55:34.391  5586  5633 I jxcore-log: 2016-10-26 20:55:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:34.391  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:34.391  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:34.391  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:34.391  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:34.391  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:34.391  5586  5633 I jxcore-log: 
,10-26 22:55:35.426  5586  5633 I jxcore-log: 2016-10-26 20:55:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:35.426  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:35.426  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:35.426  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:35.426  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:35.426  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:35.426  5586  5633 I jxcore-log: 
,10-26 22:55:35.430  5586  5633 I jxcore-log: 2016-10-26 20:55:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:35.430  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:35.430  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:35.430  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:35.430  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:35.430  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:35.430  5586  5633 I jxcore-log: 
,10-26 22:55:36.468  5586  5633 I jxcore-log: 2016-10-26 20:55:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:36.468  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:36.468  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:36.468  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:36.468  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:36.468  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:36.468  5586  5633 I jxcore-log: 
,10-26 22:55:36.473  5586  5633 I jxcore-log: 2016-10-26 20:55:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:36.473  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:36.473  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:36.473  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:36.473  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:36.473  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:36.473  5586  5633 I jxcore-log: 
,10-26 22:55:37.511  5586  5633 I jxcore-log: 2016-10-26 20:55:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:37.511  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:37.511  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:37.511  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:37.511  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:37.511  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:37.511  5586  5633 I jxcore-log: 
,10-26 22:55:37.514  5586  5633 I jxcore-log: 2016-10-26 20:55:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:37.514  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:37.514  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:37.514  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:37.514  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:37.514  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:37.514  5586  5633 I jxcore-log: 
,10-26 22:55:38.582  5586  5633 I jxcore-log: 2016-10-26 20:55:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:38.582  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:38.582  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:38.582  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:38.582  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:38.582  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:38.582  5586  5633 I jxcore-log: 
,10-26 22:55:38.586  5586  5633 I jxcore-log: 2016-10-26 20:55:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:38.586  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:38.586  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:38.586  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:38.586  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:38.586  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:38.586  5586  5633 I jxcore-log: 
,10-26 22:55:39.717  5586  5633 I jxcore-log: 2016-10-26 20:55:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:39.717  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:39.717  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:39.717  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:39.717  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:39.717  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:39.717  5586  5633 I jxcore-log: 
,10-26 22:55:39.723  5586  5633 I jxcore-log: 2016-10-26 20:55:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:39.723  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:39.723  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:39.723  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:39.723  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:39.723  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:39.723  5586  5633 I jxcore-log: 
,10-26 22:55:40.753  5586  5633 I jxcore-log: 2016-10-26 20:55:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:40.753  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:40.753  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:40.753  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:40.753  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:40.753  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:40.753  5586  5633 I jxcore-log: 
,10-26 22:55:40.756  5586  5633 I jxcore-log: 2016-10-26 20:55:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:40.756  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:40.756  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:40.756  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:40.756  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:40.756  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:40.756  5586  5633 I jxcore-log: 
,10-26 22:55:41.795  5586  5633 I jxcore-log: 2016-10-26 20:55:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:41.795  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:41.795  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:41.795  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:41.795  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:41.795  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:41.795  5586  5633 I jxcore-log: 
,10-26 22:55:41.798  5586  5633 I jxcore-log: 2016-10-26 20:55:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:41.798  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:41.798  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:41.798  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:41.798  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:41.798  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:41.798  5586  5633 I jxcore-log: 
,10-26 22:55:42.829  5586  5633 I jxcore-log: 2016-10-26 20:55:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:42.829  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:42.829  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:42.829  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:42.829  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:42.829  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:42.829  5586  5633 I jxcore-log: 
,10-26 22:55:42.833  5586  5633 I jxcore-log: 2016-10-26 20:55:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:42.833  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:42.833  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:42.833  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:42.833  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:42.833  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:42.833  5586  5633 I jxcore-log: 
,10-26 22:55:43.877  5586  5633 I jxcore-log: 2016-10-26 20:55:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 22:55:43.877  5586  5633 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 22:55:43.877  5586  5633 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 22:55:43.877  5586  5633 I jxcore-log: emit@events.js:82:1
10-26 22:55:43.877  5586  5633 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 22:55:43.877  5586  5633 I jxcore-log: emit@events.js:82:1'
10-26 22:55:43.877  5586  5633 I jxcore-log: 
,10-26 22:55:43.887  5586  5633 E jxcore  : Error!: error is undefined
10-26 22:55:43.887  5586  5633 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-26 22:55:43.890  5586  5633 I jxcore-log: 2016-10-26 20:55:43 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-26 22:55:43.890  5586  5633 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
10-26 22:55:43.890  5586  5633 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-26 22:55:43.890  5586  5633 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-26 22:55:43.890  5586  5633 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-26 22:55:43.890  5586  5633 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-26 22:55:43.890  5586  5633 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-26 22:55:43.890  5586  5633 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-26 22:55:43.891  5586  5633 I jxcore-log: 2016-10-26 20:55:43 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-26 22:55:43.891  5586  5633 I jxcore-log: 
10-26 22:55:43.893  5586  5633 E jxcore-log: TypeError: 
,10-26 22:55:43.893  5586  5633 E jxcore-log: error is undefined
10-26 22:55:43.893  5586  5633 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
10-26 22:55:43.893  5586  5633 E jxcore-log: 
,10-26 22:55:43.987   927  3192 D GraphicsStats: Buffer count: 2
10-26 22:55:43.987   927  3629 I WindowState: WIN DEATH: Window{ba04bb u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-26 22:55:43.989   927  3009 D WifiService: Client connection lost with reason: 4
,10-26 22:55:44.004   927  3186 I ActivityManager: Process com.test.thalitest (pid 5586) has died
10-26 22:55:44.001   527   527 I Zygote  : Process 5586 exited cleanly (139)
,10-26 22:55:44.019   927  3186 I ActivityManager: Start proc 5919:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-26 22:55:44.090  5919  5919 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-26 22:55:44.108  5919  5919 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-26 22:55:44.113  5919  5919 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4572-4574)
,10-26 22:55:44.113  5919  5919 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 22:55:44.122  5919  5919 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {64c9b44}
10-26 22:55:44.122  5919  5919 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-26 22:55:44.122  5919  5919 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-26 22:55:44.126  5919  5919 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-26 22:55:44.127  5919  5919 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-26 22:55:44.137  5919  5919 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-26 22:55:44.145  5919  5919 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-26 22:55:44.145  5919  5919 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 22:55:44.145  5919  5919 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 22:55:44.145  5919  5919 I Adreno  : Build Date                       : 12/06/15
10-26 22:55:44.145  5919  5919 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 22:55:44.145  5919  5919 I Adreno  : Local Branch                     : mybranch17112971
10-26 22:55:44.145  5919  5919 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 22:55:44.145  5919  5919 I Adreno  : Remote Branch                    : NONE
10-26 22:55:44.145  5919  5919 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 22:55:44.176   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6f1cded:true
,10-26 22:55:44.190  2577  2577 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34940]" dev="sockfs" ino=34940 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:55:44.190  2577  2577 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34940]" dev="sockfs" ino=34940 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:55:44.204  5919  5919 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-26 22:55:44.212  5919  5919 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-26 22:55:44.240   403   403 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[31592]" dev="sockfs" ino=31592 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 22:55:44.240   403   403 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[31592]" dev="sockfs" ino=31592 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-26 22:55:44.243  5919  5955 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-26 22:55:44.243  3629  3629 W Binder_6: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[15834]" dev="sockfs" ino=15834 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:55:44.243  3629  3629 W Binder_6: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[15834]" dev="sockfs" ino=15834 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:55:44.248  5919  5942 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-26 22:55:44.288  5919  5955 I OpenGLRenderer: Initialized EGL, version 1.4
,10-26 22:55:44.318   927  3609 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5586 uid 10077
,10-26 22:55:44.318   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +275ms (total +313ms)
,10-26 22:55:44.317  3609  3609 W Binder_5: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[34610]" dev="sockfs" ino=34610 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:55:44.317  3609  3609 W Binder_5: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[34610]" dev="sockfs" ino=34610 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:55:44.317  4039  4039 W Binder_8: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[34609]" dev="sockfs" ino=34609 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 22:55:44.317  4039  4039 W Binder_8: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[34609]" dev="sockfs" ino=34609 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 22:55:44.322  5919  5919 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5919
,10-26 22:55:44.324  3682  3682 I Keyboard.Facilitator: onFinishInput()
,10-26 22:55:44.335  5917  5917 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-26 22:55:44.350  5917  5917 D AndroidRuntime: CheckJNI is OFF
,10-26 22:55:44.373  5917  5917 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-26 22:55:44.377  5919  5919 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-26 22:55:44.397  5917  5917 I Radio-JNI: register_android_hardware_Radio DONE
,10-26 22:55:44.413  5917  5917 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-26 22:55:44.423   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-26 22:55:44.423   927   940 I ActivityManager: Killing 5919:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-26 22:55:44.457   927  3629 D GraphicsStats: Buffer count: 2
,10-26 22:55:44.457   927  4042 I WindowState: WIN DEATH: Window{50531a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-26 22:55:44.518   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
10-26 22:55:44.519   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-26 22:55:44.520   927   940 E ActivityManager: Failure starting process com.test.thalitest
10-26 22:55:44.520   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-26 22:55:44.520   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 22:55:44.520   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-26 22:55:44.520   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-26 22:55:44.520   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-26 22:55:44.520   927   950 I art     : Starting a blocking GC Explicit
10-26 22:55:44.521   927   940 I ActivityManager:   Force finishing activity ActivityRecord{3c16463 u0 com.test.thalitest/.MainActivity t66}
,10-26 22:55:44.530   927  3186 W ActivityManager: Spurious death for ProcessRecord{a17b11e 0:com.test.thalitest/u0a77}, curProc for 5919: null
,10-26 22:55:44.603   927   950 I art     : Explicit concurrent mark sweep GC freed 12945(864KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.663ms total 82.551ms
,10-26 22:55:44.620   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-26 22:55:44.622  5917  5917 I art     : System.exit called, status: 0
,10-26 22:55:44.623  5917  5917 I AndroidRuntime: VM exiting with result code 0.
,10-26 22:55:44.627   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-26 22:55:44.631   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-26 22:55:44.635  5823  5823 D BluetoothMapAppObserver: onReceive
,10-26 22:55:44.635  5823  5823 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-26 22:55:44.639  3984  4159 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-26 22:55:44.647   927  2974 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-26 22:55:44.649  3682  3682 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-26 22:55:44.672  3682  5971 I Keyboard.Facilitator.DecoderInitializer: run()
,10-26 22:55:44.677  3682  5971 I Decoder : createOrResetDecoder
,10-26 22:55:44.701  3805  3805 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-26 22:55:44.707   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-26 22:55:44.720  3439  5974 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-26 22:55:44.721  3615  3615 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-26 22:55:44.722  3615  3615 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-26 22:55:44.732  3615  3615 I ConfigService: onCreate
,10-26 22:55:44.730    27    27 W kworker/2:1: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 22:55:44.740    27    27 W kworker/2:1: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 22:55:44.750    27    27 W kworker/2:1: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 22:55:44.759  3682  5971 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-26 22:55:44.765  4110  5978 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-26 22:55:44.765  4110  5978 D AccountUtils: Clearing selected account for com.test.thalitest
,10-26 22:55:44.821  4110  5978 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-26 22:55:44.827  3439  5974 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
10-26 22:55:44.832  3439  5974 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
10-26 22:55:44.832  3439  5974 E AndroidRuntime: Process: android.process.acore, PID: 3439
10-26 22:55:44.832  3439  5974 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-26 22:55:44.832  3439  5974 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
