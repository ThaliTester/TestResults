#### Test 94407748f58d03e_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-21 15:34:31.577  3982  4373 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-21 15:34:32.079  5490  5490 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-21 15:34:32.084  5490  5490 D AndroidRuntime: CheckJNI is OFF
11-21 15:34:32.112  5490  5490 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-21 15:34:32.145  5490  5490 I Radio-JNI: register_android_hardware_Radio DONE
11-21 15:34:32.160  5490  5490 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-21 15:34:32.170   925  3767 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-21 15:34:32.192  5490  5490 D AndroidRuntime: Shutting down VM
11-21 15:34:32.200  3872  3886 W SearchService: Abort, client detached.
11-21 15:34:32.206  3872  3872 I HotwordDetector: Closing mic
11-21 15:34:32.207  3872  4095 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@60fd6e1
11-21 15:34:32.207  3872  4111 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-21 15:34:32.221   925  3747 I ActivityManager: Start proc 5499:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-21 15:34:32.277   511  4113 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-21 15:34:32.278   511  4113 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-21 15:34:32.281   511  4113 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-21 15:34:32.281   511  4113 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-21 15:34:32.282   511  2912 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-21 15:34:32.284  3872  4103 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-21 15:34:32.285  3872  4109 I MicroRecognitionRnrImpl: Detection finished
11-21 15:34:32.303  5499  5499 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-21 15:34:32.322  5499  5499 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-21 15:34:32.346  5499  5499 I LibraryLoader: Time to load native libraries: 21 ms (timestamps 7894-7915)
11-21 15:34:32.346  5499  5499 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 15:34:32.366  5499  5499 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cb5ebc4}
11-21 15:34:32.366  5499  5499 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 15:34:32.366  5499  5499 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-21 15:34:32.369  5499  5499 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-21 15:34:32.370  5499  5499 E SysUtils: ApplicationContext is null in ApplicationStatus
11-21 15:34:32.406  5499  5499 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
11-21 15:34:32.415  5499  5499 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-21 15:34:32.415  5499  5499 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-21 15:34:32.415  5499  5499 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-21 15:34:32.415  5499  5499 I Adreno  : Build Date                       : 12/06/15
11-21 15:34:32.415  5499  5499 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-21 15:34:32.415  5499  5499 I Adreno  : Local Branch                     : mybranch17112971
11-21 15:34:32.415  5499  5499 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-21 15:34:32.415  5499  5499 I Adreno  : Remote Branch                    : NONE
11-21 15:34:32.415  5499  5499 I Adreno  : Reconstruct Branch               : NOTHING
,11-21 15:34:32.455   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23d4f6c:true
,11-21 15:34:32.489   407   407 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[16821]" dev="sockfs" ino=16821 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 15:34:32.489   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[16821]" dev="sockfs" ino=16821 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 15:34:32.500  5499  5499 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-21 15:34:32.509  5499  5499 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-21 15:34:32.533   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32424]" dev="sockfs" ino=32424 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 15:34:32.533   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32424]" dev="sockfs" ino=32424 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 15:34:32.534  5499  5536 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-21 15:34:32.536  3032  3032 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[21290]" dev="sockfs" ino=21290 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 15:34:32.536  3032  3032 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[21290]" dev="sockfs" ino=21290 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 15:34:32.541  5499  5523 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-21 15:34:32.573  5499  5536 I OpenGLRenderer: Initialized EGL, version 1.4
,11-21 15:34:32.659   936   936 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30644]" dev="sockfs" ino=30644 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 15:34:32.659   936   936 W Binder_2: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[30644]" dev="sockfs" ino=30644 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 15:34:32.660   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +456ms
,11-21 15:34:32.659   935   935 W Binder_1: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[30643]" dev="sockfs" ino=30643 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 15:34:32.659   935   935 W Binder_1: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[30643]" dev="sockfs" ino=30643 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 15:34:32.663  3584  3584 I Keyboard.Facilitator: onFinishInput()
,11-21 15:34:32.702  5499  5499 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5499
,11-21 15:34:32.805  5499  5499 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-21 15:34:32.996  5499  5538 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -588510928
,11-21 15:34:33.000  5499  5538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-21 15:34:33.000  5499  5538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-21 15:34:33.000  5499  5538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-21 15:34:33.000  5499  5538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-21 15:34:33.000  5499  5538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-21 15:34:33.000  5499  5538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfda08 added. We now have 1 listener(s)
11-21 15:34:33.005  5499  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
11-21 15:34:33.006  5499  5538 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:34:33.006  5499  5538 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 15:34:33.006  5499  5538 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 15:34:33.006   925   935 I ActivityManager: Killing 5173:com.android.settings/1000 (adj 15): empty #17
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-21 15:34:33.008  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-21 15:34:33.009  5499  5538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8af2f87 added. We now have 1 listener(s)
,11-21 15:34:33.009  5499  5538 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 15:34:33.014   925  2877 D WifiService: New client listening to asynchronous messages
11-21 15:34:33.014  5499  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 15:34:33.014  5499  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-21 15:34:33.015  5499  5538 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-21 15:34:33.015  5499  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-21 15:34:33.015  5499  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-21 15:34:33.015  5499  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-21 15:34:33.015  5499  5538 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-21 15:34:33.016  5499  5538 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-21 15:34:33.033   925   935 I ActivityManager: Killing 5131:org.codeaurora.ims/1001 (adj 15): empty #18
,11-21 15:34:33.200  5499  5499 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-21 15:34:33.569  5499  5508 I art     : Background sticky concurrent mark sweep GC freed 77409(7MB) AllocSpace objects, 16(1476KB) LOS objects, 26% free, 24MB/32MB, paused 1.770ms total 278.434ms
,11-21 15:34:34.325  5499  5546 W jxcore-log: Initializing JXcore engine
11-21 15:34:34.325  5499  5546 W jxcore-log: JXcore engine is ready
,11-21 15:34:34.349  5546  5546 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11952 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-21 15:34:34.349  5546  5546 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13477]" dev="sockfs" ino=13477 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-21 15:34:34.349  5546  5546 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-21 15:34:34.349  5546  5546 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32398]" dev="sockfs" ino=32398 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-21 15:34:34.366  5499  5546 W jxcore-log: Starting JXcore engine
,11-21 15:34:34.423  5499  5546 W jxcore-log: Platform android
11-21 15:34:34.423  5499  5546 W jxcore-log: 
11-21 15:34:34.423  5499  5546 W jxcore-log: Process ARCH arm
11-21 15:34:34.423  5499  5546 W jxcore-log: 
,11-21 15:34:34.561  5499  5546 I jxcore-log: JXcore Cordova bridge is ready!
11-21 15:34:34.561  5499  5546 I jxcore-log: 
,11-21 15:34:34.561  5499  5546 W jxcore-log: JXcore engine is started
,11-21 15:34:34.583  5499  5538 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-21 15:34:34.588  5499  5499 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-21 15:34:38.691   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 15:34:39.692   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 15:34:39.855   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 15:34:40.694   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 15:34:41.695   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 15:34:42.339  3872  5548 W CronetSyncConnectionRcs: Upload content type not set.
,11-21 15:34:42.402  3484  5553 I VacuumService: Vacuum at: now=1479738882402 tag=VacuumService
,11-21 15:34:42.426  3484  5556 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-21 15:34:42.464  3484  5554 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-21 15:34:42.467  3484  5554 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-21 15:34:42.486  3484  5554 W Uploader:  no longer exists, so no auth token.
,11-21 15:34:42.493  3484  5556 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 15:34:42.696   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 15:34:42.876   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 15:34:43.040  3484  5562 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 15:34:43.189  3484  5554 W Uploader:  no longer exists, so no auth token.
,11-21 15:34:43.195  3484  5564 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 15:34:43.315  3484  5562 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 15:34:43.433  3484  5564 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 15:34:43.528  3484  5562 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 15:34:43.697   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 15:34:44.498  5499  5546 I jxcore-log: 2016-11-21 14:34:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-21 15:34:44.498  5499  5546 I jxcore-log: 
,11-21 15:34:44.500  5499  5546 I jxcore-log: 2016-11-21 14:34:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-21 15:34:44.500  5499  5546 I jxcore-log: 
,11-21 15:34:44.505  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-21 15:34:44.505  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 15:34:44.505  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 15:34:44.505  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 15:34:44.505  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 15:34:44.505  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 15:34:44.505  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 15:34:44.505  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 15:34:44.505  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 15:34:44.505  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 15:34:44.506  5499  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 15:34:44.508  5499  5546 I jxcore-log: 2016-11-21 14:34:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-21 15:34:44.508  5499  5546 I jxcore-log: 
11-21 15:34:44.510  5499  5546 I jxcore-log: 2016-11-21 14:34:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-21 15:34:44.510  5499  5546 I jxcore-log: 
,11-21 15:34:44.769  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 15:34:44.769  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2bba1 added. We now have 2 listener(s)
11-21 15:34:44.770  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:34:44.770  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 15:34:44.770  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 15:34:44.770  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-21 15:34:44.770  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79b21c6 added. We now have 2 listener(s)
11-21 15:34:44.770  5499  5546 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 15:34:44.771  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 15:34:44.772  5499  5546 D ExecuteNativeTests: Running unit tests
,11-21 15:34:44.773  5499  5546 D BluetoothAdapter: enable(): BT is already enabled..!
11-21 15:34:44.773   925  3768 D WifiService: setWifiEnabled: true pid=5499, uid=10077
11-21 15:34:44.773   925  3768 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 15:34:47.361   925  5265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=172930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 15:34:51.957   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 15:34:54.779  5499  5546 I com.test.thalitest.ThaliTestRunner: Running UT
,11-21 15:34:54.840  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 15:34:54.840  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af7098b added. We now have 3 listener(s)
11-21 15:34:54.841  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:34:54.841  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 15:34:54.841  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 15:34:54.841  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 15:34:54.841  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c999a68 added. We now have 3 listener(s)
11-21 15:34:54.842  5499  5546 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 15:34:54.842  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 15:34:54.846  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-21 15:34:54.847  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-21 15:34:54.847  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 15:34:54.847  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-21 15:34:54.847  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 15:34:54.848  5499  5546 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-21 15:34:54.848  5499  5546 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-21 15:34:54.848  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 15:34:54.848  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 15:34:54.848  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 15:34:54.848  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-21 15:34:54.849  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-21 15:34:54.849  5499  5546 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-21 15:34:54.851  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-21 15:34:54.853  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-21 15:34:54.853  5499  5546 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 15:34:54.854  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 15:34:54.855  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 15:34:54.867  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 15:34:54.867  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 15:34:54.867  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 15:34:54.867  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 15:34:54.867  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 15:34:54.867  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 15:34:54.867  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 15:34:54.867  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 15:34:54.867  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 15:34:54.868  5499  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 15:34:54.868  5499  5546 D io.jxcore.node.ConnectivityMonitor: start: OK
11-21 15:34:54.869  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-21 15:34:54.869  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-21 15:34:54.869  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.869  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.869  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.869  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-21 15:34:54.869  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 15:34:54.869  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 15:34:54.870  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 15:34:54.870  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 15:34:54.871  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 15:34:54.871  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 15:34:54.871  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 15:34:54.871  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 15:34:54.871  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 15:34:54.871  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 15:34:54.871  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 15:34:54.872  5499  5567 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 15:34:54.873  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 15:34:54.873  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 15:34:54.873  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 15:34:54.876  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 15:34:54.876  5499  5567 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 15:34:54.879  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 15:34:54.876  4549  4549 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[28514]" dev="sockfs" ino=28514 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 15:34:54.879  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 15:34:54.880  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.880  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 15:34:54.880  5499  5567 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 15:34:54.876  4549  4549 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[28514]" dev="sockfs" ino=28514 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 15:34:54.881  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 15:34:54.881  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 15:34:54.881  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
,11-21 15:34:54.882  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:54.882  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.882  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 15:34:54.882  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 15:34:54.882  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:34:54.882  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-21 15:34:54.883  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:54.883  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:54.883  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.883  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 15:34:54.883  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:54.883  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.883  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.883  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.884  5499  5546 D BluetoothAdapter: STATE_ON
,11-21 15:34:54.887  4536  4556 D BtGatt.GattService: registerClient() - UUID=d59106f6-a0a1-4e84-8462-279e60058e92
,11-21 15:34:54.887  4536  4612 D BtGatt.GattService: onClientRegistered() - UUID=d59106f6-a0a1-4e84-8462-279e60058e92, clientIf=5
,11-21 15:34:54.888  5499  5510 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 15:34:54.891  4536  4614 D BtGatt.AdvertiseManager: message : 0
,11-21 15:34:54.894  4536  4614 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 15:34:54.915  4536  4612 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 15:34:54.924  4536  4612 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 15:34:54.926  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:54.926  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.926  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 15:34:54.926  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.927  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.927  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.927  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:54.927  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.927  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 15:34:54.927  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 15:34:54.927  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.928  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.928  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:54.928  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:54.929  5499  5546 I io.jxcore.node.ConnectionHelper: start: OK
11-21 15:34:54.929  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-21 15:34:54.930  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-21 15:34:54.930  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 15:34:54.931  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 15:34:54.931  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 15:34:54.931  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:54.931  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-21 15:34:54.932  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:34:54.932  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 15:34:54.932  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-21 15:34:54.932  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-21 15:34:54.932  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 15:34:54.932  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 15:34:54.932  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 15:34:54.936  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:34:54.936  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 15:34:54.937  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:54.937  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:54.937  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 15:34:54.937  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 15:34:55.433  5499  5546 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-21 15:34:55.433  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-21 15:34:55.433  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-21 15:34:55.433  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-21 15:34:55.433  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-21 15:34:55.433  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-21 15:34:55.434  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-21 15:34:55.434  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-21 15:34:55.434  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-21 15:34:55.434  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-21 15:34:55.434  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-21 15:34:55.434  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-21 15:34:55.434  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-21 15:34:55.434  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-21 15:34:55.434  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-21 15:34:55.434  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-21 15:34:55.435  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-21 15:34:55.436  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-21 15:34:55.436  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-21 15:34:55.436  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-21 15:34:55.436  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-21 15:34:55.436  5499  5546 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 15:34:55.436  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 15:34:55.436  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 15:34:55.436  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-21 15:34:55.436  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 15:34:55.437  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 15:34:55.437  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 15:34:55.437  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 15:34:55.437  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 15:34:55.437  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-21 15:34:55.438  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-21 15:34:55.438  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 15:34:55.438  5499  5567 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 15:34:55.438  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 15:34:55.438  5499  5567 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 15:34:55.438  5499  5567 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 15:34:55.439  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.439  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 15:34:55.439  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.440  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.440  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.441  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:34:55.442  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 15:34:55.443  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:34:55.443  5499  5546 D BluetoothLeScanner: could not find callback wrapper
11-21 15:34:55.443  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 15:34:55.443  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.443  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.443  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.443  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 15:34:55.444  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.445  4536  4614 D BtGatt.AdvertiseManager: message : 1
11-21 15:34:55.446  4536  4614 D BtGatt.AdvertiseManager: stop advertise for client 5
11-21 15:34:55.459  4536  4612 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 15:34:55.459  4536  4612 D BtGatt.GattService: Client app is not null!
11-21 15:34:55.460  4536  4760 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 15:34:55.461  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 15:34:55.461  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.462  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 15:34:55.462  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.462  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.463  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.463  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 15:34:55.463  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 15:34:55.465  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 15:34:55.465  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.467  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.467  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 15:34:55.467  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.468  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.468  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 15:34:55.468  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 15:34:55.469  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 15:34:55.469  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:34:55.469  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:34:55.470  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 15:34:55.470  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 15:34:55.470  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 15:34:55.470  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.470  5499  5546 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 15:34:55.470  5499  5546 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 15:34:55.470  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-21 15:34:55.471  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-21 15:34:55.471  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.471  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.471  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.471  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 15:34:55.471  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 15:34:55.471  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 15:34:55.471  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 15:34:55.471  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 15:34:55.471  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 15:34:55.472  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.472  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.472  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 15:34:55.472  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.473  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 15:34:55.473  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 15:34:55.473  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 15:34:55.473  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 15:34:55.474  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 15:34:55.477  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.477  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.478  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-,21 15:34:55.478  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.478  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 15:34:55.478  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 15:34:55.478  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 15:34:55.478  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 15:34:55.478  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 15:34:55.478  5499  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 15:34:55.480  5499  5570 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 15:34:55.479  4549  4549 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[21313]" dev="sockfs" ino=21313 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 15:34:55.479  4549  4549 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[21313]" dev="sockfs" ino=21313 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 15:34:55.483  5499  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 15:34:55.483  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 15:34:55.483  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 15:34:55.483  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 15:34:55.488  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.488  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 15:34:55.489  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 15:34:55.489  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 15:34:55.490  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-21 15:34:55.492  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.492  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.492  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 15:34:55.493  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 15:34:55.493  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:34:55.493  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-21 15:34:55.493  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:55.493  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:55.493  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.494  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 15:34:55.494  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:55.494  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.494  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.495  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.496  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:34:55.499  4536  4556 D BtGatt.GattService: registerClient() - UUID=62573840-6dfb-401f-a194-da81f7a31bd4
11-21 15:34:55.499  4536  4612 D BtGatt.GattService: onClientRegistered() - UUID=62573840-6dfb-401f-a194-da81f7a31bd4, clientIf=5
11-21 15:34:55.500  5499  5543 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 15:34:55.501  4536  4614 D BtGatt.AdvertiseManager: message : 0
11-21 15:34:55.504  4536  4614 D BtGatt.AdvertiseManager: starting multi advertising
11-21 15:34:55.516  4536  4612 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 15:34:55.523  4536  4612 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-21 15:34:55.523  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.524  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.524  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 15:34:55.524  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.524  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.524  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.524  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.524  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.524  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 15:34:55.526  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 15:34:55.526  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.527  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.527  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.527  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:55.527  5499  5546 I io.jxcore.node.ConnectionHelper: start: OK
11-21 15:34:55.528  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 15:34:55.528  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.528  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 15:34:55.528  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 15:34:55.528  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.528  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.528  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 15:34:55.528  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.528  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 15:34:55.528  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 15:34:55.528  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.528  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.529  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 15:34:55.529  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.532  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.532  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 15:34:55.532  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.532  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.532  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:34:55.532  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 15:34:55.765   925  2876 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 15:34:56.031  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-21 15:34:56.031  5499  5546 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 15:34:56.031  5499  5546 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 15:34:56.031  5499  5546 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 15:34:56.031  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-21 15:34:56.031  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-21 15:34:56.032  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.032  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:56.032  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.033  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 15:34:56.033  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 15:34:56.033  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 15:34:56.033  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-21 15:34:56.033  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 15:34:56.033  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 15:34:56.033  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 15:34:56.033  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 15:34:56.033  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 15:34:56.033  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.033  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-21 15:34:56.034  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 15:34:56.034  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.034  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.035  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.037  4536  4614 D BtGatt.AdvertiseManager: message : 1
,11-21 15:34:56.041  4536  4614 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 15:34:56.051  4536  4612 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 15:34:56.051  4536  4612 D BtGatt.GattService: Client app is not null!
11-21 15:34:56.053  4536  4760 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 15:34:56.054  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 15:34:56.055  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.055  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 15:34:56.055  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.055  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.055  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.056  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 15:34:56.056  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:56.056  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.056  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.056  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 15:34:56.056  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 15:34:56.056  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:34:56.057  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-21 15:34:56.057  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:56.057  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:56.058  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.058  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 15:34:56.058  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:56.058  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.058  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.058  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.060  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:34:56.063  4536  4556 D BtGatt.GattService: registerClient() - UUID=8e7d2647-66a7-455f-9d60-3f949a5a1658
,11-21 15:34:56.063  4536  4612 D BtGatt.GattService: onClientRegistered() - UUID=8e7d2647-66a7-455f-9d60-3f949a5a1658, clientIf=5
,11-21 15:34:56.064  5499  5543 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 15:34:56.067  4536  4614 D BtGatt.AdvertiseManager: message : 0
,11-21 15:34:56.069  4536  4614 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 15:34:56.079  4536  4612 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 15:34:56.084  4536  4612 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 15:34:56.085  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.085  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:56.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-21 15:34:56.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.086  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 15:34:56.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.086  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-21 15:34:56.086  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 15:34:56.087  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-21 15:34:56.087  5499  5546 I io.jxcore.node.ConnectionHelper: start: OK
11-21 15:34:56.087  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.087  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 15:34:56.087  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 15:34:56.087  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.087  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.087  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 15:34:56.088  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.088  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-21 15:34:56.088  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 15:34:56.088  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.088  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.088  5499  5546 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-21 15:34:56.088  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 15:34:56.088  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 15:34:56.088  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 15:34:56.088  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 15:34:56.088  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-21 15:34:56.088  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 15:34:56.088  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 15:34:56.088  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-21 15:34:56.088  5499  5570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 15:34:56.088  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 15:34:56.088  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 15:34:56.088  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 15:34:56.088  5499  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 15:34:56.088  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 15:34:56.088  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 15:34:56.088  5499  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-21 15:34:56.089  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.089  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.089  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.089  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.089  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:34:56.090  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 15:34:56.090  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:34:56.091  5499  5546 D BluetoothLeScanner: could not find callback wrapper
11-21 15:34:56.091  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-21 15:34:56.091  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.091  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.091  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.091  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 15:34:56.091  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.092  4536  4614 D BtGatt.AdvertiseManager: message : 1
,11-21 15:34:56.092  4536  4614 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 15:34:56.098  4536  4612 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 15:34:56.098  4536  4612 D BtGatt.GattService: Client app is not null!
11-21 15:34:56.099  4536  4760 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 15:34:56.099  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 15:34:56.099  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:56.099  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 15:34:56.100  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.100  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.100  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.100  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 15:34:56.100  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 15:34:56.100  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 15:34:56.100  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.101  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.101  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 15:34:56.101  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.101  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.102  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 15:34:56.102  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 15:34:56.102  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:34:56.102  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:34:56.102  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 15:34:56.102  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 15:34:56.102  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 15:34:56.102  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.102  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 15:34:56.102  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 15:34:56.102  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.102  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-21 15:34:56.102  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 15:34:56.102  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.103  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-21 15:34:56.103  5499  5546 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-21 15:34:56.104  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.104  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.104  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.104  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.104  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 15:34:56.105  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-21 15:34:56.105  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 15:34:56.106  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-21 15:34:56.106  5499  5546 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-21 15:34:56.106  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-21 15:34:56.107  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-21 15:34:56.107  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-21 15:34:56.107  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 15:34:56.108  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 15:34:56.108  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 15:34:56.108  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 15:34:56.108  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-21 15:34:56.108  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 15:34:56.108  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 15:34:56.108  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 15:34:56.108  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 15:34:56.108  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 15:34:56.108  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 15:34:56.108  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 15:34:56.109  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-21 15:34:56.109  5499  5546 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 15:34:56.109  5499  5546 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-21 15:34:56.112  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-21 15:34:56.112  5499  5546 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-21 15:34:56.113  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-21 15:34:56.114  5499  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-21 15:34:56.119  4556  4556 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[30697]" dev="sockfs" ino=30697 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 15:34:56.119  4556  4556 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[30697]" dev="sockfs" ino=30697 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 15:34:56.114  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,11-21 15:34:56.114  5499  5546 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-21 15:34:56.115  5499  5546 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-21 15:34:56.115  5499  5546 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-21 15:34:56.115  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 15:34:56.115  5499  5546 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-21 15:34:56.115  5499  5546 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 15:34:56.115  5499  5546 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-21 15:34:56.115  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 15:34:56.115  5499  5546 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,11-21 15:34:56.115  5499  5546 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 15:34:56.115  5499  5546 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-21 15:34:56.115  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 15:34:56.115  5499  5546 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-21 15:34:56.116  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-21 15:34:56.116  5499  5546 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 15:34:56.116  5499  5546 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 15:34:56.116  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-21 15:34:56.116  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-21 15:34:56.116  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.116  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.116  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.116  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 15:34:56.116  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-21 15:34:56.116  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 15:34:56.116  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 15:34:56.117  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 15:34:56.118  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 15:34:56.118  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 15:34:56.118  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 15:34:56.118  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 15:34:56.118  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 15:34:56.118  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-21 15:34:56.118  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 15:34:56.118  5499  5574 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 15:34:56.118  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 15:34:56.118  5499  5574 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 15:34:56.120  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 15:34:56.121  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 15:34:56.121  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 15:34:56.121  5499  5574 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 15:34:56.124  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.124  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 15:34:56.125  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 15:34:56.125  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 15:34:56.125  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-21 15:34:56.127  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.127  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.127  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 15:34:56.127  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 15:34:56.127  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:34:56.128  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-21 15:34:56.128  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 15:34:56.128  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:56.128  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.128  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 15:34:56.128  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:34:56.129  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.129  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.129  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:56.130  5499  5546 D BluetoothAdapter: STATE_ON
,11-21 15:34:56.133  4536  4549 D BtGatt.GattService: registerClient() - UUID=01929aff-2a2d-40b7-9673-607797087147
,11-21 15:34:56.133  4536  4612 D BtGatt.GattService: onClientRegistered() - UUID=01929aff-2a2d-40b7-9673-607797087147, clientIf=5
,11-21 15:34:56.134  5499  5510 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 15:34:56.134  4536  4614 D BtGatt.AdvertiseManager: message : 0
,11-21 15:34:56.136  4536  4614 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 15:34:56.144  4536  4612 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 15:34:56.148  4536  4612 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 15:34:56.149  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.149  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.149  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 15:34:56.149  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:56.149  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.149  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.149  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:56.149  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.149  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 15:34:56.150  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 15:34:56.150  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:56.151  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.151  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.151  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.152  5499  5546 I io.jxcore.node.ConnectionHelper: start: OK
,11-21 15:34:56.152  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.152  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.152  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 15:34:56.152  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.154  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.154  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 15:34:56.154  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.155  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.155  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.155  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 15:34:56.652  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 15:34:56.653  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-21 15:34:56.653  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 15:34:56.653  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 15:34:56.653  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 15:34:56.654  5499  5574 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 15:34:56.654  5499  5574 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 15:34:56.654  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 15:34:56.654  5499  5574 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 15:34:56.654  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 15:34:56.654  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 15:34:56.655  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af7098b removed from the list
11-21 15:34:56.655  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 15:34:56.655  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 15:34:56.655  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 15:34:56.655  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-21 15:34:56.655  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.656  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 15:34:56.656  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.656  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:56.656  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 15:34:56.656  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.656  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 15:34:56.656  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 15:34:56.658  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:34:56.659  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 15:34:56.660  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:34:56.661  5499  5546 D BluetoothLeScanner: could not find callback wrapper
11-21 15:34:56.661  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-21 15:34:56.661  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.661  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.661  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.661  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-21 15:34:56.662  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.663  4536  4614 D BtGatt.AdvertiseManager: message : 1
,11-21 15:34:56.665  4536  4614 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 15:34:56.677  4536  4612 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 15:34:56.677  4536  4612 D BtGatt.GattService: Client app is not null!
,11-21 15:34:56.678  4536  4556 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 15:34:56.679  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 15:34:56.679  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 15:34:56.679  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 15:34:56.679  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.680  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.680  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.680  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-21 15:34:56.680  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 15:34:56.681  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 15:34:56.681  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.683  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.683  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 15:34:56.683  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.683  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:34:56.683  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c999a68 removed from the list
11-21 15:34:56.683  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:34:56.683  5499  5546 D io.jxcore.node.ConnectivityMonitor: stop
11-21 15:34:56.683  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-21 15:34:56.683  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:34:56.684  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 15:34:56.684  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.684  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 15:34:56.684  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 15:34:56.684  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.684  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-21 15:34:56.684  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 15:34:56.685  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.686  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.686  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.687  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 15:34:56.687  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 15:34:56.687  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 15:34:57.187  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 15:34:58.014   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 15:35:01.688  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-21 15:35:01.690  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-21 15:35:01.691  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 15:35:01.691  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 15:35:01.696  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 15:35:01.698  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-21 15:35:01.698  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 15:35:01.698  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 15:35:01.698  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 15:35:01.698  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 15:35:01.699  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 15:35:01.699  5499  5575 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 15:35:01.700  5499  5575 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 15:35:01.701  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-21 15:35:01.703  5499  5546 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-21 15:35:01.703  5499  5546 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 15:35:01.703  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 15:35:01.704  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 15:35:01.704  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 15:35:01.705  5499  5575 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 15:35:01.703  4549  4549 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31422]" dev="sockfs" ino=31422 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 15:35:01.703  4549  4549 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31422]" dev="sockfs" ino=31422 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 15:35:01.706  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-21 15:35:01.715  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-21 15:35:01.715  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 15:35:01.716  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 15:35:01.716  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 15:35:01.716  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 15:35:01.716  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 15:35:01.716  5499  5575 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 15:35:01.716  5499  5575 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 15:35:01.716  5499  5575 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 15:35:01.717  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 15:35:01.718  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 15:35:01.718  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 15:35:01.718  5499  5546 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af7098b not in the list
11-21 15:35:01.718  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 15:35:01.718  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-21 15:35:01.718  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 15:35:01.718  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 15:35:01.719  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-21 15:35:01.719  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:01.720  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-21 15:35:01.721  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:01.722  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 15:35:01.722  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:01.722  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:01.722  5499  5546 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c999a68 not in the list
11-21 15:35:01.722  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:35:01.722  5499  5546 D io.jxcore.node.ConnectivityMonitor: stop
11-21 15:35:01.722  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:35:01.722  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 15:35:01.724  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-21 15:35:01.725  5499  5546 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-21 15:35:01.725  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 15:35:01.726  5499  5546 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-21 15:35:01.726  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-21 15:35:01.726  5499  5546 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-21 15:35:01.726  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 15:35:01.727  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-21 15:35:01.728  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-21 15:35:01.730  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-21 15:35:01.730  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 15:35:01.730  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-21 15:35:01.731  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,11-21 15:35:01.732  5499  5546 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-21 15:35:01.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 15:35:01.732  5499  5546 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-21 15:35:01.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 15:35:01.732  5499  5546 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-21 15:35:01.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-21 15:35:01.733  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-21 15:35:01.733  5499  5546 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-21 15:35:01.733  5499  5546 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-21 15:35:01.735  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-21 15:35:01.735  5499  5546 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-21 15:35:01.735  5499  5546 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-21 15:35:01.735  5499  5546 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-21 15:35:01.735  5499  5546 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-21 15:35:01.736  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-21 15:35:01.737  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 15:35:01.737  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72279d6 added. We now have 3 listener(s)
11-21 15:35:01.739  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:35:01.739  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 15:35:01.739  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 15:35:01.739  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 15:35:01.739  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c514457 added. We now have 3 listener(s)
11-21 15:35:01.739  5499  5546 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 15:35:01.740  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 15:35:01.743  5499  5546 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 15:35:01.744   925  3313 D WifiService: setWifiEnabled: true pid=5499, uid=10077
11-21 15:35:01.744   925  3313 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 15:35:01.746  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-21 15:35:01.750  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-21 15:35:01.750  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-21 15:35:01.754  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-21 15:35:01.755  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-21 15:35:01.761  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 15:35:01.761  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 15:35:01.761  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 15:35:01.761  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 15:35:01.761  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 15:35:01.761  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 15:35:01.761  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 15:35:01.761  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 15:35:01.761  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 15:35:01.761  4536  4608 D BluetoothAdapterState: Current state: ON, message: 23
11-21 15:35:01.761  4536  4608 D BluetoothAdapterProperties: Setting state to 13
11-21 15:35:01.761  4536  4608 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-21 15:35:01.762  4536  4608 D BluetoothAdapterProperties: onBluetoothDisable()
,11-21 15:35:01.762  4536  4608 I BluetoothAdapterState: Entering PendingCommandState
,11-21 15:35:01.763  5499  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-21 15:35:01.763  5499  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 15:35:01.765  4536  4536 D BluetoothMapService: onReceive
11-21 15:35:01.765  4536  4536 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 15:35:01.765  4536  4536 D BluetoothMapService: STATE_TURNING_OFF
11-21 15:35:01.765  4536  4536 D BluetoothMapService: MAP Service closeService in
11-21 15:35:01.765  4536  4536 D BluetoothMapMasInstance0: MAP Service shutdown
11-21 15:35:01.766  4536  4536 D ObexServerSockets0: shutdown(block = true)
11-21 15:35:01.767  4536  4536 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 15:35:01.767  4536  4771 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-21 15:35:01.767  4536  4758 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-21 15:35:01.767  4536  4772 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-21 15:35:01.768  4536  4536 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-21 15:35:01.768  4536  4536 I BtOppRfcommListener: stopping Accept Thread
11-21 15:35:01.769  4536  5195 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-21 15:35:01.769  4536  5195 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-21 15:35:01.780   925   938 I ActivityManager: Start proc 5578:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-21 15:35:01.780  4536  4612 D BluetoothAdapterProperties: Scan Mode:20
11-21 15:35:01.781  4536  4608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-21 15:35:01.783  4536  4536 D HeadsetService: Received stop request...Stopping profile...
,11-21 15:35:01.785  4536  4536 V BluetoothAdapterState: isTurningOff()=true
,11-21 15:35:01.785  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-21 15:35:01.785  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
,11-21 15:35:01.785  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:01.785  3034  3045 D BluetoothHeadset: Proxy object disconnected
11-21 15:35:01.785  3034  3034 D HeadsetProfile: Bluetooth service disconnected
,11-21 15:35:01.786  3686  3701 D BluetoothHeadset: Proxy object disconnected
11-21 15:35:01.786   925   925 D BluetoothHeadset: Proxy object disconnected
11-21 15:35:01.786   925   925 D BluetoothHeadset: Proxy object disconnected
11-21 15:35:01.786   925   925 D BluetoothHeadset: Proxy object disconnected
,11-21 15:35:01.788  4536  4536 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-21 15:35:01.789  4536  4536 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-21 15:35:01.790  4536  4743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 15:35:01.790  4536  4743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 15:35:01.790  4536  4743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 15:35:01.790  4536  4612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-21 15:35:01.791  4536  4612 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-21 15:35:01.791  4536  4536 D A2dpService: Received stop request...Stopping profile...
11-21 15:35:01.791  4536  4763 D A2dpStateMachine: Exit Disconnected: -1
11-21 15:35:01.793   925   925 D BluetoothA2dp: Proxy object disconnected
,11-21 15:35:01.793  3034  3034 D BluetoothA2dp: Proxy object disconnected
11-21 15:35:01.794  4536  4536 D HidService: Received stop request...Stopping profile...
11-21 15:35:01.794  4536  4536 D HidService: Stopping Bluetooth HidService
11-21 15:35:01.795  3034  3034 D BluetoothInputDevice: Proxy object disconnected
11-21 15:35:01.795  3034  3034 D HidProfile: Bluetooth service disconnected
11-21 15:35:01.795  4536  4536 D HealthService: Received stop request...Stopping profile...
,11-21 15:35:01.797  4536  4536 D PanService: Received stop request...Stopping profile...
,11-21 15:35:01.798  3034  3034 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-21 15:35:01.798  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-21 15:35:01.798  3034  3034 D PanProfile: Bluetooth service disconnected
11-21 15:35:01.798  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-21 15:35:01.798  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:01.798  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 15:35:01.800  4536  4536 D BluetoothMapService: Received stop request...Stopping profile...
11-21 15:35:01.801  4536  4536 D BluetoothMapService: stop()
,11-21 15:35:01.802  4536  4536 D BluetoothMapAppObserver: deinitObservers()
11-21 15:35:01.802  4536  4536 D BluetoothMapAppObserver: removeReceiver()
11-21 15:35:01.803  3034  3034 D BluetoothMap: Proxy object disconnected
11-21 15:35:01.803  3034  3034 D MapProfile: Bluetooth service disconnected
,11-21 15:35:01.805  4536  4612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-21 15:35:01.805  4536  4743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 15:35:01.805  4536  4743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 15:35:01.805  4536  4743 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-21 15:35:01.805  4536  4743 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-21 15:35:01.805  4536  4743 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-21 15:35:01.805  4536  4743 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-21 15:35:01.806  4536  4536 D SapService: Received stop request...Stopping profile...
11-21 15:35:01.806  4536  4536 V SapService: stop()
11-21 15:35:01.807  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-21 15:35:01.807  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-21 15:35:01.807  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:01.807  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:01.807  4536  4536 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-21 15:35:01.808  4536  4536 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-21 15:35:01.808  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-21 15:35:01.808  4536  4612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-21 15:35:01.808  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-21 15:35:01.808  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:01.808  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:01.808  4536  4536 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-21 15:35:01.808  4536  4536 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-21 15:35:01.808  4536  4612 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-21 15:35:01.809  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-21 15:35:01.809  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-21 15:35:01.809  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:01.809  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:01.809  4536  4536 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-21 15:35:01.809  4536  4536 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-21 15:35:01.810  4536  4536 D BluetoothMapService: MAP Service closeService in
11-21 15:35:01.810  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-21 15:35:01.810  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-21 15:35:01.810  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:01.810  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:01.810  4536  4536 D BluetoothMapService: cleanup()
,11-21 15:35:01.810  4536  4536 D BluetoothMapService: MAP Service closeService in
11-21 15:35:01.811  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-21 15:35:01.811  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-21 15:35:01.811  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:01.811  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:01.811  4536  4608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-21 15:35:01.811  4536  4608 D BluetoothAdapterProperties: Setting state to 15
,11-21 15:35:01.811  4536  4608 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-21 15:35:01.812  3034  3895 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 15:35:01.813  3034  3048 D BluetoothA2dp: onBluetoothStateChange: up=false
11-21 15:35:01.813  4536  4608 I BluetoothAdapterState: Entering BleOnState
11-21 15:35:01.816  3034  3896 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-21 15:35:01.817  3034  3045 D BluetoothPan: onBluetoothStateChange on: false
11-21 15:35:01.817   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-21 15:35:01.818  3034  3895 D BluetoothMap: onBluetoothStateChange: up=false
,11-21 15:35:01.818  3686  3897 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 15:35:01.819   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
11-21 15:35:01.819  3034  3048 D BluetoothPbap: onBluetoothStateChange: up=false
11-21 15:35:01.820   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 15:35:01.820   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 15:35:01.820  4536  4608 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-21 15:35:01.821  4536  4608 D BluetoothAdapterProperties: Setting state to 16
11-21 15:35:01.821  4536  4608 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-21 15:35:01.821  4536  4608 D BluetoothAdapterProperties: onBleDisable
11-21 15:35:01.821  4536  4608 I BluetoothAdapterState: Entering PendingCommandState
,11-21 15:35:01.821  4536  4609 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-21 15:35:01.822  4536  4743 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-21 15:35:01.823  4536  4743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 15:35:01.823  4536  4612 D BluetoothAdapterProperties: Scan Mode:20
,11-21 15:35:01.836  5578  5578 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-21 15:35:01.849  5578  5578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 15:35:01.853   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ffe83df:true
,11-21 15:35:01.854  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 15:35:01.870  5578  5578 D LocalBluetoothProfileManager: Adding local MAP profile
,11-21 15:35:01.872  5578  5578 D BluetoothMap: Create BluetoothMap proxy object
,11-21 15:35:01.879  5578  5578 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-21 15:35:01.885  5578  5578 D DockEventReceiver: finishStartingService: stopping service
,11-21 15:35:01.887  5578  5578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 15:35:01.893  5578  5578 D DockEventReceiver: finishStartingService: stopping service
,11-21 15:35:01.893  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 15:35:01.895   925   936 I ActivityManager: Killing 5295:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-21 15:35:02.035  4536  4612 I bt_hci  : shut_down
,11-21 15:35:02.049  4536  4617 I bt_vendor: low_power_mode_cb
,11-21 15:35:02.053  4536  4617 D bt_hwcfg: hw_epilog_process
,11-21 15:35:02.056  4536  4617 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-21 15:35:02.056  4536  4617 I bt_vendor: epilog_cb
,11-21 15:35:02.056  4536  4617 I bt_hci  : epilog_finished_callback
,11-21 15:35:02.061  4536  4612 I bt_hci_h4: hal_close
,11-21 15:35:02.062  4536  4612 I bt_userial_vendor: device fd = 54 close
,11-21 15:35:02.182  4536  4609 D bt_stack_manager: event_shut_down_stack finished.
,11-21 15:35:02.183  4536  4608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-21 15:35:02.187  4536  4608 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-21 15:35:02.187  4536  4536 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-21 15:35:02.189  4536  4536 D BtGatt.GattService: Received stop request...Stopping profile...
,11-21 15:35:02.189  4536  4536 D BtGatt.GattService: stop()
,11-21 15:35:02.189  4536  4536 D BtGatt.AdvertiseManager: advertise clients cleared
,11-21 15:35:02.193  4536  4536 V BluetoothAdapterState: isTurningOff()=false
11-21 15:35:02.193  4536  4536 V BluetoothAdapterState: isTurningOn()=false
,11-21 15:35:02.193  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:02.194  4536  4536 V BluetoothAdapterState: isBleTurningOff()=true
,11-21 15:35:02.194  4536  4608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-21 15:35:02.195  4536  4608 D BluetoothAdapterProperties: Setting state to 10
11-21 15:35:02.195  4536  4608 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-21 15:35:02.196  4536  4608 I BluetoothAdapterState: Entering OffState
11-21 15:35:02.198   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-21 15:35:02.213  4536  4536 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-21 15:35:02.213  4536  4536 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-21 15:35:02.213  4536  4536 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-21 15:35:02.216  4536  4609 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-21 15:35:02.223  4536  4536 I art     : System.exit called, status: 0
,11-21 15:35:02.223  4536  4536 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-21 15:35:02.223  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 15:35:02.250   925   936 I ActivityManager: Process com.android.bluetooth (pid 4536) has died
,11-21 15:35:02.265  5499  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-21 15:35:02.265  5499  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 15:35:02.265  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 15:35:02.265  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 15:35:02.265  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 15:35:02.265  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-21 15:35:02.265  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 15:35:02.265  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 15:35:02.265  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 15:35:02.265  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 15:35:02.265  5499  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-21 15:35:02.265  5499  5576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 15:35:02.269  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 15:35:02.280   925   942 I ActivityManager: Start proc 5595:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-21 15:35:02.344  5595  5595 D AdapterServiceConfig: Adding HeadsetService
11-21 15:35:02.344  5595  5595 D AdapterServiceConfig: Adding A2dpService
,11-21 15:35:02.344  5595  5595 D AdapterServiceConfig: Adding HidService
11-21 15:35:02.345  5595  5595 D AdapterServiceConfig: Adding HealthService
11-21 15:35:02.345  5595  5595 D AdapterServiceConfig: Adding PanService
,11-21 15:35:02.345  5595  5595 D AdapterServiceConfig: Adding GattService
11-21 15:35:02.345  5595  5595 D AdapterServiceConfig: Adding BluetoothMapService
11-21 15:35:02.346  5595  5595 D AdapterServiceConfig: Adding SapService
,11-21 15:35:02.356   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cff50e1:true
,11-21 15:35:02.356  5595  5595 D BluetoothAdapterState: make() - Creating AdapterState
,11-21 15:35:02.358  5595  5595 I bt_bluedroid: init
,11-21 15:35:02.358  5595  5607 I BluetoothAdapterState: Entering OffState
,11-21 15:35:02.360  5595  5608 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-21 15:35:02.360  5595  5608 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-21 15:35:02.360  5595  5608 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-21 15:35:02.360  5595  5608 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-21 15:35:02.361  5595  5595 I bt_bluedroid: get_profile_interface socket
,11-21 15:35:02.362  5595  5595 I bt_bluedroid: get_profile_interface sdp
,11-21 15:35:02.362  5595  5611 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-21 15:35:02.364  5595  5611 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-21 15:35:02.367  5595  5606 I bt_bluedroid: config_hci_snoop_log
,11-21 15:35:02.369   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-21 15:35:02.376  5595  5607 D BluetoothAdapterState: Current state: OFF, message: 0
,11-21 15:35:02.376  5595  5607 D BluetoothAdapterProperties: Setting state to 14
11-21 15:35:02.376  5595  5607 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-21 15:35:02.378  5595  5607 D BluetoothBondStateMachine: make
,11-21 15:35:02.382  5595  5612 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-21 15:35:02.386  5595  5607 I BluetoothAdapterState: Entering PendingCommandState
,11-21 15:35:02.387  5595  5595 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-21 15:35:02.390  5595  5595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f89cf
11-21 15:35:02.391  5595  5595 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-21 15:35:02.392  5595  5595 D BtGatt.GattService: Received start request. Starting profile...
,11-21 15:35:02.392  5595  5595 D BtGatt.GattService: start()
11-21 15:35:02.392  5595  5595 I bt_bluedroid: get_profile_interface gatt
11-21 15:35:02.393  5595  5595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f89cf
11-21 15:35:02.393  5595  5595 D BtGatt.AdvertiseManager: advertise manager created
,11-21 15:35:02.400  5595  5595 V BluetoothAdapterState: isTurningOff()=false
11-21 15:35:02.400  5595  5595 V BluetoothAdapterState: isTurningOn()=false
11-21 15:35:02.400  5595  5595 V BluetoothAdapterState: isBleTurningOn()=true
11-21 15:35:02.400  5595  5595 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:02.400  5595  5607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-21 15:35:02.402  5595  5607 I bt_bluedroid: bt_bluedroid
,11-21 15:35:02.402  5595  5608 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-21 15:35:02.403  5595  5608 I bt_hci  : start_up
,11-21 15:35:02.410  5595  5608 I bt_vendor: alloc value 0xf3cdd871
,11-21 15:35:02.410  5595  5608 I bt_vendor: init
11-21 15:35:02.410  5595  5608 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-21 15:35:02.410  5595  5608 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-21 15:35:02.519  5595  5608 D bt_hci  : start_up starting async portion
11-21 15:35:02.519  5595  5615 I bt_hci  : event_finish_startup
11-21 15:35:02.520  5595  5615 I bt_hci_h4: hal_open
11-21 15:35:02.520  5595  5615 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-21 15:35:02.519  5616  5616 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 15:35:02.522  5595  5615 I bt_userial_vendor: device fd = 54 open
,11-21 15:35:02.536  5595  5615 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 15:35:02.539  5595  5615 D bt_hwcfg: Chipset BCM4358A3
,11-21 15:35:02.539  5595  5615 D bt_hwcfg: Target name = [BCM4358A3]
11-21 15:35:02.539  5595  5615 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-21 15:35:02.775  5595  5607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-21 15:35:02.938  5595  5615 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-21 15:35:02.938  5595  5615 D bt_hwcfg: Settlement delay -- 100 ms
,11-21 15:35:02.939  5595  5615 I bt_hwcfg: Setting fw settlement delay to 100 
,11-21 15:35:03.062  5595  5615 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 15:35:03.062  5595  5615 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-21 15:35:03.063  5595  5615 I bt_hwcfg: vendor lib fwcfg completed
11-21 15:35:03.064  5595  5615 I bt_vendor: firmware callback
11-21 15:35:03.064  5595  5615 I bt_hci  : firmware_config_callback
,11-21 15:35:03.075  5595  5618 I bt_btu  : btu_task pending for preload complete event
,11-21 15:35:03.076  5595  5618 I bt_btu_task: Bluetooth chip preload is complete
11-21 15:35:03.076  5595  5618 I bt_btu  : btu_task received preload complete event
,11-21 15:35:03.083  5595  5618 I         : BTE_InitTraceLevels -- TRC_HCI
,11-21 15:35:03.083  5595  5618 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-21 15:35:03.083  5595  5618 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-21 15:35:03.083  5595  5618 I         : BTE_InitTraceLevels -- TRC_AVDT
11-21 15:35:03.084  5595  5618 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-21 15:35:03.084  5595  5618 I         : BTE_InitTraceLevels -- TRC_A2D
11-21 15:35:03.084  5595  5618 I         : BTE_InitTraceLevels -- TRC_BNEP
11-21 15:35:03.084  5595  5618 I         : BTE_InitTraceLevels -- TRC_BTM
,11-21 15:35:03.084  5595  5618 I         : BTE_InitTraceLevels -- TRC_GAP
11-21 15:35:03.084  5595  5618 I         : BTE_InitTraceLevels -- TRC_PAN
11-21 15:35:03.084  5595  5618 I         : BTE_InitTraceLevels -- TRC_SDP
,11-21 15:35:03.084  5595  5618 I         : BTE_InitTraceLevels -- TRC_GATT
11-21 15:35:03.085  5595  5618 I         : BTE_InitTraceLevels -- TRC_SMP
11-21 15:35:03.085  5595  5618 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-21 15:35:03.085  5595  5618 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-21 15:35:03.168  5595  5618 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c5b549
,11-21 15:35:03.169  5595  5618 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c5b549 
,11-21 15:35:03.186  5595  5611 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-21 15:35:03.187  5595  5611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-21 15:35:03.188  5595  5611 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-21 15:35:03.192  5595  5611 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-21 15:35:03.196  5595  5611 D BluetoothAdapterProperties: Scan Mode:20
,11-21 15:35:03.196  5595  5611 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-21 15:35:03.197  5595  5611 D bt_hci  : do_postload posting postload work item
11-21 15:35:03.197  5595  5615 I bt_hci  : event_postload
11-21 15:35:03.197  5595  5615 I bt_vendor: sco_config_cb
11-21 15:35:03.197  5595  5615 I bt_hci  : sco_config_callback postload finished.
,11-21 15:35:03.201  5595  5611 D bt_bte_conf: Device ID record 1 : primary
,11-21 15:35:03.201  5595  5611 D bt_bte_conf:   vendorId            = 000f
11-21 15:35:03.201  5595  5611 D bt_bte_conf:   vendorIdSource      = 0001
,11-21 15:35:03.201  5595  5611 D bt_bte_conf:   product             = 1200
,11-21 15:35:03.201  5595  5611 D bt_bte_conf:   version             = 1436
11-21 15:35:03.201  5595  5611 D bt_bte_conf:   clientExecutableURL = 
11-21 15:35:03.201  5595  5611 D bt_bte_conf:   serviceDescription  = 
11-21 15:35:03.201  5595  5611 D bt_bte_conf:   documentationURL    = 
11-21 15:35:03.202  5595  5611 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-21 15:35:03.202  5595  5608 D bt_stack_manager: event_start_up_stack finished
11-21 15:35:03.203  5595  5607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-21 15:35:03.203  5595  5607 D BluetoothAdapterProperties: Setting state to 15
11-21 15:35:03.204  5595  5607 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-21 15:35:03.205  5595  5615 I bt_vendor: low_power_mode_cb
11-21 15:35:03.205  5595  5607 I BluetoothAdapterState: Entering BleOnState
11-21 15:35:03.209  5595  5607 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-21 15:35:03.209  5595  5607 D BluetoothAdapterProperties: Setting state to 11
11-21 15:35:03.209  5595  5607 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-21 15:35:03.214  5595  5595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f89cf
,11-21 15:35:03.215  5595  5595 D HeadsetService: Received start request. Starting profile...
,11-21 15:35:03.218  5595  5595 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-21 15:35:03.220  5595  5595 D HeadsetStateMachine: make
,11-21 15:35:03.232  5595  5607 I BluetoothAdapterState: Entering PendingCommandState
,11-21 15:35:03.234  5595  5595 D HeadsetStateMachine: max_hf_connections = 1
,11-21 15:35:03.234  5595  5595 I bt_bluedroid: get_profile_interface handsfree
11-21 15:35:03.234  5595  5611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-21 15:35:03.234  5595  5611 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-21 15:35:03.237  5595  5595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f89cf
,11-21 15:35:03.238  5595  5595 D A2dpService: Received start request. Starting profile...
11-21 15:35:03.238  5595  5595 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-21 15:35:03.239  5595  5595 I bt_bluedroid: get_profile_interface avrcp
,11-21 15:35:03.244  5595  5595 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-21 15:35:03.245  5595  5595 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-21 15:35:03.245  5595  5595 D A2dpStateMachine: make
11-21 15:35:03.246  5595  5595 I bt_bluedroid: get_profile_interface a2dp
11-21 15:35:03.247  5595  5611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-21 15:35:03.248  5595  5626 D A2dpStateMachine: Enter Disconnected: -2
,11-21 15:35:03.249  5595  5595 I BluetoothHidServiceJni: classInitNative: succeeds
,11-21 15:35:03.250  5595  5595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f89cf
11-21 15:35:03.251  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 15:35:03.252  5595  5595 D HidService: Received start request. Starting profile...
11-21 15:35:03.252  5595  5595 I bt_bluedroid: get_profile_interface hidhost
11-21 15:35:03.252  5595  5595 D HidService: setHidService(): set to: null
11-21 15:35:03.252  5595  5611 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c3c56d
,11-21 15:35:03.252  5595  5611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-21 15:35:03.252  5595  5595 I BluetoothHealthServiceJni: classInitNative: succeeds
11-21 15:35:03.253  5595  5595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f89cf
,11-21 15:35:03.255  5595  5595 D HealthService: Received start request. Starting profile...
11-21 15:35:03.258  5595  5595 I bt_bluedroid: get_profile_interface health
11-21 15:35:03.258  5578  5578 D BluetoothInputDevice: Proxy object connected
11-21 15:35:03.258  5578  5578 D HidProfile: Bluetooth service connected
,11-21 15:35:03.260  5595  5595 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-21 15:35:03.260  5595  5595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f89cf
11-21 15:35:03.262  5578  5578 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 15:35:03.262  5595  5595 D PanService: Received start request. Starting profile...
11-21 15:35:03.262  5595  5595 D BluetoothPanServiceJni: initializeNative(L110): pan
11-21 15:35:03.262  5595  5595 I bt_bluedroid: get_profile_interface pan
11-21 15:35:03.262  5578  5578 D PanProfile: Bluetooth service connected
11-21 15:35:03.262  5595  5611 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-21 15:35:03.264  5595  5595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f89cf
11-21 15:35:03.265  5578  5578 D BluetoothMap: Proxy object connected
11-21 15:35:03.265  5595  5595 D BluetoothMapService: Received start request. Starting profile...
11-21 15:35:03.265  5595  5595 D BluetoothMapService: start()
11-21 15:35:03.266  5578  5578 D MapProfile: Bluetooth service connected
11-21 15:35:03.266  5578  5578 D BluetoothMap: getConnectedDevices()
11-21 15:35:03.267  5578  5578 D BluetoothMap: Bluetooth is Not enabled
11-21 15:35:03.268  5595  5595 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-21 15:35:03.268  5595  5595 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-21 15:35:03.268  5595  5595 D BluetoothMapAppObserver: createReceiver()
11-21 15:35:03.269  5595  5595 D BluetoothMapAppObserver: initObservers()
11-21 15:35:03.270  5595  5595 D BluetoothMapAppObserver: getEnabledAccountItems()
11-21 15:35:03.275  5595  5595 V SapService: SapBinder()
11-21 15:35:03.275  5595  5595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f89cf
11-21 15:35:03.276  5595  5595 D SapService: Received start request. Starting profile...
11-21 15:35:03.276  5595  5595 V SapService: start()
11-21 15:35:03.277  5595  5595 V BluetoothAdapterState: isTurningOff()=false
11-21 15:35:03.277  5595  5607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
11-21 15:35:03.277  5595  5595 V BluetoothAdapterState: isTurningOn()=true
11-21 15:35:03.277  5595  5595 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:03.277  5595  5595 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:03.277  5595  5595 V BluetoothAdapterState: isTurningOff()=false
11-21 15:35:03.277  5595  5595 V BluetoothAdapterState: isTurningOn()=true
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isTurningOff()=false
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isTurningOn()=true
11-21 15:35:03.278  5595  5624 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isTurningOff()=false
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isTurningOn()=true
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isTurningOff()=false
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isTurningOn()=true
11-21 15:35:03.278  5595  5595 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:03.279  5595  5595 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:03.279  5595  5595 V BluetoothAdapterState: isTurningOff()=false
11-21 15:35:03.279  5595  5595 V BluetoothAdapterState: isTurningOn()=true
11-21 15:35:03.279  5595  5595 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:03.279  5595  5595 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:03.279  5595  5595 V BluetoothAdapterState: isTurningOff()=false
11-21 15:35:03.279  5595  5595 V BluetoothAdapterState: isTurningOn()=true
11-21 15:35:03.279  5595  5595 V BluetoothAdapterState: isBleTurningOn()=false
11-21 15:35:03.279  5595  5595 V BluetoothAdapterState: isBleTurningOff()=false
11-21 15:35:03.280  5595  5607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-21 15:35:03.280  5595  5607 D BluetoothAdapterProperties: ScanMode =  20
11-21 15:35:03.280  5595  5607 D BluetoothAdapterProperties: State =  11
11-21 15:35:03.280  5595  5607 D BluetoothAdapterProperties: Setting state to 12
11-21 15:35:03.280  5595  5607 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-21 15:35:03.281  5595  5607 I BluetoothAdapterState: Entering OnState
11-21 15:35:03.282  3034  3896 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 15:35:03.283  5595  5611 D BluetoothAdapterProperties: Scan Mode:21
11-21 15:35:03.283  3034  3045 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 15:35:03.283  5595  5611 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 15:35:03.285  5578  5588 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-21 15:35:03.285  3034  3034 D BluetoothA2dp: Proxy object connected
11-21 15:35:03.285  3034  3895 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-21 15:35:03.287  3034  3045 D BluetoothPan: onBluetoothStateChange on: true
11-21 15:35:03.288  3034  3034 D BluetoothInputDevice: Proxy object connected
11-21 15:35:03.288  3034  3034 D HidProfile: Bluetooth service connected
11-21 15:35:03.288   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 15:35:03.289  3034  3895 D BluetoothMap: onBluetoothStateChange: up=true
11-21 15:35:03.289  3034  3034 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 15:35:03.289  3034  3034 D PanProfile: Bluetooth service connected
11-21 15:35:03.290  3034  3034 D BluetoothMap: Proxy object connected
11-21 15:35:03.290  3034  3034 D MapProfile: Bluetooth service connected
11-21 15:35:03.290  3034  3034 D BluetoothMap: getConnectedDevices()
11-21 15:35:03.290  3686  3706 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 15:35:03.291   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 15:35:03.291   925   925 D BluetoothA2dp: Proxy object connected
11-21 15:35:03.291  5578  5589 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 15:35:03.292  3034  3045 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 15:35:03.294  5595  5595 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-21 15:35:03.294  5578  5588 D BluetoothPan: onBluetoothStateChange on: true
11-21 15:35:03.294   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 15:35:03.294  5595  5595 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-21 15:35:03.294  5578  5589 D BluetoothMap: onBluetoothStateChange: up=true
11-21 15:35:03.295   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 15:35:03.296   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
11-21 15:35:03.297  5595  5595 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 15:35:03.299  5578  5578 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-21 15:35:03.299  5595  5595 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 15:35:03.300  5595  5595 D ObexServerSockets: Succeed to create listening sockets 
11-21 15:35:03.300  5595  5595 D ObexServerSockets0: startAccept()
11-21 15:35:03.300  5595  5595 D ObexServerSockets0: prepareForNewConnect()
,11-21 15:35:03.302  5595  5595 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-21 15:35:03.302  5595  5595 D BluetoothSdpJni: SDP Create record success - handle: 0
11-21 15:35:03.303  5595  5633 D ObexServerSockets0: Accepting socket connection...
11-21 15:35:03.303  5595  5595 D BluetoothMapService: onReceive
11-21 15:35:03.303  5595  5595 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 15:35:03.303  5595  5595 D BluetoothMapService: STATE_ON
,11-21 15:35:03.304  5595  5632 D ObexServerSockets0: Accepting socket connection...
11-21 15:35:03.304  5578  5578 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-21 15:35:03.305  5595  5634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 15:35:03.306  5595  5634 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-21 15:35:03.307  5595  5634 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-21 15:35:03.310  5578  5578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 15:35:03.312  5578  5578 D BluetoothA2dp: Proxy object connected
,11-21 15:35:03.316  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 15:35:03.317  5578  5578 D DockEventReceiver: finishStartingService: stopping service
,11-21 15:35:03.323  5578  5578 D BluetoothPbap: Proxy object connected
,11-21 15:35:03.324  5578  5578 D PbapServerProfile: Bluetooth service connected
,11-21 15:35:03.326  3034  3034 D BluetoothPbap: Proxy object connected
11-21 15:35:03.327  3034  3034 D PbapServerProfile: Bluetooth service connected
11-21 15:35:03.328  5595  5595 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-21 15:35:03.328  5595  5595 D ObexServerSockets0: prepareForNewConnect()
11-21 15:35:03.331  5595  5638 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 15:35:03.345  5595  5642 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 15:35:03.346  5595  5642 I BtOppRfcommListener: Accept thread started.
,11-21 15:35:03.385  3034  3048 D BluetoothHeadset: Proxy object connected
,11-21 15:35:03.385  3034  3034 D HeadsetProfile: Bluetooth service connected
11-21 15:35:03.385  3686  3701 D BluetoothHeadset: Proxy object connected
11-21 15:35:03.385   925   925 D BluetoothHeadset: Proxy object connected
11-21 15:35:03.385   925   925 D BluetoothHeadset: Proxy object connected
11-21 15:35:03.385   925   925 D BluetoothHeadset: Proxy object connected
,11-21 15:35:03.389   925   942 D BluetoothHeadset: Proxy object connected
,11-21 15:35:03.391  3686  3897 D BluetoothHeadset: Proxy object connected
,11-21 15:35:03.395   925   942 D BluetoothHeadset: Proxy object connected
,11-21 15:35:03.395   925   942 D BluetoothHeadset: Proxy object connected
,11-21 15:35:03.407  5578  5589 D BluetoothHeadset: Proxy object connected
,11-21 15:35:03.408  5578  5578 D HeadsetProfile: Bluetooth service connected
,11-21 15:35:03.698   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 15:35:03.788  5499  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 15:35:03.788  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 15:35:03.788  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 15:35:03.788  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 15:35:03.788  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 15:35:03.788  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 15:35:03.788  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 15:35:03.788  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 15:35:03.788  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 15:35:03.793  5499  5576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 15:35:03.796  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-21 15:35:03.799   925  3763 D WifiService: setWifiEnabled: false pid=5499, uid=10077
11-21 15:35:03.799   925  3763 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 15:35:03.807   925  2876 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-21 15:35:03.808   925  2876 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-21 15:35:03.808   925  2876 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-21 15:35:03.808   925  2876 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-21 15:35:03.809  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 15:35:03.825   925  5266 D DhcpClient: Clearing IP address
11-21 15:35:03.826   506   919 D CommandListener: Clearing all IP addresses on wlan0
,11-21 15:35:03.832   506   919 D CommandListener: Setting iface cfg
,11-21 15:35:03.845  3484  5320 V NativeCrypto: Read error: ssl=0x7f9fb09a80: I/O error during system call, Connection timed out
,11-21 15:35:03.850  3484  5320 V NativeCrypto: SSL shutdown failed: ssl=0x7f9fb09a80: I/O error during system call, Broken pipe
,11-21 15:35:03.851   925  2878 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-21 15:35:03.853   532   532 E Parcel  : Reading a NULL string not supported here.
11-21 15:35:03.854   925  2878 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-21 15:35:03.858   925   925 D RttService: SCAN_AVAILABLE : 1
,11-21 15:35:03.859   925  2985 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-21 15:35:03.863   925  2878 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-21 15:35:03.863   925  2876 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-21 15:35:03.865  3657  3790 W QCNEJ   : |CORE| network lost: 100
11-21 15:35:03.866  3657  3790 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-21 15:35:03.867   925  5267 D DhcpClient: Receive thread stopped
,11-21 15:35:03.870   925  2876 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 15:35:03.891   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 15:35:03.911   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 15:35:03.912   506   919 D CommandListener: Clearing all IP addresses on wlan0
11-21 15:35:03.912   925  2878 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-21 15:35:03.912   506   919 D TetherController: Setting IP forward enable = 0
11-21 15:35:03.913   925  2878 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-21 15:35:03.914   925   942 D Tethering: MasterInitialState.processMessage what=3
,11-21 15:35:03.916   925  2876 D DhcpClient: doQuit
11-21 15:35:03.916   925  2876 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-21 15:35:03.917   925  5266 D DhcpClient: onQuitting
11-21 15:35:03.917  3356  3356 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-21 15:35:03.923  5147  5147 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e515cf0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-21 15:35:03.922  3872  3872 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-21 15:35:03.926  4937  4959 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 15:35:03.926  4937  4959 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 15:35:03.926  4937  4959 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-21 15:35:03.926  4937  4959 E SarControlService: no key has been found,reset the power
11-21 15:35:03.926  4937  4974 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 15:35:03.926  4937  4974 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 15:35:03.926  4937  4974 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 15:35:03.927  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 15:35:03.927  4962  4962 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-21 15:35:03.929  4937  4974 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-21 15:35:03.929  4937  4974 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 15:35:03.929  4937  4974 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 15:35:03.931  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 15:35:03.931  4962  4962 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-21 15:35:03.932  3770  3770 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-21 15:35:03.933  3356  3356 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-21 15:35:03.937  3356  3356 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-21 15:35:03.938  4962  4976 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4f8656 HexData = [00000000ea03000000000000ffffffff]
11-21 15:35:03.938  4962  4976 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 15:35:03.938  4962  4976 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-21 15:35:03.941  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 15:35:03.941  4937  4947 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 15:35:03.942  3770  3770 D SystemUpdateService: onCreate
11-21 15:35:03.948  3770  3770 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-21 15:35:03.949  4962  4976 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4f8656 HexData = [00000000eb03000000000000ffffffff]
11-21 15:35:03.949  4962  4976 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 15:35:03.949  4962  4976 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-21 15:35:03.949  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 15:35:03.950  4937  4948 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 15:35:03.956  3770  5659 I SystemUpdateService: active receiver: enabled
,11-21 15:35:03.957   506   912 W SocketClient: write error (Broken pipe)
11-21 15:35:03.957   506   912 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-21 15:35:03.957   506   912 W SocketListener: Error sending broadcast (Broken pipe)
11-21 15:35:03.958  3770  3770 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-21 15:35:03.963  3770  5291 I iu.UploadsManager: num queued entries: 0
,11-21 15:35:03.963  3770  5291 I iu.UploadsManager: num updated entries: 0
,11-21 15:35:03.966  3770  3770 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-21 15:35:03.968  3770  3770 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-21 15:35:03.969  3770  5659 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 15:35:03.971  3770  5291 I iu.SyncManager: NEXT; no task
,11-21 15:35:03.972  3770  5659 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-21 15:35:03.972  3770  5659 I SystemUpdateService: now status is 0 (complete)
11-21 15:35:03.972  3770  5659 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 15:35:03.972  3770  5659 I SystemUpdateService: file has been verified
11-21 15:35:03.973  3770  5659 I SystemUpdateService: OTA package size = 21989297
,11-21 15:35:03.978  3770  5659 I SystemUpdateService: showing system update notification
,11-21 15:35:03.981   925   936 I ActivityManager: Start proc 5661:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-21 15:35:03.985  3356  3356 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-21 15:35:03.991   925   925 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 15:35:03.992  3770  3770 D SystemUpdateService: onDestroy
,11-21 15:35:04.001  3356  3356 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-21 15:35:04.003   506   912 W SocketClient: write error (Broken pipe)
11-21 15:35:04.003   506   912 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-21 15:35:04.003   506   912 W SocketListener: Error sending broadcast (Broken pipe)
,11-21 15:35:04.009   925  2876 D wifi    : In wifi stop Hal
,11-21 15:35:04.009   925  2876 D wifi    : halHandle = 0x7f8d3a8080, mVM = 0x7fa998d140, mCls = 0x100a02
11-21 15:35:04.009   925  3355 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-21 15:35:04.009  4888  4888 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-21 15:35:04.009   925  3355 D WifiHAL : Got a signal to exit!!!
11-21 15:35:04.009   925  3355 I WifiHAL : Exit wifi_event_loop
11-21 15:35:04.010   925  2876 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-21 15:35:04.010   925  2876 E WifiHAL : Event processing terminated
11-21 15:35:04.010   925  2876 D wifi    : In wifi cleaned up handler
11-21 15:35:04.010   925  2876 I WifiHAL : Internal cleanup completed
11-21 15:35:04.011  3982  4132 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 15:35:04.024  5661  5661 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-21 15:35:04.027  5661  5661 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 15:35:04.029   506   912 W SocketClient: write error (Broken pipe)
,11-21 15:35:04.029   506   912 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 down'
11-21 15:35:04.029   506   912 W SocketListener: Error sending broadcast (Broken pipe)
11-21 15:35:04.030   925  3355 D wifi    : set interface wlan0 flags (DOWN)
11-21 15:35:04.030   925  2876 D WifiNative-HAL: HAL event thread stopped successfully
,11-21 15:35:04.034  5661  5661 D SprintDMHelper: simOperator: 
,11-21 15:35:04.034  5661  5661 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 15:35:04.051  4888  5673 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-21 15:35:04.064   925  3033 I ActivityManager: Start proc 5674:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-21 15:35:04.066   925  3033 I ActivityManager: Killing 5147:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-21 15:35:04.101  5674  5674 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-21 15:35:04.109   925  3033 I ActivityManager: Killing 3814:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-21 15:35:04.239   925   942 D Tethering: InitialState.processMessage what=4
11-21 15:35:04.249   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-21 15:35:04.315  5499  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 15:35:04.315  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 15:35:04.315  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 15:35:04.315  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-21 15:35:04.315  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 15:35:04.315  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 15:35:04.315  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 15:35:04.315  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 15:35:04.315  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 15:35:04.323  5499  5576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 15:35:04.328  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 15:35:04.329   925  3032 D WifiService: setWifiEnabled: true pid=5499, uid=10077
11-21 15:35:04.329   925  3032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 15:35:04.699   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 15:35:04.834   925  3032 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-21 15:35:04.834   925  3032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 15:35:05.011   506   919 E Netd    : netlink response contains error (No such file or directory)
,11-21 15:35:05.013   925  2878 E NetdConnector: NDC Command {113 network destroy 100} took too long (1100ms)
11-21 15:35:05.014   925  2878 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-21 15:35:05.015   925  2874 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1095ms)
,11-21 15:35:05.016   925  2873 E NetdConnector: NDC Command {115 bandwidth gettetherstats} took too long (765ms)
11-21 15:35:05.017   506   919 D SoftapController: Softap fwReload - Ok
,11-21 15:35:05.018   506   919 D TetherController: Setting IP forward enable = 0
,11-21 15:35:05.018   925  2876 E NetdConnector: NDC Command {116 softap fwreload wlan0 STA} took too long (686ms)
,11-21 15:35:05.025   506   919 D CommandListener: Setting iface cfg
,11-21 15:35:05.026   506   919 D CommandListener: Trying to bring down wlan0
,11-21 15:35:05.027   506   919 D CommandListener: Clearing all IP addresses on wlan0
,11-21 15:35:05.030   925  2876 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-21 15:35:05.338   925  3767 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-21 15:35:05.343   925  3767 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 15:35:05.634   925  2876 D wifi    : set interface wlan0 flags (UP)
,11-21 15:35:05.636   925  2876 I WifiHAL : Initializing wifi
11-21 15:35:05.636   925  2876 I WifiHAL : Creating socket
11-21 15:35:05.642   925  2876 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-21 15:35:05.643   925  2876 D wifi    : Did set static halHandle = 0x7f8d3a8080
11-21 15:35:05.643   925  2876 D wifi    : halHandle = 0x7f8d3a8080, mVM = 0x7fa998d140, mCls = 0x19ba
,11-21 15:35:05.643   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-21 15:35:05.643   925  2876 D wifi    : array field set
,11-21 15:35:05.645   925  2876 I WifiNative-HAL: interface[0] = wlan0
,11-21 15:35:05.648   925  5694 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547830268032
,11-21 15:35:05.648   925  5694 D wifi    : waitForHalEvents called, vm = 0x7fa998d140, obj = 0x19ba, env = 0x7f8e2686c0
,11-21 15:35:05.700   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 15:35:05.736  5695  5695 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-21 15:35:05.751   925  2876 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-21 15:35:05.816  5695  5695 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 15:35:05.846  5695  5695 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-21 15:35:05.846  5695  5695 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
11-21 15:35:05.846   925  3312 D WifiService: setWifiEnabled: true pid=5499, uid=10077
11-21 15:35:05.846   925  3312 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 15:35:05.860   925  2876 D WifiConfigStore: Loading config and enabling all networks 
,11-21 15:35:05.879   925  2876 D WifiConfigStore: loaded 0 passpoint configs
,11-21 15:35:05.880   925  2876 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-21 15:35:05.880   925  2876 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-21 15:35:05.880   925  2876 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-21 15:35:05.881   925  2876 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-21 15:35:05.881   925  2876 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-21 15:35:05.882   925  2876 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-21 15:35:05.882   925  2876 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-21 15:35:05.882   925  2876 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-21 15:35:05.882   925  2876 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-21 15:35:05.882   925  2876 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-21 15:35:05.882   925  2876 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-21 15:35:05.882   925  2876 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-21 15:35:05.884   925  2876 D WifiNative-HAL: Setting external_sim to 1
,11-21 15:35:05.884   925  2876 D wifi    : setting dfs flag to true, 0x7f8fbbd3a0
11-21 15:35:05.885   925  2876 D WifiStateMachine: Setting OUI to DA-A1-19
11-21 15:35:05.885   925  2876 D wifi    : setting scan oui 0x7f8fbbd3a0
11-21 15:35:05.885   925  2876 D WifiHAL : Sending mac address OUI
,11-21 15:35:05.885  4888  4888 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 15:35:05.888   925  2876 E native  : do suspend false
,11-21 15:35:05.895   925  2876 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-21 15:35:05.895   925   925 D RttService: SCAN_AVAILABLE : 3
11-21 15:35:05.895   925  2985 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-21 15:35:05.899   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-21 15:35:05.900   506   919 D CommandListener: Setting iface cfg
,11-21 15:35:05.901   925  2875 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
11-21 15:35:05.901   925  2875 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-21 15:35:05.908   925  2875 D WifiNative-HAL: p2pGetDeviceAddress
,11-21 15:35:05.909   925  2875 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-21 15:35:05.913   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=191483 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-21 15:35:06.357  5499  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 15:35:06.357  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 15:35:06.357  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 15:35:06.357  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 15:35:06.357  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 15:35:06.357  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 15:35:06.357  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 15:35:06.357  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 15:35:06.357  5499  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 15:35:06.363  5499  5576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 15:35:06.367  5499  5546 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 15:35:06.368   925  3769 D WifiService: setWifiEnabled: true pid=5499, uid=10077
11-21 15:35:06.368   925  3769 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 15:35:06.369  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-21 15:35:06.369  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 15:35:06.369  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 15:35:06.369  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72279d6 removed from the list
11-21 15:35:06.369  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 15:35:06.370  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c514457 removed from the list
11-21 15:35:06.370  5499  5546 D io.jxcore.node.ConnectivityMonitor: stop
11-21 15:35:06.372  5499  5546 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-21 15:35:06.375  5499  5546 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-21 15:35:06.376  5499  5546 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-21 15:35:06.378  5499  5546 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
11-21 15:35:06.380  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-21 15:35:06.381  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-21 15:35:06.382  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-21 15:35:06.383  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-21 15:35:06.384  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-21 15:35:06.388  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-21 15:35:06.388  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d4f3eb Bundle[{}]
11-21 15:35:06.389  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-21 15:35:06.389  5499  5546 I io.jxcore.node.LifeCycleMonitor: start: OK
11-21 15:35:06.389  5499  5546 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-21 15:35:06.390  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-21 15:35:06.390  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-21 15:35:06.391  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,11-21 15:35:06.391  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-21 15:35:06.392  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-21 15:35:06.392  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-21 15:35:06.393  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-21 15:35:06.393  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-21 15:35:06.396  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-21 15:35:06.398  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-21 15:35:06.399  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-21 15:35:06.401  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-21 15:35:06.401  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-21 15:35:06.402  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-21 15:35:06.404  5499  5546 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-21 15:35:06.405  5499  5546 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-21 15:35:06.406  5499  5546 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
11-21 15:35:06.408  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-21 15:35:06.409  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-21 15:35:06.410  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-21 15:35:06.410  5499  5546 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-21 15:35:06.411  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-21 15:35:06.411  5499  5546 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-21 15:35:06.411  5499  5546 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 143)
,11-21 15:35:06.412  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-21 15:35:06.412  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-21 15:35:06.413  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-21 15:35:06.413  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 15:35:06.413  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15b742d added. We now have 3 listener(s)
,11-21 15:35:06.416  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:35:06.416  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 15:35:06.416  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 15:35:06.416  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 15:35:06.416  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9245d62 added. We now have 3 listener(s)
11-21 15:35:06.416  5499  5546 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 15:35:06.417  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 15:35:06.422  5499  5546 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-21 15:35:06.423  5499  5546 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-21 15:35:06.423  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-21 15:35:06.423  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-21 15:35:06.423  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.423  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.423  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.423  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 15:35:06.423  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-21 15:35:06.424  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 15:35:06.424  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 15:35:06.424  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 15:35:06.431  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 15:35:06.432  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 15:35:06.432  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-21 15:35:06.433  5499  5698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 15:35:06.433  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 15:35:06.433  5499  5698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 15:35:06.434  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 15:35:06.434  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 15:35:06.434  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 15:35:06.434  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 15:35:06.434  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 15:35:06.433  5623  5623 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[28593]" dev="sockfs" ino=28593 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 15:35:06.437  5499  5698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 15:35:06.433  5623  5623 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[28593]" dev="sockfs" ino=28593 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 15:35:06.439  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-21 15:35:06.439  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 15:35:06.439  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 15:35:06.444  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:06.444  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 15:35:06.445  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 15:35:06.445  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-21 15:35:06.445  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-21 15:35:06.448  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:06.448  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.448  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 15:35:06.448  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 15:35:06.448  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:35:06.449  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
,11-21 15:35:06.449  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 15:35:06.449  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:35:06.449  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.449  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 15:35:06.449  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:35:06.449  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.449  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:06.449  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.450  5499  5546 D BluetoothAdapter: STATE_ON
,11-21 15:35:06.454  5595  5623 D BtGatt.GattService: registerClient() - UUID=30e89da6-9919-43dd-bbca-07869c4333b9
11-21 15:35:06.455  5595  5611 D BtGatt.GattService: onClientRegistered() - UUID=30e89da6-9919-43dd-bbca-07869c4333b9, clientIf=5
,11-21 15:35:06.455  5499  5509 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 15:35:06.457  5595  5613 D BtGatt.AdvertiseManager: message : 0
,11-21 15:35:06.460  5595  5613 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 15:35:06.471  5595  5611 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 15:35:06.477  5595  5611 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 15:35:06.478  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:06.478  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.478  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 15:35:06.479  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.479  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.479  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:06.479  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.479  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:06.479  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 15:35:06.481  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-21 15:35:06.481  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.483  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.483  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.483  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:06.483  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 15:35:06.483  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 15:35:06.483  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 15:35:06.483  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-21 15:35:06.483  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 15:35:06.484  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:06.484  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 15:35:06.484  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:35:06.484  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 15:35:06.484  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 15:35:06.484  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:35:06.484  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-21 15:35:06.484  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 15:35:06.484  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 15:35:06.487  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:35:06.487  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 15:35:06.487  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:06.487  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:06.487  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:35:06.487  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 15:35:06.701   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 15:35:06.988  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 15:35:06.989  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-21 15:35:06.989  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 15:35:07.702   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 15:35:08.702   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 15:35:09.024  5695  5695 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 15:35:09.036  5695  5695 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 15:35:09.043  5695  5695 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 15:35:09.048  5695  5695 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 15:35:09.069   925  2876 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-21 15:35:09.070   925  2876 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-21 15:35:09.070   925  2876 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 15:35:09.081   925  2876 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-21 15:35:09.113   925  2876 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-21 15:35:09.118  5695  5695 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-21 15:35:09.550  5695  5695 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-21 15:35:09.590  5695  5695 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-21 15:35:09.591  5695  5695 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-21 15:35:09.602   925  2876 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-21 15:35:09.602   925  2876 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 15:35:09.603   925  2878 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-21 15:35:09.620   925  2876 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 15:35:09.633   506   919 D CommandListener: Setting iface cfg
,11-21 15:35:09.638   925  2876 D WifiStateMachine: Start Dhcp Watchdog 2
,11-21 15:35:09.644   925  5703 D DhcpClient: Receive thread started
,11-21 15:35:09.650   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 15:35:09.650   925  2876 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-21 15:35:09.650   925  2878 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-21 15:35:09.731   925  2876 E native  : do suspend false
,11-21 15:35:09.741   925  5702 D DhcpClient: Broadcasting DHCPDISCOVER
,11-21 15:35:09.759   925  5703 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172646, domain null
,11-21 15:35:09.760   925  5702 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172646 seconds
,11-21 15:35:09.762   925  5702 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-21 15:35:09.786   925  5703 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-21 15:35:09.787   925  5702 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-21 15:35:09.790   506   919 D CommandListener: Setting iface cfg
11-21 15:35:09.795   925  2876 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-21 15:35:09.800   925  5702 D DhcpClient: Scheduling renewal in 86399s
,11-21 15:35:09.808   925  2876 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-21 15:35:09.810   925  2876 D WifiConfigStore: No blacklist allowed without epno enabled
11-21 15:35:09.811   925  2878 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-21 15:35:09.813   925  2878 D ConnectivityService: Adding iface wlan0 to network 101
,11-21 15:35:09.822   925  2876 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-21 15:35:09.865   925  2878 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-21 15:35:09.865   925  2878 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-21 15:35:09.866   925  2878 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-21 15:35:09.868   925  2878 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-21 15:35:09.869   925  2878 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-21 15:35:09.875   925  2878 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 15:35:09.880   925  2878 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-21 15:35:09.881   925  2878 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-21 15:35:09.881   925  2878 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-21 15:35:09.881   925  2878 D ConnectivityService:    accepting network in place of null
11-21 15:35:09.881   925  2878 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-21 15:35:09.882   925  2876 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-21 15:35:09.882   925  2876 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 15:35:09.905   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 15:35:09.907   925  5701 D NetlinkSocketObserver: NeighborEvent{elapsedMs=195476, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 15:35:09.925   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 15:35:09.928   925  2878 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-21 15:35:09.928   925  2878 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-21 15:35:09.928  3657  3790 W QCNEJ   : |CORE| network available: 101
11-21 15:35:09.929   925  2878 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-21 15:35:09.930   925   942 D Tethering: MasterInitialState.processMessage what=3
,11-21 15:35:09.935  3657  3790 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-21 15:35:09.936  3657  3790 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-21 15:35:09.936  3657  3790 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-21 15:35:09.943  4937  4959 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 15:35:09.943  4937  4959 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 15:35:09.943  4937  4959 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-21 15:35:09.943  4937  4959 E SarControlService: no key has been found,reset the power
11-21 15:35:09.943  4937  4974 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-21 15:35:09.943  4937  4974 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 15:35:09.943  4937  4974 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 15:35:09.944  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 15:35:09.944  4962  4962 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-21 15:35:09.946  4937  4974 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-21 15:35:09.946  4937  4974 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 15:35:09.946  4937  4974 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 15:35:09.946  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 15:35:09.947  4962  4962 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-21 15:35:09.948  3872  3872 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-21 15:35:09.950  3770  3770 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-21 15:35:09.952  4962  4976 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4f8656 HexData = [00000000ec03000000000000ffffffff]
,11-21 15:35:09.952  4962  4976 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 15:35:09.952  4962  4976 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-21 15:35:09.954  4962  4976 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4f8656 HexData = [00000000ed03000000000000ffffffff]
11-21 15:35:09.954  4962  4976 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 15:35:09.954  4962  4976 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-21 15:35:09.955  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 15:35:09.955  4937  4947 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 15:35:09.956  3770  3770 D SystemUpdateService: onCreate
11-21 15:35:09.957  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-21 15:35:09.957  4937  4948 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 15:35:09.961  3770  3770 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-21 15:35:09.972  3770  3770 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-21 15:35:09.977  3770  5291 I iu.UploadsManager: num queued entries: 0
,11-21 15:35:09.978  3770  5291 I iu.UploadsManager: num updated entries: 0
11-21 15:35:09.978  3770  5291 I iu.SyncManager: NEXT; no task
,11-21 15:35:09.980  3770  5713 I SystemUpdateService: active receiver: enabled
,11-21 15:35:09.985  3770  3770 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-21 15:35:09.985  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 15:35:09.985  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 15:35:09.985  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 15:35:09.985  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 15:35:09.985  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 15:35:09.986  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 15:35:09.986  5499  5698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 15:35:09.986  5499  5698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 15:35:09.986  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 15:35:09.986  5499  5698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 15:35:09.986  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 15:35:09.986  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 15:35:09.986  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 15:35:09.986  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 15:35:09.986  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 15:35:09.986  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 15:35:09.986  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 15:35:09.986  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 15:35:09.986  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:09.986  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:09.986  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:09.986  3770  3770 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-21 15:35:09.986  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:09.988  5499  5546 D BluetoothAdapter: STATE_ON
,11-21 15:35:09.988  5661  5661 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-21 15:35:09.988  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 15:35:09.989  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:35:09.989  5499  5546 D BluetoothLeScanner: could not find callback wrapper
11-21 15:35:09.989  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 15:35:09.989  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:09.989  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:09.989  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:09.989  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-21 15:35:09.989  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:09.990  5595  5613 D BtGatt.AdvertiseManager: message : 1
11-21 15:35:09.991  5595  5613 D BtGatt.AdvertiseManager: stop advertise for client 5
11-21 15:35:09.993  5661  5661 D SprintDMHelper: simOperator: 
,11-21 15:35:09.994  5661  5661 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 15:35:09.998  5595  5611 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 15:35:09.998  5595  5611 D BtGatt.GattService: Client app is not null!
11-21 15:35:09.999  5595  5623 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 15:35:09.999  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 15:35:09.999  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:09.999  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 15:35:10.000  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:10.000  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.000  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.000  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 15:35:10.000  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-21 15:35:10.001  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-21 15:35:10.002  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.003   925  5700 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-21 15:35:10.003  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.003  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 15:35:10.003  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.003  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.003  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 15:35:10.004  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 15:35:10.004  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:35:10.004  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:35:10.004  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 15:35:10.004  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.004  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 15:35:10.004  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 15:35:10.004  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.004  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.005  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-21 15:35:10.005  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.006  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.006  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.006  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.006  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.006  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 15:35:10.007  5499  5546 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-21 15:35:10.007  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 15:35:10.008  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-21 15:35:10.008  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-21 15:35:10.008  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-21 15:35:10.008  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 15:35:10.008  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 15:35:10.011  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-21 15:35:10.014  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 15:35:10.014  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 15:35:10.014  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 15:35:10.017  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.017  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 15:35:10.018  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 15:35:10.018  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 15:35:10.018  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-21 15:35:10.020  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-21 15:35:10.021  3770  5713 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-21 15:35:10.023  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-21 15:35:10.024  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.024  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 15:35:10.024  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 15:35:10.024  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-21 15:35:10.024  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 15:35:10.025  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:10.025  5499  5546 D BluetoothAdapter: STATE_ON
,11-21 15:35:10.028  5595  5631 D BtGatt.GattService: registerClient() - UUID=e0ec006c-9ce0-472c-96e9-c2ab0a5a7d2e
,11-21 15:35:10.028  5595  5611 D BtGatt.GattService: onClientRegistered() - UUID=e0ec006c-9ce0-472c-96e9-c2ab0a5a7d2e, clientIf=5
11-21 15:35:10.029  5499  5543 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-21 15:35:10.030  5595  5606 D BtGatt.GattService: start scan with filters
,11-21 15:35:10.035  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-21 15:35:10.036  5595  5614 D BtGatt.ScanManager: handling starting scan
11-21 15:35:10.036  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.036  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 15:35:10.036  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.036  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 15:35:10.036  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 15:35:10.037  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.037  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 15:35:10.037  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 15:35:10.037  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.037  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.037  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-21 15:35:10.037  5595  5614 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f89cf
11-21 15:35:10.038  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 15:35:10.038  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:10.041  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:10.041  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 15:35:10.041  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:10.041  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:10.042  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 15:35:10.042  3770  5713 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-21 15:35:10.042  3770  5713 I SystemUpdateService: now status is 0 (complete)
11-21 15:35:10.042  3770  5713 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 15:35:10.042  3770  5713 I SystemUpdateService: file has been verified
11-21 15:35:10.042  3770  5713 I SystemUpdateService: OTA package size = 21989297
11-21 15:35:10.042  5595  5611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 15:35:10.042  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:10.043  5595  5614 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-21 15:35:10.044  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.044  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.044  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.044  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:35:10.044  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 15:35:10.048  5595  5611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-21 15:35:10.048  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 15:35:10.049  3770  5713 I SystemUpdateService: showing system update notification
,11-21 15:35:10.049  5595  5614 D BtGatt.ScanManager: Starting BLE batch scan
11-21 15:35:10.049  5595  5614 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 15:35:10.057   925   925 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 15:35:10.057  5595  5611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-21 15:35:10.057  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 15:35:10.062  5595  5611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-21 15:35:10.062  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:10.062  3770  3770 D SystemUpdateService: onDestroy
,11-21 15:35:10.066   925  5700 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Nov 2016 14:35:10 GMT], X-Android-Received-Millis=[1479738910066], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479738910030]}
11-21 15:35:10.067   925  2878 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-21 15:35:10.067   925  2878 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-21 15:35:10.067   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-21 15:35:10.068   925  2878 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-21 15:35:10.193  4888  5719 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-21 15:35:10.545  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-21 15:35:10.545  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 15:35:10.545  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 15:35:10.565  5595  5595 D BtGatt.ScanManager: awakened up at time 196134
,11-21 15:35:10.567  5595  5614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 15:35:10.594  5595  5611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-21 15:35:10.594  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:10.595  5595  5611 D BtGatt.GattService: current time is 196164677502
11-21 15:35:10.595  5595  5611 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-21 15:35:10.599  5595  5611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-21 15:35:10.605  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
,11-21 15:35:10.606  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=196065526877}
,11-21 15:35:10.606  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=196065526877}
,11-21 15:35:10.607  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
,11-21 15:35:10.608  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-21 15:35:10.929   925  2878 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-21 15:35:13.044  5499  5546 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-21 15:35:13.044  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-21 15:35:13.045  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-21 15:35:13.045  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.045  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.045  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.046  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 15:35:13.046  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 15:35:13.046  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 15:35:13.046  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-21 15:35:13.046  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 15:35:13.046  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 15:35:13.046  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 15:35:13.046  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 15:35:13.046  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 15:35:13.046  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.046  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-21 15:35:13.046  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.047  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.047  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 15:35:13.047  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 15:35:13.048  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.048  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:13.048  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.052  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:35:13.052  5595  5623 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-21 15:35:13.053  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 15:35:13.054  5595  5614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-21 15:35:13.054  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:35:13.056  5595  5631 D BtGatt.GattService: stopScan() - queue size =1
11-21 15:35:13.058  5595  5606 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 15:35:13.058  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 15:35:13.059  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.059  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 15:35:13.059  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.059  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 15:35:13.059  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.060  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.060  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 15:35:13.060  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 15:35:13.060  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 15:35:13.060  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 15:35:13.061  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:13.062  5595  5595 D BtGatt.ScanManager: awakened up at time 198631
11-21 15:35:13.062  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:35:13.065  5595  5631 D BtGatt.GattService: registerClient() - UUID=a341d156-fa4d-434e-9062-3713a01853fd
11-21 15:35:13.066  5595  5611 D BtGatt.GattService: onClientRegistered() - UUID=a341d156-fa4d-434e-9062-3713a01853fd, clientIf=5
11-21 15:35:13.067  5499  5510 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-21 15:35:13.067  5595  5623 D BtGatt.GattService: start scan with filters
11-21 15:35:13.072  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-21 15:35:13.072  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:13.072  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 15:35:13.073  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.073  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.073  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 15:35:13.073  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-21 15:35:13.073  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.073  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 15:35:13.073  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 15:35:13.073  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-21 15:35:13.073  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 15:35:13.073  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 15:35:13.073  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.073  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 15:35:13.074  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 15:35:13.074  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 15:35:13.075  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 15:35:13.075  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 15:35:13.075  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 15:35:13.075  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,11-21 15:35:13.075  5499  5726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 15:35:13.076  5499  5726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 15:35:13.076  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 15:35:13.077  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 15:35:13.077  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 15:35:13.079  5499  5726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 15:35:13.076  5631  5631 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[21349]" dev="sockfs" ino=21349 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 15:35:13.076  5631  5631 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[21349]" dev="sockfs" ino=21349 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 15:35:13.081  5595  5611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-21 15:35:13.081  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:13.081  5595  5611 D BtGatt.GattService: current time is 198651323405
11-21 15:35:13.082  5595  5611 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -88, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -91, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -80, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-21 15:35:13.082  5595  5611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-21 15:35:13.082  5595  5611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-21 15:35:13.082  5595  5611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 15:35:13.082  5595  5611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-21 15:35:13.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.086  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-21 15:35:13.086  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 15:35:13.087  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 15:35:13.087  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-21 15:35:13.087  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:35:13.087  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 15:35:13.087  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.087  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 15:35:13.087  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 15:35:13.087  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.087  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.087  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.088  5499  5546 D BluetoothAdapter: STATE_ON
11-21 15:35:13.089  5595  5611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-21 15:35:13.089  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:13.089  5595  5614 D BtGatt.ScanManager: stopping BLe Batch
11-21 15:35:13.094  5595  5631 D BtGatt.GattService: registerClient() - UUID=871ab535-cf3c-4f67-8eb8-e258fdd04d0b
,11-21 15:35:13.095  5595  5611 D BtGatt.GattService: onClientRegistered() - UUID=871ab535-cf3c-4f67-8eb8-e258fdd04d0b, clientIf=6
11-21 15:35:13.095  5595  5611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-21 15:35:13.095  5499  5509 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-21 15:35:13.095  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 15:35:13.095  5595  5614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-21 15:35:13.096  5595  5613 D BtGatt.AdvertiseManager: message : 0
,11-21 15:35:13.101  5595  5611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 15:35:13.101  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:13.102  5595  5613 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 15:35:13.103  5595  5614 D BtGatt.ScanManager: handling starting scan
,11-21 15:35:13.110  5595  5611 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-21 15:35:13.114  5595  5611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 15:35:13.114  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 15:35:13.115  5595  5614 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-21 15:35:13.118  5595  5611 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-21 15:35:13.119  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.119  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-21 15:35:13.119  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-21 15:35:13.119  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 15:35:13.121  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-21 15:35:13.121  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.122  5595  5611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-21 15:35:13.122  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:13.122  5595  5614 D BtGatt.ScanManager: Starting BLE batch scan
11-21 15:35:13.122  5595  5614 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-21 15:35:13.123  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.124  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.124  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:13.124  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 15:35:13.124  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 4. Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.124  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=196551606215}
11-21 15:35:13.124  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=196551606215}
11-21 15:35:13.125  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
11-21 15:35:13.125  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-21 15:35:13.125  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=197001606215}
11-21 15:35:13.125  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestam,pNanos=197001606215}
11-21 15:35:13.125  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
11-21 15:35:13.125  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-21 15:35:13.125  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-91, mTimestampNanos=196901606215}
11-21 15:35:13.125  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-91, mTimestampNanos=196901606215}
11-21 15:35:13.125  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
11-21 15:35:13.125  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-88, mTimestampNanos=196651606215}
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-88, mTimestampNanos=196651606215}
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D1:0E:8F:74:D2:B6, provideBluetoothMacAddressRequestId = nullextra info = 37]
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 15:35:13.126  5499  5499 D org.thali,project.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.126  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.126  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.127  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-21 15:35:13.127  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.129  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.129  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 15:35:13.129  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.129  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.129  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:35:13.129  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 15:35:13.130  5595  5611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-21 15:35:13.130  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:13.135  5595  5611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-21 15:35:13.135  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 15:35:13.630  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-21 15:35:13.631  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 15:35:13.631  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 15:35:15.692   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 15:35:15.765   925  2876 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,11-21 15:35:16.127  5499  5546 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-21 15:35:16.127  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 15:35:16.128  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 15:35:16.128  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-21 15:35:16.128  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 15:35:16.128  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 15:35:16.128  5499  5726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-21 15:35:16.129  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 15:35:16.129  5499  5726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 15:35:16.129  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 15:35:16.129  5499  5726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-21 15:35:16.129  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 15:35:16.129  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 15:35:16.129  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15b742d removed from the list
11-21 15:35:16.129  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-21 15:35:16.129  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 15:35:16.130  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 15:35:16.130  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 15:35:16.130  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-21 15:35:16.130  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 15:35:16.130  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.131  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.131  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.131  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-21 15:35:16.131  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.134  5499  5546 D BluetoothAdapter: STATE_ON
,11-21 15:35:16.135  5595  5623 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-21 15:35:16.136  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 15:35:16.137  5595  5614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-21 15:35:16.137  5499  5546 D BluetoothAdapter: STATE_ON
,11-21 15:35:16.139  5595  5605 D BtGatt.GattService: stopScan() - queue size =1
11-21 15:35:16.141  5595  5631 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 15:35:16.142  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 15:35:16.142  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.142  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 15:35:16.142  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:16.142  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.143  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.143  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 15:35:16.143  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.144  5595  5613 D BtGatt.AdvertiseManager: message : 1
11-21 15:35:16.145  5595  5613 D BtGatt.AdvertiseManager: stop advertise for client 6
11-21 15:35:16.146  5595  5595 D BtGatt.ScanManager: awakened up at time 201716
11-21 15:35:16.154  5595  5611 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-21 15:35:16.154  5595  5611 D BtGatt.GattService: Client app is not null!
11-21 15:35:16.155  5595  5605 D BtGatt.GattService: unregisterClient() - clientIf=6
11-21 15:35:16.156  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 15:35:16.156  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:16.156  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 15:35:16.156  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:16.156  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.156  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:16.156  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-21 15:35:16.156  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 15:35:16.157  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 15:35:16.158  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.159  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.159  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 15:35:16.159  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 15:35:16.159  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 15:35:16.159  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9245d62 removed from the list
11-21 15:35:16.159  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:35:16.159  5499  5546 D io.jxcore.node.ConnectivityMonitor: stop
11-21 15:35:16.159  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 15:35:16.160  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 15:35:16.160  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.160  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 15:35:16.160  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-21 15:35:16.160  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.160  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.160  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-21 15:35:16.161  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.161  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-21 15:35:16.161  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 15:35:16.162  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 15:35:16.162  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 15:35:16.162  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 15:35:16.162  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-21 15:35:16.162  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-21 15:35:16.163  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.163  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-21 15:35:16.163  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.163  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.163  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.163  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 15:35:16.163  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.164  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-21 15:35:16.164  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 15:35:16.164  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-21 15:35:16.165  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.165  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 15:35:16.165  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 15:35:16.165  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-21 15:35:16.166  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-21 15:35:16.167  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-21 15:35:16.167  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-21 15:35:16.168  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-21 15:35:16.168  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-21 15:35:16.175  5595  5611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-21 15:35:16.175  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:16.175  5595  5611 D BtGatt.GattService: current time is 201744687954
11-21 15:35:16.175  5595  5611 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -87, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -93, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -79, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -80, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -79, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-21 15:35:16.175  5595  5611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-21 15:35:16.176  5595  5611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 15:35:16.176  5595  5611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-21 15:35:16.176  5595  5611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-21 15:35:16.176  5595  5611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-21 15:35:16.181  5595  5611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-21 15:35:16.181  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:16.181  5595  5614 D BtGatt.ScanManager: stopping BLe Batch
,11-21 15:35:16.185  5595  5611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-21 15:35:16.186  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 15:35:16.186  5595  5614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 15:35:16.190  5595  5611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-21 15:35:16.190  5595  5611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 15:35:16.666  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 15:35:17.883   925  2878 D ConnectivityService: handlePromptUnvalidated 101
,11-21 15:35:18.173  5499  5546 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-21 15:35:18.295  5499  5728 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 15:35:18.295  5499  5728 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 15:35:18.705   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 15:35:19.091  5499  5728 W !!      : call onHalfStreamCopied
,11-21 15:35:19.091  5499  5728 I testCopyDataAndClose: closing input stream
,11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 15:35:19.857  5499  5728 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 15:35:20.916   925  2876 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,11-21 15:35:21.732   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 15:35:24.193  5499  5546 I StreamCopyingThreadTest: Starting test: testRun
,11-21 15:35:24.199  5499  5729 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-21 15:35:24.199  5499  5729 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 15:35:24.772   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 15:35:28.955   925  5701 D NetlinkSocketObserver: NeighborEvent{elapsedMs=214524, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 15:35:29.207  5499  5730 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-21 15:35:29.209  5499  5546 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-21 15:35:29.322  5499  5731 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 15:35:29.322  5499  5731 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 15:35:30.815   925  2878 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 15:35:31.014  5499  5731 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 15:35:32.667  3584  3759 I Keyboard.Facilitator.LanguageModelFlusher: run()
11-21 15:35:32.667  3584  3759 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-21 15:35:32.697  3484  3484 I ConfigService: onCreate
,11-21 15:35:33.703   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 15:35:33.704   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 15:35:35.258  5499  5546 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-21 15:35:35.260  5499  5733 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-21 15:35:35.260  5499  5733 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 15:35:35.261  5499  5733 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
11-21 15:35:35.261  5499  5733 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 15:35:35.261  5499  5733 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 15:35:35.261  5499  5733 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 15:35:35.261  5499  5733 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 15:35:35.261  5499  5733 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-21 15:35:35.261  5499  5733 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 15:35:35.261  5499  5733 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 15:35:35.261  5499  5733 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 15:35:35.262  5499  5733 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-21 15:35:35.262  5499  5733 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-21 15:35:35.263  5499  5546 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-21 15:35:35.264  5499  5546 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-21 15:35:35.265  5499  5546 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-21 15:35:35.267  5499  5734 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-21 15:35:35.267  5499  5734 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 15:35:35.267  5499  5734 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
,11-21 15:35:35.268  5499  5734 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-21 15:35:35.268  5499  5734 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-21 15:35:35.268  5499  5734 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-21 15:35:35.268  5499  5734 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-21 15:35:35.268  5499  5734 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-21 15:35:35.270  5499  5546 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-21 15:35:35.270  5499  5546 E com.test.thalitest.ThaliTestRunner: 
11-21 15:35:35.270  5499  5546 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-21 15:35:35.270  5499  5546 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363),
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-21 15:35:35.271  5499  5546 E com.test.thalitest.Th,aliTestRunner: The BT listener was bound
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 15:35:35.271  5499  5546 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	,at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
,11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-21 15:35:35.272 , 5499  5546 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.r,un(ParentRunner.java:363)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 15:35:35.272  5499  5546 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 15:35:35.275  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG UnitTest_app: 'Running unit tests'
11-21 15:35:35.275  5499  5546 I jxcore-log: 
11-21 15:35:35.275  5499  5546 I jxcore-log: *Native tests were executed*
11-21 15:35:35.275  5499  5546 I jxcore-log: 
11-21 15:35:35.275  5499  5546 I jxcore-log: Total number of executed tests:  82
11-21 15:35:35.275  5499  5546 I jxcore-log: 
11-21 15:35:35.275  5499  5546 I jxcore-log: Number of passed tests:  79
11-21 15:35:35.275  5499  5546 I jxcore-log: 
11-21 15:35:35.275  5499  5546 I jxcore-log: Number of failed tests:  3
11-21 15:35:35.275  5499  5546 I jxcore-log: 
11-21 15:35:35.275  5499  5546 I jxcore-log: Number of ignored tests:  0
11-21 15:35:35.275  5499  5546 I jxcore-log: 
11-21 15:35:35.276  5499  5546 I jxcore-log: Total duration:  40430
11-21 15:35:35.276  5499  5546 I jxcore-log: 
11-21 15:35:35.276  5499  5546 I jxcore-log: Failed to execute UT.
11-21 15:35:35.276  5499  5546 I jxcore-log: 
11-21 15:35:35.277  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-21 15:35:35.277  5499  5546 I jxcore-log: 
11-21 15:35:35.278  5499  5546 I jxcore-log: 2016-11-21 14:3,5:35 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-21 15:35:35.278  5499  5546 I jxcore-log: 
11-21 15:35:35.281  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 15:35:35.281  5499  5546 I jxcore-log: 
11-21 15:35:35.281  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 15:35:35.281  5499  5546 I jxcore-log: 
11-21 15:35:35.282  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 15:35:35.282  5499  5546 I jxcore-log: 
11-21 15:35:35.283  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 15:35:35.283  5499  5546 I jxcore-log: 
11-21 15:35:35.283  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 15:35:35.283  5499  5546 I jxcore-log: 
11-21 15:35:35.284  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 15:35:35.284  5499  5546 I jxcore-log: 
11-21 15:35:35.284  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 15:35:35.284  5499  5546 I jxcore-log: 
11-21 15:35:35.284  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 15:35:35.284  5499  5546 I jxcore-log: 
11-21 15:35:35.285  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 15:35:35.285  5499  5546 I jxcore-log: 
11-21 15:35:35.285  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 15:35:35.285  5499  5546 I jxcore-log: 
11-21 15:35:35.285  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 15:35:35.285  5499  5546 I jxcore-log: 
11-21 15:35:35.285  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 15:35:35.285  5499  5546 I jxcore-log: 
11-21 15:35:35.285  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 15:35:35.285  5499  5546 I jxcore-log: 
11-21 15:35:35.286  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 15:35:35.286  5499  5546 I jxcore-log: 
11-21 15:35:35.286  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 15:35:35.286  5499  5546 I jxcore-log: 
11-21 15:35:35.286  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 15:35:35.286  5499  5546 I jxcore-log: 
11-21 15:35:,35.286  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 15:35:35.286  5499  5546 I jxcore-log: 
11-21 15:35:35.287  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 15:35:35.287  5499  5546 I jxcore-log: 
11-21 15:35:35.287  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 15:35:35.287  5499  5546 I jxcore-log: 
11-21 15:35:35.287  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 15:35:35.287  5499  5546 I jxcore-log: 
11-21 15:35:35.287  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 15:35:35.287  5499  5546 I jxcore-log: 
11-21 15:35:35.288  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 15:35:35.288  5499  5546 I jxcore-log: 
11-21 15:35:35.288  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 15:35:35.288  5499  5546 I jxcore-log: 
11-21 15:35:35.288  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-21 15:35:35.288  5499  5546 I jxcore-log: 
11-21 15:35:35.288  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 15:35:35.288  5499  5546 I jxcore-log: 
11-21 15:35:35.288  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-21 15:35:35.288  5499  5546 I jxcore-log: 
11-21 15:35:35.289  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 15:35:35.289  5499  5546 I jxcore-log: 
11-21 15:35:35.289  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 15:35:35.289  5499  5546 I jxcore-log: 
11-21 15:35:35.290  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 15:35:35.290  5499  5546 I jxcore-log: 
11-21 15:35:35.290  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 15:35:35.290  5499  5546 I jxcore-log: 
11-21 15:35:35.291  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-21 15:35:35.291  5499  5546 I jxcore-log: 
11-21 15:35:35.291  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 15:35:35.291  5499  5546 I jxcore-log: 
11-21 15:35:35.291  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 15:35:35.291  5499  5546 I jxcore-log: 
11-21 15:35:35.291  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-21 15:35:35.291  5499  5546 I jxcore-log: 
11-21 15:35:35.292  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 15:35:35.292  5499  5546 I jxcore-log: 
11-21 15:35:35.292  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 15:35:35.292  5499  5546 I jxcore-log: 
11-21 15:35:35.292  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 15:35:35.292  5499  5546 I jxcore-log: 
11-21 15:35:35.292  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 15:35:35.292  5499  5546 I jxcore-log: 
11-21 15:35:35.297  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-21 15:35:35.297  5499  5546 I jxcore-log: 
11-21 15:35:35.297  5499  5546 I jxcore-log: 2016-11-21 14:35:35 - WARN testUtils: 'myNameCallback not set!'
11-21 15:35:35.297  5499  5546 I jxcore-log: 
11-21 15:35:35.300  5499  5499 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-21 15:35:37.416  5499  5546 I jxcore-log: 2016-11-21 14:35:37 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-21 15:35:37.416  5499  5546 I jxcore-log: 
,11-21 15:35:37.418  5499  5546 I jxcore-log: 2016-11-21 14:35:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-21 15:35:37.418  5499  5546 I jxcore-log: 
,11-21 15:35:37.727  3484  3484 I ConfigService: onDestroy
,11-21 15:35:37.770  5499  5546 I jxcore-log: 2016-11-21 14:35:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-21 15:35:37.770  5499  5546 I jxcore-log: 
,11-21 15:35:37.783  5499  5546 I jxcore-log: 2016-11-21 14:35:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-21 15:35:37.783  5499  5546 I jxcore-log: 
,11-21 15:35:38.925  5499  5546 I jxcore-log: 2016-11-21 14:35:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-21 15:35:38.925  5499  5546 I jxcore-log: 
,11-21 15:35:39.096  5499  5546 I jxcore-log: 2016-11-21 14:35:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-21 15:35:39.096  5499  5546 I jxcore-log: 
,11-21 15:35:39.102  5499  5546 I jxcore-log: 2016-11-21 14:35:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-21 15:35:39.102  5499  5546 I jxcore-log: 
,11-21 15:35:39.114  5499  5546 I jxcore-log: 2016-11-21 14:35:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-21 15:35:39.114  5499  5546 I jxcore-log: 
,11-21 15:35:39.614  5499  5546 I jxcore-log: 2016-11-21 14:35:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-21 15:35:39.614  5499  5546 I jxcore-log: 
,11-21 15:35:39.660  5499  5546 I jxcore-log: 2016-11-21 14:35:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-21 15:35:39.660  5499  5546 I jxcore-log: 
,11-21 15:35:39.673  5499  5546 I jxcore-log: 2016-11-21 14:35:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-21 15:35:39.673  5499  5546 I jxcore-log: 
,11-21 15:35:39.678  5499  5546 I jxcore-log: 2016-11-21 14:35:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-21 15:35:39.678  5499  5546 I jxcore-log: 
,11-21 15:35:39.960  5499  5546 I jxcore-log: 2016-11-21 14:35:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-21 15:35:39.960  5499  5546 I jxcore-log: 
,11-21 15:35:40.089  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-21 15:35:40.089  5499  5546 I jxcore-log: 
,11-21 15:35:40.467  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-21 15:35:40.467  5499  5546 I jxcore-log: 
,11-21 15:35:40.476  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-21 15:35:40.476  5499  5546 I jxcore-log: 
,11-21 15:35:40.480  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-21 15:35:40.480  5499  5546 I jxcore-log: 
,11-21 15:35:40.484  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-21 15:35:40.484  5499  5546 I jxcore-log: 
,11-21 15:35:40.489  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-21 15:35:40.489  5499  5546 I jxcore-log: 
,11-21 15:35:40.531  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-21 15:35:40.531  5499  5546 I jxcore-log: 
,11-21 15:35:40.539  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-21 15:35:40.539  5499  5546 I jxcore-log: 
,11-21 15:35:40.562  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-21 15:35:40.562  5499  5546 I jxcore-log: 
,11-21 15:35:40.602  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-21 15:35:40.602  5499  5546 I jxcore-log: 
,11-21 15:35:40.618  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-21 15:35:40.618  5499  5546 I jxcore-log: 
,11-21 15:35:40.625  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-21 15:35:40.625  5499  5546 I jxcore-log: 
,11-21 15:35:40.641  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-21 15:35:40.641  5499  5546 I jxcore-log: 
,11-21 15:35:40.656  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-21 15:35:40.656  5499  5546 I jxcore-log: 
,11-21 15:35:40.662  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-21 15:35:40.662  5499  5546 I jxcore-log: 
,11-21 15:35:40.667  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-21 15:35:40.667  5499  5546 I jxcore-log: 
,11-21 15:35:40.681  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-21 15:35:40.681  5499  5546 I jxcore-log: 
,11-21 15:35:40.699  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-21 15:35:40.699  5499  5546 I jxcore-log: 
,11-21 15:35:40.713  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-21 15:35:40.713  5499  5546 I jxcore-log: 
,11-21 15:35:40.724  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-21 15:35:40.724  5499  5546 I jxcore-log: 
,11-21 15:35:40.737  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-21 15:35:40.737  5499  5546 I jxcore-log: 
,11-21 15:35:40.747  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-21 15:35:40.747  5499  5546 I jxcore-log: 
,11-21 15:35:40.761  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-21 15:35:40.761  5499  5546 I jxcore-log: 
,11-21 15:35:40.770  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-21 15:35:40.770  5499  5546 I jxcore-log: 
,11-21 15:35:40.777  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-21 15:35:40.777  5499  5546 I jxcore-log: 
,11-21 15:35:40.799  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-21 15:35:40.799  5499  5546 I jxcore-log: 
,11-21 15:35:40.805  5499  5546 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-21 15:35:40.806  5499  5546 I jxcore-log: 2016-11-21 14:35:40 - INFO testUtils: 'BLE multiple advertisement supported'
11-21 15:35:40.806  5499  5546 I jxcore-log: 
,11-21 15:35:41.055  5499  5546 I jxcore-log: 2016-11-21 14:35:41 - DEBUG CoordinatedClient: 'connected to the test server'
11-21 15:35:41.055  5499  5546 I jxcore-log: 
,11-21 15:35:41.310  5499  5546 I jxcore-log: 2016-11-21 14:35:41 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-21 15:35:41.310  5499  5546 I jxcore-log: 
,11-21 15:35:41.312  5499  5546 I jxcore-log: 2016-11-21 14:35:41 - DEBUG CoordinatedClient: 'test client failed'
11-21 15:35:41.312  5499  5546 I jxcore-log: 
11-21 15:35:41.316  5499  5546 I jxcore-log: 2016-11-21 14:35:41 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-21 15:35:41.316  5499  5546 I jxcore-log: 
,11-21 15:35:41.323  5499  5546 I jxcore-log: 2016-11-21 14:35:41 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-21 15:35:41.323  5499  5546 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-21 15:35:41.323  5499  5546 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-21 15:35:41.323  5499  5546 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-21 15:35:41.323  5499  5546 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-21 15:35:41.323  5499  5546 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-21 15:35:41.323  5499  5546 I jxcore-log: 
,11-21 15:35:41.324  5499  5546 I jxcore-log: 2016-11-21 14:35:41 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-21 15:35:41.324  5499  5546 I jxcore-log: 
,11-21 15:35:41.329  5499  5546 I jxcore-log: 2016-11-21 14:35:41 - ERROR runTests: 'Test client failed: Native unit tests failed
11-21 15:35:41.329  5499  5546 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-21 15:35:41.329  5499  5546 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-21 15:35:41.329  5499  5546 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-21 15:35:41.329  5499  5546 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-21 15:35:41.329  5499  5546 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-21 15:35:41.329  5499  5546 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
11-21 15:35:41.329  5499  5546 I jxcore-log: 
,11-21 15:35:41.773  5743  5743 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-21 15:35:41.778  5743  5743 D AndroidRuntime: CheckJNI is OFF
,11-21 15:35:41.806  5743  5743 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-21 15:35:41.836  5743  5743 I Radio-JNI: register_android_hardware_Radio DONE
,11-21 15:35:41.852  5743  5743 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-21 15:35:41.861   925   938 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-21 15:35:41.862   925   938 I ActivityManager: Killing 5499:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-21 15:35:41.975   925  3032 D GraphicsStats: Buffer count: 2
11-21 15:35:41.976   925  2877 D WifiService: Client connection lost with reason: 4
,11-21 15:35:41.976   925  3033 I WindowState: WIN DEATH: Window{9e96b9c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-21 15:35:41.994   925   938 W ActivityManager: Force removing ActivityRecord{400010d u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-21 15:35:42.003   925   950 I art     : Starting a blocking GC Explicit
,11-21 15:35:42.020   925  3747 W ActivityManager: Spurious death for ProcessRecord{8a7253f 0:com.test.thalitest/u0a77}, curProc for 5499: null
,11-21 15:35:42.045   925  3766 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5499 uid 10077
11-21 15:35:42.043  3766  3766 W Binder_9: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[20938]" dev="sockfs" ino=20938 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 15:35:42.043  3766  3766 W Binder_9: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[20938]" dev="sockfs" ino=20938 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 15:35:42.046  3584  3584 I Keyboard.Facilitator: onFinishInput()
,11-21 15:35:42.095   925   950 I art     : Explicit concurrent mark sweep GC freed 69042(4MB) AllocSpace objects, 15(460KB) LOS objects, 33% free, 29MB/43MB, paused 1.926ms total 92.359ms
,11-21 15:35:42.114  3872  5755 I MicroRecognitionRnrImpl: Starting detection.
,11-21 15:35:42.115  3872  5756 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@7c2fda6
,11-21 15:35:42.117   511  5758 I AudioFlinger: AudioFlinger's thread 0xf1b00000 ready to run
,11-21 15:35:42.118   925   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-21 15:35:42.121  5743  5743 I art     : System.exit called, status: 0
11-21 15:35:42.121  5743  5743 I AndroidRuntime: VM exiting with result code 0.
11-21 15:35:42.121   511  2912 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-21 15:35:42.124  3872  5756 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@7c2fda6
,11-21 15:35:42.130   925   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-21 15:35:42.133   511  5758 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-21 15:35:42.133   511  5758 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
,11-21 15:35:42.134   511  5758 I ACDB-LOADER: ACDB AFE returned = -19
11-21 15:35:42.134   511  5758 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-21 15:35:42.134   511  5758 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-21 15:35:42.134   511  5758 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-21 15:35:42.143   925  2842 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-21 15:35:42.143   511  5758 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-21 15:35:42.144  3982  4084 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-21 15:35:42.144  5595  5595 D BluetoothMapAppObserver: onReceive
11-21 15:35:42.144  5595  5595 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-21 15:35:42.148  3584  3584 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-21 15:35:42.172  3584  5761 I Keyboard.Facilitator.DecoderInitializer: run()
,11-21 15:35:42.187   925   925 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-21 15:35:42.196  3686  3686 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-21 15:35:42.204  3584  5761 I Decoder : createOrResetDecoder
,11-21 15:35:42.223  3298  5764 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-21 15:35:42.230  3484  3484 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-21 15:35:42.230  3484  3484 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-21 15:35:42.231  3872  3872 I HotwordWorkerImpl: onReady
,11-21 15:35:42.244  3484  3484 I ConfigService: onCreate
,11-21 15:35:42.246  3770  5769 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-21 15:35:42.246  3770  5769 D AccountUtils: Clearing selected account for com.test.thalitest
,11-21 15:35:42.249    29    29 W kworker/3:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 15:35:42.256    29    29 W kworker/3:1: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 15:35:42.259  3770  5769 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-21 15:35:42.278  3770  3770 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-21 15:35:42.278  3770  3770 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-21 15:35:42.279  3584  5761 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-21 15:35:42.289    29    29 W kworker/3:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 15:35:42.286  3770  3770 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-21 15:35:42.286  3770  3770 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-21 15:35:42.289  3770  5776 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
,11-21 15:35:42.289  3770  5776 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
,11-21 15:35:42.290  3770  5776 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
,11-21 15:35:42.290  3770  5776 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-21 15:35:42.296  3872  5779 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
11-21 15:35:42.297  3770  5776 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 1
11-21 15:35:42.297  3770  5776 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 2
,11-21 15:35:42.300  3298  5764 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-21 15:35:42.302  3770  5776 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 1
,11-21 15:35:42.303  3709  3910 E ReflectionEngine: Failed to save models
11-21 15:35:42.303  3709  3910 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
,11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 15:35:42.303  3709  3910 E ReflectionEngine: 	... 16 more
--------- beginning of crash
11-21 15:35:42.304  3298  5764 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-21 15:35:42.304  3298  5764 E AndroidRuntime: Process: android.process.acore, PID: 3298
11-21 15:35:42.304  3298  5764 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 15:35:42.304  3298  5764 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db'.
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.search.b.a(SourceFile:42)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:102)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-21 15:35:42.304  3770  5776 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: Couldn't open auto_complete_suggestions.db for writing (will try read-only):
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.da,tabase.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.search.b.a(SourceFile:42)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:102)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-21 15:35:42.304  3770  5776 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 15:35:42.306  3770  5776 W SQLiteOpenHelper: Opened auto_complete_suggestions.db in read-only mode
11-21 15:35:42.306  3770  5776 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
11-21 15:35:42.306  3770  5776 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-21 15:35:42.307  3770  5776 E SQLiteLog: (8) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-21 15:35:42.307  3770  5776 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 1
11-21 15:35:42.307  3770  5776 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-21 15:35:42.307  3770  5776 E AndroidRuntime: Process: com.google.android.gms, PID: 3770
11-21 15:35:42.307  3770  5776 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 15:35:42.307  3770  5776 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: Failed to write the stream file
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2439: open failed: EROFS (Read-only file system)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 15:35:42.322  3709  3910 E ObservedEventLogger: 	... 16 more
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: Failed to write the stream file
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2440: open failed: EROFS (Read-only file system)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 15:35:42.323  3709  3910 E ObservedEventLogger: 	... 16 more
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: Failed to write the stream file
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2441: open failed: EROFS (Read-only file system)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 15:35:42.324  3709  3910 E ObservedEventLogger: 	... 16 more
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: Failed to write the stream file
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2442: open failed: EROFS (Read-only file system)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 15:35:42.325  3709  3910 E ObservedEventLogger: 	... 16 more
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: Failed to write the stream file
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2443: open failed: EROFS (Read-only file system)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 15:35:42.326  3709  3910 E ObservedEventLogger: 	... 16 more
11-21 15:35:42.326  3872  5779 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
11-21 15:35:42.329   925   935 I ActivityManager: Start proc 5782:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-21 15:35:42.340  3584  5761 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-21 15:35:42.342  3584  5761 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-21 15:35:42.342  3584  5761 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-21 15:35:42.345  3584  5761 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-21 15:35:42.345  3584  5761 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-21 15:35:42.346  3584  5761 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-21 15:35:42.346  3584  5761 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-21 15:35:42.346   925  3769 I ActivityManager: Start proc 5795:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-21 15:35:42.348  3872  5779 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
11-21 15:35:42.348  3872  5779 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
11-21 15:35:42.348  3872  5779 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 3872
11-21 15:35:42.348  3872  5779 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 15:35:42.348  3872  5779 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 15:35:42.348  3584  5761 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-21 15:35:42.348  3584  5761 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-21 15:35:42.348  3584  5761 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-21 15:35:42.348  3584  5761 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-21 15:35:42.349  3584  5761 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-21 15:35:42.349  3584  5761 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-21 15:35:42.373   407   407 W Binder_2: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[31630]" dev="sockfs" ino=31630 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 15:35:42.373   407   407 W Binder_2: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[31630]" dev="sockfs" ino=31630 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 15:35:42.376   948   948 W Binder_3: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[33031]" dev="sockfs" ino=33031 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 15:35:42.376   948   948 W Binder_3: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[33031]" dev="sockfs" ino=33031 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 15:35:42.379   925  5810 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-21 15:35:42.408  3770  5769 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
,11-21 15:35:42.418  3770  5811 I GMPM-SVC: App measurement is starting up
,11-21 15:35:42.422  3770  3770 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-21 15:35:42.424  3770  5777 W BaseAppContext: Using Auth Proxy for data requests.
,11-21 15:35:42.425  3770  5811 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-21 15:35:42.426  3770  5811 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-21 15:35:42.427  3770  5777 W BaseAppContext: Using Auth Proxy for data requests.
,11-21 15:35:42.439   925   938 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{86a93bc u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{9d53f8e 3770 com.google.android.gms/10012/u0 remote:8f1389}: process crashing
,11-21 15:35:42.445   925  3769 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3770 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-21 15:35:42.491  3770  5775 W DriveInitializer: Awaiting to be initialized
11-21 15:35:42.492  3770  5816 W DriveInitializer: Background init thread started
,11-21 15:35:42.576  3709  3915 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-21 15:35:42.663   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
