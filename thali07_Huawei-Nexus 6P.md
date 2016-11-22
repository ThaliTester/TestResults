#### Test 931424420ae5e52_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of system
11-22 12:57:31.890   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
11-22 12:57:32.360  5490  5490 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-22 12:57:32.366  5490  5490 D AndroidRuntime: CheckJNI is OFF
11-22 12:57:32.395  5490  5490 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-22 12:57:32.437  5490  5490 I Radio-JNI: register_android_hardware_Radio DONE
11-22 12:57:32.452  5490  5490 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-22 12:57:32.455   927   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-22 12:57:32.474  5490  5490 D AndroidRuntime: Shutting down VM
11-22 12:57:32.481  3833  3846 W SearchService: Abort, client detached.
11-22 12:57:32.497  3833  3833 I HotwordDetector: Closing mic
11-22 12:57:32.497  3833  4055 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@67b989b
11-22 12:57:32.497  3833  4080 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-22 12:57:32.506   927   937 I ActivityManager: Start proc 5499:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-22 12:57:32.564   511  4086 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-22 12:57:32.566   511  4086 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-22 12:57:32.574   511  4086 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-22 12:57:32.574   511  4086 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-22 12:57:32.574   511  2892 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-22 12:57:32.575  3833  4056 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-22 12:57:32.576  3833  4075 I MicroRecognitionRnrImpl: Detection finished
11-22 12:57:32.602  5499  5499 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-22 12:57:32.625  5499  5499 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-22 12:57:32.648  5499  5499 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 5675-5695)
11-22 12:57:32.648  5499  5499 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-22 12:57:32.669  5499  5499 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {862dfa}
11-22 12:57:32.670  5499  5499 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-22 12:57:32.670  5499  5499 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-22 12:57:32.673  5499  5499 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-22 12:57:32.674  5499  5499 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-22 12:57:32.706  5499  5499 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-22 12:57:32.714  5499  5499 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-22 12:57:32.714  5499  5499 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-22 12:57:32.714  5499  5499 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-22 12:57:32.714  5499  5499 I Adreno  : Build Date                       : 12/06/15
11-22 12:57:32.714  5499  5499 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-22 12:57:32.714  5499  5499 I Adreno  : Local Branch                     : mybranch17112971
11-22 12:57:32.714  5499  5499 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-22 12:57:32.714  5499  5499 I Adreno  : Remote Branch                    : NONE
11-22 12:57:32.714  5499  5499 I Adreno  : Reconstruct Branch               : NOTHING
,11-22 12:57:32.757   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b87ef65:true
,11-22 12:57:32.784   764   764 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[21377]" dev="sockfs" ino=21377 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 12:57:32.784   764   764 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21377]" dev="sockfs" ino=21377 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 12:57:32.798  5499  5499 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-22 12:57:32.807  5499  5499 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-22 12:57:32.831   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32317]" dev="sockfs" ino=32317 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 12:57:32.831   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32317]" dev="sockfs" ino=32317 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 12:57:32.834  5499  5536 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 12:57:32.834  3054  3054 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[21389]" dev="sockfs" ino=21389 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 12:57:32.834  3054  3054 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[21389]" dev="sockfs" ino=21389 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 12:57:32.839  5499  5523 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-22 12:57:32.874  5499  5536 I OpenGLRenderer: Initialized EGL, version 1.4
,11-22 12:57:32.954  3460  3460 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32321]" dev="sockfs" ino=32321 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 12:57:32.954  3460  3460 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32321]" dev="sockfs" ino=32321 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 12:57:32.959   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +475ms
,11-22 12:57:32.954  3731  3731 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32320]" dev="sockfs" ino=32320 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 12:57:32.954  3731  3731 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32320]" dev="sockfs" ino=32320 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 12:57:32.965  3550  3550 I Keyboard.Facilitator: onFinishInput()
,11-22 12:57:33.003  5499  5499 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5499
,11-22 12:57:33.118  5499  5499 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-22 12:57:33.215  3988  4342 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-22 12:57:33.313   927  3044 I ActivityManager: Killing 5173:com.android.settings/1000 (adj 15): empty #17
,11-22 12:57:33.327  5499  5539 D jxcore_app_log: JniHelper::setJavaVM(0xf513c000), pthread_self() = -586675920
,11-22 12:57:33.331  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-22 12:57:33.331  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-22 12:57:33.331  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-22 12:57:33.331  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-22 12:57:33.331  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-22 12:57:33.331  5499  5539 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a503199 added. We now have 1 listener(s)
,11-22 12:57:33.334  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-22 12:57:33.334  5499  5539 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 12:57:33.335  5499  5539 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:57:33.335  5499  5539 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-22 12:57:33.337  5499  5539 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd8950c added. We now have 1 listener(s)
11-22 12:57:33.338  5499  5539 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:57:33.341   927  2845 D WifiService: New client listening to asynchronous messages
,11-22 12:57:33.342  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 12:57:33.342  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-22 12:57:33.342  5499  5539 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-22 12:57:33.342  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-22 12:57:33.342  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-22 12:57:33.342  5499  5539 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-22 12:57:33.343  5499  5539 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-22 12:57:33.344  5499  5539 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-22 12:57:33.345   927  3044 I ActivityManager: Killing 5132:org.codeaurora.ims/1001 (adj 15): empty #18
,11-22 12:57:33.373  5499  5499 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-22 12:57:33.841  5499  5508 I art     : Background sticky concurrent mark sweep GC freed 77597(7MB) AllocSpace objects, 16(1476KB) LOS objects, 26% free, 24MB/32MB, paused 2.642ms total 239.678ms
,11-22 12:57:34.928   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 12:57:35.127  5499  5546 W jxcore-log: Initializing JXcore engine
,11-22 12:57:35.127  5499  5546 W jxcore-log: JXcore engine is ready
,11-22 12:57:35.151  5546  5546 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1250 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-22 12:57:35.151  5546  5546 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15435]" dev="sockfs" ino=15435 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-22 12:57:35.151  5546  5546 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-22 12:57:35.151  5546  5546 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32288]" dev="sockfs" ino=32288 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-22 12:57:35.160  5499  5546 W jxcore-log: Starting JXcore engine
,11-22 12:57:35.210  5499  5546 W jxcore-log: Platform android
11-22 12:57:35.210  5499  5546 W jxcore-log: 
,11-22 12:57:35.210  5499  5546 W jxcore-log: Process ARCH arm
11-22 12:57:35.210  5499  5546 W jxcore-log: 
,11-22 12:57:35.353  5499  5546 I jxcore-log: JXcore Cordova bridge is ready!
11-22 12:57:35.353  5499  5546 I jxcore-log: 
,11-22 12:57:35.354  5499  5546 W jxcore-log: JXcore engine is started
11-22 12:57:35.362  5499  5539 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-22 12:57:35.368  5499  5499 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-22 12:57:40.117   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:57:40.970   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 12:57:41.119   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:57:42.120   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:57:42.611  3833  5547 W CronetSyncConnectionRcs: Upload content type not set.
,11-22 12:57:42.685  3469  5552 I VacuumService: Vacuum at: now=1479815862685 tag=VacuumService
,11-22 12:57:42.733  3469  5555 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-22 12:57:42.767  3469  5553 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-22 12:57:42.770  3469  5553 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-22 12:57:42.789  3469  5553 W Uploader:  no longer exists, so no auth token.
,11-22 12:57:42.794  3469  5555 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:57:43.051  3469  5557 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:57:43.121   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:57:43.211  3469  5553 W Uploader:  no longer exists, so no auth token.
,11-22 12:57:43.217  3469  5555 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:57:43.277  3469  5557 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:57:43.352  3469  5555 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:57:43.422  3469  5557 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:57:43.992   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 12:57:44.122   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:57:45.112  5499  5546 I jxcore-log: 2016-11-22 11:57:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-22 12:57:45.112  5499  5546 I jxcore-log: 
,11-22 12:57:45.114  5499  5546 I jxcore-log: 2016-11-22 11:57:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-22 12:57:45.114  5499  5546 I jxcore-log: 
11-22 12:57:45.115  5499  5546 I jxcore-log: 2016-11-22 11:57:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
11-22 12:57:45.115  5499  5546 I jxcore-log: 
,11-22 12:57:45.120  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-22 12:57:45.120  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 12:57:45.120  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:57:45.120  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:57:45.120  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:57:45.120  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:57:45.120  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:57:45.120  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:57:45.120  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:57:45.120  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 12:57:45.121  5499  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 12:57:45.122   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 12:57:45.124  5499  5546 I jxcore-log: 2016-11-22 11:57:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-22 12:57:45.124  5499  5546 I jxcore-log: 
11-22 12:57:45.126  5499  5546 I jxcore-log: 2016-11-22 11:57:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-22 12:57:45.126  5499  5546 I jxcore-log: 
,11-22 12:57:45.377  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 12:57:45.377  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9377a5e added. We now have 2 listener(s)
11-22 12:57:45.378  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 12:57:45.378  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:57:45.378  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:57:45.378  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:57:45.378  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69bee3f added. We now have 2 listener(s)
,11-22 12:57:45.378  5499  5546 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:57:45.379  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 12:57:45.380  5499  5546 D ExecuteNativeTests: Running unit tests
,11-22 12:57:45.381  5499  5546 D BluetoothAdapter: enable(): BT is already enabled..!
,11-22 12:57:45.381   927  3483 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-22 12:57:45.381   927  3483 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:57:46.964   927  5262 D NetlinkSocketObserver: NeighborEvent{elapsedMs=170011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 12:57:47.011   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 12:57:50.042   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 12:57:55.386  5499  5546 I com.test.thalitest.ThaliTestRunner: Running UT
,11-22 12:57:55.455  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 12:57:55.455  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3a7679 added. We now have 3 listener(s)
11-22 12:57:55.456  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 12:57:55.456  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:57:55.456  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:57:55.456  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 12:57:55.457  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5937fbe added. We now have 3 listener(s)
11-22 12:57:55.457  5499  5546 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:57:55.458  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 12:57:55.463  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-22 12:57:55.463  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 12:57:55.463  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:57:55.463  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:57:55.464  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:57:55.465  5499  5546 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-22 12:57:55.465  5499  5546 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 12:57:55.465  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 12:57:55.465  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 12:57:55.465  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:57:55.465  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:57:55.466  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-22 12:57:55.468  5499  5546 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-22 12:57:55.469  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-22 12:57:55.471  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-22 12:57:55.471  5499  5546 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-22 12:57:55.472  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 12:57:55.472  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 12:57:55.481  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 12:57:55.481  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:57:55.481  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:57:55.481  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:57:55.481  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:57:55.481  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:57:55.481  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:57:55.481  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:57:55.481  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 12:57:55.482  5499  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 12:57:55.482  5499  5546 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-22 12:57:55.482  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,11-22 12:57:55.483  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-22 12:57:55.483  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:55.483  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:55.483  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.483  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-22 12:57:55.483  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-22 12:57:55.483  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-22 12:57:55.483  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:57:55.484  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-22 12:57:55.485  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-22 12:57:55.485  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-22 12:57:55.485  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-22 12:57:55.485  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 12:57:55.485  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-22 12:57:55.485  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:57:55.485  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 12:57:55.485  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:57:55.485  5499  5563 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-22 12:57:55.488  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 12:57:55.488  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:57:55.489  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 12:57:55.489  5499  5563 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:57:55.489  5499  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:57:55.490  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-22 12:57:55.491  5499  5563 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-22 12:57:55.487  4561  4561 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33800]" dev="sockfs" ino=33800 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:57:55.487  4561  4561 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33800]" dev="sockfs" ino=33800 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:57:55.492  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.492  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 12:57:55.493  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-22 12:57:55.493  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:57:55.493  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-22 12:57:55.494  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.494  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.494  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-22 12:57:55.494  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-22 12:57:55.495  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 12:57:55.495  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-22 12:57:55.495  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:57:55.495  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:57:55.495  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.495  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-22 12:57:55.495  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:57:55.495  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.495  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.496  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.496  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:57:55.499  4546  4769 D BtGatt.GattService: registerClient() - UUID=d348476b-8097-41d5-8211-3f1478bc5d7b
11-22 12:57:55.500  4546  4608 D BtGatt.GattService: onClientRegistered() - UUID=d348476b-8097-41d5-8211-3f1478bc5d7b, clientIf=5
,11-22 12:57:55.501  5499  5510 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-22 12:57:55.505  4546  4612 D BtGatt.AdvertiseManager: message : 0
11-22 12:57:55.508  4546  4612 D BtGatt.AdvertiseManager: starting multi advertising
11-22 12:57:55.523  4546  4608 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-22 12:57:55.531  4546  4608 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-22 12:57:55.533  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.533  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.533  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-22 12:57:55.533  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.533  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.533  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.533  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.533  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.533  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 12:57:55.534  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 12:57:55.534  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.534  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.534  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.534  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:55.535  5499  5546 I io.jxcore.node.ConnectionHelper: start: OK
11-22 12:57:55.535  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-22 12:57:55.535  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.536  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-22 12:57:55.536  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-22 12:57:55.536  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.537  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.538  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-22 12:57:55.538  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.538  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-22 12:57:55.538  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:57:55.538  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.539  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.539  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-22 12:57:55.539  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.542  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.542  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-22 12:57:55.543  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.543  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.543  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:57:55.543  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-22 12:57:56.037  5499  5546 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 12:57:56.038  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-22 12:57:56.038  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 12:57:56.038  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-22 12:57:56.038  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-22 12:57:56.038  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 12:57:56.038  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 12:57:56.038  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 12:57:56.038  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-22 12:57:56.038  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 12:57:56.038  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 12:57:56.039  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 12:57:56.039  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 12:57:56.039  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 12:57:56.039  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-22 12:57:56.039  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 12:57:56.039  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 12:57:56.039  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 12:57:56.039  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-22 12:57:56.039  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 12:57:56.039  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 12:57:56.040  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 12:57:56.040  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-22 12:57:56.040  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 12:57:56.040  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 12:57:56.040  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 12:57:56.040  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-22 12:57:56.040  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 12:57:56.040  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 12:57:56.040  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-22 12:57:56.040  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 12:57:56.041  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-22 12:57:56.041  5499  5546 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 12:57:56.041  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-22 12:57:56.041  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 12:57:56.041  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-22 12:57:56.041  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-22 12:57:56.041  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-22 12:57:56.042  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 12:57:56.042  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 12:57:56.042  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 12:57:56.042  5499  5563 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-22 12:57:56.042  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 12:57:56.042  5499  5563 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-22 12:57:56.043  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:57:56.043  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-22 12:57:56.043  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-22 12:57:56.043  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:57:56.043  5499  5563 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-22 12:57:56.044  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.044  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.044  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.044  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.045  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:57:56.046  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 12:57:56.047  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:57:56.047  5499  5546 D BluetoothLeScanner: could not find callback wrapper
11-22 12:57:56.048  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:57:56.048  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.048  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.048  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.049  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-22 12:57:56.049  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.051  4546  4612 D BtGatt.AdvertiseManager: message : 1
11-22 12:57:56.052  4546  4612 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-22 12:57:56.064  4546  4608 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-22 12:57:56.065  4546  4608 D BtGatt.GattService: Client app is not null!
,11-22 12:57:56.066  4546  4561 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 12:57:56.067  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 12:57:56.067  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.067  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-22 12:57:56.067  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.068  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.068  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.068  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-22 12:57:56.068  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 12:57:56.069  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:57:56.070  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.072  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.072  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:57:56.073  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.073  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.073  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:57:56.073  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-22 12:57:56.074  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-22 12:57:56.076  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:57:56.076  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:57:56.076  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-22 12:57:56.076  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:57:56.076  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:57:56.076  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.077  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:57:56.077  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-22 12:57:56.077  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.077  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.077  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-22 12:57:56.077  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.077  5499  5546 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-22 12:57:56.077  5499  5546 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-22 12:57:56.078  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-22 12:57:56.078  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-22 12:57:56.078  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.078  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.078  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.078  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-22 12:57:56.078  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-22 12:57:56.078  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-22 12:57:56.078  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:57:56.079  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.079  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.080  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.080  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.080  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:57:56.081  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-22 12:57:56.082  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-22 12:57:56.084  4561  4561 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31300]" dev="sockfs" ino=31300 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:57:56.084  4561  4561 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31300]" dev="sockfs" ino=31300 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:57:56.082  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-22 12:57:56.082  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-22 12:57:56.082  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 12:57:56.082  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-22 12:57:56.082  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:57:56.082  5499  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-22 12:57:56.082  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 12:57:56.083  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-22 12:57:56.083  5499  5566 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:57:56.087  5499  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-22 12:57:56.088  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 12:57:56.088  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:57:56.088  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 12:57:56.093  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.094  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 12:57:56.095  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 12:57:56.095  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:57:56.095  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-22 12:57:56.097  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.098  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.098  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-22 12:57:56.098  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-22 12:57:56.098  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 12:57:56.098  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-22 12:57:56.098  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:57:56.099  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:57:56.099  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.099  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-22 12:57:56.099  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:57:56.099  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.099  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.099  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.100  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:57:56.104  4546  4561 D BtGatt.GattService: registerClient() - UUID=35b094c3-60a9-49f3-aec0-92ac6632ec2f
11-22 12:57:56.105  4546  4608 D BtGatt.GattService: onClientRegistered() - UUID=35b094c3-60a9-49f3-aec0-92ac6632ec2f, clientIf=5
11-22 12:57:56.105  5499  5510 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-22 12:57:56.107  4546  4612 D BtGatt.AdvertiseManager: message : 0
11-22 12:57:56.109  4546  4612 D BtGatt.AdvertiseManager: starting multi advertising
11-22 12:57:56.120  4546  4608 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-22 12:57:56.126  4546  4608 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-22 12:57:56.126  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.127  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.127  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-22 12:57:56.127  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.127  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.127  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.127  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.127  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.127  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 12:57:56.128  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 12:57:56.128  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.129  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.129  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.129  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.130  5499  5546 I io.jxcore.node.ConnectionHelper: start: OK
11-22 12:57:56.130  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-22 12:57:56.130  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.130  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-22 12:57:56.130  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-22 12:57:56.130  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.130  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.130  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:57:56.130  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.130  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-22 12:57:56.130  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:57:56.131  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.131  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.131  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-22 12:57:56.131  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.133  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.133  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-22 12:57:56.133  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.133  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.134  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.134  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-22 12:57:56.633  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-22 12:57:56.634  5499  5546 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-22 12:57:56.634  5499  5546 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-22 12:57:56.634  5499  5546 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 12:57:56.634  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-22 12:57:56.634  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-22 12:57:56.634  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-22 12:57:56.635  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.635  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.635  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.637  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-22 12:57:56.637  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-22 12:57:56.637  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-22 12:57:56.637  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-22 12:57:56.637  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-22 12:57:56.637  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-22 12:57:56.637  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-22 12:57:56.637  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-22 12:57:56.637  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-22 12:57:56.637  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.637  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-22 12:57:56.638  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.638  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.638  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.644  4546  4612 D BtGatt.AdvertiseManager: message : 1
11-22 12:57:56.645  4546  4612 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-22 12:57:56.657  4546  4608 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-22 12:57:56.657  4546  4608 D BtGatt.GattService: Client app is not null!
,11-22 12:57:56.659  4546  4559 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 12:57:56.660  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 12:57:56.660  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.660  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-22 12:57:56.661  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.661  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.661  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.661  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 12:57:56.661  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.661  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.661  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.661  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-22 12:57:56.662  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-22 12:57:56.662  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 12:57:56.662  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-22 12:57:56.662  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:57:56.662  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-22 12:57:56.663  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.663  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-22 12:57:56.663  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-22 12:57:56.663  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.663  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.664  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.665  5499  5546 D BluetoothAdapter: STATE_ON
,11-22 12:57:56.670  4546  4766 D BtGatt.GattService: registerClient() - UUID=2b01e3d6-0790-48ad-987f-6390eacafabf
11-22 12:57:56.671  4546  4608 D BtGatt.GattService: onClientRegistered() - UUID=2b01e3d6-0790-48ad-987f-6390eacafabf, clientIf=5
11-22 12:57:56.671  5499  5509 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-22 12:57:56.673  4546  4612 D BtGatt.AdvertiseManager: message : 0
,11-22 12:57:56.677  4546  4612 D BtGatt.AdvertiseManager: starting multi advertising
,11-22 12:57:56.692  4546  4608 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-22 12:57:56.699  4546  4608 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-22 12:57:56.700  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.700  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.700  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-22 12:57:56.700  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.700  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.701  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.701  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.701  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.701  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.701  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 12:57:56.701  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.701  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:57:56.701  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-22 12:57:56.701  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:57:56.701  5499  5546 I io.jxcore.node.ConnectionHelper: start: OK
11-22 12:57:56.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-22 12:57:56.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-22 12:57:56.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-22 12:57:56.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.702  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:57:56.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-22 12:57:56.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-22 12:57:56.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.702  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.702  5499  5546 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 12:57:56.703  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-22 12:57:56.703  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 12:57:56.703  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-22 12:57:56.703  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-22 12:57:56.703  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-22 12:57:56.703  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 12:57:56.703  5499  5566 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-22 12:57:56.703  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 12:57:56.703  5499  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-22 12:57:56.703  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 12:57:56.703  5499  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-22 12:57:56.703  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 12:57:56.703  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:57:56.703  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-22 12:57:56.704  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-22 12:57:56.704  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:57:56.704  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.704  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.704  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.704  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.705  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:57:56.705  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 12:57:56.706  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:57:56.706  5499  5546 D BluetoothLeScanner: could not find callback wrapper
11-22 12:57:56.706  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:57:56.706  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.706  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.706  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.706  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-22 12:57:56.706  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.707  4546  4612 D BtGatt.AdvertiseManager: message : 1
11-22 12:57:56.708  4546  4612 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-22 12:57:56.714  4546  4608 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-22 12:57:56.715  4546  4608 D BtGatt.GattService: Client app is not null!
11-22 12:57:56.715  4546  4559 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 12:57:56.716  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 12:57:56.716  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.716  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-22 12:57:56.716  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.716  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.717  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.717  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 12:57:56.717  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-22 12:57:56.717  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:57:56.717  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.719  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.719  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:57:56.719  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.719  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.719  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:57:56.719  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-22 12:57:56.719  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-22 12:57:56.720  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:57:56.720  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:57:56.720  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:57:56.720  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:57:56.720  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.720  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:57:56.720  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-22 12:57:56.720  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.720  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.720  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-22 12:57:56.720  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.722  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.722  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-22 12:57:56.722  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.722  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.722  5499  5546 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-22 12:57:56.722  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.722  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 12:57:56.723  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-22 12:57:56.724  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-22 12:57:56.724  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-22 12:57:56.724  5499  5546 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-22 12:57:56.725  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-22 12:57:56.725  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-22 12:57:56.726  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-22 12:57:56.727  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 12:57:56.727  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:57:56.727  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:57:56.727  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:57:56.727  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 12:57:56.727  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 12:57:56.727  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:57:56.727  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:57:56.727  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 12:57:56.727  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:57:56.727  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:57:56.727  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:57:56.728  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-22 12:57:56.728  5499  5546 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 12:57:56.728  5499  5546 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 12:57:56.729  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-22 12:57:56.731  5499  5546 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-22 12:57:56.731  5499  5546 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-22 12:57:56.731  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 12:57:56.732  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 12:57:56.733  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 12:57:56.733  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 12:57:56.733  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 12:57:56.733  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 12:57:56.733  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 12:57:56.733  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-22 12:57:56.733  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 12:57:56.733  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 12:57:56.733  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 12:57:56.733  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 12:57:56.733  5499  5546 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-22 12:57:56.734  5499  5546 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 12:57:56.734  5499  5546 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-22 12:57:56.734  5499  5546 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 12:57:56.734  5499  5546 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-22 12:57:56.734  5499  5546 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-22 12:57:56.734  5499  5546 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 12:57:56.734  5499  5546 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 12:57:56.734  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-22 12:57:56.738  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-22 12:57:56.739  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-22 12:57:56.739  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-22 12:57:56.740  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-22 12:57:56.740  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-22 12:57:56.740  5499  5546 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,11-22 12:57:56.740  5499  5546 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 12:57:56.740  5499  5546 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,11-22 12:57:56.744  4559  4559 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31310]" dev="sockfs" ino=31310 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:57:56.744  4559  4559 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31310]" dev="sockfs" ino=31310 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 12:57:56.742  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-22 12:57:56.742  5499  5546 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-22 12:57:56.742  5499  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
11-22 12:57:56.743  5499  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-22 12:57:56.743  5499  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-22 12:57:56.743  5499  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-22 12:57:56.743  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-22 12:57:56.743  5499  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-22 12:57:56.744  5499  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-22 12:57:56.744  5499  5570 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-22 12:57:56.745  5499  5570 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:57:56.745  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-22 12:57:56.745  5499  5546 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-22 12:57:56.745  5499  5546 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,11-22 12:57:56.745  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 12:57:56.745  5499  5546 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-22 12:57:56.745  5499  5546 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 12:57:56.746  5499  5546 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-22 12:57:56.746  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 12:57:56.746  5499  5546 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-22 12:57:56.746  5499  5546 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 12:57:56.746  5499  5546 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 12:57:56.746  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 12:57:56.746  5499  5546 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-22 12:57:56.747  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-22 12:57:56.747  5499  5546 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-22 12:57:56.747  5499  5546 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-22 12:57:56.747  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-22 12:57:56.747  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-22 12:57:56.747  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.747  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.747  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.747  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-22 12:57:56.747  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-22 12:57:56.747  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-22 12:57:56.748  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:57:56.748  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-22 12:57:56.750  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-22 12:57:56.750  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-22 12:57:56.750  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-22 12:57:56.751  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 12:57:56.751  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-22 12:57:56.751  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-22 12:57:56.751  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:57:56.751  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 12:57:56.751  5499  5571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-22 12:57:56.752  5499  5571 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:57:56.751  4766  4766 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[29565]" dev="sockfs" ino=29565 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:57:56.751  4766  4766 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[29565]" dev="sockfs" ino=29565 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:57:56.754  5499  5571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-22 12:57:56.756  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 12:57:56.757  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:57:56.757  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 12:57:56.760  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.760  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 12:57:56.761  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 12:57:56.761  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:57:56.761  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-22 12:57:56.762  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.762  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.762  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-22 12:57:56.762  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-22 12:57:56.762  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 12:57:56.762  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-22 12:57:56.763  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:57:56.763  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:57:56.763  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.763  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-22 12:57:56.763  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:57:56.763  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.763  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.763  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.764  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:57:56.768  4546  4766 D BtGatt.GattService: registerClient() - UUID=ef2468ca-3b49-48b5-9e9e-e023449c08e7
11-22 12:57:56.768  4546  4608 D BtGatt.GattService: onClientRegistered() - UUID=ef2468ca-3b49-48b5-9e9e-e023449c08e7, clientIf=5
11-22 12:57:56.768  5499  5509 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-22 12:57:56.770  4546  4612 D BtGatt.AdvertiseManager: message : 0
11-22 12:57:56.772  4546  4612 D BtGatt.AdvertiseManager: starting multi advertising
,11-22 12:57:56.780  4546  4608 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-22 12:57:56.784  4546  4608 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-22 12:57:56.785  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:56.785  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.785  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-22 12:57:56.785  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.785  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.785  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.785  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.785  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.785  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-22 12:57:56.787  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-22 12:57:56.787  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.788  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.788  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.788  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:56.788  5499  5546 I io.jxcore.node.ConnectionHelper: start: OK
11-22 12:57:56.788  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.789  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-22 12:57:56.789  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-22 12:57:56.789  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 12:57:56.791  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.791  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-22 12:57:56.792  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.792  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.792  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:57:56.792  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-22 12:57:56.925   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 12:57:57.289  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 12:57:57.289  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-22 12:57:57.290  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-22 12:57:57.290  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-22 12:57:57.290  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 12:57:57.290  5499  5571 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-22 12:57:57.291  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 12:57:57.291  5499  5571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-22 12:57:57.291  5499  5571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-22 12:57:57.291  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 12:57:57.291  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:57:57.291  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-22 12:57:57.291  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-22 12:57:57.291  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-22 12:57:57.292  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:57:57.292  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-22 12:57:57.297  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3a7679 removed from the list
11-22 12:57:57.297  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:57:57.297  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-22 12:57:57.297  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-22 12:57:57.297  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:57:57.298  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.298  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.298  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.298  5499  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
,11-22 12:57:57.298  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.298  5499  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-22 12:57:57.299  5499  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
11-22 12:57:57.299  4546  4757 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
11-22 12:57:57.300  5499  5570 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-22 12:57:57.300  5499  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
,11-22 12:57:57.300  5499  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
11-22 12:57:57.301  5499  5546 D BluetoothAdapter: STATE_ON
,11-22 12:57:57.301  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 12:57:57.301  5499  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
,11-22 12:57:57.302  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:57:57.302  5499  5546 D BluetoothLeScanner: could not find callback wrapper
11-22 12:57:57.303  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:57:57.303  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.303  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.303  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:57.303  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-22 12:57:57.303  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.304  4546  4612 D BtGatt.AdvertiseManager: message : 1
11-22 12:57:57.305  4546  4612 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-22 12:57:57.314  4546  4608 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-22 12:57:57.315  4546  4608 D BtGatt.GattService: Client app is not null!
,11-22 12:57:57.316  4546  4561 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 12:57:57.316  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-22 12:57:57.317  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.317  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-22 12:57:57.317  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.317  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.317  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.317  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 12:57:57.318  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 12:57:57.319  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:57:57.319  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.321  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:57:57.321  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:57:57.321  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.321  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:57:57.321  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5937fbe removed from the list
11-22 12:57:57.321  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:57:57.321  5499  5546 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:57:57.321  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 12:57:57.321  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:57:57.321  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-22 12:57:57.321  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:57:57.321  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:57:57.321  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-22 12:57:57.321  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:57:57.322  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:57:57.322  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-22 12:57:57.322  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 12:57:57.324  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:57:57.324  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:57.324  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:57:57.324  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:57:57.324  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 12:57:57.825  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 12:57:59.126   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 12:58:01.874  4546  4755 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-22 12:58:01.874  4546  4755 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-22 12:58:02.152   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 12:58:02.326  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-22 12:58:02.328  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-22 12:58:02.329  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 12:58:02.329  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 12:58:02.336  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-22 12:58:02.338  5499  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-22 12:58:02.339  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-22 12:58:02.339  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-22 12:58:02.340  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-22 12:58:02.340  5499  5573 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:58:02.340  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 12:58:02.340  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 12:58:02.340  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-22 12:58:02.341  4561  4561 W Binder_2: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[31319]" dev="sockfs" ino=31319 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 12:58:02.341  4561  4561 W Binder_2: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[31319]" dev="sockfs" ino=31319 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 12:58:02.345  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-22 12:58:02.346  5499  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-22 12:58:02.347  5499  5546 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-22 12:58:02.347  5499  5546 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 12:58:02.348  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 12:58:02.348  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 12:58:02.348  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:58:02.350  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-22 12:58:02.357  5499  5546 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-22 12:58:02.357  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:58:02.357  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-22 12:58:02.357  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-22 12:58:02.357  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-22 12:58:02.357  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 12:58:02.358  5499  5573 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-22 12:58:02.358  5499  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-22 12:58:02.358  5499  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-22 12:58:02.358  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-22 12:58:02.358  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 12:58:02.359  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 12:58:02.359  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:58:02.359  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-22 12:58:02.359  5499  5546 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3a7679 not in the list
,11-22 12:58:02.359  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:58:02.360  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:58:02.360  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-22 12:58:02.360  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:58:02.360  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:02.362  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:02.362  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 12:58:02.362  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:02.362  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:02.362  5499  5546 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5937fbe not in the list
11-22 12:58:02.362  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:58:02.362  5499  5546 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:58:02.362  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:58:02.362  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 12:58:02.364  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-22 12:58:02.364  5499  5546 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-22 12:58:02.364  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 12:58:02.364  5499  5546 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-22 12:58:02.364  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 12:58:02.364  5499  5546 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-22 12:58:02.364  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 12:58:02.365  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-22 12:58:02.365  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-22 12:58:02.367  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-22 12:58:02.367  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-22 12:58:02.367  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-22 12:58:02.368  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,11-22 12:58:02.368  5499  5546 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-22 12:58:02.368  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 12:58:02.368  5499  5546 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-22 12:58:02.368  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 12:58:02.368  5499  5546 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-22 12:58:02.368  5499  5546 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-22 12:58:02.369  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-22 12:58:02.369  5499  5546 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-22 12:58:02.369  5499  5546 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-22 12:58:02.370  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-22 12:58:02.370  5499  5546 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-22 12:58:02.370  5499  5546 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-22 12:58:02.370  5499  5546 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-22 12:58:02.370  5499  5546 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-22 12:58:02.371  5499  5546 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-22 12:58:02.371  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:58:02.371  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa9e39c added. We now have 3 listener(s)
,11-22 12:58:02.373  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 12:58:02.373  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:58:02.373  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:58:02.373  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:58:02.373  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@557a1a5 added. We now have 3 listener(s)
11-22 12:58:02.373  5499  5546 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:58:02.374  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 12:58:02.376  5499  5546 D BluetoothAdapter: enable(): BT is already enabled..!
,11-22 12:58:02.377   927  3460 D WifiService: setWifiEnabled: true pid=5499, uid=10077
11-22 12:58:02.377   927  3460 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-22 12:58:02.378  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-22 12:58:02.381  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-22 12:58:02.382  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-22 12:58:02.382  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-22 12:58:02.387  4546  4604 D BluetoothAdapterState: Current state: ON, message: 23
11-22 12:58:02.387  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:58:02.387  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:58:02.387  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:58:02.387  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:58:02.387  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:58:02.387  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:58:02.387  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:58:02.387  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:58:02.387  5499  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 12:58:02.387  4546  4604 D BluetoothAdapterProperties: Setting state to 13
11-22 12:58:02.387  4546  4604 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-22 12:58:02.388  5499  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:58:02.388  4546  4604 D BluetoothAdapterProperties: onBluetoothDisable()
11-22 12:58:02.388  5499  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 12:58:02.389  4546  4604 I BluetoothAdapterState: Entering PendingCommandState
,11-22 12:58:02.390  4546  4546 D BluetoothMapService: onReceive
11-22 12:58:02.390  4546  4546 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-22 12:58:02.390  4546  4546 D BluetoothMapService: STATE_TURNING_OFF
11-22 12:58:02.390  4546  4546 D BluetoothMapService: MAP Service closeService in
11-22 12:58:02.390  4546  4546 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 12:58:02.390  4546  4546 D ObexServerSockets0: shutdown(block = true)
,11-22 12:58:02.391  4546  4546 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 12:58:02.391  4546  4546 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 12:58:02.391  4546  4757 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-22 12:58:02.392  4546  4771 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-22 12:58:02.392  4546  4772 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-22 12:58:02.394  4546  4546 I BtOppRfcommListener: stopping Accept Thread
11-22 12:58:02.394  4546  5193 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-22 12:58:02.394  4546  5193 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-22 12:58:02.406   927   940 I ActivityManager: Start proc 5576:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-22 12:58:02.406  4546  4608 D BluetoothAdapterProperties: Scan Mode:20
11-22 12:58:02.407  4546  4604 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-22 12:58:02.410  4546  4546 D HeadsetService: Received stop request...Stopping profile...
11-22 12:58:02.412  3649  3874 D BluetoothHeadset: Proxy object disconnected
,11-22 12:58:02.412  4546  4546 V BluetoothAdapterState: isTurningOff()=true
11-22 12:58:02.412  4546  4546 V BluetoothAdapterState: isTurningOn()=false
11-22 12:58:02.412  4546  4546 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:02.412  4546  4546 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:02.412  3025  3873 D BluetoothHeadset: Proxy object disconnected
11-22 12:58:02.413   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 12:58:02.413  3025  3025 D HeadsetProfile: Bluetooth service disconnected
,11-22 12:58:02.413   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 12:58:02.413   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 12:58:02.416  4546  4546 D A2dpService: Received stop request...Stopping profile...
,11-22 12:58:02.416  4546  4761 D A2dpStateMachine: Exit Disconnected: -1
11-22 12:58:02.417   927   927 D BluetoothA2dp: Proxy object disconnected
11-22 12:58:02.418  3025  3025 D BluetoothA2dp: Proxy object disconnected
,11-22 12:58:02.418  4546  4546 D HidService: Received stop request...Stopping profile...
,11-22 12:58:02.418  4546  4546 D HidService: Stopping Bluetooth HidService
11-22 12:58:02.419  3025  3025 D BluetoothInputDevice: Proxy object disconnected
11-22 12:58:02.419  3025  3025 D HidProfile: Bluetooth service disconnected
,11-22 12:58:02.421  4546  4546 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 12:58:02.421  4546  4546 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 12:58:02.422  4546  4755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:58:02.422  4546  4755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:58:02.422  4546  4755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:58:02.422  4546  4546 D HealthService: Received stop request...Stopping profile...
11-22 12:58:02.422  4546  4608 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 12:58:02.423  4546  4608 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 12:58:02.423  4546  4546 D PanService: Received stop request...Stopping profile...
11-22 12:58:02.424  3025  3025 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 12:58:02.424  3025  3025 D PanProfile: Bluetooth service disconnected
11-22 12:58:02.424  4546  4546 D BluetoothMapService: Received stop request...Stopping profile...
11-22 12:58:02.424  4546  4546 D BluetoothMapService: stop()
11-22 12:58:02.425  4546  4546 D BluetoothMapAppObserver: deinitObservers()
11-22 12:58:02.425  4546  4546 D BluetoothMapAppObserver: removeReceiver()
,11-22 12:58:02.427  3025  3025 D BluetoothMap: Proxy object disconnected
11-22 12:58:02.427  3025  3025 D MapProfile: Bluetooth service disconnected
11-22 12:58:02.427  4546  4546 V BluetoothAdapterState: isTurningOff()=true
11-22 12:58:02.427  4546  4546 V BluetoothAdapterState: isTurningOn()=false
11-22 12:58:02.427  4546  4546 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:02.427  4546  4546 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 12:58:02.428  4546  4546 D SapService: Received stop request...Stopping profile...
11-22 12:58:02.428  4546  4546 V SapService: stop()
,11-22 12:58:02.429  4546  4608 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-22 12:58:02.429  4546  4755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:58:02.429  4546  4546 V BluetoothAdapterState: isTurningOff()=true
11-22 12:58:02.430  4546  4546 V BluetoothAdapterState: isTurningOn()=false
11-22 12:58:02.430  4546  4546 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:02.430  4546  4755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:58:02.430  4546  4546 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:02.430  4546  4755 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 12:58:02.430  4546  4755 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 12:58:02.430  4546  4755 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 12:58:02.430  4546  4755 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 12:58:02.430  4546  4546 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 12:58:02.430  4546  4546 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-22 12:58:02.430  4546  4546 V BluetoothAdapterState: isTurningOff()=true
11-22 12:58:02.430  4546  4546 V BluetoothAdapterState: isTurningOn()=false
11-22 12:58:02.430  4546  4546 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:02.430  4546  4546 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:02.430  4546  4608 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 12:58:02.430  4546  4546 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 12:58:02.430  4546  4608 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 12:58:02.431  4546  4546 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 12:58:02.431  4546  4546 V BluetoothAdapterState: isTurningOff()=true
11-22 12:58:02.431  4546  4546 V BluetoothAdapterState: isTurningOn()=false
11-22 12:58:02.431  4546  4546 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 12:58:02.431  4546  4546 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:02.431  4546  4546 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 12:58:02.431  4546  4546 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-22 12:58:02.433  4546  4546 D BluetoothMapService: MAP Service closeService in
11-22 12:58:02.433  4546  4546 V BluetoothAdapterState: isTurningOff()=true
11-22 12:58:02.433  4546  4546 V BluetoothAdapterState: isTurningOn()=false
11-22 12:58:02.433  4546  4546 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:02.434  4546  4546 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:02.434  4546  4546 D BluetoothMapService: cleanup()
11-22 12:58:02.434  4546  4546 D BluetoothMapService: MAP Service closeService in
11-22 12:58:02.434  4546  4546 V BluetoothAdapterState: isTurningOff()=true
11-22 12:58:02.434  4546  4546 V BluetoothAdapterState: isTurningOn()=false
11-22 12:58:02.434  4546  4546 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:02.434  4546  4546 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:02.434  4546  4604 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 12:58:02.434  4546  4604 D BluetoothAdapterProperties: Setting state to 15
,11-22 12:58:02.434  4546  4604 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-22 12:58:02.435  4546  4604 I BluetoothAdapterState: Entering BleOnState
11-22 12:58:02.435  3649  3666 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:58:02.435  3025  3872 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-22 12:58:02.438   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 12:58:02.439  3025  3038 D BluetoothMap: onBluetoothStateChange: up=false
11-22 12:58:02.439  3025  3873 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:58:02.440   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 12:58:02.440  3025  3037 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-22 12:58:02.441  3025  3872 D BluetoothPan: onBluetoothStateChange on: false
11-22 12:58:02.441   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:58:02.441  3025  3038 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 12:58:02.442   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:58:02.442  4546  4604 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 12:58:02.442  4546  4604 D BluetoothAdapterProperties: Setting state to 16
,11-22 12:58:02.442  4546  4604 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-22 12:58:02.443  4546  4604 D BluetoothAdapterProperties: onBleDisable
11-22 12:58:02.443  4546  4604 I BluetoothAdapterState: Entering PendingCommandState
11-22 12:58:02.443  4546  4605 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 12:58:02.445  4546  4608 D BluetoothAdapterProperties: Scan Mode:20
11-22 12:58:02.446  4546  4755 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 12:58:02.446  4546  4755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 12:58:02.455  5576  5576 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-22 12:58:02.468  5576  5576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 12:58:02.473   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ee0925:true
,11-22 12:58:02.474  3469  3469 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 12:58:02.490  5576  5576 D LocalBluetoothProfileManager: Adding local MAP profile
,11-22 12:58:02.491  5576  5576 D BluetoothMap: Create BluetoothMap proxy object
,11-22 12:58:02.497  5576  5576 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-22 12:58:02.503  5576  5576 D DockEventReceiver: finishStartingService: stopping service
,11-22 12:58:02.507  5576  5576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 12:58:02.512  5576  5576 D DockEventReceiver: finishStartingService: stopping service
,11-22 12:58:02.512  3469  3469 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 12:58:02.514   927  3731 I ActivityManager: Killing 5294:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-22 12:58:02.652  4546  4608 I bt_hci  : shut_down
,11-22 12:58:02.657  4546  4617 D bt_hwcfg: hw_epilog_process
,11-22 12:58:02.658  4546  4617 I bt_vendor: low_power_mode_cb
,11-22 12:58:02.660  4546  4617 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-22 12:58:02.660  4546  4617 I bt_vendor: epilog_cb
,11-22 12:58:02.660  4546  4617 I bt_hci  : epilog_finished_callback
,11-22 12:58:02.663  4546  4608 I bt_hci_h4: hal_close
,11-22 12:58:02.664  4546  4608 I bt_userial_vendor: device fd = 54 close
,11-22 12:58:02.782  4546  4605 D bt_stack_manager: event_shut_down_stack finished.
,11-22 12:58:02.783  4546  4604 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-22 12:58:02.787  4546  4604 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-22 12:58:02.787  4546  4546 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 12:58:02.788  4546  4546 D BtGatt.GattService: Received stop request...Stopping profile...
11-22 12:58:02.789  4546  4546 D BtGatt.GattService: stop()
11-22 12:58:02.789  4546  4546 D BtGatt.AdvertiseManager: advertise clients cleared
,11-22 12:58:02.792  4546  4546 V BluetoothAdapterState: isTurningOff()=false
11-22 12:58:02.792  4546  4546 V BluetoothAdapterState: isTurningOn()=false
11-22 12:58:02.792  4546  4546 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:02.792  4546  4546 V BluetoothAdapterState: isBleTurningOff()=true
11-22 12:58:02.793  4546  4604 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 12:58:02.793  4546  4604 D BluetoothAdapterProperties: Setting state to 10
11-22 12:58:02.793  4546  4604 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-22 12:58:02.795   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-22 12:58:02.796  4546  4604 I BluetoothAdapterState: Entering OffState
,11-22 12:58:02.811  4546  4546 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-22 12:58:02.811  4546  4546 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 12:58:02.811  4546  4546 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-22 12:58:02.813  4546  4605 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-22 12:58:02.825  4546  4546 I art     : System.exit called, status: 0
,11-22 12:58:02.825  4546  4546 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 12:58:02.857   927   937 I ActivityManager: Process com.android.bluetooth (pid 4546) has died
,11-22 12:58:02.862  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 12:58:02.888  5499  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 12:58:02.889  5499  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:58:02.889  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:58:02.889  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:58:02.889  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:58:02.889  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 12:58:02.889  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:58:02.889  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:58:02.889  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:58:02.889  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 12:58:02.889  5499  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:58:02.889  5499  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 12:58:02.893  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:58:02.909   927   944 I ActivityManager: Start proc 5593:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 12:58:02.971  5593  5593 D AdapterServiceConfig: Adding HeadsetService
,11-22 12:58:02.971  5593  5593 D AdapterServiceConfig: Adding A2dpService
11-22 12:58:02.971  5593  5593 D AdapterServiceConfig: Adding HidService
11-22 12:58:02.972  5593  5593 D AdapterServiceConfig: Adding HealthService
11-22 12:58:02.972  5593  5593 D AdapterServiceConfig: Adding PanService
11-22 12:58:02.972  5593  5593 D AdapterServiceConfig: Adding GattService
,11-22 12:58:02.972  5593  5593 D AdapterServiceConfig: Adding BluetoothMapService
11-22 12:58:02.972  5593  5593 D AdapterServiceConfig: Adding SapService
,11-22 12:58:02.982   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@89ead77:true
,11-22 12:58:02.982  5593  5593 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 12:58:02.985  5593  5593 I bt_bluedroid: init
,11-22 12:58:02.986  5593  5605 I BluetoothAdapterState: Entering OffState
,11-22 12:58:02.988  5593  5606 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-22 12:58:02.988  5593  5606 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 12:58:02.988  5593  5606 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-22 12:58:02.988  5593  5606 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-22 12:58:02.989  5593  5593 I bt_bluedroid: get_profile_interface socket
,11-22 12:58:02.990  5593  5609 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 12:58:02.991  5593  5593 I bt_bluedroid: get_profile_interface sdp
,11-22 12:58:02.993  5593  5609 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 12:58:02.996  5593  5604 I bt_bluedroid: config_hci_snoop_log
,11-22 12:58:02.997   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 12:58:03.001  5593  5605 D BluetoothAdapterState: Current state: OFF, message: 0
,11-22 12:58:03.001  5593  5605 D BluetoothAdapterProperties: Setting state to 14
11-22 12:58:03.002  5593  5605 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-22 12:58:03.003  5593  5605 D BluetoothBondStateMachine: make
,11-22 12:58:03.005  5593  5610 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 12:58:03.007  5593  5605 I BluetoothAdapterState: Entering PendingCommandState
,11-22 12:58:03.008  5593  5593 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 12:58:03.010  5593  5593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f656dd
11-22 12:58:03.010  5593  5593 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 12:58:03.011  5593  5593 D BtGatt.GattService: Received start request. Starting profile...
11-22 12:58:03.011  5593  5593 D BtGatt.GattService: start()
11-22 12:58:03.011  5593  5593 I bt_bluedroid: get_profile_interface gatt
11-22 12:58:03.012  5593  5593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f656dd
,11-22 12:58:03.012  5593  5593 D BtGatt.AdvertiseManager: advertise manager created
,11-22 12:58:03.017  5593  5593 V BluetoothAdapterState: isTurningOff()=false
,11-22 12:58:03.017  5593  5593 V BluetoothAdapterState: isTurningOn()=false
11-22 12:58:03.017  5593  5593 V BluetoothAdapterState: isBleTurningOn()=true
11-22 12:58:03.017  5593  5593 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:03.018  5593  5605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 12:58:03.019  5593  5605 I bt_bluedroid: bt_bluedroid
11-22 12:58:03.019  5593  5606 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-22 12:58:03.019  5593  5606 I bt_hci  : start_up
,11-22 12:58:03.024  5593  5606 I bt_vendor: alloc value 0xf3df3871
,11-22 12:58:03.025  5593  5606 I bt_vendor: init
11-22 12:58:03.025  5593  5606 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 12:58:03.025  5593  5606 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 12:58:03.133  5593  5606 D bt_hci  : start_up starting async portion
,11-22 12:58:03.133  5593  5613 I bt_hci  : event_finish_startup
11-22 12:58:03.133  5593  5613 I bt_hci_h4: hal_open
11-22 12:58:03.134  5593  5613 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-22 12:58:03.135  5593  5613 I bt_userial_vendor: device fd = 54 open
,11-22 12:58:03.134  5615  5615 W irq/448-msm_hs_: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 12:58:03.149  5593  5613 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 12:58:03.152  5593  5613 D bt_hwcfg: Chipset BCM4358A3
,11-22 12:58:03.152  5593  5613 D bt_hwcfg: Target name = [BCM4358A3]
11-22 12:58:03.152  5593  5613 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 12:58:03.398  5593  5605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-22 12:58:03.537  5593  5613 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 12:58:03.538  5593  5613 D bt_hwcfg: Settlement delay -- 100 ms
11-22 12:58:03.538  5593  5613 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 12:58:03.662  5593  5613 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 12:58:03.663  5593  5613 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-22 12:58:03.665  5593  5613 I bt_hwcfg: vendor lib fwcfg completed
,11-22 12:58:03.665  5593  5613 I bt_vendor: firmware callback
,11-22 12:58:03.665  5593  5613 I bt_hci  : firmware_config_callback
,11-22 12:58:03.675  5593  5617 I bt_btu  : btu_task pending for preload complete event
11-22 12:58:03.675  5593  5617 I bt_btu_task: Bluetooth chip preload is complete
,11-22 12:58:03.675  5593  5617 I bt_btu  : btu_task received preload complete event
,11-22 12:58:03.681  5593  5617 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 12:58:03.682  5593  5617 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-22 12:58:03.682  5593  5617 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-22 12:58:03.682  5593  5617 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-22 12:58:03.682  5593  5617 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-22 12:58:03.682  5593  5617 I         : BTE_InitTraceLevels -- TRC_A2D
11-22 12:58:03.682  5593  5617 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-22 12:58:03.682  5593  5617 I         : BTE_InitTraceLevels -- TRC_BTM
,11-22 12:58:03.682  5593  5617 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 12:58:03.683  5593  5617 I         : BTE_InitTraceLevels -- TRC_PAN
11-22 12:58:03.683  5593  5617 I         : BTE_InitTraceLevels -- TRC_SDP
,11-22 12:58:03.683  5593  5617 I         : BTE_InitTraceLevels -- TRC_GATT
11-22 12:58:03.683  5593  5617 I         : BTE_InitTraceLevels -- TRC_SMP
11-22 12:58:03.683  5593  5617 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-22 12:58:03.683  5593  5617 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 12:58:03.768  5593  5617 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d71549
11-22 12:58:03.768  5593  5617 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d71549 
,11-22 12:58:03.789  5593  5609 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 12:58:03.790  5593  5609 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 12:58:03.791  5593  5609 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 12:58:03.794  5593  5609 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 12:58:03.797  5593  5609 D BluetoothAdapterProperties: Scan Mode:20
,11-22 12:58:03.797  5593  5609 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-22 12:58:03.798  5593  5609 D bt_hci  : do_postload posting postload work item
11-22 12:58:03.798  5593  5613 I bt_hci  : event_postload
11-22 12:58:03.799  5593  5613 I bt_vendor: sco_config_cb
11-22 12:58:03.799  5593  5613 I bt_hci  : sco_config_callback postload finished.
,11-22 12:58:03.804  5593  5609 D bt_bte_conf: Device ID record 1 : primary
,11-22 12:58:03.804  5593  5609 D bt_bte_conf:   vendorId            = 000f
11-22 12:58:03.804  5593  5609 D bt_bte_conf:   vendorIdSource      = 0001
,11-22 12:58:03.804  5593  5609 D bt_bte_conf:   product             = 1200
11-22 12:58:03.804  5593  5609 D bt_bte_conf:   version             = 1436
,11-22 12:58:03.804  5593  5609 D bt_bte_conf:   clientExecutableURL = 
11-22 12:58:03.804  5593  5609 D bt_bte_conf:   serviceDescription  = 
11-22 12:58:03.805  5593  5609 D bt_bte_conf:   documentationURL    = 
,11-22 12:58:03.805  5593  5609 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 12:58:03.805  5593  5613 I bt_vendor: low_power_mode_cb
11-22 12:58:03.805  5593  5606 D bt_stack_manager: event_start_up_stack finished
,11-22 12:58:03.806  5593  5605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-22 12:58:03.807  5593  5605 D BluetoothAdapterProperties: Setting state to 15
11-22 12:58:03.807  5593  5605 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 12:58:03.808  5593  5605 I BluetoothAdapterState: Entering BleOnState
,11-22 12:58:03.814  5593  5605 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-22 12:58:03.814  5593  5605 D BluetoothAdapterProperties: Setting state to 11
11-22 12:58:03.814  5593  5605 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-22 12:58:03.824  5593  5593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f656dd
11-22 12:58:03.825  5593  5593 D HeadsetService: Received start request. Starting profile...
,11-22 12:58:03.828  5593  5593 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-22 12:58:03.829  5593  5593 D HeadsetStateMachine: make
11-22 12:58:03.837  5593  5605 I BluetoothAdapterState: Entering PendingCommandState
11-22 12:58:03.838  5593  5593 D HeadsetStateMachine: max_hf_connections = 1
11-22 12:58:03.839  5593  5593 I bt_bluedroid: get_profile_interface handsfree
11-22 12:58:03.839  5593  5609 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 12:58:03.839  5593  5609 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
11-22 12:58:03.846  5593  5593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f656dd
11-22 12:58:03.847  3469  3469 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 12:58:03.847  5593  5593 D A2dpService: Received start request. Starting profile...
11-22 12:58:03.848  5593  5593 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 12:58:03.848  5593  5593 I bt_bluedroid: get_profile_interface avrcp
11-22 12:58:03.854  5593  5593 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-22 12:58:03.854  5593  5593 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 12:58:03.854  5593  5593 D A2dpStateMachine: make
11-22 12:58:03.855  5593  5593 I bt_bluedroid: get_profile_interface a2dp
11-22 12:58:03.856  5593  5609 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-22 12:58:03.857  5593  5624 D A2dpStateMachine: Enter Disconnected: -2
11-22 12:58:03.858  5593  5593 I BluetoothHidServiceJni: classInitNative: succeeds
11-22 12:58:03.859  5593  5593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f656dd
11-22 12:58:03.860  5593  5593 D HidService: Received start request. Starting profile...
11-22 12:58:03.860  5593  5593 I bt_bluedroid: get_profile_interface hidhost
11-22 12:58:03.860  5593  5593 D HidService: setHidService(): set to: null
11-22 12:58:03.860  5593  5609 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d5256d
11-22 12:58:03.860  5593  5609 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 12:58:03.861  5576  5576 D BluetoothInputDevice: Proxy object connected
11-22 12:58:03.861  5593  5593 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 12:58:03.861  5576  5576 D HidProfile: Bluetooth service connected
11-22 12:58:03.862  5593  5593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f656dd
11-22 12:58:03.862  5593  5593 D HealthService: Received start request. Starting profile...
,11-22 12:58:03.864  5593  5593 I bt_bluedroid: get_profile_interface health
11-22 12:58:03.865  5593  5593 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-22 12:58:03.865  5593  5593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f656dd
,11-22 12:58:03.866  5576  5576 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 12:58:03.867  5593  5593 D PanService: Received start request. Starting profile...
11-22 12:58:03.867  5593  5593 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 12:58:03.867  5593  5593 I bt_bluedroid: get_profile_interface pan
11-22 12:58:03.867  5576  5576 D PanProfile: Bluetooth service connected
11-22 12:58:03.867  5593  5609 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-22 12:58:03.869  5593  5593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f656dd
,11-22 12:58:03.871  5593  5593 D BluetoothMapService: Received start request. Starting profile...
11-22 12:58:03.871  5593  5593 D BluetoothMapService: start()
11-22 12:58:03.871  5576  5576 D BluetoothMap: Proxy object connected
11-22 12:58:03.871  5576  5576 D MapProfile: Bluetooth service connected
11-22 12:58:03.871  5576  5576 D BluetoothMap: getConnectedDevices()
11-22 12:58:03.872  5576  5576 D BluetoothMap: Bluetooth is Not enabled
11-22 12:58:03.873  5593  5593 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-22 12:58:03.874  5593  5593 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-22 12:58:03.874  5593  5593 D BluetoothMapAppObserver: createReceiver()
,11-22 12:58:03.876  5593  5593 D BluetoothMapAppObserver: initObservers()
11-22 12:58:03.876  5593  5593 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-22 12:58:03.883  5593  5593 V SapService: SapBinder()
,11-22 12:58:03.883  5593  5593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f656dd
,11-22 12:58:03.883  5593  5593 D SapService: Received start request. Starting profile...
11-22 12:58:03.883  5593  5593 V SapService: start()
11-22 12:58:03.885  5593  5593 V BluetoothAdapterState: isTurningOff()=false
11-22 12:58:03.885  5593  5593 V BluetoothAdapterState: isTurningOn()=true
11-22 12:58:03.885  5593  5593 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:03.885  5593  5622 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 12:58:03.885  5593  5593 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:03.885  5593  5593 V BluetoothAdapterState: isTurningOff()=false
11-22 12:58:03.885  5593  5593 V BluetoothAdapterState: isTurningOn()=true
11-22 12:58:03.885  5593  5593 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:03.885  5593  5593 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isTurningOff()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isTurningOn()=true
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isTurningOff()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isTurningOn()=true
,11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isTurningOff()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isTurningOn()=true
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isTurningOff()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isTurningOn()=true
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:03.886  5593  5593 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:58:03.887  5593  5593 V BluetoothAdapterState: isTurningOff()=false
11-22 12:58:03.887  5593  5593 V BluetoothAdapterState: isTurningOn()=true
11-22 12:58:03.887  5593  5593 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:58:03.887  5593  5593 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 12:58:03.887  5593  5605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-22 12:58:03.887  5593  5605 D BluetoothAdapterProperties: ScanMode =  20
11-22 12:58:03.887  5593  5605 D BluetoothAdapterProperties: State =  11
11-22 12:58:03.888  5593  5605 D BluetoothAdapterProperties: Setting state to 12
11-22 12:58:03.888  5593  5605 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 12:58:03.888  3649  3667 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:58:03.889  5593  5609 D BluetoothAdapterProperties: Scan Mode:21
11-22 12:58:03.889  3025  3873 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 12:58:03.889  5593  5609 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 12:58:03.890  5593  5605 I BluetoothAdapterState: Entering OnState
,11-22 12:58:03.891  3025  3025 D BluetoothInputDevice: Proxy object connected
11-22 12:58:03.891  3025  3025 D HidProfile: Bluetooth service connected
11-22 12:58:03.892   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:58:03.892  3025  3872 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 12:58:03.894  3025  3025 D BluetoothMap: Proxy object connected
11-22 12:58:03.894  3025  3025 D MapProfile: Bluetooth service connected
11-22 12:58:03.894  3025  3025 D BluetoothMap: getConnectedDevices()
11-22 12:58:03.895  3025  3037 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:58:03.896   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 12:58:03.896  3025  3873 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 12:58:03.897   927   927 D BluetoothA2dp: Proxy object connected
,11-22 12:58:03.898  3025  3025 D BluetoothA2dp: Proxy object connected
,11-22 12:58:03.899  3025  3872 D BluetoothPan: onBluetoothStateChange on: true
11-22 12:58:03.901  5593  5593 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 12:58:03.901  5593  5593 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-22 12:58:03.903  5499  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:58:03.903  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:58:03.903  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:58:03.903  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:58:03.903  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:58:03.903  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:58:03.903  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:58:03.903  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:58:03.903  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 12:58:03.903  5593  5593 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:58:03.903  5576  5586 D BluetoothPan: onBluetoothStateChange on: true
,11-22 12:58:03.904  3025  3025 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 12:58:03.904  3025  3025 D PanProfile: Bluetooth service connected
11-22 12:58:03.904  5576  5587 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 12:58:03.905  5499  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 12:58:03.905  5576  5586 D BluetoothMap: onBluetoothStateChange: up=true
11-22 12:58:03.906  5576  5587 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 12:58:03.906   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:58:03.906  5499  5546 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-22 12:58:03.906  3025  3038 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 12:58:03.907   927  3044 D WifiService: setWifiEnabled: false pid=5499, uid=10077
11-22 12:58:03.907   927  3044 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:58:03.908   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-22 12:58:03.909   927  2844 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-22 12:58:03.909   927  2844 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-22 12:58:03.909   927  2844 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 12:58:03.909   927  2844 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 12:58:03.910   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-22 12:58:03.911  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:58:03.912  5593  5593 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:58:03.914  5593  5593 D ObexServerSockets: Succeed to create listening sockets 
11-22 12:58:03.914  5593  5593 D ObexServerSockets0: startAccept()
11-22 12:58:03.914  5593  5593 D ObexServerSockets0: prepareForNewConnect()
11-22 12:58:03.916  5593  5593 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 12:58:03.916  5593  5593 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-22 12:58:03.916  5593  5593 D BluetoothMapService: onReceive
11-22 12:58:03.916  5593  5632 D ObexServerSockets0: Accepting socket connection...
11-22 12:58:03.916  5593  5593 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 12:58:03.917  5593  5593 D BluetoothMapService: STATE_ON
11-22 12:58:03.917  5576  5576 D LocalBluetoothProfileManager: Adding local A2DP profile
11-22 12:58:03.919  5593  5633 D ObexServerSockets0: Accepting socket connection...
11-22 12:58:03.921  5593  5634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:58:03.922   927  5263 D DhcpClient: Clearing IP address
11-22 12:58:03.922  5593  5634 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-22 12:58:03.922  5593  5634 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-22 12:58:03.923   506   921 D CommandListener: Clearing all IP addresses on wlan0
11-22 12:58:03.925  5576  5576 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-22 12:58:03.929   506   921 D CommandListener: Setting iface cfg
,11-22 12:58:03.932  3469  5321 V NativeCrypto: Read error: ssl=0x7f83653a80: I/O error during system call, Connection timed out
,11-22 12:58:03.933  3469  5321 V NativeCrypto: SSL shutdown failed: ssl=0x7f83653a80: I/O error during system call, Broken pipe
11-22 12:58:03.933  5576  5576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 12:58:03.935   927   938 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-22 12:58:03.935   927  5261 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-22 12:58:03.937  5593  5593 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 12:58:03.937  5576  5576 D BluetoothA2dp: Proxy object connected
11-22 12:58:03.937  5593  5593 D ObexServerSockets0: prepareForNewConnect()
11-22 12:58:03.941  3469  3469 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 12:58:03.942  5576  5576 D DockEventReceiver: finishStartingService: stopping service
11-22 12:58:03.942   927  5264 D DhcpClient: Receive thread stopped
11-22 12:58:03.943   927  5261 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-22 12:58:03.943   927  2846 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-22 12:58:03.944   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-22 12:58:03.945   927  2846 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-22 12:58:03.946   927  2846 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 12:58:03.946   927  2846 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-22 12:58:03.950   927   927 D RttService: SCAN_AVAILABLE : 1
,11-22 12:58:03.950   532   532 E Parcel  : Reading a NULL string not supported here.
11-22 12:58:03.951   927  2953 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-22 12:58:03.951  5576  5576 D BluetoothPbap: Proxy object connected
11-22 12:58:03.952   927  2846 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-22 12:58:03.952  5576  5576 D PbapServerProfile: Bluetooth service connected
11-22 12:58:03.953  3623  3740 W QCNEJ   : |CORE| network lost: 100
,11-22 12:58:03.954  3623  3740 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-22 12:58:03.957  3025  3025 D BluetoothPbap: Proxy object connected
11-22 12:58:03.957  3025  3025 D PbapServerProfile: Bluetooth service connected
,11-22 12:58:03.964   927  2844 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-22 12:58:03.966  5593  5640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:58:03.977   927  2844 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 12:58:03.980  5593  5649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:58:03.981  5593  5649 I BtOppRfcommListener: Accept thread started.
,11-22 12:58:03.984   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 12:58:03.990  3649  4009 D BluetoothHeadset: Proxy object connected
,11-22 12:58:03.991  3025  3037 D BluetoothHeadset: Proxy object connected
11-22 12:58:03.991  3025  3025 D HeadsetProfile: Bluetooth service connected
11-22 12:58:03.991   927   927 D BluetoothHeadset: Proxy object connected
11-22 12:58:03.991   927   927 D BluetoothHeadset: Proxy object connected
11-22 12:58:03.991   927   927 D BluetoothHeadset: Proxy object connected
11-22 12:58:03.992   927   944 D BluetoothHeadset: Proxy object connected
,11-22 12:58:03.996  3025  3873 D BluetoothHeadset: Proxy object connected
,11-22 12:58:03.996  3025  3025 D HeadsetProfile: Bluetooth service connected
,11-22 12:58:04.004   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 12:58:04.004   506   921 D CommandListener: Clearing all IP addresses on wlan0
11-22 12:58:04.004   506   921 D TetherController: Setting IP forward enable = 0
,11-22 12:58:04.005   927  2846 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-22 12:58:04.005   927  2846 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 12:58:04.006   927   944 D BluetoothHeadset: Proxy object connected
,11-22 12:58:04.007   927  2844 D DhcpClient: doQuit
11-22 12:58:04.007   927  2844 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-22 12:58:04.008  3344  3344 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-22 12:58:04.008   927  5263 D DhcpClient: onQuitting
,11-22 12:58:04.009   927   944 D BluetoothHeadset: Proxy object connected
11-22 12:58:04.013  3833  3833 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-22 12:58:04.016   927   944 D Tethering: MasterInitialState.processMessage what=3
11-22 12:58:04.024  3850  3850 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 12:58:04.014  5148  5148 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1c71286 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-22 12:58:04.026  4937  4961 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 12:58:04.027  4937  4961 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 12:58:04.027  4937  4961 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 12:58:04.027  4937  4961 E SarControlService: no key has been found,reset the power
11-22 12:58:04.027  4937  4974 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-22 12:58:04.027  4937  4974 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 12:58:04.027  4937  4974 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 12:58:04.027  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 12:58:04.028  5576  5586 D BluetoothHeadset: Proxy object connected
11-22 12:58:04.029  5576  5576 D HeadsetProfile: Bluetooth service connected
11-22 12:58:04.028  4962  4962 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 12:58:04.032  4937  4974 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 12:58:04.032  4937  4974 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 12:58:04.032  4937  4974 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 12:58:04.033  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 12:58:04.033  4962  4962 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 12:58:04.036  3344  3344 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-22 12:58:04.037  4962  4976 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@429141c HexData = [00000000ea03000000000000ffffffff]
11-22 12:58:04.037  4962  4976 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:58:04.037  4962  4976 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-22 12:58:04.039  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:58:04.040  4937  4947 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 12:58:04.040  3850  3850 D SystemUpdateService: onCreate
11-22 12:58:04.042  3344  3344 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-22 12:58:04.045  3850  3850 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 12:58:04.051  4962  4976 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@429141c HexData = [00000000eb03000000000000ffffffff]
,11-22 12:58:04.052  4962  4976 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:58:04.052  4962  4976 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-22 12:58:04.052  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:58:04.052  4937  4948 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-22 12:58:04.056  3850  3850 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-22 12:58:04.059   506   921 E Netd    : netlink response contains error (No such file or directory)
11-22 12:58:04.059   506   921 D TetherController: Setting IP forward enable = 0
11-22 12:58:04.060   927  2846 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-22 12:58:04.060  3850  5660 I SystemUpdateService: active receiver: enabled
11-22 12:58:04.060   927  2846 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-22 12:58:04.062  3850  5290 I iu.UploadsManager: num queued entries: 0
11-22 12:58:04.063  3850  5290 I iu.UploadsManager: num updated entries: 0
,11-22 12:58:04.065  3850  3850 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 12:58:04.066  3850  3850 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 12:58:04.069  3850  5660 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 12:58:04.071  3850  5290 I iu.SyncManager: NEXT; no task
11-22 12:58:04.071  3344  3344 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-22 12:58:04.072  3850  5660 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-22 12:58:04.072  3850  5660 I SystemUpdateService: now status is 0 (complete)
11-22 12:58:04.072  3850  5660 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 12:58:04.072  3850  5660 I SystemUpdateService: file has been verified
11-22 12:58:04.072  3850  5660 I SystemUpdateService: OTA package size = 21989297
,11-22 12:58:04.078   927   938 I ActivityManager: Start proc 5665:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-22 12:58:04.078  3850  5660 I SystemUpdateService: showing system update notification
,11-22 12:58:04.090  3344  3344 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-22 12:58:04.090   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-22 12:58:04.092  3850  3850 D SystemUpdateService: onDestroy
,11-22 12:58:04.116  5665  5665 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-22 12:58:04.119  5665  5665 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 12:58:04.125  5665  5665 D SprintDMHelper: simOperator: 
,11-22 12:58:04.125  5665  5665 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 12:58:04.139  4892  5677 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 12:58:04.152   927  3460 I ActivityManager: Start proc 5678:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
11-22 12:58:04.153   927  3460 I ActivityManager: Killing 5148:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-22 12:58:04.192  5678  5678 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-22 12:58:04.193   927  2844 D wifi    : In wifi stop Hal
,11-22 12:58:04.193   927  2844 D wifi    : halHandle = 0x7f81f5de00, mVM = 0x7f9e58d140, mCls = 0x100a02
11-22 12:58:04.194   927  3343 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-22 12:58:04.194   927  3343 D WifiHAL : Got a signal to exit!!!
11-22 12:58:04.194   927  3343 I WifiHAL : Exit wifi_event_loop
,11-22 12:58:04.194   927  2844 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-22 12:58:04.194   927  2844 E WifiHAL : Event processing terminated
,11-22 12:58:04.194   927  2844 D wifi    : In wifi cleaned up handler
11-22 12:58:04.194  4892  4892 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 12:58:04.194   927  2844 I WifiHAL : Internal cleanup completed
11-22 12:58:04.196  3988  4120 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 12:58:04.205   927  5690 I ActivityManager: Killing 3744:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-22 12:58:04.216   927  3343 D wifi    : set interface wlan0 flags (DOWN)
,11-22 12:58:04.216   927  2844 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 12:58:04.418  5499  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:58:04.418  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:58:04.418  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:58:04.418  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 12:58:04.418  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:58:04.418  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:58:04.418  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:58:04.418  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:58:04.418  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 12:58:04.423   927   944 D Tethering: InitialState.processMessage what=4
,11-22 12:58:04.426  5499  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 12:58:04.429   927  3730 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-22 12:58:04.429   927  3730 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:58:04.432   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 12:58:04.434   506   921 D SoftapController: Softap fwReload - Ok
11-22 12:58:04.435  5499  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:58:04.439   506   921 D CommandListener: Setting iface cfg
,11-22 12:58:04.440   506   921 D CommandListener: Trying to bring down wlan0
,11-22 12:58:04.441   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-22 12:58:04.444   927  2844 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 12:58:04.934   927   938 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-22 12:58:04.940   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:58:05.045   927  2844 D wifi    : set interface wlan0 flags (UP)
11-22 12:58:05.045   927  2844 I WifiHAL : Initializing wifi
11-22 12:58:05.045   927  2844 I WifiHAL : Creating socket
11-22 12:58:05.049   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-22 12:58:05.050   927  2844 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-22 12:58:05.050   927  2844 D wifi    : Did set static halHandle = 0x7f81f5de00
11-22 12:58:05.050   927  2844 D wifi    : halHandle = 0x7f81f5de00, mVM = 0x7f9e58d140, mCls = 0x10187a
11-22 12:58:05.051   927  2844 D wifi    : array field set
11-22 12:58:05.051   927  2844 I WifiNative-HAL: interface[0] = wlan0
,11-22 12:58:05.053   927  5695 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547641220608
11-22 12:58:05.053   927  5695 D wifi    : waitForHalEvents called, vm = 0x7f9e58d140, obj = 0x10187a, env = 0x7f87447b80
,11-22 12:58:05.058   927  2844 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 12:58:05.060   927  2844 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-22 12:58:05.123   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:05.124  5696  5696 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 12:58:05.192  5696  5696 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 12:58:05.272  5696  5696 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 12:58:05.272  5696  5696 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 12:58:05.447   927  3483 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-22 12:58:05.447   927  3483 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:58:05.951   927  3731 D WifiService: setWifiEnabled: true pid=5499, uid=10077
,11-22 12:58:05.951   927  3731 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:58:06.074   927  2844 D WifiConfigStore: Loading config and enabling all networks 
,11-22 12:58:06.118   927  2844 D WifiConfigStore: loaded 0 passpoint configs
,11-22 12:58:06.119   927  2844 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-22 12:58:06.120   927  2844 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-22 12:58:06.121   927  2844 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-22 12:58:06.122   927  2844 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-22 12:58:06.123   927  2844 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-22 12:58:06.124   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:06.124   927  2844 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-22 12:58:06.125   927  2844 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-22 12:58:06.125   927  2844 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-22 12:58:06.125   927  2844 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-22 12:58:06.125   927  2844 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-22 12:58:06.125   927  2844 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 12:58:06.125   927  2844 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-22 12:58:06.130   927  2844 D WifiNative-HAL: Setting external_sim to 1
11-22 12:58:06.131   927  2844 D wifi    : setting dfs flag to true, 0x7f86d3ea40
11-22 12:58:06.131  4892  4892 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 12:58:06.131   927  2844 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 12:58:06.132   927  2844 D wifi    : setting scan oui 0x7f86d3ea40
11-22 12:58:06.132   927  2844 D WifiHAL : Sending mac address OUI
,11-22 12:58:06.137   927  2844 E native  : do suspend false
,11-22 12:58:06.147   927  2844 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-22 12:58:06.147   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-22 12:58:06.147   927   927 D RttService: SCAN_AVAILABLE : 3
,11-22 12:58:06.147   927  2953 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-22 12:58:06.149   506   921 D CommandListener: Setting iface cfg
,11-22 12:58:06.153   927  2843 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-22 12:58:06.153   927  2843 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 12:58:06.165   927  2843 D WifiNative-HAL: p2pGetDeviceAddress
,11-22 12:58:06.165   927  2843 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-22 12:58:06.170   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=189217 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-22 12:58:06.462  5499  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:58:06.462  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:58:06.462  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:58:06.462  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:58:06.462  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:58:06.462  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:58:06.462  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:58:06.462  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:58:06.462  5499  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 12:58:06.467  5499  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 12:58:06.470  5499  5546 D BluetoothAdapter: enable(): BT is already enabled..!
,11-22 12:58:06.471   927  3054 D WifiService: setWifiEnabled: true pid=5499, uid=10077
11-22 12:58:06.471   927  3054 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:58:06.472  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 12:58:06.473  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:58:06.473  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:58:06.473  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa9e39c removed from the list
11-22 12:58:06.473  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:58:06.473  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@557a1a5 removed from the list
11-22 12:58:06.473  5499  5546 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:58:06.476  5499  5546 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-22 12:58:06.477  5499  5546 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-22 12:58:06.479  5499  5546 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-22 12:58:06.480  5499  5546 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
11-22 12:58:06.482  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-22 12:58:06.483  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-22 12:58:06.484  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-22 12:58:06.484  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-22 12:58:06.486  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
11-22 12:58:06.489  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-22 12:58:06.489  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ae2de20 Bundle[{}]
11-22 12:58:06.490  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-22 12:58:06.490  5499  5546 I io.jxcore.node.LifeCycleMonitor: start: OK
11-22 12:58:06.490  5499  5546 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-22 12:58:06.491  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-22 12:58:06.491  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-22 12:58:06.491  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-22 12:58:06.492  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-22 12:58:06.492  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-22 12:58:06.492  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-22 12:58:06.493  5499  5546 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-22 12:58:06.493  5499  5546 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-22 12:58:06.494  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-22 12:58:06.495  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-22 12:58:06.496  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-22 12:58:06.497  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-22 12:58:06.498  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-22 12:58:06.499  5499  5546 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-22 12:58:06.500  5499  5546 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-22 12:58:06.502  5499  5546 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-22 12:58:07.125   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:07.504  5499  5546 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-22 12:58:07.505  5499  5546 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-22 12:58:07.506  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-22 12:58:07.507  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-22 12:58:07.508  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-22 12:58:07.508  5499  5546 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,11-22 12:58:07.509  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-22 12:58:07.509  5499  5546 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-22 12:58:07.510  5499  5546 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
,11-22 12:58:07.510  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-22 12:58:07.511  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-22 12:58:07.512  5499  5546 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-22 12:58:07.513  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:58:07.513  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a52b added. We now have 3 listener(s)
,11-22 12:58:07.514  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 12:58:07.514  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:58:07.515  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:58:07.515  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:58:07.515  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63f9d88 added. We now have 3 listener(s)
11-22 12:58:07.515  5499  5546 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:58:07.516  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 12:58:07.521  5499  5546 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-22 12:58:07.521  5499  5546 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-22 12:58:07.521  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-22 12:58:07.521  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-22 12:58:07.522  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.522  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:07.522  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.522  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-22 12:58:07.522  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-22 12:58:07.522  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-22 12:58:07.522  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:58:07.522  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 12:58:07.524  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-22 12:58:07.525  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-22 12:58:07.525  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-22 12:58:07.525  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-22 12:58:07.525  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 12:58:07.525  5499  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-22 12:58:07.525  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-22 12:58:07.525  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-22 12:58:07.526  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:58:07.526  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 12:58:07.526  5499  5700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:58:07.529  5499  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-22 12:58:07.524  5629  5629 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33068]" dev="sockfs" ino=33068 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:58:07.524  5629  5629 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33068]" dev="sockfs" ino=33068 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:58:07.529  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 12:58:07.529  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-22 12:58:07.529  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 12:58:07.533  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:07.534  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 12:58:07.534  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 12:58:07.534  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:58:07.535  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-22 12:58:07.537  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:07.537  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.537  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-22 12:58:07.537  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-22 12:58:07.537  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 12:58:07.538  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
,11-22 12:58:07.538  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:58:07.538  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:58:07.538  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.538  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-22 12:58:07.538  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-22 12:58:07.538  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.539  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.539  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:07.540  5499  5546 D BluetoothAdapter: STATE_ON
,11-22 12:58:07.543  5593  5631 D BtGatt.GattService: registerClient() - UUID=89dddae6-195e-4679-8004-263874b0a6cf
,11-22 12:58:07.544  5593  5609 D BtGatt.GattService: onClientRegistered() - UUID=89dddae6-195e-4679-8004-263874b0a6cf, clientIf=5
,11-22 12:58:07.545  5499  5509 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-22 12:58:07.547  5593  5611 D BtGatt.AdvertiseManager: message : 0
,11-22 12:58:07.548  5593  5611 D BtGatt.AdvertiseManager: starting multi advertising
,11-22 12:58:07.558  5593  5609 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-22 12:58:07.563  5593  5609 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-22 12:58:07.563  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:07.564  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.564  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-22 12:58:07.564  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.564  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.564  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.564  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.564  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.564  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 12:58:07.565  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-22 12:58:07.565  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.566  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.567  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.567  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:07.567  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-22 12:58:07.567  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-22 12:58:07.567  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-22 12:58:07.567  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-22 12:58:07.567  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-22 12:58:07.567  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-22 12:58:07.567  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:58:07.567  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:58:07.567  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-22 12:58:07.567  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:58:07.567  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:58:07.568  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-22 12:58:07.568  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-22 12:58:07.568  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:58:07.570  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:58:07.570  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-22 12:58:07.570  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:58:07.570  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 12:58:07.570  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:58:07.570  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-22 12:58:08.071  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-22 12:58:08.071  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-22 12:58:08.072  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 12:58:08.126   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:09.127   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:09.221  5696  5696 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:58:09.223  5696  5696 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-22 12:58:09.224  5696  5696 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:58:09.259   927  2844 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 12:58:09.260   927  2844 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-22 12:58:09.260   927  2844 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 12:58:09.271   927  2844 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 12:58:09.306   927  2844 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 12:58:09.312  5696  5696 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 12:58:09.736  5696  5696 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 12:58:09.776  5696  5696 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-22 12:58:09.777  5696  5696 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 12:58:09.790   927  2844 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-22 12:58:09.791   927  2844 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 12:58:09.791   927  2846 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 12:58:09.813   927  2844 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 12:58:09.827   506   921 D CommandListener: Setting iface cfg
,11-22 12:58:09.835   927  2844 D WifiStateMachine: Start Dhcp Watchdog 2
,11-22 12:58:09.842   927  5705 D DhcpClient: Receive thread started
,11-22 12:58:09.848   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:58:09.848   927  2844 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-22 12:58:09.848   927  2846 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-22 12:58:09.931   927  2844 E native  : do suspend false
,11-22 12:58:09.942   927  5704 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 12:58:09.955   927  5705 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172647, domain null
,11-22 12:58:09.955   927  5704 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172647 seconds
,11-22 12:58:09.958   927  5704 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-22 12:58:09.969   927  5705 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 12:58:09.970   927  5704 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-22 12:58:09.973   506   921 D CommandListener: Setting iface cfg
,11-22 12:58:09.977   927  2844 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-22 12:58:09.981   927  5704 D DhcpClient: Scheduling renewal in 86399s
,11-22 12:58:09.993   927  2844 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-22 12:58:09.995   927  2844 D WifiConfigStore: No blacklist allowed without epno enabled
11-22 12:58:09.996   927  2846 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-22 12:58:09.997   927  2846 D ConnectivityService: Adding iface wlan0 to network 101
11-22 12:58:10.004   927  2844 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 12:58:10.057   927  2846 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-22 12:58:10.057   927  2846 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-22 12:58:10.059   927  2846 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-22 12:58:10.061   927  2846 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-22 12:58:10.064   927  2846 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-22 12:58:10.071   927  2846 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:58:10.075   927  2846 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-22 12:58:10.076   927  2846 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-22 12:58:10.076   927  2846 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-22 12:58:10.076   927  2844 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 12:58:10.076   927  2846 D ConnectivityService:    accepting network in place of null
11-22 12:58:10.076   927  2844 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 12:58:10.077   927  2846 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 12:58:10.092   927  5703 D NetlinkSocketObserver: NeighborEvent{elapsedMs=193139, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 12:58:10.100   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 12:58:10.122   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 12:58:10.125   927  2846 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-22 12:58:10.125   927  2846 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 12:58:10.125  3623  3740 W QCNEJ   : |CORE| network available: 101
11-22 12:58:10.126   927  2846 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-22 12:58:10.127  3623  3740 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-22 12:58:10.127   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
11-22 12:58:10.128   927   944 D Tethering: MasterInitialState.processMessage what=3
11-22 12:58:10.128  3623  3740 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 12:58:10.129  3623  3740 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-22 12:58:10.139  4937  4961 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-22 12:58:10.139  4937  4961 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 12:58:10.139  4937  4961 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 12:58:10.139  4937  4961 E SarControlService: no key has been found,reset the power
11-22 12:58:10.139  4937  4974 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 12:58:10.140  4937  4974 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 12:58:10.140  4937  4974 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-22 12:58:10.141  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 12:58:10.141  4962  4962 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 12:58:10.142  4937  4974 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 12:58:10.143  4937  4974 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-22 12:58:10.143  3833  3833 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-22 12:58:10.145  4937  4974 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-22 12:58:10.146  3850  3850 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 12:58:10.149  4962  4976 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@429141c HexData = [00000000ec03000000000000ffffffff]
11-22 12:58:10.149  4962  4976 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:58:10.149  4962  4976 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-22 12:58:10.150  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:58:10.150  4937  4947 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 12:58:10.151  3850  3850 D SystemUpdateService: onCreate
11-22 12:58:10.152  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 12:58:10.152  4962  4962 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-22 12:58:10.156  4962  4976 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@429141c HexData = [00000000ed03000000000000ffffffff]
11-22 12:58:10.157  4962  4976 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:58:10.157  4962  4976 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-22 12:58:10.157  4962  4962 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:58:10.157  4937  4948 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 12:58:10.158  3850  3850 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 12:58:10.168  3850  3850 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-22 12:58:10.174  3850  5290 I iu.UploadsManager: num queued entries: 0
,11-22 12:58:10.174  3850  5290 I iu.UploadsManager: num updated entries: 0
11-22 12:58:10.175  3850  5290 I iu.SyncManager: NEXT; no task
,11-22 12:58:10.178  3850  5715 I SystemUpdateService: active receiver: enabled
,11-22 12:58:10.179   927  5702 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.46,2a00:1450:4001:81b::200e
,11-22 12:58:10.180  3850  3850 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 12:58:10.182  3850  3850 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 12:58:10.184  5665  5665 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 12:58:10.189  5665  5665 D SprintDMHelper: simOperator: 
11-22 12:58:10.189  5665  5665 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 12:58:10.211  3850  5715 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 12:58:10.226  3850  5715 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-22 12:58:10.226  3850  5715 I SystemUpdateService: now status is 0 (complete)
11-22 12:58:10.226  3850  5715 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 12:58:10.226  3850  5715 I SystemUpdateService: file has been verified
11-22 12:58:10.226  3850  5715 I SystemUpdateService: OTA package size = 21989297
,11-22 12:58:10.230   927  5702 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 11:58:10 GMT], X-Android-Received-Millis=[1479815890229], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479815890204]}
,11-22 12:58:10.231   927  2846 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 12:58:10.231   927  2846 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-22 12:58:10.231   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:58:10.232   927  2846 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-22 12:58:10.235  3850  5715 I SystemUpdateService: showing system update notification
,11-22 12:58:10.241   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 12:58:10.243  3850  3850 D SystemUpdateService: onDestroy
,11-22 12:58:10.298  4892  5721 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 12:58:11.069  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-22 12:58:11.069  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 12:58:11.070  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-22 12:58:11.070  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-22 12:58:11.070  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-22 12:58:11.070  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:58:11.070  5499  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-22 12:58:11.071  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 12:58:11.071  5499  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-22 12:58:11.071  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 12:58:11.071  5499  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-22 12:58:11.071  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 12:58:11.071  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-22 12:58:11.071  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:58:11.072  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-22 12:58:11.072  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:58:11.072  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.072  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:11.072  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.073  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.076  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:58:11.076  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-22 12:58:11.078  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:58:11.078  5499  5546 D BluetoothLeScanner: could not find callback wrapper
11-22 12:58:11.078  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:58:11.078  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:11.079  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.079  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.079  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-22 12:58:11.079  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:11.081  5593  5611 D BtGatt.AdvertiseManager: message : 1
,11-22 12:58:11.082  5593  5611 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-22 12:58:11.094  5593  5609 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-22 12:58:11.095  5593  5609 D BtGatt.GattService: Client app is not null!
,11-22 12:58:11.096  5593  5631 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 12:58:11.097  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-22 12:58:11.097  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:11.098  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-22 12:58:11.098  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.098  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.098  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:11.098  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 12:58:11.098  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 12:58:11.099  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 12:58:11.100  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:11.102  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.103  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 12:58:11.104  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:11.105  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.106  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:58:11.106  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-22 12:58:11.106  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-22 12:58:11.107  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:58:11.107  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:58:11.107  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:58:11.107  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:58:11.107  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.107  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:58:11.107  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-22 12:58:11.108  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.108  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.108  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-22 12:58:11.108  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 12:58:11.110  5499  5546 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-22 12:58:11.110  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:58:11.110  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.110  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.111  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.111  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.111  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:58:11.111  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 12:58:11.111  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 12:58:11.111  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 12:58:11.111  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:58:11.111  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 12:58:11.114  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 12:58:11.117  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 12:58:11.118  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:58:11.118  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 12:58:11.122  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.122  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 12:58:11.123  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 12:58:11.124  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-22 12:58:11.124  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-22 12:58:11.126   927  2846 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-22 12:58:11.127  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-22 12:58:11.131  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-22 12:58:11.132  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.132  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 12:58:11.132  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 12:58:11.132  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 12:58:11.133  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 12:58:11.133  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:11.134  5499  5546 D BluetoothAdapter: STATE_ON
,11-22 12:58:11.138  5593  5629 D BtGatt.GattService: registerClient() - UUID=68998acb-49d4-420d-8c8e-0edab820d2d0
11-22 12:58:11.138  5593  5609 D BtGatt.GattService: onClientRegistered() - UUID=68998acb-49d4-420d-8c8e-0edab820d2d0, clientIf=5
,11-22 12:58:11.139  5499  5510 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-22 12:58:11.140  5593  5604 D BtGatt.GattService: start scan with filters
,11-22 12:58:11.145  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 12:58:11.145  5593  5612 D BtGatt.ScanManager: handling starting scan
,11-22 12:58:11.146  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:11.146  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 12:58:11.147  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.147  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 12:58:11.148  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:58:11.148  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.148  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 12:58:11.148  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:58:11.148  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.148  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-22 12:58:11.148  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-22 12:58:11.149  5593  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f656dd
,11-22 12:58:11.149  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-22 12:58:11.152  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.155  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.155  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:58:11.155  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.156  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:11.156  5593  5609 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 12:58:11.156  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:58:11.156  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.156  5593  5612 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 12:58:11.159  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.159  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.159  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 12:58:11.159  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:58:11.159  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 12:58:11.163  5593  5609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-22 12:58:11.163  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:58:11.163  5593  5612 D BtGatt.ScanManager: Starting BLE batch scan
11-22 12:58:11.163  5593  5612 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 12:58:11.173  5593  5609 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-22 12:58:11.173  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:58:11.179  5593  5609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-22 12:58:11.179  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:58:11.660  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-22 12:58:11.661  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:58:11.661  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 12:58:12.870   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:58:14.158  5499  5546 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
11-22 12:58:14.159  5499  5546 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-22 12:58:14.159  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-22 12:58:14.160  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:14.160  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.160  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:14.161  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-22 12:58:14.161  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.161  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.161  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 12:58:14.162  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-22 12:58:14.162  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.162  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.163  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:14.168  5499  5546 D BluetoothAdapter: STATE_ON
,11-22 12:58:14.169  5593  5604 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 12:58:14.170  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-22 12:58:14.171  5593  5612 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:58:14.172  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:58:14.174  5593  5631 D BtGatt.GattService: stopScan() - queue size =1
,11-22 12:58:14.175  5593  5629 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 12:58:14.176  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:58:14.177  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.177  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 12:58:14.177  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.177  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:58:14.177  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.177  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.177  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 12:58:14.177  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 12:58:14.178  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 12:58:14.178  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 12:58:14.178  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:14.179  5499  5546 D BluetoothAdapter: STATE_ON
,11-22 12:58:14.182  5593  5593 D BtGatt.ScanManager: awakened up at time 197229
11-22 12:58:14.185  5593  5631 D BtGatt.GattService: registerClient() - UUID=70dbe298-0d6f-46dc-9829-b9ed0564e056
11-22 12:58:14.186  5593  5609 D BtGatt.GattService: onClientRegistered() - UUID=70dbe298-0d6f-46dc-9829-b9ed0564e056, clientIf=5
11-22 12:58:14.187  5499  5510 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-22 12:58:14.188  5593  5629 D BtGatt.GattService: start scan with filters
,11-22 12:58:14.194  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 12:58:14.194  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.194  5593  5609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-22 12:58:14.194  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-22 12:58:14.194  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:58:14.194  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.194  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.194  5593  5609 D BtGatt.GattService: current time is 197241807810
11-22 12:58:14.195  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-22 12:58:14.195  5499  5546 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-22 12:58:14.195  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-22 12:58:14.195  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 12:58:14.195  5593  5609 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-22 12:58:14.195  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-22 12:58:14.196  5593  5609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 12:58:14.196  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-22 12:58:14.196  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-22 12:58:14.196  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-22 12:58:14.196  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 12:58:14.196  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:58:14.196  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-22 12:58:14.196  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.196  5499  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-22 12:58:14.196  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 12:58:14.197  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 12:58:14.197  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-22 12:58:14.197  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.197  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-22 12:58:14.197  5499  5729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:58:14.198  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 12:58:14.198  5499  5546 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:58:14.194  5631  5631 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33839]" dev="sockfs" ino=33839 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:58:14.194  5631  5631 W Binder_4: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33839]" dev="sockfs" ino=33839 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:58:14.199  5593  5609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-22 12:58:14.200  5499  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-22 12:58:14.206  5593  5609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 12:58:14.206  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:58:14.206  5593  5612 D BtGatt.ScanManager: stopping BLe Batch
11-22 12:58:14.208  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.208  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:14.208  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.208  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-22 12:58:14.208  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-22 12:58:14.208  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 12:58:14.208  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-22 12:58:14.208  5499  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:58:14.209  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-22 12:58:14.209  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.209  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-22 12:58:14.209  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-22 12:58:14.209  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.209  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.209  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:14.211  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:58:14.211  5593  5609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 12:58:14.211  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:58:14.211  5593  5612 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 12:58:14.217  5593  5629 D BtGatt.GattService: registerClient() - UUID=6e3fd17e-68f7-485e-ac53-adc07f1a3feb
,11-22 12:58:14.217  5593  5609 D BtGatt.GattService: onClientRegistered() - UUID=6e3fd17e-68f7-485e-ac53-adc07f1a3feb, clientIf=6
11-22 12:58:14.217  5499  5509 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-22 12:58:14.218  5593  5609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 12:58:14.218  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:58:14.218  5593  5611 D BtGatt.AdvertiseManager: message : 0
,11-22 12:58:14.220  5593  5612 D BtGatt.ScanManager: handling starting scan
,11-22 12:58:14.221  5593  5611 D BtGatt.AdvertiseManager: starting multi advertising
,11-22 12:58:14.226  5593  5609 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-22 12:58:14.226  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:58:14.226  5593  5612 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 12:58:14.233  5593  5609 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-22 12:58:14.237  5593  5609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-22 12:58:14.237  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:58:14.237  5593  5612 D BtGatt.ScanManager: Starting BLE batch scan
11-22 12:58:14.237  5593  5612 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 12:58:14.241  5593  5609 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-22 12:58:14.242  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:14.242  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.242  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-22 12:58:14.242  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.242  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.242  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.242  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.242  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.242  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:14.242  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.242  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.242  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-22 12:58:14.242  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-22 12:58:14.243  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-22 12:58:14.244  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-22 12:58:14.244  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.246  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.246  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.246  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:14.246  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-22 12:58:14.246  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.246  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-22 12:58:14.246  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-22 12:58:14.246  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.247  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.247  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:58:14.247  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.247  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-22 12:58:14.247  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 12:58:14.247  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.247  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.247  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-22 12:58:14.247  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 12:58:14.249  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-22 12:58:14.250  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-22 12:58:14.250  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.250  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.250  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:58:14.250  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-22 12:58:14.251  5593  5609 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 12:58:14.251  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:58:14.255  5593  5609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-22 12:58:14.255  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:58:14.751  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
11-22 12:58:14.751  5499  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-22 12:58:14.751  5499  5499 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 12:58:15.901   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:58:16.926   927  2844 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,11-22 12:58:17.250  5499  5546 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-22 12:58:17.250  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:58:17.250  5499  5546 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-22 12:58:17.251  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-22 12:58:17.251  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-22 12:58:17.251  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:58:17.251  5499  5729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-22 12:58:17.251  5499  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-22 12:58:17.251  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 12:58:17.252  5499  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-22 12:58:17.252  5499  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-22 12:58:17.252  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-22 12:58:17.252  5499  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-22 12:58:17.252  5499  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a52b removed from the list
11-22 12:58:17.252  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-22 12:58:17.252  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:58:17.253  5499  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:58:17.253  5499  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:58:17.253  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-22 12:58:17.253  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:58:17.254  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.254  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:17.254  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.254  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 12:58:17.255  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.256  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:58:17.257  5593  5604 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 12:58:17.257  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-22 12:58:17.259  5499  5546 D BluetoothAdapter: STATE_ON
11-22 12:58:17.259  5593  5612 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:58:17.260  5593  5631 D BtGatt.GattService: stopScan() - queue size =1
11-22 12:58:17.262  5593  5629 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 12:58:17.263  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:58:17.263  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.263  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 12:58:17.264  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.264  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.264  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.264  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-22 12:58:17.264  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.264  5593  5593 D BtGatt.ScanManager: awakened up at time 200311
,11-22 12:58:17.266  5593  5611 D BtGatt.AdvertiseManager: message : 1
11-22 12:58:17.266  5593  5611 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-22 12:58:17.277  5593  5609 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-22 12:58:17.277  5593  5609 D BtGatt.GattService: Client app is not null!
,11-22 12:58:17.278  5593  5604 D BtGatt.GattService: unregisterClient() - clientIf=6
11-22 12:58:17.278  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-22 12:58:17.278  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.278  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-22 12:58:17.278  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.279  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.279  5499  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.279  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-22 12:58:17.279  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 12:58:17.279  5499  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 12:58:17.280  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:17.284  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.284  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:58:17.284  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:58:17.284  5499  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:58:17.284  5499  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63f9d88 removed from the list
,11-22 12:58:17.284  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:58:17.284  5499  5546 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:58:17.284  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:58:17.285  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:58:17.285  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:58:17.285  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:58:17.285  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-22 12:58:17.285  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:58:17.285  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:58:17.285  5499  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-22 12:58:17.285  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:58:17.286  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-22 12:58:17.287  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-22 12:58:17.287  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-22 12:58:17.287  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-22 12:58:17.287  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:58:17.287  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-22 12:58:17.287  5499  5546 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 12:58:17.288  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-22 12:58:17.289  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-22 12:58:17.289  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:58:17.289  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:58:17.289  5499  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:58:17.290  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Cur,rent thread: Thread[main,5,main], id: 1
11-22 12:58:17.290  5499  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:58:17.290  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:58:17.290  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:58:17.290  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:58:17.290  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:58:17.290  5499  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:58:17.290  5499  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:58:17.289  5593  5609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-22 12:58:17.290  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:58:17.290  5593  5609 D BtGatt.GattService: current time is 200337718579
,11-22 12:58:17.290  5593  5609 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -79, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 12:58:17.291  5593  5609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-22 12:58:17.291  5593  5609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 12:58:17.291  5593  5609 E BtGatt.ContextMap: Context not found for ID 5
,11-22 12:58:17.293  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-22 12:58:17.294  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-22 12:58:17.295  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-22 12:58:17.296  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-22 12:58:17.297  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,11-22 12:58:17.298  5499  5546 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-22 12:58:17.299  5593  5609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 12:58:17.300  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:58:17.300  5593  5612 D BtGatt.ScanManager: stopping BLe Batch
,11-22 12:58:17.304  5593  5609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 12:58:17.305  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:58:17.305  5593  5612 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 12:58:17.310  5593  5609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 12:58:17.311  5593  5609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:58:17.790  5499  5499 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 12:58:18.077   927  2846 D ConnectivityService: handlePromptUnvalidated 101
,11-22 12:58:19.303  5499  5546 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-22 12:58:19.449  5499  5731 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 12:58:19.449  5499  5731 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:58:20.249  5499  5731 W !!      : call onHalfStreamCopied
,11-22 12:58:20.249  5499  5731 I testCopyDataAndClose: closing input stream
,11-22 12:58:21.025  5499  5731 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 12:58:21.025  5499  5731 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:58:21.025  5499  5731 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 12:58:21.025  5499  5731 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 12:58:21.025  5499  5731 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 12:58:21.026  5499  5731 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 12:58:21.026  5499  5731 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-22 12:58:21.026  5499  5731 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-22 12:58:21.026  5499  5731 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-22 12:58:21.026  5499  5731 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 12:58:21.026  5499  5731 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 12:58:21.164   927  2844 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,11-22 12:58:25.222  5499  5546 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-22 12:58:25.303  5499  5732 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 12:58:25.303  5499  5732 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:58:26.954  5499  5732 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 194, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 12:58:26.954  5499  5732 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 12:58:26.955  5499  5732 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 12:58:26.955  5499  5732 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 12:58:26.955  5499  5732 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 12:58:26.955  5499  5732 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 12:58:26.955  5499  5732 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 12:58:26.955  5499  5732 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 12:58:26.955  5499  5732 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 12:58:26.955  5499  5732 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 12:58:26.955  5499  5732 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 12:58:27.988   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:58:31.016   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:58:31.220  5499  5546 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-22 12:58:31.222  5499  5733 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:58:31.222  5499  5733 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:58:31.223  5499  5733 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 196, thread name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:58:31.223  5499  5733 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 12:58:31.223  5499  5733 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 12:58:31.223  5499  5733 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:58:31.223  5499  5733 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 12:58:31.223  5499  5733 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-22 12:58:31.223  5499  5733 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 12:58:31.224  5499  5733 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 12:58:31.224  5499  5733 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-22 12:58:31.224  5499  5733 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:58:31.224  5499  5733 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-22 12:58:31.225  5499  5546 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-22 12:58:31.226  5499  5546 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-22 12:58:31.227  5499  5546 I StreamCopyingThreadTest: Starting test: testRunWithException
11-22 12:58:31.229  5499  5734 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:58:31.229  5499  5734 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:58:31.229  5499  5734 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 200, thread name: My test thread name): Test exception.
11-22 12:58:31.230  5499  5734 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:58:31.230  5499  5734 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-22 12:58:31.230  5499  5734 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-22 12:58:31.230  5499  5734 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:58:31.230  5499  5734 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-22 12:58:31.235  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG UnitTest_app: 'Running unit tests'
11-22 12:58:31.235  5499  5546 I jxcore-log: 
11-22 12:58:31.235  5499  5546 I jxcore-log: *Native tests were executed*
11-22 12:58:31.235  5499  5546 I jxcore-log: 
11-22 12:58:31.235  5499  5546 I jxcore-log: Total number of executed tests:  81
11-22 12:58:31.235  5499  5546 I jxcore-log: 
,11-22 12:58:31.235  5499  5546 I jxcore-log: Number of passed tests:  79
11-22 12:58:31.235  5499  5546 I jxcore-log: 
11-22 12:58:31.235  5499  5546 I jxcore-log: Number of failed tests:  0
11-22 12:58:31.235  5499  5546 I jxcore-log: 
11-22 12:58:31.236  5499  5546 I jxcore-log: Number of ignored tests:  2
11-22 12:58:31.236  5499  5546 I jxcore-log: 
11-22 12:58:31.236  5499  5546 I jxcore-log: Total duration:  35778
11-22 12:58:31.236  5499  5546 I jxcore-log: 
,11-22 12:58:31.237  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-22 12:58:31.237  5499  5546 I jxcore-log: 
11-22 12:58:31.240  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:58:31.240  5499  5546 I jxcore-log: 
11-22 12:58:31.240  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-22 12:58:31.240  5499  5546 I jxcore-log: 
11-22 12:58:31.241  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:58:31.241  5499  5546 I jxcore-log: 
,11-22 12:58:31.242  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-22 12:58:31.242  5499  5546 I jxcore-log: 
11-22 12:58:31.243  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-22 12:58:31.243  5499  5546 I jxcore-log: 
,11-22 12:58:31.243  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 12:58:31.243  5499  5546 I jxcore-log: 
11-22 12:58:31.243  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:58:31.243  5499  5546 I jxcore-log: 
11-22 12:58:31.244  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-22 12:58:31.244  5499  5546 I jxcore-log: 
,11-22 12:58:31.244  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 12:58:31.244  5499  5546 I jxcore-log: 
11-22 12:58:31.244  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:58:31.244  5499  5546 I jxcore-log: 
11-22 12:58:31.245  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-22 12:58:31.245  5499  5546 I jxcore-log: 
11-22 12:58:31.245  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 12:58:31.245  5499  5546 I jxcore-log: 
11-22 12:58:31.245  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:58:31.245  5499  5546 I jxcore-log: 
11-22 12:58:31.245  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 12:58:31.245  5499  5546 I jxcore-log: 
,11-22 12:58:31.245  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:58:31.245  5499  5546 I jxcore-log: 
11-22 12:58:31.245  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:58:31.245  5499  5546 I jxcore-log: 
11-22 12:58:31.246  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-22 12:58:31.246  5499  5546 I jxcore-log: 
11-22 12:58:31.246  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 12:58:31.246  5499  5546 I jxcore-log: 
11-22 12:58:31.246  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:58:31.246  5499  5546 I jxcore-log: 
,11-22 12:58:31.246  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:58:31.246  5499  5546 I jxcore-log: 
11-22 12:58:31.247  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-22 12:58:31.247  5499  5546 I jxcore-log: 
11-22 12:58:31.247  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:58:31.247  5499  5546 I jxcore-log: 
11-22 12:58:31.247  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-22 12:58:31.247  5499  5546 I jxcore-log: 
11-22 12:58:31.247  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 12:58:31.247  5499  5546 I jxcore-log: 
,11-22 12:58:31.247  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-22 12:58:31.247  5499  5546 I jxcore-log: 
11-22 12:58:31.248  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-22 12:58:31.248  5499  5546 I jxcore-log: 
11-22 12:58:31.248  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-22 12:58:31.248  5499  5546 I jxcore-log: 
11-22 12:58:31.248  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-22 12:58:31.248  5499  5546 I jxcore-log: 
11-22 12:58:31.249  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 12:58:31.249  5499  5546 I jxcore-log: 
,11-22 12:58:31.250  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:58:31.250  5499  5546 I jxcore-log: 
11-22 12:58:31.250  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 12:58:31.250  5499  5546 I jxcore-log: 
11-22 12:58:31.250  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 12:58:31.250  5499  5546 I jxcore-log: 
11-22 12:58:31.251  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:58:31.251  5499  5546 I jxcore-log: 
,11-22 12:58:31.251  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-22 12:58:31.251  5499  5546 I jxcore-log: 
11-22 12:58:31.251  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 12:58:31.251  5499  5546 I jxcore-log: 
11-22 12:58:31.251  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:58:31.251  5499  5546 I jxcore-log: 
11-22 12:58:31.251  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 12:58:31.251  5499  5546 I jxcore-log: 
11-22 12:58:31.251  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:58:31.251  5499  5546 I jxcore-log: 
,11-22 12:58:31.256  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-22 12:58:31.256  5499  5546 I jxcore-log: 
11-22 12:58:31.257  5499  5546 I jxcore-log: 2016-11-22 11:58:31 - WARN testUtils: 'myNameCallback not set!'
11-22 12:58:31.257  5499  5546 I jxcore-log: 
,11-22 12:58:31.264  5499  5499 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-22 12:58:32.966  3550  3718 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-22 12:58:32.966  3550  3718 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-22 12:58:33.001  3469  3469 I ConfigService: onCreate
,11-22 12:58:33.355  5499  5546 I jxcore-log: 2016-11-22 11:58:33 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-22 12:58:33.355  5499  5546 I jxcore-log: 
,11-22 12:58:33.356  5499  5546 I jxcore-log: 2016-11-22 11:58:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-22 12:58:33.356  5499  5546 I jxcore-log: 
,11-22 12:58:33.707  5499  5546 I jxcore-log: 2016-11-22 11:58:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-22 12:58:33.707  5499  5546 I jxcore-log: 
,11-22 12:58:33.721  5499  5546 I jxcore-log: 2016-11-22 11:58:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-22 12:58:33.721  5499  5546 I jxcore-log: 
,11-22 12:58:33.774  5696  5696 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:58:34.853  5499  5546 I jxcore-log: 2016-11-22 11:58:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-22 12:58:34.853  5499  5546 I jxcore-log: 
,11-22 12:58:35.021  5499  5546 I jxcore-log: 2016-11-22 11:58:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-22 12:58:35.021  5499  5546 I jxcore-log: 
,11-22 12:58:35.027  5499  5546 I jxcore-log: 2016-11-22 11:58:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-22 12:58:35.027  5499  5546 I jxcore-log: 
,11-22 12:58:35.039  5499  5546 I jxcore-log: 2016-11-22 11:58:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-22 12:58:35.039  5499  5546 I jxcore-log: 
,11-22 12:58:35.128   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 12:58:35.128   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 12:58:35.539  5499  5546 I jxcore-log: 2016-11-22 11:58:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-22 12:58:35.539  5499  5546 I jxcore-log: 
,11-22 12:58:35.584  5499  5546 I jxcore-log: 2016-11-22 11:58:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-22 12:58:35.584  5499  5546 I jxcore-log: 
,11-22 12:58:35.598  5499  5546 I jxcore-log: 2016-11-22 11:58:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-22 12:58:35.598  5499  5546 I jxcore-log: 
,11-22 12:58:35.602  5499  5546 I jxcore-log: 2016-11-22 11:58:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-22 12:58:35.602  5499  5546 I jxcore-log: 
,11-22 12:58:35.879  5499  5546 I jxcore-log: 2016-11-22 11:58:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-22 12:58:35.879  5499  5546 I jxcore-log: 
,11-22 12:58:36.006  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-22 12:58:36.006  5499  5546 I jxcore-log: 
,11-22 12:58:36.383  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-22 12:58:36.383  5499  5546 I jxcore-log: 
,11-22 12:58:36.390  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-22 12:58:36.390  5499  5546 I jxcore-log: 
,11-22 12:58:36.394  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-22 12:58:36.394  5499  5546 I jxcore-log: 
,11-22 12:58:36.398  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-22 12:58:36.398  5499  5546 I jxcore-log: 
,11-22 12:58:36.402  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-22 12:58:36.402  5499  5546 I jxcore-log: 
,11-22 12:58:36.441  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-22 12:58:36.441  5499  5546 I jxcore-log: 
,11-22 12:58:36.447  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-22 12:58:36.447  5499  5546 I jxcore-log: 
,11-22 12:58:36.477  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-22 12:58:36.477  5499  5546 I jxcore-log: 
,11-22 12:58:36.516  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-22 12:58:36.516  5499  5546 I jxcore-log: 
,11-22 12:58:36.524  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-22 12:58:36.524  5499  5546 I jxcore-log: 
,11-22 12:58:36.530  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-22 12:58:36.530  5499  5546 I jxcore-log: 
,11-22 12:58:36.546  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-22 12:58:36.546  5499  5546 I jxcore-log: 
,11-22 12:58:36.561  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-22 12:58:36.561  5499  5546 I jxcore-log: 
,11-22 12:58:36.567  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-22 12:58:36.567  5499  5546 I jxcore-log: 
,11-22 12:58:36.572  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-22 12:58:36.572  5499  5546 I jxcore-log: 
,11-22 12:58:36.585  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-22 12:58:36.585  5499  5546 I jxcore-log: 
,11-22 12:58:36.603  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-22 12:58:36.603  5499  5546 I jxcore-log: 
,11-22 12:58:36.618  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-22 12:58:36.618  5499  5546 I jxcore-log: 
,11-22 12:58:36.628  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-22 12:58:36.628  5499  5546 I jxcore-log: 
,11-22 12:58:36.641  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-22 12:58:36.641  5499  5546 I jxcore-log: 
,11-22 12:58:36.652  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-22 12:58:36.652  5499  5546 I jxcore-log: 
,11-22 12:58:36.665  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-22 12:58:36.665  5499  5546 I jxcore-log: 
,11-22 12:58:36.675  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-22 12:58:36.675  5499  5546 I jxcore-log: 
,11-22 12:58:36.682  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-22 12:58:36.682  5499  5546 I jxcore-log: 
,11-22 12:58:36.703  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-22 12:58:36.703  5499  5546 I jxcore-log: 
,11-22 12:58:36.709  5499  5546 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-22 12:58:36.710  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - INFO testUtils: 'BLE multiple advertisement supported'
11-22 12:58:36.710  5499  5546 I jxcore-log: 
,11-22 12:58:36.966  5499  5546 I jxcore-log: 2016-11-22 11:58:36 - DEBUG CoordinatedClient: 'connected to the test server'
11-22 12:58:36.966  5499  5546 I jxcore-log: 
,11-22 12:58:38.031  3469  3469 I ConfigService: onDestroy
,11-22 12:58:45.130   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:46.131   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:47.133   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:48.134   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:49.135   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:49.175   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:58:50.060   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 12:58:50.136   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 12:58:52.208   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:58:55.137   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:56.138   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:57.140   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:58.141   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:58:59.142   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:00.143   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 12:59:01.302   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:59:07.373   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:59:10.144   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:10.389   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:59:11.146   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:12.147   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:13.148   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:13.404   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:59:14.150   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:15.151   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 12:59:22.496   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:59:25.527   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:59:30.066   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 12:59:30.152   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:31.154   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:32.155   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:33.156   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:34.158   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:35.158   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 12:59:50.067   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 12:59:52.787   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:59:55.159   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:55.820   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:59:56.160   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:57.162   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:58.163   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:59:59.164   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:00.165   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 13:00:07.932   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:00:10.953   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:00:25.165   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 13:00:25.165   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 13:00:30.069   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 13:00:32.154   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:00:38.220   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:00:40.167   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:41.168   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:41.253   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:00:42.170   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:43.171   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:44.173   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:45.174   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 13:00:47.309   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:00:50.072   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 13:00:50.175   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:51.177   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:52.178   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:53.180   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:54.181   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:00:55.182   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 13:00:59.447   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:01:02.481   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:01:05.184   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:06.185   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:07.187   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:08.188   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:09.190   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:10.075   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 13:01:10.191   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 13:01:14.604   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:01:20.661   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:01:25.192   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:26.194   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:27.195   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:28.197   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:29.198   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:30.199   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 13:01:47.915   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:01:50.078   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 13:01:50.200   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:51.201   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:52.203   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:53.204   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:53.974   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:01:54.205   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:01:55.206   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 13:02:06.088   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:02:10.080   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 13:02:12.144   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:02:20.206   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 13:02:20.207   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 13:02:21.229   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:02:27.295   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:02:30.081   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 13:02:36.371   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:02:40.207   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:02:41.208   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:02:42.210   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:02:42.445   927  2846 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 13:02:43.162  5499  5546 I jxcore-log: 2016-11-22 12:02:43 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-22 13:02:43.162  5499  5546 I jxcore-log: 
,11-22 13:02:43.211   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:02:43.427  5499  5546 I jxcore-log: 2016-11-22 12:02:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:43.427  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:43.427  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:43.427  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:43.427  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:43.427  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:43.427  5499  5546 I jxcore-log: 
,11-22 13:02:43.432  5499  5546 I jxcore-log: 2016-11-22 12:02:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:43.432  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:43.432  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:43.432  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:43.432  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:43.432  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:43.432  5499  5546 I jxcore-log: 
,11-22 13:02:43.703  5499  5546 I jxcore-log: 2016-11-22 12:02:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:43.703  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:43.703  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:43.703  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:43.703  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:43.703  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:43.703  5499  5546 I jxcore-log: 
,11-22 13:02:43.706  5499  5546 I jxcore-log: 2016-11-22 12:02:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:43.706  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:43.706  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:43.706  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:43.706  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:43.706  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:43.706  5499  5546 I jxcore-log: 
,11-22 13:02:44.212   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:02:45.074  5499  5546 I jxcore-log: 2016-11-22 12:02:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:45.074  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:45.074  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:45.074  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:45.074  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:45.074  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:45.074  5499  5546 I jxcore-log: 
,11-22 13:02:45.081  5499  5546 I jxcore-log: 2016-11-22 12:02:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:45.081  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:45.081  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:45.081  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:45.081  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:45.081  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:45.081  5499  5546 I jxcore-log: 
,11-22 13:02:45.213   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 13:02:46.111  5499  5546 I jxcore-log: 2016-11-22 12:02:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:46.111  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:46.111  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:46.111  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:46.111  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:46.111  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:46.111  5499  5546 I jxcore-log: 
,11-22 13:02:46.114  5499  5546 I jxcore-log: 2016-11-22 12:02:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:46.114  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:46.114  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:46.114  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:46.114  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:46.114  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:46.114  5499  5546 I jxcore-log: 
,11-22 13:02:47.153  5499  5546 I jxcore-log: 2016-11-22 12:02:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:47.153  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:47.153  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:47.153  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:47.153  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:47.153  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:47.153  5499  5546 I jxcore-log: 
,11-22 13:02:47.157  5499  5546 I jxcore-log: 2016-11-22 12:02:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:47.157  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:47.157  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:47.157  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:47.157  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:47.157  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:47.157  5499  5546 I jxcore-log: 
,11-22 13:02:48.189  5499  5546 I jxcore-log: 2016-11-22 12:02:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:48.189  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:48.189  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:48.189  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:48.189  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:48.189  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:48.189  5499  5546 I jxcore-log: 
,11-22 13:02:48.192  5499  5546 I jxcore-log: 2016-11-22 12:02:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:48.192  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:48.192  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:48.192  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:48.192  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:48.192  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:48.192  5499  5546 I jxcore-log: 
,11-22 13:02:49.230  5499  5546 I jxcore-log: 2016-11-22 12:02:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:49.230  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:49.230  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:49.230  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:49.230  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:49.230  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:49.230  5499  5546 I jxcore-log: 
,11-22 13:02:49.235  5499  5546 I jxcore-log: 2016-11-22 12:02:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:49.235  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:49.235  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:49.235  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:49.235  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:49.235  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:49.235  5499  5546 I jxcore-log: 
,11-22 13:02:50.083   927  2844 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 13:02:50.215   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:02:50.273  5499  5546 I jxcore-log: 2016-11-22 12:02:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:50.273  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:50.273  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:50.273  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:50.273  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:50.273  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:50.273  5499  5546 I jxcore-log: 
,11-22 13:02:50.278  5499  5546 I jxcore-log: 2016-11-22 12:02:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:50.278  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:50.278  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:50.278  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:50.278  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:50.278  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:50.278  5499  5546 I jxcore-log: 
,11-22 13:02:51.216   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:02:51.313  5499  5546 I jxcore-log: 2016-11-22 12:02:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:51.313  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:51.313  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:51.313  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:51.313  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:51.313  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:51.313  5499  5546 I jxcore-log: 
,11-22 13:02:51.318  5499  5546 I jxcore-log: 2016-11-22 12:02:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:51.318  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:51.318  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:51.318  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:51.318  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:51.318  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:51.318  5499  5546 I jxcore-log: 
,11-22 13:02:52.217   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:02:52.387  5499  5546 I jxcore-log: 2016-11-22 12:02:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:52.387  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:52.387  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:52.387  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:52.387  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:52.387  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:52.387  5499  5546 I jxcore-log: 
,11-22 13:02:52.392  5499  5546 I jxcore-log: 2016-11-22 12:02:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:52.392  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:52.392  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:52.392  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:52.392  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:52.392  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:52.392  5499  5546 I jxcore-log: 
,11-22 13:02:53.218   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:02:53.432  5499  5546 I jxcore-log: 2016-11-22 12:02:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:53.432  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:53.432  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:53.432  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:53.432  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:53.432  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:53.432  5499  5546 I jxcore-log: 
,11-22 13:02:53.439  5499  5546 I jxcore-log: 2016-11-22 12:02:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:53.439  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:53.439  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:53.439  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:53.439  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:53.439  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:53.439  5499  5546 I jxcore-log: 
,11-22 13:02:54.219   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 13:02:54.472  5499  5546 I jxcore-log: 2016-11-22 12:02:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:54.472  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:54.472  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:54.472  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:54.472  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:54.472  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:54.472  5499  5546 I jxcore-log: 
,11-22 13:02:54.477  5499  5546 I jxcore-log: 2016-11-22 12:02:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:54.477  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:54.477  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:54.477  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:54.477  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:54.477  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:54.477  5499  5546 I jxcore-log: 
,11-22 13:02:55.220   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 13:02:55.509  5499  5546 I jxcore-log: 2016-11-22 12:02:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:55.509  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:55.509  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:55.509  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:55.509  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:55.509  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:55.509  5499  5546 I jxcore-log: 
,11-22 13:02:55.514  5499  5546 I jxcore-log: 2016-11-22 12:02:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:55.514  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:55.514  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:55.514  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:55.514  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:55.514  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:55.514  5499  5546 I jxcore-log: 
,11-22 13:02:56.551  5499  5546 I jxcore-log: 2016-11-22 12:02:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:56.551  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:56.551  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:56.551  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:56.551  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:56.551  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:56.551  5499  5546 I jxcore-log: 
,11-22 13:02:56.556  5499  5546 I jxcore-log: 2016-11-22 12:02:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:56.556  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:56.556  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:56.556  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:56.556  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:56.556  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:56.556  5499  5546 I jxcore-log: 
,11-22 13:02:57.593  5499  5546 I jxcore-log: 2016-11-22 12:02:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 13:02:57.593  5499  5546 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 13:02:57.593  5499  5546 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 13:02:57.593  5499  5546 I jxcore-log: emit@events.js:82:1
11-22 13:02:57.593  5499  5546 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 13:02:57.593  5499  5546 I jxcore-log: emit@events.js:82:1'
11-22 13:02:57.593  5499  5546 I jxcore-log: 
,11-22 13:02:57.604  5499  5546 E jxcore  : Error!: error is undefined
11-22 13:02:57.604  5499  5546 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-22 13:02:57.608  5499  5546 I jxcore-log: 2016-11-22 12:02:57 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-22 13:02:57.608  5499  5546 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-22 13:02:57.608  5499  5546 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-22 13:02:57.608  5499  5546 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-22 13:02:57.608  5499  5546 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-22 13:02:57.608  5499  5546 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-22 13:02:57.608  5499  5546 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-22 13:02:57.608  5499  5546 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-22 13:02:57.610  5499  5546 I jxcore-log: 2016-11-22 12:02:57 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-22 13:02:57.610  5499  5546 I jxcore-log: 
,11-22 13:02:57.613  5499  5546 E jxcore-log: TypeError: 
11-22 13:02:57.614  5499  5546 E jxcore-log: error is undefined
11-22 13:02:57.614  5499  5546 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-22 13:02:57.614  5499  5546 E jxcore-log: 
,11-22 13:02:57.724   927  3730 I WindowState: WIN DEATH: Window{6292178 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-22 13:02:57.725   927  2845 D WifiService: Client connection lost with reason: 4
11-22 13:02:57.725   927  3044 D GraphicsStats: Buffer count: 2
,11-22 13:02:57.736   526   526 I Zygote  : Process 5499 exited cleanly (139)
,11-22 13:02:57.741   927  3460 I ActivityManager: Process com.test.thalitest (pid 5499) has died
,11-22 13:02:57.743   927  3460 W ActivityManager: Force removing ActivityRecord{2616800 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-22 13:02:57.780   927  3731 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5499 uid 10077
11-22 13:02:57.777  3731  3731 W Binder_8: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[28845]" dev="sockfs" ino=28845 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 13:02:57.777  3731  3731 W Binder_8: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[28845]" dev="sockfs" ino=28845 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 13:02:57.782  3550  3550 I Keyboard.Facilitator: onFinishInput()
,11-22 13:02:57.802  3833  3833 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,11-22 13:02:57.831  3833  5752 I MicroRecognitionRnrImpl: Starting detection.
,11-22 13:02:57.833  3833  5753 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@1bea3fd
,11-22 13:02:57.834   511  5755 I AudioFlinger: AudioFlinger's thread 0xf2080000 ready to run
,11-22 13:02:57.840   511  2892 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-22 13:02:57.843  3833  5753 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@1bea3fd
,11-22 13:02:57.853   511  5755 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-22 13:02:57.853   511  5755 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-22 13:02:57.854   511  5755 I ACDB-LOADER: ACDB AFE returned = -19
11-22 13:02:57.854   511  5755 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-22 13:02:57.854   511  5755 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-22 13:02:57.854   511  5755 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-22 13:02:57.862   511  5755 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-22 13:02:57.936  3833  3833 I HotwordWorkerImpl: onReady
,11-22 13:02:57.975  5747  5747 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-22 13:02:57.979  5747  5747 D AndroidRuntime: CheckJNI is OFF
,11-22 13:02:58.003  5747  5747 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-22 13:02:58.030  5747  5747 I Radio-JNI: register_android_hardware_Radio DONE
,11-22 13:02:58.045  5747  5747 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-22 13:02:58.051   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-22 13:02:58.182   927   950 I art     : Starting a blocking GC Explicit
,11-22 13:02:58.308  3668  3925 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-22 13:02:58.310   927   950 I art     : Explicit concurrent mark sweep GC freed 149316(10MB) AllocSpace objects, 86(2MB) LOS objects, 33% free, 29MB/43MB, paused 2.123ms total 127.533ms
,11-22 13:02:58.328   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-22 13:02:58.330  5747  5747 I art     : System.exit called, status: 0
,11-22 13:02:58.330  5747  5747 I AndroidRuntime: VM exiting with result code 0.
,11-22 13:02:58.334   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-22 13:02:58.355  3550  3550 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-22 13:02:58.356  5593  5593 D BluetoothMapAppObserver: onReceive
,11-22 13:02:58.356  5593  5593 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-22 13:02:58.360  3550  5770 I Keyboard.Facilitator.DecoderInitializer: run()
,11-22 13:02:58.365   927  2826 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-22 13:02:58.368  3550  5770 I Decoder : createOrResetDecoder
11-22 13:02:58.368  3988  4054 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-22 13:02:58.379  3294  5772 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-22 13:02:58.414  5744  5744 W kworker/2:2: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 13:02:58.423  3469  3469 I ConfigService: onCreate
,11-22 13:02:58.424   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-22 13:02:58.426  3649  3649 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-22 13:02:58.421  5744  5744 W kworker/2:2: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 13:02:58.427  5744  5744 W kworker/2:2: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 13:02:58.433  3469  3469 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-22 13:02:58.434  3469  3469 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-22 13:02:58.435  3469  3469 E AndroidRuntime: FATAL EXCEPTION: main
11-22 13:02:58.435  3469  3469 E AndroidRuntime: Process: com.google.process.gapps, PID: 3469
11-22 13:02:58.435  3469  3469 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-22 13:02:58.435  3469  3469 E AndroidRuntime: 	... 8 more
,11-22 13:02:58.440  3550  5770 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-22 13:02:58.444   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-22 13:02:58.446   927   939 E PackageManager: Failed to write settings, restoring backup
11-22 13:02:58.446   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-22 13:02:58.446   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-22 13:02:58.446   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-22 13:02:58.446   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-22 13:02:58.446   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-22 13:02:58.446   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 13:02:58.446   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-22 13:02:58.446   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 13:02:58.446  3668  3787 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-22 13:02:58.451   927  5777 E DropBoxManagerService: Can't write: system_app_crash
11-22 13:02:58.451   927  5777 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 13:02:58.451   927  5777 E DropBoxManagerService: 	... 5 more
,11-22 13:02:58.451   927   940 E DropBoxManagerService: Can't write: system_server_wtf
11-22 13:02:58.451   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-22 13:02:58.451   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 13:02:58.451   927   940 E DropBoxManagerService: 	... 13 more
,11-22 13:02:58.457   406   406 W Binder_1: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[33146]" dev="sockfs" ino=33146 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 13:02:58.457   406   406 W Binder_1: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[33146]" dev="sockfs" ino=33146 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 13:02:58.464   927  5778 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 13:02:58.461   408   408 W Binder_2: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[35897]" dev="sockfs" ino=35897 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 13:02:58.461   408   408 W Binder_2: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[35897]" dev="sockfs" ino=35897 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 13:02:58.466  3294  5772 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-22 13:02:58.467  3294  5772 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-22 13:02:58.467  3294  5772 E AndroidRuntime: Process: android.process.acore, PID: 3294
11-22 13:02:58.467  3294  5772 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 13:02:58.467  3294  5772 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 13:02:58.477   927  3483 I ActivityManager: Start proc 5779:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-22 13:02:58.477  3550  5770 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-22 13:02:58.478  3668  3787 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-22 13:02:58.478  3668  3787 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3668
11-22 13:02:58.478  3668  3787 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 13:02:58.478  3668  3787 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 13:02:58.480   927  5785 E DropBoxManagerService: Can't write: system_app_crash
11-22 13:02:58.480   927  5785 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 13:02:58.480   927  5785 E DropBoxManagerService: 	... 5 more
11-22 13:02:58.481   927  3730 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-22 13:02:58.481  3550  5770 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-22 13:02:58.481  3550  5770 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-22 13:02:58.484   927  5787 E DropBoxManagerService: Can't write: system_app_crash
11-22 13:02:58.484   927  5787 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 13:02:58.484   927  5787 E DropBoxManagerService: 	... 5 more
,11-22 13:02:58.484  3833  3846 W SearchService: Abort, client detached.
11-22 13:02:58.484  3550  5770 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-22 13:02:58.484  3550  5770 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-22 13:02:58.485  3550  5770 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-22 13:02:58.485  3550  5770 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-22 13:02:58.486  3833  3833 I HotwordDetector: Closing mic
11-22 13:02:58.486  3833  4055 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1bea3fd
11-22 13:02:58.486  3833  5753 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-22 13:02:58.487  3550  5770 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-22 13:02:58.487  3550  5770 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-22 13:02:58.487  3550  5770 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-22 13:02:58.487  3550  5770 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-22 13:02:58.487  3550  5770 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-22 13:02:58.487  3550  5770 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-22 13:02:58.518   927  5778 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-22 13:02:58.518   927  5778 I Adreno  : Build Date                       : 12/06/15
11-22 13:02:58.518   927  5778 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-22 13:02:58.518   927  5778 I Adreno  : Local Branch                     : mybranch17112971
11-22 13:02:58.518   927  5778 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-22 13:02:58.518   927  5778 I Adreno  : Remote Branch                    : NONE
11-22 13:02:58.518   927  5778 I Adreno  : Reconstruct Branch               : NOTHING
,11-22 13:02:58.533   927  3044 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-22 13:02:58.549   511  5755 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-22 13:02:58.550   511  5755 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-22 13:02:58.552   511  5755 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-22 13:02:58.553   511  5755 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-22 13:02:58.553   511  2892 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-22 13:02:58.555  3833  5752 I MicroRecognitionRnrImpl: Detection finished
,11-22 13:02:58.557  3833  4056 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-22 13:02:58.829   386   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
