#### Test 90793797671d7b3_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-25 14:25:15.065  3821  4039 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,10-25 14:25:15.156  3821  4039 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
10-25 14:25:15.507  5504  5504 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-25 14:25:15.513  5504  5504 D AndroidRuntime: CheckJNI is OFF
10-25 14:25:15.540  5504  5504 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-25 14:25:15.570  5504  5504 I Radio-JNI: register_android_hardware_Radio DONE
10-25 14:25:15.585  5504  5504 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-25 14:25:15.588   926  3040 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-25 14:25:15.610  5504  5504 D AndroidRuntime: Shutting down VM
10-25 14:25:15.614  3799  3807 W SearchService: Abort, client detached.
10-25 14:25:15.620  3799  3799 I HotwordDetector: Closing mic
10-25 14:25:15.620  3799  4036 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c46147e
10-25 14:25:15.621  3799  4041 E AudioRecord-JNI: Error -4 during AudioRecord native read
10-25 14:25:15.644   926   937 I ActivityManager: Start proc 5513:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-25 14:25:15.689   511  4043 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
10-25 14:25:15.691   511  4043 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
10-25 14:25:15.698   511  4043 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
10-25 14:25:15.698   511  4043 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
10-25 14:25:15.699   511  2877 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
10-25 14:25:15.700  3799  4037 I MicroRecognitionRnrImpl: Stopping hotword detection.
10-25 14:25:15.701  3799  4040 I MicroRecognitionRnrImpl: Detection finished
10-25 14:25:15.748  5513  5513 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
10-25 14:25:15.764  5513  5513 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
10-25 14:25:15.821  5513  5513 I LibraryLoader: Time to load native libraries: 53 ms (timestamps 8537-8590)
10-25 14:25:15.821  5513  5513 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-25 14:25:15.861  5513  5513 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9eb185}
,10-25 14:25:15.861  5513  5513 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-25 14:25:15.861  5513  5513 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-25 14:25:15.864  5513  5513 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-25 14:25:15.865  5513  5513 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-25 14:25:15.910  5513  5513 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-25 14:25:15.918  5513  5513 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-25 14:25:15.918  5513  5513 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-25 14:25:15.918  5513  5513 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-25 14:25:15.918  5513  5513 I Adreno  : Build Date                       : 12/06/15
10-25 14:25:15.918  5513  5513 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-25 14:25:15.918  5513  5513 I Adreno  : Local Branch                     : mybranch17112971
10-25 14:25:15.918  5513  5513 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-25 14:25:15.918  5513  5513 I Adreno  : Remote Branch                    : NONE
10-25 14:25:15.918  5513  5513 I Adreno  : Reconstruct Branch               : NOTHING
,10-25 14:25:15.957   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6f8a12f:true
,10-25 14:25:15.991  2820  2820 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[33802]" dev="sockfs" ino=33802 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 14:25:15.991  2820  2820 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33802]" dev="sockfs" ino=33802 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 14:25:16.007  5513  5513 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-25 14:25:16.015  5513  5513 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-25 14:25:16.041  2821  2821 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32332]" dev="sockfs" ino=32332 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 14:25:16.041  2821  2821 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32332]" dev="sockfs" ino=32332 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 14:25:16.047  3044  3044 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33814]" dev="sockfs" ino=33814 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:25:16.047  3044  3044 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33814]" dev="sockfs" ino=33814 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:16.052  5513  5537 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-25 14:25:16.084  5513  5550 I OpenGLRenderer: Initialized EGL, version 1.4
,10-25 14:25:16.163   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +546ms
,10-25 14:25:16.157  3498  3498 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31195]" dev="sockfs" ino=31195 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:25:16.157  3498  3498 W Binder_7: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31195]" dev="sockfs" ino=31195 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:16.164  3290  3290 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31194]" dev="sockfs" ino=31194 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:25:16.164  3290  3290 W Binder_6: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31194]" dev="sockfs" ino=31194 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:25:16.169  3528  3528 I Keyboard.Facilitator: onFinishInput()
,10-25 14:25:16.202  5513  5513 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5513
,10-25 14:25:16.288  5513  5513 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-25 14:25:16.525  5513  5552 D jxcore_app_log: JniHelper::setJavaVM(0xf523c000), pthread_self() = -580650704
,10-25 14:25:16.530  5513  5552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-25 14:25:16.530  5513  5552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-25 14:25:16.530  5513  5552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-25 14:25:16.530  5513  5552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-25 14:25:16.530  5513  5552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-25 14:25:16.530  5513  5552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e8bcf9 added. We now have 1 listener(s)
,10-25 14:25:16.532  5513  5552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,10-25 14:25:16.533  5513  5552 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-25 14:25:16.533  5513  5552 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 14:25:16.533  5513  5552 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-25 14:25:16.536  5513  5552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ed9fec added. We now have 1 listener(s)
10-25 14:25:16.536  5513  5552 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 14:25:16.540   926  2830 D WifiService: New client listening to asynchronous messages
,10-25 14:25:16.541  5513  5552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-25 14:25:16.541  5513  5552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-25 14:25:16.541  5513  5552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-25 14:25:16.541  5513  5552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-25 14:25:16.541  5513  5552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-25 14:25:16.543  5513  5552 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 14:25:16.543  5513  5552 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,10-25 14:25:16.546  5513  5552 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-25 14:25:16.546  5513  5552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 14:25:16.546  5513  5552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:16.546  5513  5552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:16.546  5513  5552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:16.546  5513  5552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:16.546  5513  5552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:16.546  5513  5552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 14:25:16.546  5513  5552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 14:25:16.547  5513  5552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-25 14:25:16.547  5513  5552 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 14:25:16.547  5513  5552 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-25 14:25:16.716  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:16.723  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:16.731  5513  5513 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-25 14:25:17.061  5513  5522 I art     : Background sticky concurrent mark sweep GC freed 75304(7MB) AllocSpace objects, 16(1044KB) LOS objects, 24% free, 24MB/32MB, paused 1.673ms total 258.486ms
,10-25 14:25:17.275   926  2829 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-25 14:25:18.298  5513  5522 I art     : Background partial concurrent mark sweep GC freed 53084(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.749ms total 340.338ms
,10-25 14:25:19.118  5513  5560 W jxcore-log: Initializing JXcore engine
10-25 14:25:19.118  5513  5560 W jxcore-log: JXcore engine is ready
,10-25 14:25:19.137  5560  5560 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11735 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-25 14:25:19.137  5560  5560 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14451]" dev="sockfs" ino=14451 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-25 14:25:19.137  5560  5560 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5954 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-25 14:25:19.137  5560  5560 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32303]" dev="sockfs" ino=32303 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-25 14:25:19.151  5513  5560 W jxcore-log: Starting JXcore engine
,10-25 14:25:19.171  3458  3458 I ConfigService: onDestroy
,10-25 14:25:19.200  5513  5560 W jxcore-log: Platform android
10-25 14:25:19.200  5513  5560 W jxcore-log: 
,10-25 14:25:19.201  5513  5560 W jxcore-log: Process ARCH arm
10-25 14:25:19.201  5513  5560 W jxcore-log: 
,10-25 14:25:19.398  5513  5560 I jxcore-log: JXcore Cordova bridge is ready!
10-25 14:25:19.398  5513  5560 I jxcore-log: 
,10-25 14:25:19.399  5513  5560 W jxcore-log: JXcore engine is started
,10-25 14:25:19.405  5513  5552 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-25 14:25:19.412  5513  5513 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-25 14:25:20.518   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:25:20.635   926  3286 I ActivityManager: Killing 5297:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-25 14:25:20.667   926  3286 I ActivityManager: Killing 4948:com.google.android.apps.maps/u0a58 (adj 15): empty #18
,10-25 14:25:21.519   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:25:22.520   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:25:23.521   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:25:24.522   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:25:25.523   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-25 14:25:28.776  3799  5561 W CronetSyncConnectionRcs: Upload content type not set.
,10-25 14:25:28.848  4703  4775 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-25 14:25:28.849  4703  4703 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-25 14:25:29.155  5513  5560 I jxcore-log: 2016-10-25 12:25:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-25 14:25:29.155  5513  5560 I jxcore-log: 
,10-25 14:25:29.157  5513  5560 I jxcore-log: 2016-10-25 12:25:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-25 14:25:29.157  5513  5560 I jxcore-log: 
,10-25 14:25:29.160  5513  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 14:25:29.160  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:29.160  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:29.160  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:29.160  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:29.160  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:29.160  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 14:25:29.160  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 14:25:29.162  5513  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 14:25:29.163  5513  5560 I jxcore-log: 2016-10-25 12:25:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-25 14:25:29.163  5513  5560 I jxcore-log: 
,10-25 14:25:29.164  5513  5560 I jxcore-log: 2016-10-25 12:25:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-25 14:25:29.164  5513  5560 I jxcore-log: 
,10-25 14:25:29.415  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-25 14:25:29.415  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@416e442 added. We now have 2 listener(s)
10-25 14:25:29.416  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 14:25:29.416  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-25 14:25:29.416  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 14:25:29.416  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 14:25:29.416  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4577c53 added. We now have 2 listener(s)
10-25 14:25:29.416  5513  5560 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 14:25:29.417  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-25 14:25:29.419  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 14:25:29.423  5513  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 14:25:29.423  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:29.423  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:29.423  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:29.423  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:29.423  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:29.423  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 14:25:29.423  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 14:25:29.427  5513  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:29.428  5513  5560 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 14:25:29.428  5513  5560 D ExecuteNativeTests: Running unit tests
10-25 14:25:29.429  5513  5560 D BluetoothAdapter: enable(): BT is already enabled..!
10-25 14:25:29.429   926  3498 D WifiService: setWifiEnabled: true pid=5513, uid=10077
10-25 14:25:29.429   926  3498 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 14:25:29.433  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:29.438  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:39.435  5513  5560 I com.test.thalitest.ThaliTestRunner: Running UT
,10-25 14:25:39.500  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-25 14:25:39.501  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34136d added. We now have 3 listener(s)
10-25 14:25:39.502  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-25 14:25:39.502  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 14:25:39.502  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 14:25:39.502  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 14:25:39.502  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@765aba2 added. We now have 3 listener(s)
10-25 14:25:39.502  5513  5560 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 14:25:39.503  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-25 14:25:39.506  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 14:25:39.510  5513  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 14:25:39.510  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:39.510  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:39.510  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:39.510  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:39.510  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:39.510  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 14:25:39.510  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 14:25:39.513  5513  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:39.513  5513  5560 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-25 14:25:39.518  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:39.521  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
10-25 14:25:39.522  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-25 14:25:39.522  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 14:25:39.522  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 14:25:39.522  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 14:25:39.523  5513  5560 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-25 14:25:39.523  5513  5560 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-25 14:25:39.523  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-25 14:25:39.523  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 14:25:39.523  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 14:25:39.523  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 14:25:39.523  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:39.524  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,10-25 14:25:39.526  5513  5560 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,10-25 14:25:39.527  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
10-25 14:25:39.529  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,10-25 14:25:39.529  5513  5560 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-25 14:25:39.529  5513  5560 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-25 14:25:39.529  5513  5560 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,10-25 14:25:39.529  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,10-25 14:25:39.529  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-25 14:25:39.529  5513  5560 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-25 14:25:39.529  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 14:25:39.529  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 14:25:39.530  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-25 14:25:39.530  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-25 14:25:39.531  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 14:25:39.531  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 14:25:39.531  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 14:25:39.531  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-25 14:25:39.531  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 14:25:39.531  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 14:25:39.531  5513  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-25 14:25:39.532  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-25 14:25:39.533  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-25 14:25:39.534  5513  5565 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 14:25:39.534  5513  5560 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 14:25:39.535  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-25 14:25:39.531  4746  4746 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31213]" dev="sockfs" ino=31213 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:39.531  4746  4746 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31213]" dev="sockfs" ino=31213 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:39.538  5513  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-25 14:25:39.542  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-25 14:25:39.546  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 14:25:39.547  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-25 14:25:39.552  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:39.552  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-25 14:25:39.553  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 14:25:39.553  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
10-25 14:25:39.555  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-25 14:25:39.555  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.555  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:39.555  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.556  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:39.557  5513  5560 D BluetoothAdapter: STATE_ON
,10-25 14:25:39.562  4518  4746 D BtGatt.GattService: registerClient() - UUID=f5ef9668-1527-4e99-9498-068628214d39
,10-25 14:25:39.563  4518  4595 D BtGatt.GattService: onClientRegistered() - UUID=f5ef9668-1527-4e99-9498-068628214d39, clientIf=5
,10-25 14:25:39.564  5513  5524 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-25 14:25:39.567  4518  4597 D BtGatt.AdvertiseManager: message : 0
,10-25 14:25:39.570  4518  4597 D BtGatt.AdvertiseManager: starting multi advertising
,10-25 14:25:39.590  4518  4595 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-25 14:25:39.602  4518  4595 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-25 14:25:39.604  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:39.605  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.605  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-25 14:25:39.605  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:39.605  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.605  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.606  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.606  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.606  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-25 14:25:39.608  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 14:25:39.608  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.609  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.609  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.609  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:39.610  5513  5560 I io.jxcore.node.ConnectionHelper: start: OK
10-25 14:25:39.610  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 14:25:39.611  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 14:25:39.611  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:39.611  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 14:25:39.611  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 14:25:39.611  5513  5513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:39.612  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 14:25:39.612  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-25 14:25:39.612  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 14:25:39.612  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 14:25:39.612  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-25 14:25:39.612  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-25 14:25:39.613  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-25 14:25:39.617  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-25 14:25:39.617  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 14:25:39.618  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,10-25 14:25:39.618  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-25 14:25:39.618  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 14:25:39.618  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:39.618  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-25 14:25:40.116  5513  5560 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-25 14:25:40.116  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-25 14:25:40.117  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-25 14:25:40.117  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-25 14:25:40.117  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-25 14:25:40.117  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-25 14:25:40.117  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-25 14:25:40.117  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-25 14:25:40.118  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-25 14:25:40.118  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-25 14:25:40.118  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-25 14:25:40.118  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-25 14:25:40.118  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-25 14:25:40.118  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-25 14:25:40.119  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,10-25 14:25:40.119  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-25 14:25:40.119  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-25 14:25:40.119  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-25 14:25:40.119  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-25 14:25:40.119  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-25 14:25:40.120  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-25 14:25:40.120  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,10-25 14:25:40.120  5513  5513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-25 14:25:40.120  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-25 14:25:40.120  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-25 14:25:40.120  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-25 14:25:40.120  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-25 14:25:40.120  5513  5513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-25 14:25:40.120  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,10-25 14:25:40.121  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-25 14:25:40.121  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-25 14:25:40.121  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-25 14:25:40.121  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-25 14:25:40.121  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-25 14:25:40.121  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,10-25 14:25:40.122  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-25 14:25:40.122  5513  5560 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-25 14:25:40.122  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 14:25:40.122  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 14:25:40.123  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-25 14:25:40.123  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 14:25:40.124  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 14:25:40.124  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-25 14:25:40.124  5513  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-25 14:25:40.124  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 14:25:40.124  5513  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-25 14:25:40.124  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-25 14:25:40.125  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-25 14:25:40.125  5513  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-25 14:25:40.125  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 14:25:40.125  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 14:25:40.126  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.126  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.129  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:25:40.130  5513  5560 D BluetoothLeScanner: could not find callback wrapper
10-25 14:25:40.130  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 14:25:40.130  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.132  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.133  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-25 14:25:40.133  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.135  4518  4597 D BtGatt.AdvertiseManager: message : 1
,10-25 14:25:40.136  4518  4597 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-25 14:25:40.149  4518  4595 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-25 14:25:40.149  4518  4595 D BtGatt.GattService: Client app is not null!
,10-25 14:25:40.151  4518  4746 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-25 14:25:40.152  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-25 14:25:40.152  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.152  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 14:25:40.152  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.152  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.152  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.152  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 14:25:40.152  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-25 14:25:40.153  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.153  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:40.153  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-25 14:25:40.153  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.156  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.156  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 14:25:40.156  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.156  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.156  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.156  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.156  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.156  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 14:25:40.156  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 14:25:40.157  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 14:25:40.158  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.159  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.159  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.159  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.159  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 14:25:40.159  5513  5513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-25 14:25:40.159  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-25 14:25:40.159  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 14:25:40.160  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:25:40.160  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:25:40.160  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 14:25:40.161  5513  5560 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-25 14:25:40.161  5513  5560 V io.jxcore.node.ConnectivityMonitor: start: Already started
,10-25 14:25:40.161  5513  5560 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
10-25 14:25:40.161  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
10-25 14:25:40.162  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 14:25:40.162  5513  5560 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-25 14:25:40.162  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 14:25:40.162  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 14:25:40.162  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-25 14:25:40.163  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-25 14:25:40.163  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 14:25:40.163  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 14:25:40.163  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 14:25:40.163  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-25 14:25:40.163  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-25 14:25:40.163  5513  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-25 14:25:40.163  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 14:25:40.163  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 14:25:40.164  5513  5568 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 14:25:40.164  4531  4531 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33012]" dev="sockfs" ino=33012 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:40.164  4531  4531 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33012]" dev="sockfs" ino=33012 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:40.167  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 14:25:40.168  5513  5560 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 14:25:40.168  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-25 14:25:40.168  5513  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-25 14:25:40.173  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 14:25:40.174  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 14:25:40.175  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 14:25:40.177  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.177  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-25 14:25:40.177  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 14:25:40.177  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
10-25 14:25:40.178  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-25 14:25:40.178  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.178  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.178  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.178  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.178  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:25:40.180  4518  4533 D BtGatt.GattService: registerClient() - UUID=e21dea24-3dfd-48c2-967b-16972ffc40b4
10-25 14:25:40.181  4518  4595 D BtGatt.GattService: onClientRegistered() - UUID=e21dea24-3dfd-48c2-967b-16972ffc40b4, clientIf=5
10-25 14:25:40.181  5513  5523 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-25 14:25:40.182  4518  4597 D BtGatt.AdvertiseManager: message : 0
10-25 14:25:40.184  4518  4597 D BtGatt.AdvertiseManager: starting multi advertising
10-25 14:25:40.195  4518  4595 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
10-25 14:25:40.202  4518  4595 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-25 14:25:40.202  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.202  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:40.202  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-25 14:25:40.202  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.202  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.202  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.203  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.203  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.203  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 14:25:40.204  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 14:25:40.204  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.205  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.205  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.206  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.206  5513  5560 I io.jxcore.node.ConnectionHelper: start: OK
10-25 14:25:40.206  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 14:25:40.206  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.206  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:40.206  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 14:25:40.206  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.206  5513  5513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:40.206  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.206  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-25 14:25:40.206  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 14:25:40.206  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.207  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.207  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-25 14:25:40.207  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.209  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.209  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 14:25:40.210  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.210  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.210  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.210  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:40.210  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-25 14:25:40.711  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
10-25 14:25:40.711  5513  5513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-25 14:25:40.711  5513  5560 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-25 14:25:40.711  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-25 14:25:40.712  5513  5560 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-25 14:25:40.712  5513  5513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-25 14:25:40.712  5513  5560 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
10-25 14:25:40.712  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,10-25 14:25:40.713  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-25 14:25:40.713  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-25 14:25:40.713  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-25 14:25:40.713  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
10-25 14:25:40.713  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-25 14:25:40.713  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-25 14:25:40.713  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-25 14:25:40.713  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-25 14:25:40.713  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-25 14:25:40.713  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.717  4518  4597 D BtGatt.AdvertiseManager: message : 1
,10-25 14:25:40.719  4518  4597 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-25 14:25:40.733  4518  4595 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-25 14:25:40.733  4518  4595 D BtGatt.GattService: Client app is not null!
10-25 14:25:40.734  4518  4746 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-25 14:25:40.735  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 14:25:40.735  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:40.735  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 14:25:40.735  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.735  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.735  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 14:25:40.735  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.735  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-25 14:25:40.736  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 14:25:40.736  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
10-25 14:25:40.736  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-25 14:25:40.736  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.736  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.736  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.736  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.738  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:25:40.741  4518  4531 D BtGatt.GattService: registerClient() - UUID=2125d50e-d913-40d8-8327-1bd5f0c6ee60
10-25 14:25:40.743  4518  4595 D BtGatt.GattService: onClientRegistered() - UUID=2125d50e-d913-40d8-8327-1bd5f0c6ee60, clientIf=5
10-25 14:25:40.744  5513  5524 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-25 14:25:40.745  4518  4597 D BtGatt.AdvertiseManager: message : 0
,10-25 14:25:40.749  4518  4597 D BtGatt.AdvertiseManager: starting multi advertising
,10-25 14:25:40.762  4518  4595 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-25 14:25:40.770  4518  4595 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-25 14:25:40.771  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.771  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.771  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.771  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-25 14:25:40.771  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.771  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.771  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:40.771  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.772  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.772  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 14:25:40.772  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,10-25 14:25:40.772  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 14:25:40.772  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 14:25:40.772  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.772  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-25 14:25:40.772  5513  5513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:40.772  5513  5560 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 14:25:40.772  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,10-25 14:25:40.772  5513  5560 I io.jxcore.node.ConnectionHelper: start: OK
10-25 14:25:40.772  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-25 14:25:40.772  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-25 14:25:40.772  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.772  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.773  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:40.774  5513  5560 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 14:25:40.774  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-25 14:25:40.774  5513  5560 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-25 14:25:40.774  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 14:25:40.774  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 14:25:40.774  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-25 14:25:40.775  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 14:25:40.775  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 14:25:40.775  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-25 14:25:40.775  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 14:25:40.775  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-25 14:25:40.775  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 14:25:40.775  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 14:25:40.775  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-25 14:25:40.775  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.775  5513  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-25 14:25:40.775  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.775  5513  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-25 14:25:40.775  5513  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-25 14:25:40.776  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:25:40.776  5513  5560 D BluetoothLeScanner: could not find callback wrapper
10-25 14:25:40.776  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 14:25:40.777  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.777  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.777  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-25 14:25:40.777  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:40.778  4518  4597 D BtGatt.AdvertiseManager: message : 1
,10-25 14:25:40.779  4518  4597 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-25 14:25:40.787  4518  4595 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-25 14:25:40.788  4518  4595 D BtGatt.GattService: Client app is not null!
,10-25 14:25:40.789  4518  4533 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-25 14:25:40.789  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 14:25:40.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 14:25:40.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.790  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 14:25:40.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-25 14:25:40.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:40.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.790  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-25 14:25:40.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.792  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.792  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 14:25:40.792  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.792  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.792  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.792  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.793  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.793  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 14:25:40.793  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 14:25:40.793  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-25 14:25:40.793  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:40.795  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.795  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.795  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:40.795  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 14:25:40.795  5513  5513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-25 14:25:40.796  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:25:40.796  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:25:40.796  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-25 14:25:40.796  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 14:25:40.796  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 14:25:40.797  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
10-25 14:25:40.798  5513  5560 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-25 14:25:40.799  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,10-25 14:25:40.799  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-25 14:25:40.800  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
10-25 14:25:40.800  5513  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-25 14:25:40.801  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
10-25 14:25:40.801  5513  5560 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,10-25 14:25:40.802  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
,10-25 14:25:40.802  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-25 14:25:40.803  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 14:25:40.803  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 14:25:40.803  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 14:25:40.803  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-25 14:25:40.803  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 14:25:40.803  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 14:25:40.803  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 14:25:40.803  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-25 14:25:40.803  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-25 14:25:40.803  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 14:25:40.803  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 14:25:40.804  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
10-25 14:25:40.805  5513  5560 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-25 14:25:40.805  5513  5560 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,10-25 14:25:40.809  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
10-25 14:25:40.809  5513  5560 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-25 14:25:40.811  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
10-25 14:25:40.811  5513  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-25 14:25:40.812  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
10-25 14:25:40.812  5513  5560 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
10-25 14:25:40.812  5513  5560 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-25 14:25:40.812  5513  5560 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-25 14:25:40.812  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-25 14:25:40.812  5513  5560 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,10-25 14:25:40.812  5513  5560 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,10-25 14:25:40.813  5513  5560 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-25 14:25:40.813  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-25 14:25:40.813  5513  5560 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-25 14:25:40.813  5513  5560 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-25 14:25:40.813  5513  5560 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-25 14:25:40.813  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-25 14:25:40.813  5513  5560 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-25 14:25:40.814  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
10-25 14:25:40.814  5513  5560 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-25 14:25:40.814  5513  5560 V io.jxcore.node.ConnectivityMonitor: start: Already started
,10-25 14:25:40.814  5513  5560 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,10-25 14:25:40.814  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
10-25 14:25:40.814  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 14:25:40.815  5513  5560 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-25 14:25:40.815  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 14:25:40.815  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 14:25:40.816  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-25 14:25:40.817  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-25 14:25:40.817  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 14:25:40.817  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 14:25:40.817  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 14:25:40.817  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-25 14:25:40.817  5513  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-25 14:25:40.817  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,10-25 14:25:40.817  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 14:25:40.818  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 14:25:40.818  5513  5572 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 14:25:40.817  4531  4531 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33022]" dev="sockfs" ino=33022 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:40.817  4531  4531 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33022]" dev="sockfs" ino=33022 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:40.821  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 14:25:40.821  5513  5560 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 14:25:40.821  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-25 14:25:40.822  5513  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-25 14:25:40.825  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 14:25:40.826  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 14:25:40.826  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 14:25:40.829  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.829  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-25 14:25:40.829  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 14:25:40.829  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
10-25 14:25:40.829  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-25 14:25:40.829  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.830  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.830  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.830  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.831  5513  5560 D BluetoothAdapter: STATE_ON
,10-25 14:25:40.834  4518  4533 D BtGatt.GattService: registerClient() - UUID=473c4168-59e5-4a3f-9e0c-9e53cf69e521
10-25 14:25:40.834  4518  4595 D BtGatt.GattService: onClientRegistered() - UUID=473c4168-59e5-4a3f-9e0c-9e53cf69e521, clientIf=5
10-25 14:25:40.835  5513  5524 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-25 14:25:40.836  4518  4597 D BtGatt.AdvertiseManager: message : 0
10-25 14:25:40.839  4518  4597 D BtGatt.AdvertiseManager: starting multi advertising
,10-25 14:25:40.850  4518  4595 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-25 14:25:40.857  4518  4595 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-25 14:25:40.858  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.858  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.858  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-25 14:25:40.858  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.858  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.858  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.858  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.858  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.858  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-25 14:25:40.859  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 14:25:40.860  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:40.861  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:40.861  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.861  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:40.861  5513  5560 I io.jxcore.node.ConnectionHelper: start: OK
10-25 14:25:40.861  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 14:25:40.861  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.862  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:40.862  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 14:25:40.862  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.862  5513  5513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:40.862  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.862  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-25 14:25:40.862  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-25 14:25:40.862  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.862  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.862  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-25 14:25:40.862  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.864  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.865  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 14:25:40.865  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.865  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.865  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 14:25:40.865  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:40.865  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-25 14:25:41.363  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-25 14:25:41.364  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 14:25:41.364  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-25 14:25:41.364  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-25 14:25:41.365  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 14:25:41.365  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-25 14:25:41.365  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-25 14:25:41.365  5513  5572 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-25 14:25:41.366  5513  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-25 14:25:41.366  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 14:25:41.366  5513  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-25 14:25:41.366  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34136d removed from the list
10-25 14:25:41.366  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 14:25:41.366  5513  5513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-25 14:25:41.366  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 14:25:41.366  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 14:25:41.366  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-25 14:25:41.367  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-25 14:25:41.367  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-25 14:25:41.367  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.367  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-25 14:25:41.367  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.370  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:25:41.370  5513  5560 D BluetoothLeScanner: could not find callback wrapper
,10-25 14:25:41.370  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 14:25:41.371  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:41.371  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.371  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-25 14:25:41.371  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:41.374  4518  4597 D BtGatt.AdvertiseManager: message : 1
10-25 14:25:41.375  4518  4597 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-25 14:25:41.392  4518  4595 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-25 14:25:41.393  4518  4595 D BtGatt.GattService: Client app is not null!
,10-25 14:25:41.395  4518  4533 D BtGatt.GattService: unregisterClient() - clientIf=5
10-25 14:25:41.397  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 14:25:41.397  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.397  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 14:25:41.397  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:41.398  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.398  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.398  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 14:25:41.398  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-25 14:25:41.398  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.398  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.399  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-25 14:25:41.399  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:41.403  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.403  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 14:25:41.403  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.403  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.403  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.403  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.403  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.404  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 14:25:41.404  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-25 14:25:41.405  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 14:25:41.405  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:41.409  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.409  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:41.409  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:41.409  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@765aba2 removed from the list
10-25 14:25:41.409  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:25:41.409  5513  5560 D io.jxcore.node.ConnectivityMonitor: stop
10-25 14:25:41.409  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 14:25:41.409  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:25:41.409  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 14:25:41.911  5513  5513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 14:25:46.413  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,10-25 14:25:46.418  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-25 14:25:46.418  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 14:25:46.421  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-25 14:25:46.422  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-25 14:25:46.422  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 14:25:46.422  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 14:25:46.422  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 14:25:46.424  4531  4531 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[30509]" dev="sockfs" ino=30509 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:46.423  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-25 14:25:46.423  5513  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-25 14:25:46.423  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-25 14:25:46.425  5513  5573 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 14:25:46.425  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,10-25 14:25:46.427  5513  5560 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-25 14:25:46.428  5513  5560 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-25 14:25:46.428  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-25 14:25:46.428  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 14:25:46.428  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 14:25:46.432  5513  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-25 14:25:46.430  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
10-25 14:25:46.427  4531  4531 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[30509]" dev="sockfs" ino=30509 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-25 14:25:46.449  5513  5560 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,10-25 14:25:46.450  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 14:25:46.450  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 14:25:46.450  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 14:25:46.450  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-25 14:25:46.451  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 14:25:46.451  5513  5573 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-25 14:25:46.451  5513  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-25 14:25:46.451  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 14:25:46.451  5513  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-25 14:25:46.451  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-25 14:25:46.451  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-25 14:25:46.452  5513  5560 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34136d not in the list
,10-25 14:25:46.452  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 14:25:46.452  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-25 14:25:46.452  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 14:25:46.452  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-25 14:25:46.452  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-25 14:25:46.452  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 14:25:46.453  5513  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 14:25:46.453  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 14:25:46.453  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:46.458  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:46.458  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 14:25:46.458  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:46.459  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:46.459  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:25:46.460  5513  5560 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@765aba2 not in the list
10-25 14:25:46.460  5513  5560 D io.jxcore.node.ConnectivityMonitor: stop
10-25 14:25:46.460  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:25:46.460  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 14:25:46.460  5513  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 14:25:46.460  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 14:25:46.462  5513  5560 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
10-25 14:25:46.463  5513  5560 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-25 14:25:46.463  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-25 14:25:46.463  5513  5560 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-25 14:25:46.463  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-25 14:25:46.463  5513  5560 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-25 14:25:46.463  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-25 14:25:46.464  5513  5560 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
10-25 14:25:46.466  5513  5560 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,10-25 14:25:46.469  5513  5560 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,10-25 14:25:46.470  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-25 14:25:46.470  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,10-25 14:25:46.472  5513  5560 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
10-25 14:25:46.472  5513  5560 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-25 14:25:46.473  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-25 14:25:46.473  5513  5560 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-25 14:25:46.473  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-25 14:25:46.473  5513  5560 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,10-25 14:25:46.473  5513  5560 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-25 14:25:46.474  5513  5560 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,10-25 14:25:46.476  5513  5560 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-25 14:25:46.476  5513  5560 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,10-25 14:25:46.477  5513  5560 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,10-25 14:25:46.478  5513  5560 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-25 14:25:46.478  5513  5560 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-25 14:25:46.478  5513  5560 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-25 14:25:46.478  5513  5560 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-25 14:25:46.479  5513  5560 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
10-25 14:25:46.479  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-25 14:25:46.479  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a744152 added. We now have 3 listener(s)
,10-25 14:25:46.481  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 14:25:46.481  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 14:25:46.481  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 14:25:46.482  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 14:25:46.482  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d2fc23 added. We now have 3 listener(s)
,10-25 14:25:46.482  5513  5560 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 14:25:46.483  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-25 14:25:46.487  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 14:25:46.493  5513  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 14:25:46.493  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:46.493  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:46.493  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:46.493  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:46.493  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:46.493  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 14:25:46.493  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 14:25:46.495  5513  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:46.496  5513  5560 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-25 14:25:46.498  5513  5560 D BluetoothAdapter: enable(): BT is already enabled..!
10-25 14:25:46.498   926  3040 D WifiService: setWifiEnabled: true pid=5513, uid=10077
10-25 14:25:46.498   926  3040 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-25 14:25:46.499  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:46.500  5513  5560 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
10-25 14:25:46.503  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:46.504  5513  5560 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,10-25 14:25:46.505  5513  5560 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,10-25 14:25:46.509   926  3639 D WifiService: setWifiEnabled: false pid=5513, uid=10077
,10-25 14:25:46.509   926  3639 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 14:25:46.514   926  2829 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-25 14:25:46.514   926  2829 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-25 14:25:46.514   926  2829 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-25 14:25:46.514   926  2829 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 14:25:46.524   926  5268 D DhcpClient: Clearing IP address
,10-25 14:25:46.524   506   920 D CommandListener: Clearing all IP addresses on wlan0
,10-25 14:25:46.531   506   920 D CommandListener: Setting iface cfg
,10-25 14:25:46.539  3458  5322 V NativeCrypto: Read error: ssl=0x7f797cb180: I/O error during system call, Connection timed out
,10-25 14:25:46.542  3458  5322 V NativeCrypto: SSL shutdown failed: ssl=0x7f797cb180: I/O error during system call, Broken pipe
,10-25 14:25:46.545   926   936 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,10-25 14:25:46.546   926  5264 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-25 14:25:46.547   926  2831 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-25 14:25:46.548   926  2831 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-25 14:25:46.548   926  5264 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-25 14:25:46.552   535   535 E Parcel  : Reading a NULL string not supported here.
10-25 14:25:46.553   926   926 D RttService: SCAN_AVAILABLE : 1
,10-25 14:25:46.554   926  2938 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-25 14:25:46.558   926  2831 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-25 14:25:46.559   926  3647 I ActivityManager: Killing 5309:com.android.chrome/u0a39 (adj 15): empty #17
10-25 14:25:46.560  3596  3716 W QCNEJ   : |CORE| network lost: 100
10-25 14:25:46.561   926  5269 D DhcpClient: Receive thread stopped
10-25 14:25:46.561  3596  3716 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-25 14:25:46.561   926  2829 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-25 14:25:46.592   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 14:25:46.599   926  2829 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-25 14:25:46.610   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 14:25:46.611   506   920 D CommandListener: Clearing all IP addresses on wlan0
10-25 14:25:46.611   926  2831 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-25 14:25:46.611   926  2831 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-25 14:25:46.612   506   920 D TetherController: Setting IP forward enable = 0
,10-25 14:25:46.614   926   943 D Tethering: MasterInitialState.processMessage what=3
10-25 14:25:46.615  5153  5153 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a9cf6c1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,10-25 14:25:46.617   926  2829 D DhcpClient: doQuit
10-25 14:25:46.617   926  2829 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-25 14:25:46.617   926  5268 D DhcpClient: onQuitting
10-25 14:25:46.618  3799  3799 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-25 14:25:46.618  3321  3321 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-25 14:25:46.621  4936  4960 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-25 14:25:46.621  4936  4960 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-25 14:25:46.621  4936  4960 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-25 14:25:46.622  4936  4960 E SarControlService: no key has been found,reset the power
10-25 14:25:46.622  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:46.622  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:46.622  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:46.622  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:46.622  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:46.622  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:46.622  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:46.622  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:46.625  4936  4972 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-25 14:25:46.625  4936  4972 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-25 14:25:46.625  4936  4972 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-25 14:25:46.625  4961  4961 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 14:25:46.626  4961  4961 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-25 14:25:46.624  3821  3821 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-25 14:25:46.628  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:46.629  4936  4972 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-25 14:25:46.629  4936  4972 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-25 14:25:46.629  4936  4972 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-25 14:25:46.630  4961  4961 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 14:25:46.630  4961  4961 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-25 14:25:46.631  4961  4975 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@247bef HexData = [00000000ea03000000000000ffffffff]
,10-25 14:25:46.631  4961  4975 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 14:25:46.631  4961  4975 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-25 14:25:46.632  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:46.632  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:46.632  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:46.632  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 14:25:46.632  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:46.632  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:46.632  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:46.632  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 14:25:46.634  4961  4961 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-25 14:25:46.634  4936  4947 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-25 14:25:46.634  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:46.638  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:46.638  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:46.638  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:46.638  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 14:25:46.638  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:46.638  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:46.638  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:46.638  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 14:25:46.639  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:46.640  3821  3821 D SystemUpdateService: onCreate
10-25 14:25:46.643  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:46.643  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:46.643  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:46.643  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 14:25:46.643  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:46.643  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:46.643  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:46.643  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 14:25:46.644  3321  3321 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-25 14:25:46.644  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:46.646  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:46.647  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:46.648  3321  3321 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-25 14:25:46.649   506   913 W SocketClient: write error (Broken pipe)
10-25 14:25:46.649   506   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
,10-25 14:25:46.650   506   913 W SocketListener: Error sending broadcast (Broken pipe)
10-25 14:25:46.650  4961  4975 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@247bef HexData = [00000000eb03000000000000ffffffff]
10-25 14:25:46.651  4961  4975 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 14:25:46.651  4961  4975 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-25 14:25:46.651  4961  4961 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 14:25:46.652  4936  4946 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-25 14:25:46.652  3821  3821 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-25 14:25:46.656  3821  5592 I SystemUpdateService: active receiver: enabled
,10-25 14:25:46.660  3821  3821 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-25 14:25:46.666  3821  5293 I iu.UploadsManager: num queued entries: 0
,10-25 14:25:46.666  3821  5293 I iu.UploadsManager: num updated entries: 0
,10-25 14:25:46.668  3821  5592 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-25 14:25:46.670  3821  3821 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-25 14:25:46.672  3821  3821 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-25 14:25:46.667  3821  5293 I iu.SyncManager: NEXT; no task
10-25 14:25:46.674  3821  5592 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-25 14:25:46.674  3821  5592 I SystemUpdateService: now status is 0 (complete)
10-25 14:25:46.674  3821  5592 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-25 14:25:46.674  3821  5592 I SystemUpdateService: file has been verified
10-25 14:25:46.674  3821  5592 I SystemUpdateService: OTA package size = 21989297
10-25 14:25:46.675   506   920 E Netd    : netlink response contains error (No such file or directory)
10-25 14:25:46.676   926  2831 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-25 14:25:46.679  3821  5592 I SystemUpdateService: showing system update notification
,10-25 14:25:46.685   926  3044 I ActivityManager: Start proc 5595:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-25 14:25:46.687  3321  3321 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-25 14:25:46.697   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
10-25 14:25:46.698  3821  3821 D SystemUpdateService: onDestroy
,10-25 14:25:46.701  3321  3321 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-25 14:25:46.717  5595  5595 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-25 14:25:46.720  5595  5595 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-25 14:25:46.727  5595  5595 D SprintDMHelper: simOperator: 
,10-25 14:25:46.727  5595  5595 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-25 14:25:46.740   926  3040 I ActivityManager: Start proc 5607:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
10-25 14:25:46.741   926  3040 I ActivityManager: Killing 4328:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-25 14:25:46.805   926  2829 D wifi    : In wifi stop Hal
,10-25 14:25:46.805   926  2829 D wifi    : halHandle = 0x7f77f2fe00, mVM = 0x7f9458d140, mCls = 0x100a02
10-25 14:25:46.806   926  3319 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-25 14:25:46.806   926  3319 D WifiHAL : Got a signal to exit!!!
10-25 14:25:46.806   926  3319 I WifiHAL : Exit wifi_event_loop
10-25 14:25:46.807  4871  4871 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-25 14:25:46.807   926  2829 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-25 14:25:46.807   926  2829 E WifiHAL : Event processing terminated
10-25 14:25:46.807   926  2829 D wifi    : In wifi cleaned up handler
10-25 14:25:46.807   926  2829 I WifiHAL : Internal cleanup completed
,10-25 14:25:46.809  3978  4098 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-25 14:25:46.810  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:46.812  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:46.813  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:46.829   926  3319 D wifi    : set interface wlan0 flags (DOWN)
,10-25 14:25:46.829   926  2829 D WifiNative-HAL: HAL event thread stopped successfully
,10-25 14:25:46.832  4871  5621 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-25 14:25:46.844   926  3647 I ActivityManager: Start proc 5622:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-25 14:25:46.845   926  3647 I ActivityManager: Killing 5016:com.google.android.deskclock/u0a66 (adj 15): empty #17
,10-25 14:25:46.881  5622  5622 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-25 14:25:46.887   926  3647 I ActivityManager: Killing 5344:com.qualcomm.timeservice/1000 (adj 15): empty #17
,10-25 14:25:46.960  5513  5513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 14:25:47.018  5513  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:47.023   926  3647 D WifiService: setWifiEnabled: true pid=5513, uid=10077
10-25 14:25:47.023   926  3647 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 14:25:47.033   506   920 D SoftapController: Softap fwReload - Ok
,10-25 14:25:47.035   926   943 D Tethering: InitialState.processMessage what=4
,10-25 14:25:47.036   506   920 D CommandListener: Setting iface cfg
10-25 14:25:47.037   506   920 D CommandListener: Trying to bring down wlan0
10-25 14:25:47.038   506   920 D CommandListener: Clearing all IP addresses on wlan0
,10-25 14:25:47.041   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-25 14:25:47.041   926  2829 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-25 14:25:47.529   926  3044 D WifiService: setWifiEnabled: true pid=5513, uid=10077
10-25 14:25:47.532   926  3044 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 14:25:47.630   926  2829 D wifi    : set interface wlan0 flags (UP)
10-25 14:25:47.631   926  2829 I WifiHAL : Initializing wifi
10-25 14:25:47.631   926  2829 I WifiHAL : Creating socket
,10-25 14:25:47.637   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-25 14:25:47.642   926  2829 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-25 14:25:47.643   926  2829 D wifi    : Did set static halHandle = 0x7f77f2fe00
10-25 14:25:47.643   926  2829 D wifi    : halHandle = 0x7f77f2fe00, mVM = 0x7f9458d140, mCls = 0x1606
,10-25 14:25:47.644   926  2829 D wifi    : array field set
10-25 14:25:47.645   926  2829 I WifiNative-HAL: interface[0] = wlan0
,10-25 14:25:47.648   926  5637 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547473260032
,10-25 14:25:47.648   926  5637 D wifi    : waitForHalEvents called, vm = 0x7f9458d140, obj = 0x1606, env = 0x7f7592ad80
,10-25 14:25:47.685   506   920 D TetherController: Setting IP forward enable = 0
,10-25 14:25:47.721  5638  5638 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-25 14:25:47.751   926  2829 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-25 14:25:47.755  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:47.757  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:47.758  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:47.788  5638  5638 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-25 14:25:47.843  5638  5638 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-25 14:25:47.843  5638  5638 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-25 14:25:47.872   926  2829 D WifiConfigStore: Loading config and enabling all networks 
,10-25 14:25:47.882  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:47.882  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:47.882  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:47.882  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:47.882  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:47.882  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:47.882  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:47.882  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:47.887  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:47.894  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:47.894  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:47.894  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:47.894  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:47.894  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:47.894  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:47.894  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:47.894  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 14:25:47.896  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:47.902  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:47.902  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:47.902  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:47.902  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:47.902  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:47.902  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:47.902  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:47.902  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:47.904  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:47.906   926  2829 D WifiConfigStore: loaded 0 passpoint configs
,10-25 14:25:47.907   926  2829 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
10-25 14:25:47.907   926  2829 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-25 14:25:47.908   926  2829 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-25 14:25:47.909   926  2829 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-25 14:25:47.909   926  2829 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
10-25 14:25:47.910   926  2829 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-25 14:25:47.911   926  2829 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-25 14:25:47.911   926  2829 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
10-25 14:25:47.911   926  2829 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-25 14:25:47.911   926  2829 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-25 14:25:47.911   926  2829 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-25 14:25:47.911   926  2829 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-25 14:25:47.914   926  2829 D WifiNative-HAL: Setting external_sim to 1
,10-25 14:25:47.914  4871  4871 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 14:25:47.915   926  2829 D wifi    : setting dfs flag to true, 0x7f7d159be0
,10-25 14:25:47.915   926  2829 D WifiStateMachine: Setting OUI to DA-A1-19
10-25 14:25:47.916   926  2829 D wifi    : setting scan oui 0x7f7d159be0
10-25 14:25:47.916   926  2829 D WifiHAL : Sending mac address OUI
,10-25 14:25:47.920   926  2829 E native  : do suspend false
,10-25 14:25:47.928   926  2829 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-25 14:25:47.928   926   926 D RttService: SCAN_AVAILABLE : 3
10-25 14:25:47.928   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-25 14:25:47.928   926  2938 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-25 14:25:47.929   506   920 D CommandListener: Setting iface cfg
,10-25 14:25:47.933   926  2828 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,10-25 14:25:47.933   926  2828 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-25 14:25:47.944   926  2828 D WifiNative-HAL: p2pGetDeviceAddress
,10-25 14:25:47.949   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=110718 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-25 14:25:47.950   926  2828 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-25 14:25:48.037  5513  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:48.050  4518  4591 D BluetoothAdapterState: Current state: ON, message: 23
,10-25 14:25:48.050  4518  4591 D BluetoothAdapterProperties: Setting state to 13
,10-25 14:25:48.050  4518  4591 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-25 14:25:48.051  4518  4591 D BluetoothAdapterProperties: onBluetoothDisable()
10-25 14:25:48.054  4518  4518 D BluetoothMapService: onReceive
10-25 14:25:48.054  4518  4518 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-25 14:25:48.054  4518  4591 I BluetoothAdapterState: Entering PendingCommandState
10-25 14:25:48.054  4518  4518 D BluetoothMapService: STATE_TURNING_OFF
10-25 14:25:48.055  4518  4518 D BluetoothMapService: MAP Service closeService in
,10-25 14:25:48.055  4518  4518 D BluetoothMapMasInstance0: MAP Service shutdown
,10-25 14:25:48.055  4518  4518 D ObexServerSockets0: shutdown(block = true)
10-25 14:25:48.056  4518  4757 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-25 14:25:48.056  4518  4518 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 14:25:48.057  4518  4758 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-25 14:25:48.058  4518  4518 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 14:25:48.058  4518  4744 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-25 14:25:48.065  5513  5513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 14:25:48.065  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:48.065  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:48.065  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:48.065  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:48.065  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 14:25:48.065  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:48.065  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:48.065  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 14:25:48.066  5513  5513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 14:25:48.067  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:48.071  5513  5513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 14:25:48.071  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:48.071  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:48.071  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:48.071  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:48.071  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 14:25:48.071  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:48.071  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:48.071  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:48.072  5513  5513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 14:25:48.073  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:48.077  5513  5513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 14:25:48.077  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:48.077  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:48.077  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:48.077  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:48.077  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 14:25:48.077  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:48.077  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:48.077  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:48.078   926   939 I ActivityManager: Start proc 5647:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-25 14:25:48.078  5513  5513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 14:25:48.078  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:48.079  4518  4518 I BtOppRfcommListener: stopping Accept Thread
10-25 14:25:48.079  4518  5200 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-25 14:25:48.079  4518  5200 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-25 14:25:48.081  4518  4595 D BluetoothAdapterProperties: Scan Mode:20
,10-25 14:25:48.081  4518  4591 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-25 14:25:48.084  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:48.085  4518  4518 D HeadsetService: Received stop request...Stopping profile...
10-25 14:25:48.086  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:48.088  3626  3860 D BluetoothHeadset: Proxy object disconnected
10-25 14:25:48.089  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:48.089   926   926 D BluetoothHeadset: Proxy object disconnected
10-25 14:25:48.089  4518  4518 D A2dpService: Received stop request...Stopping profile...
10-25 14:25:48.089   926   926 D BluetoothHeadset: Proxy object disconnected
10-25 14:25:48.089  4518  4749 D A2dpStateMachine: Exit Disconnected: -1
10-25 14:25:48.089  2984  3874 D BluetoothHeadset: Proxy object disconnected
10-25 14:25:48.090   926   926 D BluetoothHeadset: Proxy object disconnected
,10-25 14:25:48.090  2984  2984 D HeadsetProfile: Bluetooth service disconnected
,10-25 14:25:48.093   926   926 D BluetoothA2dp: Proxy object disconnected
10-25 14:25:48.093  2984  2984 D BluetoothA2dp: Proxy object disconnected
,10-25 14:25:48.095  4518  4518 D HidService: Received stop request...Stopping profile...
10-25 14:25:48.096  4518  4518 D HidService: Stopping Bluetooth HidService
10-25 14:25:48.098  2984  2984 D BluetoothInputDevice: Proxy object disconnected
,10-25 14:25:48.098  2984  2984 D HidProfile: Bluetooth service disconnected
,10-25 14:25:48.098  4518  4518 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:48.098  4518  4518 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:48.098  4518  4518 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:48.098  4518  4518 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:48.100  4518  4518 D HealthService: Received stop request...Stopping profile...
10-25 14:25:48.104  4518  4518 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-25 14:25:48.104  4518  4518 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-25 14:25:48.104  4518  4595 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-25 14:25:48.104  4518  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:48.104  4518  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:48.104  4518  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:48.105  4518  4595 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-25 14:25:48.105  4518  4518 D PanService: Received stop request...Stopping profile...
,10-25 14:25:48.106  2984  2984 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-25 14:25:48.106  2984  2984 D PanProfile: Bluetooth service disconnected
10-25 14:25:48.106  4518  4518 D BluetoothMapService: Received stop request...Stopping profile...
10-25 14:25:48.107  4518  4518 D BluetoothMapService: stop()
,10-25 14:25:48.107  4518  4518 D BluetoothMapAppObserver: deinitObservers()
10-25 14:25:48.108  4518  4518 D BluetoothMapAppObserver: removeReceiver()
10-25 14:25:48.110  2984  2984 D BluetoothMap: Proxy object disconnected
10-25 14:25:48.110  2984  2984 D MapProfile: Bluetooth service disconnected
10-25 14:25:48.110  4518  4518 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:48.110  4518  4518 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:48.110  4518  4518 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:48.110  4518  4518 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:48.112  4518  4518 D SapService: Received stop request...Stopping profile...
10-25 14:25:48.112  4518  4518 V SapService: stop()
10-25 14:25:48.114  4518  4595 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-25 14:25:48.114  4518  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:48.114  4518  4518 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:48.114  4518  4518 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:48.114  4518  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:48.114  4518  4518 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:48.115  4518  4518 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:48.115  4518  4728 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-25 14:25:48.115  4518  4728 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-25 14:25:48.115  4518  4728 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-25 14:25:48.115  4518  4728 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-25 14:25:48.115  4518  4518 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-25 14:25:48.115  4518  4518 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-25 14:25:48.115  4518  4595 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-25 14:25:48.115  4518  4518 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:48.115  4518  4518 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:48.115  4518  4518 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:48.115  4518  4518 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:48.115  4518  4518 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-25 14:25:48.116  4518  4518 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-25 14:25:48.116  4518  4518 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:48.116  4518  4518 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:48.116  4518  4518 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:48.116  4518  4518 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:48.116  4518  4518 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-25 14:25:48.117  4518  4518 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-25 14:25:48.117  4518  4595 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-25 14:25:48.119  4518  4518 D BluetoothMapService: MAP Service closeService in
10-25 14:25:48.119  4518  4518 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:48.119  4518  4518 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:48.119  4518  4518 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:48.119  4518  4518 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:48.119  4518  4518 D BluetoothMapService: cleanup()
10-25 14:25:48.119  4518  4518 D BluetoothMapService: MAP Service closeService in
10-25 14:25:48.119  4518  4518 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:48.119  4518  4518 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:48.119  4518  4518 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:48.119  4518  4518 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:48.120  4518  4591 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-25 14:25:48.120  4518  4591 D BluetoothAdapterProperties: Setting state to 15
10-25 14:25:48.120  4518  4591 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-25 14:25:48.120   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 14:25:48.121  2984  2999 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 14:25:48.121  2984  3873 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-25 14:25:48.121   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 14:25:48.122   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 14:25:48.122  2984  3874 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 14:25:48.122  2984  3002 D BluetoothMap: onBluetoothStateChange: up=false
10-25 14:25:48.123  2984  2999 D BluetoothPan: onBluetoothStateChange on: false
10-25 14:25:48.123  3626  3640 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 14:25:48.124  4518  4591 I BluetoothAdapterState: Entering BleOnState
10-25 14:25:48.124   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 14:25:48.124  2984  3873 D BluetoothPbap: onBluetoothStateChange: up=false
10-25 14:25:48.125  4518  4591 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-25 14:25:48.125  4518  4591 D BluetoothAdapterProperties: Setting state to 16
10-25 14:25:48.125  4518  4591 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-25 14:25:48.126  4518  4591 D BluetoothAdapterProperties: onBleDisable
10-25 14:25:48.126  4518  4591 I BluetoothAdapterState: Entering PendingCommandState
10-25 14:25:48.126  4518  4592 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-25 14:25:48.127  4518  4595 D BluetoothAdapterProperties: Scan Mode:20
10-25 14:25:48.128  4518  4728 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-25 14:25:48.128  4518  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:48.130  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:48.132  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:48.133  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:48.135  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:48.136  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:48.137  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:48.147  5647  5647 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-25 14:25:48.158  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-25 14:25:48.164   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a97ed3d:true
,10-25 14:25:48.164  3458  3458 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 14:25:48.177   926   936 I ActivityManager: Start proc 5659:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-25 14:25:48.189  5647  5647 D LocalBluetoothProfileManager: Adding local MAP profile
,10-25 14:25:48.192  5647  5647 D BluetoothMap: Create BluetoothMap proxy object
,10-25 14:25:48.205  5647  5647 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-25 14:25:48.218  5659  5659 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-25 14:25:48.221  5647  5647 D DockEventReceiver: finishStartingService: stopping service
,10-25 14:25:48.230   926  3286 I ActivityManager: Killing 5153:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-25 14:25:48.336  4518  4595 I bt_hci  : shut_down
,10-25 14:25:48.341  4518  4599 D bt_hwcfg: hw_epilog_process
,10-25 14:25:48.341  4518  4599 I bt_vendor: low_power_mode_cb
10-25 14:25:48.343  4518  4599 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-25 14:25:48.343  4518  4599 I bt_vendor: epilog_cb
10-25 14:25:48.343  4518  4599 I bt_hci  : epilog_finished_callback
,10-25 14:25:48.346  4518  4595 I bt_hci_h4: hal_close
,10-25 14:25:48.346  4518  4595 I bt_userial_vendor: device fd = 54 close
,10-25 14:25:48.422  5659  5659 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.io.File.exists(File.java:361)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-25 14:25:48.422  5659  5659 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 14:25:48.422  5659  5659 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 14:25:48.422  5659  5659 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.e.b(PG:170)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 14:25:48.422  5659  5659 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.k.d(PG:583)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.e.b(PG:170)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 14:25:48.422  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 14:25:48.423  5659  5659 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at java.io.File.exists(File.java:361)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 14:25:48.423  5659  5659 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at java.io.File.exists(File.java:361)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 14:25:48.423  5659  5659 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 14:25:48.423  5659  5659 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 14:25:48.429  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-25 14:25:48.435  3458  3458 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 14:25:48.447  5647  5647 D DockEventReceiver: finishStartingService: stopping service
10-25 14:25:48.449   926  3044 I ActivityManager: Killing 3725:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-25 14:25:48.486  4518  4592 D bt_stack_manager: event_shut_down_stack finished.
10-25 14:25:48.486  4518  4591 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-25 14:25:48.489  4518  4518 D BtGatt.DebugUtils: handleDebugAction() action=null
10-25 14:25:48.489  4518  4591 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-25 14:25:48.489  4518  4518 D BtGatt.GattService: Received stop request...Stopping profile...
10-25 14:25:48.489  4518  4518 D BtGatt.GattService: stop()
10-25 14:25:48.489  4518  4518 D BtGatt.AdvertiseManager: advertise clients cleared
10-25 14:25:48.491  4518  4518 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:48.491  4518  4518 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:48.491  4518  4518 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:48.491  4518  4518 V BluetoothAdapterState: isBleTurningOff()=true
10-25 14:25:48.491  4518  4591 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-25 14:25:48.491  4518  4591 D BluetoothAdapterProperties: Setting state to 10
10-25 14:25:48.491  4518  4591 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-25 14:25:48.493  4518  4591 I BluetoothAdapterState: Entering OffState
10-25 14:25:48.493   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-25 14:25:48.499  4518  4518 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-25 14:25:48.499  4518  4518 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-25 14:25:48.499  4518  4518 I BluetoothServiceJni: cleanupNative: return from cleanup
10-25 14:25:48.501  4518  4592 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-25 14:25:48.508  4518  4518 I art     : System.exit called, status: 0
,10-25 14:25:48.509  4518  4518 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-25 14:25:48.545   926  3290 I ActivityManager: Process com.android.bluetooth (pid 4518) has died
,10-25 14:25:48.549  5513  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:48.562   926   943 I ActivityManager: Start proc 5691:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-25 14:25:48.618  5691  5691 D AdapterServiceConfig: Adding HeadsetService
,10-25 14:25:48.618  5691  5691 D AdapterServiceConfig: Adding A2dpService
10-25 14:25:48.619  5691  5691 D AdapterServiceConfig: Adding HidService
10-25 14:25:48.619  5691  5691 D AdapterServiceConfig: Adding HealthService
10-25 14:25:48.619  5691  5691 D AdapterServiceConfig: Adding PanService
10-25 14:25:48.619  5691  5691 D AdapterServiceConfig: Adding GattService
,10-25 14:25:48.619  5691  5691 D AdapterServiceConfig: Adding BluetoothMapService
10-25 14:25:48.619  5691  5691 D AdapterServiceConfig: Adding SapService
,10-25 14:25:48.626   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@796ec3a:true
,10-25 14:25:48.626  5691  5691 D BluetoothAdapterState: make() - Creating AdapterState
,10-25 14:25:48.628  5691  5691 I bt_bluedroid: init
,10-25 14:25:48.628  5691  5703 I BluetoothAdapterState: Entering OffState
,10-25 14:25:48.630  5691  5704 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-25 14:25:48.630  5691  5704 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-25 14:25:48.630  5691  5704 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-25 14:25:48.630  5691  5704 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-25 14:25:48.631  5691  5691 I bt_bluedroid: get_profile_interface socket
,10-25 14:25:48.632  5691  5691 I bt_bluedroid: get_profile_interface sdp
,10-25 14:25:48.632  5691  5707 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-25 14:25:48.633  5691  5707 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-25 14:25:48.635  5691  5702 I bt_bluedroid: config_hci_snoop_log
,10-25 14:25:48.635   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,10-25 14:25:48.638  5691  5703 D BluetoothAdapterState: Current state: OFF, message: 0
,10-25 14:25:48.638  5691  5703 D BluetoothAdapterProperties: Setting state to 14
10-25 14:25:48.638  5691  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-25 14:25:48.639  5691  5703 D BluetoothBondStateMachine: make
10-25 14:25:48.641  5691  5708 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-25 14:25:48.643  5691  5703 I BluetoothAdapterState: Entering PendingCommandState
,10-25 14:25:48.643  5691  5691 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-25 14:25:48.645  5691  5691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
,10-25 14:25:48.645  5691  5691 D BtGatt.DebugUtils: handleDebugAction() action=null
10-25 14:25:48.645  5691  5691 D BtGatt.GattService: Received start request. Starting profile...
10-25 14:25:48.645  5691  5691 D BtGatt.GattService: start()
,10-25 14:25:48.645  5691  5691 I bt_bluedroid: get_profile_interface gatt
10-25 14:25:48.646  5691  5691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
10-25 14:25:48.646  5691  5691 D BtGatt.AdvertiseManager: advertise manager created
,10-25 14:25:48.649  5691  5691 V BluetoothAdapterState: isTurningOff()=false
,10-25 14:25:48.649  5691  5691 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:48.649  5691  5691 V BluetoothAdapterState: isBleTurningOn()=true
10-25 14:25:48.649  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 14:25:48.649  5691  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-25 14:25:48.650  5691  5703 I bt_bluedroid: bt_bluedroid
,10-25 14:25:48.650  5691  5704 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-25 14:25:48.650  5691  5704 I bt_hci  : start_up
,10-25 14:25:48.655  5691  5704 I bt_vendor: alloc value 0xf3f13871
,10-25 14:25:48.655  5691  5704 I bt_vendor: init
10-25 14:25:48.655  5691  5704 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-25 14:25:48.655  5691  5704 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-25 14:25:48.670  5659  5683 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-25 14:25:48.678   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@801263:true
,10-25 14:25:48.764  5691  5704 D bt_hci  : start_up starting async portion
10-25 14:25:48.764  5691  5711 I bt_hci  : event_finish_startup
10-25 14:25:48.764  5691  5711 I bt_hci_h4: hal_open
10-25 14:25:48.764  5691  5711 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-25 14:25:48.765  5691  5711 I bt_userial_vendor: device fd = 54 open
,10-25 14:25:48.761  5714  5714 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 14:25:48.777  5691  5711 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-25 14:25:48.779  5691  5711 D bt_hwcfg: Chipset BCM4358A3
,10-25 14:25:48.779  5691  5711 D bt_hwcfg: Target name = [BCM4358A3]
10-25 14:25:48.779  5691  5711 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-25 14:25:49.059  5691  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-25 14:25:49.172  5691  5711 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-25 14:25:49.173  5691  5711 D bt_hwcfg: Settlement delay -- 100 ms
,10-25 14:25:49.173  5691  5711 I bt_hwcfg: Setting fw settlement delay to 100 
,10-25 14:25:49.295  5691  5711 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-25 14:25:49.296  5691  5711 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,10-25 14:25:49.297  5691  5711 I bt_hwcfg: vendor lib fwcfg completed
,10-25 14:25:49.297  5691  5711 I bt_vendor: firmware callback
,10-25 14:25:49.297  5691  5711 I bt_hci  : firmware_config_callback
,10-25 14:25:49.306  5691  5716 I bt_btu  : btu_task pending for preload complete event
,10-25 14:25:49.306  5691  5716 I bt_btu_task: Bluetooth chip preload is complete
10-25 14:25:49.306  5691  5716 I bt_btu  : btu_task received preload complete event
,10-25 14:25:49.314  5691  5716 I         : BTE_InitTraceLevels -- TRC_HCI
,10-25 14:25:49.314  5691  5716 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-25 14:25:49.314  5691  5716 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-25 14:25:49.314  5691  5716 I         : BTE_InitTraceLevels -- TRC_AVDT
10-25 14:25:49.315  5691  5716 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-25 14:25:49.315  5691  5716 I         : BTE_InitTraceLevels -- TRC_A2D
10-25 14:25:49.315  5691  5716 I         : BTE_InitTraceLevels -- TRC_BNEP
10-25 14:25:49.315  5691  5716 I         : BTE_InitTraceLevels -- TRC_BTM
,10-25 14:25:49.315  5691  5716 I         : BTE_InitTraceLevels -- TRC_GAP
10-25 14:25:49.315  5691  5716 I         : BTE_InitTraceLevels -- TRC_PAN
10-25 14:25:49.315  5691  5716 I         : BTE_InitTraceLevels -- TRC_SDP
10-25 14:25:49.315  5691  5716 I         : BTE_InitTraceLevels -- TRC_GATT
,10-25 14:25:49.315  5691  5716 I         : BTE_InitTraceLevels -- TRC_SMP
10-25 14:25:49.316  5691  5716 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-25 14:25:49.316  5691  5716 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-25 14:25:49.400  5691  5716 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e91549
,10-25 14:25:49.400  5691  5716 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e91549 
,10-25 14:25:49.423  5691  5707 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-25 14:25:49.425  5691  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-25 14:25:49.425  5691  5707 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-25 14:25:49.427  5691  5707 D BluetoothAdapterProperties: Name is: Nexus 6P
10-25 14:25:49.429  5691  5707 D BluetoothAdapterProperties: Scan Mode:20
10-25 14:25:49.430  5691  5707 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-25 14:25:49.430  5691  5707 D bt_hci  : do_postload posting postload work item
10-25 14:25:49.430  5691  5711 I bt_hci  : event_postload
,10-25 14:25:49.430  5691  5711 I bt_vendor: sco_config_cb
,10-25 14:25:49.430  5691  5711 I bt_hci  : sco_config_callback postload finished.
10-25 14:25:49.432  5691  5707 D bt_bte_conf: Device ID record 1 : primary
10-25 14:25:49.432  5691  5707 D bt_bte_conf:   vendorId            = 000f
10-25 14:25:49.432  5691  5707 D bt_bte_conf:   vendorIdSource      = 0001
10-25 14:25:49.433  5691  5707 D bt_bte_conf:   product             = 1200
10-25 14:25:49.433  5691  5707 D bt_bte_conf:   version             = 1436
10-25 14:25:49.433  5691  5707 D bt_bte_conf:   clientExecutableURL = 
,10-25 14:25:49.433  5691  5707 D bt_bte_conf:   serviceDescription  = 
10-25 14:25:49.433  5691  5707 D bt_bte_conf:   documentationURL    = 
10-25 14:25:49.433  5691  5707 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-25 14:25:49.433  5691  5704 D bt_stack_manager: event_start_up_stack finished
10-25 14:25:49.434  5691  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-25 14:25:49.434  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.435  5691  5703 D BluetoothAdapterProperties: Setting state to 15
10-25 14:25:49.435  5691  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-25 14:25:49.436  5691  5703 I BluetoothAdapterState: Entering BleOnState
,10-25 14:25:49.439  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.443  5691  5711 I bt_vendor: low_power_mode_cb
10-25 14:25:49.443  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:49.444  5691  5703 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-25 14:25:49.444  5691  5703 D BluetoothAdapterProperties: Setting state to 11
10-25 14:25:49.444  5691  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-25 14:25:49.448  5691  5691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
,10-25 14:25:49.449  5691  5691 D HeadsetService: Received start request. Starting profile...
,10-25 14:25:49.451  5691  5691 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-25 14:25:49.451  5691  5691 D HeadsetStateMachine: make
,10-25 14:25:49.455  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:49.456  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.460  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:49.461  5691  5691 D HeadsetStateMachine: max_hf_connections = 1
,10-25 14:25:49.461  5691  5691 I bt_bluedroid: get_profile_interface handsfree
10-25 14:25:49.462  5691  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-25 14:25:49.462  5691  5707 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-25 14:25:49.465  5691  5691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
10-25 14:25:49.465  5691  5691 D A2dpService: Received start request. Starting profile...
10-25 14:25:49.466  5691  5691 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-25 14:25:49.466  5691  5691 I bt_bluedroid: get_profile_interface avrcp
10-25 14:25:49.467  5691  5703 I BluetoothAdapterState: Entering PendingCommandState
,10-25 14:25:49.472  5691  5691 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-25 14:25:49.472  5691  5691 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-25 14:25:49.472  5691  5691 D A2dpStateMachine: make
,10-25 14:25:49.473  5691  5691 I bt_bluedroid: get_profile_interface a2dp
,10-25 14:25:49.475  5691  5725 D A2dpStateMachine: Enter Disconnected: -2
10-25 14:25:49.476  5691  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-25 14:25:49.476  5691  5691 I BluetoothHidServiceJni: classInitNative: succeeds
,10-25 14:25:49.477  5691  5691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
,10-25 14:25:49.478  5647  5647 D BluetoothInputDevice: Proxy object connected
,10-25 14:25:49.479  5647  5647 D HidProfile: Bluetooth service connected
,10-25 14:25:49.480  5691  5691 D HidService: Received start request. Starting profile...
,10-25 14:25:49.480  5691  5691 I bt_bluedroid: get_profile_interface hidhost
10-25 14:25:49.481  5691  5707 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e7256d
10-25 14:25:49.481  5691  5691 D HidService: setHidService(): set to: null
10-25 14:25:49.481  5691  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-25 14:25:49.483  5691  5691 I BluetoothHealthServiceJni: classInitNative: succeeds
10-25 14:25:49.483  5691  5691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
,10-25 14:25:49.484  5691  5691 D HealthService: Received start request. Starting profile...
,10-25 14:25:49.485  5691  5691 I bt_bluedroid: get_profile_interface health
,10-25 14:25:49.487  5691  5691 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-25 14:25:49.487  5691  5691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
10-25 14:25:49.487  3458  3458 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 14:25:49.490  5691  5691 D PanService: Received start request. Starting profile...
,10-25 14:25:49.491  5691  5691 D BluetoothPanServiceJni: initializeNative(L110): pan
10-25 14:25:49.491  5691  5691 I bt_bluedroid: get_profile_interface pan
10-25 14:25:49.492  5691  5707 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-25 14:25:49.493  5691  5691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
10-25 14:25:49.494  5647  5647 D BluetoothPan: BluetoothPAN Proxy object connected
,10-25 14:25:49.494  5691  5691 D BluetoothMapService: Received start request. Starting profile...
10-25 14:25:49.494  5691  5691 D BluetoothMapService: start()
,10-25 14:25:49.498  5691  5691 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-25 14:25:49.500  5647  5647 D PanProfile: Bluetooth service connected
10-25 14:25:49.500  5647  5647 D BluetoothMap: Proxy object connected
10-25 14:25:49.500  5647  5647 D MapProfile: Bluetooth service connected
10-25 14:25:49.500  5647  5647 D BluetoothMap: getConnectedDevices()
10-25 14:25:49.500  5691  5691 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-25 14:25:49.501  5691  5691 D BluetoothMapAppObserver: createReceiver()
10-25 14:25:49.501  5647  5647 D BluetoothMap: Bluetooth is Not enabled
10-25 14:25:49.502  5691  5691 D BluetoothMapAppObserver: initObservers()
,10-25 14:25:49.502  5691  5691 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-25 14:25:49.508  5691  5691 V BluetoothAdapterState: isTurningOff()=false
,10-25 14:25:49.509  5691  5691 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:49.509  5691  5723 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
10-25 14:25:49.509  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.509  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 14:25:49.510  5691  5691 V SapService: SapBinder()
10-25 14:25:49.510  5691  5691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
,10-25 14:25:49.511  5691  5691 D SapService: Received start request. Starting profile...
10-25 14:25:49.511  5691  5691 V SapService: start()
,10-25 14:25:49.512  5691  5691 V BluetoothAdapterState: isTurningOff()=false
,10-25 14:25:49.512  5691  5691 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:49.512  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.512  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.513  5691  5691 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:49.513  5691  5691 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:49.513  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.513  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 14:25:49.513  5691  5691 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:49.513  5691  5691 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:49.513  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.513  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.514  5691  5691 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:49.514  5691  5691 V BluetoothAdapterState: isTurningOn()=true
,10-25 14:25:49.514  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.514  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.514  5691  5691 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:49.515  5691  5691 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:49.515  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.515  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.516  5691  5691 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:49.516  5691  5691 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:49.516  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.516  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.516  5691  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-25 14:25:49.516  5691  5703 D BluetoothAdapterProperties: ScanMode =  20
10-25 14:25:49.516  5691  5703 D BluetoothAdapterProperties: State =  11
,10-25 14:25:49.518  5691  5707 D BluetoothAdapterProperties: Scan Mode:21
10-25 14:25:49.518  5691  5703 D BluetoothAdapterProperties: Setting state to 12
10-25 14:25:49.518  5691  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-25 14:25:49.518  5691  5707 D BluetoothAdapterProperties: Discoverable Timeout:120
10-25 14:25:49.518  5691  5703 I BluetoothAdapterState: Entering OnState
10-25 14:25:49.519  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-25 14:25:49.519   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-25 14:25:49.520  2984  2999 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 14:25:49.521   926   926 D BluetoothA2dp: Proxy object connected
10-25 14:25:49.521  5513  5513 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-25 14:25:49.522  5647  5657 D BluetoothMap: onBluetoothStateChange: up=true
10-25 14:25:49.522  2984  3002 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-25 14:25:49.524  5513  5513 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,10-25 14:25:49.526  2984  2984 D BluetoothInputDevice: Proxy object connected
,10-25 14:25:49.526  2984  2984 D HidProfile: Bluetooth service connected
10-25 14:25:49.527  5647  5658 D BluetoothPan: onBluetoothStateChange on: true
10-25 14:25:49.527   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 14:25:49.527  5647  5657 D BluetoothPbap: onBluetoothStateChange: up=true
10-25 14:25:49.528  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:49.528  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:49.528  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:49.528  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:49.528  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:49.528  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:49.528  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:49.528  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:49.529  5691  5691 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-25 14:25:49.529   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-25 14:25:49.530  2984  3873 D BluetoothA2dp: onBluetoothStateChange: up=true
10-25 14:25:49.530  5691  5691 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-25 14:25:49.531  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:49.531  5691  5691 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 14:25:49.532  2984  2984 D BluetoothA2dp: Proxy object connected
10-25 14:25:49.532  2984  3002 D BluetoothMap: onBluetoothStateChange: up=true
10-25 14:25:49.534  2984  2999 D BluetoothPan: onBluetoothStateChange on: true
10-25 14:25:49.534  2984  2984 D BluetoothMap: Proxy object connected
10-25 14:25:49.534  2984  2984 D MapProfile: Bluetooth service connected
10-25 14:25:49.534  2984  2984 D BluetoothMap: getConnectedDevices()
10-25 14:25:49.535  5691  5691 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 14:25:49.536  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:49.536  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:49.536  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:49.536  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:49.536  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:49.536  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:49.536  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:49.536  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:49.536  3626  3640 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-25 14:25:49.537  5691  5691 D ObexServerSockets: Succeed to create listening sockets 
10-25 14:25:49.537  5691  5691 D ObexServerSockets0: startAccept()
10-25 14:25:49.537  5691  5691 D ObexServerSockets0: prepareForNewConnect()
,10-25 14:25:49.537  2984  2984 D BluetoothPan: BluetoothPAN Proxy object connected
,10-25 14:25:49.538  2984  2984 D PanProfile: Bluetooth service connected
10-25 14:25:49.538  5647  5658 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-25 14:25:49.538   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 14:25:49.539  2984  3874 D BluetoothPbap: onBluetoothStateChange: up=true
10-25 14:25:49.539  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:49.542   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
10-25 14:25:49.542  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:49.542  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:49.542  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:49.542  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:49.542  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:49.542  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:49.542  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:49.542  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:49.544  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:49.544  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-25 14:25:49.545  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.546  5691  5691 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-25 14:25:49.546  5691  5691 D BluetoothSdpJni: SDP Create record success - handle: 0
10-25 14:25:49.546  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.547  5691  5730 D ObexServerSockets0: Accepting socket connection...
10-25 14:25:49.547  5691  5691 D BluetoothMapService: onReceive
10-25 14:25:49.547  5691  5691 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-25 14:25:49.547  5691  5691 D BluetoothMapService: STATE_ON
10-25 14:25:49.547  5691  5731 D ObexServerSockets0: Accepting socket connection...
10-25 14:25:49.548  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:49.549  5647  5647 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-25 14:25:49.549  5691  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 14:25:49.552  5691  5733 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-25 14:25:49.552  5691  5733 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-25 14:25:49.554  5647  5647 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-25 14:25:49.560  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-25 14:25:49.561  5513  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:49.562  5647  5647 D BluetoothA2dp: Proxy object connected
10-25 14:25:49.562  5513  5560 D io.jxcore.node.ConnectivityMonitor: stop
10-25 14:25:49.562  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 14:25:49.566  3458  3458 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 14:25:49.567  5513  5560 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,10-25 14:25:49.568  5647  5647 D DockEventReceiver: finishStartingService: stopping service
10-25 14:25:49.569  5513  5560 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,10-25 14:25:49.571  5513  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:49.572  5691  5703 D BluetoothAdapterState: Current state: ON, message: 23
10-25 14:25:49.572  5691  5703 D BluetoothAdapterProperties: Setting state to 13
,10-25 14:25:49.572  5691  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-25 14:25:49.573  5691  5703 D BluetoothAdapterProperties: onBluetoothDisable()
10-25 14:25:49.573  5691  5703 I BluetoothAdapterState: Entering PendingCommandState
,10-25 14:25:49.576  5691  5707 D BluetoothAdapterProperties: Scan Mode:20
,10-25 14:25:49.576  5691  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-25 14:25:49.577  2984  2984 D BluetoothPbap: Proxy object connected
10-25 14:25:49.577  5647  5647 D BluetoothPbap: Proxy object connected
10-25 14:25:49.577  2984  2984 D PbapServerProfile: Bluetooth service connected
10-25 14:25:49.578  5647  5647 D PbapServerProfile: Bluetooth service connected
10-25 14:25:49.579  5513  5513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 14:25:49.580  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:49.580  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:49.580  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:49.580  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:49.580  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 14:25:49.580  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:49.580  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:49.580  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 14:25:49.580  5513  5513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 14:25:49.580  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:49.583  5513  5513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 14:25:49.583  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:49.583  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:49.583  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:49.583  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:49.583  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 14:25:49.583  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:49.583  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:49.583  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 14:25:49.583  5513  5513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 14:25:49.583  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:49.584  5691  5691 D BluetoothMapService: onReceive
,10-25 14:25:49.584  5691  5691 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-25 14:25:49.584  5691  5691 D BluetoothMapService: STATE_TURNING_OFF
,10-25 14:25:49.584  5691  5691 D HeadsetService: Received stop request...Stopping profile...
10-25 14:25:49.586  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.587  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.588  5691  5691 D A2dpService: Received stop request...Stopping profile...
10-25 14:25:49.588  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-25 14:25:49.588  5691  5725 D A2dpStateMachine: Exit Disconnected: -1
10-25 14:25:49.590   926   926 D BluetoothA2dp: Proxy object disconnected
,10-25 14:25:49.595  5647  5647 D DockEventReceiver: finishStartingService: stopping service
10-25 14:25:49.596  5647  5647 D BluetoothA2dp: Proxy object disconnected
10-25 14:25:49.596  2984  2984 D BluetoothA2dp: Proxy object disconnected
,10-25 14:25:49.602  5691  5691 D HidService: Received stop request...Stopping profile...
10-25 14:25:49.602  5691  5691 D HidService: Stopping Bluetooth HidService
,10-25 14:25:49.603  2984  2984 D BluetoothInputDevice: Proxy object disconnected
10-25 14:25:49.603  2984  2984 D HidProfile: Bluetooth service disconnected
,10-25 14:25:49.603  5691  5691 D HealthService: Received stop request...Stopping profile...
,10-25 14:25:49.604  5647  5647 D BluetoothInputDevice: Proxy object disconnected
10-25 14:25:49.604  5647  5647 D HidProfile: Bluetooth service disconnected
10-25 14:25:49.605  5691  5691 D PanService: Received stop request...Stopping profile...
10-25 14:25:49.605  2984  2984 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-25 14:25:49.605  2984  2984 D PanProfile: Bluetooth service disconnected
10-25 14:25:49.606  5647  5647 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-25 14:25:49.606  5647  5647 D PanProfile: Bluetooth service disconnected
10-25 14:25:49.606  5691  5691 D BluetoothMapService: Received stop request...Stopping profile...
10-25 14:25:49.606  5691  5691 D BluetoothMapService: stop()
,10-25 14:25:49.606  5691  5691 D BluetoothMapAppObserver: deinitObservers()
,10-25 14:25:49.606  5691  5691 D BluetoothMapAppObserver: removeReceiver()
10-25 14:25:49.608  2984  2984 D BluetoothMap: Proxy object disconnected
10-25 14:25:49.608  5647  5647 D BluetoothMap: Proxy object disconnected
,10-25 14:25:49.608  5647  5647 D MapProfile: Bluetooth service disconnected
10-25 14:25:49.608  2984  2984 D MapProfile: Bluetooth service disconnected
10-25 14:25:49.608  5691  5691 D SapService: Received stop request...Stopping profile...
10-25 14:25:49.608  5691  5691 V SapService: stop()
,10-25 14:25:49.610  5691  5691 V BluetoothAdapterState: isTurningOff()=true
,10-25 14:25:49.610  5691  5691 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:49.610  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.610  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 14:25:49.612  5691  5691 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-25 14:25:49.612  5691  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,10-25 14:25:49.612  5691  5716 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:49.612  5691  5716 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:49.612  5691  5716 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:49.612  5691  5691 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-25 14:25:49.612  5691  5707 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
10-25 14:25:49.612  5691  5691 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:49.612  5691  5691 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:49.613  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.613  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.614  5691  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-25 14:25:49.614  5691  5716 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:49.614  5691  5716 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:49.614  5691  5716 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-25 14:25:49.614  5691  5716 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-25 14:25:49.614  5691  5716 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-25 14:25:49.614  5691  5716 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-25 14:25:49.615  5691  5691 V BluetoothAdapterState: isTurningOff()=true
,10-25 14:25:49.615  5691  5691 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:49.615  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.616  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.616  5691  5691 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-25 14:25:49.616  5691  5691 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-25 14:25:49.616  5691  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-25 14:25:49.616  5691  5691 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:49.616  5691  5691 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:49.616  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.616  3458  3458 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 14:25:49.616  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.617  5691  5691 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-25 14:25:49.617  5691  5707 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-25 14:25:49.617  5691  5691 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-25 14:25:49.617  5691  5691 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:49.618  5691  5691 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:49.618  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.618  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.618  5691  5691 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-25 14:25:49.618  5691  5691 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-25 14:25:49.619  5691  5691 D BluetoothMapService: MAP Service closeService in
10-25 14:25:49.619  5691  5691 D BluetoothMapMasInstance0: MAP Service shutdown
10-25 14:25:49.619  5691  5691 D ObexServerSockets0: shutdown(block = true)
10-25 14:25:49.620  5691  5730 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-25 14:25:49.620  5691  5691 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 14:25:49.620  5691  5691 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 14:25:49.620  5691  5731 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-25 14:25:49.620  5691  5691 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:49.621  5691  5691 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:49.621  5691  5718 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-25 14:25:49.621  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.621  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.621  5691  5691 D BluetoothMapService: cleanup()
10-25 14:25:49.621  5691  5691 D BluetoothMapService: MAP Service closeService in
10-25 14:25:49.621  5691  5691 V BluetoothAdapterState: isTurningOff()=true
10-25 14:25:49.622  5691  5691 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:49.622  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.622  5691  5691 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:49.622  5691  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-25 14:25:49.622  5691  5703 D BluetoothAdapterProperties: Setting state to 15
10-25 14:25:49.622  5691  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,10-25 14:25:49.623   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 14:25:49.623  2984  3873 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 14:25:49.623  5691  5703 I BluetoothAdapterState: Entering BleOnState
10-25 14:25:49.623  5647  5658 D BluetoothMap: onBluetoothStateChange: up=false
10-25 14:25:49.624  2984  3874 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-25 14:25:49.625  2984  2984 D BluetoothPbap: Proxy object disconnected
10-25 14:25:49.625  2984  2984 D PbapServerProfile: Bluetooth service disconnected
10-25 14:25:49.625  5647  5647 D BluetoothPbap: Proxy object disconnected
10-25 14:25:49.625  5647  5647 D PbapServerProfile: Bluetooth service disconnected
10-25 14:25:49.626  5647  5657 D BluetoothPan: onBluetoothStateChange on: false
,10-25 14:25:49.627   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 14:25:49.627  5647  5658 D BluetoothPbap: onBluetoothStateChange: up=false
10-25 14:25:49.628  5647  5657 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 14:25:49.628   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 14:25:49.628  2984  2999 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 14:25:49.629  2984  3002 D BluetoothMap: onBluetoothStateChange: up=false
10-25 14:25:49.629  2984  3873 D BluetoothPan: onBluetoothStateChange on: false
10-25 14:25:49.630  5647  5658 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 14:25:49.630  3626  3876 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 14:25:49.631  5647  5657 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-25 14:25:49.631   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-25 14:25:49.631  2984  3874 D BluetoothPbap: onBluetoothStateChange: up=false
10-25 14:25:49.632  5691  5703 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-25 14:25:49.632  5691  5703 D BluetoothAdapterProperties: Setting state to 16
10-25 14:25:49.632  5691  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-25 14:25:49.632  5691  5703 D BluetoothAdapterProperties: onBleDisable
10-25 14:25:49.633  5691  5703 I BluetoothAdapterState: Entering PendingCommandState
10-25 14:25:49.633  5691  5704 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-25 14:25:49.633  5691  5716 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-25 14:25:49.634  5691  5716 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 14:25:49.634  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.636  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.636  5691  5707 D BluetoothAdapterProperties: Scan Mode:20
10-25 14:25:49.638  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.638  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-25 14:25:49.639  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:49.642  3458  3458 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 14:25:49.645  5647  5647 D DockEventReceiver: finishStartingService: stopping service
,10-25 14:25:49.834  5691  5707 I bt_hci  : shut_down
,10-25 14:25:49.835  5691  5711 D bt_hwcfg: hw_epilog_process
,10-25 14:25:49.836  5691  5711 I bt_vendor: low_power_mode_cb
,10-25 14:25:49.839  5691  5711 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-25 14:25:49.839  5691  5711 I bt_vendor: epilog_cb
,10-25 14:25:49.839  5691  5711 I bt_hci  : epilog_finished_callback
10-25 14:25:49.841  5691  5707 I bt_hci_h4: hal_close
10-25 14:25:49.841  5691  5707 I bt_userial_vendor: device fd = 54 close
,10-25 14:25:49.966  5691  5704 D bt_stack_manager: event_shut_down_stack finished.
,10-25 14:25:49.967  5691  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-25 14:25:49.970  5691  5703 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-25 14:25:49.970  5691  5691 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-25 14:25:49.971  5691  5691 D BtGatt.GattService: Received stop request...Stopping profile...
10-25 14:25:49.971  5691  5691 D BtGatt.GattService: stop()
,10-25 14:25:49.971  5691  5691 D BtGatt.AdvertiseManager: advertise clients cleared
,10-25 14:25:49.974  5691  5691 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:49.974  5691  5691 V BluetoothAdapterState: isTurningOn()=false
,10-25 14:25:49.974  5691  5691 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:49.974  5691  5691 V BluetoothAdapterState: isBleTurningOff()=true
10-25 14:25:49.975  5691  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-25 14:25:49.975  5691  5703 D BluetoothAdapterProperties: Setting state to 10
10-25 14:25:49.975  5691  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-25 14:25:49.976  5691  5703 I BluetoothAdapterState: Entering OffState
,10-25 14:25:49.977   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-25 14:25:49.988  5691  5691 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-25 14:25:49.988  5691  5691 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-25 14:25:49.988  5691  5691 I BluetoothServiceJni: cleanupNative: return from cleanup
10-25 14:25:49.990  5691  5704 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-25 14:25:49.997  5691  5691 I art     : System.exit called, status: 0
,10-25 14:25:49.997  5691  5691 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-25 14:25:50.026   926  3290 I ActivityManager: Process com.android.bluetooth (pid 5691) has died
,10-25 14:25:50.077  5513  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 14:25:50.078  5513  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:50.078  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:50.078  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:50.078  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:50.078  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 14:25:50.078  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:50.078  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:50.078  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:50.078  5513  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 14:25:50.078  5513  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:50.084  5513  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:50.105   926   943 I ActivityManager: Start proc 5745:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-25 14:25:50.186  5745  5745 D AdapterServiceConfig: Adding HeadsetService
,10-25 14:25:50.187  5745  5745 D AdapterServiceConfig: Adding A2dpService
10-25 14:25:50.187  5745  5745 D AdapterServiceConfig: Adding HidService
10-25 14:25:50.187  5745  5745 D AdapterServiceConfig: Adding HealthService
10-25 14:25:50.187  5745  5745 D AdapterServiceConfig: Adding PanService
,10-25 14:25:50.187  5745  5745 D AdapterServiceConfig: Adding GattService
10-25 14:25:50.188  5745  5745 D AdapterServiceConfig: Adding BluetoothMapService
10-25 14:25:50.188  5745  5745 D AdapterServiceConfig: Adding SapService
,10-25 14:25:50.199   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3405a23:true
,10-25 14:25:50.199  5745  5745 D BluetoothAdapterState: make() - Creating AdapterState
,10-25 14:25:50.202  5745  5745 I bt_bluedroid: init
,10-25 14:25:50.202  5745  5757 I BluetoothAdapterState: Entering OffState
,10-25 14:25:50.204  5745  5758 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-25 14:25:50.204  5745  5758 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-25 14:25:50.204  5745  5758 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-25 14:25:50.204  5745  5758 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-25 14:25:50.205  5745  5745 I bt_bluedroid: get_profile_interface socket
,10-25 14:25:50.206  5745  5761 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
10-25 14:25:50.207  5745  5745 I bt_bluedroid: get_profile_interface sdp
,10-25 14:25:50.208  5745  5761 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-25 14:25:50.211  5745  5756 I bt_bluedroid: config_hci_snoop_log
,10-25 14:25:50.212   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-25 14:25:50.216  5745  5757 D BluetoothAdapterState: Current state: OFF, message: 0
10-25 14:25:50.216  5745  5757 D BluetoothAdapterProperties: Setting state to 14
10-25 14:25:50.216  5745  5757 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-25 14:25:50.217  5745  5757 D BluetoothBondStateMachine: make
,10-25 14:25:50.219  5745  5762 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-25 14:25:50.222  5745  5757 I BluetoothAdapterState: Entering PendingCommandState
,10-25 14:25:50.222  5745  5745 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-25 14:25:50.225  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
10-25 14:25:50.225  5745  5745 D BtGatt.DebugUtils: handleDebugAction() action=null
10-25 14:25:50.226  5745  5745 D BtGatt.GattService: Received start request. Starting profile...
10-25 14:25:50.226  5745  5745 D BtGatt.GattService: start()
10-25 14:25:50.226  5745  5745 I bt_bluedroid: get_profile_interface gatt
10-25 14:25:50.227  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
10-25 14:25:50.227  5745  5745 D BtGatt.AdvertiseManager: advertise manager created
,10-25 14:25:50.232  5745  5745 V BluetoothAdapterState: isTurningOff()=false
,10-25 14:25:50.232  5745  5745 V BluetoothAdapterState: isTurningOn()=false
10-25 14:25:50.232  5745  5745 V BluetoothAdapterState: isBleTurningOn()=true
10-25 14:25:50.232  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:50.232  5745  5757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-25 14:25:50.233  5745  5757 I bt_bluedroid: bt_bluedroid
10-25 14:25:50.234  5745  5758 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-25 14:25:50.234  5745  5758 I bt_hci  : start_up
,10-25 14:25:50.239  5745  5758 I bt_vendor: alloc value 0xf3f13871,
10-25 14:25:50.239  5745  5758 I bt_vendor: init
10-25 14:25:50.239  5745  5758 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-25 14:25:50.239  5745  5758 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-25 14:25:50.351  5745  5758 D bt_hci  : start_up starting async portion
,10-25 14:25:50.351  5745  5765 I bt_hci  : event_finish_startup
10-25 14:25:50.351  5745  5765 I bt_hci_h4: hal_open
,10-25 14:25:50.351  5745  5765 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-25 14:25:50.347  5766  5766 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-25 14:25:50.355  5745  5765 I bt_userial_vendor: device fd = 54 open
,10-25 14:25:50.369  5745  5765 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-25 14:25:50.372  5745  5765 D bt_hwcfg: Chipset BCM4358A3
,10-25 14:25:50.372  5745  5765 D bt_hwcfg: Target name = [BCM4358A3]
10-25 14:25:50.373  5745  5765 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-25 14:25:50.523   541   541 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-25 14:25:50.523   541   541 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-25 14:25:50.588  5745  5757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-25 14:25:50.783  5745  5765 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-25 14:25:50.784  5745  5765 D bt_hwcfg: Settlement delay -- 100 ms
,10-25 14:25:50.784  5745  5765 I bt_hwcfg: Setting fw settlement delay to 100 
,10-25 14:25:50.907  5745  5765 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-25 14:25:50.907  5745  5765 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,10-25 14:25:50.910  5745  5765 I bt_hwcfg: vendor lib fwcfg completed
,10-25 14:25:50.910  5745  5765 I bt_vendor: firmware callback
,10-25 14:25:50.910  5745  5765 I bt_hci  : firmware_config_callback
,10-25 14:25:50.920  5745  5768 I bt_btu  : btu_task pending for preload complete event
,10-25 14:25:50.920  5745  5768 I bt_btu_task: Bluetooth chip preload is complete
,10-25 14:25:50.920  5745  5768 I bt_btu  : btu_task received preload complete event
,10-25 14:25:50.927  5745  5768 I         : BTE_InitTraceLevels -- TRC_HCI
,10-25 14:25:50.928  5745  5768 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-25 14:25:50.928  5745  5768 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-25 14:25:50.928  5745  5768 I         : BTE_InitTraceLevels -- TRC_AVDT
10-25 14:25:50.928  5745  5768 I         : BTE_InitTraceLevels -- TRC_AVRC
10-25 14:25:50.928  5745  5768 I         : BTE_InitTraceLevels -- TRC_A2D
10-25 14:25:50.928  5745  5768 I         : BTE_InitTraceLevels -- TRC_BNEP
10-25 14:25:50.928  5745  5768 I         : BTE_InitTraceLevels -- TRC_BTM
10-25 14:25:50.929  5745  5768 I         : BTE_InitTraceLevels -- TRC_GAP
10-25 14:25:50.929  5745  5768 I         : BTE_InitTraceLevels -- TRC_PAN
10-25 14:25:50.929  5745  5768 I         : BTE_InitTraceLevels -- TRC_SDP
10-25 14:25:50.929  5745  5768 I         : BTE_InitTraceLevels -- TRC_GATT
10-25 14:25:50.929  5745  5768 I         : BTE_InitTraceLevels -- TRC_SMP
10-25 14:25:50.929  5745  5768 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-25 14:25:50.929  5745  5768 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-25 14:25:50.997  5638  5638 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 14:25:51.017  5745  5768 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e91549
,10-25 14:25:51.017  5745  5768 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e91549 
,10-25 14:25:51.026  5638  5638 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 14:25:51.034  5745  5761 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-25 14:25:51.036  5745  5761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-25 14:25:51.036  5638  5638 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 14:25:51.037  5745  5761 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-25 14:25:51.039  5745  5761 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-25 14:25:51.041  5745  5761 D BluetoothAdapterProperties: Scan Mode:20
10-25 14:25:51.043  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:51.044  5745  5761 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-25 14:25:51.044  5745  5761 D bt_hci  : do_postload posting postload work item
10-25 14:25:51.045  5745  5765 I bt_hci  : event_postload
10-25 14:25:51.045  5745  5765 I bt_vendor: sco_config_cb
,10-25 14:25:51.045  5745  5765 I bt_hci  : sco_config_callback postload finished.
10-25 14:25:51.046  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:51.047  5745  5761 D bt_bte_conf: Device ID record 1 : primary
10-25 14:25:51.047  5745  5761 D bt_bte_conf:   vendorId            = 000f
10-25 14:25:51.047  5745  5761 D bt_bte_conf:   vendorIdSource      = 0001
10-25 14:25:51.047  5745  5761 D bt_bte_conf:   product             = 1200
10-25 14:25:51.048  5745  5761 D bt_bte_conf:   version             = 1436
10-25 14:25:51.048  5745  5761 D bt_bte_conf:   clientExecutableURL = 
10-25 14:25:51.048  5745  5761 D bt_bte_conf:   serviceDescription  = 
10-25 14:25:51.048  5745  5761 D bt_bte_conf:   documentationURL    = 
10-25 14:25:51.048  5745  5761 D bt_bte_conf: bte_load_did_conf no section named DID2.
,10-25 14:25:51.048  5745  5758 D bt_stack_manager: event_start_up_stack finished
10-25 14:25:51.050  5745  5757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-25 14:25:51.051  5745  5757 D BluetoothAdapterProperties: Setting state to 15
10-25 14:25:51.051  5745  5757 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-25 14:25:51.051  5745  5757 I BluetoothAdapterState: Entering BleOnState
,10-25 14:25:51.054  5745  5757 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-25 14:25:51.054  5745  5757 D BluetoothAdapterProperties: Setting state to 11
10-25 14:25:51.054  5745  5757 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-25 14:25:51.057  5745  5765 I bt_vendor: low_power_mode_cb
10-25 14:25:51.059  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
,10-25 14:25:51.062  5745  5745 D HeadsetService: Received start request. Starting profile...
,10-25 14:25:51.062  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:51.063  5647  5658 D BluetoothHeadset: Proxy object connected
,10-25 14:25:51.064  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:51.064  3626  3640 D BluetoothHeadset: Proxy object connected
10-25 14:25:51.065   926   926 D BluetoothHeadset: Proxy object connected
,10-25 14:25:51.065   926   926 D BluetoothHeadset: Proxy object connected
10-25 14:25:51.065  5745  5745 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-25 14:25:51.065  5745  5745 D HeadsetStateMachine: make
10-25 14:25:51.066  5647  5647 D HeadsetProfile: Bluetooth service connected
,10-25 14:25:51.067  2984  3874 D BluetoothHeadset: Proxy object connected
10-25 14:25:51.067   926   926 D BluetoothHeadset: Proxy object connected
,10-25 14:25:51.076  5745  5757 I BluetoothAdapterState: Entering PendingCommandState
,10-25 14:25:51.078  5745  5745 D HeadsetStateMachine: max_hf_connections = 1
,10-25 14:25:51.078  5745  5745 I bt_bluedroid: get_profile_interface handsfree
10-25 14:25:51.078   926  2829 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-25 14:25:51.079  5745  5761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-25 14:25:51.079  5745  5761 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
10-25 14:25:51.079   926  2829 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-25 14:25:51.080   926  2829 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-25 14:25:51.081  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
10-25 14:25:51.083  5745  5745 D A2dpService: Received start request. Starting profile...
10-25 14:25:51.085  5745  5745 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-25 14:25:51.085  5745  5745 I bt_bluedroid: get_profile_interface avrcp
,10-25 14:25:51.090   926  2829 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-25 14:25:51.091  5745  5757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-25 14:25:51.091  5745  5745 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-25 14:25:51.091  2984  2984 D HeadsetProfile: Bluetooth service connected
10-25 14:25:51.091  5745  5745 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-25 14:25:51.091  5745  5745 D A2dpStateMachine: make
,10-25 14:25:51.093  5745  5745 I bt_bluedroid: get_profile_interface a2dp
,10-25 14:25:51.094  5745  5761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-25 14:25:51.095  5745  5776 D A2dpStateMachine: Enter Disconnected: -2
,10-25 14:25:51.095  5745  5745 I BluetoothHidServiceJni: classInitNative: succeeds
,10-25 14:25:51.097  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
10-25 14:25:51.098  5745  5745 D HidService: Received start request. Starting profile...
10-25 14:25:51.098  5745  5745 I bt_bluedroid: get_profile_interface hidhost
10-25 14:25:51.098  5745  5745 D HidService: setHidService(): set to: null
10-25 14:25:51.098  5745  5761 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e7256d
10-25 14:25:51.099  5745  5761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-25 14:25:51.100  5745  5745 I BluetoothHealthServiceJni: classInitNative: succeeds
10-25 14:25:51.101  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
10-25 14:25:51.101  3458  3458 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 14:25:51.101  5745  5745 D HealthService: Received start request. Starting profile...
,10-25 14:25:51.102  5745  5745 I bt_bluedroid: get_profile_interface health
10-25 14:25:51.103  5745  5745 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-25 14:25:51.104  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
,10-25 14:25:51.105  5745  5745 D PanService: Received start request. Starting profile...
,10-25 14:25:51.105  5745  5745 D BluetoothPanServiceJni: initializeNative(L110): pan
10-25 14:25:51.105  5745  5745 I bt_bluedroid: get_profile_interface pan
10-25 14:25:51.107  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
10-25 14:25:51.107  5745  5761 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-25 14:25:51.108  5745  5745 D BluetoothMapService: Received start request. Starting profile...
10-25 14:25:51.108  5745  5745 D BluetoothMapService: start()
10-25 14:25:51.110  5745  5745 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-25 14:25:51.110  5745  5745 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-25 14:25:51.110  5745  5745 D BluetoothMapAppObserver: createReceiver()
,10-25 14:25:51.112  5745  5745 D BluetoothMapAppObserver: initObservers()
,10-25 14:25:51.112  5745  5745 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-25 14:25:51.119  5745  5745 V SapService: SapBinder()
,10-25 14:25:51.119  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
,10-25 14:25:51.119  5745  5745 D SapService: Received start request. Starting profile...
10-25 14:25:51.119  5745  5745 V SapService: start()
,10-25 14:25:51.122  5745  5745 V BluetoothAdapterState: isTurningOff()=false
,10-25 14:25:51.122  5745  5745 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:51.122  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:51.122  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:51.122  5745  5745 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:51.122  5745  5745 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:51.122  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:51.122  5745  5774 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,10-25 14:25:51.122  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:51.123  5745  5745 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:51.123  5745  5745 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:51.123  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:51.123  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:51.123  5745  5745 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:51.123  5745  5745 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:51.123  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
,10-25 14:25:51.123  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:51.124  5745  5745 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:51.124  5745  5745 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:51.124  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:51.124  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:51.124  5745  5745 V BluetoothAdapterState: isTurningOff()=false
,10-25 14:25:51.124  5745  5745 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:51.124  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:51.124  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
10-25 14:25:51.125  5745  5745 V BluetoothAdapterState: isTurningOff()=false
10-25 14:25:51.125  5745  5745 V BluetoothAdapterState: isTurningOn()=true
10-25 14:25:51.125  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
10-25 14:25:51.125  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 14:25:51.125  5745  5757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-25 14:25:51.125  5745  5757 D BluetoothAdapterProperties: ScanMode =  20
10-25 14:25:51.125  5745  5757 D BluetoothAdapterProperties: State =  11
10-25 14:25:51.127  5745  5761 D BluetoothAdapterProperties: Scan Mode:21
,10-25 14:25:51.127  5745  5757 D BluetoothAdapterProperties: Setting state to 12
10-25 14:25:51.127  5745  5757 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-25 14:25:51.127  5745  5761 D BluetoothAdapterProperties: Discoverable Timeout:120
10-25 14:25:51.127   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-25 14:25:51.128  5745  5757 I BluetoothAdapterState: Entering OnState
,10-25 14:25:51.128  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-25 14:25:51.129  2984  3002 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-25 14:25:51.129   926   926 D BluetoothA2dp: Proxy object connected
10-25 14:25:51.129  5647  5658 D BluetoothMap: onBluetoothStateChange: up=true
10-25 14:25:51.131   926  2829 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
10-25 14:25:51.132  2984  3874 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-25 14:25:51.132  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:51.132  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:51.132  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:51.132  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:51.132  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:51.132  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:51.132  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:51.132  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 14:25:51.133  5647  5647 D BluetoothMap: Proxy object connected
10-25 14:25:51.133  5647  5647 D MapProfile: Bluetooth service connected
,10-25 14:25:51.133  5647  5647 D BluetoothMap: getConnectedDevices()
10-25 14:25:51.134  5647  5658 D BluetoothPan: onBluetoothStateChange on: true
10-25 14:25:51.135  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:51.135  2984  2984 D BluetoothInputDevice: Proxy object connected
10-25 14:25:51.135  2984  2984 D HidProfile: Bluetooth service connected
10-25 14:25:51.136   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 14:25:51.136  5638  5638 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
10-25 14:25:51.136  5647  5657 D BluetoothPbap: onBluetoothStateChange: up=true
10-25 14:25:51.137  5745  5745 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-25 14:25:51.138  5745  5745 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-25 14:25:51.138  5647  5658 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 14:25:51.138   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-25 14:25:51.138  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:51.138  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:51.138  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:51.138  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:51.138  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:51.138  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:51.138  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:51.138  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 14:25:51.138  2984  2999 D BluetoothA2dp: onBluetoothStateChange: up=true
10-25 14:25:51.140  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:51.140  2984  2984 D BluetoothA2dp: Proxy object connected
10-25 14:25:51.140  2984  3874 D BluetoothMap: onBluetoothStateChange: up=true
10-25 14:25:51.140  5647  5647 D BluetoothPan: BluetoothPAN Proxy object connected
10-25 14:25:51.141  5647  5647 D PanProfile: Bluetooth service connected
10-25 14:25:51.141  5745  5745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 14:25:51.142  2984  2984 D BluetoothMap: Proxy object connected
10-25 14:25:51.142  2984  2999 D BluetoothPan: onBluetoothStateChange on: true
10-25 14:25:51.142  2984  2984 D MapProfile: Bluetooth service connected
,10-25 14:25:51.142  2984  2984 D BluetoothMap: getConnectedDevices()
10-25 14:25:51.145  5745  5745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 14:25:51.146  2984  2984 D BluetoothPan: BluetoothPAN Proxy object connected
10-25 14:25:51.146  5647  5657 D BluetoothA2dp: onBluetoothStateChange: up=true
10-25 14:25:51.146  2984  2984 D PanProfile: Bluetooth service connected
,10-25 14:25:51.147  5745  5745 D ObexServerSockets: Succeed to create listening sockets 
10-25 14:25:51.147  5745  5745 D ObexServerSockets0: startAccept()
10-25 14:25:51.147  5745  5745 D ObexServerSockets0: prepareForNewConnect()
10-25 14:25:51.148  3626  3638 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-25 14:25:51.148  5647  5782 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-25 14:25:51.150  5647  5647 D BluetoothA2dp: Proxy object connected
10-25 14:25:51.150  5745  5745 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,10-25 14:25:51.150  5745  5745 D BluetoothSdpJni: SDP Create record success - handle: 0
10-25 14:25:51.151   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 14:25:51.151  2984  3873 D BluetoothPbap: onBluetoothStateChange: up=true
10-25 14:25:51.151  5745  5783 D ObexServerSockets0: Accepting socket connection...
10-25 14:25:51.152  5745  5784 D ObexServerSockets0: Accepting socket connection...
10-25 14:25:51.153   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
10-25 14:25:51.153   926   926 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
10-25 14:25:51.154  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-25 14:25:51.154  5745  5745 D BluetoothMapService: onReceive
10-25 14:25:51.154  5745  5745 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-25 14:25:51.154  5745  5745 D BluetoothMapService: STATE_ON
10-25 14:25:51.155  5647  5647 D BluetoothInputDevice: Proxy object connected
10-25 14:25:51.155  5647  5647 D HidProfile: Bluetooth service connected
10-25 14:25:51.155  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:51.157  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:51.157  5745  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 14:25:51.158  5745  5785 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-25 14:25:51.159  5745  5785 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-25 14:25:51.162  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-25 14:25:51.168  3458  3458 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 14:25:51.169  5647  5647 D DockEventReceiver: finishStartingService: stopping service
,10-25 14:25:51.174  5647  5647 D BluetoothPbap: Proxy object connected
,10-25 14:25:51.174  5647  5647 D PbapServerProfile: Bluetooth service connected
,10-25 14:25:51.179  5745  5745 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-25 14:25:51.179  5745  5745 D ObexServerSockets0: prepareForNewConnect()
10-25 14:25:51.180  5745  5790 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 14:25:51.186  2984  2984 D BluetoothPbap: Proxy object connected
10-25 14:25:51.186  2984  2984 D PbapServerProfile: Bluetooth service connected
,10-25 14:25:51.197  5745  5794 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 14:25:51.198  5745  5794 I BtOppRfcommListener: Accept thread started.
,10-25 14:25:51.563  5638  5638 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-25 14:25:51.600  5513  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:51.600  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:51.600  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:51.600  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:51.600  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:51.600  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:51.600  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:51.600  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:51.605  5513  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:51.609  5513  5560 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
10-25 14:25:51.609  5638  5638 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-25 14:25:51.611  5638  5638 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-25 14:25:51.612   926  3040 D WifiService: setWifiEnabled: false pid=5513, uid=10077
10-25 14:25:51.613   926  3040 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-25 14:25:51.613  5513  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:51.625   926  2829 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-25 14:25:51.625   926  2829 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-25 14:25:51.625   926  2831 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-25 14:25:51.646   926  2829 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 14:25:51.658   506   920 D CommandListener: Setting iface cfg
,10-25 14:25:51.664   926  2829 D WifiStateMachine: Start Dhcp Watchdog 2
,10-25 14:25:51.670   926  5801 D DhcpClient: Receive thread started
,10-25 14:25:51.674   926  2829 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{1}, ntable=[]
,10-25 14:25:51.674   926  2829 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-25 14:25:51.675   926  2829 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 14:25:51.684   506   920 D CommandListener: Clearing all IP addresses on wlan0
,10-25 14:25:51.697   926   926 D RttService: SCAN_AVAILABLE : 1
,10-25 14:25:51.697   926  2938 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-25 14:25:51.697   926  5801 D DhcpClient: Receive thread stopped
,10-25 14:25:51.701   926  2831 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-25 14:25:51.702   926  2831 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
10-25 14:25:51.702   926  2831 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
10-25 14:25:51.702   926  2831 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 0
,10-25 14:25:51.705   926  2829 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-25 14:25:51.707   506   920 D CommandListener: Clearing all IP addresses on wlan0
,10-25 14:25:51.708   926  2831 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-25 14:25:51.709   926  2829 D DhcpClient: doQuit
,10-25 14:25:51.710   926  2829 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-25 14:25:51.710   926  5800 D DhcpClient: onQuitting
10-25 14:25:51.711  5638  5638 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-25 14:25:51.712   926  2829 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-25 14:25:51.718  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:51.718  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:51.718  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:51.718  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 14:25:51.718  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:51.718  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:51.718  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:51.718  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:51.723  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:51.727  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:51.727  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:51.727  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:51.727  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 14:25:51.727  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:51.727  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:51.727  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:51.727  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 14:25:51.729  5638  5638 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-25 14:25:51.729  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:51.732  5638  5638 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-25 14:25:51.761  5638  5638 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-25 14:25:51.764  5638  5638 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-25 14:25:51.867  4871  4871 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 14:25:51.868   926  2829 D wifi    : In wifi stop Hal
,10-25 14:25:51.868   926  2829 D wifi    : halHandle = 0x7f77f2fe00, mVM = 0x7f9458d140, mCls = 0x1606
10-25 14:25:51.868   926  5637 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-25 14:25:51.868   926  5637 D WifiHAL : Got a signal to exit!!!
10-25 14:25:51.868   926  5637 I WifiHAL : Exit wifi_event_loop
10-25 14:25:51.870   926  2829 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-25 14:25:51.870   926  2829 E WifiHAL : Event processing terminated
10-25 14:25:51.870   926  2829 D wifi    : In wifi cleaned up handler
,10-25 14:25:51.870   926  2829 I WifiHAL : Internal cleanup completed
10-25 14:25:51.875  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:51.875  3978  4098 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 14:25:51.879  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:51.900   926  5637 D wifi    : set interface wlan0 flags (DOWN)
,10-25 14:25:51.900   926  2829 D WifiNative-HAL: HAL event thread stopped successfully
,10-25 14:25:52.107   926   943 D Tethering: InitialState.processMessage what=4
,10-25 14:25:52.114   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-25 14:25:52.125  5513  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:52.125  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:52.125  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:52.125  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 14:25:52.125  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:52.125  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:52.125  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:52.125  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:52.130  5513  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:52.132   926  3286 D WifiService: setWifiEnabled: true pid=5513, uid=10077
10-25 14:25:52.132   926  3286 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 14:25:52.134  5513  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:52.139   506   920 D SoftapController: Softap fwReload - Ok
,10-25 14:25:52.143   506   920 D CommandListener: Setting iface cfg
,10-25 14:25:52.144   506   920 D CommandListener: Trying to bring down wlan0
10-25 14:25:52.146   506   920 D CommandListener: Clearing all IP addresses on wlan0
,10-25 14:25:52.151   926  2829 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-25 14:25:52.637   926  3639 D WifiService: setWifiEnabled: true pid=5513, uid=10077
,10-25 14:25:52.642   926  3639 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 14:25:52.758   926  2829 D wifi    : set interface wlan0 flags (UP)
,10-25 14:25:52.759   926  2829 I WifiHAL : Initializing wifi
10-25 14:25:52.760   926  2829 I WifiHAL : Creating socket
,10-25 14:25:52.767   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-25 14:25:52.767   926  2829 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-25 14:25:52.768   926  2829 D wifi    : Did set static halHandle = 0x7f77f2fe00
,10-25 14:25:52.768   926  2829 D wifi    : halHandle = 0x7f77f2fe00, mVM = 0x7f9458d140, mCls = 0x101322
10-25 14:25:52.768   926  2829 D wifi    : array field set
10-25 14:25:52.769   926  2829 I WifiNative-HAL: interface[0] = wlan0
10-25 14:25:52.771   926  5804 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547473260032
,10-25 14:25:52.771   926  5804 D wifi    : waitForHalEvents called, vm = 0x7f9458d140, obj = 0x101322, env = 0x7f77f17900
,10-25 14:25:52.831  5805  5805 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-25 14:25:52.877  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:52.877   926  2829 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-25 14:25:52.883  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:52.909  5805  5805 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-25 14:25:52.935  5805  5805 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-25 14:25:52.936  5805  5805 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-25 14:25:52.948   926  2829 D WifiConfigStore: Loading config and enabling all networks 
,10-25 14:25:52.960  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:52.960  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:52.960  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:52.960  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:52.960  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:52.960  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:52.960  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:52.960  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:52.965  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 14:25:52.966   926  2829 D WifiConfigStore: loaded 0 passpoint configs
10-25 14:25:52.966   926  2829 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,10-25 14:25:52.967   926  2829 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-25 14:25:52.967   926  2829 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-25 14:25:52.967   926  2829 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,10-25 14:25:52.968   926  2829 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
10-25 14:25:52.968   926  2829 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-25 14:25:52.968   926  2829 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-25 14:25:52.969   926  2829 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,10-25 14:25:52.969   926  2829 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-25 14:25:52.969   926  2829 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-25 14:25:52.969   926  2829 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,10-25 14:25:52.969   926  2829 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-25 14:25:52.971  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:52.971  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:52.971  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:52.971  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:52.971  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:52.971  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:52.971  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:52.971  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:52.975  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:52.988   926  2829 D WifiNative-HAL: Setting external_sim to 1
10-25 14:25:52.988   926  2829 D wifi    : setting dfs flag to true, 0x7f7d17fc00
10-25 14:25:52.988   926  2829 D WifiStateMachine: Setting OUI to DA-A1-19
10-25 14:25:52.989   926  2829 D wifi    : setting scan oui 0x7f7d17fc00
10-25 14:25:52.989   926  2829 D WifiHAL : Sending mac address OUI
,10-25 14:25:52.991  4871  4871 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 14:25:52.991   926  2829 E native  : do suspend false
,10-25 14:25:52.999   926  2829 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-25 14:25:52.999   926   926 D RttService: SCAN_AVAILABLE : 3
,10-25 14:25:52.999   926  2938 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-25 14:25:53.005   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-25 14:25:53.007   506   920 D CommandListener: Setting iface cfg
,10-25 14:25:53.010   926  2828 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '137 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 137 Failed to set address (No such device)'
,10-25 14:25:53.010   926  2828 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-25 14:25:53.017   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=115786 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=11 mControllerEnergyUsed=41 }
,10-25 14:25:53.019   926  2828 D WifiNative-HAL: p2pGetDeviceAddress
,10-25 14:25:53.020   926  2828 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-25 14:25:53.150  5513  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:53.150  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:53.150  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:53.150  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:53.150  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:53.150  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:53.150  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:53.150  5513  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:53.154  5513  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:53.158  5513  5560 D BluetoothAdapter: enable(): BT is already enabled..!
,10-25 14:25:53.159   926  3647 D WifiService: setWifiEnabled: true pid=5513, uid=10077
10-25 14:25:53.159   926  3647 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-25 14:25:53.160  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 14:25:53.160  5513  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 14:25:53.160  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 14:25:53.160  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 14:25:53.160  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-25 14:25:53.160  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a744152 removed from the list
10-25 14:25:53.160  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 14:25:53.160  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d2fc23 removed from the list
10-25 14:25:53.161  5513  5560 D io.jxcore.node.ConnectivityMonitor: stop
10-25 14:25:53.161  5513  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 14:25:53.161  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 14:25:53.162  5513  5560 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
10-25 14:25:53.163  5513  5560 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
10-25 14:25:53.164  5513  5560 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,10-25 14:25:53.166  5513  5560 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
10-25 14:25:53.167  5513  5560 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,10-25 14:25:53.168  5513  5560 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-25 14:25:53.169  5513  5560 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
10-25 14:25:53.169  5513  5560 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-25 14:25:53.169  5513  5560 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
10-25 14:25:53.171  5513  5560 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
10-25 14:25:53.171  5513  5560 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16b1b00 Bundle[{}]
10-25 14:25:53.172  5513  5560 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
10-25 14:25:53.172  5513  5560 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-25 14:25:53.172  5513  5560 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-25 14:25:53.173  5513  5560 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
10-25 14:25:53.173  5513  5560 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-25 14:25:53.174  5513  5560 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
10-25 14:25:53.174  5513  5560 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-25 14:25:53.174  5513  5560 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
10-25 14:25:53.174  5513  5560 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-25 14:25:53.175  5513  5560 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
10-25 14:25:53.175  5513  5560 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-25 14:25:53.176  5513  5560 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
10-25 14:25:53.178  5513  5560 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,10-25 14:25:53.179  5513  5560 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
10-25 14:25:53.179  5513  5560 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,10-25 14:25:53.180  5513  5560 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
10-25 14:25:53.180  5513  5560 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
10-25 14:25:53.181  5513  5560 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,10-25 14:25:53.182  5513  5560 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
10-25 14:25:53.182  5513  5560 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
10-25 14:25:53.183  5513  5560 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,10-25 14:25:53.184  5513  5560 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
10-25 14:25:53.185  5513  5560 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,10-25 14:25:53.185  5513  5560 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
10-25 14:25:53.185  5513  5560 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
10-25 14:25:53.186  5513  5560 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-25 14:25:53.186  5513  5560 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
10-25 14:25:53.186  5513  5560 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
10-25 14:25:53.187  5513  5560 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
10-25 14:25:53.187  5513  5560 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
10-25 14:25:53.188  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-25 14:25:53.188  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@871209e added. We now have 3 listener(s)
10-25 14:25:53.189  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 14:25:53.189  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 14:25:53.189  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 14:25:53.190  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 14:25:53.190  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84f377f added. We now have 3 listener(s)
,10-25 14:25:53.190  5513  5560 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 14:25:53.191  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-25 14:25:53.194  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 14:25:53.198  5513  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 14:25:53.198  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:53.198  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:53.198  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:53.198  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:53.198  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 14:25:53.198  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 14:25:53.198  5513  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 14:25:53.200  5513  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 14:25:53.200  5513  5560 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-25 14:25:53.203  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 14:25:53.205  5513  5560 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
10-25 14:25:53.206  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 14:25:53.206  5513  5560 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
10-25 14:25:53.206  5513  5560 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,10-25 14:25:53.206  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
10-25 14:25:53.206  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 14:25:53.206  5513  5560 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-25 14:25:53.206  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 14:25:53.206  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 14:25:53.208  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-25 14:25:53.207  5786  5786 W Binder_5: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[31382]" dev="sockfs" ino=31382 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:53.207  5786  5786 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[31382]" dev="sockfs" ino=31382 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:53.208  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-25 14:25:53.209  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 14:25:53.209  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 14:25:53.209  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-25 14:25:53.209  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-25 14:25:53.209  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 14:25:53.209  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 14:25:53.209  5513  5807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-25 14:25:53.209  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-25 14:25:53.210  5513  5807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 14:25:53.213  5513  5807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-25 14:25:53.213  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 14:25:53.214  5513  5560 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-25 14:25:53.214  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-25 14:25:53.219  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-25 14:25:53.219  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 14:25:53.219  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-25 14:25:53.222  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:53.222  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-25 14:25:53.222  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 14:25:53.222  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
10-25 14:25:53.222  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-25 14:25:53.222  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.222  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:53.222  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.222  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.223  5513  5560 D BluetoothAdapter: STATE_ON
,10-25 14:25:53.227  5745  5755 D BtGatt.GattService: registerClient() - UUID=6da2af82-24e8-4611-9a8c-4e2c8a757c8f
,10-25 14:25:53.228  5745  5761 D BtGatt.GattService: onClientRegistered() - UUID=6da2af82-24e8-4611-9a8c-4e2c8a757c8f, clientIf=5
10-25 14:25:53.229  5513  5523 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-25 14:25:53.231  5745  5763 D BtGatt.AdvertiseManager: message : 0
,10-25 14:25:53.234  5745  5763 D BtGatt.AdvertiseManager: starting multi advertising
,10-25 14:25:53.244  5745  5761 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-25 14:25:53.250  5745  5761 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-25 14:25:53.250  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:53.250  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.250  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-25 14:25:53.251  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.251  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:53.251  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.251  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.251  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.251  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-25 14:25:53.252  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-25 14:25:53.252  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.253  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.253  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.253  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:53.253  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 14:25:53.254  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,10-25 14:25:53.254  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:53.254  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 14:25:53.254  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 14:25:53.254  5513  5513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:53.254  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 14:25:53.254  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,10-25 14:25:53.254  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-25 14:25:53.254  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 14:25:53.254  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-25 14:25:53.254  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-25 14:25:53.254  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-25 14:25:53.257  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-25 14:25:53.257  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 14:25:53.257  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-25 14:25:53.257  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-25 14:25:53.257  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 14:25:53.257  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,10-25 14:25:53.257  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-25 14:25:53.758  5513  5513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-25 14:25:53.759  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-25 14:25:53.759  5513  5513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-25 14:25:55.524   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:25:56.025  5805  5805 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 14:25:56.032  5805  5805 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 14:25:56.038  5805  5805 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 14:25:56.073  5805  5805 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-25 14:25:56.116   926  2829 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-25 14:25:56.118   926  2829 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-25 14:25:56.119   926  2829 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 14:25:56.133   926  2829 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-25 14:25:56.165   926  2829 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-25 14:25:56.495  5805  5805 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-25 14:25:56.525   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:25:56.530  5805  5805 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-25 14:25:56.533  5805  5805 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-25 14:25:56.541   926  2829 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-25 14:25:56.541   926  2829 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-25 14:25:56.541   926  2831 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-25 14:25:56.555   926  2829 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 14:25:56.569   506   920 D CommandListener: Setting iface cfg
,10-25 14:25:56.575   926  2829 D WifiStateMachine: Start Dhcp Watchdog 3
,10-25 14:25:56.581   926  5812 D DhcpClient: Receive thread started
,10-25 14:25:56.586   926  2829 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-25 14:25:56.586   926  2831 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-25 14:25:56.586   926  2831 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-25 14:25:56.667   926  2829 E native  : do suspend false
,10-25 14:25:56.679   926  5811 D DhcpClient: Broadcasting DHCPDISCOVER
,10-25 14:25:56.698   926  5812 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172721, domain null
,10-25 14:25:56.698   926  5811 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172721 seconds
,10-25 14:25:56.700   926  5811 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-25 14:25:56.728   926  5812 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-25 14:25:56.729   926  5811 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-25 14:25:56.732   506   920 D CommandListener: Setting iface cfg
10-25 14:25:56.736   926  2829 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-25 14:25:56.743   926  5811 D DhcpClient: Scheduling renewal in 86399s
,10-25 14:25:56.750   926  2829 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-25 14:25:56.751   926  2829 D WifiConfigStore: No blacklist allowed without epno enabled
,10-25 14:25:56.751   926  2831 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-25 14:25:56.754   926  2831 D ConnectivityService: Adding iface wlan0 to network 102
,10-25 14:25:56.759  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-25 14:25:56.760  5513  5560 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-25 14:25:56.760  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 14:25:56.760  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-25 14:25:56.760  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-25 14:25:56.761  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 14:25:56.762  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 14:25:56.762  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-25 14:25:56.762  5513  5807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-25 14:25:56.762  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 14:25:56.762  5513  5807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-25 14:25:56.762  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 14:25:56.762  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-25 14:25:56.762  5513  5807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-25 14:25:56.762  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 14:25:56.762  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 14:25:56.763  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.763  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.764   926  2829 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
10-25 14:25:56.767  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:25:56.767  5513  5560 D BluetoothLeScanner: could not find callback wrapper
,10-25 14:25:56.767  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 14:25:56.768  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.768  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.768  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-25 14:25:56.768  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.769  5745  5763 D BtGatt.AdvertiseManager: message : 1
10-25 14:25:56.771  5745  5763 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-25 14:25:56.780  5745  5761 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-25 14:25:56.780  5745  5761 D BtGatt.GattService: Client app is not null!
,10-25 14:25:56.782  5745  5773 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-25 14:25:56.784  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 14:25:56.785  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.785  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 14:25:56.785  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.785  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.785  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.785  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 14:25:56.785  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-25 14:25:56.785  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.785  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.785  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-25 14:25:56.785  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.787  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.787  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 14:25:56.787  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.787  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.787  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.787  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.787  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.787  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 14:25:56.787  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 14:25:56.788  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 14:25:56.788  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-,25 14:25:56.790  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.790  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 14:25:56.790  5513  5513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-25 14:25:56.790  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-25 14:25:56.790  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 14:25:56.790  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:25:56.791  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:25:56.791  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 14:25:56.793  5513  5560 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
10-25 14:25:56.793  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-25 14:25:56.794  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 14:25:56.794  5513  5560 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-25 14:25:56.794  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-25 14:25:56.794  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 14:25:56.794  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 14:25:56.797  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 14:25:56.798  5513  5560 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 14:25:56.798  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-25 14:25:56.802  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-25 14:25:56.802  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-25 14:25:56.803  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-25 14:25:56.807  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:56.807  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-25 14:25:56.807  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-25 14:25:56.807  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-25 14:25:56.807   926  2831 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-25 14:25:56.808  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-25 14:25:56.808   926  2831 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
10-25 14:25:56.808  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.809  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:25:56.809   926  2831 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
10-25 14:25:56.811   926  2831 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-25 14:25:56.812  5745  5781 D BtGatt.GattService: registerClient() - UUID=5923e5c4-b3ad-4f63-85ca-b2e1e7b146c5
,10-25 14:25:56.812   926  2831 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-25 14:25:56.814  5745  5761 D BtGatt.GattService: onClientRegistered() - UUID=5923e5c4-b3ad-4f63-85ca-b2e1e7b146c5, clientIf=5
,10-25 14:25:56.814  5513  5523 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-25 14:25:56.815  5745  5773 D BtGatt.GattService: start scan with filters
,10-25 14:25:56.819   926  2831 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-25 14:25:56.819  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-25 14:25:56.819  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.819  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-25 14:25:56.819  5745  5764 D BtGatt.ScanManager: handling starting scan
10-25 14:25:56.820  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:56.821  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:56.821  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-25 14:25:56.821  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 14:25:56.821  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:56.821  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.821  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-25 14:25:56.821  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.822  5745  5764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cddf994
,10-25 14:25:56.824  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.824  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 14:25:56.824   926  2831 D ConnectivityService: scheduleUnvalidatedPrompt 102
10-25 14:25:56.824  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.824  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.824   926  2831 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-25 14:25:56.825  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.825  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 14:25:56.825   926  2831 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-25 14:25:56.825   926  2829 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-25 14:25:56.825   926  2831 D ConnectivityService:    accepting network in place of null
10-25 14:25:56.825   926  2829 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-25 14:25:56.825  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 14:25:56.826   926  2831 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-25 14:25:56.826  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 14:25:56.826  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:56.828  5745  5761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-25 14:25:56.828  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 14:25:56.829  5745  5764 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-25 14:25:56.829  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.829  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:56.829  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:56.834  5745  5761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-25 14:25:56.834  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 14:25:56.834  5745  5764 D BtGatt.ScanManager: Starting BLE batch scan
10-25 14:25:56.834  5745  5764 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-25 14:25:56.840   926  5810 D NetlinkSocketObserver: NeighborEvent{elapsedMs=119609, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-25 14:25:56.844  5745  5761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-25 14:25:56.844  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 14:25:56.845   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 14:25:56.849  5745  5761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-25 14:25:56.849  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 14:25:56.864   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 14:25:56.866   926  2831 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-25 14:25:56.867   926  2831 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-25 14:25:56.867  3596  3716 W QCNEJ   : |CORE| network available: 102
,10-25 14:25:56.868   926  2831 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,10-25 14:25:56.868   926   943 D Tethering: MasterInitialState.processMessage what=3
10-25 14:25:56.870  3596  3716 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-25 14:25:56.871  3596  3716 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-25 14:25:56.871  3596  3716 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-25 14:25:56.879  4936  4960 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-25 14:25:56.879  4936  4960 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-25 14:25:56.879  4936  4960 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-25 14:25:56.879  4936  4960 E SarControlService: no key has been found,reset the power
10-25 14:25:56.880  4936  4972 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-25 14:25:56.880  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:56.880  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:56.880  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:56.880  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:56.880  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:56.880  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:56.880  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 14:25:56.880  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 14:25:56.880  4936  4972 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-25 14:25:56.880  4936  4972 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-25 14:25:56.880  4961  4961 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 14:25:56.880  4961  4961 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-25 14:25:56.882  3799  3799 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-25 14:25:56.882  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 14:25:56.883  4936  4972 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-25 14:25:56.883  4936  4972 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-25 14:25:56.883  4936  4972 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,10-25 14:25:56.884  4961  4961 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 14:25:56.885  3821  3821 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-25 14:25:56.887  4961  4961 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-25 14:25:56.887  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:56.887  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:56.887  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:56.887  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:56.887  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:56.887  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:56.887  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 14:25:56.887  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 14:25:56.889  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 14:25:56.891  4961  4975 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@247bef HexData = [00000000ec03000000000000ffffffff]
10-25 14:25:56.892  4961  4975 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 14:25:56.892  4961  4975 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,10-25 14:25:56.892  3821  3821 D SystemUpdateService: onCreate
,10-25 14:25:56.893  4961  4961 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 14:25:56.893  4936  4947 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-25 14:25:56.894  4961  4975 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@247bef HexData = [00000000ed03000000000000ffffffff]
10-25 14:25:56.894  4961  4975 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 14:25:56.894  4961  4975 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-25 14:25:56.895  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 14:25:56.895  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 14:25:56.895  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 14:25:56.895  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 14:25:56.895  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 14:25:56.895  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:56.895  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 14:25:56.895  5513  5513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 14:25:56.895  4961  4961 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 14:25:56.895  4936  4946 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-25 14:25:56.897  5513  5513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 14:25:56.897  3821  3821 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-25 14:25:56.907  3821  3821 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-25 14:25:56.912  3821  5293 I iu.UploadsManager: num queued entries: 0
10-25 14:25:56.912  3821  5293 I iu.UploadsManager: num updated entries: 0
10-25 14:25:56.913  3821  5293 I iu.SyncManager: NEXT; no task
,10-25 14:25:56.917  3821  3821 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-25 14:25:56.919  3821  3821 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-25 14:25:56.921  5595  5595 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-25 14:25:56.924  5595  5595 D SprintDMHelper: simOperator: 
10-25 14:25:56.924  5595  5595 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-25 14:25:56.935  3821  5826 I SystemUpdateService: active receiver: enabled
,10-25 14:25:56.957   926  5809 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-25 14:25:56.959  3821  5826 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-25 14:25:56.965  3821  5826 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-25 14:25:56.965  3821  5826 I SystemUpdateService: now status is 0 (complete)
10-25 14:25:56.965  3821  5826 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-25 14:25:56.965  3821  5826 I SystemUpdateService: file has been verified
10-25 14:25:56.965  3821  5826 I SystemUpdateService: OTA package size = 21989297
,10-25 14:25:56.971  3821  5826 I SystemUpdateService: showing system update notification
,10-25 14:25:56.978   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-25 14:25:56.979  3821  3821 D SystemUpdateService: onDestroy
,10-25 14:25:57.007   926  5809 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 25 Oct 2016 12:25:56 GMT], X-Android-Received-Millis=[1477398357006], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477398356982]}
,10-25 14:25:57.007   926  2831 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-25 14:25:57.007   926  2831 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-25 14:25:57.007   926  2831 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-25 14:25:57.008   926  2831 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-25 14:25:57.034  4871  5831 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-25 14:25:57.280   926  2829 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 10 -> obsolete
,10-25 14:25:57.326  5513  5513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-25 14:25:57.326  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-25 14:25:57.327  5513  5513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-25 14:25:57.353  5745  5745 D BtGatt.ScanManager: awakened up at time 120122
,10-25 14:25:57.355  5745  5764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-25 14:25:57.384  5745  5761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,10-25 14:25:57.384  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 14:25:57.385  5745  5761 D BtGatt.GattService: current time is 120154300451
10-25 14:25:57.385  5745  5761 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -88, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-25 14:25:57.387  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-25 14:25:57.391  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
,10-25 14:25:57.391  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-25 14:25:57.392  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-88, mTimestampNanos=119654799305}
,10-25 14:25:57.526   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:25:57.868   926  2831 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-25 14:25:58.527   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:25:59.528   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:25:59.832  5513  5560 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,10-25 14:25:59.833  5513  5560 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
10-25 14:25:59.833  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,10-25 14:25:59.833  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-25 14:25:59.833  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-25 14:25:59.833  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-25 14:25:59.833  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
10-25 14:25:59.833  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-25 14:25:59.833  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-25 14:25:59.833  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-25 14:25:59.833  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-25 14:25:59.833  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-25 14:25:59.834  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 14:25:59.834  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 14:25:59.836  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:25:59.838  5745  5786 D BtGatt.GattService: stopScan() - queue size =1
10-25 14:25:59.840  5745  5756 D BtGatt.GattService: unregisterClient() - clientIf=5
10-25 14:25:59.842  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 14:25:59.842  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.842  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-25 14:25:59.842  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 14:25:59.843  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.843  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-25 14:25:59.843  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-25 14:25:59.843  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-25 14:25:59.843  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-25 14:25:59.843  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.845  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:25:59.849  5745  5745 D BtGatt.ScanManager: awakened up at time 122618
10-25 14:25:59.856  5745  5781 D BtGatt.GattService: registerClient() - UUID=97f216b9-8d82-489d-ab73-cbc3ac230aa8
10-25 14:25:59.857  5745  5761 D BtGatt.GattService: onClientRegistered() - UUID=97f216b9-8d82-489d-ab73-cbc3ac230aa8, clientIf=5
10-25 14:25:59.858  5513  5523 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-25 14:25:59.858  5745  5761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-25 14:25:59.858  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 14:25:59.859  5745  5764 D BtGatt.ScanManager: stopping BLe Batch
10-25 14:25:59.860  5745  5755 D BtGatt.GattService: start scan with filters
,10-25 14:25:59.865  5745  5761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-25 14:25:59.865  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 14:25:59.865  5745  5764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-25 14:25:59.865  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-25 14:25:59.866  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.866  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-25 14:25:59.866  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.866  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.866  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-25 14:25:59.866  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-25 14:25:59.866  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.866  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:59.866  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-25 14:25:59.866  5513  5560 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-25 14:25:59.866  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 14:25:59.866  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 14:25:59.867  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-25 14:25:59.868  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-25 14:25:59.868  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 14:25:59.868  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-25 14:25:59.868  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 14:25:59.868  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-25 14:25:59.868  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
10-25 14:25:59.868  5513  5838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-25 14:25:59.869  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 14:25:59.869  5513  5838 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 14:25:59.869  5513  5560 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-25 14:25:59.871  5513  5838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-25 14:25:59.867  5756  5756 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34890]" dev="sockfs" ino=34890 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:59.867  5756  5756 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34890]" dev="sockfs" ino=34890 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 14:25:59.875  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.876  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.876  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-25 14:25:59.876  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 14:25:59.876  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
10-25 14:25:59.876  5513  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-25 14:25:59.876  5745  5761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,10-25 14:25:59.876  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.876  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 14:25:59.876  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:59.876  5745  5761 D BtGatt.GattService: current time is 122646125856
10-25 14:25:59.877  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.877  5745  5761 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -87, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -96, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -89, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
10-25 14:25:59.877  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.877  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
10-25 14:25:59.877  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-25 14:25:59.877  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-25 14:25:59.878  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
10-25 14:25:59.878  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:25:59.878  5745  5764 D BtGatt.ScanManager: handling starting scan
10-25 14:25:59.880  5745  5773 D BtGatt.GattService: registerClient() - UUID=3dff3776-d058-4ff7-b52d-bc5c34603e39
10-25 14:25:59.880  5745  5761 D BtGatt.GattService: onClientRegistered() - UUID=3dff3776-d058-4ff7-b52d-bc5c34603e39, clientIf=6
10-25 14:25:59.881  5513  5524 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,10-25 14:25:59.882  5745  5763 D BtGatt.AdvertiseManager: message : 0
,10-25 14:25:59.885  5745  5763 D BtGatt.AdvertiseManager: starting multi advertising
,10-25 14:25:59.886  5745  5761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-25 14:25:59.886  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 14:25:59.886  5745  5764 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-25 14:25:59.894  5745  5761 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,10-25 14:25:59.898  5745  5761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-25 14:25:59.898  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 14:25:59.898  5745  5764 D BtGatt.ScanManager: Starting BLE batch scan
,10-25 14:25:59.898  5745  5764 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-25 14:25:59.902  5745  5761 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
10-25 14:25:59.902  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.902  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.902  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-25 14:25:59.902  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.902  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.902  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.902  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.903  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.903  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:59.903  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.903  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.903  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
10-25 14:25:59.903  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
10-25 14:25:59.903  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 14:25:59.904  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 14:25:59.904  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:25:59.908  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.909  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.909  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:25:59.909  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-25 14:25:59.909  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 14:25:59.909  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:59.909  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 14:25:59.909  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 14:25:59.909  5513  5513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:59.910  5745  5761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-25 14:25:59.910  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 14:25:59.909  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 14:25:59.919  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
,10-25 14:25:59.919  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-25 14:25:59.919  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 14:25:59.919  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-25 14:25:59.919  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
10-25 14:25:59.919  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-25 14:25:59.921  5745  5761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-25 14:25:59.921  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 14:25:59.922  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-25 14:25:59.922  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
10-25 14:25:59.922  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,10-25 14:25:59.922  5513  5513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-25 14:25:59.922  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 14:25:59.922  5513  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 14:25:59.922  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-25 14:26:00.423  5513  5513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,10-25 14:26:00.424  5513  5513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-25 14:26:00.424  5513  5513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-25 14:26:00.529   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-25 14:26:02.919  5513  5560 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
10-25 14:26:02.920  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 14:26:02.920  5513  5560 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 14:26:02.920  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 14:26:02.920  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-25 14:26:02.921  5513  5838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-25 14:26:02.921  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 14:26:02.921  5513  5838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-25 14:26:02.921  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 14:26:02.922  5513  5838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-25 14:26:02.922  5513  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-25 14:26:02.922  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 14:26:02.922  5513  5513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-25 14:26:02.922  5513  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@871209e removed from the list
10-25 14:26:02.922  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 14:26:02.922  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-25 14:26:02.922  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 14:26:02.922  5513  5513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 14:26:02.922  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 14:26:02.923  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 14:26:02.923  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.923  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.923  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-25 14:26:02.926  5513  5560 D BluetoothAdapter: STATE_ON
10-25 14:26:02.927  5745  5755 D BtGatt.GattService: stopScan() - queue size =1
,10-25 14:26:02.929  5745  5756 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-25 14:26:02.930  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 14:26:02.931  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.931  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-25 14:26:02.931  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.931  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.931  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-25 14:26:02.931  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
10-25 14:26:02.932  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.932  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.932  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
10-25 14:26:02.932  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.937  5745  5745 D BtGatt.ScanManager: awakened up at time 125706
10-25 14:26:02.938  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.939  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 14:26:02.939  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.939  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.939  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:26:02.939  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.939  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-25 14:26:02.939  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:26:02.941  5745  5763 D BtGatt.AdvertiseManager: message : 1
10-25 14:26:02.941  5745  5761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-25 14:26:02.941  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 14:26:02.942  5745  5763 D BtGatt.AdvertiseManager: stop advertise for client 6
,10-25 14:26:02.942  5745  5764 D BtGatt.ScanManager: stopping BLe Batch
10-25 14:26:02.944   926  2829 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 10 -> obsolete
,10-25 14:26:02.952  5745  5761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-25 14:26:02.952  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 14:26:02.953  5745  5764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-25 14:26:02.960  5745  5761 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
10-25 14:26:02.961  5745  5761 D BtGatt.GattService: Client app is not null!
,10-25 14:26:02.962  5745  5756 D BtGatt.GattService: unregisterClient() - clientIf=6
10-25 14:26:02.962  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 14:26:02.962  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 14:26:02.962  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 14:26:02.963  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.963  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.963  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:26:02.963  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 14:26:02.963  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-25 14:26:02.963  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.963  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:26:02.963  5513  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-25 14:26:02.963  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:26:02.966  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.966  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 14:26:02.966  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-25 14:26:02.966  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.966  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.966  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.967  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.967  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 14:26:02.967  5513  5560 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 14:26:02.968  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-25 14:26:02.968  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.969  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.969  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.970  5513  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 14:26:02.970  5513  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84f377f removed from the list
10-25 14:26:02.970  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:26:02.970  5513  5560 D io.jxcore.node.ConnectivityMonitor: stop
10-25 14:26:02.970  5513  5513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 14:26:02.970  5513  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 14:26:02.970  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 14:26:02.970  5513  5513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 14:26:02.973  5513  5560 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
10-25 14:26:02.973  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,10-25 14:26:02.973  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-25 14:26:02.973  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-25 14:26:02.973  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 14:26:02.973  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-25 14:26:02.974  5513  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-25 14:26:02.975  5513  5560 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
10-25 14:26:02.976  5513  5560 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,10-25 14:26:02.978  5513  5560 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,10-25 14:26:02.979  5513  5560 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
10-25 14:26:02.980  5513  5560 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
10-25 14:26:02.982  5513  5560 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
10-25 14:26:02.983  5513  5560 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
10-25 14:26:02.984  5513  5560 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,10-25 14:26:02.996  5745  5761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-25 14:26:02.997  5745  5761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 14:26:02.997  5745  5761 D BtGatt.GattService: current time is 125766399490
10-25 14:26:02.997  5745  5761 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -97, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -76, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -76, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -77, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
10-25 14:26:02.997  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-25 14:26:02.998  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-25 14:26:02.998  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-25 14:26:02.998  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-25 14:26:02.998  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-25 14:26:02.999  5745  5761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,10-25 14:26:03.471  5513  5513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 14:26:04.831   926  2831 D ConnectivityService: handlePromptUnvalidated 102
,10-25 14:26:04.988  5513  5560 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,10-25 14:26:05.143  5513  5840 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-25 14:26:05.143  5513  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 14:26:05.529   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:05.945  5513  5840 W !!      : call onHalfStreamCopied
,10-25 14:26:05.946  5513  5840 I testCopyDataAndClose: closing input stream
,10-25 14:26:06.530   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-25 14:26:06.715  5513  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-25 14:26:07.531   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:08.019   926  2829 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,10-25 14:26:08.533   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:09.534   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:10.535   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-25 14:26:11.559  5513  5560 I StreamCopyingThreadTest: Starting test: testRun
,10-25 14:26:11.563  5513  5845 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
10-25 14:26:11.563  5513  5845 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 14:26:16.170  3528  3700 I Keyboard.Facilitator.LanguageModelFlusher: run()
,10-25 14:26:16.171  3528  3700 I Keyboard.Facilitator: flushDynamicLanguageModels()
,10-25 14:26:16.198  3458  3458 I ConfigService: onCreate
,10-25 14:26:16.571  5513  5846 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,10-25 14:26:16.573  5513  5560 I StreamCopyingThreadTest: Starting test: testCopyBigData
,10-25 14:26:16.729  5513  5848 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-25 14:26:16.729  5513  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-25 14:26:18.337  5513  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-25 14:26:20.536   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:21.230  3458  3458 I ConfigService: onDestroy
,10-25 14:26:21.538   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:22.539   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:23.144  5513  5560 I StreamCopyingThreadTest: Starting test: testRunNotify
,10-25 14:26:23.146  5513  5849 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
10-25 14:26:23.146  5513  5849 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 14:26:23.147  5513  5849 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
10-25 14:26:23.147  5513  5849 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 14:26:23.147  5513  5849 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-25 14:26:23.147  5513  5849 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 14:26:23.147  5513  5849 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-25 14:26:23.147  5513  5849 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-25 14:26:23.148  5513  5849 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-25 14:26:23.148  5513  5849 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-25 14:26:23.148  5513  5849 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-25 14:26:23.148  5513  5849 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
10-25 14:26:23.148  5513  5849 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-25 14:26:23.149  5513  5560 I StreamCopyingThreadTest: Starting test: testSetBufferSize
10-25 14:26:23.150  5513  5560 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-25 14:26:23.151  5513  5560 I StreamCopyingThreadTest: Starting test: testRunWithException
,10-25 14:26:23.153  5513  5850 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
10-25 14:26:23.153  5513  5850 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 14:26:23.154  5513  5850 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
10-25 14:26:23.154  5513  5850 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
10-25 14:26:23.154  5513  5850 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-25 14:26:23.154  5513  5850 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-25 14:26:23.154  5513  5850 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
10-25 14:26:23.154  5513  5850 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-25 14:26:23.156  5513  5560 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
10-25 14:26:23.156  5513  5560 E com.test.thalitest.ThaliTestRunner: 
10-25 14:26:23.156  5513  5560 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-25 14:26:23.156  5513  5560 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 14:26:23.157  5513,  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-25 14:26:23.157  5513  5560 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
10-25 14:26:23.158  5513  5560 E com.test.t,halitest.ThaliTestRunner: Expected: is <true>
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363,)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:26:23.158  5513  5560 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-25 14:26:23.162  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG UnitTest_app: 'Running unit tests'
10-25 14:26:23.162  5513  5560 I jxcore-log: 
10-25 14:26:23.162  5513  5560 I jxcore-log: *Native tests were executed*
10-25 14:26:23.162  5513  5560 I jxcore-log: 
10-25 14:26:23.162  5513  5560 I jxcore-log: Total number of executed tests:  82
10-25 14:26:23.162  5513  5560 I jxcore-log: 
10-25 14:26:23.162  5513  5560 I jxcore-log: Number of passed tests:  80
10-25 14:26:23.162  5513  5560 I jxcore-log: 
10-25 14:26:23.162  5513  5560 I jxcore-log: Number of failed tests:  2
10-25 14:26:23.162  5513  5560 I jxcore-log: 
10-25 14:26:23.162  5513  5560 I jxcore-log: Number of ignored tests:  0
10-25 14:26:23.162  5513  5560 I jxcore-log: 
10-25 14:26:23.163  5513  5560 I jxcore-log: Total duration:  43657
10-25 14:26:23.163  5513  5560 I jxcore-log: 
10-25 14:26:23.163  5513  5560 I jxcore-log: Failed to execute UT.
10-25 14:26:23.163  5513  5560 I jxcore-log: 
10-25 14:26:23.163  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-25 14:26:23.163  5513  5560 I jxcore-log: 
10-25 14:26:23.165  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG UnitTest_ap,p: 'Unit Test app is loaded'
10-25 14:26:23.165  5513  5560 I jxcore-log: 
10-25 14:26:23.167  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 14:26:23.167  5513  5560 I jxcore-log: 
10-25 14:26:23.168  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.168  5513  5560 I jxcore-log: 
10-25 14:26:23.169  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 14:26:23.169  5513  5560 I jxcore-log: 
10-25 14:26:23.170  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.170  5513  5560 I jxcore-log: 
,10-25 14:26:23.170  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 14:26:23.170  5513  5560 I jxcore-log: 
10-25 14:26:23.170  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.170  5513  5560 I jxcore-log: 
10-25 14:26:23.171  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-25 14:26:23.171  5513  5560 I jxcore-log: 
10-25 14:26:23.171  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-25 14:26:23.171  5513  5560 I jxcore-log: 
,10-25 14:26:23.171  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-25 14:26:23.171  5513  5560 I jxcore-log: 
10-25 14:26:23.172  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 14:26:23.172  5513  5560 I jxcore-log: 
10-25 14:26:23.172  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 14:26:23.172  5513  5560 I jxcore-log: 
10-25 14:26:23.172  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.172  5513  5560 I jxcore-log: 
10-25 14:26:23.172  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.172  5513  5560 I jxcore-log: 
,10-25 14:26:23.172  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.172  5513  5560 I jxcore-log: 
10-25 14:26:23.173  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 14:26:23.173  5513  5560 I jxcore-log: 
10-25 14:26:23.173  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.173  5513  5560 I jxcore-log: 
10-25 14:26:23.173  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 14:26:23.173  5513  5560 I jxcore-log: 
10-25 14:26:23.173  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.173  5513  5560 I jxcore-log: 
10-25 14:26:23.173  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 14:26:23.173  5513  5560 I jxcore-log: 
10-25 14:26:23.174  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.174  5513  5560 I jxcore-log: 
10-25 14:26:23.174  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 14:26:23.174  5513  5560 I jxcore-log: 
10-25 14:26:23.174  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.174  5513  5560 I jxcore-log: 
10-25 14:26:23.174  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.174  5513  5560 I jxcore-log: 
10-25 14:26:23.175  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.175  5513  5560 I jxcore-log: 
10-25 14:26:23.175  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.175  5513  5560 I jxcore-log: 
10-25 14:26:23.175  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.175  5513  5560 I jxcore-log: 
10-25 14:26:23.175  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.175  5513  5560 I jxcore-log: 
10-25 14:26:23.176  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.176  5513  5560 I jxcore-log: 
10-25 14:26:23.176  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.176  5513  5560 I jxcore-log: 
10-25 14:26:23.177  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.177  5513  5560 I jxcore-log: 
10-25 14:26:23.178  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.178  5513  5560 I jxcore-log: 
10-25 14:26:23.178  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetoo,th":"off","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.178  5513  5560 I jxcore-log: 
10-25 14:26:23.178  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.178  5513  5560 I jxcore-log: 
10-25 14:26:23.178  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.178  5513  5560 I jxcore-log: 
10-25 14:26:23.178  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.178  5513  5560 I jxcore-log: 
10-25 14:26:23.179  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.179  5513  5560 I jxcore-log: 
10-25 14:26:23.179  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.179  5513  5560 I jxcore-log: 
10-25 14:26:23.179  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.179  5513  5560 I jxcore-log: 
,10-25 14:26:23.179  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.179  5513  5560 I jxcore-log: 
10-25 14:26:23.179  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.179  5513  5560 I jxcore-log: 
10-25 14:26:23.180  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.180  5513  5560 I jxcore-log: 
10-25 14:26:23.180  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.180  5513  5560 I jxcore-log: 
10-25 14:26:23.180  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.180  5513  5560 I jxcore-log: 
10-25 14:26:23.180  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.180  5513  5560 I jxcore-log: 
,10-25 14:26:23.180  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.180  5513  5560 I jxcore-log: 
10-25 14:26:23.181  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.181  5513  5560 I jxcore-log: 
10-25 14:26:23.181  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.181  5513  5560 I jxcore-log: 
,10-25 14:26:23.181  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.181  5513  5560 I jxcore-log: 
10-25 14:26:23.181  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.181  5513  5560 I jxcore-log: 
,10-25 14:26:23.181  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.181  5513  5560 I jxcore-log: 
10-25 14:26:23.181  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.181  5513  5560 I jxcore-log: 
10-25 14:26:23.182  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 14:26:23.182  5513  5560 I jxcore-log: 
10-25 14:26:23.182  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.182  5513  5560 I jxcore-log: 
10-25 14:26:23.182  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 14:26:23.182  5513  5560 I jxcore-log: 
,10-25 14:26:23.182  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.182  5513  5560 I jxcore-log: 
10-25 14:26:23.182  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 14:26:23.182  5513  5560 I jxcore-log: 
10-25 14:26:23.183  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.183  5513  5560 I jxcore-log: 
10-25 14:26:23.183  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.183  5513  5560 I jxcore-log: 
10-25 14:26:23.183  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.183  5513  5560 I jxcore-log: 
10-25 14:26:23.183  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.183  5513  5560 I jxcore-log: 
10-25 14:26:23.183  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.183  5513  5560 I jxcore-log: 
10-25 14:26:23.183  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.183  5513  5560 I jxcore-log: 
,10-25 14:26:23.184  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.184  5513  5560 I jxcore-log: 
10-25 14:26:23.184  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 14:26:23.184  5513  5560 I jxcore-log: 
10-25 14:26:23.184  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.184  5513  5560 I jxcore-log: 
10-25 14:26:23.184  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-25 14:26:23.184  5513  5560 I jxcore-log: 
10-25 14:26:23.184  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 14:26:23.184  5513  5560 I jxcore-log: 
10-25 14:26:23.185  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.185  5513  5560 I jxcore-log: 
10-25 14:26:23.185  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 14:26:23.185  5513  5560 I jxcore-log: 
,10-25 14:26:23.185  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.185  5513  5560 I jxcore-log: 
10-25 14:26:23.185  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 14:26:23.185  5513  5560 I jxcore-log: 
10-25 14:26:23.185  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 14:26:23.185  5513  5560 I jxcore-log: 
10-25 14:26:23.186  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-25 14:26:23.186  5513  5560 I jxcore-log: 
,10-25 14:26:23.186  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
10-25 14:26:23.186  5513  5560 I jxcore-log: 
10-25 14:26:23.186  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 14:26:23.186  5513  5560 I jxcore-log: 
10-25 14:26:23.187  5513  5513 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-25 14:26:23.191  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-25 14:26:23.191  5513  5560 I jxcore-log: 
10-25 14:26:23.191  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - WARN testUtils: 'myNameCallback not set!'
10-25 14:26:23.191  5513  5560 I jxcore-log: 
,10-25 14:26:23.192  5513  5560 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-25 14:26:23.193  5513  5560 I jxcore-log: 2016-10-25 12:26:23 - DEBUG UnitTest_app: 'Running for NATIVE network type'
10-25 14:26:23.193  5513  5560 I jxcore-log: 
,10-25 14:26:23.540   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:24.542   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:25.191  5513  5560 I jxcore-log: 2016-10-25 12:26:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-25 14:26:25.191  5513  5560 I jxcore-log: 
,10-25 14:26:25.518  5513  5560 I jxcore-log: 2016-10-25 12:26:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-25 14:26:25.518  5513  5560 I jxcore-log: 
,10-25 14:26:25.533  5513  5560 I jxcore-log: 2016-10-25 12:26:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-25 14:26:25.533  5513  5560 I jxcore-log: 
,10-25 14:26:25.542   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-25 14:26:26.613  5513  5560 I jxcore-log: 2016-10-25 12:26:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-25 14:26:26.613  5513  5560 I jxcore-log: 
,10-25 14:26:26.760  5513  5560 I jxcore-log: 2016-10-25 12:26:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-25 14:26:26.760  5513  5560 I jxcore-log: 
,10-25 14:26:26.765  5513  5560 I jxcore-log: 2016-10-25 12:26:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-25 14:26:26.765  5513  5560 I jxcore-log: 
,10-25 14:26:26.770  5513  5560 I jxcore-log: 2016-10-25 12:26:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-25 14:26:26.770  5513  5560 I jxcore-log: 
,10-25 14:26:27.244  5513  5560 I jxcore-log: 2016-10-25 12:26:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-25 14:26:27.244  5513  5560 I jxcore-log: 
,10-25 14:26:27.286  5513  5560 I jxcore-log: 2016-10-25 12:26:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-25 14:26:27.286  5513  5560 I jxcore-log: 
,10-25 14:26:27.299  5513  5560 I jxcore-log: 2016-10-25 12:26:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-25 14:26:27.299  5513  5560 I jxcore-log: 
,10-25 14:26:27.303  5513  5560 I jxcore-log: 2016-10-25 12:26:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-25 14:26:27.303  5513  5560 I jxcore-log: 
,10-25 14:26:27.576  5513  5560 I jxcore-log: 2016-10-25 12:26:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-25 14:26:27.576  5513  5560 I jxcore-log: 
,10-25 14:26:27.699  5513  5560 I jxcore-log: 2016-10-25 12:26:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-25 14:26:27.699  5513  5560 I jxcore-log: 
,10-25 14:26:28.069  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-25 14:26:28.069  5513  5560 I jxcore-log: 
,10-25 14:26:28.102  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
10-25 14:26:28.102  5513  5560 I jxcore-log: 
,10-25 14:26:28.108  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-25 14:26:28.108  5513  5560 I jxcore-log: 
,10-25 14:26:28.113  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-25 14:26:28.113  5513  5560 I jxcore-log: 
,10-25 14:26:28.121  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
10-25 14:26:28.121  5513  5560 I jxcore-log: 
,10-25 14:26:28.134  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-25 14:26:28.134  5513  5560 I jxcore-log: 
,10-25 14:26:28.140  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-25 14:26:28.140  5513  5560 I jxcore-log: 
,10-25 14:26:28.168  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-25 14:26:28.168  5513  5560 I jxcore-log: 
,10-25 14:26:28.205  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-25 14:26:28.205  5513  5560 I jxcore-log: 
,10-25 14:26:28.212  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-25 14:26:28.212  5513  5560 I jxcore-log: 
,10-25 14:26:28.219  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-25 14:26:28.219  5513  5560 I jxcore-log: 
,10-25 14:26:28.234  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-25 14:26:28.234  5513  5560 I jxcore-log: 
,10-25 14:26:28.238  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-25 14:26:28.238  5513  5560 I jxcore-log: 
,10-25 14:26:28.244  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-25 14:26:28.244  5513  5560 I jxcore-log: 
,10-25 14:26:28.249  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-25 14:26:28.249  5513  5560 I jxcore-log: 
,10-25 14:26:28.262  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-25 14:26:28.262  5513  5560 I jxcore-log: 
,10-25 14:26:28.285  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-25 14:26:28.285  5513  5560 I jxcore-log: 
,10-25 14:26:28.296  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-25 14:26:28.296  5513  5560 I jxcore-log: 
,10-25 14:26:28.308  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-25 14:26:28.308  5513  5560 I jxcore-log: 
,10-25 14:26:28.318  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-25 14:26:28.318  5513  5560 I jxcore-log: 
,10-25 14:26:28.330  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-25 14:26:28.330  5513  5560 I jxcore-log: 
,10-25 14:26:28.340  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-25 14:26:28.340  5513  5560 I jxcore-log: 
,10-25 14:26:28.345  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-25 14:26:28.345  5513  5560 I jxcore-log: 
,10-25 14:26:28.351  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
10-25 14:26:28.351  5513  5560 I jxcore-log: 
,10-25 14:26:28.357  5513  5560 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-25 14:26:28.358  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - INFO testUtils: 'BLE multiple advertisement supported'
10-25 14:26:28.358  5513  5560 I jxcore-log: 
,10-25 14:26:28.433  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:28.433  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:28.433  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:28.433  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:28.433  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:28.433  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:28.433  5513  5560 I jxcore-log: 
,10-25 14:26:28.588   926   946 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,10-25 14:26:28.587   937   937 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[31194]" dev="sockfs" ino=31194 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:28.587   937   937 W Binder_2: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[31194]" dev="sockfs" ino=31194 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:28.595  3528  3528 I Keyboard.Facilitator: onFinishInput()
,10-25 14:26:28.621   926   946 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-25 14:26:28.621   926   946 I Adreno  : Build Date                       : 12/06/15
10-25 14:26:28.621   926   946 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-25 14:26:28.621   926   946 I Adreno  : Local Branch                     : mybranch17112971
10-25 14:26:28.621   926   946 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-25 14:26:28.621   926   946 I Adreno  : Remote Branch                    : NONE
10-25 14:26:28.621   926   946 I Adreno  : Reconstruct Branch               : NOTHING
,10-25 14:26:28.665   383   407 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (226 us)
,10-25 14:26:28.700  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:28.700  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:28.700  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:28.700  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:28.700  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:28.700  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:28.700  5513  5560 I jxcore-log: 
,10-25 14:26:28.702  5513  5560 I jxcore-log: 2016-10-25 12:26:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:28.702  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:28.702  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:28.702  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:28.702  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:28.702  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:28.702  5513  5560 I jxcore-log: 
,10-25 14:26:29.302  5513  5560 I jxcore-log: 2016-10-25 12:26:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:29.302  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:29.302  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:29.302  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:29.302  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:29.302  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:29.302  5513  5560 I jxcore-log: 
,10-25 14:26:29.306  5513  5560 I jxcore-log: 2016-10-25 12:26:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:29.306  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:29.306  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:29.306  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:29.306  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:29.306  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:29.306  5513  5560 I jxcore-log: 
,10-25 14:26:29.311  5513  5513 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-25 14:26:29.311  5513  5513 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,10-25 14:26:29.340   926   946 I sensors : batch
,10-25 14:26:29.340   926   946 V KeyguardServiceDelegate: onScreenTurnedOff()
,10-25 14:26:29.342  5513  5513 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16b1b00 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@18b3413, 16908290=android.view.AbsSavedState$1@18b3413}, android:focusedViewId=100}]}]
,10-25 14:26:29.342  5513  5513 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
10-25 14:26:29.343  5513  5513 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-25 14:26:29.343  5513  5513 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,10-25 14:26:29.345   926   946 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
10-25 14:26:29.345   926   946 I sensors : activate
10-25 14:26:29.346   383   383 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f8a243c00
,10-25 14:26:29.346   383   383 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
10-25 14:26:29.346   926   944 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
10-25 14:26:29.347   926  2618 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,10-25 14:26:29.351   926  2618 I hubconnection: sensorhub said: 'activate 7 enable:0'
,10-25 14:26:29.638   383   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,10-25 14:26:29.639   383   383 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,10-25 14:26:29.644   926  2941 D SurfaceControl: Excessive delay in setPowerMode(): 298ms
,10-25 14:26:29.658   926   946 I DreamManagerService: Entering dreamland.
10-25 14:26:29.658   926   946 I PowerManagerService: Dozing...
,10-25 14:26:29.659   926   941 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,10-25 14:26:29.671  3040  3040 W Binder_3: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[31478]" dev="sockfs" ino=31478 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:29.671  3040  3040 W Binder_3: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[31478]" dev="sockfs" ino=31478 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:29.677   926  3290 I sensors : batch
10-25 14:26:29.677   926  3290 I sensors : activate
,10-25 14:26:29.680   926  2618 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,10-25 14:26:29.681   926  2618 I hubconnection: sensorhub said: 'activate 21 enable:1'
,10-25 14:26:29.684   511  2879 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,10-25 14:26:29.702  3626  4606 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,10-25 14:26:29.702  3626  4606 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-25 14:26:29.702  3626  4606 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-25 14:26:29.702   524  1069 D         : oem-qmi: Connection accepted
10-25 14:26:29.702   926  2829 E native  : do suspend false
10-25 14:26:29.702   524  1069 D         : oem-qmi: Waiting to accept connection
,10-25 14:26:29.704   926   926 I sensors : activate
10-25 14:26:29.704   511  2878 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,10-25 14:26:29.707   926  2618 I hubconnection: sensorhub said: 'activate 31 enable:0'
,10-25 14:26:29.708  3626  4606 D         : oem_qmi_lib:output 0
,10-25 14:26:29.708  3626  4606 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-25 14:26:29.715   926  2829 D WifiConfigStore: No blacklist allowed without epno enabled
,10-25 14:26:29.722   926  2829 E native  : do suspend true
,10-25 14:26:29.727  3626  4606 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,10-25 14:26:29.727  3626  4606 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-25 14:26:29.727  3626  4606 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
,10-25 14:26:29.727   524  1069 D         : oem-qmi: Connection accepted
10-25 14:26:29.727   524  1069 D         : oem-qmi: Waiting to accept connection
,10-25 14:26:29.729  3626  4606 D         : oem_qmi_lib:output 0
,10-25 14:26:29.730  3626  4606 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-25 14:26:29.865  5513  5560 I jxcore-log: 2016-10-25 12:26:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:29.865  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:29.865  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:29.865  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:29.865  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:29.865  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:29.865  5513  5560 I jxcore-log: 
,10-25 14:26:29.868  5513  5560 I jxcore-log: 2016-10-25 12:26:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:29.868  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:29.868  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:29.868  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:29.868  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:29.868  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:29.868  5513  5560 I jxcore-log: 
,10-25 14:26:29.925   506   920 D TetherController: Setting IP forward enable = 1
,10-25 14:26:30.197   926  2829 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,10-25 14:26:30.908  5513  5560 I jxcore-log: 2016-10-25 12:26:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:30.908  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:30.908  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:30.908  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:30.908  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:30.908  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:30.908  5513  5560 I jxcore-log: 
,10-25 14:26:30.917  5513  5560 I jxcore-log: 2016-10-25 12:26:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,10-25 14:26:30.917  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:30.917  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:30.917  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:30.917  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:30.917  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:30.917  5513  5560 I jxcore-log: 
,10-25 14:26:31.958  5513  5560 I jxcore-log: 2016-10-25 12:26:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:31.958  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:31.958  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:31.958  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:31.958  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:31.958  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:31.958  5513  5560 I jxcore-log: 
,10-25 14:26:31.961  5513  5560 I jxcore-log: 2016-10-25 12:26:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:31.961  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:31.961  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:31.961  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:31.961  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:31.961  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:31.961  5513  5560 I jxcore-log: 
,10-25 14:26:32.997  5513  5560 I jxcore-log: 2016-10-25 12:26:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:32.997  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:32.997  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:32.997  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:32.997  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:32.997  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:32.997  5513  5560 I jxcore-log: 
,10-25 14:26:33.002  5513  5560 I jxcore-log: 2016-10-25 12:26:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:33.002  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:33.002  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:33.002  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:33.002  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:33.002  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:33.002  5513  5560 I jxcore-log: 
,10-25 14:26:33.678  3978  4326 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,10-25 14:26:34.044  5513  5560 I jxcore-log: 2016-10-25 12:26:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:34.044  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:34.044  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:34.044  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:34.044  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:34.044  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:34.044  5513  5560 I jxcore-log: 
,10-25 14:26:34.049  5513  5560 I jxcore-log: 2016-10-25 12:26:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:34.049  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:34.049  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:34.049  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:34.049  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:34.049  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:34.049  5513  5560 I jxcore-log: 
,10-25 14:26:34.368   926  5810 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157137, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-25 14:26:35.082  5513  5560 I jxcore-log: 2016-10-25 12:26:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:35.082  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:35.082  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:35.082  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:35.082  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:35.082  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:35.082  5513  5560 I jxcore-log: 
,10-25 14:26:35.086  5513  5560 I jxcore-log: 2016-10-25 12:26:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:35.086  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:35.086  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:35.086  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:35.086  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:35.086  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:35.086  5513  5560 I jxcore-log: 
,10-25 14:26:36.119  5513  5560 I jxcore-log: 2016-10-25 12:26:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:36.119  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:36.119  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:36.119  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:36.119  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:36.119  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:36.119  5513  5560 I jxcore-log: 
,10-25 14:26:36.123  5513  5560 I jxcore-log: 2016-10-25 12:26:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:36.123  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:36.123  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:36.123  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:36.123  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:36.123  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:36.123  5513  5560 I jxcore-log: 
,10-25 14:26:36.811   926  2829 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,10-25 14:26:37.201  5513  5560 I jxcore-log: 2016-10-25 12:26:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:37.201  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:37.201  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:37.201  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:37.201  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:37.201  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:37.201  5513  5560 I jxcore-log: 
,10-25 14:26:37.207  5513  5560 I jxcore-log: 2016-10-25 12:26:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:37.207  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:37.207  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:37.207  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:37.207  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:37.207  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:37.207  5513  5560 I jxcore-log: 
,10-25 14:26:38.248  5513  5560 I jxcore-log: 2016-10-25 12:26:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:38.248  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:38.248  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:38.248  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:38.248  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:38.248  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:38.248  5513  5560 I jxcore-log: 
,10-25 14:26:38.254  5513  5560 I jxcore-log: 2016-10-25 12:26:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:38.254  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:38.254  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:38.254  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:38.254  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:38.254  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:38.254  5513  5560 I jxcore-log: 
,10-25 14:26:39.283  5513  5560 I jxcore-log: 2016-10-25 12:26:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:39.283  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:39.283  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:39.283  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:39.283  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:39.283  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:39.283  5513  5560 I jxcore-log: 
,10-25 14:26:39.289  5513  5560 I jxcore-log: 2016-10-25 12:26:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:39.289  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:39.289  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:39.289  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:39.289  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:39.289  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:39.289  5513  5560 I jxcore-log: 
,10-25 14:26:40.081   926  5810 D NetlinkSocketObserver: NeighborEvent{elapsedMs=162850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,10-25 14:26:40.543   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:41.544   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:42.545   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:43.343  5513  5560 I jxcore-log: 2016-10-25 12:26:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:43.343  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:43.343  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:43.343  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:43.343  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:43.343  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:43.343  5513  5560 I jxcore-log: 
,10-25 14:26:43.348  5513  5560 I jxcore-log: 2016-10-25 12:26:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:43.348  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:43.348  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:43.348  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:43.348  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:43.348  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:43.348  5513  5560 I jxcore-log: 
,10-25 14:26:43.547   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:44.381  5513  5560 I jxcore-log: 2016-10-25 12:26:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:44.381  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:44.381  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:44.381  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:44.381  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:44.381  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:44.381  5513  5560 I jxcore-log: 
,10-25 14:26:44.385  5513  5560 I jxcore-log: 2016-10-25 12:26:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,10-25 14:26:44.385  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:44.385  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:44.385  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:44.385  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:44.385  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:44.385  5513  5560 I jxcore-log: 
,10-25 14:26:44.548   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 14:26:45.416  5513  5560 I jxcore-log: 2016-10-25 12:26:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 14:26:45.416  5513  5560 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 14:26:45.416  5513  5560 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 14:26:45.416  5513  5560 I jxcore-log: emit@events.js:82:1
10-25 14:26:45.416  5513  5560 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 14:26:45.416  5513  5560 I jxcore-log: emit@events.js:82:1'
10-25 14:26:45.416  5513  5560 I jxcore-log: 
,10-25 14:26:45.426  5513  5560 E jxcore  : Error!: error is undefined
10-25 14:26:45.426  5513  5560 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-25 14:26:45.431  5513  5560 I jxcore-log: 2016-10-25 12:26:45 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-25 14:26:45.431  5513  5560 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
10-25 14:26:45.431  5513  5560 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-25 14:26:45.431  5513  5560 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-25 14:26:45.431  5513  5560 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-25 14:26:45.431  5513  5560 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-25 14:26:45.431  5513  5560 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-25 14:26:45.431  5513  5560 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-25 14:26:45.433  5513  5560 I jxcore-log: 2016-10-25 12:26:45 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-25 14:26:45.433  5513  5560 I jxcore-log: 
,10-25 14:26:45.435  5513  5560 E jxcore-log: TypeError: 
10-25 14:26:45.435  5513  5560 E jxcore-log: error is undefined
10-25 14:26:45.435  5513  5560 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
10-25 14:26:45.435  5513  5560 E jxcore-log: 
,10-25 14:26:45.523   926   937 I WindowState: WIN DEATH: Window{634c5ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-25 14:26:45.524   926  2830 D WifiService: Client connection lost with reason: 4
10-25 14:26:45.524   926  3286 D GraphicsStats: Buffer count: 2
,10-25 14:26:45.536   526   526 I Zygote  : Process 5513 exited cleanly (139)
,10-25 14:26:45.540   926  3290 I ActivityManager: Process com.test.thalitest (pid 5513) has died
,10-25 14:26:45.548   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-25 14:26:45.558   926  3290 I ActivityManager: Start proc 5894:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-25 14:26:45.638  5894  5894 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-25 14:26:45.657  5894  5894 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-25 14:26:45.664  5894  5894 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8430-8433)
,10-25 14:26:45.664  5894  5894 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-25 14:26:45.674  5894  5894 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {725c6fc}
10-25 14:26:45.674  5894  5894 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-25 14:26:45.674  5894  5894 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-25 14:26:45.678  5894  5894 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-25 14:26:45.678  5894  5894 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-25 14:26:45.689  5894  5894 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-25 14:26:45.697  5894  5894 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-25 14:26:45.697  5894  5894 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-25 14:26:45.697  5894  5894 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-25 14:26:45.697  5894  5894 I Adreno  : Build Date                       : 12/06/15
10-25 14:26:45.697  5894  5894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-25 14:26:45.697  5894  5894 I Adreno  : Local Branch                     : mybranch17112971
10-25 14:26:45.697  5894  5894 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-25 14:26:45.697  5894  5894 I Adreno  : Remote Branch                    : NONE
10-25 14:26:45.697  5894  5894 I Adreno  : Reconstruct Branch               : NOTHING
,10-25 14:26:45.729   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@99d8392:true
,10-25 14:26:45.741   949   949 W Binder_3: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[15717]" dev="sockfs" ino=15717 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:45.741   949   949 W Binder_3: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[15717]" dev="sockfs" ino=15717 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:45.754  5894  5894 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-25 14:26:45.761  5894  5894 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-25 14:26:45.791   949   949 W Binder_3: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[36824]" dev="sockfs" ino=36824 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:45.796  5894  5930 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-25 14:26:45.791   949   949 W Binder_3: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[36824]" dev="sockfs" ino=36824 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:45.797  3044  3044 W Binder_4: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[33963]" dev="sockfs" ino=33963 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:45.797  3044  3044 W Binder_4: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[33963]" dev="sockfs" ino=33963 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:45.804  5894  5917 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-25 14:26:45.843  5894  5930 I OpenGLRenderer: Initialized EGL, version 1.4
,10-25 14:26:45.902   926  3044 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5513 uid 10077
,10-25 14:26:45.897  3044  3044 W Binder_4: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[36879]" dev="sockfs" ino=36879 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-25 14:26:45.897  3044  3044 W Binder_4: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[36879]" dev="sockfs" ino=36879 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-25 14:26:45.903  5892  5892 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-25 14:26:45.903   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +323ms (total +361ms)
,10-25 14:26:45.904   937   937 W Binder_2: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[36878]" dev="sockfs" ino=36878 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:45.904   937   937 W Binder_2: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[36878]" dev="sockfs" ino=36878 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 14:26:45.913  3528  3528 I Keyboard.Facilitator: onFinishInput()
,10-25 14:26:45.921  5892  5892 D AndroidRuntime: CheckJNI is OFF
,10-25 14:26:45.924  5894  5894 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5894
,10-25 14:26:45.943  5892  5892 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-25 14:26:45.968  5892  5892 I Radio-JNI: register_android_hardware_Radio DONE
,10-25 14:26:45.982  5892  5892 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-25 14:26:45.987   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
10-25 14:26:45.987   926   939 I ActivityManager: Killing 5894:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-25 14:26:46.000   926  2818 W InputDispatcher: channel 'a650789 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-25 14:26:46.001   926  2818 E InputDispatcher: channel 'a650789 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
10-25 14:26:46.001   926  3637 D GraphicsStats: Buffer count: 2
10-25 14:26:46.001   926  3639 I WindowState: WIN DEATH: Window{a650789 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-25 14:26:46.001   926  3639 W InputDispatcher: Attempted to unregister already unregistered input channel 'a650789 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,10-25 14:26:46.100   926   939 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
10-25 14:26:46.101   926   939 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-25 14:26:46.102   926   939 E ActivityManager: Failure starting process com.test.thalitest
10-25 14:26:46.102   926   939 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-25 14:26:46.102   926   939 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:26:46.102   926   939 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:26:46.102   926   939 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-25 14:26:46.102   926   939 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-25 14:26:46.102   926   939 I ActivityManager:   Force finishing activity ActivityRecord{448c2e3 u0 com.test.thalitest/.MainActivity t66}
,10-25 14:26:46.105   926   950 I art     : Starting a blocking GC Explicit
,10-25 14:26:46.110   926  3286 W ActivityManager: Spurious death for ProcessRecord{48697af 0:com.test.thalitest/u0a77}, curProc for 5894: null
,10-25 14:26:46.189   926   950 I art     : Explicit concurrent mark sweep GC freed 15423(1024KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 1.579ms total 83.598ms
,10-25 14:26:46.208   926   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-25 14:26:46.212  5892  5892 I art     : System.exit called, status: 0
,10-25 14:26:46.212  5892  5892 I AndroidRuntime: VM exiting with result code 0.
,10-25 14:26:46.217   926   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-25 14:26:46.227   926   939 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-25 14:26:46.231  5745  5745 D BluetoothMapAppObserver: onReceive
,10-25 14:26:46.231  5745  5745 D BluetoothMapAppObserver: The removed package is: com.test.thalitest,
,10-25 14:26:46.233  3528  3528 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-25 14:26:46.234  3978  4035 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-25 14:26:46.244   926  2819 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-25 14:26:46.272  3528  5944 I Keyboard.Facilitator.DecoderInitializer: run()
,10-25 14:26:46.275  3626  3626 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-25 14:26:46.276  3266  5945 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-25 14:26:46.291  3528  5944 I Decoder : createOrResetDecoder
,10-25 14:26:46.301   392   392 W kworker/3:2: type=1400 audit(0.0:141): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 14:26:46.313  3458  3458 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-25 14:26:46.313  3458  3458 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-25 14:26:46.307   392   392 W kworker/3:2: type=1400 audit(0.0:142): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 14:26:46.321   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-25 14:26:46.321   392   392 W kworker/3:2: type=1400 audit(0.0:143): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 14:26:46.344   926   938 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
10-25 14:26:46.345   926   938 E PackageManager: Failed to write settings, restoring backup
10-25 14:26:46.345   926   938 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
10-25 14:26:46.345   926   938 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
10-25 14:26:46.345   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
10-25 14:26:46.345   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-25 14:26:46.345   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-25 14:26:46.345   926   938 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:26:46.345   926   938 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:26:46.345   926   938 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-25 14:26:46.344  3646  3756 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-25 14:26:46.349   926   939 E DropBoxManagerService: Can't write: system_server_wtf
10-25 14:26:46.349   926   939 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-25 14:26:46.349   926   939 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-25 14:26:46.349   926   939 E DropBoxManagerService: 	... 13 more
,10-25 14:26:46.360   926  3637 I ActivityManager: Start proc 5951:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-25 14:26:46.361  3646  3756 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-25 14:26:46.361  3646  3756 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3646
10-25 14:26:46.361  3646  3756 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:26:46.361  3646  3756 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-25 14:26:46.368   926  5962 E DropBoxManagerService: Can't write: system_app_crash
10-25 14:26:46.368   926  5962 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-25 14:26:46.368   926  5962 E DropBoxManagerService: 	... 5 more
,10-25 14:26:46.371   926  3044 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-25 14:26:46.372  3266  3304 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjFEAA9D9B8) - 
10-25 14:26:46.372  3821  5964 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
10-25 14:26:46.373  3821  5964 D AccountUtils: Clearing selected account for com.test.thalitest
,10-25 14:26:46.377  3646  3756 I Process : Sending signal. PID: 3646 SIG: 9
,10-25 14:26:46.380  3458  3458 I ConfigService: onCreate
,10-25 14:26:46.386  3458  5966 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-25 14:26:46.386  3458  5966 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-25 14:26:46.386  3458  5966 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,10-25 14:26:46.388  3458  5966 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-25 14:26:46.396  3458  3458 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/ns.db'.
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 14:26:46.396  3458  3458 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-25 14:26:46.397  3458  3458 D AndroidRuntime: Shutting down VM

```
