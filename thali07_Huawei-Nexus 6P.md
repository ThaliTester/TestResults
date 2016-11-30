#### Test 95813110eafd18b_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-30 23:03:48.997   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-30 23:03:49.550  5636  5636 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-30 23:03:49.556  5636  5636 D AndroidRuntime: CheckJNI is OFF
11-30 23:03:49.584  5636  5636 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-30 23:03:49.617  5636  5636 I Radio-JNI: register_android_hardware_Radio DONE
11-30 23:03:49.632  5636  5636 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-30 23:03:49.635   931  3194 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-30 23:03:49.662  4014  4025 W SearchService: Abort, client detached.
11-30 23:03:49.669  5636  5636 D AndroidRuntime: Shutting down VM
11-30 23:03:49.673  4014  4014 I HotwordDetector: Closing mic
11-30 23:03:49.673  4014  4229 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@717b013
11-30 23:03:49.674  4014  4252 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-30 23:03:49.703   931  3188 I ActivityManager: Start proc 5646:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-30 23:03:49.751   512  4257 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-30 23:03:49.752   512  4257 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-30 23:03:49.758   512  4257 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-30 23:03:49.758   512  4257 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-30 23:03:49.759   512  3041 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-30 23:03:49.761  4014  4240 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-30 23:03:49.761  4014  4251 I MicroRecognitionRnrImpl: Detection finished
11-30 23:03:49.809  5646  5646 I CordovaLog: Changing log level to DEBUG(3)
11-30 23:03:49.809  5646  5646 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-30 23:03:49.809  5646  5646 D CordovaActivity: CordovaActivity.onCreate()
11-30 23:03:49.813  5646  5646 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-30 23:03:49.832  5646  5646 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-30 23:03:49.855  5646  5646 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 9355-9375)
11-30 23:03:49.855  5646  5646 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-30 23:03:49.873  5646  5646 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b4333d9}
11-30 23:03:49.874  5646  5646 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-30 23:03:49.874  5646  5646 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-30 23:03:49.877  5646  5646 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-30 23:03:49.878  5646  5646 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-30 23:03:49.911  5646  5646 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-30 23:03:49.919  5646  5646 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-30 23:03:49.920  5646  5646 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-30 23:03:49.920  5646  5646 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-30 23:03:49.920  5646  5646 I Adreno  : Build Date                       : 12/06/15
11-30 23:03:49.920  5646  5646 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-30 23:03:49.920  5646  5646 I Adreno  : Local Branch                     : mybranch17112971
11-30 23:03:49.920  5646  5646 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-30 23:03:49.920  5646  5646 I Adreno  : Remote Branch                    : NONE
11-30 23:03:49.920  5646  5646 I Adreno  : Reconstruct Branch               : NOTHING
,11-30 23:03:49.958   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7a2b092:true
,11-30 23:03:49.992   741   741 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[14260]" dev="sockfs" ino=14260 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 23:03:49.992   741   741 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14260]" dev="sockfs" ino=14260 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 23:03:50.001  5646  5646 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-30 23:03:50.010  5646  5646 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-30 23:03:50.014  5646  5646 D PluginManager: init()
,11-30 23:03:50.016  5646  5646 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-30 23:03:50.031  5646  5646 D CordovaActivity: Started the activity.
,11-30 23:03:50.031  5646  5646 D CordovaActivity: Resumed the activity.
,11-30 23:03:50.032   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32088]" dev="sockfs" ino=32088 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 23:03:50.032   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32088]" dev="sockfs" ino=32088 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-30 23:03:50.036  5646  5683 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-30 23:03:50.039  3457  3457 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14271]" dev="sockfs" ino=14271 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 23:03:50.039  3457  3457 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14271]" dev="sockfs" ino=14271 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-30 23:03:50.041  5646  5670 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-30 23:03:50.077  5646  5683 I OpenGLRenderer: Initialized EGL, version 1.4
,11-30 23:03:50.149   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +472ms
,11-30 23:03:50.149  3457  3457 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32091]" dev="sockfs" ino=32091 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 23:03:50.149  3457  3457 W Binder_6: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32091]" dev="sockfs" ino=32091 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 23:03:50.152  3906  3906 W Binder_A: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32090]" dev="sockfs" ino=32090 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-30 23:03:50.152  3906  3906 W Binder_A: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32090]" dev="sockfs" ino=32090 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-30 23:03:50.158  3708  3708 I Keyboard.Facilitator: onFinishInput()
,11-30 23:03:50.162  5646  5646 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-30 23:03:50.180  5646  5646 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5646
,11-30 23:03:50.286  5646  5646 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-30 23:03:50.498  5646  5686 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -563607248
,11-30 23:03:50.499   931  3457 I ActivityManager: Killing 5440:com.android.chrome/u0a39 (adj 15): empty #17
,11-30 23:03:50.503  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-30 23:03:50.503  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-30 23:03:50.503  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-30 23:03:50.503  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-30 23:03:50.503  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-30 23:03:50.504  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f0e9a4 added. We now have 1 listener(s)
,11-30 23:03:50.507  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-30 23:03:50.507  5646  5686 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 23:03:50.508  5646  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 23:03:50.508  5646  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-30 23:03:50.511  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f01c8d3 added. We now have 1 listener(s)
11-30 23:03:50.511  5646  5686 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-30 23:03:50.516   931  2994 D WifiService: New client listening to asynchronous messages
,11-30 23:03:50.517  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-30 23:03:50.517  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-30 23:03:50.517  5646  5686 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-30 23:03:50.517  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-30 23:03:50.517  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-30 23:03:50.517  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-30 23:03:50.518  5646  5686 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-30 23:03:50.519  5646  5686 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-30 23:03:50.531   931  3457 I ActivityManager: Killing 5428:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,11-30 23:03:50.784  5646  5646 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-30 23:03:50.793  5646  5646 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-30 23:03:50.795  5646  5646 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-30 23:03:51.126  5646  5655 I art     : Background sticky concurrent mark sweep GC freed 77497(7MB) AllocSpace objects, 16(1476KB) LOS objects, 25% free, 24MB/32MB, paused 1.456ms total 221.492ms
,11-30 23:03:52.128  5646  5693 W jxcore-log: Initializing JXcore engine
,11-30 23:03:52.128  5646  5693 W jxcore-log: JXcore engine is ready
,11-30 23:03:52.149  5693  5693 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=2980 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-30 23:03:52.149  5693  5693 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14373]" dev="sockfs" ino=14373 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-30 23:03:52.149  5693  5693 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5886 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-30 23:03:52.149  5693  5693 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32059]" dev="sockfs" ino=32059 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-30 23:03:52.158  5646  5693 W jxcore-log: Starting JXcore engine
,11-30 23:03:52.213  5646  5693 W jxcore-log: Platform android
11-30 23:03:52.213  5646  5693 W jxcore-log: 
,11-30 23:03:52.213  5646  5693 W jxcore-log: Process ARCH arm
11-30 23:03:52.213  5646  5693 W jxcore-log: 
,11-30 23:03:52.366  5646  5693 I jxcore-log: JXcore Cordova bridge is ready!
11-30 23:03:52.366  5646  5693 I jxcore-log: 
,11-30 23:03:52.366  5646  5693 W jxcore-log: JXcore engine is started
,11-30 23:03:52.376   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-30 23:03:52.385  5646  5686 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-30 23:03:52.391  5646  5646 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
11-30 23:03:52.392  5646  5646 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-30 23:03:57.107  4102  4518 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-30 23:03:59.977  4014  5694 W CronetSyncConnectionRcs: Upload content type not set.
,11-30 23:03:59.983   931  2994 D WifiService: New client listening to asynchronous messages
,11-30 23:03:59.985  3628  5700 I VacuumService: Vacuum at: now=1480543439985 tag=VacuumService
,11-30 23:04:00.024  3628  5709 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-30 23:04:00.055  3628  5701 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-30 23:04:00.057  3628  5701 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-30 23:04:00.075  3628  5701 W Uploader:  no longer exists, so no auth token.
,11-30 23:04:00.081  3628  5709 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-30 23:04:01.303  3628  5701 W Uploader:  no longer exists, so no auth token.
,11-30 23:04:01.335  3628  5717 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-30 23:04:01.428   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-30 23:04:01.464  3628  5719 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-30 23:04:01.654  3628  5717 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-30 23:04:01.837  3628  5719 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-30 23:04:01.970  5646  5693 I jxcore-log: 2016-11-30 22:04:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-30 23:04:01.970  5646  5693 I jxcore-log: 
,11-30 23:04:01.972  5646  5693 I jxcore-log: 2016-11-30 22:04:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-30 23:04:01.972  5646  5693 I jxcore-log: 
,11-30 23:04:01.977  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-30 23:04:01.978  5646  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-30 23:04:01.978  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 23:04:01.978  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 23:04:01.978  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 23:04:01.978  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 23:04:01.978  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 23:04:01.978  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 23:04:01.978  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 23:04:01.978  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-30 23:04:01.981  5646  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 23:04:01.985  5646  5693 I jxcore-log: 2016-11-30 22:04:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-30 23:04:01.985  5646  5693 I jxcore-log: 
,11-30 23:04:01.989  5646  5693 I jxcore-log: 2016-11-30 22:04:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-30 23:04:01.989  5646  5693 I jxcore-log: 
,11-30 23:04:02.238  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-30 23:04:02.239  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66e873c added. We now have 2 listener(s)
,11-30 23:04:02.239  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 23:04:02.239  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 23:04:02.240  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 23:04:02.240  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 23:04:02.240  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eac0cc5 added. We now have 2 listener(s)
,11-30 23:04:02.240  5646  5693 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 23:04:02.240  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-30 23:04:02.242  5646  5693 D ExecuteNativeTests: Running unit tests
,11-30 23:04:02.242  5646  5693 D BluetoothAdapter: enable(): BT is already enabled..!
11-30 23:04:02.242   931  3906 D WifiService: setWifiEnabled: true pid=5646, uid=10077
11-30 23:04:02.242   931  3906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 23:04:03.999   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:04:04.466   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-30 23:04:05.000   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:04:05.037   931  5398 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-30 23:04:06.001   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:04:07.003   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:04:08.004   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:04:09.005   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-30 23:04:12.248  5646  5693 I com.test.thalitest.ThaliTestRunner: Running UT
,11-30 23:04:12.313  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-30 23:04:12.313  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d62d70f added. We now have 3 listener(s)
11-30 23:04:12.314  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 23:04:12.314  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-30 23:04:12.314  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 23:04:12.314  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 23:04:12.314  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@536539c added. We now have 3 listener(s)
11-30 23:04:12.314  5646  5693 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-30 23:04:12.315  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 23:04:12.319  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-30 23:04:12.319  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 23:04:12.319  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 23:04:12.319  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 23:04:12.320  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-30 23:04:12.320  5646  5693 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-30 23:04:12.321  5646  5693 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-30 23:04:12.321  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-30 23:04:12.321  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 23:04:12.321  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-30 23:04:12.321  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 23:04:12.322  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-30 23:04:12.323  5646  5693 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-30 23:04:12.324  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-30 23:04:12.326  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-30 23:04:12.326  5646  5693 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-30 23:04:12.328  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 23:04:12.328  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-30 23:04:12.332  5646  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-30 23:04:12.332  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 23:04:12.332  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 23:04:12.332  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 23:04:12.332  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 23:04:12.332  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 23:04:12.332  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 23:04:12.332  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 23:04:12.332  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-30 23:04:12.333  5646  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 23:04:12.333  5646  5693 D io.jxcore.node.ConnectivityMonitor: start: OK
11-30 23:04:12.333  5646  5693 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-30 23:04:12.333  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-30 23:04:12.334  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.334  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.334  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:12.334  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 23:04:12.334  5646  5693 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 23:04:12.334  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 23:04:12.334  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 23:04:12.334  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 23:04:12.335  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 23:04:12.335  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 23:04:12.335  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 23:04:12.336  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 23:04:12.336  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 23:04:12.336  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-30 23:04:12.336  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 23:04:12.336  5646  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 23:04:12.337  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-30 23:04:12.338  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 23:04:12.339  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 23:04:12.340  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-30 23:04:12.340  5646  5693 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 23:04:12.340  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-30 23:04:12.343  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.343  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 23:04:12.344  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 23:04:12.344  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 23:04:12.344  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-30 23:04:12.345  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.345  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.345  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 23:04:12.345  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 23:04:12.345  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 23:04:12.345  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
,11-30 23:04:12.345  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:12.345  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-30 23:04:12.345  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.346  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 23:04:12.346  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:12.346  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.346  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.346  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.346  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:12.349  4910  4910 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32172]" dev="sockfs" ino=32172 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:12.349  4910  4910 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32172]" dev="sockfs" ino=32172 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 23:04:12.347  5646  5722 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 23:04:12.350  4697  4712 D BtGatt.GattService: registerClient() - UUID=4e842b3d-a8c8-42a7-afc3-23415adc8315
11-30 23:04:12.351  4697  4773 D BtGatt.GattService: onClientRegistered() - UUID=4e842b3d-a8c8-42a7-afc3-23415adc8315, clientIf=5
11-30 23:04:12.351  5646  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 23:04:12.352  5646  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-30 23:04:12.355  4697  4775 D BtGatt.AdvertiseManager: message : 0
,11-30 23:04:12.359  4697  4775 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 23:04:12.374  4697  4773 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 23:04:12.382  4697  4773 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 23:04:12.384  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.384  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:12.384  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 23:04:12.384  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.384  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.384  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.384  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.384  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:12.384  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 23:04:12.385  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 23:04:12.385  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.386  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.386  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.386  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:12.386  5646  5693 I io.jxcore.node.ConnectionHelper: start: OK
,11-30 23:04:12.386  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 23:04:12.387  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.387  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:12.387  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 23:04:12.387  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.388  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.388  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-30 23:04:12.388  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.388  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 23:04:12.388  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 23:04:12.388  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.388  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.389  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-30 23:04:12.389  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.389  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.392  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.392  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 23:04:12.393  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.393  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-30 23:04:12.393  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 23:04:12.888  5646  5723 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-30 23:04:12.890  5646  5693 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-30 23:04:12.890  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-30 23:04:12.890  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-30 23:04:12.891  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-30 23:04:12.891  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-30 23:04:12.891  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-30 23:04:12.891  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-30 23:04:12.891  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-30 23:04:12.891  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-30 23:04:12.891  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-30 23:04:12.891  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-30 23:04:12.892  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-30 23:04:12.892  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-30 23:04:12.892  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-30 23:04:12.892  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-30 23:04:12.892  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-30 23:04:12.892  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-30 23:04:12.892  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-30 23:04:12.893  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-30 23:04:12.893  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-30 23:04:12.893  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-30 23:04:12.893  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-30 23:04:12.893  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-30 23:04:12.893  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-30 23:04:12.893  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-30 23:04:12.893  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-30 23:04:12.893  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-30 23:04:12.894  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-30 23:04:12.894  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-30 23:04:12.894  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-30 23:04:12.894  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-30 23:04:12.894  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-30 23:04:12.894  5646  5693 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-30 23:04:12.894  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-30 23:04:12.895  5646  5693 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-30 23:04:12.895  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-30 23:04:12.895  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 23:04:12.895  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 23:04:12.895  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 23:04:12.895  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-30 23:04:12.895  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 23:04:12.896  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 23:04:12.895  5646  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 23:04:12.896  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-30 23:04:12.896  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 23:04:12.896  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.896  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 23:04:12.896  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 23:04:12.896  5646  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 23:04:12.896  5646  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 23:04:12.897  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.897  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.897  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.897  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.898  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:12.899  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 23:04:12.899  5646  5693 D BluetoothAdapter: STATE_ON
,11-30 23:04:12.900  5646  5693 D BluetoothLeScanner: could not find callback wrapper
11-30 23:04:12.900  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 23:04:12.900  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.900  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.900  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:12.900  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 23:04:12.900  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.901  4697  4775 D BtGatt.AdvertiseManager: message : 1
11-30 23:04:12.903  4697  4775 D BtGatt.AdvertiseManager: stop advertise for client 5
11-30 23:04:12.915  4697  4773 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 23:04:12.916  4697  4773 D BtGatt.GattService: Client app is not null!
,11-30 23:04:12.918  4697  4710 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 23:04:12.919  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 23:04:12.919  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.919  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 23:04:12.919  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.920  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.920  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.920  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 23:04:12.920  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 23:04:12.921  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 23:04:12.921  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:12.922  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.922  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-30 23:04:12.922  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.923  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.923  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 23:04:12.923  5646  5646 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 23:04:12.925  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 23:04:12.925  5646  5724 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
11-30 23:04:12.925  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 23:04:12.925  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 23:04:12.925  5646  5693 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 23:04:12.925  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 23:04:12.926  5646  5693 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-30 23:04:12.926  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 23:04:12.926  5646  5693 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-30 23:04:12.926  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-30 23:04:12.926  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:12.926  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.926  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.926  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-30 23:04:12.926  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.926  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 23:04:12.926  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-30 23:04:12.927  5646  5693 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 23:04:12.927  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 23:04:12.927  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 23:04:12.927  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 23:04:12.927  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.927  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.927  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.927  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:12.927  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.928  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.928  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 23:04:12.928  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 23:04:12.928  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 23:04:12.928  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 23:04:12.928  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 23:04:12.929  5646  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 23:04:12.930  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.930  5646  5725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 23:04:12.931  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.931  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.931  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 23:04:12.931  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 23:04:12.931  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 23:04:12.932  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 23:04:12.933  5646  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 23:04:12.932  4910  4910 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31360]" dev="sockfs" ino=31360 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:12.932  4910  4910 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31360]" dev="sockfs" ino=31360 ioctlcmd=7704 sco,ntext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:12.936  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 23:04:12.936  5646  5693 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 23:04:12.936  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-30 23:04:12.940  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.940  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 23:04:12.941  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 23:04:12.941  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 23:04:12.941  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-30 23:04:12.944  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.944  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.944  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 23:04:12.944  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 23:04:12.944  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 23:04:12.944  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-30 23:04:12.945  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:12.945  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:12.945  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.945  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 23:04:12.945  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:12.945  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.945  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.946  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.947  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:12.949  4697  4910 D BtGatt.GattService: registerClient() - UUID=31fe5023-ef4b-402e-92f7-2c2579027e70
11-30 23:04:12.950  4697  4773 D BtGatt.GattService: onClientRegistered() - UUID=31fe5023-ef4b-402e-92f7-2c2579027e70, clientIf=5
11-30 23:04:12.951  5646  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-30 23:04:12.952  4697  4775 D BtGatt.AdvertiseManager: message : 0
11-30 23:04:12.955  4697  4775 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 23:04:12.969  4697  4773 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-30 23:04:12.977  4697  4773 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-30 23:04:12.978  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.978  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.978  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 23:04:12.978  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.979  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.979  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.979  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.979  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.979  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 23:04:12.982  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 23:04:12.982  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.983  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.983  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.983  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:12.984  5646  5693 I io.jxcore.node.ConnectionHelper: start: OK
11-30 23:04:12.984  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 23:04:12.984  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.984  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:12.984  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 23:04:12.984  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.985  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.985  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:12.985  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.985  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 23:04:12.985  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 23:04:12.985  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.985  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.985  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.985  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.985  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.989  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.989  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 23:04:12.989  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.989  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:12.989  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 23:04:13.485  5646  5726 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-30 23:04:13.488  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-30 23:04:13.488  5646  5693 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 23:04:13.488  5646  5693 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-30 23:04:13.488  5646  5693 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-30 23:04:13.488  5646  5693 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-30 23:04:13.488  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-30 23:04:13.489  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.489  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:13.489  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.490  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-30 23:04:13.491  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-30 23:04:13.491  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-30 23:04:13.491  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-30 23:04:13.491  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-30 23:04:13.491  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-30 23:04:13.491  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-30 23:04:13.491  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-30 23:04:13.491  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-30 23:04:13.491  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-30 23:04:13.491  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.491  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-30 23:04:13.492  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.492  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.492  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.494  4697  4775 D BtGatt.AdvertiseManager: message : 1
11-30 23:04:13.495  4697  4775 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 23:04:13.509  4697  4773 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 23:04:13.510  4697  4773 D BtGatt.GattService: Client app is not null!
,11-30 23:04:13.512  4697  4710 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-30 23:04:13.512  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 23:04:13.512  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.513  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 23:04:13.513  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.513  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.513  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:13.513  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 23:04:13.513  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.513  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.514  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.514  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-30 23:04:13.514  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 23:04:13.514  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 23:04:13.514  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-30 23:04:13.514  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:13.515  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-30 23:04:13.515  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.515  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 23:04:13.515  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:13.515  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.515  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.515  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.517  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:13.523  4697  4910 D BtGatt.GattService: registerClient() - UUID=3e47ea8d-ea1f-4823-a32a-adae9478b671
,11-30 23:04:13.523  4697  4773 D BtGatt.GattService: onClientRegistered() - UUID=3e47ea8d-ea1f-4823-a32a-adae9478b671, clientIf=5
11-30 23:04:13.524  5646  5657 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 23:04:13.525  4697  4775 D BtGatt.AdvertiseManager: message : 0
,11-30 23:04:13.528  4697  4775 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 23:04:13.544  4697  4773 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 23:04:13.554  4697  4773 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 23:04:13.555  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.555  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.555  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 23:04:13.555  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.555  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.556  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:13.556  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.556  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.556  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.556  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 23:04:13.556  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.556  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-30 23:04:13.557  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 23:04:13.557  5646  5693 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-30 23:04:13.557  5646  5693 I io.jxcore.node.ConnectionHelper: start: OK
11-30 23:04:13.557  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.557  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:13.557  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 23:04:13.557  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.558  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.558  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:13.558  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.558  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 23:04:13.558  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 23:04:13.558  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.558  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-30 23:04:13.559  5646  5727 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
11-30 23:04:13.559  5646  5693 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-30 23:04:13.559  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-30 23:04:13.559  5646  5693 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-30 23:04:13.559  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-30 23:04:13.559  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-30 23:04:13.559  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 23:04:13.560  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-30 23:04:13.560  5646  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 23:04:13.560  5646  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 23:04:13.560  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 23:04:13.560  5646  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 23:04:13.560  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 23:04:13.560  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 23:04:13.560  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 23:04:13.560  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 23:04:13.560  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 23:04:13.560  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.560  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 23:04:13.560  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 23:04:13.561  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 23:04:13.561  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.561  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:13.561  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.561  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.562  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:13.562  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 23:04:13.562  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:13.563  5646  5693 D BluetoothLeScanner: could not find callback wrapper
11-30 23:04:13.563  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 23:04:13.563  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.563  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.563  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.563  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 23:04:13.563  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.564  4697  4775 D BtGatt.AdvertiseManager: message : 1
11-30 23:04:13.565  4697  4775 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 23:04:13.572  4697  4773 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-30 23:04:13.573  4697  4773 D BtGatt.GattService: Client app is not null!
,11-30 23:04:13.574  4697  4910 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 23:04:13.574  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 23:04:13.574  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.574  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-30 23:04:13.574  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.575  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.575  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.575  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-30 23:04:13.575  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 23:04:13.575  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 23:04:13.576  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:13.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.577  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-30 23:04:13.577  5646  5646 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 23:04:13.578  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 23:04:13.578  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 23:04:13.578  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:13.578  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.579  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 23:04:13.579  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 23:04:13.579  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.579  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.580  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.580  5646  5728 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
11-30 23:04:13.580  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:13.580  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.580  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.581  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-30 23:04:13.581  5646  5693 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-30 23:04:13.583  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-30 23:04:13.583  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-30 23:04:13.584  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-30 23:04:13.584  5646  5693 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-30 23:04:13.585  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-30 23:04:13.585  5646  5693 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-30 23:04:13.585  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.585  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.585  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.586  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-30 23:04:13.586  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 ,when trying to connect
11-30 23:04:13.586  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 23:04:13.587  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 23:04:13.587  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 23:04:13.587  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-30 23:04:13.587  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 23:04:13.587  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 23:04:13.587  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 23:04:13.587  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 23:04:13.587  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 23:04:13.587  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 23:04:13.587  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-30 23:04:13.588  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-30 23:04:13.588  5646  5693 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 23:04:13.589  5646  5693 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-30 23:04:13.589  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-30 23:04:13.592  5646  5693 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 23:04:13.592  5646  5693 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-30 23:04:13.593  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndR,emoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-30 23:04:13.594  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-30 23:04:13.595  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-30 23:04:13.595  5646  5693 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-30 23:04:13.595  5646  5693 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-30 23:04:13.595  5646  5693 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-30 23:04:13.595  5646  5693 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 23:04:13.595  5646  5693 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-30 23:04:13.595  5646  5693 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-30 23:04:13.595  5646  5693 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 23:04:13.596  5646  5693 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-30 23:04:13.596  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-30 23:04:13.600  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-30 23:04:13.602  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-30 23:04:13.602  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-30 23:04:13.603  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-30 23:04:13.603  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-30 23:04:13.603  5646  5693 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-30 23:04:13.603  5646  5693 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 23:04:13.604  5646  5693 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-30 23:04:13.604  5646  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
11-30 23:04:13.604  5646  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,11-30 23:04:13.604  5646  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-30 23:04:13.604  5646  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
,11-30 23:04:13.604  5646  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-30 23:04:13.605  4712  4712 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32893]" dev="sockfs" ino=32893 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:13.604  5646  5729 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-30 23:04:13.604  5646  5729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 23:04:13.605  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-30 23:04:13.606  5646  5693 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-30 23:04:13.607  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-30 23:04:13.608  5646  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-30 23:04:13.605  4712  4712 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32893]" dev="sockfs" ino=32893 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:13.609  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-30 23:04:13.609  5646  5693 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-30 23:04:13.609  5646  5693 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-30 23:04:13.609  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 23:04:13.609  5646  5693 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-30 23:04:13.610  5646  5693 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-30 23:04:13.610  5646  5693 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-30 23:04:13.610  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-30 23:04:13.610  5646  5693 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-30 23:04:13.610  5646  5693 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-30 23:04:13.610  5646  5693 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-30 23:04:13.610  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-30 23:04:13.610  5646  5693 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-30 23:04:13.611  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-30 23:04:13.611  5646  5693 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 23:04:13.611  5646  5693 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-30 23:04:13.611  5646  5693 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-30 23:04:13.611  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-30 23:04:13.611  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.611  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.611  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.612  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 23:04:13.612  5646  5693 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 23:04:13.612  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 23:04:13.612  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 23:04:13.612  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 23:04:13.613  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 23:04:13.613  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 23:04:13.613  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 23:04:13.613  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 23:04:13.613  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 23:04:13.613  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 23:04:13.613  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 23:04:13.614  5646  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 23:04:13.614  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 23:04:13.614  5646  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 23:04:13.617  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-30 23:04:13.618  5646  5693 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 23:04:13.618  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-30 23:04:13.620  5646  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-30 23:04:13.615  4710  4710 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32187]" dev="sockfs" ino=32187 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:13.619  4710  4710 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32187]" dev="sockfs" ino=32187 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 23:04:13.622  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:13.622  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 23:04:13.623  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 23:04:13.623  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 23:04:13.623  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
,11-30 23:04:13.625  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:13.625  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.625  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 23:04:13.625  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 23:04:13.625  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 23:04:13.625  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-30 23:04:13.625  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:13.625  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-30 23:04:13.625  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.626  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 23:04:13.626  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:13.626  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.626  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.626  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.627  5646  5693 D BluetoothAdapter: STATE_ON
,11-30 23:04:13.629  4697  4712 D BtGatt.GattService: registerClient() - UUID=43d4720a-78a3-40ba-94e8-f6f42b931a3a
,11-30 23:04:13.629  4697  4773 D BtGatt.GattService: onClientRegistered() - UUID=43d4720a-78a3-40ba-94e8-f6f42b931a3a, clientIf=5
11-30 23:04:13.629  5646  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 23:04:13.630  4697  4775 D BtGatt.AdvertiseManager: message : 0
,11-30 23:04:13.632  4697  4775 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 23:04:13.641  4697  4773 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 23:04:13.646  4697  4773 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-30 23:04:13.646  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.647  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.647  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 23:04:13.647  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.647  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.647  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.647  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.647  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.647  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 23:04:13.648  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 23:04:13.648  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.649  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.649  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.649  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:13.649  5646  5693 I io.jxcore.node.ConnectionHelper: start: OK
11-30 23:04:13.650  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.650  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.650  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.650  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.653  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.653  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 23:04:13.653  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.653  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:13.653  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 23:04:14.150  5646  5723 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
11-30 23:04:14.150  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-30 23:04:14.151  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-30 23:04:14.151  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 23:04:14.151  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 23:04:14.152  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-30 23:04:14.152  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 23:04:14.152  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 23:04:14.152  5646  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-30 23:04:14.152  5646  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 23:04:14.152  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-30 23:04:14.152  5646  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 23:04:14.152  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 23:04:14.153  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-30 23:04:14.153  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-30 23:04:14.153  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-30 23:04:14.154  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 23:04:14.156  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d62d70f removed from the list
11-30 23:04:14.157  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-30 23:04:14.157  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 23:04:14.158  5646  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
11-30 23:04:14.158  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:14.158  5646  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-30 23:04:14.158  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 23:04:14.158  5646  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
11-30 23:04:14.158  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-30 23:04:14.159  4697  4908 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
11-30 23:04:14.159  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.159  5646  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
,11-30 23:04:14.159  5646  5729 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-30 23:04:14.159  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.159  5646  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-30 23:04:14.159  5646  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
,11-30 23:04:14.159  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.160  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.163  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:14.163  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-30 23:04:14.166  5646  5693 D BluetoothAdapter: STATE_ON
,11-30 23:04:14.166  5646  5693 D BluetoothLeScanner: could not find callback wrapper
11-30 23:04:14.166  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 23:04:14.167  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.167  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.167  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.168  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 23:04:14.168  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.170  4697  4775 D BtGatt.AdvertiseManager: message : 1
,11-30 23:04:14.171  4697  4775 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 23:04:14.178  4697  4773 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 23:04:14.178  4697  4773 D BtGatt.GattService: Client app is not null!
,11-30 23:04:14.179  4697  4710 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 23:04:14.179  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 23:04:14.179  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.180  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 23:04:14.180  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:14.180  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.180  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.180  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 23:04:14.180  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 23:04:14.181  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 23:04:14.181  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.182  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.183  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:14.183  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:14.183  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:14.183  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@536539c removed from the list
11-30 23:04:14.183  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 23:04:14.183  5646  5693 D io.jxcore.node.ConnectivityMonitor: stop
11-30 23:04:14.183  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 23:04:14.183  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-30 23:04:14.183  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:14.183  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:14.184  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 23:04:14.184  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 23:04:14.184  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:14.184  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 23:04:14.184  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:14.184  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:14.184  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 23:04:14.184  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 23:04:14.186  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 23:04:14.186  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:14.186  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-30 23:04:14.685  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 23:04:16.561   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-30 23:04:18.735  4697  4903 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-30 23:04:18.735  4697  4903 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-30 23:04:19.185  5646  5724 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,11-30 23:04:19.188  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-30 23:04:19.190  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-30 23:04:19.191  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-30 23:04:19.191  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-30 23:04:19.198  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-30 23:04:19.199  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 23:04:19.199  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 23:04:19.199  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-30 23:04:19.199  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-30 23:04:19.199  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 23:04:19.199  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-30 23:04:19.200  5646  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 23:04:19.201  5646  5732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 23:04:19.202  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-30 23:04:19.204  5646  5693 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-30 23:04:19.205  5646  5693 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-30 23:04:19.205  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-30 23:04:19.205  5646  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-30 23:04:19.205  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 23:04:19.206  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-30 23:04:19.202  4910  4910 W Binder_3: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[32195]" dev="sockfs" ino=32195 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:19.202  4910  4910 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32195]" dev="sockfs" ino=32195 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:19.207  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-30 23:04:19.217  5646  5693 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-30 23:04:19.217  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-30 23:04:19.217  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-30 23:04:19.218  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 23:04:19.218  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 23:04:19.218  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 23:04:19.218  5646  5732 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-30 23:04:19.218  5646  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 23:04:19.218  5646  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 23:04:19.219  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 23:04:19.219  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-30 23:04:19.219  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 23:04:19.220  5646  5693 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d62d70f not in the list
11-30 23:04:19.220  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 23:04:19.220  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-30 23:04:19.220  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 23:04:19.220  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 23:04:19.220  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:19.220  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-30 23:04:19.220  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 23:04:19.220  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:19.223  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:19.223  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:19.223  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:19.224  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:19.224  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 23:04:19.224  5646  5693 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@536539c not in the list
11-30 23:04:19.224  5646  5693 D io.jxcore.node.ConnectivityMonitor: stop
11-30 23:04:19.224  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-30 23:04:19.224  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:19.226  5646  5693 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-30 23:04:19.227  5646  5693 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-30 23:04:19.227  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 23:04:19.227  5646  5693 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-30 23:04:19.228  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 23:04:19.228  5646  5693 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-30 23:04:19.228  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-30 23:04:19.229  5646  5693 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-30 23:04:19.231  5646  5693 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-30 23:04:19.232  5646  5693 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-30 23:04:19.232  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-30 23:04:19.232  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-30 23:04:19.233  5646  5693 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-30 23:04:19.234  5646  5693 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-30 23:04:19.234  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-30 23:04:19.234  5646  5693 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-30 23:04:19.235  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-30 23:04:19.235  5646  5693 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-30 23:04:19.235  5646  5693 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-30 23:04:19.236  5646  5693 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-30 23:04:19.236  5646  5693 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-30 23:04:19.237  5646  5693 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-30 23:04:19.238  5646  5693 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-30 23:04:19.239  5646  5693 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-30 23:04:19.239  5646  5693 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-30 23:04:19.239  5646  5693 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-30 23:04:19.239  5646  5693 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-30 23:04:19.240  5646  5693 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-30 23:04:19.241  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-30 23:04:19.242  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1f52a added. We now have 3 listener(s)
,11-30 23:04:19.244  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-30 23:04:19.244  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 23:04:19.244  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 23:04:19.244  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 23:04:19.245  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac45f1b added. We now have 3 listener(s)
11-30 23:04:19.245  5646  5693 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 23:04:19.245  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 23:04:19.248  5646  5693 D BluetoothAdapter: enable(): BT is already enabled..!
,11-30 23:04:19.249   931   942 D WifiService: setWifiEnabled: true pid=5646, uid=10077
11-30 23:04:19.249   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-30 23:04:19.250  5646  5693 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
11-30 23:04:19.253  5646  5693 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-30 23:04:19.255  5646  5693 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-30 23:04:19.255  5646  5693 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-30 23:04:19.261  5646  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 23:04:19.261  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 23:04:19.261  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 23:04:19.261  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 23:04:19.261  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 23:04:19.261  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 23:04:19.261  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 23:04:19.261  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 23:04:19.261  5646  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-30 23:04:19.264  5646  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 23:04:19.264  4697  4769 D BluetoothAdapterState: Current state: ON, message: 23
11-30 23:04:19.264  4697  4769 D BluetoothAdapterProperties: Setting state to 13
11-30 23:04:19.264  4697  4769 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-30 23:04:19.265  4697  4769 D BluetoothAdapterProperties: onBluetoothDisable()
,11-30 23:04:19.266  4697  4769 I BluetoothAdapterState: Entering PendingCommandState
,11-30 23:04:19.266  4697  4697 D BluetoothMapService: onReceive
11-30 23:04:19.266  4697  4697 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-30 23:04:19.266  4697  4697 D BluetoothMapService: STATE_TURNING_OFF
11-30 23:04:19.267  4697  4697 D BluetoothMapService: MAP Service closeService in
11-30 23:04:19.267  4697  4697 D BluetoothMapMasInstance0: MAP Service shutdown
11-30 23:04:19.267  4697  4697 D ObexServerSockets0: shutdown(block = true)
11-30 23:04:19.267  4697  4921 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-30 23:04:19.268  4697  4697 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-30 23:04:19.268  4697  4697 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-30 23:04:19.268  4697  4922 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-30 23:04:19.269  4697  4697 I BtOppRfcommListener: stopping Accept Thread
11-30 23:04:19.269  4697  4908 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-30 23:04:19.269  4697  5329 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-30 23:04:19.270  4697  5329 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-30 23:04:19.292   931   944 I ActivityManager: Start proc 5735:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-30 23:04:19.292  4697  4773 D BluetoothAdapterProperties: Scan Mode:20
11-30 23:04:19.293  4697  4769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-30 23:04:19.296  4697  4697 D HeadsetService: Received stop request...Stopping profile...
,11-30 23:04:19.301   931   931 D BluetoothHeadset: Proxy object disconnected
,11-30 23:04:19.303  3187  5645 D BluetoothHeadset: Proxy object disconnected
,11-30 23:04:19.303  3187  3187 D HeadsetProfile: Bluetooth service disconnected
11-30 23:04:19.303  3804  3826 D BluetoothHeadset: Proxy object disconnected
11-30 23:04:19.304   931   931 D BluetoothHeadset: Proxy object disconnected
11-30 23:04:19.304   931   931 D BluetoothHeadset: Proxy object disconnected
11-30 23:04:19.305  4697  4697 D A2dpService: Received stop request...Stopping profile...
11-30 23:04:19.306  4697  4913 D A2dpStateMachine: Exit Disconnected: -1
11-30 23:04:19.306   931   931 D BluetoothA2dp: Proxy object disconnected
11-30 23:04:19.307  3187  3187 D BluetoothA2dp: Proxy object disconnected
,11-30 23:04:19.307  4697  4697 D HidService: Received stop request...Stopping profile...
11-30 23:04:19.307  4697  4697 D HidService: Stopping Bluetooth HidService
11-30 23:04:19.308  3187  3187 D BluetoothInputDevice: Proxy object disconnected
11-30 23:04:19.308  3187  3187 D HidProfile: Bluetooth service disconnected
11-30 23:04:19.308  4697  4697 D HealthService: Received stop request...Stopping profile...
11-30 23:04:19.309  4697  4697 V BluetoothAdapterState: isTurningOff()=true
11-30 23:04:19.309  4697  4697 V BluetoothAdapterState: isTurningOn()=false
11-30 23:04:19.309  4697  4697 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:19.309  4697  4697 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:19.310  4697  4697 D PanService: Received stop request...Stopping profile...
11-30 23:04:19.311  3187  3187 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-30 23:04:19.311  3187  3187 D PanProfile: Bluetooth service disconnected
11-30 23:04:19.312  4697  4697 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-30 23:04:19.312  4697  4697 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-30 23:04:19.312  4697  4903 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-30 23:04:19.312  4697  4903 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 23:04:19.312  4697  4903 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-30 23:04:19.313  4697  4773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-30 23:04:19.313  4697  4697 D BluetoothMapService: Received stop request...Stopping profile...
11-30 23:04:19.313  4697  4697 D BluetoothMapService: stop()
11-30 23:04:19.313  4697  4773 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-30 23:04:19.313  4697  4697 D BluetoothMapAppObserver: deinitObservers()
11-30 23:04:19.313  4697  4697 D BluetoothMapAppObserver: removeReceiver()
11-30 23:04:19.315  3187  3187 D BluetoothMap: Proxy object disconnected
,11-30 23:04:19.315  3187  3187 D MapProfile: Bluetooth service disconnected
11-30 23:04:19.316  4697  4697 V BluetoothAdapterState: isTurningOff()=true
11-30 23:04:19.316  4697  4697 V BluetoothAdapterState: isTurningOn()=false
11-30 23:04:19.316  4697  4697 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:19.316  4697  4697 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:19.317  4697  4903 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 23:04:19.318  4697  4903 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 23:04:19.318  4697  4903 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-30 23:04:19.318  4697  4903 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-30 23:04:19.318  4697  4903 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-30 23:04:19.318  4697  4697 D SapService: Received stop request...Stopping profile...
,11-30 23:04:19.318  4697  4903 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-30 23:04:19.318  4697  4697 V SapService: stop()
11-30 23:04:19.318  4697  4773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-30 23:04:19.323  4697  4697 V BluetoothAdapterState: isTurningOff()=true
11-30 23:04:19.323  4697  4697 V BluetoothAdapterState: isTurningOn()=false
11-30 23:04:19.323  4697  4697 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:19.323  4697  4697 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:19.323  4697  4697 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-30 23:04:19.324  4697  4697 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-30 23:04:19.324  4697  4773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-30 23:04:19.324  4697  4697 V BluetoothAdapterState: isTurningOff()=true
11-30 23:04:19.324  4697  4697 V BluetoothAdapterState: isTurningOn()=false
11-30 23:04:19.324  4697  4697 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:19.324  4697  4697 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:19.324  4697  4697 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-30 23:04:19.324  4697  4773 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-30 23:04:19.325  4697  4697 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-30 23:04:19.325  4697  4697 V BluetoothAdapterState: isTurningOff()=true
11-30 23:04:19.325  4697  4697 V BluetoothAdapterState: isTurningOn()=false
11-30 23:04:19.325  4697  4697 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:19.325  4697  4697 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:19.326  4697  4697 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-30 23:04:19.326  4697  4697 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-30 23:04:19.327  4697  4697 D BluetoothMapService: MAP Service closeService in
,11-30 23:04:19.327  4697  4697 V BluetoothAdapterState: isTurningOff()=true
11-30 23:04:19.327  4697  4697 V BluetoothAdapterState: isTurningOn()=false
11-30 23:04:19.327  4697  4697 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:19.327  4697  4697 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:19.328  4697  4697 D BluetoothMapService: cleanup()
,11-30 23:04:19.328  4697  4697 D BluetoothMapService: MAP Service closeService in
11-30 23:04:19.328  4697  4697 V BluetoothAdapterState: isTurningOff()=true
11-30 23:04:19.328  4697  4697 V BluetoothAdapterState: isTurningOn()=false
11-30 23:04:19.328  4697  4697 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:19.328  4697  4697 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:19.329  4697  4769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-30 23:04:19.329  4697  4769 D BluetoothAdapterProperties: Setting state to 15
11-30 23:04:19.329  4697  4769 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-30 23:04:19.329  4697  4769 I BluetoothAdapterState: Entering BleOnState
11-30 23:04:19.329   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 23:04:19.329   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-30 23:04:19.330  3804  3836 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-30 23:04:19.330  3187  4038 D BluetoothPan: onBluetoothStateChange on: false
11-30 23:04:19.331  3187  3201 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-30 23:04:19.331   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 23:04:19.332   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-30 23:04:19.332  3187  3200 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 23:04:19.332  3187  5645 D BluetoothMap: onBluetoothStateChange: up=false
11-30 23:04:19.332  3187  4038 D BluetoothPbap: onBluetoothStateChange: up=false
11-30 23:04:19.334  3187  3201 D BluetoothA2dp: onBluetoothStateChange: up=false
11-30 23:04:19.335  4697  4769 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-30 23:04:19.335  4697  4769 D BluetoothAdapterProperties: Setting state to 16
11-30 23:04:19.335  4697  4769 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-30 23:04:19.336  4697  4769 D BluetoothAdapterProperties: onBleDisable
11-30 23:04:19.336  4697  4769 I BluetoothAdapterState: Entering PendingCommandState
11-30 23:04:19.336  4697  4770 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-30 23:04:19.338  4697  4773 D BluetoothAdapterProperties: Scan Mode:20
11-30 23:04:19.338  4697  4903 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-30 23:04:19.338  4697  4903 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-30 23:04:19.342  5735  5735 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-30 23:04:19.356  5735  5735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-30 23:04:19.361   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@57d914c:true
,11-30 23:04:19.364  3628  3628 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 23:04:19.377   931  3456 I ActivityManager: Start proc 5747:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-30 23:04:19.384  5735  5735 D LocalBluetoothProfileManager: Adding local MAP profile
,11-30 23:04:19.388  5735  5735 D BluetoothMap: Create BluetoothMap proxy object
,11-30 23:04:19.404  5735  5735 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-30 23:04:19.416  5747  5747 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-30 23:04:19.420  5735  5735 D DockEventReceiver: finishStartingService: stopping service
,11-30 23:04:19.428   931  3777 I ActivityManager: Killing 4520:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-30 23:04:19.546  4697  4773 I bt_hci  : shut_down
,11-30 23:04:19.551  4697  4777 D bt_hwcfg: hw_epilog_process
,11-30 23:04:19.551  4697  4777 I bt_vendor: low_power_mode_cb
,11-30 23:04:19.553  4697  4777 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-30 23:04:19.553  4697  4777 I bt_vendor: epilog_cb
11-30 23:04:19.553  4697  4777 I bt_hci  : epilog_finished_callback
11-30 23:04:19.556  4697  4773 I bt_hci_h4: hal_close
11-30 23:04:19.556  4697  4773 I bt_userial_vendor: device fd = 54 close
,11-30 23:04:19.638  5747  5747 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.File.exists(File.java:361)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-30 23:04:19.638  5747  5747 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 23:04:19.638  5747  5747 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 23:04:19.638  5747  5747 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.e.b(PG:170)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 23:04:19.638  5747  5747 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.k.d(PG:583)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.e.b(PG:170)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 23:04:19.638  5747  5747 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.File.exists(File.java:361)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 23:04:19.638  5747  5747 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.File.exists(File.java:361)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 23:04:19.638  5747  5747 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 23:04:19.638  5747  5747 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 23:04:19.651  5735  5735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-30 23:04:19.657  3628  3628 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-30 23:04:19.666  4697  4770 D bt_stack_manager: event_shut_down_stack finished.
11-30 23:04:19.666  4697  4769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-30 23:04:19.667  5735  5735 D DockEventReceiver: finishStartingService: stopping service
11-30 23:04:19.668  4697  4697 D BtGatt.DebugUtils: handleDebugAction() action=null
11-30 23:04:19.668  4697  4769 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-30 23:04:19.668  4697  4697 D BtGatt.GattService: Received stop request...Stopping profile...
11-30 23:04:19.669  4697  4697 D BtGatt.GattService: stop()
11-30 23:04:19.669  4697  4697 D BtGatt.AdvertiseManager: advertise clients cleared
11-30 23:04:19.671  4697  4697 V BluetoothAdapterState: isTurningOff()=false
11-30 23:04:19.671  4697  4697 V BluetoothAdapterState: isTurningOn()=false
11-30 23:04:19.671  4697  4697 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:19.671  4697  4697 V BluetoothAdapterState: isBleTurningOff()=true
11-30 23:04:19.672  4697  4769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-30 23:04:19.672  4697  4769 D BluetoothAdapterProperties: Setting state to 10
11-30 23:04:19.672  4697  4769 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-30 23:04:19.673  4697  4769 I BluetoothAdapterState: Entering OffState
11-30 23:04:19.673   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-30 23:04:19.679  4697  4697 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-30 23:04:19.679  4697  4697 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-30 23:04:19.679  4697  4697 I BluetoothServiceJni: cleanupNative: return from cleanup
11-30 23:04:19.680  4697  4770 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-30 23:04:19.687   931   942 I ActivityManager: Killing 5148:com.google.android.deskclock/u0a66 (adj 15): empty #17
11-30 23:04:19.699  4697  4770 D bt_stack_manager: event_clean_up_stack finished.
,11-30 23:04:19.720  4697  4697 I art     : System.exit called, status: 0
,11-30 23:04:19.720  4697  4697 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-30 23:04:19.726  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 23:04:19.754   931   941 I ActivityManager: Process com.android.bluetooth (pid 4697) has died
,11-30 23:04:19.765  5646  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-30 23:04:19.765  5646  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 23:04:19.765  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 23:04:19.765  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 23:04:19.765  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 23:04:19.765  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-30 23:04:19.765  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 23:04:19.765  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 23:04:19.765  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 23:04:19.765  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-30 23:04:19.765  5646  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-30 23:04:19.765  5646  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 23:04:19.770  5646  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 23:04:19.782   931   948 I ActivityManager: Start proc 5780:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-30 23:04:19.837  5780  5780 D AdapterServiceConfig: Adding HeadsetService
,11-30 23:04:19.837  5780  5780 D AdapterServiceConfig: Adding A2dpService
11-30 23:04:19.837  5780  5780 D AdapterServiceConfig: Adding HidService
11-30 23:04:19.837  5780  5780 D AdapterServiceConfig: Adding HealthService
11-30 23:04:19.837  5780  5780 D AdapterServiceConfig: Adding PanService
11-30 23:04:19.838  5780  5780 D AdapterServiceConfig: Adding GattService
,11-30 23:04:19.838  5780  5780 D AdapterServiceConfig: Adding BluetoothMapService
11-30 23:04:19.838  5780  5780 D AdapterServiceConfig: Adding SapService
,11-30 23:04:19.845   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d30f180:true
,11-30 23:04:19.845  5780  5780 D BluetoothAdapterState: make() - Creating AdapterState
11-30 23:04:19.845  5747  5792 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
11-30 23:04:19.846  5780  5780 I bt_bluedroid: init
,11-30 23:04:19.847  5780  5793 I BluetoothAdapterState: Entering OffState
,11-30 23:04:19.848  5780  5794 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-30 23:04:19.848  5780  5794 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-30 23:04:19.848  5780  5794 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-30 23:04:19.848  5780  5794 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-30 23:04:19.849  5780  5780 I bt_bluedroid: get_profile_interface socket
,11-30 23:04:19.851  5780  5780 I bt_bluedroid: get_profile_interface sdp
,11-30 23:04:19.851  5780  5798 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-30 23:04:19.852  5780  5798 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-30 23:04:19.853  5780  5790 I bt_bluedroid: config_hci_snoop_log
,11-30 23:04:19.854   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-30 23:04:19.857  5780  5793 D BluetoothAdapterState: Current state: OFF, message: 0
,11-30 23:04:19.857  5780  5793 D BluetoothAdapterProperties: Setting state to 14
11-30 23:04:19.857  5780  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-30 23:04:19.858  5780  5793 D BluetoothBondStateMachine: make
,11-30 23:04:19.860  5780  5799 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-30 23:04:19.862  5780  5793 I BluetoothAdapterState: Entering PendingCommandState
11-30 23:04:19.862  5780  5780 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-30 23:04:19.864  5780  5780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb9c138
,11-30 23:04:19.864  5780  5780 D BtGatt.DebugUtils: handleDebugAction() action=null
11-30 23:04:19.864  5780  5780 D BtGatt.GattService: Received start request. Starting profile...
11-30 23:04:19.864  5780  5780 D BtGatt.GattService: start()
,11-30 23:04:19.864  5780  5780 I bt_bluedroid: get_profile_interface gatt
11-30 23:04:19.865  5780  5780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb9c138
11-30 23:04:19.865  5780  5780 D BtGatt.AdvertiseManager: advertise manager created
,11-30 23:04:19.868  5780  5780 V BluetoothAdapterState: isTurningOff()=false
,11-30 23:04:19.868  5780  5780 V BluetoothAdapterState: isTurningOn()=false
11-30 23:04:19.868  5780  5780 V BluetoothAdapterState: isBleTurningOn()=true
11-30 23:04:19.868  5780  5780 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 23:04:19.868  5780  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-30 23:04:19.869  5780  5793 I bt_bluedroid: bt_bluedroid
11-30 23:04:19.869  5780  5794 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-30 23:04:19.869  5780  5794 I bt_hci  : start_up
,11-30 23:04:19.874  5780  5794 I bt_vendor: alloc value 0xf3ff5871
,11-30 23:04:19.874  5780  5794 I bt_vendor: init
11-30 23:04:19.874  5780  5794 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-30 23:04:19.874  5780  5794 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-30 23:04:19.899  5747  5765 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-30 23:04:19.907   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ffd70f1:true
,11-30 23:04:19.983  5780  5794 D bt_hci  : start_up starting async portion
,11-30 23:04:19.983  5780  5802 I bt_hci  : event_finish_startup
11-30 23:04:19.983  5780  5802 I bt_hci_h4: hal_open
11-30 23:04:19.983  5780  5802 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-30 23:04:19.984  5780  5802 I bt_userial_vendor: device fd = 54 open
,11-30 23:04:19.982  5805  5805 W irq/448-msm_hs_: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 23:04:19.996  5780  5802 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-30 23:04:19.998  5780  5802 D bt_hwcfg: Chipset BCM4358A3
,11-30 23:04:19.998  5780  5802 D bt_hwcfg: Target name = [BCM4358A3]
11-30 23:04:19.998  5780  5802 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-30 23:04:20.271  5780  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-30 23:04:20.314  3628  5810 V NQFileLogger: [147] e.a: about to write to file
,11-30 23:04:20.318  3628  5810 V ProcessReports: [147] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,11-30 23:04:20.343  5780  5802 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-30 23:04:20.343  5780  5802 D bt_hwcfg: Settlement delay -- 100 ms
11-30 23:04:20.343  5780  5802 I bt_hwcfg: Setting fw settlement delay to 100 
,11-30 23:04:20.438   931  2993 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 23:04:20.468  5780  5802 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-30 23:04:20.468  5780  5802 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-30 23:04:20.469  5780  5802 I bt_hwcfg: vendor lib fwcfg completed
,11-30 23:04:20.470  5780  5802 I bt_vendor: firmware callback
,11-30 23:04:20.470  5780  5802 I bt_hci  : firmware_config_callback
,11-30 23:04:20.478  5780  5812 I bt_btu  : btu_task pending for preload complete event
,11-30 23:04:20.479  5780  5812 I bt_btu_task: Bluetooth chip preload is complete
11-30 23:04:20.479  5780  5812 I bt_btu  : btu_task received preload complete event
,11-30 23:04:20.485  5780  5812 I         : BTE_InitTraceLevels -- TRC_HCI
,11-30 23:04:20.485  5780  5812 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_AVDT
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_AVRC
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_A2D
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_BNEP
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_BTM
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_GAP
,11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_PAN
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_SDP
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_GATT
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_SMP
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-30 23:04:20.486  5780  5812 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-30 23:04:20.565  5780  5812 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f73549
,11-30 23:04:20.565  5780  5812 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f73549 
,11-30 23:04:20.585  5780  5798 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-30 23:04:20.587  5780  5798 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-30 23:04:20.588  5780  5798 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-30 23:04:20.590  5780  5798 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-30 23:04:20.592  5780  5798 D BluetoothAdapterProperties: Scan Mode:20
,11-30 23:04:20.592  5780  5798 D BluetoothAdapterProperties: Discoverable Timeout:120
11-30 23:04:20.593  5780  5798 D bt_hci  : do_postload posting postload work item
,11-30 23:04:20.593  5780  5802 I bt_hci  : event_postload
,11-30 23:04:20.593  5780  5802 I bt_vendor: sco_config_cb
11-30 23:04:20.593  5780  5802 I bt_hci  : sco_config_callback postload finished.
11-30 23:04:20.595  5780  5798 D bt_bte_conf: Device ID record 1 : primary
11-30 23:04:20.595  5780  5798 D bt_bte_conf:   vendorId            = 000f
11-30 23:04:20.595  5780  5798 D bt_bte_conf:   vendorIdSource      = 0001
11-30 23:04:20.595  5780  5798 D bt_bte_conf:   product             = 1200
11-30 23:04:20.595  5780  5798 D bt_bte_conf:   version             = 1436
11-30 23:04:20.595  5780  5798 D bt_bte_conf:   clientExecutableURL = 
,11-30 23:04:20.595  5780  5798 D bt_bte_conf:   serviceDescription  = 
11-30 23:04:20.595  5780  5798 D bt_bte_conf:   documentationURL    = 
11-30 23:04:20.596  5780  5798 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-30 23:04:20.596  5780  5794 D bt_stack_manager: event_start_up_stack finished
,11-30 23:04:20.597  5780  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-30 23:04:20.598  5780  5793 D BluetoothAdapterProperties: Setting state to 15
11-30 23:04:20.598  5780  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-30 23:04:20.599  5780  5793 I BluetoothAdapterState: Entering BleOnState
,11-30 23:04:20.600  5780  5802 I bt_vendor: low_power_mode_cb
11-30 23:04:20.602  5780  5793 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-30 23:04:20.602  5780  5793 D BluetoothAdapterProperties: Setting state to 11
11-30 23:04:20.602  5780  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-30 23:04:20.608  5780  5780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb9c138
11-30 23:04:20.610  5780  5780 D HeadsetService: Received start request. Starting profile...
11-30 23:04:20.613  5780  5780 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-30 23:04:20.614  5780  5780 D HeadsetStateMachine: make
,11-30 23:04:20.622  5780  5780 D HeadsetStateMachine: max_hf_connections = 1
,11-30 23:04:20.623  5780  5780 I bt_bluedroid: get_profile_interface handsfree
11-30 23:04:20.623  5780  5798 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-30 23:04:20.623  5780  5798 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-30 23:04:20.624  5780  5793 I BluetoothAdapterState: Entering PendingCommandState
,11-30 23:04:20.628  5780  5780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb9c138
,11-30 23:04:20.628  5780  5780 D A2dpService: Received start request. Starting profile...
,11-30 23:04:20.629  5780  5780 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-30 23:04:20.630  5780  5780 I bt_bluedroid: get_profile_interface avrcp
,11-30 23:04:20.636  5780  5780 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-30 23:04:20.636  5780  5780 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-30 23:04:20.636  5780  5780 D A2dpStateMachine: make
,11-30 23:04:20.637  5780  5780 I bt_bluedroid: get_profile_interface a2dp
,11-30 23:04:20.638  5780  5798 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-30 23:04:20.639  5780  5820 D A2dpStateMachine: Enter Disconnected: -2
11-30 23:04:20.641  5780  5780 I BluetoothHidServiceJni: classInitNative: succeeds
11-30 23:04:20.642  5780  5780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb9c138
11-30 23:04:20.642  3628  3628 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 23:04:20.643  5780  5780 D HidService: Received start request. Starting profile...
,11-30 23:04:20.644  5780  5780 I bt_bluedroid: get_profile_interface hidhost
11-30 23:04:20.644  5780  5780 D HidService: setHidService(): set to: null
11-30 23:04:20.644  5780  5798 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f5456d
11-30 23:04:20.644  5780  5798 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-30 23:04:20.644  5780  5780 I BluetoothHealthServiceJni: classInitNative: succeeds
11-30 23:04:20.645  5780  5780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb9c138
11-30 23:04:20.646  5780  5780 D HealthService: Received start request. Starting profile...
11-30 23:04:20.646  5735  5735 D BluetoothInputDevice: Proxy object connected
11-30 23:04:20.647  5735  5735 D HidProfile: Bluetooth service connected
11-30 23:04:20.647  5780  5780 I bt_bluedroid: get_profile_interface health
11-30 23:04:20.649  5780  5780 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-30 23:04:20.650  5780  5780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb9c138
,11-30 23:04:20.651  5780  5780 D PanService: Received start request. Starting profile...
,11-30 23:04:20.652  5780  5780 D BluetoothPanServiceJni: initializeNative(L110): pan
11-30 23:04:20.652  5780  5780 I bt_bluedroid: get_profile_interface pan
11-30 23:04:20.652  5780  5798 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-30 23:04:20.655  5735  5735 D BluetoothPan: BluetoothPAN Proxy object connected
11-30 23:04:20.656  5780  5780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb9c138
11-30 23:04:20.657  5735  5735 D PanProfile: Bluetooth service connected
11-30 23:04:20.658  5735  5735 D BluetoothMap: Proxy object connected
11-30 23:04:20.658  5780  5780 D BluetoothMapService: Received start request. Starting profile...
11-30 23:04:20.658  5735  5735 D MapProfile: Bluetooth service connected
11-30 23:04:20.658  5780  5780 D BluetoothMapService: start()
11-30 23:04:20.658  5735  5735 D BluetoothMap: getConnectedDevices()
11-30 23:04:20.659  5735  5735 D BluetoothMap: Bluetooth is Not enabled
11-30 23:04:20.661  5780  5780 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-30 23:04:20.662  5780  5780 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-30 23:04:20.662  5780  5780 D BluetoothMapAppObserver: createReceiver()
,11-30 23:04:20.663  5780  5780 D BluetoothMapAppObserver: initObservers()
11-30 23:04:20.663  5780  5780 D BluetoothMapAppObserver: getEnabledAccountItems()
11-30 23:04:20.671  5780  5780 V SapService: SapBinder()
11-30 23:04:20.671  5780  5780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb9c138
11-30 23:04:20.671  5780  5780 D SapService: Received start request. Starting profile...
11-30 23:04:20.671  5780  5780 V SapService: start()
11-30 23:04:20.673  5780  5780 V BluetoothAdapterState: isTurningOff()=false
11-30 23:04:20.673  5780  5780 V BluetoothAdapterState: isTurningOn()=true
11-30 23:04:20.673  5780  5780 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:20.673  5780  5780 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:20.673  5780  5780 V BluetoothAdapterState: isTurningOff()=false
11-30 23:04:20.673  5780  5780 V BluetoothAdapterState: isTurningOn()=true
11-30 23:04:20.673  5780  5780 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:20.673  5780  5817 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-30 23:04:20.674  5780  5780 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:20.674  5780  5780 V BluetoothAdapterState: isTurningOff()=false
11-30 23:04:20.674  5780  5780 V BluetoothAdapterState: isTurningOn()=true
11-30 23:04:20.674  5780  5780 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:20.674  5780  5780 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:20.674  5780  5780 V BluetoothAdapterState: isTurningOff()=false
11-30 23:04:20.675  5780  5780 V BluetoothAdapterState: isTurningOn()=true
11-30 23:04:20.675  5780  5780 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:20.675  5780  5780 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:20.675  5780  5780 V BluetoothAdapterState: isTurningOff()=false
11-30 23:04:20.675  5780  5780 V BluetoothAdapterState: isTurningOn()=true
11-30 23:04:20.675  5780  5780 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:20.675  5780  5780 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:20.675  5780  5780 V BluetoothAdapterState: isTurningOff()=false
11-30 23:04:20.675  5780  5780 V BluetoothAdapterState: isTurningOn()=true
11-30 23:04:20.675  5780  5780 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:20.676  5780  5780 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:20.677  5780  5780 V BluetoothAdapterState: isTurningOff()=false
11-30 23:04:20.677  5780  5780 V BluetoothAdapterState: isTurningOn()=true
11-30 23:04:20.677  5780  5780 V BluetoothAdapterState: isBleTurningOn()=false
11-30 23:04:20.677  5780  5780 V BluetoothAdapterState: isBleTurningOff()=false
11-30 23:04:20.677  5780  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-30 23:04:20.677  5780  5793 D BluetoothAdapterProperties: ScanMode =  20
11-30 23:04:20.677  5780  5793 D BluetoothAdapterProperties: State =  11
11-30 23:04:20.679  5780  5798 D BluetoothAdapterProperties: Scan Mode:21
11-30 23:04:20.679  5780  5793 D BluetoothAdapterProperties: Setting state to 12
11-30 23:04:20.680  5780  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-30 23:04:20.680  5780  5798 D BluetoothAdapterProperties: Discoverable Timeout:120
11-30 23:04:20.680   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 23:04:20.680  5780  5793 I BluetoothAdapterState: Entering OnState
11-30 23:04:20.680  5735  5745 D BluetoothPbap: onBluetoothStateChange: up=true
11-30 23:04:20.681   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 23:04:20.682  3804  3836 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 23:04:20.682  5735  5746 D BluetoothPan: onBluetoothStateChange on: true
11-30 23:04:20.682  5735  5745 D BluetoothMap: onBluetoothStateChange: up=true
11-30 23:04:20.683  3187  4038 D BluetoothPan: onBluetoothStateChange on: true
11-30 23:04:20.684  3187  3187 D BluetoothPan: BluetoothPAN Proxy object connected
11-30 23:04:20.684  3187  5645 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-30 23:04:20.684  3187  3187 D PanProfile: Bluetooth service connected
11-30 23:04:20.685   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 23:04:20.685  3187  3187 D BluetoothInputDevice: Proxy object connected
11-30 23:04:20.685  3187  3187 D HidProfile: Bluetooth service connected
11-30 23:04:20.685   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
11-30 23:04:20.686  3187  3200 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 23:04:20.687   931   931 D BluetoothA2dp: Proxy object connected
11-30 23:04:20.687  5735  5746 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-30 23:04:20.688  3187  5645 D BluetoothMap: onBluetoothStateChange: up=true
11-30 23:04:20.689  3187  3187 D BluetoothMap: Proxy object connected
11-30 23:04:20.689  3187  3201 D BluetoothPbap: onBluetoothStateChange: up=true
11-30 23:04:20.689  3187  3187 D MapProfile: Bluetooth service connected
11-30 23:04:20.689  3187  3187 D BluetoothMap: getConnectedDevices()
11-30 23:04:20.691  5780  5780 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-30 23:04:20.691  3187  3200 D BluetoothA2dp: onBluetoothStateChange: up=true
11-30 23:04:20.692  5780  5780 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-30 23:04:20.693  3187  3187 D BluetoothA2dp: Proxy object connected
11-30 23:04:20.693  5780  5780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 23:04:20.694   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
11-30 23:04:20.696  5780  5780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 23:04:20.697  5780  5780 D ObexServerSockets: Succeed to create listening sockets 
11-30 23:04:20.697  5780  5780 D ObexServerSockets0: startAccept()
11-30 23:04:20.697  5780  5780 D ObexServerSockets0: prepareForNewConnect()
11-30 23:04:20.699  5780  5780 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-30 23:04:20.699  5735  5735 D LocalBluetoothProfileManager: Adding local A2DP profile
11-30 23:04:20.699  5780  5780 D BluetoothSdpJni: SDP Create record success - handle: 0
11-30 23:04:20.700  5780  5827 D ObexServerSockets0: Accepting socket connection...
11-30 23:04:20.700  5780  5780 D BluetoothMapService: onReceive
11-30 23:04:20.700  5780  5780 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-30 23:04:20.700  5780  5780 D BluetoothMapService: STATE_ON
11-30 23:04:20.701  5780  5828 D ObexServerSockets0: Accepting socket connection...
11-30 23:04:20.702  5735  5735 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-30 23:04:20.703  5780  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 23:04:20.704  5780  5829 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-30 23:04:20.704  5780  5829 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-30 23:04:20.708  5735  5735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-30 23:04:20.710  5735  5735 D BluetoothA2dp: Proxy object connected
,11-30 23:04:20.717  5735  5735 D DockEventReceiver: finishStartingService: stopping service
,11-30 23:04:20.720  3628  3628 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 23:04:20.724  5780  5780 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-30 23:04:20.724  3187  3187 D BluetoothPbap: Proxy object connected
11-30 23:04:20.724  5780  5780 D ObexServerSockets0: prepareForNewConnect()
11-30 23:04:20.724  3187  3187 D PbapServerProfile: Bluetooth service connected
,11-30 23:04:20.724  5735  5735 D BluetoothPbap: Proxy object connected
11-30 23:04:20.725  5735  5735 D PbapServerProfile: Bluetooth service connected
,11-30 23:04:20.727  5780  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 23:04:20.743  5780  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 23:04:20.744  5780  5837 I BtOppRfcommListener: Accept thread started.
,11-30 23:04:20.774  5646  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 23:04:20.774  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 23:04:20.774  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 23:04:20.774  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 23:04:20.774  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 23:04:20.774  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 23:04:20.774  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 23:04:20.774  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 23:04:20.774  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-30 23:04:20.775  5646  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 23:04:20.776  5646  5693 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-30 23:04:20.778   931  3906 D WifiService: setWifiEnabled: false pid=5646, uid=10077
11-30 23:04:20.778   931  3906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-30 23:04:20.780   931  2993 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-30 23:04:20.780   931  2993 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-30 23:04:20.780   931  2993 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-30 23:04:20.780   931  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-30 23:04:20.780  5646  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 23:04:20.782   931   931 D BluetoothHeadset: Proxy object connected
,11-30 23:04:20.783  3187  4038 D BluetoothHeadset: Proxy object connected
11-30 23:04:20.783  3187  3187 D HeadsetProfile: Bluetooth service connected
,11-30 23:04:20.784  3804  4159 D BluetoothHeadset: Proxy object connected
11-30 23:04:20.784   931   931 D BluetoothHeadset: Proxy object connected
11-30 23:04:20.784   931   931 D BluetoothHeadset: Proxy object connected
11-30 23:04:20.786   931   948 D BluetoothHeadset: Proxy object connected
11-30 23:04:20.787  3187  3201 D BluetoothHeadset: Proxy object connected
,11-30 23:04:20.787  3187  3187 D HeadsetProfile: Bluetooth service connected
,11-30 23:04:20.791   931  5399 D DhcpClient: Clearing IP address
,11-30 23:04:20.791   507   930 D CommandListener: Clearing all IP addresses on wlan0
,11-30 23:04:20.793   507   930 D CommandListener: Setting iface cfg
,11-30 23:04:20.798  3628  5453 V NativeCrypto: Read error: ssl=0x7f9b109380: I/O error during system call, Connection timed out
,11-30 23:04:20.801  3628  5453 V NativeCrypto: SSL shutdown failed: ssl=0x7f9b109380: I/O error during system call, Broken pipe
,11-30 23:04:20.803   931  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-30 23:04:20.803   931  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-30 23:04:20.805  5735  5745 D BluetoothHeadset: Proxy object connected
11-30 23:04:20.808   931   931 D RttService: SCAN_AVAILABLE : 1
,11-30 23:04:20.808   931  3112 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-30 23:04:20.809   541   541 E Parcel  : Reading a NULL string not supported here.
11-30 23:04:20.809  5735  5735 D HeadsetProfile: Bluetooth service connected
11-30 23:04:20.810   931  2996 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-30 23:04:20.812  3770  3924 W QCNEJ   : |CORE| network lost: 100
11-30 23:04:20.814   931  2993 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-30 23:04:20.813  3770  3924 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-30 23:04:20.820   931  2993 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-30 23:04:20.822   931  5400 D DhcpClient: Receive thread stopped
,11-30 23:04:20.838   507   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 23:04:20.856   507   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 23:04:20.856   507   930 D CommandListener: Clearing all IP addresses on wlan0
,11-30 23:04:20.856   931  2996 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-30 23:04:20.857   931  2996 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-30 23:04:20.857   507   930 D TetherController: Setting IP forward enable = 0
11-30 23:04:20.858   931  2993 D DhcpClient: doQuit
11-30 23:04:20.858   931  2993 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-30 23:04:20.859   931  5399 D DhcpClient: onQuitting
11-30 23:04:20.859  3486  3486 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-30 23:04:20.859   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-30 23:04:20.867  5282  5282 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@870fe55 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-30 23:04:20.869  4014  4014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-30 23:04:20.872  3894  3894 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-30 23:04:20.875  3894  3894 D SystemUpdateService: onCreate
11-30 23:04:20.875  5072  5096 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-30 23:04:20.875  5072  5096 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-30 23:04:20.875  5072  5096 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-30 23:04:20.875  5072  5096 E SarControlService: no key has been found,reset the power
11-30 23:04:20.876  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-30 23:04:20.876  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-30 23:04:20.876  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-30 23:04:20.876  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 23:04:20.876  5097  5097 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-30 23:04:20.877  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-30 23:04:20.877  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-30 23:04:20.877  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-30 23:04:20.878  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-30 23:04:20.878  5097  5097 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-30 23:04:20.879  3894  3894 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-30 23:04:20.881  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e1d923 HexData = [00000000ea03000000000000ffffffff]
11-30 23:04:20.882  3894  5851 I SystemUpdateService: active receiver: enabled
11-30 23:04:20.882  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 23:04:20.882  5097  5111 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-30 23:04:20.884  3486  3486 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-30 23:04:20.884  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 23:04:20.884  5072  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-30 23:04:20.885  3894  5851 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-30 23:04:20.886  3894  5851 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-30 23:04:20.886  3894  5851 I SystemUpdateService: now status is 0 (complete)
11-30 23:04:20.887  3894  5851 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-30 23:04:20.887  3894  5851 I SystemUpdateService: file has been verified
11-30 23:04:20.887  3894  5851 I SystemUpdateService: OTA package size = 21989297
11-30 23:04:20.888  3894  3894 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-30 23:04:20.889  3894  5425 I iu.UploadsManager: num queued entries: 0
,11-30 23:04:20.889  3894  5851 I SystemUpdateService: showing system update notification
11-30 23:04:20.890  3894  5425 I iu.UploadsManager: num updated entries: 0
11-30 23:04:20.891  3486  3486 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-30 23:04:20.889  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e1d923 HexData = [00000000eb03000000000000ffffffff]
11-30 23:04:20.893  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 23:04:20.893  5097  5111 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-30 23:04:20.893  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 23:04:20.894  5072  5082 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-30 23:04:20.897   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-30 23:04:20.892  3894  5425 I iu.SyncManager: NEXT; no task
,11-30 23:04:20.904  3894  3894 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-30 23:04:20.908  3894  3894 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-30 23:04:20.908  3894  3894 D SystemUpdateService: onDestroy
,11-30 23:04:20.917   507   923 W SocketClient: write error (Broken pipe)
,11-30 23:04:20.917   507   923 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-30 23:04:20.918   507   923 W SocketListener: Error sending broadcast (Broken pipe)
11-30 23:04:20.919   931   941 I ActivityManager: Start proc 5856:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-30 23:04:20.941  3486  3486 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-30 23:04:20.951  5856  5856 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-30 23:04:20.953  3486  3486 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-30 23:04:20.954  5856  5856 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-30 23:04:20.954   507   923 W SocketClient: write error (Broken pipe)
11-30 23:04:20.954   507   923 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-30 23:04:20.954   507   923 W SocketListener: Error sending broadcast (Broken pipe)
,11-30 23:04:20.960  5856  5856 D SprintDMHelper: simOperator: 
11-30 23:04:20.960  5856  5856 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-30 23:04:20.972   931  3456 I ActivityManager: Start proc 5868:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-30 23:04:21.053  5047  5882 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-30 23:04:21.064   931  3906 I ActivityManager: Start proc 5883:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-30 23:04:21.066   931  2993 D wifi    : In wifi stop Hal
11-30 23:04:21.066   931  2993 D wifi    : halHandle = 0x7f8896e080, mVM = 0x7fa4f8d140, mCls = 0x100a02
,11-30 23:04:21.067   931  3484 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-30 23:04:21.067   931  3484 D WifiHAL : Got a signal to exit!!!
11-30 23:04:21.067   931  3484 I WifiHAL : Exit wifi_event_loop
11-30 23:04:21.067   931  2993 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-30 23:04:21.068   931  2993 E WifiHAL : Event processing terminated
,11-30 23:04:21.068   931  2993 D wifi    : In wifi cleaned up handler
,11-30 23:04:21.068   931  2993 I WifiHAL : Internal cleanup completed
11-30 23:04:21.069  5047  5047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-30 23:04:21.069   931  3194 I ActivityManager: Killing 5475:com.qualcomm.timeservice/1000 (adj 15): empty #17
11-30 23:04:21.073  4102  4265 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-30 23:04:21.096   931  3484 D wifi    : set interface wlan0 flags (DOWN)
11-30 23:04:21.097   931  2993 D WifiNative-HAL: HAL event thread stopped successfully
11-30 23:04:21.097   507   923 W SocketClient: write error (Broken pipe)
,11-30 23:04:21.097   507   923 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 down'
,11-30 23:04:21.097   507   923 W SocketListener: Error sending broadcast (Broken pipe)
,11-30 23:04:21.110  5883  5883 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-30 23:04:21.117   931   941 I ActivityManager: Killing 5282:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-30 23:04:21.282  5646  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 23:04:21.282  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 23:04:21.282  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 23:04:21.282  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-30 23:04:21.282  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 23:04:21.282  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-30 23:04:21.282  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-30 23:04:21.282  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-30 23:04:21.282  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-30 23:04:21.284  5646  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-30 23:04:21.286   931  3457 D WifiService: setWifiEnabled: true pid=5646, uid=10077
11-30 23:04:21.286   931  3457 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 23:04:21.288  5646  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 23:04:21.299   931   948 D Tethering: InitialState.processMessage what=4
,11-30 23:04:21.304   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-30 23:04:21.790   931  3906 D WifiService: setWifiEnabled: true pid=5646, uid=10077
,11-30 23:04:21.790   931  3906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 23:04:21.955   507   930 E Netd    : netlink response contains error (No such file or directory)
,11-30 23:04:21.957   931  2996 E NetdConnector: NDC Command {114 network destroy 100} took too long (1099ms)
,11-30 23:04:21.957   931  2996 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-30 23:04:21.959   931  2991 E NetdConnector: NDC Command {115 bandwidth setglobalalert 2097152} took too long (1092ms)
,11-30 23:04:21.960   507   930 D SoftapController: Softap fwReload - Ok
,11-30 23:04:21.960   931  2993 E NetdConnector: NDC Command {116 softap fwreload wlan0 STA} took too long (663ms)
,11-30 23:04:21.961   931  2990 E NetdConnector: NDC Command {117 bandwidth gettetherstats} took too long (657ms)
,11-30 23:04:21.963   507   930 D TetherController: Setting IP forward enable = 0
,11-30 23:04:21.966   507   930 D CommandListener: Setting iface cfg
,11-30 23:04:21.967   507   930 D CommandListener: Trying to bring down wlan0
,11-30 23:04:21.970   507   930 D CommandListener: Clearing all IP addresses on wlan0
,11-30 23:04:21.974   931  2993 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-30 23:04:22.292   931  3456 D WifiService: setWifiEnabled: true pid=5646, uid=10077
11-30 23:04:22.295   931  3456 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 23:04:22.578   931  2993 D wifi    : set interface wlan0 flags (UP)
,11-30 23:04:22.578   931  2993 I WifiHAL : Initializing wifi
,11-30 23:04:22.578   931  2993 I WifiHAL : Creating socket
11-30 23:04:22.584   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-30 23:04:22.589   931  2993 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-30 23:04:22.589   931  2993 D wifi    : Did set static halHandle = 0x7f8896e080
11-30 23:04:22.589   931  2993 D wifi    : halHandle = 0x7f8896e080, mVM = 0x7fa4f8d140, mCls = 0x18be
11-30 23:04:22.590   931  2993 D wifi    : array field set
11-30 23:04:22.590   931  2993 I WifiNative-HAL: interface[0] = wlan0
,11-30 23:04:22.593   931  5903 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547752435840
,11-30 23:04:22.593   931  5903 D wifi    : waitForHalEvents called, vm = 0x7fa4f8d140, obj = 0x18be, env = 0x7f8a339bc0
,11-30 23:04:22.676  5904  5904 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-30 23:04:22.694   931  2993 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-30 23:04:22.759  5904  5904 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-30 23:04:22.768  5904  5904 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-30 23:04:22.768  5904  5904 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-30 23:04:22.782   931  2993 D WifiConfigStore: Loading config and enabling all networks 
,11-30 23:04:22.798   931  2993 D WifiConfigStore: loaded 0 passpoint configs
,11-30 23:04:22.799   931  2993 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-30 23:04:22.800   931  2993 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-30 23:04:22.800   931  2993 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-30 23:04:22.801   931  2993 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-30 23:04:22.801   931  2993 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-30 23:04:22.802   931  2993 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-30 23:04:22.802   931  2993 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-30 23:04:22.802   931  2993 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-30 23:04:22.802   931  2993 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-30 23:04:22.802   931  2993 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-30 23:04:22.802   931  2993 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-30 23:04:22.802   931  2993 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-30 23:04:22.802  5646  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 23:04:22.802  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 23:04:22.802  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 23:04:22.802  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 23:04:22.802  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 23:04:22.802  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-30 23:04:22.802  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-30 23:04:22.802  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-30 23:04:22.802  5646  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-30 23:04:22.805   931  2993 D WifiNative-HAL: Setting external_sim to 1
,11-30 23:04:22.805   931  2993 D wifi    : setting dfs flag to true, 0x7f8d47eb20
11-30 23:04:22.805   931  2993 D WifiStateMachine: Setting OUI to DA-A1-19
,11-30 23:04:22.805  5047  5047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-30 23:04:22.805   931  2993 D wifi    : setting scan oui 0x7f8d47eb20
11-30 23:04:22.805   931  2993 D WifiHAL : Sending mac address OUI
,11-30 23:04:22.807  5646  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-30 23:04:22.808   931  2993 E native  : do suspend false
,11-30 23:04:22.809  5646  5693 D BluetoothAdapter: enable(): BT is already enabled..!
,11-30 23:04:22.809   931  3906 D WifiService: setWifiEnabled: true pid=5646, uid=10077
11-30 23:04:22.810   931  3906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-30 23:04:22.810  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-30 23:04:22.810  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 23:04:22.810  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-30 23:04:22.810  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1f52a removed from the list
11-30 23:04:22.810  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 23:04:22.811  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac45f1b removed from the list
11-30 23:04:22.811  5646  5693 D io.jxcore.node.ConnectivityMonitor: stop
,11-30 23:04:22.812  5646  5693 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-30 23:04:22.814  5646  5693 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-30 23:04:22.814   931  2993 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-30 23:04:22.814  5646  5693 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-30 23:04:22.814   931   931 D RttService: SCAN_AVAILABLE : 3
11-30 23:04:22.814   931  3112 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-30 23:04:22.815  5646  5693 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
11-30 23:04:22.817   507   930 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-30 23:04:22.819  5646  5693 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-30 23:04:22.819   507   930 D CommandListener: Setting iface cfg
,11-30 23:04:22.819  5646  5693 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-30 23:04:22.820   931  2992 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-30 23:04:22.820   931  2992 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
11-30 23:04:22.821  5646  5693 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-30 23:04:22.821  5646  5693 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-30 23:04:22.822  5646  5693 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-30 23:04:22.824  5646  5693 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-30 23:04:22.824  5646  5693 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@796e477 Bundle[{}]
11-30 23:04:22.824   931  2992 D WifiNative-HAL: p2pGetDeviceAddress
11-30 23:04:22.825  5646  5693 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-30 23:04:22.825  5646  5693 I io.jxcore.node.LifeCycleMonitor: start: OK
11-30 23:04:22.826  5646  5693 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-30 23:04:22.827  5646  5693 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-30 23:04:22.827  5646  5693 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-30 23:04:22.828  5646  5693 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-30 23:04:22.828  5646  5693 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-30 23:04:22.828   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=182348 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=10 mControllerEnergyUsed=38 }
11-30 23:04:22.828   931  2992 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
11-30 23:04:22.828  5646  5693 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-30 23:04:22.828  5646  5693 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-30 23:04:22.829  5646  5693 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-30 23:04:22.829  5646  5693 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-30 23:04:22.830  5646  5693 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-30 23:04:22.831  5646  5693 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
11-30 23:04:22.831  5646  5693 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-30 23:04:22.831  5646  5693 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-30 23:04:22.831  5646  5693 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-30 23:04:22.832  5646  5693 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-30 23:04:22.832  5646  5693 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-30 23:04:22.833  5646  5693 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-30 23:04:23.834  5646  5693 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-30 23:04:23.835  5646  5693 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-30 23:04:23.836  5646  5693 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-30 23:04:23.837  5646  5693 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-30 23:04:23.838  5646  5693 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-30 23:04:23.838  5646  5693 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,11-30 23:04:23.838  5646  5693 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-30 23:04:23.839  5646  5693 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-30 23:04:23.839  5646  5693 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
11-30 23:04:23.839  5646  5693 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-30 23:04:23.840  5646  5693 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-30 23:04:23.841  5646  5693 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-30 23:04:23.841  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-30 23:04:23.841  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b35691 added. We now have 3 listener(s)
,11-30 23:04:23.843  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 23:04:23.843  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 23:04:23.843  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-30 23:04:23.844  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 23:04:23.844  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e239f6 added. We now have 3 listener(s)
11-30 23:04:23.844  5646  5693 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-30 23:04:23.845  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 23:04:23.850  5646  5693 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-30 23:04:23.851  5646  5693 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-30 23:04:23.851  5646  5693 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-30 23:04:23.851  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-30 23:04:23.852  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.852  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:23.852  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.852  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 23:04:23.852  5646  5693 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 23:04:23.853  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 23:04:23.853  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 23:04:23.853  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-30 23:04:23.855  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-30 23:04:23.856  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 23:04:23.856  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 23:04:23.856  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 23:04:23.856  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 23:04:23.856  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 23:04:23.856  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 23:04:23.856  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 23:04:23.856  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 23:04:23.857  5646  5908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 23:04:23.859  5646  5908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 23:04:23.859  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 23:04:23.859  5646  5693 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 23:04:23.860  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 23:04:23.863  5646  5908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-30 23:04:23.864  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:23.859  5825  5825 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34837]" dev="sockfs" ino=34837 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:23.864  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 23:04:23.865  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-30 23:04:23.865  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 23:04:23.865  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-30 23:04:23.862  5825  5825 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34837]" dev="sockfs" ino=34837 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:23.866  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.867  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.867  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 23:04:23.867  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-30 23:04:23.867  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 23:04:23.867  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-30 23:04:23.867  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-30 23:04:23.867  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:23.867  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.867  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-30 23:04:23.867  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:23.867  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.867  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.867  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.868  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:23.870  5780  5825 D BtGatt.GattService: registerClient() - UUID=e4dfff5e-ba17-41bb-a853-819eecc431ab
11-30 23:04:23.871  5780  5798 D BtGatt.GattService: onClientRegistered() - UUID=e4dfff5e-ba17-41bb-a853-819eecc431ab, clientIf=5
,11-30 23:04:23.871  5646  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-30 23:04:23.873  5780  5800 D BtGatt.AdvertiseManager: message : 0
,11-30 23:04:23.876  5780  5800 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 23:04:23.888  5780  5798 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 23:04:23.895  5780  5798 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 23:04:23.896  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:23.896  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.896  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 23:04:23.896  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.896  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.897  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.897  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.897  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.897  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 23:04:23.898  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 23:04:23.898  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.900  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.900  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.900  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:23.900  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 23:04:23.901  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 23:04:23.901  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-30 23:04:23.901  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 23:04:23.901  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 23:04:23.901  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:23.901  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:23.902  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:23.902  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-30 23:04:23.902  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 23:04:23.902  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:23.902  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 23:04:23.902  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:23.902  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 23:04:23.902  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 23:04:23.906  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 23:04:23.907  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 23:04:23.907  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:23.907  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:23.907  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 23:04:24.408  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-30 23:04:24.408  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-30 23:04:24.408  5646  5646 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 23:04:25.301   931  3899 I ActivityManager: Killing 3943:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-30 23:04:25.977  5904  5904 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 23:04:25.979  5904  5904 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 23:04:25.981  5904  5904 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 23:04:26.021   931  2993 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-30 23:04:26.022   931  2993 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-30 23:04:26.022   931  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 23:04:26.032   931  2993 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-30 23:04:26.066   931  2993 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
11-30 23:04:26.071  5904  5904 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-30 23:04:26.490  5904  5904 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-30 23:04:26.522  5904  5904 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-30 23:04:26.524  5904  5904 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-30 23:04:26.537   931  2993 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-30 23:04:26.537   931  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-30 23:04:26.537   931  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-30 23:04:26.556   931  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 23:04:26.569   507   930 D CommandListener: Setting iface cfg
,11-30 23:04:26.576   931  2993 D WifiStateMachine: Start Dhcp Watchdog 2
,11-30 23:04:26.583   931  5913 D DhcpClient: Receive thread started
,11-30 23:04:26.587   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-30 23:04:26.587   931  2993 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-30 23:04:26.587   931  2996 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-30 23:04:26.668   931  2993 E native  : do suspend false
,11-30 23:04:26.681   931  5912 D DhcpClient: Broadcasting DHCPDISCOVER
,11-30 23:04:26.693   931  5913 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172654, domain null
,11-30 23:04:26.694   931  5912 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172654 seconds
,11-30 23:04:26.696   931  5912 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-30 23:04:26.716   931  5913 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-30 23:04:26.717   931  5912 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-30 23:04:26.720   507   930 D CommandListener: Setting iface cfg
11-30 23:04:26.725   931  2993 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-30 23:04:26.731   931  5912 D DhcpClient: Scheduling renewal in 86399s
,11-30 23:04:26.737   931  2993 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-30 23:04:26.738   931  2993 D WifiConfigStore: No blacklist allowed without epno enabled
11-30 23:04:26.738   931  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-30 23:04:26.740   931  2993 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-30 23:04:26.743   931  2996 D ConnectivityService: Adding iface wlan0 to network 101
,11-30 23:04:26.783   931  2996 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-30 23:04:26.783   931  2996 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-30 23:04:26.785   931  2996 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-30 23:04:26.787   931  2996 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-30 23:04:26.789   931  2996 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-30 23:04:26.797   931  2996 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:04:26.801   931  2996 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-30 23:04:26.801   931  2996 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-30 23:04:26.801   931  2996 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-30 23:04:26.801   931  2993 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-30 23:04:26.801   931  2996 D ConnectivityService:    accepting network in place of null
,11-30 23:04:26.801   931  2993 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-30 23:04:26.802   931  2996 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-30 23:04:26.816   931  5911 D NetlinkSocketObserver: NeighborEvent{elapsedMs=186336, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-30 23:04:26.826   507   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 23:04:26.848   507   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 23:04:26.852   931  2996 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-30 23:04:26.852   931  2996 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-30 23:04:26.852  3770  3924 W QCNEJ   : |CORE| network available: 101
,11-30 23:04:26.853   931  2996 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-30 23:04:26.854   931   948 D Tethering: MasterInitialState.processMessage what=3
11-30 23:04:26.855  3770  3924 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-30 23:04:26.857  3770  3924 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-30 23:04:26.857  3770  3924 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-30 23:04:26.864  5072  5096 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-30 23:04:26.865  5072  5096 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-30 23:04:26.865  5072  5096 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-30 23:04:26.865  5072  5096 E SarControlService: no key has been found,reset the power
11-30 23:04:26.865  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-30 23:04:26.865  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-30 23:04:26.865  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-30 23:04:26.865  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-30 23:04:26.866  5097  5097 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-30 23:04:26.869  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-30 23:04:26.869  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-30 23:04:26.869  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-30 23:04:26.870  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 23:04:26.870  5097  5097 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-30 23:04:26.872  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e1d923 HexData = [00000000ec03000000000000ffffffff]
11-30 23:04:26.872  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 23:04:26.872  5097  5111 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-30 23:04:26.873  4014  4014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-30 23:04:26.874  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-30 23:04:26.874  5072  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-30 23:04:26.877  3894  3894 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-30 23:04:26.879  3894  3894 D SystemUpdateService: onCreate
,11-30 23:04:26.883  3894  3894 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-30 23:04:26.884  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e1d923 HexData = [00000000ed03000000000000ffffffff]
11-30 23:04:26.884  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 23:04:26.884  5097  5111 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-30 23:04:26.885  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-30 23:04:26.885  5072  5082 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-30 23:04:26.894  3894  3894 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-30 23:04:26.903   931  5910 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:814::200e
,11-30 23:04:26.905  3894  5425 I iu.UploadsManager: num queued entries: 0
,11-30 23:04:26.906  3894  5425 I iu.UploadsManager: num updated entries: 0
,11-30 23:04:26.907  3894  5425 I iu.SyncManager: NEXT; no task
,11-30 23:04:26.908  3894  3894 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-30 23:04:26.909  3894  3894 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-30 23:04:26.912  5856  5856 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-30 23:04:26.915  5856  5856 D SprintDMHelper: simOperator: 
11-30 23:04:26.915  5856  5856 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-30 23:04:26.918  3894  5923 I SystemUpdateService: active receiver: enabled
,11-30 23:04:26.948  3894  5923 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-30 23:04:26.957  3894  5923 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-30 23:04:26.957  3894  5923 I SystemUpdateService: now status is 0 (complete)
11-30 23:04:26.957  3894  5923 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-30 23:04:26.957  3894  5923 I SystemUpdateService: file has been verified
11-30 23:04:26.957  3894  5923 I SystemUpdateService: OTA package size = 21989297
,11-30 23:04:26.964  3894  5923 I SystemUpdateService: showing system update notification
,11-30 23:04:26.971   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-30 23:04:26.972  3894  3894 D SystemUpdateService: onDestroy
,11-30 23:04:26.976   931  5910 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 30 Nov 2016 22:04:26 GMT], X-Android-Received-Millis=[1480543466975], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480543466945]}
,11-30 23:04:26.976   931  2996 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-30 23:04:26.977   931  2996 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-30 23:04:26.977   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:04:26.978   931  2996 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-30 23:04:27.039  5047  5928 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-30 23:04:27.403  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-30 23:04:27.403  5646  5693 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-30 23:04:27.403  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-30 23:04:27.404  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 23:04:27.404  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 23:04:27.404  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 23:04:27.404  5646  5908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 23:04:27.404  5646  5908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 23:04:27.405  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-30 23:04:27.405  5646  5908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 23:04:27.405  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 23:04:27.405  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 23:04:27.405  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 23:04:27.405  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-30 23:04:27.405  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.406  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 23:04:27.406  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 23:04:27.406  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:27.406  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.407  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.407  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.410  5646  5693 D BluetoothAdapter: STATE_ON
,11-30 23:04:27.410  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-30 23:04:27.411  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:27.412  5646  5693 D BluetoothLeScanner: could not find callback wrapper
11-30 23:04:27.412  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-30 23:04:27.412  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.412  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.412  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.413  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 23:04:27.413  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.415  5780  5800 D BtGatt.AdvertiseManager: message : 1
11-30 23:04:27.416  5780  5800 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 23:04:27.428  5780  5798 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-30 23:04:27.429  5780  5798 D BtGatt.GattService: Client app is not null!
11-30 23:04:27.430  5780  5826 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 23:04:27.431  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 23:04:27.431  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.431  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 23:04:27.431  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.432  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:27.432  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.432  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 23:04:27.432  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 23:04:27.433  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 23:04:27.434  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.436  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:27.436  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:27.436  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.436  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.437  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 23:04:27.437  5646  5646 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 23:04:27.437  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 23:04:27.437  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 23:04:27.437  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 23:04:27.437  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 23:04:27.437  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:27.437  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.439  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-30 23:04:27.439  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 23:04:27.439  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.439  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.439  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.440  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:27.440  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.440  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 23:04:27.440  5646  5693 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-30 23:04:27.441  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 23:04:27.442  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 23:04:27.442  5646  5693 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-30 23:04:27.443  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.443  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.443  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.443  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-30 23:04:27.443  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-30 23:04:27.444  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-30 23:04:27.446  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-30 23:04:27.450  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-30 23:04:27.451  5646  5693 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 23:04:27.451  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 23:04:27.456  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:27.456  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-30 23:04:27.457  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 23:04:27.457  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 23:04:27.457  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-30 23:04:27.461  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-30 23:04:27.467  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-30 23:04:27.467  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.467  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-30 23:04:27.467  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-30 23:04:27.467  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-30 23:04:27.468  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-30 23:04:27.468  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:27.470  5646  5693 D BluetoothAdapter: STATE_ON
,11-30 23:04:27.474  5780  5825 D BtGatt.GattService: registerClient() - UUID=3bfd2888-32f7-4497-9e46-db1c794ed3e7
,11-30 23:04:27.475  5780  5798 D BtGatt.GattService: onClientRegistered() - UUID=3bfd2888-32f7-4497-9e46-db1c794ed3e7, clientIf=5
,11-30 23:04:27.477  5646  5762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-30 23:04:27.479  5780  5818 D BtGatt.GattService: start scan with filters
11-30 23:04:27.485  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-30 23:04:27.485  5780  5801 D BtGatt.ScanManager: handling starting scan
11-30 23:04:27.485  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.485  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-30 23:04:27.486  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:27.486  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 23:04:27.486  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:27.486  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.486  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-30 23:04:27.487  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 23:04:27.487  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.487  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.487  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.487  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-30 23:04:27.488  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-30 23:04:27.488  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.488  5780  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb9c138
,11-30 23:04:27.491  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.491  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-30 23:04:27.491  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.491  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:27.492  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 23:04:27.495  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 23:04:27.495  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.495  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:27.495  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-30 23:04:27.495  5780  5798 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-30 23:04:27.496  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 23:04:27.496  5780  5801 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-30 23:04:27.502  5780  5798 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-30 23:04:27.502  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 23:04:27.502  5780  5801 D BtGatt.ScanManager: Starting BLE batch scan
11-30 23:04:27.503  5780  5801 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-30 23:04:27.513  5780  5798 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-30 23:04:27.513  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 23:04:27.518  5780  5798 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-30 23:04:27.519  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 23:04:27.853   931  2996 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-30 23:04:27.996  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-30 23:04:27.997  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-30 23:04:27.997  5646  5646 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 23:04:29.007   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:04:29.608   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:04:30.008   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:04:30.494  5646  5693 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-30 23:04:30.494  5646  5693 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-30 23:04:30.495  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-30 23:04:30.495  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.495  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:30.496  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61,
11-30 23:04:30.496  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-30 23:04:30.496  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-30 23:04:30.496  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-30 23:04:30.496  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-30 23:04:30.496  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-30 23:04:30.496  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-30 23:04:30.496  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-30 23:04:30.496  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-30 23:04:30.496  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-30 23:04:30.496  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:30.496  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-30 23:04:30.497  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.497  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.497  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 23:04:30.497  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 23:04:30.497  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.497  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:30.498  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.500  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:30.501  5780  5818 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-30 23:04:30.503  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-30 23:04:30.504  5780  5801 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 23:04:30.508  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:30.510  5780  5791 D BtGatt.GattService: stopScan() - queue size =1
11-30 23:04:30.513  5780  5780 D BtGatt.ScanManager: awakened up at time 190034
,11-30 23:04:30.514  5780  5826 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-30 23:04:30.515  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 23:04:30.516  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.518  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-30 23:04:30.518  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.518  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 23:04:30.518  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:30.519  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.519  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-30 23:04:30.519  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-30 23:04:30.519  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-30 23:04:30.519  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-30 23:04:30.520  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.522  5646  5693 D BluetoothAdapter: STATE_ON
,11-30 23:04:30.524  5780  5826 D BtGatt.GattService: registerClient() - UUID=e07a3f93-18b2-40af-90cf-ad1d87b76517
11-30 23:04:30.525  5780  5798 D BtGatt.GattService: onClientRegistered() - UUID=e07a3f93-18b2-40af-90cf-ad1d87b76517, clientIf=5
,11-30 23:04:30.525  5646  5762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-30 23:04:30.526  5780  5791 D BtGatt.GattService: start scan with filters
,11-30 23:04:30.529  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-30 23:04:30.529  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.529  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-30 23:04:30.530  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:30.530  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.530  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:30.530  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-30 23:04:30.530  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 23:04:30.530  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-30 23:04:30.530  5646  5693 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 23:04:30.530  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-30 23:04:30.530  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 23:04:30.530  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.530  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 23:04:30.530  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.531  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-30 23:04:30.531  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 23:04:30.532  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 23:04:30.532  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-30 23:04:30.532  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 23:04:30.532  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 23:04:30.532  5818  5818 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33010]" dev="sockfs" ino=33010 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:30.532  5818  5818 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33010]" dev="sockfs" ino=33010 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 23:04:30.532  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-30 23:04:30.532  5646  5936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 23:04:30.533  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 23:04:30.533  5646  5936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 23:04:30.533  5646  5693 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 23:04:30.535  5780  5798 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-30 23:04:30.535  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 23:04:30.536  5646  5936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-30 23:04:30.537  5780  5798 D BtGatt.GattService: current time is 190058042206
11-30 23:04:30.538  5780  5798 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -85, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -79, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -84, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -98, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,11-30 23:04:30.539  5780  5798 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-30 23:04:30.540  5780  5798 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-30 23:04:30.540  5780  5798 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-30 23:04:30.541  5780  5798 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-30 23:04:30.541  5780  5798 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,11-30 23:04:30.542  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.542  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.542  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.542  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-30 23:04:30.542  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 23:04:30.542  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 23:04:30.542  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-30 23:04:30.543  5646  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:30.543  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:30.543  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.543  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-30 23:04:30.543  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 23:04:30.543  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.543  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.543  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.544  5646  5693 D BluetoothAdapter: STATE_ON
,11-30 23:04:30.547  5780  5798 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-30 23:04:30.547  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 23:04:30.547  5780  5791 D BtGatt.GattService: registerClient() - UUID=fd9a4bd5-cea4-4671-a965-5c02f1fd3d5b
,11-30 23:04:30.547  5780  5801 D BtGatt.ScanManager: stopping BLe Batch
11-30 23:04:30.547  5780  5798 D BtGatt.GattService: onClientRegistered() - UUID=fd9a4bd5-cea4-4671-a965-5c02f1fd3d5b, clientIf=6
11-30 23:04:30.548  5646  5657 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-30 23:04:30.549  5780  5800 D BtGatt.AdvertiseManager: message : 0
,11-30 23:04:30.552  5780  5800 D BtGatt.AdvertiseManager: starting multi advertising
11-30 23:04:30.552  5780  5798 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-30 23:04:30.553  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 23:04:30.553  5780  5801 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 23:04:30.558  5780  5798 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-30 23:04:30.559  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 23:04:30.561  5780  5801 D BtGatt.ScanManager: handling starting scan
,11-30 23:04:30.567  5780  5798 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-30 23:04:30.571  5780  5798 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-30 23:04:30.571  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 23:04:30.572  5780  5801 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-30 23:04:30.576  5780  5798 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-30 23:04:30.576  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.576  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.576  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-30 23:04:30.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:30.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.577  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-30 23:04:30.577  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-30 23:04:30.577  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 23:04:30.578  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 23:04:30.578  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.580  5780  5798 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-30 23:04:30.580  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 23:04:30.580  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.580  5780  5801 D BtGatt.ScanManager: Starting BLE batch scan
,11-30 23:04:30.580  5780  5801 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-30 23:04:30.580  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.581  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:30.581  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 23:04:30.581  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.581  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:30.581  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-30 23:04:30.581  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.581  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.581  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:30.581  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.581  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
,11-30 23:04:30.581  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-30 23:04:30.581  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.581  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.582  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.582  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.582  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 23:04:30.584  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 23:04:30.584  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-30 23:04:30.584  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.584  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:30.584  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-30 23:04:30.589  5780  5798 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-30 23:04:30.589  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 23:04:30.594  5780  5798 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-30 23:04:30.594  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 23:04:31.009   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:04:31.085  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-30 23:04:31.085  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-30 23:04:31.086  5646  5646 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 23:04:32.011   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:04:32.633   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:04:33.012   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:04:33.587  5646  5693 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-30 23:04:33.588  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-30 23:04:33.588  5646  5693 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 23:04:33.588  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 23:04:33.588  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-30 23:04:33.589  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 23:04:33.589  5646  5936 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 23:04:33.589  5646  5936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 23:04:33.589  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 23:04:33.590  5646  5936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-30 23:04:33.590  5646  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 23:04:33.590  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 23:04:33.590  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-30 23:04:33.590  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 23:04:33.590  5646  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b35691 removed from the list
11-30 23:04:33.590  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 23:04:33.590  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-30 23:04:33.590  5646  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-30 23:04:33.591  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.591  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 23:04:33.591  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 23:04:33.591  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:33.592  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.592  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.592  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-30 23:04:33.593  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.595  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:33.596  5780  5791 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-30 23:04:33.596  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 23:04:33.597  5780  5801 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-30 23:04:33.598  5646  5693 D BluetoothAdapter: STATE_ON
11-30 23:04:33.599  5780  5818 D BtGatt.GattService: stopScan() - queue size =1
11-30 23:04:33.601  5780  5825 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 23:04:33.601  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 23:04:33.602  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.602  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-30 23:04:33.602  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.602  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.604  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.604  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 23:04:33.604  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.605  5780  5800 D BtGatt.AdvertiseManager: message : 1
,11-30 23:04:33.606  5780  5800 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-30 23:04:33.610  5780  5780 D BtGatt.ScanManager: awakened up at time 193130
,11-30 23:04:33.613  5780  5798 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-30 23:04:33.614  5780  5798 D BtGatt.GattService: Client app is not null!
11-30 23:04:33.614  5780  5826 D BtGatt.GattService: unregisterClient() - clientIf=6
11-30 23:04:33.616  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 23:04:33.616  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.616  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 23:04:33.616  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.617  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.617  5646  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.617  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 23:04:33.617  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 23:04:33.617  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 23:04:33.618  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:33.620  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-30 23:04:33.620  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:33.620  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.620  5646  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 23:04:33.620  5646  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e239f6 removed from the list
11-30 23:04:33.620  5646  5693 D io.jxcore.node.ConnectivityMonitor: stop
11-30 23:04:33.620  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 23:04:33.621  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 23:04:33.621  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:33.621  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.621  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 23:04:33.621  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-30 23:04:33.621  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.621  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.621  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.621  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 23:04:33.622  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.622  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 23:04:33.622  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 23:04:33.622  5646  5693 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,11-30 23:04:33.622  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.622  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.622  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-30 23:04:33.622  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 23:04:33.622  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 23:04:33.622  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 23:04:33.622  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.622  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 23:04:33.622  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.622  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-30 23:04:33.623  5646  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-30 23:04:33.624  5646  5693 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-30 23:04:33.624  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.624  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-30 23:04:33.624  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 23:04:33.625  5646  5693 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-30 23:04:33.626  5646  5693 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-30 23:04:33.626  5780  5798 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-30 23:04:33.626  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 23:04:33.627  5780  5798 D BtGatt.GattService: current time is 193147469829
11-30 23:04:33.627  5780  5798 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -79, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -94, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -86, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-30 23:04:33.627  5780  5798 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,11-30 23:04:33.627  5646  5693 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-30 23:04:33.627  5780  5798 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-30 23:04:33.627  5780  5798 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-30 23:04:33.628  5780  5798 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-30 23:04:33.628  5780  5798 E BtGatt.ContextMap: Context not found for ID 5
11-30 23:04:33.628  5646  5693 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-30 23:04:33.629  5646  5693 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-30 23:04:33.629  5646  5693 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,11-30 23:04:33.630  5646  5693 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-30 23:04:33.637  5780  5798 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-30 23:04:33.637  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 23:04:33.637  5780  5801 D BtGatt.ScanManager: stopping BLe Batch
,11-30 23:04:33.642  5780  5798 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-30 23:04:33.643  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 23:04:33.643  5780  5801 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 23:04:33.648  5780  5798 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-30 23:04:33.648  5780  5798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 23:04:34.012   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-30 23:04:34.122  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 23:04:34.803   931  2996 D ConnectivityService: handlePromptUnvalidated 101
,11-30 23:04:35.635  5646  5693 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-30 23:04:35.652   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:04:35.791  5646  5939 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 23:04:35.791  5646  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 23:04:36.638  5646  5939 W !!      : call onHalfStreamCopied
,11-30 23:04:36.638  5646  5939 I testCopyDataAndClose: closing input stream
,11-30 23:04:37.417  5646  5939 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 23:04:37.417  5646  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 23:04:37.417  5646  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 23:04:37.417  5646  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 23:04:37.417  5646  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-30 23:04:37.417  5646  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-30 23:04:37.418  5646  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-30 23:04:37.418  5646  5939 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-30 23:04:37.418  5646  5939 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-30 23:04:37.418  5646  5939 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 23:04:37.418  5646  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-30 23:04:37.831   931  2993 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,11-30 23:04:38.681   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:04:40.440   931  2993 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,11-30 23:04:41.720  5646  5693 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-30 23:04:41.803  5646  5941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 23:04:41.803  5646  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 194, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 23:04:43.411  5646  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-30 23:04:44.735   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:04:47.677  5646  5693 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-30 23:04:47.680  5646  5942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-30 23:04:47.680  5646  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 23:04:47.680  5646  5942 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 196, thread name: My test thread name). Connection data: Peer properties: [null null].
11-30 23:04:47.680  5646  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 23:04:47.680  5646  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 23:04:47.680  5646  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 23:04:47.680  5646  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-30 23:04:47.680  5646  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-30 23:04:47.680  5646  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-30 23:04:47.681  5646  5942 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-30 23:04:47.681  5646  5942 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-30 23:04:47.681  5646  5942 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-30 23:04:47.681  5646  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-30 23:04:47.682  5646  5693 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-30 23:04:47.683  5646  5693 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-30 23:04:47.684  5646  5693 I StreamCopyingThreadTest: Starting test: testRunWithException
11-30 23:04:47.686  5646  5943 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-30 23:04:47.686  5646  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 23:04:47.687  5646  5943 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 200, thread name: My test thread name): Test exception.
11-30 23:04:47.687  5646  5943 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-30 23:04:47.687  5646  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-30 23:04:47.687  5646  5943 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-30 23:04:47.687  5646  5943 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-30 23:04:47.687  5646  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-30 23:04:47.692  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG UnitTest_app: 'Running unit tests'
11-30 23:04:47.692  5646  5693 I jxcore-log: 
11-30 23:04:47.692  5646  5693 I jxcore-log: *Native tests were executed*
11-30 23:04:47.692  5646  5693 I jxcore-log: 
11-30 23:04:47.692  5646  5693 I jxcore-log: Total number of executed tests:  81
11-30 23:04:47.692  5646  5693 I jxcore-log: 
11-30 23:04:47.692  5646  5693 I jxcore-log: Number of passed tests:  79
11-30 23:04:47.692  5646  5693 I jxcore-log: 
,11-30 23:04:47.692  5646  5693 I jxcore-log: Number of failed tests:  0
11-30 23:04:47.692  5646  5693 I jxcore-log: 
11-30 23:04:47.692  5646  5693 I jxcore-log: Number of ignored tests:  2
11-30 23:04:47.692  5646  5693 I jxcore-log: 
11-30 23:04:47.693  5646  5693 I jxcore-log: Total duration:  35378
11-30 23:04:47.693  5646  5693 I jxcore-log: 
11-30 23:04:47.694  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-30 23:04:47.694  5646  5693 I jxcore-log: 
,11-30 23:04:47.697  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 23:04:47.697  5646  5693 I jxcore-log: 
11-30 23:04:47.698  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 23:04:47.698  5646  5693 I jxcore-log: 
11-30 23:04:47.698  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 23:04:47.698  5646  5693 I jxcore-log: 
,11-30 23:04:47.699  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 23:04:47.699  5646  5693 I jxcore-log: 
,11-30 23:04:47.700  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 23:04:47.700  5646  5693 I jxcore-log: 
,11-30 23:04:47.700  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 23:04:47.700  5646  5693 I jxcore-log: 
11-30 23:04:47.701  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 23:04:47.701  5646  5693 I jxcore-log: 
11-30 23:04:47.701  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 23:04:47.701  5646  5693 I jxcore-log: 
11-30 23:04:47.701  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 23:04:47.701  5646  5693 I jxcore-log: 
,11-30 23:04:47.701  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 23:04:47.701  5646  5693 I jxcore-log: 
11-30 23:04:47.701  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 23:04:47.701  5646  5693 I jxcore-log: 
11-30 23:04:47.702  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 23:04:47.702  5646  5693 I jxcore-log: 
11-30 23:04:47.702  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 23:04:47.702  5646  5693 I jxcore-log: 
,11-30 23:04:47.702  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 23:04:47.702  5646  5693 I jxcore-log: 
11-30 23:04:47.702  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 23:04:47.702  5646  5693 I jxcore-log: 
11-30 23:04:47.703  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 23:04:47.703  5646  5693 I jxcore-log: 
11-30 23:04:47.703  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 23:04:47.703  5646  5693 I jxcore-log: 
11-30 23:04:47.703  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 23:04:47.703  5646  5693 I jxcore-log: 
,11-30 23:04:47.703  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 23:04:47.703  5646  5693 I jxcore-log: 
11-30 23:04:47.704  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 23:04:47.704  5646  5693 I jxcore-log: 
11-30 23:04:47.704  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 23:04:47.704  5646  5693 I jxcore-log: 
11-30 23:04:47.704  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 23:04:47.704  5646  5693 I jxcore-log: 
11-30 23:04:47.704  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 23:04:47.704  5646  5693 I jxcore-log: 
11-30 23:04:47.705  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-30 23:04:47.705  5646  5693 I jxcore-log: 
11-30 23:04:47.705  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 23:04:47.705  5646  5693 I jxcore-log: 
,11-30 23:04:47.705  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-30 23:04:47.705  5646  5693 I jxcore-log: 
11-30 23:04:47.705  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 23:04:47.705  5646  5693 I jxcore-log: 
11-30 23:04:47.705  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 23:04:47.705  5646  5693 I jxcore-log: 
11-30 23:04:47.706  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 23:04:47.706  5646  5693 I jxcore-log: 
11-30 23:04:47.707  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 23:04:47.707  5646  5693 I jxcore-log: 
11-30 23:04:47.707  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-30 23:04:47.707  5646  5693 I jxcore-log: 
,11-30 23:04:47.708  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 23:04:47.708  5646  5693 I jxcore-log: 
11-30 23:04:47.708  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 23:04:47.708  5646  5693 I jxcore-log: 
11-30 23:04:47.708  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-30 23:04:47.708  5646  5693 I jxcore-log: 
11-30 23:04:47.708  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 23:04:47.708  5646  5693 I jxcore-log: 
,11-30 23:04:47.708  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 23:04:47.708  5646  5693 I jxcore-log: 
11-30 23:04:47.709  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 23:04:47.709  5646  5693 I jxcore-log: 
11-30 23:04:47.709  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 23:04:47.709  5646  5693 I jxcore-log: 
11-30 23:04:47.711  5646  5646 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,11-30 23:04:47.711  5646  5646 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-30 23:04:47.714  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-30 23:04:47.714  5646  5693 I jxcore-log: 
11-30 23:04:47.714  5646  5693 I jxcore-log: 2016-11-30 22:04:47 - WARN testUtils: 'myNameCallback not set!'
11-30 23:04:47.714  5646  5693 I jxcore-log: 
,11-30 23:04:49.800  5646  5693 I jxcore-log: 2016-11-30 22:04:49 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-30 23:04:49.800  5646  5693 I jxcore-log: 
,11-30 23:04:49.801  5646  5693 I jxcore-log: 2016-11-30 22:04:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-30 23:04:49.801  5646  5693 I jxcore-log: 
,11-30 23:04:50.146  5646  5693 I jxcore-log: 2016-11-30 22:04:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-30 23:04:50.146  5646  5693 I jxcore-log: 
,11-30 23:04:50.159  5646  5693 I jxcore-log: 2016-11-30 22:04:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-30 23:04:50.159  5646  5693 I jxcore-log: 
,11-30 23:04:50.159  3708  3907 I Keyboard.Facilitator.LanguageModelFlusher: run()
11-30 23:04:50.159  3708  3907 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-30 23:04:50.191  3628  3628 I ConfigService: onCreate
,11-30 23:04:51.248  5646  5693 I jxcore-log: 2016-11-30 22:04:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-30 23:04:51.248  5646  5693 I jxcore-log: 
,11-30 23:04:51.416  5646  5693 I jxcore-log: 2016-11-30 22:04:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-30 23:04:51.416  5646  5693 I jxcore-log: 
,11-30 23:04:51.421  5646  5693 I jxcore-log: 2016-11-30 22:04:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-30 23:04:51.421  5646  5693 I jxcore-log: 
,11-30 23:04:51.433  5646  5693 I jxcore-log: 2016-11-30 22:04:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-30 23:04:51.433  5646  5693 I jxcore-log: 
,11-30 23:04:51.929  5646  5693 I jxcore-log: 2016-11-30 22:04:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-30 23:04:51.929  5646  5693 I jxcore-log: 
,11-30 23:04:51.974  5646  5693 I jxcore-log: 2016-11-30 22:04:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-30 23:04:51.974  5646  5693 I jxcore-log: 
,11-30 23:04:51.987  5646  5693 I jxcore-log: 2016-11-30 22:04:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-30 23:04:51.987  5646  5693 I jxcore-log: 
,11-30 23:04:51.991  5646  5693 I jxcore-log: 2016-11-30 22:04:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-30 23:04:51.991  5646  5693 I jxcore-log: 
,11-30 23:04:52.265  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-30 23:04:52.265  5646  5693 I jxcore-log: 
,11-30 23:04:52.391  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-30 23:04:52.391  5646  5693 I jxcore-log: 
,11-30 23:04:52.764  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-30 23:04:52.764  5646  5693 I jxcore-log: 
,11-30 23:04:52.771  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-30 23:04:52.771  5646  5693 I jxcore-log: 
,11-30 23:04:52.775  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-30 23:04:52.775  5646  5693 I jxcore-log: 
,11-30 23:04:52.778  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-30 23:04:52.778  5646  5693 I jxcore-log: 
,11-30 23:04:52.783  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-30 23:04:52.783  5646  5693 I jxcore-log: 
,11-30 23:04:52.821  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-30 23:04:52.821  5646  5693 I jxcore-log: 
,11-30 23:04:52.827  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-30 23:04:52.827  5646  5693 I jxcore-log: 
,11-30 23:04:52.850  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-30 23:04:52.850  5646  5693 I jxcore-log: 
,11-30 23:04:52.889  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-30 23:04:52.889  5646  5693 I jxcore-log: 
,11-30 23:04:52.905  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-30 23:04:52.905  5646  5693 I jxcore-log: 
,11-30 23:04:52.912  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-30 23:04:52.912  5646  5693 I jxcore-log: 
,11-30 23:04:52.927  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-30 23:04:52.927  5646  5693 I jxcore-log: 
,11-30 23:04:52.942  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-30 23:04:52.942  5646  5693 I jxcore-log: 
,11-30 23:04:52.948  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-30 23:04:52.948  5646  5693 I jxcore-log: 
,11-30 23:04:52.954  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-30 23:04:52.954  5646  5693 I jxcore-log: 
,11-30 23:04:52.979  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-30 23:04:52.979  5646  5693 I jxcore-log: 
,11-30 23:04:52.998  5646  5693 I jxcore-log: 2016-11-30 22:04:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-30 23:04:52.998  5646  5693 I jxcore-log: 
,11-30 23:04:53.011  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-30 23:04:53.011  5646  5693 I jxcore-log: 
,11-30 23:04:53.021  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-30 23:04:53.021  5646  5693 I jxcore-log: 
,11-30 23:04:53.032  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-30 23:04:53.032  5646  5693 I jxcore-log: 
,11-30 23:04:53.041  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-30 23:04:53.041  5646  5693 I jxcore-log: 
,11-30 23:04:53.053  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-30 23:04:53.053  5646  5693 I jxcore-log: 
,11-30 23:04:53.062  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-30 23:04:53.062  5646  5693 I jxcore-log: 
,11-30 23:04:53.068  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-30 23:04:53.068  5646  5693 I jxcore-log: 
,11-30 23:04:53.087  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-30 23:04:53.087  5646  5693 I jxcore-log: 
,11-30 23:04:53.094  5646  5693 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-30 23:04:53.095  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - INFO testUtils: 'BLE multiple advertisement supported'
11-30 23:04:53.095  5646  5693 I jxcore-log: 
,11-30 23:04:53.126  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-30 23:04:53.126  5646  5693 I jxcore-log: 
,11-30 23:04:53.345  5646  5693 I jxcore-log: 2016-11-30 22:04:53 - DEBUG CoordinatedClient: 'connected to the test server'
11-30 23:04:53.345  5646  5693 I jxcore-log: 
,11-30 23:04:53.804   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:04:55.228  3628  3628 I ConfigService: onDestroy
,11-30 23:04:59.013   543   543 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-30 23:04:59.013   543   543 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-30 23:04:59.857   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:05:06.755   931  2993 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 23:05:09.014   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:10.016   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:11.017   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:11.973   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:05:12.018   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:13.019   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:14.020   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-30 23:05:18.028   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:05:19.021   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:20.023   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:21.024   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:21.064   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:05:22.026   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:23.027   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:24.028   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-30 23:05:24.101   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:05:27.127   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:05:30.148   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:05:34.030   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:35.031   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:36.033   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:37.034   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:38.036   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:39.036   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-30 23:05:45.304   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:05:46.761   931  2993 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 23:05:51.366   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:05:54.038   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:55.040   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:56.041   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:57.042   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:58.044   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:05:59.045   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-30 23:06:03.476   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:06:06.509   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:06:06.761   931  2993 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 23:06:15.590   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:06:18.627   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:06:19.046   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:06:20.048   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:06:21.049   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:06:22.050   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:06:23.052   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:06:24.053   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-30 23:06:24.678   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:06:33.749   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:06:39.804   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:06:46.766   931  2993 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 23:06:49.054   543   543 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-30 23:06:49.054   543   543 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-30 23:06:51.926   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:06:54.957   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:06:57.987   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:07:01.018   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:07:04.040   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:07:04.055   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:05.056   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:06.057   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:06.769   931  2993 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 23:07:07.056   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-30 23:07:07.061   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:08.062   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:09.063   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-30 23:07:10.090   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:07:13.124   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:07:14.064   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:15.066   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:16.067   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:17.068   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:18.069   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:19.070   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-30 23:07:25.246   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:07:26.771   931  2993 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 23:07:29.071   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:30.072   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:31.074   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:32.075   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:33.076   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:34.077   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-30 23:07:34.340   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:07:37.372   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:07:46.453   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:07:49.078   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:50.080   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:51.081   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:52.082   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:53.084   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:07:54.085   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-30 23:07:55.533   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:08:01.592   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:08:04.628   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:08:06.773   931  2993 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 23:08:07.663   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:08:13.722   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:08:14.086   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:08:15.088   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:08:16.089   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:08:17.091   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:08:18.092   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 23:08:19.093   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-30 23:08:19.791   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:08:26.774   931  2993 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 23:08:28.879   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:08:34.938   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:08:44.093   543   543 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-30 23:08:44.094   543   543 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-30 23:08:46.778   931  2993 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 23:08:47.057   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:08:50.088   931  2996 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 23:08:54.032  5646  5693 I jxcore-log: 2016-11-30 22:08:54 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-30 23:08:54.032  5646  5693 I jxcore-log: 
,11-30 23:08:54.224  5646  5693 I jxcore-log: 2016-11-30 22:08:54 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 23:08:54.224  5646  5693 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 23:08:54.224  5646  5693 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 23:08:54.224  5646  5693 I jxcore-log: emit@events.js:82:1
11-30 23:08:54.224  5646  5693 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 23:08:54.224  5646  5693 I jxcore-log: emit@events.js:82:1''
11-30 23:08:54.224  5646  5693 I jxcore-log: 
,11-30 23:08:54.225  5646  5693 I jxcore-log: 2016-11-30 22:08:54 - DEBUG CoordinatedClient: 'test client failed'
11-30 23:08:54.225  5646  5693 I jxcore-log: 
,11-30 23:08:54.233  5646  5693 I jxcore-log: 2016-11-30 22:08:54 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 23:08:54.233  5646  5693 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 23:08:54.233  5646  5693 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 23:08:54.233  5646  5693 I jxcore-log: emit@events.js:82:1
11-30 23:08:54.233  5646  5693 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 23:08:54.233  5646  5693 I jxcore-log: emit@events.js:82:1''
11-30 23:08:54.233  5646  5693 I jxcore-log: 
,11-30 23:08:54.234  5646  5693 I jxcore-log: 2016-11-30 22:08:54 - DEBUG CoordinatedClient: 'test client failed'
11-30 23:08:54.234  5646  5693 I jxcore-log: 
11-30 23:08:54.237  5646  5693 I jxcore-log: 2016-11-30 22:08:54 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 23:08:54.237  5646  5693 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 23:08:54.237  5646  5693 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 23:08:54.237  5646  5693 I jxcore-log: emit@events.js:82:1
11-30 23:08:54.237  5646  5693 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 23:08:54.237  5646  5693 I jxcore-log: emit@events.js:82:1''
11-30 23:08:54.237  5646  5693 I jxcore-log: 
11-30 23:08:54.238  5646  5693 I jxcore-log: 2016-11-30 22:08:54 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-30 23:08:54.238  5646  5693 I jxcore-log: 
,11-30 23:08:54.240  5646  5693 I jxcore-log: 2016-11-30 22:08:54 - ERROR runTests: 'websocket error
11-30 23:08:54.240  5646  5693 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 23:08:54.240  5646  5693 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 23:08:54.240  5646  5693 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 23:08:54.240  5646  5693 I jxcore-log: emit@events.js:82:1
11-30 23:08:54.240  5646  5693 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 23:08:54.240  5646  5693 I jxcore-log: emit@events.js:82:1'
11-30 23:08:54.240  5646  5693 I jxcore-log: 
,11-30 23:08:54.815  5956  5956 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-30 23:08:54.838  5956  5956 D AndroidRuntime: CheckJNI is OFF
,11-30 23:08:54.862  5956  5956 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-30 23:08:54.890  5956  5956 I Radio-JNI: register_android_hardware_Radio DONE
,11-30 23:08:54.906  5956  5956 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-30 23:08:54.917   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-30 23:08:54.918   931   944 I ActivityManager: Killing 5646:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-30 23:08:55.025   931  3194 I WindowState: WIN DEATH: Window{3346242 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-30 23:08:55.025   931  2994 D WifiService: Client connection lost with reason: 4
,11-30 23:08:55.025   931  3457 D GraphicsStats: Buffer count: 2
,11-30 23:08:55.038   931   944 W ActivityManager: Force removing ActivityRecord{b5b9afb u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-30 23:08:55.054   931   954 I art     : Starting a blocking GC Explicit
,11-30 23:08:55.060   931   941 W ActivityManager: Spurious death for ProcessRecord{6edc1f4 0:com.test.thalitest/u0a77}, curProc for 5646: null
,11-30 23:08:55.084   931  3194 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5646 uid 10077
,11-30 23:08:55.082  3194  3194 W Binder_4: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[26428]" dev="sockfs" ino=26428 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-30 23:08:55.086  3708  3708 I Keyboard.Facilitator: onFinishInput()
11-30 23:08:55.082  3194  3194 W Binder_4: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[26428]" dev="sockfs" ino=26428 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 23:08:55.145  4014  5969 I MicroRecognitionRnrImpl: Starting detection.
,11-30 23:08:55.146  4014  5970 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@54e55c0
,11-30 23:08:55.148   512  5972 I AudioFlinger: AudioFlinger's thread 0xf1cc0000 ready to run
,11-30 23:08:55.153   512  3041 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-30 23:08:55.154  4014  5970 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@54e55c0
,11-30 23:08:55.164   512  5972 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-30 23:08:55.164   512  5972 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-30 23:08:55.164   512  5972 I ACDB-LOADER: ACDB AFE returned = -19
11-30 23:08:55.164   512  5972 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,11-30 23:08:55.164   512  5972 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-30 23:08:55.164   512  5972 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
11-30 23:08:55.168   931   954 I art     : Explicit concurrent mark sweep GC freed 157632(10MB) AllocSpace objects, 85(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.762ms total 113.109ms
,11-30 23:08:55.168   931   940 I art     : WaitForGcToComplete blocked for 72.617ms for cause Background
,11-30 23:08:55.175   512  5972 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-30 23:08:55.187   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-30 23:08:55.189  5956  5956 I art     : System.exit called, status: 0
11-30 23:08:55.189  5956  5956 I AndroidRuntime: VM exiting with result code 0.
,11-30 23:08:55.194   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-30 23:08:55.220  5780  5780 D BluetoothMapAppObserver: onReceive
11-30 23:08:55.220  5780  5780 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-30 23:08:55.227  3708  3708 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-30 23:08:55.230  4102  4222 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-30 23:08:55.232   931  2985 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-30 23:08:55.250  3708  5978 I Keyboard.Facilitator.DecoderInitializer: run()
,11-30 23:08:55.253  4014  4014 I HotwordWorkerImpl: onReady
,11-30 23:08:55.254  3708  5978 I Decoder : createOrResetDecoder
,11-30 23:08:55.285   446   446 W kworker/5:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 23:08:55.289   446   446 W kworker/5:1: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 23:08:55.299  3804  3804 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-30 23:08:55.304  3440  5981 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-30 23:08:55.311  3628  3628 I ConfigService: onCreate
,11-30 23:08:55.312   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-30 23:08:55.318  3842  3985 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-30 23:08:55.319  3628  3628 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-30 23:08:55.319  3628  3628 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-30 23:08:55.319   446   446 W kworker/5:1: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 23:08:55.330  3708  5978 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-30 23:08:55.333   931  3456 I ActivityManager: Start proc 5986:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-30 23:08:55.333  3842  3985 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-30 23:08:55.333  3842  3985 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3842
11-30 23:08:55.333  3842  3985 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-30 23:08:55.333  3842  3985 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 23:08:55.337   931  5991 E DropBoxManagerService: Can't write: system_app_crash
11-30 23:08:55.337   931  5991 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 23:08:55.337   931  5991 E DropBoxManagerService: 	... 5 more
,11-30 23:08:55.339   931  3188 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-30 23:08:55.343  4014  4026 W SearchService: Abort, client detached.
,11-30 23:08:55.345  4014  4014 I HotwordDetector: Closing mic
,11-30 23:08:55.345  4014  4229 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@54e55c0
11-30 23:08:55.345  4014  5970 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-30 23:08:55.359   407   407 W Binder_2: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[31588]" dev="sockfs" ino=31588 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 23:08:55.359   407   407 W Binder_2: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[31588]" dev="sockfs" ino=31588 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 23:08:55.362   740   740 W Binder_3: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[31591]" dev="sockfs" ino=31591 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 23:08:55.362   740   740 W Binder_3: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[31591]" dev="sockfs" ino=31591 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-30 23:08:55.364   931  5999 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-30 23:08:55.370  3440  5981 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-30 23:08:55.375  3440  5981 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-30 23:08:55.375  3440  5981 E AndroidRuntime: Process: android.process.acore, PID: 3440
11-30 23:08:55.375  3440  5981 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-30 23:08:55.375  3440  5981 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 23:08:55.381   931  6000 E DropBoxManagerService: Can't write: system_app_crash
11-30 23:08:55.381   931  6000 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 23:08:55.381   931  6000 E DropBoxManagerService: 	... 5 more
,11-30 23:08:55.386  3708  5978 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-30 23:08:55.391  3708  5978 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-30 23:08:55.391  3708  5978 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-30 23:08:55.394  3708  5978 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-30 23:08:55.394  3708  5978 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-30 23:08:55.396  3708  5978 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,11-30 23:08:55.396  3708  5978 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-30 23:08:55.396  3894  6002 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-30 23:08:55.397  3894  6002 D AccountUtils: Clearing selected account for com.test.thalitest
11-30 23:08:55.398  3708  5978 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-30 23:08:55.398  3708  5978 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-30 23:08:55.398  3708  5978 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-30 23:08:55.398  3708  5978 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-30 23:08:55.398  3708  5978 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-30 23:08:55.398  3708  5978 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-30 23:08:55.412   512  5972 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-30 23:08:55.414   512  5972 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-30 23:08:55.418   512  5972 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-30 23:08:55.418   512  5972 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-30 23:08:55.419   512  3041 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-30 23:08:55.422  4014  5969 I MicroRecognitionRnrImpl: Detection finished
,11-30 23:08:55.423  4014  4240 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-30 23:08:55.687   380   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
