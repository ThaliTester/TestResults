#### Test 9504761584995ac_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-23 18:51:16.083  4087  4247 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-23 18:51:16.167  4087  4247 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-23 18:51:16.571  5593  5593 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-23 18:51:16.576  5593  5593 D AndroidRuntime: CheckJNI is OFF
11-23 18:51:16.604  5593  5593 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-23 18:51:16.636  5593  5593 I Radio-JNI: register_android_hardware_Radio DONE
11-23 18:51:16.652  5593  5593 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-23 18:51:16.657   929  3173 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-23 18:51:16.680  5593  5593 D AndroidRuntime: Shutting down VM
11-23 18:51:16.688  3970  5588 W SearchService: Abort, client detached.
11-23 18:51:16.700  3970  3970 I HotwordDetector: Closing mic
11-23 18:51:16.701  3970  4237 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7c6b3f
11-23 18:51:16.701  3970  4245 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-23 18:51:16.715   929  4036 I ActivityManager: Start proc 5602:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-23 18:51:16.777   513  4248 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-23 18:51:16.779   513  4248 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-23 18:51:16.783   513  4248 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-23 18:51:16.783   513  4248 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-23 18:51:16.784   513  3011 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-23 18:51:16.787  3970  4244 I MicroRecognitionRnrImpl: Detection finished
11-23 18:51:16.787  3970  4239 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-23 18:51:16.810  5602  5602 I CordovaLog: Changing log level to DEBUG(3)
11-23 18:51:16.810  5602  5602 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-23 18:51:16.810  5602  5602 D CordovaActivity: CordovaActivity.onCreate()
11-23 18:51:16.816  5602  5602 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-23 18:51:16.841  5602  5602 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-23 18:51:16.903  5602  5602 I LibraryLoader: Time to load native libraries: 59 ms (timestamps 9471-9530)
11-23 18:51:16.903  5602  5602 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-23 18:51:16.937  5602  5602 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4a4cbef}
,11-23 18:51:16.938  5602  5602 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-23 18:51:16.938  5602  5602 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-23 18:51:16.944  5602  5602 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-23 18:51:16.946  5602  5602 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-23 18:51:16.993  5602  5602 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-23 18:51:17.010  5602  5602 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-23 18:51:17.011  5602  5602 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 18:51:17.011  5602  5602 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 18:51:17.011  5602  5602 I Adreno  : Build Date                       : 12/06/15
11-23 18:51:17.011  5602  5602 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 18:51:17.011  5602  5602 I Adreno  : Local Branch                     : mybranch17112971
11-23 18:51:17.011  5602  5602 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 18:51:17.011  5602  5602 I Adreno  : Remote Branch                    : NONE
11-23 18:51:17.011  5602  5602 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 18:51:17.064   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@98168c0:true
,11-23 18:51:17.104   760   760 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[24138]" dev="sockfs" ino=24138 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 18:51:17.104   760   760 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[24138]" dev="sockfs" ino=24138 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 18:51:17.118  5602  5602 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-23 18:51:17.129  5602  5602 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-23 18:51:17.133  5602  5602 D PluginManager: init()
,11-23 18:51:17.136  5602  5602 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-23 18:51:17.260  5602  5602 D CordovaActivity: Started the activity.
,11-23 18:51:17.261  5602  5602 D CordovaActivity: Resumed the activity.
,11-23 18:51:17.264  3879  3879 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[30622]" dev="sockfs" ino=30622 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 18:51:17.264  3879  3879 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30622]" dev="sockfs" ino=30622 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 18:51:17.268  5602  5639 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 18:51:17.274  3434  3434 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30625]" dev="sockfs" ino=30625 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 18:51:17.277  3434  3434 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30625]" dev="sockfs" ino=30625 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 18:51:17.282  5602  5626 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-23 18:51:17.329  5602  5639 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 18:51:17.419   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +726ms
,11-23 18:51:17.414  3173  3173 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31466]" dev="sockfs" ino=31466 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 18:51:17.417  3173  3173 W Binder_3: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31466]" dev="sockfs" ino=31466 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 18:51:17.417   939   939 W Binder_1: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31465]" dev="sockfs" ino=31465 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 18:51:17.417   939   939 W Binder_1: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31465]" dev="sockfs" ino=31465 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 18:51:17.423  3685  3685 I Keyboard.Facilitator: onFinishInput()
,11-23 18:51:17.440  5602  5602 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-23 18:51:17.462  5602  5602 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5602
,11-23 18:51:17.571  5602  5602 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-23 18:51:17.751  5602  5641 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -584058576
,11-23 18:51:17.762  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-23 18:51:17.762  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-23 18:51:17.762  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-23 18:51:17.762  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-23 18:51:17.762  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-23 18:51:17.762  5602  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e33af2 added. We now have 1 listener(s)
,11-23 18:51:17.767  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-23 18:51:17.767  5602  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:51:17.768  5602  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 18:51:17.768  5602  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-23 18:51:17.770  5602  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2208cf9 added. We now have 1 listener(s)
11-23 18:51:17.770  5602  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 18:51:17.775   929  2990 D WifiService: New client listening to asynchronous messages
,11-23 18:51:17.775  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 18:51:17.775  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-23 18:51:17.776  5602  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-23 18:51:17.776  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-23 18:51:17.776  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-23 18:51:17.776  5602  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-23 18:51:17.776  5602  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-23 18:51:17.777  5602  5641 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 18:51:17.897  5602  5602 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-23 18:51:17.899  5602  5602 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-23 18:51:17.899  5602  5602 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-23 18:51:18.100   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:51:18.332  5602  5611 I art     : Background sticky concurrent mark sweep GC freed 76372(7MB) AllocSpace objects, 16(1076KB) LOS objects, 23% free, 25MB/32MB, paused 2.124ms total 361.407ms
,11-23 18:51:19.306  5602  5649 E filemap : mmap(27398144,0) failed: Invalid argument
,11-23 18:51:19.306  5602  5649 W asset   : create map from entry failed
11-23 18:51:19.306  5602  5649 W jxcore-FileManager: aproxFileSize failed
11-23 18:51:19.306  5602  5649 W System.err: java.io.FileNotFoundException: www/jxcore/node_modules/thali/install/node_modules/findit/test/stop/q/w/c
,11-23 18:51:19.313  5602  5649 W System.err: 	at android.content.res.AssetManager.openAsset(Native Method)
,11-23 18:51:19.313  5602  5649 W System.err: 	at android.content.res.AssetManager.open(AssetManager.java:313)
11-23 18:51:19.313  5602  5649 W System.err: 	at io.jxcore.node.FileManager.aproxFileSize(FileManager.java:48)
11-23 18:51:19.313  5602  5649 W System.err: 	at io.jxcore.node.jxcore.Initialize(jxcore.java:281)
11-23 18:51:19.313  5602  5649 W System.err: 	at io.jxcore.node.jxcore.access$200(jxcore.java:25)
11-23 18:51:19.313  5602  5649 W System.err: 	at io.jxcore.node.jxcore$6.run(jxcore.java:343)
11-23 18:51:19.314  5602  5649 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
11-23 18:51:19.314  5602  5649 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-23 18:51:19.314  5602  5649 W System.err: 	at android.os.Looper.loop(Looper.java:148)
11-23 18:51:19.314  5602  5649 W System.err: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,11-23 18:51:19.329  5602  5611 I art     : Background partial concurrent mark sweep GC freed 59636(6MB) AllocSpace objects, 2(1176KB) LOS objects, 36% free, 27MB/43MB, paused 1.871ms total 106.157ms
,11-23 18:51:19.476  5602  5649 W jxcore-log: Initializing JXcore engine
,11-23 18:51:19.476  5602  5649 W jxcore-log: JXcore engine is ready
,11-23 18:51:19.497  5649  5649 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12503 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-23 18:51:19.497  5649  5649 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15372]" dev="sockfs" ino=15372 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-23 18:51:19.497  5649  5649 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-23 18:51:19.497  5649  5649 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31440]" dev="sockfs" ino=31440 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-23 18:51:19.509  5602  5649 W jxcore-log: Starting JXcore engine
,11-23 18:51:19.559  5602  5649 W jxcore-log: Platform android
11-23 18:51:19.559  5602  5649 W jxcore-log: 
,11-23 18:51:19.560  5602  5649 W jxcore-log: Process ARCH arm
11-23 18:51:19.560  5602  5649 W jxcore-log: 
,11-23 18:51:19.740  5602  5649 I jxcore-log: JXcore Cordova bridge is ready!
11-23 18:51:19.740  5602  5649 I jxcore-log: 
,11-23 18:51:19.740  5602  5649 W jxcore-log: JXcore engine is started
,11-23 18:51:19.757  5602  5641 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-23 18:51:19.761  5602  5602 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-23 18:51:19.762  5602  5602 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-23 18:51:20.475  3602  3602 I ConfigService: onDestroy
,11-23 18:51:20.860   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:51:21.710   929  3174 I ActivityManager: Killing 5241:org.codeaurora.ims/1001 (adj 15): empty #17
,11-23 18:51:21.748   929  3174 I ActivityManager: Killing 5163:com.google.android.youtube/u0a75 (adj 15): empty #18
,11-23 18:51:21.861   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:51:22.861   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:51:23.862   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:51:24.864   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:51:25.864   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 18:51:29.373  5602  5649 I jxcore-log: 2016-11-23 17:51:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-23 18:51:29.373  5602  5649 I jxcore-log: 
,11-23 18:51:29.375  5602  5649 I jxcore-log: 2016-11-23 17:51:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-23 18:51:29.375  5602  5649 I jxcore-log: 
,11-23 18:51:29.382  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-23 18:51:29.382  5602  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 18:51:29.382  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:51:29.382  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:51:29.382  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 18:51:29.382  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 18:51:29.382  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 18:51:29.382  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 18:51:29.382  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 18:51:29.382  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 18:51:29.384  5602  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 18:51:29.387  5602  5649 I jxcore-log: 2016-11-23 17:51:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-23 18:51:29.387  5602  5649 I jxcore-log: 
,11-23 18:51:29.388  5602  5649 I jxcore-log: 2016-11-23 17:51:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-23 18:51:29.388  5602  5649 I jxcore-log: 
,11-23 18:51:29.633  5602  5649 I jxcore-log: 2016-11-23 17:51:29 - DEBUG UnitTest_app: 'Running unit tests'
11-23 18:51:29.633  5602  5649 I jxcore-log: 
,11-23 18:51:29.634  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 18:51:29.634  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f05199c added. We now have 2 listener(s)
11-23 18:51:29.635  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 18:51:29.635  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:51:29.635  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 18:51:29.635  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 18:51:29.635  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da19fa5 added. We now have 2 listener(s)
11-23 18:51:29.635  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 18:51:29.636  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 18:51:29.637  5602  5649 D executeNativeTests: Running unit tests
,11-23 18:51:29.679  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 18:51:29.679  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a added. We now have 3 listener(s)
11-23 18:51:29.680  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 18:51:29.680  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:51:29.680  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 18:51:29.680  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:51:29.680  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b added. We now have 3 listener(s)
,11-23 18:51:29.680  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 18:51:29.681  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 18:51:29.684  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-23 18:51:29.684  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 18:51:29.684  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 18:51:29.684  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 18:51:29.685  5602  5649 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-23 18:51:29.685  5602  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 18:51:29.685  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 18:51:29.685  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 18:51:29.685  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 18:51:29.685  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 18:51:29.685  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:29.686  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:29.686  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:29.686  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:29.686  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:29.686  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:51:29.686  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a removed from the list
11-23 18:51:29.686  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:29.687  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b removed from the list
11-23 18:51:29.687  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:29.687  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.687  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.688  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.688  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.688  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.688  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:29.688  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:29.688  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:29.688  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.,thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:29.689  5602  5649 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-23 18:51:29.689  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:29.689  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:29.690  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:29.690  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:29.690  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:29.690  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:29.690  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:29.690  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:29.690  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:29.690  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:29.690  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.691  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.691  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.691  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.691  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:29.691  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:29.691  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:29.691  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 18:51:29.694  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 18:51:29.695  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 18:51:29.695  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 18:51:29.695  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:29.695  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:29.695  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:29.695  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:29.695  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:29.695  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:29.695  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:29.695  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:29.695  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:29.695  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.695  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.696  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.696  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:29.696  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.696  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:29.696  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:29.696  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:29.696  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:29.697  5602  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 18:51:29.730  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 18:51:29.731  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 18:51:29.736  5602  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 18:51:29.736  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:51:29.736  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:51:29.736  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 18:51:29.736  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 18:51:29.736  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 18:51:29.736  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 18:51:29.736  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 18:51:29.736  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 18:51:29.738  5602  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 18:51:29.738  5602  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 18:51:29.738  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:51:29.738  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 18:51:29.738  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-23 18:51:29.738  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 18:51:29.738  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 18:51:29.743  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 18:51:29.743  5602  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 18:51:29.743  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 18:51:29.743  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:51:29.746  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.746  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 18:51:29.746  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:51:29.748  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 18:51:29.749  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-23 18:51:29.749  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 18:51:29.750  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-23 18:51:29.751  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-23 18:51:29.751  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:29.751  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 18:51:29.751  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 18:51:29.751  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 18:51:29.752  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-23 18:51:29.752  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:29.752  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:51:29.754  4668  4892 D BtGatt.GattService: registerClient() - UUID=46f0dd6e-ced2-4dce-8d21-9f66f808b114
11-23 18:51:29.755  4668  4742 D BtGatt.GattService: onClientRegistered() - UUID=46f0dd6e-ced2-4dce-8d21-9f66f808b114, clientIf=5
11-23 18:51:29.757  5602  5613 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 18:51:29.757  4668  4685 D BtGatt.GattService: start scan with filters
,11-23 18:51:29.761  4668  4745 D BtGatt.ScanManager: handling starting scan
11-23 18:51:29.761  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 18:51:29.761  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.761  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 18:51:29.761  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.761  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-23 18:51:29.761  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 18:51:29.762  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 18:51:29.762  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:51:29.762  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.762  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 18:51:29.762  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 18:51:29.762  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 18:51:29.762  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 18:51:29.763  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:51:29.763  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 18:51:29.764  4668  4745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:51:29.766  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.767  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.767  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:29.767  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 18:51:29.767  5602  5649 I io.jxcore.node.ConnectionHelper: start: OK
,11-23 18:51:29.770  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:51:29.770  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:51:29.771  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:51:29.771  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 18:51:29.771  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:51:29.771  4668  4742 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 18:51:29.772  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:51:29.772  4668  4745 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 18:51:29.776  3970  5650 W CronetSyncConnectionRcs: Upload content type not set.
11-23 18:51:29.777  4668  4742 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 18:51:29.777  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:29.777  4668  4745 D BtGatt.ScanManager: Starting BLE batch scan
11-23 18:51:29.777  4668  4745 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 18:51:29.786  4668  4742 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 18:51:29.786  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:51:29.791  4668  4742 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 18:51:29.791  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:51:29.843  4878  4922 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-23 18:51:29.844  4878  4878 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-23 18:51:30.272  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 18:51:30.272  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:51:30.273  5602  5602 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 18:51:34.772  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:34.772  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:34.772  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-23 18:51:34.772  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:51:34.772  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 18:51:34.772  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:34.773  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 18:51:34.773  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 18:51:34.773  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.773  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 18:51:34.773  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 18:51:34.774  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.774  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.774  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.775  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 18:51:34.775  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:34.776  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:51:34.776  4668  4892 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 18:51:34.776  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 18:51:34.778  4668  4745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 18:51:34.780  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:51:34.780  4668  4900 D BtGatt.GattService: stopScan() - queue size =1
,11-23 18:51:34.781  4668  4688 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 18:51:34.782  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-23 18:51:34.782  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:34.782  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-23 18:51:34.782  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.782  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.782  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.782  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:34.783  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 18:51:34.783  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.783  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.783  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.783  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 18:51:34.784  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 18:51:34.785  4668  4668 D BtGatt.ScanManager: awakened up at time 97412
11-23 18:51:34.786  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:51:34.788  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.791  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.791  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:51:34.792  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.792  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:34.792  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:34.792  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:51:34.792  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:51:34.793  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:51:34.792  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:51:34.793  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-23 18:51:34.793  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:34.793  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:51:34.793  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:34.793  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 18:51:34.793  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:34.793  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 18:51:34.794  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:34.794  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:34.794  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 18:51:34.794  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 18:51:34.794  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 18:51:34.794  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:51:34.794  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:51:34.794  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 18:51:34.795  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 18:51:34.798  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:51:34.798  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:51:34.798  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 18:51:34.812  4668  4742 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-23 18:51:34.812  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:34.813  4668  4742 D BtGatt.GattService: current time is 97440213268
11-23 18:51:34.813  4668  4742 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -80, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -91, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -82, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 18:51:34.815  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 18:51:34.815  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-23 18:51:34.816  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 18:51:34.816  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 18:51:34.816  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 18:51:34.816  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-23 18:51:34.823  4668  4742 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 18:51:34.823  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:34.823  4668  4745 D BtGatt.ScanManager: stopping BLe Batch
,11-23 18:51:34.830  4668  4742 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 18:51:34.830  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:34.831  4668  4745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 18:51:34.837  4668  4742 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 18:51:34.837  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:51:35.296  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 18:51:39.796  5602  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 18:51:39.802  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 18:51:39.802  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 18:51:39.817  5602  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 18:51:39.817  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:51:39.817  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:51:39.817  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 18:51:39.817  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 18:51:39.817  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 18:51:39.817  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 18:51:39.817  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 18:51:39.817  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 18:51:39.821  5602  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 18:51:39.821  5602  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-23 18:51:39.821  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:51:39.821  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 18:51:39.821  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 18:51:39.821  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 18:51:39.821  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 18:51:39.826  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 18:51:39.830  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 18:51:39.831  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 18:51:39.832  5602  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 18:51:39.832  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 18:51:39.837  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:39.837  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 18:51:39.838  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 18:51:39.838  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 18:51:39.838  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 18:51:39.842  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.842  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-23 18:51:39.842  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 18:51:39.842  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-23 18:51:39.842  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-23 18:51:39.843  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:39.844  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:51:39.846  4668  4900 D BtGatt.GattService: registerClient() - UUID=daf9ae22-c074-466f-bc13-8090b966bc45
11-23 18:51:39.847  4668  4742 D BtGatt.GattService: onClientRegistered() - UUID=daf9ae22-c074-466f-bc13-8090b966bc45, clientIf=5
,11-23 18:51:39.848  5602  5613 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 18:51:39.849  4668  4688 D BtGatt.GattService: start scan with filters
,11-23 18:51:39.852  4668  4745 D BtGatt.ScanManager: handling starting scan
11-23 18:51:39.853  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 18:51:39.854  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.854  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 18:51:39.854  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.854  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 18:51:39.854  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-23 18:51:39.854  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.854  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 18:51:39.854  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 18:51:39.854  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.854  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.855  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.855  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.856  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 18:51:39.856  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.858  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.858  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:51:39.858  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.859  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.859  5602  5649 I io.jxcore.node.ConnectionHelper: start: OK
,11-23 18:51:39.859  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.860  4668  4742 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 18:51:39.860  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:39.860  4668  4745 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 18:51:39.862  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:39.862  5602  5649 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 18:51:39.862  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:39.862  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 18:51:39.862  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:51:39.862  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 18:51:39.862  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:39.863  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 18:51:39.864  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.864  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.864  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.864  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:51:39.864  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 18:51:39.864  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.864  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 18:51:39.865  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 18:51:39.865  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.865  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.865  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.865  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 18:51:39.865  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.866  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:51:39.866  4668  4900 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 18:51:39.866  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-23 18:51:39.867  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:51:39.867  4668  4742 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 18:51:39.867  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:39.867  4668  4745 D BtGatt.ScanManager: Starting BLE batch scan
11-23 18:51:39.867  4668  4745 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 18:51:39.867  4668  4892 D BtGatt.GattService: stopScan() - queue size =1
,11-23 18:51:39.868  4668  4685 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 18:51:39.868  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.869  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-23 18:51:39.869  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 18:51:39.870  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:51:39.870  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.871  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.871  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:51:39.871  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:39.871  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.871  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:39.871  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:51:39.871  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:51:39.872  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:51:39.872  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:51:39.872  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:39.872  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 18:51:39.872  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:39.872  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.872  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:39.872  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:39.872  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 18:51:39.872  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:39.872  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 18:51:39.872  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 18:51:39.872  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.872  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.872  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 18:51:39.872  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:51:39.872  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.872  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.873  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.874  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.874  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.874  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.874  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:39.876  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.876  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.876  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.876  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:39.876  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:39.876  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:39.876  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:39.877  5602  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 18:51:39.879  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 18:51:39.879  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 18:51:39.879  4668  4742 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-23 18:51:39.879  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:51:39.885  5602  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 18:51:39.885  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:51:39.885  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:51:39.885  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 18:51:39.885  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 18:51:39.885  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 18:51:39.885  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 18:51:39.885  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 18:51:39.885  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 18:51:39.888  5602  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 18:51:39.888  5602  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 18:51:39.888  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:51:39.888  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-23 18:51:39.889  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 18:51:39.889  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 18:51:39.889  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 18:51:39.889  4668  4742 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 18:51:39.889  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:51:39.891  4668  4745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 18:51:39.891  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 18:51:39.892  5602  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-23 18:51:39.892  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 18:51:39.892  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:51:39.896  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 18:51:39.896  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.896  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 18:51:39.897  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 18:51:39.897  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 18:51:39.897  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 18:51:39.897  4668  4742 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 18:51:39.897  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:39.897  4668  4742 E BtGatt.ContextMap: Context not found for ID 5
11-23 18:51:39.900  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.900  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 18:51:39.900  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 18:51:39.900  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 18:51:39.900  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 18:51:39.900  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.901  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:51:39.902  4668  4892 D BtGatt.GattService: registerClient() - UUID=e739a72b-991d-4a0f-8373-0fcfc112cb52
11-23 18:51:39.903  4668  4742 D BtGatt.GattService: onClientRegistered() - UUID=e739a72b-991d-4a0f-8373-0fcfc112cb52, clientIf=5
11-23 18:51:39.903  5602  5612 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 18:51:39.903  4668  4688 D BtGatt.GattService: start scan with filters
11-23 18:51:39.904  4668  4742 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 18:51:39.904  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:39.904  4668  4745 D BtGatt.ScanManager: stopping BLe Batch
,11-23 18:51:39.905  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 18:51:39.905  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.905  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 18:51:39.905  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.905  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 18:51:39.905  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 18:51:39.905  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.905  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 18:51:39.905  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 18:51:39.905  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.906  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.906  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.906  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.906  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 18:51:39.907  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.909  4668  4742 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 18:51:39.909  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:39.909  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.909  4668  4745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 18:51:39.909  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:51:39.909  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.909  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:39.909  5602  5649 I io.jxcore.node.ConnectionHelper: start: OK
11-23 18:51:39.910  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 18:51:39.913  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.913  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.913  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 18:51:39.914  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:51:39.914  4668  4742 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 18:51:39.914  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:51:39.915  4668  4745 D BtGatt.ScanManager: handling starting scan
,11-23 18:51:39.921  4668  4742 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-23 18:51:39.921  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:39.921  4668  4745 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 18:51:39.926  4668  4742 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 18:51:39.926  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:39.926  4668  4745 D BtGatt.ScanManager: Starting BLE batch scan
,11-23 18:51:39.926  4668  4745 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 18:51:39.935  4668  4742 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 18:51:39.935  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:51:39.940  4668  4742 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 18:51:39.940  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:51:40.415  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-23 18:51:40.415  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 18:51:40.415  5602  5602 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 18:51:44.910  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 18:51:44.910  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:44.910  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 18:51:44.911  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:51:44.911  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 18:51:44.911  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 18:51:44.911  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 18:51:44.911  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 18:51:44.912  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.912  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 18:51:44.912  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-23 18:51:44.912  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.912  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.913  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.913  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 18:51:44.913  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:44.915  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:51:44.915  4668  4688 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 18:51:44.917  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 18:51:44.918  4668  4745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 18:51:44.921  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:51:44.922  4668  4685 D BtGatt.GattService: stopScan() - queue size =1
11-23 18:51:44.924  4668  4892 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-23 18:51:44.925  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 18:51:44.925  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.926  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 18:51:44.926  4668  4668 D BtGatt.ScanManager: awakened up at time 107553
11-23 18:51:44.926  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:44.926  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.926  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.927  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.927  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 18:51:44.927  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.927  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:44.927  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.927  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 18:51:44.928  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 18:51:44.928   929  5463 I ActivityManager: Killing 5280:com.android.settings/1000 (adj 15): empty #17
,11-23 18:51:44.946  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 18:51:44.947  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.948  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:44.948  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:51:44.948  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.948  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:44.948  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 18:51:44.948  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:51:44.949  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 18:51:44.949  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:51:44.949  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 18:51:44.949  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 18:51:44.949  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-23 18:51:44.949  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 18:51:44.949  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:51:44.949  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:51:44.949  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 18:51:44.949  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 18:51:44.951  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:51:44.951  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:51:44.951  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 18:51:44.960  4668  4742 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-23 18:51:44.960  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:44.960  4668  4742 D BtGatt.GattService: current time is 107587978788
11-23 18:51:44.961  4668  4742 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -95, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -91, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -94, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 18:51:44.961  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 18:51:44.961  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 18:51:44.961  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 18:51:44.962  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 18:51:44.962  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 18:51:44.962  4668  4742 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-23 18:51:44.967  4668  4742 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 18:51:44.967  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:44.968  4668  4745 D BtGatt.ScanManager: stopping BLe Batch
,11-23 18:51:44.972  4668  4742 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 18:51:44.973  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:51:44.973  4668  4745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 18:51:44.978  4668  4742 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 18:51:44.978  4668  4742 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:51:45.450  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 18:51:45.450  5602  5602 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 18:51:45.450  5602  5602 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 18:51:49.950  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 18:51:49.950  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 18:51:49.950  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:49.951  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:49.951  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:51:49.951  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 18:51:49.951  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:49.951  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:49.951  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:49.952  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.952  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:49.952  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 18:51:49.954  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.955  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.958  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.958  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.959  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.959  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:49.959  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:49.959  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:49.959  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.961  5602  5649 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-23 18:51:49.963  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:49.963  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:49.963  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 18:51:49.963  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:49.964  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:49.964  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:49.964  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:49.964  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.964  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:49.965  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.965  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.968  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.968  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.968  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.969  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 18:51:49.969  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:49.969  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:49.969  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.971  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-23 18:51:49.971  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:49.972  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:49.972  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:49.972  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:49.972  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:49.972  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:49.972  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:49.973  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.973  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 18:51:49.973  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.973  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.975  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.975  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.976  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.976  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:49.976  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 18:51:49.976  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:49.976  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
,11-23 18:51:49.977  5602  5649 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-23 18:51:49.978  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:49.978  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 18:51:49.978  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:49.978  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:49.978  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:49.978  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:49.978  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:49.979  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.979  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 18:51:49.979  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.979  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.982  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.982  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.982  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.982  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:49.982  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:49.982  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:49.983  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.984  5602  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-23 18:51:49.984  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:49.985  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:49.985  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:49.985  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:49.985  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 18:51:49.985  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:49.985  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:49.985  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.985  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:49.986  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.986  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.988  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.988  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.988  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.988  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:49.988  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:49.989  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:49.989  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.990  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 18:51:49.990  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 18:51:49.991  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 18:51:49.991  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 18:51:49.991  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 18:51:49.991  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 18:51:49.991  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 18:51:49.991  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 18:51:49.991  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 18:51:49.991  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:49.992  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:49.992  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:49.992  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 18:51:49.992  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:49.992  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:49.992  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:49.992  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.992  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:49.993  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.993  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.995  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:49.995  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.995  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:49.995  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:49.995  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:49.995  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:49.996  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:49.997  5602  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 18:51:49.997  5602  5649 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-23 18:51:49.997  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 18:51:50.001  5602  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 18:51:50.001  5602  5649 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-23 18:51:50.001  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 18:51:50.001  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 18:51:50.001  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 18:51:50.001  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 18:51:50.001  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 18:51:50.001  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 18:51:50.001  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 18:51:50.001  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-23 18:51:50.002  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 18:51:50.003  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 18:51:50.003  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 18:51:50.003  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 18:51:50.003  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 18:51:50.003  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 18:51:50.003  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 18:51:50.003  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 18:51:50.003  5602  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-23 18:51:50.003  5602  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 18:51:50.004  5602  5649 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,11-23 18:51:50.004  5602  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 18:51:50.004  5602  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 18:51:50.004  5602  5649 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-23 18:51:50.004  5602  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 18:51:50.004  5602  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 18:51:50.004  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-23 18:51:50.009  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-23 18:51:50.010  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-23 18:51:50.010  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-23 18:51:50.010  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-23 18:51:50.011  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-23 18:51:50.011  5602  5649 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-23 18:51:50.011  5602  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 18:51:50.011  5602  5649 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-23 18:51:50.011  5602  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
11-23 18:51:50.011  5602  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-23 18:51:50.011  5602  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-23 18:51:50.011  5602  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-23 18:51:50.012  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:50.012  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:50.012  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:50.012  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 18:51:50.010  4892  4892 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32890]" dev="sockfs" ino=32890 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 18:51:50.010  4892  4892 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32890]" dev="sockfs" ino=32890 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 18:51:50.012  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:50.014  5602  5654 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-23 18:51:50.014  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-23 18:51:50.014  5602  5654 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 18:51:50.014  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
,11-23 18:51:50.014  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:50.015  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:50.015  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:50.015  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.015  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.016  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.016  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.016  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:50.016  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:50.016  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:50.016  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:50.016  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:50.017  5602  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
11-23 18:51:50.017  5602  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-23 18:51:50.017  5602  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
,11-23 18:51:50.017  5602  5654 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-23 18:51:50.017  5602  5649 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-23 18:51:50.017  5602  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
11-23 18:51:50.017  5602  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-23 18:51:50.017  5602  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
11-23 18:51:50.017  4668  4890 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
,11-23 18:51:50.018  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:50.018  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:50.018  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:50.018  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:50.018  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:50.018  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:50.018  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:50.018  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
,11-23 18:51:50.018  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:50.019  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.020  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.021  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.021  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.021  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.021  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 18:51:50.022  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:50.022  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:50.022  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:50.022  5602  5649 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-23 18:51:50.023  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:50.023  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:50.023  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:50.023  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:50.023  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:50.023  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:50.023  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:50.023  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
,11-23 18:51:50.023  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:50.023  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.023  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.025  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.025  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.025  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.025  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:50.025  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:50.025  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:50.025  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
,11-23 18:51:50.026  5602  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-23 18:51:50.026  5602  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-23 18:51:50.026  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 18:51:50.026  5602  5649 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-23 18:51:50.026  5602  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 18:51:50.026  5602  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-23 18:51:50.026  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 18:51:50.026  5602  5649 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,11-23 18:51:50.026  5602  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 18:51:50.026  5602  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 18:51:50.026  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 18:51:50.026  5602  5649 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-23 18:51:50.027  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:50.027  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:50.027  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:50.027  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:50.027  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:50.027  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:50.027  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:50.027  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:50.027  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:50.027  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:50.027  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.028  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.028  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.028  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:50.028  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:50.028  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:50.029  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:50.029  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:50.029  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:50.029  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:50.029  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:50.029  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:50.029  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
,11-23 18:51:50.030  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 18:51:50.865   598   598 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-23 18:51:50.866   598   598 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 18:51:55.030  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:55.031  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.031  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:55.031  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:55.031  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
,11-23 18:51:55.031  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:55.032  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:55.032  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 18:51:55.032  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:55.032  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:55.032  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:55.033  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:55.033  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.033  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:55.033  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.034  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:55.037  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.037  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.037  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.037  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:55.038  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:55.038  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:55.038  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.042  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-23 18:51:55.043  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 18:51:55.043  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 18:51:55.048  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-23 18:51:55.050  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-23 18:51:55.050  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-23 18:51:55.051  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-23 18:51:55.051  5602  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-23 18:51:55.051  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-23 18:51:55.051  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 18:51:55.051  5602  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-23 18:51:55.051  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:55.051  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-23 18:51:55.052  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-23 18:51:55.052  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-23 18:51:55.052  5602  5656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 18:51:55.052  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 18:51:55.052  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 18:51:55.052  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-23 18:51:55.053  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:55.053  5602  5602 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-23 18:51:55.053  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:55.053  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 18:51:55.053  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:55.053  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 18:51:55.053  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 18:51:55.053  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.050  4685  4685 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32895]" dev="sockfs" ino=32895 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 18:51:55.050  4685  4685 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32895]" dev="sockfs" ino=32895 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 18:51:55.055  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:55.055  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:51:55.055  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.055  5602  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-23 18:51:55.055  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.055  5602  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-23 18:51:55.055  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.055  5602  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-23 18:51:55.055  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:51:55.055  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:55.055  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:51:55.055  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:55.055  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:55.056  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:51:55.056  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:55.056  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 18:51:55.056  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-23 18:51:55.056  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:55.056  5602  5602 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:55.056  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:55.056  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.056  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:55.056  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.057  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.058  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.058  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.058  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.058  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:55.058  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:55.058  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:55.058  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.060  5602  5649 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-23 18:51:55.060  5602  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 18:51:55.060  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-23 18:51:55.060  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 18:51:55.060  5602  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 18:51:55.061  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:55.061  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:55.061  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:55.061  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:55.061  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 18:51:55.061  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:55.061  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:55.061  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.061  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:55.061  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.061  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.063  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.063  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:55.063  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.063  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:55.064  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:55.064  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:55.064  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
,11-23 18:51:55.070  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 18:51:55.071  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:55.071  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:55.071  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:55.071  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:51:55.071  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:55.071  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:55.071  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.071  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:55.071  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.071  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:55.072  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.072  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.072  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.072  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:55.072  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:55.072  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:51:55.072  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.073  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:51:55.073  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:51:55.073  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:51:55.073  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:51:55.073  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 18:51:55.074  5602  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce6ab2a not in the list
11-23 18:51:55.074  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:55.074  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.074  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:51:55.074  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.074  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:55.075  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:51:55.076  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.076  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:51:55.076  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:51:55.076  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:51:55.076  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:51:55.076  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9dd1b not in the list
11-23 18:51:55.077  5602  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-23 18:51:55.077  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 18:51:55.077  5602  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-23 18:51:55.077  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 18:51:55.077  5602  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-23 18:51:55.077  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 18:51:55.079  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 18:51:55.079  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-23 18:51:55.080  5602  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-23 18:51:55.080  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 18:51:55.080  5602  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-23 18:51:55.080  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 18:51:55.080  5602  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-23 18:51:55.080  5602  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-23 18:51:55.081  5602  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-23 18:51:55.081  5602  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-23 18:51:55.081  5602  5649 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-23 18:51:55.081  5602  5649 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-23 18:51:55.081  5602  5649 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-23 18:51:55.081  5602  5649 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-23 18:51:55.082  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:51:55.082  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd415e8 added. We now have 3 listener(s)
11-23 18:51:55.082  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 18:51:55.084  5602  5649 D BluetoothAdapter: enable(): BT is already enabled..!
11-23 18:51:55.085   929  5463 D WifiService: setWifiEnabled: true pid=5602, uid=10077
,11-23 18:51:55.085   929  5463 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 18:51:55.145  4668  4864 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-23 18:51:55.145  4668  4864 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-23 18:51:55.557  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 18:51:55.867   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:51:56.868   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:51:57.869   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:51:58.107   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:51:58.870   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:51:59.871   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:00.088  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 18:52:00.088  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6a3401 added. We now have 4 listener(s)
11-23 18:52:00.088  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 18:52:00.091  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:00.091  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6a3401 removed from the list
11-23 18:52:00.092  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:52:00.092  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:00.092  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d6a2a6 added. We now have 4 listener(s)
,11-23 18:52:00.092  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 18:52:00.094  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:00.094  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d6a2a6 removed from the list
11-23 18:52:00.094  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 18:52:00.095  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 18:52:00.095  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5604e7 added. We now have 4 listener(s)
11-23 18:52:00.095  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 18:52:00.097   929  5463 D WifiService: setWifiEnabled: false pid=5602, uid=10077
11-23 18:52:00.097   929  5463 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-23 18:52:00.099   929  2989 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-23 18:52:00.099   929  2989 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-23 18:52:00.099   929  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 18:52:00.099   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 18:52:00.102  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 18:52:00.102  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 18:52:00.102  4668  4738 D BluetoothAdapterState: Current state: ON, message: 23
11-23 18:52:00.102  4668  4738 D BluetoothAdapterProperties: Setting state to 13
11-23 18:52:00.102  4668  4738 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 18:52:00.104  4668  4738 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 18:52:00.104  4668  4738 I BluetoothAdapterState: Entering PendingCommandState
,11-23 18:52:00.108  4668  4668 D BluetoothMapService: onReceive
11-23 18:52:00.108  4668  4668 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 18:52:00.108  4668  4668 D BluetoothMapService: STATE_TURNING_OFF
,11-23 18:52:00.108  4668  4668 D BluetoothMapService: MAP Service closeService in
11-23 18:52:00.108  4668  4668 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 18:52:00.108  4668  4668 D ObexServerSockets0: shutdown(block = true)
11-23 18:52:00.109  4668  4668 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 18:52:00.109  4668  4668 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 18:52:00.109  4668  4903 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 18:52:00.110  4668  4890 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 18:52:00.111  4668  4902 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-23 18:52:00.113   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-23 18:52:00.113   929  5374 D DhcpClient: Clearing IP address
,11-23 18:52:00.117  4668  4668 I BtOppRfcommListener: stopping Accept Thread
11-23 18:52:00.117  4668  5301 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 18:52:00.117  4668  5301 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-23 18:52:00.120   508   922 D CommandListener: Setting iface cfg
,11-23 18:52:00.125  3602  5425 V NativeCrypto: Read error: ssl=0x7f871c9380: I/O error during system call, Connection timed out
,11-23 18:52:00.126   929   942 I ActivityManager: Start proc 5660:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-23 18:52:00.127  3602  5425 V NativeCrypto: SSL shutdown failed: ssl=0x7f871c9380: I/O error during system call, Broken pipe
11-23 18:52:00.127  4668  4742 D BluetoothAdapterProperties: Scan Mode:20
11-23 18:52:00.127  4668  4738 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-23 18:52:00.130   929  5463 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-23 18:52:00.130   929  5372 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-23 18:52:00.132   929  5372 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-23 18:52:00.133   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-23 18:52:00.133   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-23 18:52:00.134  4668  4668 D HeadsetService: Received stop request...Stopping profile...
11-23 18:52:00.134  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:00.134  5602  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 18:52:00.134  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:52:00.134  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:52:00.134  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 18:52:00.134  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 18:52:00.134  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 18:52:00.134  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 18:52:00.134  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 18:52:00.134  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 18:52:00.134   929  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-23 18:52:00.135  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:00.136  5602  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 18:52:00.136  5602  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 18:52:00.138   596   596 E Parcel  : Reading a NULL string not supported here.
11-23 18:52:00.138   929  5375 D DhcpClient: Receive thread stopped
11-23 18:52:00.138   929   929 D RttService: SCAN_AVAILABLE : 1
11-23 18:52:00.138   929  3098 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 18:52:00.139  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 18:52:00.140  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 18:52:00.140  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:52:00.140  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:52:00.140  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 18:52:00.140  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 18:52:00.140  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 18:52:00.140  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-23 18:52:00.140  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 18:52:00.140  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 18:52:00.140  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:00.140  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-23 18:52:00.143  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:52:00.143  3803  3824 D BluetoothHeadset: Proxy object disconnected
11-23 18:52:00.144  4668  4668 D A2dpService: Received stop request...Stopping profile...
11-23 18:52:00.144   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 18:52:00.144  4668  4895 D A2dpStateMachine: Exit Disconnected: -1
11-23 18:52:00.144  3146  3997 D BluetoothHeadset: Proxy object disconnected
11-23 18:52:00.144   929   929 D BluetoothHeadset: Proxy object disconnected
,11-23 18:52:00.144   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 18:52:00.145   929   929 D BluetoothA2dp: Proxy object disconnected
11-23 18:52:00.146   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 18:52:00.146   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-23 18:52:00.146  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:52:00.146  4668  4668 D HidService: Received stop request...Stopping profile...
11-23 18:52:00.147  4668  4668 D HidService: Stopping Bluetooth HidService
,11-23 18:52:00.148  4668  4668 D HealthService: Received stop request...Stopping profile...
,11-23 18:52:00.149  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:00.149  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:00.149  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:00.149  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:00.150  4668  4668 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 18:52:00.150  4668  4668 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 18:52:00.150  4668  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 18:52:00.150  4668  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 18:52:00.150  4668  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 18:52:00.151  4668  4742 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 18:52:00.151   929  2991 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-23 18:52:00.151  4668  4742 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-23 18:52:00.151  4668  4668 D PanService: Received stop request...Stopping profile...
,11-23 18:52:00.153  4668  4668 V BluetoothAdapterState: isTurningOff()=true
,11-23 18:52:00.153  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:00.153  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 18:52:00.153  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:00.153  3771  3891 W QCNEJ   : |CORE| network lost: 100
11-23 18:52:00.154  3771  3891 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 18:52:00.154  4668  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 18:52:00.154  4668  4742 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 18:52:00.154  4668  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 18:52:00.154  4668  4864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 18:52:00.154  4668  4864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 18:52:00.154  4668  4864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 18:52:00.154  4668  4864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 18:52:00.155  4668  4668 D BluetoothMapService: Received stop request...Stopping profile...
11-23 18:52:00.155  4668  4668 D BluetoothMapService: stop()
11-23 18:52:00.156  4668  4668 D BluetoothMapAppObserver: deinitObservers()
11-23 18:52:00.156  4668  4668 D BluetoothMapAppObserver: removeReceiver()
11-23 18:52:00.157  3146  3146 D HeadsetProfile: Bluetooth service disconnected
11-23 18:52:00.157  3146  3146 D BluetoothA2dp: Proxy object disconnected
11-23 18:52:00.157  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:00.157  3146  3146 D BluetoothInputDevice: Proxy object disconnected
11-23 18:52:00.157  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:00.157  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:00.157  3146  3146 D HidProfile: Bluetooth service disconnected
11-23 18:52:00.157  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:00.157  3146  3146 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 18:52:00.158  3146  3146 D PanProfile: Bluetooth service disconnected
11-23 18:52:00.158  4668  4668 D SapService: Received stop request...Stopping profile...
11-23 18:52:00.158  4668  4668 V SapService: stop()
11-23 18:52:00.159  3146  3146 D BluetoothMap: Proxy object disconnected
11-23 18:52:00.160  3146  3146 D MapProfile: Bluetooth service disconnected
11-23 18:52:00.160  4668  4668 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-23 18:52:00.161  4668  4668 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 18:52:00.161  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:00.161  4668  4742 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 18:52:00.161  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:00.161  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:00.161  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:00.162  4668  4668 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 18:52:00.162  4668  4742 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 18:52:00.162  4668  4668 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 18:52:00.162  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:00.163  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:00.163  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:00.163  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:00.163  4668  4668 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 18:52:00.163  4668  4668 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 18:52:00.164  4668  4668 D BluetoothMapService: MAP Service closeService in
11-23 18:52:00.164  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:00.164  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:00.164  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:00.164  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:00.164  4668  4668 D BluetoothMapService: cleanup()
11-23 18:52:00.164  4668  4668 D BluetoothMapService: MAP Service closeService in
,11-23 18:52:00.165  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:00.165  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:00.165  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:00.165  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:00.165  4668  4738 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 18:52:00.165  4668  4738 D BluetoothAdapterProperties: Setting state to 15
11-23 18:52:00.165  4668  4738 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 18:52:00.165  4668  4738 I BluetoothAdapterState: Entering BleOnState
11-23 18:52:00.168  3146  3997 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 18:52:00.171  3146  3157 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 18:52:00.171  3803  3832 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 18:52:00.172   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 18:52:00.172   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 18:52:00.172  3146  3159 D BluetoothMap: onBluetoothStateChange: up=false
11-23 18:52:00.172  3146  3997 D BluetoothPan: onBluetoothStateChange on: false
11-23 18:52:00.173  3146  3157 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 18:52:00.173   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 18:52:00.174  3146  3159 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 18:52:00.174   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 18:52:00.175  4668  4738 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 18:52:00.175  4668  4738 D BluetoothAdapterProperties: Setting state to 16
,11-23 18:52:00.175  4668  4738 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 18:52:00.175  4668  4738 D BluetoothAdapterProperties: onBleDisable
11-23 18:52:00.176  4668  4738 I BluetoothAdapterState: Entering PendingCommandState
11-23 18:52:00.176  4668  4739 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 18:52:00.177  4668  4864 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 18:52:00.177  4668  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 18:52:00.177  4668  4742 D BluetoothAdapterProperties: Scan Mode:20
,11-23 18:52:00.180  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:00.180  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 18:52:00.180  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:52:00.180  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:52:00.180  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 18:52:00.180  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 18:52:00.180  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 18:52:00.180  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 18:52:00.180  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 18:52:00.180  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 18:52:00.181  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:00.181  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 18:52:00.183  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 18:52:00.188   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 18:52:00.190   929  2989 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-23 18:52:00.190   929  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 18:52:00.202  5660  5660 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-23 18:52:00.211   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 18:52:00.211   508   922 D CommandListener: Clearing all IP addresses on wlan0
11-23 18:52:00.212   508   922 D TetherController: Setting IP forward enable = 0
11-23 18:52:00.212  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 18:52:00.213   929  2991 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-23 18:52:00.213   929  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 18:52:00.214   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-23 18:52:00.217  5258  5258 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dfa0f7a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-23 18:52:00.217   929  2989 D DhcpClient: doQuit
11-23 18:52:00.218   929  2989 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 18:52:00.218   929  5374 D DhcpClient: onQuitting
,11-23 18:52:00.219  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:52:00.219  3456  3456 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 18:52:00.221  3970  3970 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-23 18:52:00.224  5037  5051 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 18:52:00.224  5037  5051 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 18:52:00.224  5037  5051 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 18:52:00.224  5037  5051 E SarControlService: no key has been found,reset the power
11-23 18:52:00.224  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:00.224  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 18:52:00.224  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:52:00.224  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:52:00.224  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 18:52:00.224  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 18:52:00.224  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 18:52:00.224  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 18:52:00.224  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 18:52:00.224  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 18:52:00.224  5037  5084 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-23 18:52:00.224  5037  5084 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 18:52:00.224  5037  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 18:52:00.225  5065  5065 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 18:52:00.225  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:00.225  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 18:52:00.225  5065  5065 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 18:52:00.226  5037  5084 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 18:52:00.226  5037  5084 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 18:52:00.226  5037  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-23 18:52:00.227  5065  5065 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 18:52:00.227  5065  5065 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 18:52:00.230  5065  5086 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402c9b0 HexData = [00000000ea03000000000000ffffffff]
11-23 18:52:00.231  5065  5086 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 18:52:00.231  5065  5086 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-23 18:52:00.231  5065  5065 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 18:52:00.231  5037  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 18:52:00.236   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4b104f1:true
11-23 18:52:00.237  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 18:52:00.237  5065  5086 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402c9b0 HexData = [00000000eb03000000000000ffffffff]
11-23 18:52:00.238  5065  5086 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 18:52:00.238  5065  5086 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-23 18:52:00.238  5065  5065 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 18:52:00.239  5037  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 18:52:00.240  3456  3456 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 18:52:00.248  3456  3456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 18:52:00.258  5660  5660 D LocalBluetoothProfileManager: Adding local MAP profile
11-23 18:52:00.260  5660  5660 D BluetoothMap: Create BluetoothMap proxy object
,11-23 18:52:00.269  5660  5660 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-23 18:52:00.274  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,11-23 18:52:00.276   508   922 E Netd    : netlink response contains error (No such file or directory)
,11-23 18:52:00.277   508   922 D TetherController: Setting IP forward enable = 0
,11-23 18:52:00.277  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 18:52:00.278   929  2991 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 18:52:00.282  5660  5660 D DockEventReceiver: finishStartingService: stopping service
11-23 18:52:00.282  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 18:52:00.284   929  3435 I ActivityManager: Killing 5399:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-23 18:52:00.286  3456  3456 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 18:52:00.300  3456  3456 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 18:52:00.316  4087  4087 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 18:52:00.319  4087  4087 D SystemUpdateService: onCreate
,11-23 18:52:00.322  4087  4087 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 18:52:00.330  4087  4087 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 18:52:00.334  4087  5697 I SystemUpdateService: active receiver: enabled
,11-23 18:52:00.335  4087  5396 I iu.UploadsManager: num queued entries: 0
,11-23 18:52:00.335  4087  5396 I iu.UploadsManager: num updated entries: 0
,11-23 18:52:00.339  4087  4087 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 18:52:00.341  4087  4087 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 18:52:00.342  4087  5697 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-23 18:52:00.343  4087  5396 I iu.SyncManager: NEXT; no task
11-23 18:52:00.344  4087  5697 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-23 18:52:00.344  4087  5697 I SystemUpdateService: now status is 0 (complete)
11-23 18:52:00.344  4087  5697 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 18:52:00.344  4087  5697 I SystemUpdateService: file has been verified
11-23 18:52:00.345  4087  5697 I SystemUpdateService: OTA package size = 21989297
,11-23 18:52:00.350  4087  5697 I SystemUpdateService: showing system update notification
,11-23 18:52:00.352   929  3173 I ActivityManager: Start proc 5699:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-23 18:52:00.365   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 18:52:00.367  4087  4087 D SystemUpdateService: onDestroy
,11-23 18:52:00.384  4668  4742 I bt_hci  : shut_down
11-23 18:52:00.389  4668  4746 D bt_hwcfg: hw_epilog_process
11-23 18:52:00.389  4668  4746 I bt_vendor: low_power_mode_cb
11-23 18:52:00.391  4668  4746 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-23 18:52:00.391  4668  4746 I bt_vendor: epilog_cb
11-23 18:52:00.391  4668  4746 I bt_hci  : epilog_finished_callback
11-23 18:52:00.394  4668  4742 I bt_hci_h4: hal_close
11-23 18:52:00.395  4668  4742 I bt_userial_vendor: device fd = 54 close
11-23 18:52:00.395  5699  5699 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
11-23 18:52:00.399  5699  5699 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 18:52:00.404  4478  4478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 18:52:00.404   929  2989 D wifi    : In wifi stop Hal
11-23 18:52:00.404   929  2989 D wifi    : halHandle = 0x7f74a5e680, mVM = 0x7f9104d140, mCls = 0x1009fa
11-23 18:52:00.404   929  3455 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 18:52:00.404   929  3455 D WifiHAL : Got a signal to exit!!!
11-23 18:52:00.404   929  3455 I WifiHAL : Exit wifi_event_loop
11-23 18:52:00.405   929  2989 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-23 18:52:00.405   929  2989 E WifiHAL : Event processing terminated
11-23 18:52:00.406   929  2989 D wifi    : In wifi cleaned up handler
11-23 18:52:00.406   929  2989 I WifiHAL : Internal cleanup completed
,11-23 18:52:00.407  3956  4235 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 18:52:00.407  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 18:52:00.409  5699  5699 D SprintDMHelper: simOperator: 
,11-23 18:52:00.409  5699  5699 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 18:52:00.423  4478  5711 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 18:52:00.425   929  5463 I ActivityManager: Killing 5258:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-23 18:52:00.428   929  3455 D wifi    : set interface wlan0 flags (DOWN)
,11-23 18:52:00.428   929  2989 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 18:52:00.453   929  5463 I ActivityManager: Start proc 5712:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-23 18:52:00.481  5712  5712 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-23 18:52:00.488   929  3435 I ActivityManager: Killing 5475:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-23 18:52:00.509  4668  4739 D bt_stack_manager: event_shut_down_stack finished.
,11-23 18:52:00.510  4668  4738 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 18:52:00.511  4668  4738 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-23 18:52:00.511  4668  4668 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 18:52:00.512  4668  4668 D BtGatt.GattService: Received stop request...Stopping profile...
,11-23 18:52:00.512  4668  4668 D BtGatt.GattService: stop()
11-23 18:52:00.512  4668  4668 D BtGatt.AdvertiseManager: advertise clients cleared
11-23 18:52:00.515  4668  4668 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:00.515  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:00.515  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:00.515  4668  4668 V BluetoothAdapterState: isBleTurningOff()=true
11-23 18:52:00.515  4668  4738 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-23 18:52:00.515  4668  4738 D BluetoothAdapterProperties: Setting state to 10
11-23 18:52:00.515  4668  4738 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 18:52:00.516  4668  4738 I BluetoothAdapterState: Entering OffState
,11-23 18:52:00.517   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 18:52:00.527  4668  4668 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 18:52:00.527  4668  4668 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 18:52:00.527  4668  4668 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 18:52:00.529  4668  4739 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 18:52:00.533  4668  4668 I art     : System.exit called, status: 0
,11-23 18:52:00.533  4668  4668 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 18:52:00.566   929  3434 I ActivityManager: Process com.android.bluetooth (pid 4668) has died
,11-23 18:52:00.631   929   946 D Tethering: InitialState.processMessage what=4
11-23 18:52:00.634   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 18:52:00.871   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 18:52:05.139   929   940 D WifiService: setWifiEnabled: true pid=5602, uid=10077
11-23 18:52:05.139   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 18:52:05.150   508   922 D SoftapController: Softap fwReload - Ok
,11-23 18:52:05.157   508   922 D CommandListener: Setting iface cfg
,11-23 18:52:05.157   508   922 D CommandListener: Trying to bring down wlan0
,11-23 18:52:05.161   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-23 18:52:05.168   929  2989 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 18:52:05.760   929  2989 D wifi    : set interface wlan0 flags (UP)
,11-23 18:52:05.764   929  2989 I WifiHAL : Initializing wifi
,11-23 18:52:05.765   929  2989 I WifiHAL : Creating socket
,11-23 18:52:05.769   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 18:52:05.774   929  2989 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-23 18:52:05.775   929  2989 D wifi    : Did set static halHandle = 0x7f74a5e680
11-23 18:52:05.775   929  2989 D wifi    : halHandle = 0x7f74a5e680, mVM = 0x7f9104d140, mCls = 0x1019ce
11-23 18:52:05.775   929  2989 D wifi    : array field set
11-23 18:52:05.775   929  2989 I WifiNative-HAL: interface[0] = wlan0
11-23 18:52:05.777   929  5728 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547417876096
11-23 18:52:05.778   929  5728 D wifi    : waitForHalEvents called, vm = 0x7f9104d140, obj = 0x1019ce, env = 0x7f75420e40
,11-23 18:52:05.860  5729  5729 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 18:52:05.872   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:05.879   929  2989 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 18:52:05.887  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 18:52:05.932  5729  5729 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 18:52:05.958  5729  5729 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 18:52:05.958  5729  5729 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 18:52:05.974   929  2989 D WifiConfigStore: Loading config and enabling all networks 
,11-23 18:52:05.978  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 18:52:05.979  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 18:52:05.979  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:52:05.979  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:52:05.979  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 18:52:05.979  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 18:52:05.979  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 18:52:05.979  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 18:52:05.979  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 18:52:05.979  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 18:52:05.979  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:05.979  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 18:52:05.995   929  2989 D WifiConfigStore: loaded 0 passpoint configs
,11-23 18:52:05.997   929  2989 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-23 18:52:05.997   929  2989 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-23 18:52:05.997   929  2989 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-23 18:52:05.998   929  2989 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-23 18:52:05.998   929  2989 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-23 18:52:05.999   929  2989 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 18:52:05.999   929  2989 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-23 18:52:05.999   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-23 18:52:05.999   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-23 18:52:05.999   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 18:52:05.999   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 18:52:05.999   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 18:52:06.001   929  2989 D WifiNative-HAL: Setting external_sim to 1
,11-23 18:52:06.002   929  2989 D wifi    : setting dfs flag to true, 0x7f775fe540
,11-23 18:52:06.002  4478  4478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 18:52:06.002   929  2989 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 18:52:06.003   929  2989 D wifi    : setting scan oui 0x7f775fe540
11-23 18:52:06.003   929  2989 D WifiHAL : Sending mac address OUI
,11-23 18:52:06.006   929  2989 E native  : do suspend false
,11-23 18:52:06.012   929  2989 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 18:52:06.012   929   929 D RttService: SCAN_AVAILABLE : 3
11-23 18:52:06.012   929  3098 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 18:52:06.013   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-23 18:52:06.014   508   922 D CommandListener: Setting iface cfg
,11-23 18:52:06.018   929  2988 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-23 18:52:06.019   929  2988 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 18:52:06.030   929  2988 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 18:52:06.035   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128661 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-23 18:52:06.035   929  2988 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 18:52:06.873   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:07.874   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:08.875   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:09.048  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 18:52:09.052  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 18:52:09.141   929  2989 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-23 18:52:09.142   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 18:52:09.143   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 18:52:09.154   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 18:52:09.188   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 18:52:09.195  5729  5729 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 18:52:09.876   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:09.958  5729  5729 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 18:52:10.149   929  3173 D WifiService: setWifiEnabled: false pid=5602, uid=10077
11-23 18:52:10.149   929  3173 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 18:52:10.156   929   929 D RttService: SCAN_AVAILABLE : 1
,11-23 18:52:10.157   929  3098 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 18:52:10.172   929  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 18:52:10.173   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-23 18:52:10.183   929  2989 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 18:52:10.184  5729  5729 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-23 18:52:10.194  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 18:52:10.194  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 18:52:10.194  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:52:10.194  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:52:10.194  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 18:52:10.194  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 18:52:10.194  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 18:52:10.194  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 18:52:10.194  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 18:52:10.194  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 18:52:10.194  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:10.194  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 18:52:10.199  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 18:52:10.206  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 18:52:10.208  5729  5729 I wpa_supplicant: wlan0: WPA: 4-Way Handshake failed - pre-shared key may be incorrect
11-23 18:52:10.209  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="NG700" auth_failures=1 duration=10 reason=WRONG_KEY
,11-23 18:52:10.210   929  2989 E WifiStateMachine: Error! unhandled message{ when=0 what=147469 obj=id=0 ssid="NG700" auth_failures=1 duration=10 reason=WRONG_KEY target=com.android.internal.util.StateMachine$SmHandler }
,11-23 18:52:10.230  5729  5729 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 18:52:10.248  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 18:52:10.352   929  2989 D wifi    : In wifi stop Hal
,11-23 18:52:10.352   929  2989 D wifi    : halHandle = 0x7f74a5e680, mVM = 0x7f9104d140, mCls = 0x1019ce
,11-23 18:52:10.352   929  5728 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 18:52:10.352   929  5728 D WifiHAL : Got a signal to exit!!!
,11-23 18:52:10.353   929  5728 I WifiHAL : Exit wifi_event_loop
11-23 18:52:10.354   929  2989 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 18:52:10.354   929  2989 E WifiHAL : Event processing terminated
11-23 18:52:10.354  3956  4235 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 18:52:10.355   929  2989 D wifi    : In wifi cleaned up handler
11-23 18:52:10.356   929  2989 I WifiHAL : Internal cleanup completed
11-23 18:52:10.357  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:52:10.362  4478  4478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 18:52:10.394   929  5728 D wifi    : set interface wlan0 flags (DOWN)
,11-23 18:52:10.394   929  2989 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 18:52:10.601   929   946 D Tethering: InitialState.processMessage what=4
,11-23 18:52:10.606   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 18:52:10.877   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 18:52:15.190   929   946 I ActivityManager: Start proc 5735:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 18:52:15.281  5735  5735 D AdapterServiceConfig: Adding HeadsetService
11-23 18:52:15.281  5735  5735 D AdapterServiceConfig: Adding A2dpService
11-23 18:52:15.282  5735  5735 D AdapterServiceConfig: Adding HidService
11-23 18:52:15.282  5735  5735 D AdapterServiceConfig: Adding HealthService
11-23 18:52:15.282  5735  5735 D AdapterServiceConfig: Adding PanService
11-23 18:52:15.282  5735  5735 D AdapterServiceConfig: Adding GattService
,11-23 18:52:15.282  5735  5735 D AdapterServiceConfig: Adding BluetoothMapService
11-23 18:52:15.283  5735  5735 D AdapterServiceConfig: Adding SapService
,11-23 18:52:15.292   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bdc92a4:true
,11-23 18:52:15.293  5735  5735 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 18:52:15.295  5735  5735 I bt_bluedroid: init
,11-23 18:52:15.295  5735  5747 I BluetoothAdapterState: Entering OffState
,11-23 18:52:15.297  5735  5748 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 18:52:15.298  5735  5748 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 18:52:15.298  5735  5748 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 18:52:15.298  5735  5748 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 18:52:15.298  5735  5735 I bt_bluedroid: get_profile_interface socket
,11-23 18:52:15.300  5735  5751 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 18:52:15.301  5735  5735 I bt_bluedroid: get_profile_interface sdp
11-23 18:52:15.302  5735  5751 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 18:52:15.305  5735  5746 I bt_bluedroid: config_hci_snoop_log
,11-23 18:52:15.306   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 18:52:15.310  5735  5747 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 18:52:15.310  5735  5747 D BluetoothAdapterProperties: Setting state to 14
,11-23 18:52:15.310  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 18:52:15.311  5735  5747 D BluetoothBondStateMachine: make
,11-23 18:52:15.313  5735  5752 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 18:52:15.315  5735  5747 I BluetoothAdapterState: Entering PendingCommandState
,11-23 18:52:15.316  5735  5735 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 18:52:15.319  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
,11-23 18:52:15.319  5735  5735 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 18:52:15.320  5735  5735 D BtGatt.GattService: Received start request. Starting profile...
11-23 18:52:15.320  5735  5735 D BtGatt.GattService: start()
,11-23 18:52:15.320  5735  5735 I bt_bluedroid: get_profile_interface gatt
,11-23 18:52:15.321  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:52:15.321  5735  5735 D BtGatt.AdvertiseManager: advertise manager created
,11-23 18:52:15.326  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:15.326  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:15.326  5735  5735 V BluetoothAdapterState: isBleTurningOn()=true
11-23 18:52:15.326  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:15.326  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 18:52:15.328  5735  5747 I bt_bluedroid: bt_bluedroid
,11-23 18:52:15.328  5735  5748 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-23 18:52:15.328  5735  5748 I bt_hci  : start_up
,11-23 18:52:15.333  5735  5748 I bt_vendor: alloc value 0xf3ca5871
,11-23 18:52:15.333  5735  5748 I bt_vendor: init
11-23 18:52:15.333  5735  5748 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 18:52:15.333  5735  5748 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 18:52:15.445  5735  5748 D bt_hci  : start_up starting async portion
11-23 18:52:15.445  5735  5755 I bt_hci  : event_finish_startup
11-23 18:52:15.445  5735  5755 I bt_hci_h4: hal_open
11-23 18:52:15.445  5735  5755 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 18:52:15.448  5735  5755 I bt_userial_vendor: device fd = 54 open
,11-23 18:52:15.444  5756  5756 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 18:52:15.461  5735  5755 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 18:52:15.464  5735  5755 D bt_hwcfg: Chipset BCM4358A3
11-23 18:52:15.464  5735  5755 D bt_hwcfg: Target name = [BCM4358A3]
,11-23 18:52:15.464  5735  5755 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 18:52:15.866  5735  5755 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-23 18:52:15.867  5735  5755 D bt_hwcfg: Settlement delay -- 100 ms
,11-23 18:52:15.867  5735  5755 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 18:52:16.002  5735  5755 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 18:52:16.003  5735  5755 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-23 18:52:16.004  5735  5755 I bt_hwcfg: vendor lib fwcfg completed
11-23 18:52:16.005  5735  5755 I bt_vendor: firmware callback
11-23 18:52:16.005  5735  5755 I bt_hci  : firmware_config_callback
,11-23 18:52:16.014  5735  5758 I bt_btu  : btu_task pending for preload complete event
,11-23 18:52:16.014  5735  5758 I bt_btu_task: Bluetooth chip preload is complete
11-23 18:52:16.014  5735  5758 I bt_btu  : btu_task received preload complete event
,11-23 18:52:16.022  5735  5758 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 18:52:16.022  5735  5758 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 18:52:16.022  5735  5758 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 18:52:16.022  5735  5758 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 18:52:16.022  5735  5758 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 18:52:16.023  5735  5758 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 18:52:16.023  5735  5758 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 18:52:16.023  5735  5758 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 18:52:16.023  5735  5758 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 18:52:16.023  5735  5758 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 18:52:16.023  5735  5758 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 18:52:16.024  5735  5758 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 18:52:16.024  5735  5758 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 18:52:16.024  5735  5758 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 18:52:16.024  5735  5758 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 18:52:16.108  5735  5758 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c23549
11-23 18:52:16.109  5735  5758 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c23549 
,11-23 18:52:16.130  5735  5751 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 18:52:16.131  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 18:52:16.132  5735  5751 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 18:52:16.135  5735  5751 D BluetoothAdapterProperties: Name is: Nexus 6P
11-23 18:52:16.137  5735  5751 D BluetoothAdapterProperties: Scan Mode:20
11-23 18:52:16.137  5735  5751 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 18:52:16.138  5735  5751 D bt_hci  : do_postload posting postload work item
,11-23 18:52:16.138  5735  5755 I bt_hci  : event_postload
11-23 18:52:16.138  5735  5755 I bt_vendor: sco_config_cb
11-23 18:52:16.138  5735  5755 I bt_hci  : sco_config_callback postload finished.
11-23 18:52:16.140  5735  5751 D bt_bte_conf: Device ID record 1 : primary
11-23 18:52:16.140  5735  5751 D bt_bte_conf:   vendorId            = 000f
11-23 18:52:16.141  5735  5751 D bt_bte_conf:   vendorIdSource      = 0001
11-23 18:52:16.141  5735  5751 D bt_bte_conf:   product             = 1200
11-23 18:52:16.141  5735  5751 D bt_bte_conf:   version             = 1436
11-23 18:52:16.141  5735  5751 D bt_bte_conf:   clientExecutableURL = 
11-23 18:52:16.141  5735  5751 D bt_bte_conf:   serviceDescription  = 
11-23 18:52:16.141  5735  5751 D bt_bte_conf:   documentationURL    = 
,11-23 18:52:16.141  5735  5751 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 18:52:16.141  5735  5748 D bt_stack_manager: event_start_up_stack finished
11-23 18:52:16.142  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:52:16.143  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 18:52:16.143  5735  5747 D BluetoothAdapterProperties: Setting state to 15
11-23 18:52:16.143  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-23 18:52:16.146  5735  5755 I bt_vendor: low_power_mode_cb
,11-23 18:52:16.146  5735  5747 I BluetoothAdapterState: Entering BleOnState
,11-23 18:52:16.150  5735  5747 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-23 18:52:16.151  5735  5747 D BluetoothAdapterProperties: Setting state to 11
11-23 18:52:16.151  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 18:52:16.156  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:52:16.157  5735  5735 D HeadsetService: Received start request. Starting profile...
,11-23 18:52:16.159  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:52:16.159  5735  5735 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 18:52:16.160  5735  5735 D HeadsetStateMachine: make
,11-23 18:52:16.170  5735  5735 D HeadsetStateMachine: max_hf_connections = 1
,11-23 18:52:16.170  5735  5747 I BluetoothAdapterState: Entering PendingCommandState
11-23 18:52:16.170  5735  5735 I bt_bluedroid: get_profile_interface handsfree
11-23 18:52:16.171  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 18:52:16.171  5735  5751 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 18:52:16.174  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
,11-23 18:52:16.175  5735  5735 D A2dpService: Received start request. Starting profile...
11-23 18:52:16.175  5735  5735 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 18:52:16.175  5735  5735 I bt_bluedroid: get_profile_interface avrcp
,11-23 18:52:16.180  5735  5735 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 18:52:16.180  5735  5735 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 18:52:16.180  5735  5735 D A2dpStateMachine: make
11-23 18:52:16.181  5735  5735 I bt_bluedroid: get_profile_interface a2dp
11-23 18:52:16.183  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-23 18:52:16.183  5735  5765 D A2dpStateMachine: Enter Disconnected: -2
11-23 18:52:16.183  5735  5735 I BluetoothHidServiceJni: classInitNative: succeeds
11-23 18:52:16.184  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
,11-23 18:52:16.185  5735  5735 D HidService: Received start request. Starting profile...
11-23 18:52:16.185  5735  5735 I bt_bluedroid: get_profile_interface hidhost
11-23 18:52:16.186  5735  5735 D HidService: setHidService(): set to: null
11-23 18:52:16.186  5735  5751 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c0456d
11-23 18:52:16.186  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-23 18:52:16.186  5660  5660 D BluetoothInputDevice: Proxy object connected
11-23 18:52:16.187  5660  5660 D HidProfile: Bluetooth service connected
11-23 18:52:16.188  5735  5735 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 18:52:16.188  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:52:16.189  5735  5735 D HealthService: Received start request. Starting profile...
11-23 18:52:16.189  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 18:52:16.190  5735  5735 I bt_bluedroid: get_profile_interface health
,11-23 18:52:16.192  5735  5735 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 18:52:16.192  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
,11-23 18:52:16.194  5660  5660 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 18:52:16.194  5660  5660 D PanProfile: Bluetooth service connected
,11-23 18:52:16.195  5735  5735 D PanService: Received start request. Starting profile...
11-23 18:52:16.195  5735  5735 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 18:52:16.195  5735  5735 I bt_bluedroid: get_profile_interface pan
11-23 18:52:16.195  5735  5751 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 18:52:16.197  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
,11-23 18:52:16.198  5660  5660 D BluetoothMap: Proxy object connected
,11-23 18:52:16.198  5735  5735 D BluetoothMapService: Received start request. Starting profile...
11-23 18:52:16.198  5735  5735 D BluetoothMapService: start()
11-23 18:52:16.199  5660  5660 D MapProfile: Bluetooth service connected
11-23 18:52:16.199  5660  5660 D BluetoothMap: getConnectedDevices()
11-23 18:52:16.199  5660  5660 D BluetoothMap: Bluetooth is Not enabled
,11-23 18:52:16.201  5735  5735 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 18:52:16.202  5735  5735 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 18:52:16.202  5735  5735 D BluetoothMapAppObserver: createReceiver()
11-23 18:52:16.203  5735  5735 D BluetoothMapAppObserver: initObservers()
11-23 18:52:16.203  5735  5735 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 18:52:16.209  5735  5735 V SapService: SapBinder()
,11-23 18:52:16.209  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:52:16.209  5735  5735 D SapService: Received start request. Starting profile...
11-23 18:52:16.209  5735  5735 V SapService: start()
,11-23 18:52:16.210  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:16.211  5735  5763 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isTurningOff()=false
,11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isTurningOn()=true
,11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:16.211  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:16.212  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:16.212  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:16.212  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:16.212  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:16.212  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:16.212  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:16.212  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:16.212  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:16.213  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:16.213  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:16.213  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:16.213  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 18:52:16.213  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 18:52:16.213  5735  5747 D BluetoothAdapterProperties: ScanMode =  20
11-23 18:52:16.213  5735  5747 D BluetoothAdapterProperties: State =  11
11-23 18:52:16.215  5735  5751 D BluetoothAdapterProperties: Scan Mode:21
11-23 18:52:16.215  5735  5751 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 18:52:16.215  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-23 18:52:16.215  5735  5747 D BluetoothAdapterProperties: Setting state to 12
,11-23 18:52:16.215  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 18:52:16.216  3146  3157 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 18:52:16.217  5735  5747 I BluetoothAdapterState: Entering OnState
11-23 18:52:16.218  3146  3146 D BluetoothInputDevice: Proxy object connected
11-23 18:52:16.219  3146  3997 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 18:52:16.219  3146  3146 D HidProfile: Bluetooth service connected
11-23 18:52:16.219  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 18:52:16.219  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:52:16.219  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:52:16.219  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 18:52:16.219  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 18:52:16.219  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 18:52:16.219  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 18:52:16.219  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 18:52:16.219  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 18:52:16.220  5660  5677 D BluetoothMap: onBluetoothStateChange: up=true
11-23 18:52:16.221  3803  4011 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 18:52:16.221  3146  3146 D BluetoothA2dp: Proxy object connected
11-23 18:52:16.222  5660  5679 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-23 18:52:16.222   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 18:52:16.222   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 18:52:16.222  3146  3159 D BluetoothMap: onBluetoothStateChange: up=true
11-23 18:52:16.222  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 18:52:16.223  3146  3146 D BluetoothMap: Proxy object connected
11-23 18:52:16.224  3146  3157 D BluetoothPan: onBluetoothStateChange on: true
11-23 18:52:16.224  3146  3146 D MapProfile: Bluetooth service connected
11-23 18:52:16.224  3146  3146 D BluetoothMap: getConnectedDevices()
11-23 18:52:16.225  3146  3997 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 18:52:16.225  3146  3146 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 18:52:16.225  3146  3146 D PanProfile: Bluetooth service connected
11-23 18:52:16.225   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 18:52:16.226   929   929 D BluetoothA2dp: Proxy object connected
11-23 18:52:16.226  5660  5677 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 18:52:16.227  3146  3159 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 18:52:16.227  5735  5735 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 18:52:16.228  5735  5735 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-23 18:52:16.229   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 18:52:16.229  5660  5679 D BluetoothPan: onBluetoothStateChange on: true
,11-23 18:52:16.229  5735  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 18:52:16.230   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 18:52:16.231  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 18:52:16.232  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:52:16.233  5735  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 18:52:16.233  5660  5660 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-23 18:52:16.234  5735  5735 D ObexServerSockets: Succeed to create listening sockets 
11-23 18:52:16.234  5735  5735 D ObexServerSockets0: startAccept()
11-23 18:52:16.234  5735  5735 D ObexServerSockets0: prepareForNewConnect()
11-23 18:52:16.236  5660  5660 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-23 18:52:16.238  5735  5735 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 18:52:16.239  5735  5735 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 18:52:16.239  5735  5773 D ObexServerSockets0: Accepting socket connection...
11-23 18:52:16.239  5735  5774 D ObexServerSockets0: Accepting socket connection...
11-23 18:52:16.239  5735  5735 D BluetoothMapService: onReceive
11-23 18:52:16.239  5735  5735 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 18:52:16.240  5735  5735 D BluetoothMapService: STATE_ON
11-23 18:52:16.241  5735  5775 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 18:52:16.243  5735  5775 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 18:52:16.243  5735  5775 D BluetoothSdpJni: SDP Create record success - handle: 1
11-23 18:52:16.243  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 18:52:16.245  5660  5660 D BluetoothA2dp: Proxy object connected
,11-23 18:52:16.249  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 18:52:16.249  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,11-23 18:52:16.256  5660  5660 D BluetoothPbap: Proxy object connected
,11-23 18:52:16.256  5660  5660 D PbapServerProfile: Bluetooth service connected
11-23 18:52:16.256  3146  3146 D BluetoothPbap: Proxy object connected
11-23 18:52:16.256  3146  3146 D PbapServerProfile: Bluetooth service connected
,11-23 18:52:16.262  5735  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 18:52:16.272  5735  5735 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 18:52:16.272  5735  5735 D ObexServerSockets0: prepareForNewConnect()
,11-23 18:52:16.276  5735  5783 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 18:52:16.277  5735  5783 I BtOppRfcommListener: Accept thread started.
,11-23 18:52:16.323  3803  4012 D BluetoothHeadset: Proxy object connected
11-23 18:52:16.323   929   929 D BluetoothHeadset: Proxy object connected
,11-23 18:52:16.323  3146  3997 D BluetoothHeadset: Proxy object connected
,11-23 18:52:16.323  3146  3146 D HeadsetProfile: Bluetooth service connected
11-23 18:52:16.324   929   929 D BluetoothHeadset: Proxy object connected
,11-23 18:52:16.324   929   929 D BluetoothHeadset: Proxy object connected
11-23 18:52:16.325  3146  3159 D BluetoothHeadset: Proxy object connected
,11-23 18:52:16.326  3146  3146 D HeadsetProfile: Bluetooth service connected
,11-23 18:52:16.329   929   946 D BluetoothHeadset: Proxy object connected
,11-23 18:52:16.338  5660  5679 D BluetoothHeadset: Proxy object connected
11-23 18:52:16.339  5660  5660 D HeadsetProfile: Bluetooth service connected
,11-23 18:52:17.423  3685  3874 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-23 18:52:17.424  3685  3874 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-23 18:52:17.453  3602  3602 I ConfigService: onCreate
,11-23 18:52:20.166  5735  5747 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 18:52:20.166  5735  5747 D BluetoothAdapterProperties: Setting state to 13
,11-23 18:52:20.166  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 18:52:20.168  5735  5747 D BluetoothAdapterProperties: onBluetoothDisable()
,11-23 18:52:20.170  5735  5747 I BluetoothAdapterState: Entering PendingCommandState
,11-23 18:52:20.176  5735  5735 D BluetoothMapService: onReceive
11-23 18:52:20.176  5735  5735 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 18:52:20.177  5735  5735 D BluetoothMapService: STATE_TURNING_OFF
11-23 18:52:20.178  5735  5735 D BluetoothMapService: MAP Service closeService in
,11-23 18:52:20.178  5735  5735 D BluetoothMapMasInstance0: MAP Service shutdown
,11-23 18:52:20.179  5735  5735 D ObexServerSockets0: shutdown(block = true)
,11-23 18:52:20.179  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:20.179  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 18:52:20.179  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:52:20.179  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:52:20.179  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 18:52:20.179  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 18:52:20.179  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 18:52:20.179  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 18:52:20.179  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 18:52:20.179  5602  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 18:52:20.181  5735  5735 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 18:52:20.181  5735  5773 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-23 18:52:20.181  5735  5751 D BluetoothAdapterProperties: Scan Mode:20
11-23 18:52:20.181  5735  5735 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 18:52:20.181  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 18:52:20.181  5735  5774 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 18:52:20.182  5735  5760 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 18:52:20.183  5602  5602 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 18:52:20.183  5602  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 18:52:20.184  5735  5735 I BtOppRfcommListener: stopping Accept Thread
11-23 18:52:20.185  5735  5783 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 18:52:20.185  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 18:52:20.186  5735  5783 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 18:52:20.187  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 18:52:20.192  5735  5735 D HeadsetService: Received stop request...Stopping profile...
11-23 18:52:20.197  3803  4152 D BluetoothHeadset: Proxy object disconnected
11-23 18:52:20.198   929   929 D BluetoothHeadset: Proxy object disconnected
,11-23 18:52:20.199  5660  5677 D BluetoothHeadset: Proxy object disconnected
11-23 18:52:20.201  3146  3157 D BluetoothHeadset: Proxy object disconnected
11-23 18:52:20.201   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 18:52:20.201   929   929 D BluetoothHeadset: Proxy object disconnected
,11-23 18:52:20.202  5660  5660 D DockEventReceiver: finishStartingService: stopping service
11-23 18:52:20.204  5735  5735 D A2dpService: Received stop request...Stopping profile...
11-23 18:52:20.204  5735  5765 D A2dpStateMachine: Exit Disconnected: -1
11-23 18:52:20.205  5660  5660 D HeadsetProfile: Bluetooth service disconnected
11-23 18:52:20.206   929   929 D BluetoothA2dp: Proxy object disconnected
11-23 18:52:20.207  5660  5660 D BluetoothA2dp: Proxy object disconnected
,11-23 18:52:20.209  5735  5735 D HidService: Received stop request...Stopping profile...
11-23 18:52:20.209  5735  5735 D HidService: Stopping Bluetooth HidService
11-23 18:52:20.211  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 18:52:20.211  5660  5660 D BluetoothInputDevice: Proxy object disconnected
11-23 18:52:20.211  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:20.212  5660  5660 D HidProfile: Bluetooth service disconnected
11-23 18:52:20.212  5735  5735 V BluetoothAdapterState: isTurningOn()=false
,11-23 18:52:20.212  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:20.212  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:20.212  5735  5735 D HealthService: Received stop request...Stopping profile...
,11-23 18:52:20.215  3146  3146 D HeadsetProfile: Bluetooth service disconnected
11-23 18:52:20.215  3146  3146 D BluetoothA2dp: Proxy object disconnected
11-23 18:52:20.215  3146  3146 D BluetoothInputDevice: Proxy object disconnected
11-23 18:52:20.215  3146  3146 D HidProfile: Bluetooth service disconnected
,11-23 18:52:20.215  5735  5735 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 18:52:20.215  5735  5735 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-23 18:52:20.215  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-23 18:52:20.216  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 18:52:20.216  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 18:52:20.216  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 18:52:20.216  5735  5735 D PanService: Received stop request...Stopping profile...
11-23 18:52:20.216  5735  5751 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 18:52:20.217  5660  5660 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-23 18:52:20.217  5660  5660 D PanProfile: Bluetooth service disconnected
11-23 18:52:20.217  3146  3146 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 18:52:20.217  3146  3146 D PanProfile: Bluetooth service disconnected
,11-23 18:52:20.218  5735  5735 D BluetoothMapService: Received stop request...Stopping profile...
,11-23 18:52:20.218  5735  5735 D BluetoothMapService: stop()
11-23 18:52:20.219  5735  5735 D BluetoothMapAppObserver: deinitObservers()
11-23 18:52:20.219  5735  5735 D BluetoothMapAppObserver: removeReceiver()
11-23 18:52:20.221  5660  5660 D BluetoothMap: Proxy object disconnected
,11-23 18:52:20.221  3146  3146 D BluetoothMap: Proxy object disconnected
11-23 18:52:20.221  5660  5660 D MapProfile: Bluetooth service disconnected
11-23 18:52:20.221  3146  3146 D MapProfile: Bluetooth service disconnected
11-23 18:52:20.223  5735  5735 D SapService: Received stop request...Stopping profile...
11-23 18:52:20.223  5735  5735 V SapService: stop()
,11-23 18:52:20.226  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:20.226  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:20.226  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:20.226  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:20.227  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 18:52:20.228  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 18:52:20.228  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 18:52:20.228  5735  5758 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 18:52:20.228  5735  5758 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 18:52:20.228  5735  5758 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-23 18:52:20.228  5735  5758 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 18:52:20.230  5660  5660 D BluetoothPbap: Proxy object disconnected
,11-23 18:52:20.230  5660  5660 D PbapServerProfile: Bluetooth service disconnected
,11-23 18:52:20.230  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:20.230  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:20.230  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:20.230  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:20.230  5735  5735 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 18:52:20.230  3146  3146 D BluetoothPbap: Proxy object disconnected
11-23 18:52:20.230  5735  5735 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 18:52:20.230  3146  3146 D PbapServerProfile: Bluetooth service disconnected
,11-23 18:52:20.231  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 18:52:20.231  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:20.231  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:20.231  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 18:52:20.231  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:20.231  5735  5735 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 18:52:20.231  5735  5751 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 18:52:20.232  5735  5735 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 18:52:20.232  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:20.232  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:20.232  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:20.232  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 18:52:20.232  5735  5735 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 18:52:20.233  5735  5735 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 18:52:20.233  5735  5735 D BluetoothMapService: MAP Service closeService in
11-23 18:52:20.234  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:20.234  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:20.234  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:20.234  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:20.234  5735  5735 D BluetoothMapService: cleanup()
11-23 18:52:20.234  5735  5735 D BluetoothMapService: MAP Service closeService in
11-23 18:52:20.234  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-23 18:52:20.235  5735  5735 V BluetoothAdapterState: isTurningOn()=false
,11-23 18:52:20.235  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:20.235  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:20.236  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 18:52:20.236  5735  5747 D BluetoothAdapterProperties: Setting state to 15
11-23 18:52:20.236  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 18:52:20.237  5735  5747 I BluetoothAdapterState: Entering BleOnState
11-23 18:52:20.239  3146  3157 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 18:52:20.241  3146  3997 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 18:52:20.242  5660  5788 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 18:52:20.242  5660  5679 D BluetoothMap: onBluetoothStateChange: up=false
11-23 18:52:20.243  3803  3824 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 18:52:20.243  5660  5677 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 18:52:20.244   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 18:52:20.245  5660  5788 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 18:52:20.245   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 18:52:20.245  3146  3159 D BluetoothMap: onBluetoothStateChange: up=false
11-23 18:52:20.246  3146  3157 D BluetoothPan: onBluetoothStateChange on: false
11-23 18:52:20.246  3146  3997 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 18:52:20.247   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 18:52:20.247  5660  5679 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 18:52:20.247  3146  3159 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 18:52:20.248   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 18:52:20.248  5660  5677 D BluetoothPan: onBluetoothStateChange on: false
11-23 18:52:20.249  5735  5747 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 18:52:20.249  5735  5747 D BluetoothAdapterProperties: Setting state to 16
11-23 18:52:20.249  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 18:52:20.249  5735  5747 D BluetoothAdapterProperties: onBleDisable
11-23 18:52:20.250  5735  5747 I BluetoothAdapterState: Entering PendingCommandState
,11-23 18:52:20.251  5735  5748 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-23 18:52:20.252  5735  5758 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 18:52:20.253  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 18:52:20.253  5735  5751 D BluetoothAdapterProperties: Scan Mode:20
11-23 18:52:20.254  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 18:52:20.255  5602  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 18:52:20.258  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 18:52:20.264  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 18:52:20.268  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,11-23 18:52:20.460  5735  5751 I bt_hci  : shut_down
,11-23 18:52:20.466  5735  5755 D bt_hwcfg: hw_epilog_process
11-23 18:52:20.466  5735  5755 I bt_vendor: low_power_mode_cb
,11-23 18:52:20.468  5735  5755 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 18:52:20.468  5735  5755 I bt_vendor: epilog_cb
11-23 18:52:20.468  5735  5755 I bt_hci  : epilog_finished_callback
,11-23 18:52:20.472  5735  5751 I bt_hci_h4: hal_close
,11-23 18:52:20.472  5735  5751 I bt_userial_vendor: device fd = 54 close
,11-23 18:52:20.582  5735  5748 D bt_stack_manager: event_shut_down_stack finished.
,11-23 18:52:20.582  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 18:52:20.585  5735  5747 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 18:52:20.586  5735  5735 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 18:52:20.587  5735  5735 D BtGatt.GattService: Received stop request...Stopping profile...
,11-23 18:52:20.587  5735  5735 D BtGatt.GattService: stop()
11-23 18:52:20.587  5735  5735 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 18:52:20.590  5735  5735 V BluetoothAdapterState: isTurningOff()=false
,11-23 18:52:20.590  5735  5735 V BluetoothAdapterState: isTurningOn()=false
,11-23 18:52:20.590  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:20.590  5735  5735 V BluetoothAdapterState: isBleTurningOff()=true
11-23 18:52:20.591  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-23 18:52:20.591  5735  5747 D BluetoothAdapterProperties: Setting state to 10
11-23 18:52:20.591  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 18:52:20.592  5735  5747 I BluetoothAdapterState: Entering OffState
,11-23 18:52:20.593   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 18:52:20.603  5735  5735 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-23 18:52:20.603  5735  5735 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-23 18:52:20.603  5735  5735 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 18:52:20.604  5735  5748 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 18:52:20.609  5735  5735 I art     : System.exit called, status: 0
,11-23 18:52:20.610  5735  5735 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 18:52:20.635   929  3836 I ActivityManager: Process com.android.bluetooth (pid 5735) has died
,11-23 18:52:20.878   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:21.879   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:22.485  3602  3602 I ConfigService: onDestroy
,11-23 18:52:22.880   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:23.881   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:24.882   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:25.164  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 18:52:25.164  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 18:52:25.169  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:52:25.170  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5604e7 removed from the list
11-23 18:52:25.170  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 18:52:25.174  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 18:52:25.175  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43a4332 added. We now have 4 listener(s)
11-23 18:52:25.175  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 18:52:25.176  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 18:52:25.177  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43a4332 removed from the list
,11-23 18:52:25.177  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:52:25.179  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:25.179  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f40883 added. We now have 4 listener(s)
11-23 18:52:25.179  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 18:52:25.882   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 18:52:30.190  5602  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 18:52:30.228   929   946 I ActivityManager: Start proc 5793:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 18:52:30.322  5793  5793 D AdapterServiceConfig: Adding HeadsetService
,11-23 18:52:30.322  5793  5793 D AdapterServiceConfig: Adding A2dpService
11-23 18:52:30.322  5793  5793 D AdapterServiceConfig: Adding HidService
11-23 18:52:30.322  5793  5793 D AdapterServiceConfig: Adding HealthService
11-23 18:52:30.322  5793  5793 D AdapterServiceConfig: Adding PanService
11-23 18:52:30.323  5793  5793 D AdapterServiceConfig: Adding GattService
11-23 18:52:30.323  5793  5793 D AdapterServiceConfig: Adding BluetoothMapService
,11-23 18:52:30.323  5793  5793 D AdapterServiceConfig: Adding SapService
,11-23 18:52:30.334   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@59b71d0:true
,11-23 18:52:30.334  5793  5793 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 18:52:30.337  5793  5793 I bt_bluedroid: init
11-23 18:52:30.337  5793  5805 I BluetoothAdapterState: Entering OffState
,11-23 18:52:30.339  5793  5806 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 18:52:30.339  5793  5806 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 18:52:30.339  5793  5806 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 18:52:30.339  5793  5806 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-23 18:52:30.340  5793  5793 I bt_bluedroid: get_profile_interface socket
,11-23 18:52:30.342  5793  5809 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-23 18:52:30.342  5793  5793 I bt_bluedroid: get_profile_interface sdp
,11-23 18:52:30.343  5793  5809 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 18:52:30.346  5793  5804 I bt_bluedroid: config_hci_snoop_log
,11-23 18:52:30.347   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-23 18:52:30.351  5793  5805 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 18:52:30.351  5793  5805 D BluetoothAdapterProperties: Setting state to 14
11-23 18:52:30.351  5793  5805 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 18:52:30.353  5793  5805 D BluetoothBondStateMachine: make
,11-23 18:52:30.355  5793  5810 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 18:52:30.357  5793  5805 I BluetoothAdapterState: Entering PendingCommandState
,11-23 18:52:30.359  5793  5793 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 18:52:30.361  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:52:30.362  5793  5793 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 18:52:30.362  5793  5793 D BtGatt.GattService: Received start request. Starting profile...
,11-23 18:52:30.362  5793  5793 D BtGatt.GattService: start()
11-23 18:52:30.362  5793  5793 I bt_bluedroid: get_profile_interface gatt
11-23 18:52:30.363  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:52:30.363  5793  5793 D BtGatt.AdvertiseManager: advertise manager created
,11-23 18:52:30.368  5793  5793 V BluetoothAdapterState: isTurningOff()=false
,11-23 18:52:30.368  5793  5793 V BluetoothAdapterState: isTurningOn()=false
11-23 18:52:30.368  5793  5793 V BluetoothAdapterState: isBleTurningOn()=true
11-23 18:52:30.368  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 18:52:30.368  5793  5805 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 18:52:30.370  5793  5805 I bt_bluedroid: bt_bluedroid
11-23 18:52:30.370  5793  5806 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 18:52:30.370  5793  5806 I bt_hci  : start_up
,11-23 18:52:30.375  5793  5806 I bt_vendor: alloc value 0xf3ca5871
11-23 18:52:30.375  5793  5806 I bt_vendor: init
11-23 18:52:30.375  5793  5806 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,11-23 18:52:30.375  5793  5806 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 18:52:30.488  5793  5806 D bt_hci  : start_up starting async portion
,11-23 18:52:30.489  5793  5813 I bt_hci  : event_finish_startup
,11-23 18:52:30.489  5793  5813 I bt_hci_h4: hal_open
11-23 18:52:30.489  5793  5813 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-23 18:52:30.487  5814  5814 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-23 18:52:30.491  5793  5813 I bt_userial_vendor: device fd = 54 open
,11-23 18:52:30.506  5793  5813 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 18:52:30.509  5793  5813 D bt_hwcfg: Chipset BCM4358A3
,11-23 18:52:30.509  5793  5813 D bt_hwcfg: Target name = [BCM4358A3]
11-23 18:52:30.509  5793  5813 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 18:52:31.020  5793  5813 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-23 18:52:31.021  5793  5813 D bt_hwcfg: Settlement delay -- 100 ms
,11-23 18:52:31.021  5793  5813 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 18:52:31.154  5793  5813 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 18:52:31.155  5793  5813 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-23 18:52:31.157  5793  5813 I bt_hwcfg: vendor lib fwcfg completed
,11-23 18:52:31.157  5793  5813 I bt_vendor: firmware callback
,11-23 18:52:31.157  5793  5813 I bt_hci  : firmware_config_callback
,11-23 18:52:31.166  5793  5816 I bt_btu  : btu_task pending for preload complete event
,11-23 18:52:31.166  5793  5816 I bt_btu_task: Bluetooth chip preload is complete
11-23 18:52:31.166  5793  5816 I bt_btu  : btu_task received preload complete event
,11-23 18:52:31.172  5793  5816 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 18:52:31.172  5793  5816 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 18:52:31.172  5793  5816 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-23 18:52:31.172  5793  5816 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 18:52:31.173  5793  5816 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 18:52:31.173  5793  5816 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 18:52:31.173  5793  5816 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-23 18:52:31.173  5793  5816 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 18:52:31.173  5793  5816 I         : BTE_InitTraceLevels -- TRC_GAP
,11-23 18:52:31.173  5793  5816 I         : BTE_InitTraceLevels -- TRC_PAN
,11-23 18:52:31.173  5793  5816 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 18:52:31.173  5793  5816 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 18:52:31.174  5793  5816 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 18:52:31.174  5793  5816 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-23 18:52:31.174  5793  5816 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 18:52:31.267  5793  5816 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c23549
,11-23 18:52:31.268  5793  5816 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c23549 
,11-23 18:52:31.304  5793  5809 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 18:52:31.307  5793  5809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 18:52:31.307  5793  5809 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-23 18:52:31.309  5793  5809 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 18:52:31.311  5793  5809 D BluetoothAdapterProperties: Scan Mode:20
11-23 18:52:31.312  5793  5809 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 18:52:31.312  5793  5809 D bt_hci  : do_postload posting postload work item
,11-23 18:52:31.312  5793  5813 I bt_hci  : event_postload
11-23 18:52:31.312  5793  5813 I bt_vendor: sco_config_cb
11-23 18:52:31.312  5793  5813 I bt_hci  : sco_config_callback postload finished.
11-23 18:52:31.314  5793  5809 D bt_bte_conf: Device ID record 1 : primary
,11-23 18:52:31.314  5793  5809 D bt_bte_conf:   vendorId            = 000f
11-23 18:52:31.314  5793  5809 D bt_bte_conf:   vendorIdSource      = 0001
11-23 18:52:31.314  5793  5809 D bt_bte_conf:   product             = 1200
11-23 18:52:31.314  5793  5809 D bt_bte_conf:   version             = 1436
11-23 18:52:31.314  5793  5809 D bt_bte_conf:   clientExecutableURL = 
11-23 18:52:31.314  5793  5809 D bt_bte_conf:   serviceDescription  = 
11-23 18:52:31.315  5793  5809 D bt_bte_conf:   documentationURL    = 
11-23 18:52:31.315  5793  5809 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 18:52:31.315  5793  5806 D bt_stack_manager: event_start_up_stack finished
11-23 18:52:31.316  5793  5805 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 18:52:31.317  5793  5805 D BluetoothAdapterProperties: Setting state to 15
,11-23 18:52:31.317  5793  5805 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 18:52:31.319  5793  5805 I BluetoothAdapterState: Entering BleOnState
11-23 18:52:31.323  5793  5805 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 18:52:31.323  5793  5805 D BluetoothAdapterProperties: Setting state to 11
11-23 18:52:31.323  5793  5813 I bt_vendor: low_power_mode_cb
11-23 18:52:31.323  5793  5805 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 18:52:31.337  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
,11-23 18:52:31.338  5793  5793 D HeadsetService: Received start request. Starting profile...
11-23 18:52:31.341  5793  5793 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 18:52:31.341  5793  5793 D HeadsetStateMachine: make
,11-23 18:52:31.348  5793  5805 I BluetoothAdapterState: Entering PendingCommandState
,11-23 18:52:31.353  5793  5793 D HeadsetStateMachine: max_hf_connections = 1
11-23 18:52:31.353  5793  5793 I bt_bluedroid: get_profile_interface handsfree
,11-23 18:52:31.353  5793  5809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 18:52:31.354  5793  5809 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 18:52:31.357  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:52:31.358  5793  5793 D A2dpService: Received start request. Starting profile...
11-23 18:52:31.359  5793  5793 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 18:52:31.359  5793  5793 I bt_bluedroid: get_profile_interface avrcp
,11-23 18:52:31.367  5793  5793 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 18:52:31.367  5793  5793 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 18:52:31.367  5793  5793 D A2dpStateMachine: make
,11-23 18:52:31.368  5793  5793 I bt_bluedroid: get_profile_interface a2dp
,11-23 18:52:31.369  5793  5809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-23 18:52:31.370  5793  5824 D A2dpStateMachine: Enter Disconnected: -2
11-23 18:52:31.370  5793  5793 I BluetoothHidServiceJni: classInitNative: succeeds
11-23 18:52:31.371  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
,11-23 18:52:31.372  5793  5793 D HidService: Received start request. Starting profile...
11-23 18:52:31.372  5793  5793 I bt_bluedroid: get_profile_interface hidhost
11-23 18:52:31.372  5793  5793 D HidService: setHidService(): set to: null
,11-23 18:52:31.372  5793  5809 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c0456d
11-23 18:52:31.372  5793  5809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 18:52:31.373  5793  5793 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 18:52:31.373  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:52:31.374  5793  5793 D HealthService: Received start request. Starting profile...
,11-23 18:52:31.376  5793  5793 I bt_bluedroid: get_profile_interface health
11-23 18:52:31.377  5793  5793 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 18:52:31.378  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
,11-23 18:52:31.378  5793  5793 D PanService: Received start request. Starting profile...
,11-23 18:52:31.379  5793  5793 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 18:52:31.379  5793  5793 I bt_bluedroid: get_profile_interface pan
,11-23 18:52:31.379  5793  5809 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 18:52:31.381  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:52:31.381  5793  5793 D BluetoothMapService: Received start request. Starting profile...
11-23 18:52:31.381  5793  5793 D BluetoothMapService: start()
11-23 18:52:31.384  5793  5793 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-23 18:52:31.385  5793  5793 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 18:52:31.385  5793  5793 D BluetoothMapAppObserver: createReceiver()
11-23 18:52:31.386  5793  5793 D BluetoothMapAppObserver: initObservers()
11-23 18:52:31.386  5793  5793 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 18:52:31.392  5793  5793 V SapService: SapBinder()
11-23 18:52:31.393  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
,11-23 18:52:31.393  5793  5793 D SapService: Received start request. Starting profile...
,11-23 18:52:31.393  5793  5793 V SapService: start()
11-23 18:52:31.397  5793  5793 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:31.398  5793  5793 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:31.398  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:31.398  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:31.398  5793  5822 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 18:52:31.398  5793  5793 V BluetoothAdapterState: isTurningOff()=false
,11-23 18:52:31.398  5793  5793 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:31.399  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:31.399  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:31.399  5793  5793 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:31.399  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 18:52:31.399  5793  5793 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:31.399  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:31.399  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:31.399  5793  5793 V BluetoothAdapterState: isTurningOff()=false
,11-23 18:52:31.399  5793  5793 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:31.399  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 18:52:31.399  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:31.400  5793  5793 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:31.400  5793  5793 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:31.400  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:31.400  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:31.400  5793  5793 V BluetoothAdapterState: isTurningOff()=false
11-23 18:52:31.400  5793  5793 V BluetoothAdapterState: isTurningOn()=true
11-23 18:52:31.400  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 18:52:31.400  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:31.401  5793  5793 V BluetoothAdapterState: isTurningOff()=false
,11-23 18:52:31.401  5793  5793 V BluetoothAdapterState: isTurningOn()=true
,11-23 18:52:31.401  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
11-23 18:52:31.401  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
11-23 18:52:31.402  5793  5805 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 18:52:31.402  5793  5805 D BluetoothAdapterProperties: ScanMode =  20
11-23 18:52:31.402  5793  5805 D BluetoothAdapterProperties: State =  11
,11-23 18:52:31.402  5793  5805 D BluetoothAdapterProperties: Setting state to 12
11-23 18:52:31.402  5793  5805 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 18:52:31.403  5793  5805 I BluetoothAdapterState: Entering OnState
11-23 18:52:31.403  3146  3997 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-23 18:52:31.405  5793  5809 D BluetoothAdapterProperties: Scan Mode:21
11-23 18:52:31.405  5793  5809 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 18:52:31.406  3146  3159 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 18:52:31.407  3146  3146 D BluetoothInputDevice: Proxy object connected
11-23 18:52:31.407  3146  3146 D HidProfile: Bluetooth service connected
,11-23 18:52:31.408  5660  5677 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-23 18:52:31.410  3146  3146 D BluetoothA2dp: Proxy object connected
11-23 18:52:31.410  5660  5679 D BluetoothMap: onBluetoothStateChange: up=true
11-23 18:52:31.412  3803  4152 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 18:52:31.412  5793  5793 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 18:52:31.413  5660  5788 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 18:52:31.413  5793  5793 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 18:52:31.414  5793  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 18:52:31.414   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 18:52:31.415  5660  5679 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 18:52:31.415   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 18:52:31.415  3146  3157 D BluetoothMap: onBluetoothStateChange: up=true
,11-23 18:52:31.416  5793  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 18:52:31.416  3146  3159 D BluetoothPan: onBluetoothStateChange on: true
11-23 18:52:31.417  5793  5793 D ObexServerSockets: Succeed to create listening sockets 
11-23 18:52:31.417  5793  5793 D ObexServerSockets0: startAccept()
11-23 18:52:31.417  5793  5793 D ObexServerSockets0: prepareForNewConnect()
11-23 18:52:31.418  3146  3997 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 18:52:31.418   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 18:52:31.419   929   929 D BluetoothA2dp: Proxy object connected
11-23 18:52:31.419  5660  5677 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 18:52:31.419  5660  5660 D BluetoothA2dp: Proxy object connected
11-23 18:52:31.420  5793  5793 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-23 18:52:31.420  5793  5793 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 18:52:31.421  3146  3146 D BluetoothMap: Proxy object connected
11-23 18:52:31.421  3146  3146 D MapProfile: Bluetooth service connected
11-23 18:52:31.421  3146  3146 D BluetoothMap: getConnectedDevices()
11-23 18:52:31.422  3146  3157 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 18:52:31.423  5793  5829 D ObexServerSockets0: Accepting socket connection...
11-23 18:52:31.423   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 18:52:31.423  3146  3146 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 18:52:31.423  3146  3146 D PanProfile: Bluetooth service connected
11-23 18:52:31.424  5660  5679 D BluetoothPan: onBluetoothStateChange on: true
11-23 18:52:31.426   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 18:52:31.426  5793  5830 D ObexServerSockets0: Accepting socket connection...
11-23 18:52:31.426  5793  5793 D BluetoothMapService: onReceive
11-23 18:52:31.427  5793  5793 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 18:52:31.427  5793  5793 D BluetoothMapService: STATE_ON
,11-23 18:52:31.429  5660  5660 D BluetoothInputDevice: Proxy object connected
11-23 18:52:31.429  5660  5660 D HidProfile: Bluetooth service connected
11-23 18:52:31.430  5793  5833 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 18:52:31.431  5660  5660 D BluetoothMap: Proxy object connected
11-23 18:52:31.431  5660  5660 D MapProfile: Bluetooth service connected
11-23 18:52:31.431  5660  5660 D BluetoothMap: getConnectedDevices()
11-23 18:52:31.432  5793  5833 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 18:52:31.432  5793  5833 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 18:52:31.434  5660  5660 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 18:52:31.435  5660  5660 D PanProfile: Bluetooth service connected
11-23 18:52:31.438  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 18:52:31.445  5660  5660 D DockEventReceiver: finishStartingService: stopping service
11-23 18:52:31.445  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 18:52:31.453  5660  5660 D BluetoothPbap: Proxy object connected
11-23 18:52:31.453  5660  5660 D PbapServerProfile: Bluetooth service connected
,11-23 18:52:31.455  5793  5793 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 18:52:31.455  5793  5793 D ObexServerSockets0: prepareForNewConnect()
11-23 18:52:31.455  3146  3146 D BluetoothPbap: Proxy object connected
11-23 18:52:31.455  3146  3146 D PbapServerProfile: Bluetooth service connected
,11-23 18:52:31.466  5793  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 18:52:31.478  5793  5841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 18:52:31.479  5793  5841 I BtOppRfcommListener: Accept thread started.
,11-23 18:52:31.514  3803  3824 D BluetoothHeadset: Proxy object connected
,11-23 18:52:31.514   929   946 D BluetoothHeadset: Proxy object connected
11-23 18:52:31.515   929   929 D BluetoothHeadset: Proxy object connected
11-23 18:52:31.515  5660  5677 D BluetoothHeadset: Proxy object connected
11-23 18:52:31.515  5660  5677 D BluetoothHeadset: Proxy object connected
11-23 18:52:31.515  3146  3159 D BluetoothHeadset: Proxy object connected
,11-23 18:52:31.516   929   946 D BluetoothHeadset: Proxy object connected
,11-23 18:52:31.516  3146  3146 D HeadsetProfile: Bluetooth service connected
11-23 18:52:31.516   929   929 D BluetoothHeadset: Proxy object connected
11-23 18:52:31.516   929   929 D BluetoothHeadset: Proxy object connected
11-23 18:52:31.516  5660  5660 D HeadsetProfile: Bluetooth service connected
,11-23 18:52:31.518  5660  5660 D HeadsetProfile: Bluetooth service connected
11-23 18:52:31.518  3146  3157 D BluetoothHeadset: Proxy object connected
11-23 18:52:31.519  3146  3146 D HeadsetProfile: Bluetooth service connected
,11-23 18:52:31.523   929   946 D BluetoothHeadset: Proxy object connected
,11-23 18:52:33.371  3956  4448 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-23 18:52:35.207  5602  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 18:52:35.207  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:52:35.207  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:52:35.207  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 18:52:35.207  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 18:52:35.207  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 18:52:35.207  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 18:52:35.207  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 18:52:35.207  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 18:52:35.215  5602  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 18:52:35.215  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:35.216  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f40883 removed from the list
11-23 18:52:35.216  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 18:52:35.219  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 18:52:35.219  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5d1ba00 added. We now have 4 listener(s)
11-23 18:52:35.219  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 18:52:35.224   929  3836 D WifiService: setWifiEnabled: false pid=5602, uid=10077
,11-23 18:52:35.224   929  3836 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 18:52:40.239  5602  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 18:52:40.240   929   939 D WifiService: setWifiEnabled: true pid=5602, uid=10077
,11-23 18:52:40.240   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 18:52:40.247   508   922 D SoftapController: Softap fwReload - Ok
,11-23 18:52:40.252   508   922 D CommandListener: Setting iface cfg
,11-23 18:52:40.253   508   922 D CommandListener: Trying to bring down wlan0
,11-23 18:52:40.254   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-23 18:52:40.258   929  2989 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 18:52:40.884   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:40.926   929  2989 D wifi    : set interface wlan0 flags (UP)
,11-23 18:52:40.926   929  2989 I WifiHAL : Initializing wifi
11-23 18:52:40.927   929  2989 I WifiHAL : Creating socket
,11-23 18:52:40.935   929  2989 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-23 18:52:40.937   929  2989 D wifi    : Did set static halHandle = 0x7f74a5e680
11-23 18:52:40.937   929  2989 D wifi    : halHandle = 0x7f74a5e680, mVM = 0x7f9104d140, mCls = 0x19ca
11-23 18:52:40.937   929  2989 D wifi    : array field set
11-23 18:52:40.937   929  2989 I WifiNative-HAL: interface[0] = wlan0
11-23 18:52:40.938   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-23 18:52:40.941   929  5846 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547417876096
11-23 18:52:40.941   929  5846 D wifi    : waitForHalEvents called, vm = 0x7f9104d140, obj = 0x19ca, env = 0x7f75420000
,11-23 18:52:41.001  5847  5847 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 18:52:41.041   929  2989 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 18:52:41.072  5847  5847 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 18:52:41.147  5847  5847 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-23 18:52:41.147  5847  5847 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 18:52:41.173   929  2989 D WifiConfigStore: Loading config and enabling all networks 
,11-23 18:52:41.198   929  2989 D WifiConfigStore: loaded 0 passpoint configs
,11-23 18:52:41.199   929  2989 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-23 18:52:41.200   929  2989 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-23 18:52:41.201   929  2989 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 18:52:41.202   929  2989 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-23 18:52:41.204   929  2989 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-23 18:52:41.206   929  2989 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 18:52:41.206   929  2989 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-23 18:52:41.206   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-23 18:52:41.206   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-23 18:52:41.206   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 18:52:41.206   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 18:52:41.207   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 18:52:41.210   929  2989 D WifiNative-HAL: Setting external_sim to 1
,11-23 18:52:41.210  4478  4478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 18:52:41.210   929  2989 D wifi    : setting dfs flag to true, 0x7f758cec80
11-23 18:52:41.211   929  2989 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 18:52:41.211   929  2989 D wifi    : setting scan oui 0x7f758cec80
11-23 18:52:41.212   929  2989 D WifiHAL : Sending mac address OUI
,11-23 18:52:41.216   929  2989 E native  : do suspend false
,11-23 18:52:41.228   929  2989 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 18:52:41.229   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-23 18:52:41.229   929   929 D RttService: SCAN_AVAILABLE : 3
11-23 18:52:41.229   929  3098 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 18:52:41.230   508   922 D CommandListener: Setting iface cfg
,11-23 18:52:41.235   929  2988 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '137 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 137 Failed to set address (No such device)'
11-23 18:52:41.235   929  2988 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 18:52:41.240   929  2988 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 18:52:41.240   929  2988 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 18:52:41.272   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163899 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=36 mControllerEnergyUsed=136 }
,11-23 18:52:41.890   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:42.892   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:43.893   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:44.278  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 18:52:44.283  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 18:52:44.344   929  2989 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 18:52:44.346   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 18:52:44.346   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 18:52:44.360   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 18:52:44.400   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 18:52:44.406  5847  5847 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 18:52:44.840  5847  5847 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 18:52:44.880  5847  5847 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 18:52:44.881  5847  5847 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 18:52:44.894   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:52:44.895   929  2989 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 18:52:44.895   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 18:52:44.895   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 18:52:44.919   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 18:52:44.935   508   922 D CommandListener: Setting iface cfg
,11-23 18:52:44.941   929  2989 D WifiStateMachine: Start Dhcp Watchdog 2
,11-23 18:52:44.949   929  5852 D DhcpClient: Receive thread started
,11-23 18:52:44.954   929  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-23 18:52:44.954   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-23 18:52:44.954   929  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-23 18:52:45.042   929  2989 E native  : do suspend false
,11-23 18:52:45.061   929  5851 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 18:52:45.074   929  5852 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172673, domain null
,11-23 18:52:45.075   929  5851 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172673 seconds
11-23 18:52:45.077   929  5851 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 18:52:45.092   929  5852 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 18:52:45.093   929  5851 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 18:52:45.096   508   922 D CommandListener: Setting iface cfg
11-23 18:52:45.101   929  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 18:52:45.107   929  5851 D DhcpClient: Scheduling renewal in 86399s
,11-23 18:52:45.118   929  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 18:52:45.120   929  2989 D WifiConfigStore: No blacklist allowed without epno enabled
,11-23 18:52:45.120   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-23 18:52:45.124   929  2991 D ConnectivityService: Adding iface wlan0 to network 101
,11-23 18:52:45.134   929  2989 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 18:52:45.171   929  2991 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 18:52:45.171   929  2991 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-23 18:52:45.173   929  2991 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-23 18:52:45.175   929  2991 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-23 18:52:45.178   929  2991 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-23 18:52:45.188   929  2991 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:52:45.193   929  2991 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-23 18:52:45.193   929  2991 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-23 18:52:45.193   929  2991 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,11-23 18:52:45.193   929  2991 D ConnectivityService:    accepting network in place of null
,11-23 18:52:45.194   929  2991 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-23 18:52:45.195   929  2989 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 18:52:45.195   929  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 18:52:45.202   929  5850 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167828, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 18:52:45.222   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 18:52:45.245   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 18:52:45.249   929  2991 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-23 18:52:45.249   929  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 18:52:45.249  3771  3891 W QCNEJ   : |CORE| network available: 101
11-23 18:52:45.251   929  2991 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-23 18:52:45.252   929   946 D Tethering: MasterInitialState.processMessage what=3
11-23 18:52:45.256  3771  3891 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 18:52:45.258  3771  3891 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 18:52:45.258  3771  3891 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-23 18:52:45.259  5602  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 18:52:45.259  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 18:52:45.259  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 18:52:45.259  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 18:52:45.259  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 18:52:45.259  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 18:52:45.259  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 18:52:45.259  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 18:52:45.259  5602  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 18:52:45.263  5602  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 18:52:45.263  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.264  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5d1ba00 removed from the list
11-23 18:52:45.264  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:52:45.265   929  5849 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:802::200e
11-23 18:52:45.267  5037  5051 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 18:52:45.268  5602  5649 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-23 18:52:45.268  5037  5051 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-23 18:52:45.268  5037  5051 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,11-23 18:52:45.268  5037  5051 E SarControlService: no key has been found,reset the power
,11-23 18:52:45.268  5037  5084 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 18:52:45.268  5602  5649 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-23 18:52:45.268  5037  5084 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 18:52:45.268  5037  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 18:52:45.269  5065  5065 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 18:52:45.269  5065  5065 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 18:52:45.270  5037  5084 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 18:52:45.270  5037  5084 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 18:52:45.271  5037  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-23 18:52:45.271  5602  5649 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f115c3d Bundle[{}]
11-23 18:52:45.271  5065  5065 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 18:52:45.271  5065  5065 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 18:52:45.271  5602  5649 I io.jxcore.node.LifeCycleMonitor: start: OK
11-23 18:52:45.271  5602  5649 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-23 18:52:45.272  5602  5649 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-23 18:52:45.272  3970  3970 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-23 18:52:45.272  5602  5649 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-23 18:52:45.273  5602  5649 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-23 18:52:45.273  5602  5649 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-23 18:52:45.275  4087  4087 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 18:52:45.276  5065  5086 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402c9b0 HexData = [00000000ec03000000000000ffffffff]
11-23 18:52:45.276  5065  5086 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 18:52:45.276  5065  5086 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-23 18:52:45.277  5065  5086 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402c9b0 HexData = [00000000ed03000000000000ffffffff]
11-23 18:52:45.277  5065  5086 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 18:52:45.277  5065  5086 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-23 18:52:45.278  4087  4087 D SystemUpdateService: onCreate
11-23 18:52:45.278  5065  5065 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 18:52:45.280  5037  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 18:52:45.281  5065  5065 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 18:52:45.281  5037  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 18:52:45.281  5602  5649 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 164)
11-23 18:52:45.282  5602  5649 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-23 18:52:45.282  5602  5649 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
11-23 18:52:45.283  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 18:52:45.283  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf86239 added. We now have 3 listener(s)
11-23 18:52:45.284  4087  4087 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-23 18:52:45.285  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:52:45.285  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:52:45.285  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 18:52:45.285  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:45.285  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c5607e added. We now have 4 listener(s)
11-23 18:52:45.285  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 18:52:45.286  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 18:52:45.287  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 18:52:45.287  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae4a9df added. We now have 4 listener(s)
11-23 18:52:45.289  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:52:45.289  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:52:45.289  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 18:52:45.289  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:45.289  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98762c added. We now have 5 listener(s)
11-23 18:52:45.289  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 18:52:45.290  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:52:45.290  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:52:45.290  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 18:52:45.290  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:52:45.290  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:52:45.290  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:52:45.290  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf86239 removed from the list
11-23 18:52:45.290  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.290  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c5607e removed from the list
11-23 18:52:45.290  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:52:45.290  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.290  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.291  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.291  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.291  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.291  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:52:45.291  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:52:45.291  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.291  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c5607e not in the list
11-23 18:52:45.291  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.291  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.292  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.292  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.293  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.293  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:52:45.293  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:52:45.293  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.294  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98762c removed from the list
11-23 18:52:45.294  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 18:52:45.294  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:52:45.294  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:52:45.294  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae4a9df removed from the list
11-23 18:52:45.295  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 18:52:45.295  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f3e8f5 added. We now have 3 listener(s)
11-23 18:52:45.296  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:52:45.296  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:52:45.297  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 18:52:45.297  4087  4087 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-23 18:52:45.297  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:45.297  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@953068a added. We now have 4 listener(s)
11-23 18:52:45.297  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 18:52:45.297  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 18:52:45.299  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 18:52:45.299  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1404fb added. We now have 4 listener(s)
,11-23 18:52:45.301  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:52:45.301  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 18:52:45.301  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 18:52:45.301  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:45.301  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc918 added. We now have 5 listener(s)
11-23 18:52:45.301  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 18:52:45.301  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:52:45.302  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 18:52:45.302  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 18:52:45.302  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 18:52:45.302  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 18:52:45.303  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 18:52:45.306  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 18:52:45.306  5602  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 18:52:45.306  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 18:52:45.306  4087  5396 I iu.UploadsManager: num queued entries: 0
,11-23 18:52:45.307  4087  5396 I iu.UploadsManager: num updated entries: 0
11-23 18:52:45.307  4087  5396 I iu.SyncManager: NEXT; no task
,11-23 18:52:45.309  4087  5862 I SystemUpdateService: active receiver: enabled
,11-23 18:52:45.310  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.310  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 18:52:45.310  4087  4087 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 18:52:45.311  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 18:52:45.311  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 18:52:45.311  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 18:52:45.312  4087  4087 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 18:52:45.315  5699  5699 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 18:52:45.316  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.316  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 18:52:45.316  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 18:52:45.316  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 18:52:45.316  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 18:52:45.316  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.317  5602  5649 D BluetoothAdapter: STATE_ON
,11-23 18:52:45.319  5793  5804 D BtGatt.GattService: registerClient() - UUID=1e81d8cb-240e-4c5c-a01a-a405690b08df
11-23 18:52:45.320  5793  5809 D BtGatt.GattService: onClientRegistered() - UUID=1e81d8cb-240e-4c5c-a01a-a405690b08df, clientIf=5
11-23 18:52:45.320  5602  5612 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 18:52:45.321  5793  5832 D BtGatt.GattService: start scan with filters
11-23 18:52:45.323  5699  5699 D SprintDMHelper: simOperator: 
,11-23 18:52:45.323  5699  5699 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-23 18:52:45.324  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 18:52:45.324  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.324  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-23 18:52:45.324  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.324  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 18:52:45.325  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 18:52:45.325  5793  5812 D BtGatt.ScanManager: handling starting scan
11-23 18:52:45.325  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.325  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 18:52:45.325  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 18:52:45.325  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-23 18:52:45.325  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.325  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.325  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 18:52:45.325  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.326  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:52:45.327  5793  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17edba6
11-23 18:52:45.328  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.328  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:52:45.328  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.328  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.328  5602  5649 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 18:52:45.328  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 18:52:45.328  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 18:52:45.328  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:52:45.328  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:52:45.328  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:52:45.328  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 18:52:45.328  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 18:52:45.328  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.328  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 18:52:45.328  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 18:52:45.328  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.329  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.329  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.329  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 18:52:45.329  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.329  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:52:45.330  5793  5831 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 18:52:45.330  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 18:52:45.330  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:52:45.331  5793  5832 D BtGatt.GattService: stopScan() - queue size =1
11-23 18:52:45.333  5793  5821 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 18:52:45.333  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 18:52:45.333  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.333  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-23 18:52:45.333  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.333  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.333  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.333  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.333  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 18:52:45.333  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.333  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.334  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.334  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 18:52:45.334  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 18:52:45.334  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 18:52:45.335  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.335  5793  5809 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 18:52:45.335  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.336  5793  5812 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 18:52:45.336  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.336  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:52:45.336  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.336  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.337  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 18:52:45.339  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:52:45.339  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 18:52:45.339  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:52:45.339  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.339  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:52:45.339  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.339  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:52:45.339  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:52:45.339  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 18:52:45.339  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:52:45.339  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:52:45.339  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:52:45.339  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f3e8f5 removed from the list
11-23 18:52:45.339  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.339  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 18:52:45.339  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@953068a removed from the list
11-23 18:52:45.339  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.339  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:52:45.339  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-23 18:52:45.339  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.340  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 18:52:45.340  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.340  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.340  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.340  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.340  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:52:45.341  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.341  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.342  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 18:52:45.342  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.342  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.342  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.342  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.343  5793  5812 D BtGatt.ScanManager: Starting BLE batch scan
11-23 18:52:45.343  5793  5812 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 18:52:45.343   929  5849 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 17:52:45 GMT], X-Android-Received-Millis=[1479923565342], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479923565314]}
11-23 18:52:45.343  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.343  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.343  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.343  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:52:45.343  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:52:45.343  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.343  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@953068a not in the list
11-23 18:52:45.343  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.344  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.344   929  2991 D ConnectivityService: setProvNotificationVisibleInte,nt null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-23 18:52:45.344   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-23 18:52:45.344   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-23 18:52:45.345  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.345  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.345   929  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-23 18:52:45.346  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.347  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:52:45.347  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:52:45.347  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.347  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc918 removed from the list
11-23 18:52:45.347  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:52:45.347  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:52:45.347  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:52:45.348  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1404fb removed from the list
11-23 18:52:45.348  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 18:52:45.349  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd41ad added. We now have 3 listener(s)
11-23 18:52:45.350  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:52:45.350  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:52:45.350  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 18:52:45.351  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:45.351  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea5dce2 added. We now have 4 listener(s)
11-23 18:52:45.351  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 18:52:45.351  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 18:52:45.353  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 18:52:45.353  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb81873 added. We now have 4 listener(s)
11-23 18:52:45.353  4087  5862 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-23 18:52:45.355  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:52:45.355  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:52:45.355  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 18:52:45.355  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:45.355  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c7a330 added. We now have 5 listener(s)
11-23 18:52:45.355  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 18:52:45.355  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:52:45.356  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:52:45.356  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 18:52:45.356  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 18:52:45.357  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 18:52:45.357  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 18:52:45.359  5793  5809 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 18:52:45.359  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 18:52:45.359  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.362  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 18:52:45.362  5602  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 18:52:45.362  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 18:52:45.364  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 18:52:45.364  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.366  5793  5812 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 18:52:45.367  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.367  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 18:52:45.368  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 18:52:45.368  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 18:52:45.368  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 18:52:45.370  4087  5862 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-23 18:52:45.371  4087  5862 I SystemUpdateService: now status is 0 (complete)
11-23 18:52:45.371  4087  5862 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 18:52:45.371  4087  5862 I SystemUpdateService: file has been verified
11-23 18:52:45.371  4087  5862 I SystemUpdateService: OTA package size = 21989297
11-23 18:52:45.372  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.372  5793  5809 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 18:52:45.372  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.372  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 18:52:45.373  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 18:52:45.373  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 18:52:45.373  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 18:52:45.373  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.373  5793  5809 E BtGatt.ContextMap: Context not found for ID 5
11-23 18:52:45.373  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:52:45.376  5793  5804 D BtGatt.GattService: registerClient() - UUID=a5dd59b6-c139-4785-b69f-0dcc961d1584
11-23 18:52:45.376  5793  5809 D BtGatt.GattService: onClientRegistered() - UUID=a5dd59b6-c139-4785-b69f-0dcc961d1584, clientIf=5
11-23 18:52:45.376  5602  5612 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 18:52:45.377  5793  5821 D BtGatt.GattService: start scan with filters
11-23 18:52:45.377  4087  5862 I SystemUpdateService: showing system update notification
11-23 18:52:45.379  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 18:52:45.379  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.380  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 18:52:45.380  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.380  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 18:52:45.380  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 18:52:45.380  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.380  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 18:52:45.380  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 18:52:45.380  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.380  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.380  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.380  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.381  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 18:52:45.381  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.381  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 18:52:45.382  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.382  5793  5812 D BtGatt.ScanManager: stopping BLe Batch
11-23 18:52:45.383  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.383  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:52:45.384  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.384  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 18:52:45.384  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:52:45.384  5602  5649 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-23 18:52:45.384  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:52:45.384  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:52:45.384  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:52:45.384  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:52:45.384  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:52:45.384  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:52:45.385  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:52:45.385  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:52:45.385  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd41ad removed from the list
11-23 18:52:45.385  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.385  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.385  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea5dce2 removed from the list
11-23 18:52:45.385  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:52:45.385  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:52:45.385  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:52:45.385  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.385  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 18:52:45.385  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 18:52:45.385  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:52:45.385  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:52:45.386   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-23 18:52:45.387  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.387  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.387  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 18:52:45.387  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.387  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.387  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.388  5793  5812 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 18:52:45.388  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:52:45.388  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.388  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.388  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.388  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:52:45.388  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:52:45.388  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.388  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea5dce2 not in the list
11-23 18:52:45.388  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 18:52:45.388  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.388  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 18:52:45.388  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 18:52:45.388  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.389  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.389  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.389  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 18:52:45.389  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.389  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:52:45.390  5793  5821 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 18:52:45.390  4087  4087 D SystemUpdateService: onDestroy
11-23 18:52:45.390  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 18:52:45.391  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:52:45.391  5793  5832 D BtGatt.GattService: stopScan() - queue size =0
11-23 18:52:45.392  5793  5804 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 18:52:45.392  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 18:52:45.392  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.392  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 18:52:45.392  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.393  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.393  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.393  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.393  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 18:52:45.393  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.393  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.393  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.393  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 18:52:45.393  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 18:52:45.393  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 18:52:45.394  5793  5809 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 18:52:45.394  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.394  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.395  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.395  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:52:45.395  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.395  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.395  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:52:45.395  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:52:45.395  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.395  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:52:45.395  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c7a330 removed from the list
11-23 18:52:45.395  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:52:45.395  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:52:45.395  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:52:45.395  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:52:45.395  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 18:52:45.395  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb81873 removed from the list
11-23 18:52:45.395  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.395  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 18:52:45.395  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 18:52:45.395  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.395  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.396  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.396  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:52:45.396  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.396  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.396  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 18:52:45.396  5793  5812 D BtGatt.ScanManager: handling starting scan
11-23 18:52:45.396  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f51f965 added. We now have 3 listener(s)
11-23 18:52:45.397  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.397  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.397  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.398  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:52:45.398  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:52:45.398  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 18:52:45.398  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:45.398  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@902263a added. We now have 4 listener(s)
11-23 18:52:45.398  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 18:52:45.398  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 18:52:45.399  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 18:52:45.399  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86c22eb added. We now have 4 listener(s)
11-23 18:52:45.400  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:52:45.401  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:52:45.401  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 18:52:45.401  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:45.401  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@570a848 added. We now have 5 listener(s)
11-23 18:52:45.401  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 18:52:45.401  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:52:45.401  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 18:52:45.401  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 18:52:45.401  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 18:52:45.401  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 18:52:45.402  5793  5809 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 18:52:45.402  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.402  5793  5812 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 18:52:45.403  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 18:52:45.406  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 18:52:45.406  5602  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 18:52:45.406  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 18:52:45.407  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 18:52:45.407  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.407  5793  5812 D BtGatt.ScanManager: Starting BLE batch scan
11-23 18:52:45.407  5793  5812 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 18:52:45.409  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.410  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 18:52:45.410  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 18:52:45.410  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 18:52:45.410  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 18:52:45.415  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.415  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 18:52:45.416  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 18:52:45.416  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 18:52:45.416  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 18:52:45.416  5793  5809 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 18:52:45.416  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.416  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.417  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:52:45.419  5793  5831 D BtGatt.GattService: registerClient() - UUID=61e5d302-db8c-421d-819d-e8fb9381b768
11-23 18:52:45.419  5793  5809 D BtGatt.GattService: onClientRegistered() - UUID=61e5d302-db8c-421d-819d-e8fb9381b768, clientIf=5
11-23 18:52:45.419  5602  5612 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 18:52:45.420  5793  5821 D BtGatt.GattService: start scan with filters
11-23 18:52:45.421  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 18:52:45.421  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:52:45.422  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 18:52:45.422  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.422  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 18:52:45.422  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.422  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 18:52:45.422  5793  5812 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 18:52:45.422  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 18:52:45.422  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.422  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 18:52:45.422  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 18:52:45.422  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.423  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.423  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.423  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.423  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 18:52:45.423  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.426  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.426  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:52:45.426  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.426  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.426  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.427  5793  5809 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 18:52:45.427  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.429  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.429  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.429  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.429  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 18:52:45.429  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.429  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:52:45.429  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:52:45.430  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:52:45.430  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:52:45.430  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:52:45.430  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:52:45.430  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:52:45.430  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:52:45.430  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f51f965 removed from the list
11-23 18:52:45.430  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.430  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@902263a removed from the list
11-23 18:52:45.430  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:52:45.430  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:52:45.430  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:52:45.430  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.430  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 18:52:45.430  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 18:52:45.430  5602  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 18:52:45.430  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 18:52:45.430  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.431  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.431  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.431  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.431  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:52:45.431  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:52:45.431  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.431  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@902263a not in the list
11-23 18:52:45.431  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 18:52:45.431  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.432  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 18:52:45.432  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 18:52:45.432  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.432  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.432  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.432  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 18:52:45.432  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.433  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:52:45.433  5793  5803 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 18:52:45.433  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 18:52:45.433  5602  5649 D BluetoothAdapter: STATE_ON
11-23 18:52:45.434  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 18:52:45.434  5793  5821 D BtGatt.GattService: stopScan() - queue size =0
11-23 18:52:45.434  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.434  5793  5812 D BtGatt.ScanManager: stopping BLe Batch
11-23 18:52:45.435  5793  5832 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 18:52:45.435  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 18:52:45.435  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.435  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 18:52:45.435  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.435  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.435  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.436  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.436  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 18:52:45.436  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.436  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.436  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.436  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 18:52:45.437  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 18:52:45.437  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 18:52:45.438  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.438  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.438  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:52:45.439  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.439  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.439  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:52:45.439  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:52:45.439  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.439  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:52:45.439  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@570a848 removed from the list
11-23 18:52:45.439  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:52:45.439  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 18:52:45.439  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:52:45.439  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:52:45.439  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 18:52:45.439  5602  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 18:52:45.439  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86c22eb removed from the list
11-23 18:52:45.439  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.439  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.439  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 18:52:45.439  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 18:52:45.439  5793  5812 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 18:52:45.439  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.439  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.439  5602  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.439  5602  5602 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 18:52:45.440  5602  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.440  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.440  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 18:52:45.440  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61ef01d added. We now have 3 listener(s)
11-23 18:52:45.441  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.441  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.441  5602  5602 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 18:52:45.441  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:52:45.441  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:52:45.441  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 18:52:45.441  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:45.441  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc34292 added. We now have 4 listener(s)
11-23 18:52:45.441  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 18:52:45.441  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 18:52:45.443  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 18:52:45.443  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f580463 added. We now have 4 listener(s)
11-23 18:52:45.444  5793  5809 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 18:52:45.444  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.445  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 18:52:45.445  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 18:52:45.445  5602  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 18:52:45.445  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 18:52:45.445  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1623860 added. We now have 5 listener(s)
11-23 18:52:45.445  5602  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 18:52:45.445  5602  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 18:52:45.445  5793  5812 D BtGatt.ScanManager: handling starting scan
11-23 18:52:45.445  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:52:45.446  5602  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 18:52:45.446  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:52:45.446  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:52:45.446  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:52:45.446  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61ef01d removed from the list
11-23 18:52:45.446  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.446  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc34292 removed from the list
11-23 18:52:45.446  5602  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-23 18:52:45.446  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.446  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.448  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.448  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.448  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.448  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:52:45.448  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:52:45.448  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.448  5602  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc34292 not in the list
11-23 18:52:45.448  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.449  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.451  5793  5809 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 18:52:45.451  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.451  5793  5812 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 18:52:45.453  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.453  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.453  5602  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 18:52:45.453  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 18:52:45.453  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 18:52:45.453  5602  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 18:52:45.453  5602  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1623860 removed from the list
11-23 18:52:45.454  5602  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 18:52:45.454  5602  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 18:52:45.454  5602  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 18:52:45.454  5602  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f580463 removed from the list
11-23 18:52:45.455  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-23 18:52:45.455  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-23 18:52:45.455  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-23 18:52:45.455  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:52:45.455  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-23 18:52:45.455  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 18:52:45.456  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 18:52:45.456  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.456  5793  5812 D BtGatt.ScanManager: Starting BLE batch scan
11-23 18:52:45.456  5793  5812 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 18:52:45.464  5793  5809 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 18:52:45.464  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:52:45.469  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 18:52:45.469  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.470  5793  5812 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 18:52:45.474  5793  5809 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 18:52:45.474  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.475  5793  5809 E BtGatt.ContextMap: Context not found for ID 5
11-23 18:52:45.480  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 18:52:45.480  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.481  5793  5812 D BtGatt.ScanManager: stopping BLe Batch
11-23 18:52:45.486  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 18:52:45.486  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 18:52:45.486  5793  5812 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 18:52:45.489  4478  5867 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-23 18:52:45.491  5793  5809 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 18:52:45.491  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 18:52:45.841  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 18:52:45.895   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 18:52:45.897  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 18:52:45.940  5602  5602 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 18:52:46.250   929  2991 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-23 18:52:47.614  5602  5874 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 18:52:47.614  5602  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 18:52:48.406  5602  5874 W !!      : call onHalfStreamCopied
,11-23 18:52:48.407  5602  5874 I testCopyDataAndClose: closing input stream
,11-23 18:52:49.177  5602  5874 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 18:52:49.177  5602  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 18:52:49.177  5602  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 18:52:49.177  5602  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 18:52:49.177  5602  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 18:52:49.177  5602  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 18:52:49.177  5602  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-23 18:52:49.177  5602  5874 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 18:52:49.177  5602  5874 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 18:52:49.178  5602  5874 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 18:52:49.178  5602  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 18:52:53.199   929  2991 D ConnectivityService: handlePromptUnvalidated 101
,11-23 18:52:53.485  5602  5875 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
11-23 18:52:53.485  5602  5875 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 18:52:55.485  5602  5649 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 176. Connection data: Peer properties: [null null].
11-23 18:52:55.485  5602  5649 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 18:52:55.485  5602  5649 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 176, name: My test thread name)
,11-23 18:52:55.619  5602  5875 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-23 18:52:55.619  5602  5875 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
11-23 18:52:55.619  5602  5875 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-23 18:52:55.625  5602  5876 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 18:52:55.625  5602  5876 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 18:52:56.275   929  2989 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 18:52:57.228  5602  5876 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 18:53:01.476  5602  5877 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-23 18:53:01.476  5602  5877 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 18:53:01.477  5602  5877 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: My test thread name). Connection data: Peer properties: [null null].
11-23 18:53:01.477  5602  5877 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 18:53:01.477  5602  5877 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 18:53:01.477  5602  5877 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 18:53:01.477  5602  5877 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 18:53:01.477  5602  5877 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 18:53:01.477  5602  5877 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 18:53:01.478  5602  5877 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 18:53:01.478  5602  5877 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-23 18:53:01.478  5602  5877 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-23 18:53:01.478  5602  5877 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-23 18:53:01.479  5602  5649 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-23 18:53:01.482  5602  5878 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 18:53:01.482  5602  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 18:53:01.483  5602  5878 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 184, thread name: My test thread name): Test exception.
11-23 18:53:01.483  5602  5878 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 18:53:01.483  5602  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-23 18:53:01.483  5602  5878 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-23 18:53:01.483  5602  5878 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 18:53:01.483  5602  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 18:53:01.487  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-23 18:53:01.487  5602  5649 I jxcore-log: 
11-23 18:53:01.487  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-23 18:53:01.487  5602  5649 I jxcore-log: 
11-23 18:53:01.488  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-23 18:53:01.488  5602  5649 I jxcore-log: 
11-23 18:53:01.488  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-23 18:53:01.488  5602  5649 I jxcore-log: 
,11-23 18:53:01.488  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG UnitTest_app: 'Total duration:  91807'
11-23 18:53:01.488  5602  5649 I jxcore-log: 
11-23 18:53:01.490  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-23 18:53:01.490  5602  5649 I jxcore-log: 
,11-23 18:53:01.495  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 18:53:01.495  5602  5649 I jxcore-log: 
,11-23 18:53:01.505  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 18:53:01.505  5602  5649 I jxcore-log: 
11-23 18:53:01.506  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 18:53:01.506  5602  5649 I jxcore-log: 
,11-23 18:53:01.506  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 18:53:01.506  5602  5649 I jxcore-log: 
11-23 18:53:01.507  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 18:53:01.507  5602  5649 I jxcore-log: 
11-23 18:53:01.507  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 18:53:01.507  5602  5649 I jxcore-log: 
11-23 18:53:01.507  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 18:53:01.507  5602  5649 I jxcore-log: 
11-23 18:53:01.507  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 18:53:01.507  5602  5649 I jxcore-log: 
11-23 18:53:01.508  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 18:53:01.508  5602  5649 I jxcore-log: 
11-23 18:53:01.508  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 18:53:01.508  5602  5649 I jxcore-log: 
,11-23 18:53:01.508  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 18:53:01.508  5602  5649 I jxcore-log: 
11-23 18:53:01.508  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 18:53:01.508  5602  5649 I jxcore-log: 
11-23 18:53:01.509  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 18:53:01.509  5602  5649 I jxcore-log: 
11-23 18:53:01.509  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 18:53:01.509  5602  5649 I jxcore-log: 
,11-23 18:53:01.509  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 18:53:01.509  5602  5649 I jxcore-log: 
11-23 18:53:01.509  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 18:53:01.509  5602  5649 I jxcore-log: 
11-23 18:53:01.510  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","ssidName":"<unknown ssid>"}'
11-23 18:53:01.510  5602  5649 I jxcore-log: 
11-23 18:53:01.510  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 18:53:01.510  5602  5649 I jxcore-log: 
11-23 18:53:01.510  5602  5602 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-23 18:53:01.510  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 18:53:01.510  5602  5649 I jxcore-log: 
,11-23 18:53:01.510  5602  5602 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-23 18:53:01.510  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 18:53:01.510  5602  5649 I jxcore-log: 
11-23 18:53:01.511  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 18:53:01.511  5602  5649 I jxcore-log: 
11-23 18:53:01.511  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 18:53:01.511  5602  5649 I jxcore-log: 
11-23 18:53:01.511  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 18:53:01.511  5602  5649 I jxcore-log: 
,11-23 18:53:01.512  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 18:53:01.512  5602  5649 I jxcore-log: 
11-23 18:53:01.513  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 18:53:01.513  5602  5649 I jxcore-log: 
11-23 18:53:01.514  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 18:53:01.514  5602  5649 I jxcore-log: 
11-23 18:53:01.514  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 18:53:01.514  5602  5649 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-23 18:53:01.514  5602  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 18:53:01.514  5602  5649 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-23 18:53:01.514  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 18:53:01.514  5602  5649 I jxcore-log: 
,11-23 18:53:01.514  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 18:53:01.514  5602  5649 I jxcore-log: 
11-23 18:53:01.515  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 18:53:01.515  5602  5649 I jxcore-log: 
11-23 18:53:01.515  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 18:53:01.515  5602  5649 I jxcore-log: 
11-23 18:53:01.515  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 18:53:01.515  5602  5649 I jxcore-log: 
11-23 18:53:01.515  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 18:53:01.515  5602  5649 I jxcore-log: 
,11-23 18:53:01.525  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-23 18:53:01.525  5602  5649 I jxcore-log: 
,11-23 18:53:01.526  5602  5649 I jxcore-log: 2016-11-23 17:53:01 - WARN testUtils: 'myNameCallback not set!'
11-23 18:53:01.526  5602  5649 I jxcore-log: 
,11-23 18:53:03.564  5602  5649 I jxcore-log: 2016-11-23 17:53:03 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-23 18:53:03.564  5602  5649 I jxcore-log: 
,11-23 18:53:03.567  5602  5649 I jxcore-log: 2016-11-23 17:53:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-23 18:53:03.567  5602  5649 I jxcore-log: 
,11-23 18:53:03.916  5602  5649 I jxcore-log: 2016-11-23 17:53:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-23 18:53:03.916  5602  5649 I jxcore-log: 
,11-23 18:53:03.927  5602  5649 I jxcore-log: 2016-11-23 17:53:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-23 18:53:03.927  5602  5649 I jxcore-log: 
,11-23 18:53:05.043  5602  5649 I jxcore-log: 2016-11-23 17:53:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-23 18:53:05.043  5602  5649 I jxcore-log: 
,11-23 18:53:05.235  5602  5649 I jxcore-log: 2016-11-23 17:53:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-23 18:53:05.235  5602  5649 I jxcore-log: 
,11-23 18:53:05.240  5602  5649 I jxcore-log: 2016-11-23 17:53:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-23 18:53:05.240  5602  5649 I jxcore-log: 
,11-23 18:53:05.245  5602  5649 I jxcore-log: 2016-11-23 17:53:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-23 18:53:05.245  5602  5649 I jxcore-log: 
,11-23 18:53:05.727  5602  5649 I jxcore-log: 2016-11-23 17:53:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-23 18:53:05.727  5602  5649 I jxcore-log: 
,11-23 18:53:05.772  5602  5649 I jxcore-log: 2016-11-23 17:53:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-23 18:53:05.772  5602  5649 I jxcore-log: 
,11-23 18:53:05.785  5602  5649 I jxcore-log: 2016-11-23 17:53:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-23 18:53:05.785  5602  5649 I jxcore-log: 
,11-23 18:53:05.789  5602  5649 I jxcore-log: 2016-11-23 17:53:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-23 18:53:05.789  5602  5649 I jxcore-log: 
,11-23 18:53:05.896   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:06.057  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-23 18:53:06.057  5602  5649 I jxcore-log: 
,11-23 18:53:06.184  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-23 18:53:06.184  5602  5649 I jxcore-log: 
,11-23 18:53:06.551  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-23 18:53:06.551  5602  5649 I jxcore-log: 
,11-23 18:53:06.560  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-23 18:53:06.560  5602  5649 I jxcore-log: 
,11-23 18:53:06.564  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-23 18:53:06.564  5602  5649 I jxcore-log: 
,11-23 18:53:06.569  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-23 18:53:06.569  5602  5649 I jxcore-log: 
,11-23 18:53:06.575  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-23 18:53:06.575  5602  5649 I jxcore-log: 
,11-23 18:53:06.604  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-23 18:53:06.604  5602  5649 I jxcore-log: 
,11-23 18:53:06.642  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-23 18:53:06.642  5602  5649 I jxcore-log: 
,11-23 18:53:06.649  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-23 18:53:06.649  5602  5649 I jxcore-log: 
,11-23 18:53:06.656  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-23 18:53:06.656  5602  5649 I jxcore-log: 
,11-23 18:53:06.671  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-23 18:53:06.671  5602  5649 I jxcore-log: 
,11-23 18:53:06.687  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-23 18:53:06.687  5602  5649 I jxcore-log: 
,11-23 18:53:06.693  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-23 18:53:06.693  5602  5649 I jxcore-log: 
,11-23 18:53:06.698  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-23 18:53:06.698  5602  5649 I jxcore-log: 
,11-23 18:53:06.711  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-23 18:53:06.711  5602  5649 I jxcore-log: 
,11-23 18:53:06.728  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-23 18:53:06.728  5602  5649 I jxcore-log: 
,11-23 18:53:06.742  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-23 18:53:06.742  5602  5649 I jxcore-log: 
,11-23 18:53:06.753  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-23 18:53:06.753  5602  5649 I jxcore-log: 
,11-23 18:53:06.765  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-23 18:53:06.765  5602  5649 I jxcore-log: 
,11-23 18:53:06.775  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-23 18:53:06.775  5602  5649 I jxcore-log: 
,11-23 18:53:06.788  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-23 18:53:06.788  5602  5649 I jxcore-log: 
,11-23 18:53:06.798  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-23 18:53:06.798  5602  5649 I jxcore-log: 
,11-23 18:53:06.805  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-23 18:53:06.805  5602  5649 I jxcore-log: 
,11-23 18:53:06.827  5602  5649 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-23 18:53:06.828  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO testUtils: 'BLE multiple advertisement supported'
11-23 18:53:06.828  5602  5649 I jxcore-log: 
,11-23 18:53:06.861  5602  5649 I jxcore-log: 2016-11-23 17:53:06 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-23 18:53:06.861  5602  5649 I jxcore-log: 
,11-23 18:53:06.900   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:07.266  5602  5649 I jxcore-log: 2016-11-23 17:53:07 - DEBUG CoordinatedClient: 'connected to the test server'
11-23 18:53:07.266  5602  5649 I jxcore-log: 
,11-23 18:53:07.901   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:08.902   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:09.138  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 18:53:09.903   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:10.904   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 18:53:25.176   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:53:35.905   598   598 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 18:53:35.905   598   598 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 18:53:42.381   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:53:42.391   929  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 56
,11-23 18:53:45.409   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:53:45.413   929  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-23 18:53:45.907   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:46.908   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:47.910   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:48.433   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:53:48.912   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:49.913   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:50.914   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 18:53:51.469   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:53:55.915   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:56.916   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:57.917   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:58.919   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:53:59.395  4087  5888 I EventLogService: Aggregate from 1479921839274 (log), 1479921839274 (data)
,11-23 18:53:59.518  3602  5891 I VacuumService: Vacuum at: now=1479923639518 tag=VacuumService
,11-23 18:53:59.543  3602  5894 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-23 18:53:59.576  3602  5892 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-23 18:53:59.579  3602  5892 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-23 18:53:59.603  3602  5892 W Uploader:  no longer exists, so no auth token.
,11-23 18:53:59.610  3602  5894 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 18:53:59.880  3602  5896 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 18:53:59.920   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:00.054  3602  5894 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 18:54:00.112  3602  5892 W Uploader:  no longer exists, so no auth token.
,11-23 18:54:00.120  3602  5896 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 18:54:00.195  3602  5894 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 18:54:00.275  3602  5896 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 18:54:00.921   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 18:54:05.180   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:54:10.922   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:11.923   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:12.924   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:13.926   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:14.927   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:15.928   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 18:54:25.180   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:54:30.929   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:31.930   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:32.931   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:33.932   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:34.933   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:35.934   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 18:54:55.935   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:56.937   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:57.938   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:58.939   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:54:59.940   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:00.940   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 18:55:01.072   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:55:04.104   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:55:05.186   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:55:25.190   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:55:25.941   598   598 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 18:55:25.941   598   598 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 18:55:40.942   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:41.944   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:42.945   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:43.946   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:44.947   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:45.191   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:55:45.948   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 18:55:50.949   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:51.951   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:52.952   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:53.954   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:54.955   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:55:55.956   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 18:56:04.604   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:56:05.958   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:06.959   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:07.625   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:56:07.961   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:08.962   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:09.963   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:10.964   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 18:56:16.699   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:56:19.734   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:56:25.195   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:56:25.966   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:26.967   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:27.969   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:28.971   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:29.972   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:30.973   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 18:56:45.198   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:56:50.974   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:51.975   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:52.976   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:53.977   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:54.979   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:56:55.980   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 18:57:05.129   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:57:05.198   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:57:08.164   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:57:20.980   598   598 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 18:57:20.980   598   598 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 18:57:25.201   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:57:40.982   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:57:41.466   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:57:41.983   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:57:42.985   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:57:43.986   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:57:44.499   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:57:44.987   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:57:45.203   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 18:57:45.988   598   598 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 18:57:50.540   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:57:50.990   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:57:51.991   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:57:52.459  5602  5649 I jxcore-log: 2016-11-23 17:57:52 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-23 18:57:52.459  5602  5649 I jxcore-log: 
,11-23 18:57:52.622  5602  5649 I jxcore-log: 2016-11-23 17:57:52 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 18:57:52.622  5602  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 18:57:52.622  5602  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 18:57:52.622  5602  5649 I jxcore-log: emit@events.js:82:1
11-23 18:57:52.622  5602  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 18:57:52.622  5602  5649 I jxcore-log: emit@events.js:82:1''
11-23 18:57:52.622  5602  5649 I jxcore-log: 
,11-23 18:57:52.624  5602  5649 I jxcore-log: 2016-11-23 17:57:52 - DEBUG CoordinatedClient: 'test client failed'
11-23 18:57:52.624  5602  5649 I jxcore-log: 
,11-23 18:57:52.633  5602  5649 I jxcore-log: 2016-11-23 17:57:52 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 18:57:52.633  5602  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 18:57:52.633  5602  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 18:57:52.633  5602  5649 I jxcore-log: emit@events.js:82:1
11-23 18:57:52.633  5602  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 18:57:52.633  5602  5649 I jxcore-log: emit@events.js:82:1''
11-23 18:57:52.633  5602  5649 I jxcore-log: 
,11-23 18:57:52.634  5602  5649 I jxcore-log: 2016-11-23 17:57:52 - DEBUG CoordinatedClient: 'test client failed'
11-23 18:57:52.634  5602  5649 I jxcore-log: 
,11-23 18:57:52.638  5602  5649 I jxcore-log: 2016-11-23 17:57:52 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 18:57:52.638  5602  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 18:57:52.638  5602  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 18:57:52.638  5602  5649 I jxcore-log: emit@events.js:82:1
11-23 18:57:52.638  5602  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 18:57:52.638  5602  5649 I jxcore-log: emit@events.js:82:1''
11-23 18:57:52.638  5602  5649 I jxcore-log: 
11-23 18:57:52.639  5602  5649 I jxcore-log: 2016-11-23 17:57:52 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-23 18:57:52.639  5602  5649 I jxcore-log: 
,11-23 18:57:52.992   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:57:53.184  5905  5905 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-23 18:57:53.189  5905  5905 D AndroidRuntime: CheckJNI is OFF
,11-23 18:57:53.214  5905  5905 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-23 18:57:53.244  5905  5905 I Radio-JNI: register_android_hardware_Radio DONE
,11-23 18:57:53.260  5905  5905 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-23 18:57:53.268   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-23 18:57:53.268   929   942 I ActivityManager: Killing 5602:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-23 18:57:53.372   929  2990 D WifiService: Client connection lost with reason: 4
,11-23 18:57:53.374   929  3827 I WindowState: WIN DEATH: Window{1a3cd1c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-23 18:57:53.374   929  5463 D GraphicsStats: Buffer count: 2
,11-23 18:57:53.387   929   942 W ActivityManager: Force removing ActivityRecord{c62f124 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-23 18:57:53.408   929   952 I art     : Starting a blocking GC Explicit
,11-23 18:57:53.414   929  3173 W ActivityManager: Spurious death for ProcessRecord{1c103d6 0:com.test.thalitest/u0a77}, curProc for 5602: null
,11-23 18:57:53.444  3434  3434 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[26260]" dev="sockfs" ino=26260 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 18:57:53.444  3434  3434 W Binder_5: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[26260]" dev="sockfs" ino=26260 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 18:57:53.446   929  3434 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5602 uid 10077
11-23 18:57:53.447  3685  3685 I Keyboard.Facilitator: onFinishInput()
,11-23 18:57:53.524  3970  5920 I MicroRecognitionRnrImpl: Starting detection.
11-23 18:57:53.524   929   952 I art     : Explicit concurrent mark sweep GC freed 138011(9MB) AllocSpace objects, 93(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.897ms total 115.387ms
,11-23 18:57:53.527  3970  5921 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@8cc99bd
,11-23 18:57:53.529   513  5923 I AudioFlinger: AudioFlinger's thread 0xf1b80000 ready to run
11-23 18:57:53.536   513  3011 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-23 18:57:53.538  3970  5921 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@8cc99bd
,11-23 18:57:53.548   513  5923 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-23 18:57:53.548   513  5923 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-23 18:57:53.548   513  5923 I ACDB-LOADER: ACDB AFE returned = -19
11-23 18:57:53.548   513  5923 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-23 18:57:53.548   513  5923 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-23 18:57:53.548   513  5923 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
11-23 18:57:53.549   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-23 18:57:53.554  5905  5905 I art     : System.exit called, status: 0
11-23 18:57:53.554  5905  5905 I AndroidRuntime: VM exiting with result code 0.
,11-23 18:57:53.556   513  5923 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-23 18:57:53.558   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 18:57:53.573   929   952 I ActivityManager: Start proc 5927:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-23 18:57:53.575   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-23 18:57:53.584  3685  3685 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-23 18:57:53.586  5793  5793 D BluetoothMapAppObserver: onReceive
,11-23 18:57:53.587  5793  5793 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-23 18:57:53.589  3956  4176 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-23 18:57:53.592   929  2955 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-23 18:57:53.611  3685  5939 I Keyboard.Facilitator.DecoderInitializer: run()
,11-23 18:57:53.614  3419  5940 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-23 18:57:53.625  3685  5939 I Decoder : createOrResetDecoder
,11-23 18:57:53.645  3970  3970 I HotwordWorkerImpl: onReady
,11-23 18:57:53.664  3803  3803 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-23 18:57:53.667    17    17 W kworker/2:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 18:57:53.674   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-23 18:57:53.670    17    17 W kworker/2:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 18:57:53.683   929   941 E PackageManager: Failed to write settings, restoring backup
11-23 18:57:53.683   929   941 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
11-23 18:57:53.683   929   941 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-23 18:57:53.683   929   941 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-23 18:57:53.683   929   941 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
11-23 18:57:53.683   929   941 E PackageManager: 	at java.io.OutputStreamWriter.convert(OutputStreamWriter.java:184)
11-23 18:57:53.683   929   941 E PackageManager: 	at java.io.OutputStreamWriter.write(OutputStreamWriter.java:269)
11-23 18:57:53.683   929   941 E PackageManager: 	at java.io.BufferedWriter.write(BufferedWriter.java:236)
11-23 18:57:53.683   929   941 E PackageManager: 	at org.kxml2.io.KXmlSerializer.attribute(KXmlSerializer.java:468)
11-23 18:57:53.683   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4644)
11-23 18:57:53.683   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-23 18:57:53.683   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-23 18:57:53.683   929   941 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 18:57:53.683   929   941 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 18:57:53.683   929   941 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 18:57:53.683   929   941 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
11-23 18:57:53.683   929   941 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
11-23 18:57:53.683   929   941 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
11-23 18:57:53.683   929   941 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-23 18:57:53.683   929   941 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-23 18:57:53.683   929   941 E PackageManager: 	... 12 more
,11-23 18:57:53.685  3602  3602 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-23 18:57:53.686  3602  3602 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-23 18:57:53.687  3602  3602 E AndroidRuntime: FATAL EXCEPTION: main
11-23 18:57:53.687  3602  3602 E AndroidRuntime: Process: com.google.process.gapps, PID: 3602
11-23 18:57:53.687  3602  3602 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-23 18:57:53.687  3602  3602 E AndroidRuntime: 	... 8 more
,11-23 18:57:53.687    17    17 W kworker/2:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 18:57:53.701   929  3434 I ActivityManager: Start proc 5946:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-23 18:57:53.702  3839  3935 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-23 18:57:53.702  3839  3935 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3839
11-23 18:57:53.702  3839  3935 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 18:57:53.702  3839  3935 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 18:57:53.706   929  5953 E DropBoxManagerService: Can't write: system_app_crash
11-23 18:57:53.706   929  5953 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 18:57:53.706   929  5953 E DropBoxManagerService: 	... 5 more
11-23 18:57:53.706   929  5955 E DropBoxManagerService: Can't write: system_app_crash
11-23 18:57:53.706   929  5955 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 18:57:53.706   929  5955 E DropBoxManagerService: 	... 5 more
,11-23 18:57:53.724   405   405 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[36902]" dev="sockfs" ino=36902 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 18:57:53.724   405   405 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[36902]" dev="sockfs" ino=36902 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 18:57:53.726  3419  5940 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-23 18:57:53.724   405   405 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33367]" dev="sockfs" ino=33367 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 18:57:53.729   929  5960 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 18:57:53.737   929  3827 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-23 18:57:53.739  3970  3987 W SearchService: Abort, client detached.
,11-23 18:57:53.741   929  5961 E DropBoxManagerService: Can't write: system_app_crash
11-23 18:57:53.741   929  5961 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 18:57:53.741   929  5961 E DropBoxManagerService: 	... 5 more
11-23 18:57:53.741  3970  3970 I HotwordDetector: Closing mic
11-23 18:57:53.742  3970  4237 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8cc99bd
11-23 18:57:53.742  3970  5921 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-23 18:57:53.773   929  5960 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 18:57:53.773   929  5960 I Adreno  : Build Date                       : 12/06/15
11-23 18:57:53.773   929  5960 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 18:57:53.773   929  5960 I Adreno  : Local Branch                     : mybranch17112971
11-23 18:57:53.773   929  5960 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 18:57:53.773   929  5960 I Adreno  : Remote Branch                    : NONE
11-23 18:57:53.773   929  5960 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 18:57:53.782   929  5960 I OpenGLRenderer: Initialized EGL, version 1.4
11-23 18:57:53.785   929   940 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-23 18:57:53.807   513  5923 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-23 18:57:53.808   513  5923 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-23 18:57:53.812   513  5923 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-23 18:57:53.812   513  5923 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-23 18:57:53.813   513  3011 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-23 18:57:53.815  3970  5920 I MicroRecognitionRnrImpl: Detection finished
11-23 18:57:53.816  3970  4239 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-23 18:57:53.993   598   598 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 18:57:54.088   382   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
