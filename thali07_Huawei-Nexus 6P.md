#### Test 91973007e12c4c0_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-03 13:33:29.320  4077  4271 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-03 13:33:29.407  4077  4271 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-03 13:33:29.784  5641  5641 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-03 13:33:29.791  5641  5641 D AndroidRuntime: CheckJNI is OFF
11-03 13:33:29.819  5641  5641 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-03 13:33:29.852  5641  5641 I Radio-JNI: register_android_hardware_Radio DONE
11-03 13:33:29.868  5641  5641 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-03 13:33:29.872   930  3803 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-03 13:33:29.891  5641  5641 D AndroidRuntime: Shutting down VM
11-03 13:33:29.895  3997  4010 W SearchService: Abort, client detached.
11-03 13:33:29.904  3997  4263 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6b34992
11-03 13:33:29.905  3997  4272 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-03 13:33:29.904  3997  3997 I HotwordDetector: Closing mic
11-03 13:33:29.926   930  3176 I ActivityManager: Start proc 5651:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-03 13:33:29.988   514  4275 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-03 13:33:29.989   514  4275 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-03 13:33:29.992   514  4275 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-03 13:33:29.992   514  4275 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-03 13:33:29.993   514  3046 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-03 13:33:29.996  3997  4268 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-03 13:33:29.997  3997  4270 I MicroRecognitionRnrImpl: Detection finished
11-03 13:33:30.022  5651  5651 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-03 13:33:30.042  5651  5651 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-03 13:33:30.102  5651  5651 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 558-615)
11-03 13:33:30.102  5651  5651 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 13:33:30.134  5651  5651 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c2290b4}
11-03 13:33:30.134  5651  5651 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 13:33:30.134  5651  5651 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 13:33:30.140  5651  5651 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 13:33:30.141  5651  5651 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 13:33:30.191  5651  5651 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 13:33:30.202  5651  5651 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-03 13:33:30.203  5651  5651 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 13:33:30.203  5651  5651 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 13:33:30.203  5651  5651 I Adreno  : Build Date                       : 12/06/15
11-03 13:33:30.203  5651  5651 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 13:33:30.203  5651  5651 I Adreno  : Local Branch                     : mybranch17112971
11-03 13:33:30.203  5651  5651 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 13:33:30.203  5651  5651 I Adreno  : Remote Branch                    : NONE
11-03 13:33:30.203  5651  5651 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 13:33:30.246   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4a0a228:true
,11-03 13:33:30.275   407   407 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[22384]" dev="sockfs" ino=22384 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 13:33:30.275   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22384]" dev="sockfs" ino=22384 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 13:33:30.286  5651  5651 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 13:33:30.294  5651  5651 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 13:33:30.315   505   505 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32094]" dev="sockfs" ino=32094 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 13:33:30.315   505   505 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32094]" dev="sockfs" ino=32094 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 13:33:30.319  5651  5688 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 13:33:30.323  5651  5675 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 13:33:30.319  3856  3856 W Binder_F: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14234]" dev="sockfs" ino=14234 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:33:30.319  3856  3856 W Binder_F: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14234]" dev="sockfs" ino=14234 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:33:30.349  5651  5688 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 13:33:30.425  3716  3716 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28564]" dev="sockfs" ino=28564 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:33:30.431   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +530ms
11-03 13:33:30.432  3692  3692 I Keyboard.Facilitator: onFinishInput()
,11-03 13:33:30.429  3716  3716 W Binder_8: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[28564]" dev="sockfs" ino=28564 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:33:30.429  3803  3803 W Binder_B: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[28563]" dev="sockfs" ino=28563 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 13:33:30.429  3803  3803 W Binder_B: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[28563]" dev="sockfs" ino=28563 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:33:30.459  5651  5651 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5651
,11-03 13:33:30.552  5651  5651 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 13:33:30.651   930  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 13:33:30.772  5651  5691 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -579860176
,11-03 13:33:30.776  5651  5691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-03 13:33:30.776  5651  5691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-03 13:33:30.776  5651  5691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-03 13:33:30.776  5651  5691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-03 13:33:30.776  5651  5691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-03 13:33:30.776  5651  5691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac2175b added. We now have 1 listener(s)
,11-03 13:33:30.780  5651  5691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-03 13:33:30.781  5651  5691 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 13:33:30.781  5651  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 13:33:30.781  5651  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-03 13:33:30.784  5651  5691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d47f36 added. We now have 1 listener(s)
11-03 13:33:30.784  5651  5691 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 13:33:30.789   930  3025 D WifiService: New client listening to asynchronous messages
,11-03 13:33:30.790  5651  5691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 13:33:30.790  5651  5691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-03 13:33:30.792  5651  5691 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-03 13:33:30.792  5651  5691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-03 13:33:30.792  5651  5691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-03 13:33:30.792  5651  5691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-03 13:33:30.793  5651  5691 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-03 13:33:30.795  5651  5691 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-03 13:33:30.936  5651  5651 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-03 13:33:31.198  5651  5660 I art     : Background sticky concurrent mark sweep GC freed 79146(7MB) AllocSpace objects, 16(1076KB) LOS objects, 22% free, 25MB/32MB, paused 1.695ms total 204.704ms
,11-03 13:33:31.755  5651  5699 E filemap : mmap(30035968,0) failed: Invalid argument
11-03 13:33:31.755  5651  5699 W asset   : create map from entry failed
11-03 13:33:31.755  5651  5699 W jxcore-FileManager: aproxFileSize failed
11-03 13:33:31.755  5651  5699 W System.err: java.io.FileNotFoundException: www/jxcore/node_modules/tmp/test/symlinkme/file.js
,11-03 13:33:31.761  5651  5699 W System.err: 	at android.content.res.AssetManager.openAsset(Native Method)
11-03 13:33:31.761  5651  5699 W System.err: 	at android.content.res.AssetManager.open(AssetManager.java:313)
11-03 13:33:31.761  5651  5699 W System.err: 	at io.jxcore.node.FileManager.aproxFileSize(FileManager.java:48)
11-03 13:33:31.761  5651  5699 W System.err: 	at io.jxcore.node.jxcore.Initialize(jxcore.java:281)
11-03 13:33:31.761  5651  5699 W System.err: 	at io.jxcore.node.jxcore.access$200(jxcore.java:25)
11-03 13:33:31.761  5651  5699 W System.err: 	at io.jxcore.node.jxcore$6.run(jxcore.java:343)
11-03 13:33:31.761  5651  5699 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 13:33:31.761  5651  5699 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 13:33:31.761  5651  5699 W System.err: 	at android.os.Looper.loop(Looper.java:148)
11-03 13:33:31.761  5651  5699 W System.err: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,11-03 13:33:31.792  5651  5699 W jxcore-log: Initializing JXcore engine
,11-03 13:33:31.792  5651  5699 W jxcore-log: JXcore engine is ready
,11-03 13:33:31.815  5699  5699 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12409 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-03 13:33:31.815  5699  5699 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16422]" dev="sockfs" ino=16422 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-03 13:33:31.815  5699  5699 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-03 13:33:31.815  5699  5699 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32834]" dev="sockfs" ino=32834 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-03 13:33:31.824  5651  5699 W jxcore-log: Starting JXcore engine
,11-03 13:33:31.874  5651  5699 W jxcore-log: Platform android
11-03 13:33:31.874  5651  5699 W jxcore-log: 
,11-03 13:33:31.874  5651  5699 W jxcore-log: Process ARCH arm
11-03 13:33:31.874  5651  5699 W jxcore-log: 
,11-03 13:33:32.064  5651  5699 I jxcore-log: JXcore Cordova bridge is ready!
11-03 13:33:32.064  5651  5699 I jxcore-log: 
,11-03 13:33:32.064  5651  5699 W jxcore-log: JXcore engine is started
,11-03 13:33:32.072  5651  5691 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-03 13:33:32.076  5651  5651 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-03 13:33:32.916   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:33:33.453  3637  3637 I ConfigService: onDestroy
,11-03 13:33:33.917   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:33:34.909   930  3822 I ActivityManager: Killing 5297:org.codeaurora.ims/1001 (adj 15): empty #17
,11-03 13:33:34.918   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:33:34.952   930  3822 I ActivityManager: Killing 5206:com.google.android.youtube/u0a75 (adj 15): empty #18
,11-03 13:33:35.919   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:33:36.920   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:33:37.921   593   593 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 13:33:40.001  3997  5700 W CronetSyncConnectionRcs: Upload content type not set.
,11-03 13:33:41.776  5651  5699 I jxcore-log: 2016-11-03 12:33:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-03 13:33:41.776  5651  5699 I jxcore-log: 
,11-03 13:33:41.777  5651  5699 I jxcore-log: 2016-11-03 12:33:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-03 13:33:41.777  5651  5699 I jxcore-log: 
,11-03 13:33:41.783  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-03 13:33:41.783  5651  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 13:33:41.783  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:33:41.783  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:33:41.783  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:33:41.783  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 13:33:41.783  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 13:33:41.783  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 13:33:41.783  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 13:33:41.784  5651  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 13:33:41.786  5651  5699 I jxcore-log: 2016-11-03 12:33:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-03 13:33:41.786  5651  5699 I jxcore-log: 
11-03 13:33:41.788  5651  5699 I jxcore-log: 2016-11-03 12:33:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-03 13:33:41.788  5651  5699 I jxcore-log: 
,11-03 13:33:42.038  5651  5699 I jxcore-log: 2016-11-03 12:33:42 - DEBUG UnitTest_app: 'Running unit tests'
11-03 13:33:42.038  5651  5699 I jxcore-log: 
,11-03 13:33:42.038  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 13:33:42.039  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23d27a7 added. We now have 2 listener(s)
,11-03 13:33:42.040  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 13:33:42.040  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 13:33:42.040  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 13:33:42.040  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 13:33:42.040  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@848f454 added. We now have 2 listener(s)
11-03 13:33:42.040  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 13:33:42.040  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 13:33:42.042  5651  5699 D executeNativeTests: Running unit tests
,11-03 13:33:42.081  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 13:33:42.081  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d added. We now have 3 listener(s)
,11-03 13:33:42.081  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 13:33:42.081  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 13:33:42.081  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 13:33:42.081  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:33:42.082  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 added. We now have 3 listener(s)
,11-03 13:33:42.082  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:33:42.082  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 13:33:42.084  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-03 13:33:42.084  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 13:33:42.084  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 13:33:42.084  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 13:33:42.085  5651  5699 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-03 13:33:42.085  5651  5699 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-03 13:33:42.085  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 13:33:42.085  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 13:33:42.085  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 13:33:42.085  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 13:33:42.085  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:33:42.085  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:33:42.085  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:33:42.085  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:33:42.086  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 13:33:42.086  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 13:33:42.086  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d removed from the list
11-03 13:33:42.086  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:33:42.086  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 removed from the list
11-03 13:33:42.086  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:33:42.086  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.087  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.087  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.087  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.087  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:33:42.087  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:33:42.087  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:33:42.087  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:33:42.088  5651  5699 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-03 13:33:42.088  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:33:42.088  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:33:42.088  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:33:42.088  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:33:42.088  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:33:42.088  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:33:42.088  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:33:42.088  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:33:42.088  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:33:42.088  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:42.089  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.089  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.089  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.089  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:33:42.089  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:33:42.089  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:33:42.089  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 13:33:42.091  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-03 13:33:42.092  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:33:42.092  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:33:42.092  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:33:42.092  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:33:42.092  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:33:42.092  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
,11-03 13:33:42.092  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:33:42.092  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:33:42.092  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:33:42.092  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.093  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:42.093  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.093  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.093  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:33:42.093  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:33:42.093  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:33:42.093  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:33:42.094  5651  5699 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 13:33:42.095  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 13:33:42.095  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 13:33:42.097  5651  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 13:33:42.097  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:33:42.097  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:33:42.097  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:33:42.097  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 13:33:42.097  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 13:33:42.097  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 13:33:42.097  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 13:33:42.098  5651  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 13:33:42.098  5651  5699 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 13:33:42.099  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 13:33:42.099  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 13:33:42.099  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 13:33:42.099  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 13:33:42.099  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 13:33:42.101  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 13:33:42.102  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:33:42.103  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 13:33:42.103  5651  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 13:33:42.103  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 13:33:42.106  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.106  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 13:33:42.107  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 13:33:42.108  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 13:33:42.108  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 13:33:42.112  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-03 13:33:42.114  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-03 13:33:42.114  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.114  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 13:33:42.114  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 13:33:42.114  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 13:33:42.115  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-03 13:33:42.115  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.115  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:33:42.117  4719  4951 D BtGatt.GattService: registerClient() - UUID=8b3e2008-6bf5-473e-a85b-9018c494228c
11-03 13:33:42.118  4719  4778 D BtGatt.GattService: onClientRegistered() - UUID=8b3e2008-6bf5-473e-a85b-9018c494228c, clientIf=5
,11-03 13:33:42.119  5651  5692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 13:33:42.120  4719  4730 D BtGatt.GattService: start scan with filters
,11-03 13:33:42.125  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 13:33:42.125  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.125  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 13:33:42.125  4719  4787 D BtGatt.ScanManager: handling starting scan
11-03 13:33:42.125  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.125  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 13:33:42.125  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 13:33:42.126  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-03 13:33:42.126  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 13:33:42.126  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 13:33:42.126  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:42.126  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 13:33:42.126  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:33:42.126  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-03 13:33:42.126  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.126  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 13:33:42.126  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:42.126  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:42.127  5651  5699 I io.jxcore.node.ConnectionHelper: start: OK
11-03 13:33:42.127  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:33:42.128  4719  4787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
,11-03 13:33:42.130  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 13:33:42.130  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 13:33:42.130  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 13:33:42.131  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:33:42.131  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:33:42.131  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 13:33:42.137  4719  4778 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 13:33:42.137  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:33:42.138  4719  4787 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 13:33:42.145  4719  4778 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 13:33:42.145  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:33:42.145  4719  4787 D BtGatt.ScanManager: Starting BLE batch scan
11-03 13:33:42.146  4719  4787 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 13:33:42.157  4719  4778 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-03 13:33:42.157  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:33:42.163  4719  4778 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 13:33:42.163  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:33:42.632  5651  5651 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-03 13:33:42.633  5651  5651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:33:42.633  5651  5651 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 13:33:47.131  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:33:47.131  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 13:33:47.132  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 13:33:47.132  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:33:47.132  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 13:33:47.132  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:33:47.132  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 13:33:47.132  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 13:33:47.132  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 13:33:47.132  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-03 13:33:47.133  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.133  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.133  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.134  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 13:33:47.134  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.135  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:33:47.135  4719  4949 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 13:33:47.135  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-03 13:33:47.136  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:33:47.137  4719  4787 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 13:33:47.137  4719  4951 D BtGatt.GattService: stopScan() - queue size =1
11-03 13:33:47.139  4719  4730 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 13:33:47.140  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-03 13:33:47.141  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.141  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 13:33:47.141  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.141  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:47.142  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.142  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.142  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 13:33:47.143  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.143  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:47.143  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.143  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 13:33:47.144  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 13:33:47.144  4719  4719 D BtGatt.ScanManager: awakened up at time 97657
,11-03 13:33:47.151  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 13:33:47.151  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.155  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.155  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:33:47.155  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.155  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:47.156  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:33:47.156  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:33:47.156  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:33:47.156  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 13:33:47.156  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 13:33:47.156  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:33:47.156  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 13:33:47.156  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:33:47.156  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 13:33:47.156  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:33:47.156  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 13:33:47.156  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:33:47.157  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:33:47.157  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 13:33:47.157  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 13:33:47.157  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:33:47.157  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 13:33:47.157  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 13:33:47.157  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 13:33:47.190  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 13:33:47.190  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 13:33:47.190  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:33:47.190  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:33:47.190  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 13:33:47.197  4719  4778 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 13:33:47.197  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:47.197  4719  4778 D BtGatt.GattService: current time is 97711377594
11-03 13:33:47.198  4719  4778 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -86, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -99, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
11-03 13:33:47.199  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 13:33:47.200  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-03 13:33:47.200  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 13:33:47.200  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
11-03 13:33:47.200  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
11-03 13:33:47.200  4719  4778 E BtGatt.ContextMap: Context not found for ID 5
,11-03 13:33:47.207  4719  4778 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 13:33:47.207  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:47.207  4719  4787 D BtGatt.ScanManager: stopping BLe Batch
,11-03 13:33:47.214  4719  4778 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 13:33:47.214  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:47.214  4719  4787 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 13:33:47.219  4719  4778 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 13:33:47.219  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:33:47.269  4930  4976 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-03 13:33:47.270  4930  4930 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-03 13:33:47.692  5651  5651 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 13:33:52.190  5651  5699 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-03 13:33:52.195  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 13:33:52.196  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 13:33:52.210  5651  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 13:33:52.210  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:33:52.210  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:33:52.210  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:33:52.210  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 13:33:52.210  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 13:33:52.210  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 13:33:52.210  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 13:33:52.215  5651  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 13:33:52.215  5651  5699 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 13:33:52.215  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:33:52.215  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 13:33:52.215  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 13:33:52.215  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 13:33:52.215  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 13:33:52.219  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 13:33:52.222  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 13:33:52.222  5651  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 13:33:52.222  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 13:33:52.223  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:33:52.226  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:52.226  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 13:33:52.227  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 13:33:52.227  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 13:33:52.227  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 13:33:52.230  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.230  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 13:33:52.230  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-03 13:33:52.230  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-03 13:33:52.230  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 13:33:52.231  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.231  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:33:52.234  4719  4949 D BtGatt.GattService: registerClient() - UUID=923b31d9-55d1-40cb-8149-241596a89854
11-03 13:33:52.234  4719  4778 D BtGatt.GattService: onClientRegistered() - UUID=923b31d9-55d1-40cb-8149-241596a89854, clientIf=5
11-03 13:33:52.234  5651  5692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 13:33:52.234  4719  4732 D BtGatt.GattService: start scan with filters
11-03 13:33:52.237  4719  4787 D BtGatt.ScanManager: handling starting scan
11-03 13:33:52.237  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 13:33:52.238  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.238  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 13:33:52.238  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.238  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 13:33:52.238  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 13:33:52.238  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.238  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 13:33:52.238  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 13:33:52.238  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.238  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.238  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-03 13:33:52.239  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 13:33:52.239  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.242  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.242  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 13:33:52.242  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.242  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.242  5651  5699 I io.jxcore.node.ConnectionHelper: start: OK
11-03 13:33:52.242  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.244  4719  4778 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 13:33:52.244  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.245  4719  4787 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 13:33:52.245  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:33:52.245  5651  5699 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 13:33:52.245  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 13:33:52.245  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 13:33:52.245  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:33:52.245  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 13:33:52.245  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:33:52.245  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-03 13:33:52.247  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 13:33:52.247  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.247  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.247  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.247  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 13:33:52.247  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 13:33:52.247  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 13:33:52.247  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 13:33:52.247  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:52.247  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.248  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.248  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 13:33:52.248  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:52.248  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:33:52.249  4719  4950 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-03 13:33:52.249  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 13:33:52.250  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:33:52.250  4719  4732 D BtGatt.GattService: stopScan() - queue size =1
11-03 13:33:52.251  4719  4778 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 13:33:52.251  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.251  4719  4730 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 13:33:52.251  4719  4787 D BtGatt.ScanManager: Starting BLE batch scan
11-03 13:33:52.251  4719  4787 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 13:33:52.251  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 13:33:52.251  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.251  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 13:33:52.251  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.252  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.252  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:52.252  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.252  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 13:33:52.252  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.252  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.252  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.252  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 13:33:52.252  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 13:33:52.253  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 13:33:52.253  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.255  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.255  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:33:52.255  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.255  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.255  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:33:52.255  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:33:52.255  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:33:52.256  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 13:33:52.256  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:33:52.256  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:33:52.256  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:33:52.256  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:33:52.256  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:33:52.256  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 13:33:52.256  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:33:52.256  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 13:33:52.256  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.256  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.b,luetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 13:33:52.256  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 13:33:52.256  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.256  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.256  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 13:33:52.256  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.257  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.258  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.258  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.258  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.258  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.258  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:33:52.259  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.259  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.259  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.259  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:33:52.259  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:33:52.259  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:33:52.259  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:33:52.260  5651  5699 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 13:33:52.262  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 13:33:52.262  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 13:33:52.264  4719  4778 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 13:33:52.264  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.270  4719  4778 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 13:33:52.270  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.271  4719  4787 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 13:33:52.271  5651  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 13:33:52.271  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:33:52.271  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:33:52.271  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:33:52.271  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 13:33:52.271  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 13:33:52.271  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 13:33:52.271  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 13:33:52.274  5651  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 13:33:52.274  5651  5699 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 13:33:52.274  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:33:52.274  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 13:33:52.274  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 13:33:52.274  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 13:33:52.274  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 13:33:52.277  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:33:52.277  4719  4778 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 13:33:52.277  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.277  4719  4778 E BtGatt.ContextMap: Context not found for ID 5
11-03 13:33:52.277  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 13:33:52.277  5651  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 13:33:52.277  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 13:33:52.280  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:33:52.280  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.280  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 13:33:52.281  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 13:33:52.281  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 13:33:52.281  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 13:33:52.284  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.284  4719  4778 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 13:33:52.284  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 13:33:52.284  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.284  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 13:33:52.284  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 13:33:52.284  4719  4787 D BtGatt.ScanManager: stopping BLe Batch
11-03 13:33:52.284  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 13:33:52.284  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.285  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:33:52.286  4719  4732 D BtGatt.GattService: registerClient() - UUID=aada129f-e37c-41e0-b78b-74489972eab8
11-03 13:33:52.287  4719  4778 D BtGatt.GattService: onClientRegistered() - UUID=aada129f-e37c-41e0-b78b-74489972eab8, clientIf=5
11-03 13:33:52.287  5651  5661 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 13:33:52.287  4719  4951 D BtGatt.GattService: start scan with filters
11-03 13:33:52.289  4719  4778 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 13:33:52.289  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.289  4719  4787 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 13:33:52.290  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 13:33:52.291  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.291  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 13:33:52.291  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.291  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 13:33:52.291  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 13:33:52.291  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.291  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 13:33:52.291  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 13:33:52.291  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.291  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.291  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 13:33:52.293  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 13:33:52.293  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.294  4719  4778 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 13:33:52.294  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.295  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.296  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 13:33:52.296  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.296  4719  4787 D BtGatt.ScanManager: handling starting scan
11-03 13:33:52.296  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:52.296  5651  5699 I io.jxcore.node.ConnectionHelper: start: OK
11-03 13:33:52.296  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.298  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.298  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.298  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.298  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:33:52.298  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 13:33:52.301  4719  4778 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 13:33:52.301  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.302  4719  4787 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 13:33:52.306  4719  4778 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 13:33:52.306  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.306  4719  4787 D BtGatt.ScanManager: Starting BLE batch scan
11-03 13:33:52.306  4719  4787 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 13:33:52.315  4719  4778 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 13:33:52.315  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:52.320  4719  4778 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 13:33:52.320  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:33:52.800  5651  5651 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-03 13:33:52.800  5651  5651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:33:52.800  5651  5651 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 13:33:53.865   930  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 13:33:53.870   930  3026 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-03 13:33:56.894   930  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 13:33:56.900   930  3026 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-03 13:33:57.296  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:33:57.297  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 13:33:57.297  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 13:33:57.297  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:33:57.297  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 13:33:57.298  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 13:33:57.298  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 13:33:57.298  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 13:33:57.298  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 13:33:57.298  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 13:33:57.298  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.299  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.299  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.299  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 13:33:57.299  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.301  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:33:57.302  4719  4951 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-03 13:33:57.303  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 13:33:57.305  4719  4787 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 13:33:57.307  5651  5699 D BluetoothAdapter: STATE_ON
,11-03 13:33:57.308  4719  4730 D BtGatt.GattService: stopScan() - queue size =1
,11-03 13:33:57.310  4719  4950 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 13:33:57.311  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 13:33:57.312  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.312  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 13:33:57.312  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.312  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.312  4719  4719 D BtGatt.ScanManager: awakened up at time 107826
11-03 13:33:57.312  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:57.312  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.313  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 13:33:57.313  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:57.313  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.313  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.314  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 13:33:57.314  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 13:33:57.318   930  3470 I ActivityManager: Killing 5314:com.android.settings/1000 (adj 15): empty #17
,11-03 13:33:57.343  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 13:33:57.343  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.345  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:33:57.345  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:33:57.345  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.345  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:33:57.345  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 13:33:57.345  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:33:57.345  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 13:33:57.346  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 13:33:57.346  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 13:33:57.346  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-03 13:33:57.346  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:33:57.346  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 13:33:57.346  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,11-03 13:33:57.346  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:33:57.348  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 13:33:57.348  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 13:33:57.348  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:33:57.348  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:33:57.348  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 13:33:57.360  4719  4778 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-03 13:33:57.361  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:57.361  4719  4778 D BtGatt.GattService: current time is 107874685834
11-03 13:33:57.361  4719  4778 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -76, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -82, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -96, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 13:33:57.361  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 13:33:57.362  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 13:33:57.362  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 13:33:57.362  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 13:33:57.362  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 13:33:57.362  4719  4778 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 13:33:57.369  4719  4778 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 13:33:57.369  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:57.370  4719  4787 D BtGatt.ScanManager: stopping BLe Batch
,11-03 13:33:57.376  4719  4778 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 13:33:57.377  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:33:57.377  4719  4787 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 13:33:57.383  4719  4778 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 13:33:57.383  4719  4778 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:33:57.849  5651  5651 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 13:33:57.850  5651  5651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:33:57.850  5651  5651 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 13:33:59.778   930  5423 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 13:34:02.347  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:02.347  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 13:34:02.347  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:02.348  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:02.348  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:34:02.348  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 13:34:02.348  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.348  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:02.348  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.349  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.349  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 13:34:02.349  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 13:34:02.352  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:02.356  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.357  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:02.357  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:02.357  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:02.357  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:02.357  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.357  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:02.359  5651  5699 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-03 13:34:02.360  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:34:02.361  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:02.361  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:02.361  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:02.361  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.361  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:02.362  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:02.362  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.362  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:02.362  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.365  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.365  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.365  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.365  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 13:34:02.366  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:02.366  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.366  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:02.368  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 13:34:02.368  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:34:02.368  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:02.368  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:02.368  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:02.368  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.368  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:02.368  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.369  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:02.369  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:02.369  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.370  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.370  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.370  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.370  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:02.371  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 13:34:02.371  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.371  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.372  5651  5699 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-03 13:34:02.372  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:02.372  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:02.372  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 13:34:02.373  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:02.373  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.373  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:02.373  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:02.373  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.373  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:02.374  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:02.376  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.376  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:02.376  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.376  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:02.376  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:02.376  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.376  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:02.377  5651  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-03 13:34:02.377  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:02.377  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:02.377  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:02.378  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:02.378  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.378  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:02.378  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.378  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:02.378  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:02.378  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:02.380  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:02.380  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.380  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.381  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:02.381  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:02.381  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.381  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.381  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-03 13:34:02.382  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 13:34:02.382  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 13:34:02.382  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 13:34:02.382  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 13:34:02.382  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 13:34:02.382  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 13:34:02.382  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 13:34:02.382  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 13:34:02.382  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:02.382  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:02.382  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:02.383  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:02.383  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.383  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:02.383  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.383  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:02.383  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:02.383  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.389  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.389  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.389  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.389  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:02.389  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:02.389  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.389  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.391  5651  5699 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-03 13:34:02.391  5651  5699 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 13:34:02.391  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-03 13:34:02.395  5651  5699 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 13:34:02.395  5651  5699 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-03 13:34:02.396  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-03 13:34:02.396  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 13:34:02.396  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 13:34:02.396  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 13:34:02.397  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 13:34:02.398  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 13:34:02.398  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 13:34:02.398  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 13:34:02.398  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-03 13:34:02.398  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 13:34:02.398  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 13:34:02.399  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 13:34:02.399  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 13:34:02.399  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-03 13:34:02.399  5651  5699 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-03 13:34:02.399  5651  5699 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 13:34:02.399  5651  5699 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-03 13:34:02.399  5651  5699 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-03 13:34:02.399  5651  5699 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 13:34:02.400  5651  5699 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-03 13:34:02.400  5651  5699 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 13:34:02.400  5651  5699 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 13:34:02.400  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-03 13:34:02.405  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-03 13:34:02.407  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-03 13:34:02.407  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-03 13:34:02.407  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-03 13:34:02.408  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-03 13:34:02.408  5651  5699 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-03 13:34:02.408  5651  5699 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 13:34:02.408  5651  5699 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-03 13:34:02.408  5651  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
,11-03 13:34:02.408  5651  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-03 13:34:02.408  5651  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-03 13:34:02.408  5651  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-03 13:34:02.409  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:02.409  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 13:34:02.409  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:02.409  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:02.409  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.409  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-03 13:34:02.410  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
,11-03 13:34:02.410  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.410  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.410  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:02.411  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.411  5651  5704 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-03 13:34:02.411  5651  5704 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 13:34:02.409  4949  4949 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29608]" dev="sockfs" ino=29608 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 13:34:02.412  4949  4949 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29608]" dev="sockfs" ino=29608 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 13:34:02.412  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.412  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.412  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.412  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:02.412  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:02.412  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.412  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:02.413  5651  5699 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-03 13:34:02.414  5651  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-03 13:34:02.414  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:02.414  5651  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-03 13:34:02.414  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:02.414  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:02.414  5651  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
11-03 13:34:02.414  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 13:34:02.414  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.414  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:02.414  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.414  5651  5704 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-03 13:34:02.414  5651  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
11-03 13:34:02.414  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.414  5651  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-03 13:34:02.414  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:02.414  5651  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
,11-03 13:34:02.415  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.415  4719  4928 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
,11-03 13:34:02.419  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.419  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.419  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:02.420  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:02.420  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:02.420  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.420  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.420  5651  5699 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-03 13:34:02.421  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:02.421  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:02.421  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 13:34:02.421  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:02.421  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.421  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:02.421  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.421  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.421  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:02.421  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.423  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.423  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:02.423  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.423  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:02.423  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 13:34:02.423  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.423  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.424  5651  5699 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-03 13:34:02.424  5651  5699 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-03 13:34:02.424  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 13:34:02.424  5651  5699 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-03 13:34:02.424  5651  5699 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 13:34:02.424  5651  5699 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-03 13:34:02.425  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 13:34:02.425  5651  5699 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,11-03 13:34:02.425  5651  5699 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 13:34:02.425  5651  5699 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 13:34:02.425  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 13:34:02.425  5651  5699 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-03 13:34:02.425  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:02.425  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:02.426  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:02.426  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:02.426  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.426  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:02.426  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:02.427  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.427  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:02.427  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.428  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.428  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:02.428  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:02.428  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:02.428  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:02.428  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.428  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.429  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:02.429  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:02.429  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:02.429  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:02.429  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:02.429  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 13:34:02.921   593   593 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-03 13:34:02.922   593   593 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 13:34:07.430  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:07.430  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:07.430  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:07.431  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:07.431  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:07.431  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:07.431  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 13:34:07.431  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:07.432  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:07.432  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:07.432  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:07.432  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:07.432  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:07.433  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:07.433  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:07.436  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:07.436  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:07.437  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.437  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 13:34:07.437  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:07.437  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:07.437  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:07.440  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-03 13:34:07.441  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 13:34:07.441  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 13:34:07.446  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-03 13:34:07.448  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-03 13:34:07.448  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 13:34:07.449  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 13:34:07.449  5651  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 13:34:07.450  5651  5651 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-03 13:34:07.449  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-03 13:34:07.450  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 13:34:07.451  5651  5706 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 13:34:07.451  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:07.451  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-03 13:34:07.451  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 13:34:07.451  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-03 13:34:07.451  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 13:34:07.452  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-03 13:34:07.452  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 13:34:07.453  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
,11-03 13:34:07.453  5651  5651 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 13:34:07.453  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:07.453  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 13:34:07.453  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-03 13:34:07.453  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 13:34:07.453  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:07.452  4950  4950 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33025]" dev="sockfs" ino=33025 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 13:34:07.452  4950  4950 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33025]" dev="sockfs" ino=33025 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 13:34:07.455  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:07.455  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:34:07.456  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.456  5651  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 13:34:07.456  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.456  5651  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 13:34:07.456  5651  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-03 13:34:07.456  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:07.456  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:34:07.456  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:34:07.456  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:34:07.456  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:07.456  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:34:07.456  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:07.457  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:07.457  5651  5651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-03 13:34:07.457  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:07.457  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:07.457  5651  5651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:07.457  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:07.457  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:07.457  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:07.457  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.459  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.460  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.460  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.460  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:07.460  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:07.460  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:07.460  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:07.462  5651  5699 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-03 13:34:07.462  5651  5699 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 13:34:07.462  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-03 13:34:07.463  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 13:34:07.463  5651  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 13:34:07.463  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:07.463  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:07.463  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:07.463  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:07.464  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:07.464  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:07.464  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:07.464  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:07.466  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 13:34:07.467  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.471  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.471  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:07.471  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.472  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:07.472  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:07.472  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:07.472  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:07.479  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:34:07.479  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:07.479  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:07.479  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:07.479  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:07.479  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:07.479  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:07.479  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:07.479  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:07.479  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.481  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:07.481  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.481  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.481  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:07.481  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 13:34:07.481  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:07.481  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:07.483  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:34:07.483  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:07.483  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:07.483  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:07.483  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 13:34:07.484  5651  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f43b26d not in the list
11-03 13:34:07.484  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:07.484  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
11-03 13:34:07.484  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 13:34:07.484  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.485  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.486  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:07.486  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:07.486  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:07.486  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:07.486  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:07.486  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e5ea2 not in the list
,11-03 13:34:07.487  5651  5699 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-03 13:34:07.487  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 13:34:07.487  5651  5699 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-03 13:34:07.487  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 13:34:07.488  5651  5699 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-03 13:34:07.488  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-03 13:34:07.490  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-03 13:34:07.490  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-03 13:34:07.491  5651  5699 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-03 13:34:07.491  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 13:34:07.491  5651  5699 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-03 13:34:07.491  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 13:34:07.491  5651  5699 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-03 13:34:07.491  5651  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-03 13:34:07.492  5651  5699 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-03 13:34:07.492  5651  5699 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-03 13:34:07.492  5651  5699 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-03 13:34:07.492  5651  5699 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-03 13:34:07.493  5651  5699 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-03 13:34:07.493  5651  5699 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-03 13:34:07.494  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:07.494  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5cf323 added. We now have 3 listener(s)
11-03 13:34:07.494  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:07.496  5651  5699 D BluetoothAdapter: enable(): BT is already enabled..!
11-03 13:34:07.496   930  3779 D WifiService: setWifiEnabled: true pid=5651, uid=10077
,11-03 13:34:07.496   930  3779 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 13:34:07.540  4719  4925 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-03 13:34:07.540  4719  4925 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-03 13:34:07.923   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:07.957  5651  5651 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 13:34:08.924   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:09.925   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:10.657   930  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 13:34:10.925   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:11.927   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:12.502  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 13:34:12.502  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cba6020 added. We now have 4 listener(s)
,11-03 13:34:12.503  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 13:34:12.515  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:12.516  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cba6020 removed from the list
11-03 13:34:12.516  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 13:34:12.517  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:12.518  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d64ddd9 added. We now have 4 listener(s)
,11-03 13:34:12.518  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 13:34:12.521  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:12.522  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d64ddd9 removed from the list
11-03 13:34:12.522  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:12.523  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:12.523  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e60c39e added. We now have 4 listener(s)
,11-03 13:34:12.523  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 13:34:12.526   930  3849 D WifiService: setWifiEnabled: false pid=5651, uid=10077
11-03 13:34:12.526   930  3849 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 13:34:12.530   930  3017 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 13:34:12.530   930  3017 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 13:34:12.530   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 13:34:12.530   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 13:34:12.534  4719  4774 D BluetoothAdapterState: Current state: ON, message: 23
11-03 13:34:12.535  4719  4774 D BluetoothAdapterProperties: Setting state to 13
,11-03 13:34:12.535  4719  4774 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-03 13:34:12.537  4719  4774 D BluetoothAdapterProperties: onBluetoothDisable()
11-03 13:34:12.537  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 13:34:12.538  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 13:34:12.539  4719  4774 I BluetoothAdapterState: Entering PendingCommandState
11-03 13:34:12.540  4719  4719 D BluetoothMapService: onReceive
11-03 13:34:12.541  4719  4719 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 13:34:12.542  4719  4719 D BluetoothMapService: STATE_TURNING_OFF
11-03 13:34:12.542  4719  4719 D BluetoothMapService: MAP Service closeService in
11-03 13:34:12.542  4719  4719 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 13:34:12.543  4719  4719 D ObexServerSockets0: shutdown(block = true)
,11-03 13:34:12.544  4719  4719 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 13:34:12.544  4719  4719 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 13:34:12.544  4719  4928 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 13:34:12.544  4719  4953 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-03 13:34:12.545  4719  4954 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 13:34:12.547  4719  4719 I BtOppRfcommListener: stopping Accept Thread
11-03 13:34:12.547  4719  5356 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 13:34:12.550   930  5424 D DhcpClient: Clearing IP address
11-03 13:34:12.550   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-03 13:34:12.553  4719  5356 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-03 13:34:12.558   509   923 D CommandListener: Setting iface cfg
,11-03 13:34:12.558   930   943 I ActivityManager: Start proc 5710:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-03 13:34:12.561  3637  5480 V NativeCrypto: Read error: ssl=0x7f6b686000: I/O error during system call, Connection timed out
,11-03 13:34:12.563  3637  5480 V NativeCrypto: SSL shutdown failed: ssl=0x7f6b686000: I/O error during system call, Broken pipe
11-03 13:34:12.563  4719  4778 D BluetoothAdapterProperties: Scan Mode:20
11-03 13:34:12.566  4719  4774 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-03 13:34:12.566   930  3849 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-03 13:34:12.567   930  5422 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-03 13:34:12.570  4719  4719 D HeadsetService: Received stop request...Stopping profile...
11-03 13:34:12.570   930  5422 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-03 13:34:12.571  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:12.571  5651  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 13:34:12.571  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:12.571  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:12.571  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:34:12.571  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 13:34:12.571  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 13:34:12.571  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 13:34:12.571  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 13:34:12.571   930  5425 D DhcpClient: Receive thread stopped
11-03 13:34:12.571   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-03 13:34:12.571   930  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-03 13:34:12.572  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:12.572  5651  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 13:34:12.572   930  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-03 13:34:12.572  5651  5699 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 13:34:12.575   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 13:34:12.575  3799  4030 D BluetoothHeadset: Proxy object disconnected
,11-03 13:34:12.575   930   930 D BluetoothHeadset: Proxy object disconnected
,11-03 13:34:12.576  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:34:12.577  4719  4719 D A2dpService: Received stop request...Stopping profile...
11-03 13:34:12.577  3193  3205 D BluetoothHeadset: Proxy object disconnected
11-03 13:34:12.577  4719  4944 D A2dpStateMachine: Exit Disconnected: -1
11-03 13:34:12.578   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-03 13:34:12.578   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-03 13:34:12.580  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 13:34:12.580  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:12.580  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:12.580  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:12.580  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:34:12.580  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 13:34:12.580  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 13:34:12.580  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 13:34:12.580  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 13:34:12.581   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 13:34:12.581   591   591 E Parcel  : Reading a NULL string not supported here.
11-03 13:34:12.581   930   930 D BluetoothA2dp: Proxy object disconnected
11-03 13:34:12.581  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:12.582  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 13:34:12.583   930   930 D RttService: SCAN_AVAILABLE : 1
11-03 13:34:12.583   930  3129 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 13:34:12.584  4719  4719 D HidService: Received stop request...Stopping profile...
11-03 13:34:12.584  4719  4719 D HidService: Stopping Bluetooth HidService
11-03 13:34:12.585  4719  4719 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:12.586  4719  4719 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:12.586  4719  4719 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:12.586  4719  4719 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:12.586   930  3026 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-03 13:34:12.586  4719  4719 D HealthService: Received stop request...Stopping profile...
,11-03 13:34:12.587  3769  3918 W QCNEJ   : |CORE| network lost: 100
11-03 13:34:12.588  3769  3918 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-03 13:34:12.589  3193  3193 D HeadsetProfile: Bluetooth service disconnected
11-03 13:34:12.589  4719  4719 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 13:34:12.589  4719  4719 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 13:34:12.589  4719  4778 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 13:34:12.589  4719  4925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 13:34:12.590  4719  4925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 13:34:12.590  4719  4925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 13:34:12.590  3193  3193 D BluetoothA2dp: Proxy object disconnected
11-03 13:34:12.590  4719  4778 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 13:34:12.591  4719  4719 D PanService: Received stop request...Stopping profile...
11-03 13:34:12.591  4719  4719 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:12.591  4719  4719 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:12.591  4719  4719 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 13:34:12.592  4719  4719 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:12.592  3193  3193 D BluetoothInputDevice: Proxy object disconnected
11-03 13:34:12.592  3193  3193 D HidProfile: Bluetooth service disconnected
11-03 13:34:12.593  4719  4925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 13:34:12.593  4719  4778 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 13:34:12.593  4719  4925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 13:34:12.593  4719  4925 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 13:34:12.593  4719  4925 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 13:34:12.593  4719  4925 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 13:34:12.593  4719  4925 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-03 13:34:12.594  4719  4719 D BluetoothMapService: Received stop request...Stopping profile...
11-03 13:34:12.594  4719  4719 D BluetoothMapService: stop()
11-03 13:34:12.594  4719  4719 D BluetoothMapAppObserver: deinitObservers()
11-03 13:34:12.595  4719  4719 D BluetoothMapAppObserver: removeReceiver()
,11-03 13:34:12.596   930  3017 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 13:34:12.600  4719  4719 D SapService: Received stop request...Stopping profile...
11-03 13:34:12.600  4719  4719 V SapService: stop()
,11-03 13:34:12.602  3193  3193 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-03 13:34:12.602  3193  3193 D PanProfile: Bluetooth service disconnected
11-03 13:34:12.602  3193  3193 D BluetoothMap: Proxy object disconnected
11-03 13:34:12.602  3193  3193 D MapProfile: Bluetooth service disconnected
11-03 13:34:12.603  4719  4719 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:12.604  4719  4719 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:12.604  4719  4719 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:12.604  4719  4719 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 13:34:12.604  4719  4719 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 13:34:12.604  4719  4719 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 13:34:12.604  4719  4719 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:12.604  4719  4719 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:12.604  4719  4719 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:12.604  4719  4719 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 13:34:12.604  4719  4778 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 13:34:12.604  4719  4719 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-03 13:34:12.604  4719  4778 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 13:34:12.604  4719  4719 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 13:34:12.605  4719  4719 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:12.605  4719  4719 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:12.605  4719  4719 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:12.605  4719  4719 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 13:34:12.605  4719  4719 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 13:34:12.605  4719  4719 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 13:34:12.606  4719  4719 D BluetoothMapService: MAP Service closeService in
11-03 13:34:12.606  4719  4719 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:12.606  4719  4719 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:12.606  4719  4719 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:12.606  4719  4719 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 13:34:12.606  4719  4719 D BluetoothMapService: cleanup()
11-03 13:34:12.606  4719  4719 D BluetoothMapService: MAP Service closeService in
11-03 13:34:12.607  4719  4719 V BluetoothAdapterState: isTurningOff()=true
,11-03 13:34:12.607  4719  4719 V BluetoothAdapterState: isTurningOn()=false
,11-03 13:34:12.607  4719  4719 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:12.607  4719  4719 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:12.607  4719  4774 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 13:34:12.607  4719  4774 D BluetoothAdapterProperties: Setting state to 15
11-03 13:34:12.607  4719  4774 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 13:34:12.607  4719  4774 I BluetoothAdapterState: Entering BleOnState
,11-03 13:34:12.608  3799  3828 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 13:34:12.608  3193  3205 D BluetoothPan: onBluetoothStateChange on: false
11-03 13:34:12.610   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 13:34:12.610  3193  4022 D BluetoothMap: onBluetoothStateChange: up=false
11-03 13:34:12.611  3193  3204 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-03 13:34:12.611  3193  5650 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 13:34:12.611   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-03 13:34:12.612  3193  3205 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 13:34:12.616   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 13:34:12.616   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 13:34:12.617  3193  3204 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 13:34:12.617   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-03 13:34:12.618  4719  4774 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 13:34:12.618  4719  4774 D BluetoothAdapterProperties: Setting state to 16
11-03 13:34:12.618  4719  4774 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 13:34:12.618  4719  4774 D BluetoothAdapterProperties: onBleDisable
11-03 13:34:12.618  4719  4774 I BluetoothAdapterState: Entering PendingCommandState
11-03 13:34:12.618  4719  4775 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-03 13:34:12.619  4719  4778 D BluetoothAdapterProperties: Scan Mode:20
11-03 13:34:12.621   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 13:34:12.622  4719  4925 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 13:34:12.622  4719  4925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 13:34:12.626  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:12.626  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:12.626  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:12.626  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:12.626  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:34:12.626  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 13:34:12.626  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 13:34:12.626  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 13:34:12.626  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 13:34:12.628  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 13:34:12.632  5710  5710 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-03 13:34:12.636   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 13:34:12.636   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-03 13:34:12.637   930  3026 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-03 13:34:12.637   930  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 13:34:12.638   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-03 13:34:12.641  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:34:12.642  5328  5328 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@344788f and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-03 13:34:12.643  3997  3997 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-03 13:34:12.655  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 13:34:12.660   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d238f39:true
,11-03 13:34:12.661  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 13:34:12.679  5710  5710 D LocalBluetoothProfileManager: Adding local MAP profile
,11-03 13:34:12.680   509   923 E Netd    : netlink response contains error (No such file or directory)
,11-03 13:34:12.681   930  3026 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 13:34:12.682  5710  5710 D BluetoothMap: Create BluetoothMap proxy object
11-03 13:34:12.682   930  3017 D DhcpClient: doQuit
11-03 13:34:12.682   930  3017 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 13:34:12.682   509   923 D TetherController: Setting IP forward enable = 0
11-03 13:34:12.682   930  5424 D DhcpClient: onQuitting
11-03 13:34:12.683  3490  3490 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-03 13:34:12.688  5710  5710 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-03 13:34:12.688  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:12.688  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:12.688  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:12.688  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:12.688  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 13:34:12.688  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 13:34:12.688  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 13:34:12.688  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 13:34:12.688  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 13:34:12.689  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:12.689  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 13:34:12.695  5710  5710 D DockEventReceiver: finishStartingService: stopping service
,11-03 13:34:12.698  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 13:34:12.702  5710  5710 D DockEventReceiver: finishStartingService: stopping service
11-03 13:34:12.702  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 13:34:12.704   930  3856 I ActivityManager: Killing 5451:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-03 13:34:12.709  3490  3490 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 13:34:12.714  3490  3490 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 13:34:12.721   509   923 D TetherController: Setting IP forward enable = 0
,11-03 13:34:12.741  4077  4077 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 13:34:12.744  4077  4077 D SystemUpdateService: onCreate
11-03 13:34:12.745  3490  3490 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-03 13:34:12.747  4077  4077 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-03 13:34:12.753  4077  4077 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 13:34:12.757  4077  4296 I iu.UploadsManager: num queued entries: 0
,11-03 13:34:12.757  4077  4296 I iu.UploadsManager: num updated entries: 0
11-03 13:34:12.758  4077  4296 I iu.SyncManager: NEXT; no task
,11-03 13:34:12.759  4077  5746 I SystemUpdateService: active receiver: enabled
,11-03 13:34:12.762  4077  4077 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 13:34:12.763  3490  3490 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-03 13:34:12.764  4077  4077 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 13:34:12.767  4077  5746 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 13:34:12.769  4077  5746 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-03 13:34:12.769  4077  5746 I SystemUpdateService: now status is 0 (complete)
11-03 13:34:12.769  4077  5746 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 13:34:12.769  4077  5746 I SystemUpdateService: file has been verified
11-03 13:34:12.769  4077  5746 I SystemUpdateService: OTA package size = 21989297
,11-03 13:34:12.774  4077  5746 I SystemUpdateService: showing system update notification
,11-03 13:34:12.776   930  3469 I ActivityManager: Start proc 5748:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-03 13:34:12.787   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 13:34:12.788  4077  4077 D SystemUpdateService: onDestroy
,11-03 13:34:12.812  5748  5748 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-03 13:34:12.815  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 13:34:12.822  5748  5748 D SprintDMHelper: simOperator: 
,11-03 13:34:12.822  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 13:34:12.828  4719  4778 I bt_hci  : shut_down
,11-03 13:34:12.832  4719  4791 D bt_hwcfg: hw_epilog_process
,11-03 13:34:12.832  4719  4791 I bt_vendor: low_power_mode_cb
,11-03 13:34:12.836  4719  4791 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-03 13:34:12.836  4719  4791 I bt_vendor: epilog_cb
11-03 13:34:12.836  4719  4791 I bt_hci  : epilog_finished_callback
,11-03 13:34:12.851   930  3716 I ActivityManager: Start proc 5761:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-03 13:34:12.852  4719  4778 I bt_hci_h4: hal_close
,11-03 13:34:12.852   930  3716 I ActivityManager: Killing 5328:com.google.android.music:main/u0a59 (adj 15): empty #17
11-03 13:34:12.852  4719  4778 I bt_userial_vendor: device fd = 54 close
,11-03 13:34:12.875   930  3017 D wifi    : In wifi stop Hal
,11-03 13:34:12.876   930  3017 D wifi    : halHandle = 0x7f59b21b80, mVM = 0x7f7618d140, mCls = 0x1009fa
,11-03 13:34:12.876   930  3489 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 13:34:12.876  4565  4565 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 13:34:12.876   930  3489 D WifiHAL : Got a signal to exit!!!
11-03 13:34:12.876   930  3489 I WifiHAL : Exit wifi_event_loop
11-03 13:34:12.877   930  3017 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-03 13:34:12.877   930  3017 E WifiHAL : Event processing terminated
11-03 13:34:12.877   930  3017 D wifi    : In wifi cleaned up handler
11-03 13:34:12.877   930  3017 I WifiHAL : Internal cleanup completed
11-03 13:34:12.878  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:34:12.878  3879  4226 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 13:34:12.893  5761  5761 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-03 13:34:12.898   930  3489 D wifi    : set interface wlan0 flags (DOWN)
,11-03 13:34:12.898   930  3017 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 13:34:12.901   930  3779 I ActivityManager: Killing 3938:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-03 13:34:12.927   593   593 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 13:34:12.962  4719  4775 D bt_stack_manager: event_shut_down_stack finished.
,11-03 13:34:12.962  4719  4774 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 13:34:12.963  4719  4774 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-03 13:34:12.963  4719  4719 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 13:34:12.964  4719  4719 D BtGatt.GattService: Received stop request...Stopping profile...
,11-03 13:34:12.964  4719  4719 D BtGatt.GattService: stop()
11-03 13:34:12.964  4719  4719 D BtGatt.AdvertiseManager: advertise clients cleared
11-03 13:34:12.965  4719  4719 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:12.965  4719  4719 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:12.965  4719  4719 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:12.965  4719  4719 V BluetoothAdapterState: isBleTurningOff()=true
11-03 13:34:12.965  4719  4774 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-03 13:34:12.965  4719  4774 D BluetoothAdapterProperties: Setting state to 10
11-03 13:34:12.965  4719  4774 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-03 13:34:12.966  4719  4774 I BluetoothAdapterState: Entering OffState
,11-03 13:34:12.967   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 13:34:12.972  4719  4719 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 13:34:12.972  4719  4719 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 13:34:12.973  4719  4719 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-03 13:34:12.974  4719  4775 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 13:34:12.977  4719  4719 I art     : System.exit called, status: 0
,11-03 13:34:12.977  4719  4719 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 13:34:12.998   930  3690 I ActivityManager: Process com.android.bluetooth (pid 4719) has died
,11-03 13:34:13.101   930   947 D Tethering: InitialState.processMessage what=4
,11-03 13:34:13.104   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 13:34:17.575   930  3470 D WifiService: setWifiEnabled: true pid=5651, uid=10077
,11-03 13:34:17.575   930  3470 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 13:34:17.584   509   923 D SoftapController: Softap fwReload - Ok
,11-03 13:34:17.590   509   923 D CommandListener: Setting iface cfg
,11-03 13:34:17.590   509   923 D CommandListener: Trying to bring down wlan0
,11-03 13:34:17.592   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-03 13:34:17.600   930  3017 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 13:34:17.928   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:18.191   930  3017 D wifi    : set interface wlan0 flags (UP)
,11-03 13:34:18.191   930  3017 I WifiHAL : Initializing wifi
11-03 13:34:18.192   930  3017 I WifiHAL : Creating socket
,11-03 13:34:18.200   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 13:34:18.202   930  3017 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 13:34:18.202   930  3017 D wifi    : Did set static halHandle = 0x7f59b21b80
,11-03 13:34:18.202   930  3017 D wifi    : halHandle = 0x7f59b21b80, mVM = 0x7f7618d140, mCls = 0x10191e
11-03 13:34:18.203   930  3017 D wifi    : array field set
11-03 13:34:18.203   930  3017 I WifiNative-HAL: interface[0] = wlan0
11-03 13:34:18.205   930  5777 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546965691264
,11-03 13:34:18.205   930  5777 D wifi    : waitForHalEvents called, vm = 0x7f7618d140, obj = 0x10191e, env = 0x7f57397380
,11-03 13:34:18.277  5778  5778 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 13:34:18.306   930  3017 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 13:34:18.314  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 13:34:18.340  5778  5778 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 13:34:18.364  5778  5778 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 13:34:18.364  5778  5778 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 13:34:18.377   930  3017 D WifiConfigStore: Loading config and enabling all networks 
,11-03 13:34:18.381  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:18.381  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:18.381  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:18.381  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:18.381  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:34:18.381  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 13:34:18.381  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 13:34:18.381  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 13:34:18.381  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 13:34:18.381  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 13:34:18.381  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 13:34:18.402   930  3017 D WifiConfigStore: loaded 0 passpoint configs
,11-03 13:34:18.403   930  3017 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 13:34:18.403   930  3017 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-03 13:34:18.404   930  3017 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-03 13:34:18.404   930  3017 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-03 13:34:18.404   930  3017 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 13:34:18.405   930  3017 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-03 13:34:18.405   930  3017 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 13:34:18.406   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 13:34:18.406   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 13:34:18.406   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-03 13:34:18.406   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 13:34:18.406   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 13:34:18.408   930  3017 D WifiNative-HAL: Setting external_sim to 1
,11-03 13:34:18.409  4565  4565 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 13:34:18.409   930  3017 D wifi    : setting dfs flag to true, 0x7f5ca7fda0
11-03 13:34:18.409   930  3017 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 13:34:18.409   930  3017 D wifi    : setting scan oui 0x7f5ca7fda0
11-03 13:34:18.409   930  3017 D WifiHAL : Sending mac address OUI
,11-03 13:34:18.413   930  3017 E native  : do suspend false
,11-03 13:34:18.419   930  3017 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-03 13:34:18.419   930   930 D RttService: SCAN_AVAILABLE : 3
11-03 13:34:18.419   930  3129 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-03 13:34:18.420   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 13:34:18.421   509   923 D CommandListener: Setting iface cfg
,11-03 13:34:18.424   930  3000 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-03 13:34:18.424   930  3000 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 13:34:18.436   930  3000 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 13:34:18.440   930  3000 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 13:34:18.441   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128954 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-03 13:34:18.931   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:19.932   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:20.933   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:21.527  5778  5778 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 13:34:21.534  5778  5778 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 13:34:21.540  5778  5778 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 13:34:21.545  5778  5778 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 13:34:21.567   930  3017 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 13:34:21.568   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-03 13:34:21.568   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 13:34:21.578   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 13:34:21.613   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 13:34:21.618  5778  5778 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 13:34:21.934   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:22.046  5778  5778 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 13:34:22.081  5778  5778 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 13:34:22.082  5778  5778 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 13:34:22.088   930  3017 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-03 13:34:22.089   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 13:34:22.089   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 13:34:22.105   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 13:34:22.117   509   923 D CommandListener: Setting iface cfg
,11-03 13:34:22.121   930  3017 D WifiStateMachine: Start Dhcp Watchdog 2
,11-03 13:34:22.126   930  5786 D DhcpClient: Receive thread started
,11-03 13:34:22.130   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 13:34:22.130   930  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-03 13:34:22.130   930  3026 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-03 13:34:22.210   930  3017 E native  : do suspend false
,11-03 13:34:22.219   930  5785 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 13:34:22.234   930  5786 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172708, domain null
,11-03 13:34:22.235   930  5785 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172708 seconds
,11-03 13:34:22.237   930  5785 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 13:34:22.249   930  5786 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 13:34:22.250   930  5785 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-03 13:34:22.252   509   923 D CommandListener: Setting iface cfg
,11-03 13:34:22.256   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 13:34:22.260   930  5785 D DhcpClient: Scheduling renewal in 86399s
,11-03 13:34:22.271   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-03 13:34:22.272   930  3017 D WifiConfigStore: No blacklist allowed without epno enabled
11-03 13:34:22.273   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-03 13:34:22.279   930  3026 D ConnectivityService: Adding iface wlan0 to network 101
11-03 13:34:22.281   930  3017 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-03 13:34:22.330   930  3026 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-03 13:34:22.330   930  3026 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-03 13:34:22.332   930  3026 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-03 13:34:22.334   930  3026 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-03 13:34:22.336   930  3026 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-03 13:34:22.345   930  3026 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 13:34:22.349   930  3026 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-03 13:34:22.350   930  3026 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-03 13:34:22.350   930  3026 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-03 13:34:22.350   930  3017 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 13:34:22.350   930  3026 D ConnectivityService:    accepting network in place of null
11-03 13:34:22.350   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 13:34:22.351   930  3026 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 13:34:22.366   930  5784 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132879, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 13:34:22.375   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 13:34:22.399   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 13:34:22.405   930  3026 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-03 13:34:22.405   930  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 13:34:22.405  3769  3918 W QCNEJ   : |CORE| network available: 101
,11-03 13:34:22.406   930  3026 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-03 13:34:22.408   930   947 D Tethering: MasterInitialState.processMessage what=3
11-03 13:34:22.411  3769  3918 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-03 13:34:22.411  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:22.411  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:22.411  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:22.411  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:22.411  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:34:22.411  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 13:34:22.411  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 13:34:22.411  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 13:34:22.411  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 13:34:22.411  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:22.411  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 13:34:22.412  3769  3918 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 13:34:22.412  3769  3918 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-03 13:34:22.427  3997  3997 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-03 13:34:22.431  4077  4077 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 13:34:22.434   930  5783 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 13:34:22.437  4077  4077 D SystemUpdateService: onCreate
,11-03 13:34:22.442  4077  4077 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 13:34:22.453  4077  4077 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-03 13:34:22.461  4077  4296 I iu.UploadsManager: num queued entries: 0
,11-03 13:34:22.462  4077  4296 I iu.UploadsManager: num updated entries: 0
11-03 13:34:22.462  4077  4296 I iu.SyncManager: NEXT; no task
11-03 13:34:22.463  4077  5795 I SystemUpdateService: active receiver: enabled
,11-03 13:34:22.465  4077  4077 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 13:34:22.466  4077  4077 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 13:34:22.468  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 13:34:22.475  5748  5748 D SprintDMHelper: simOperator: 
,11-03 13:34:22.475  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 13:34:22.491   930  5783 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 12:34:22 GMT], X-Android-Received-Millis=[1478176462490], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478176462469]}
,11-03 13:34:22.491   930  3026 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 13:34:22.491   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-03 13:34:22.492   930  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 13:34:22.493   930  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-03 13:34:22.498  4077  5795 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 13:34:22.509  4077  5795 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-03 13:34:22.509  4077  5795 I SystemUpdateService: now status is 0 (complete)
,11-03 13:34:22.509  4077  5795 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-03 13:34:22.510  4077  5795 I SystemUpdateService: file has been verified
,11-03 13:34:22.510  4077  5795 I SystemUpdateService: OTA package size = 21989297
,11-03 13:34:22.517  4077  5795 I SystemUpdateService: showing system update notification
,11-03 13:34:22.526   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 13:34:22.531  4077  4077 D SystemUpdateService: onDestroy
,11-03 13:34:22.581   930  3803 D WifiService: setWifiEnabled: false pid=5651, uid=10077
,11-03 13:34:22.581   930  3803 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 13:34:22.583   930  3017 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 13:34:22.583   930  3017 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 13:34:22.583   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 13:34:22.584   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 13:34:22.591   930  5785 D DhcpClient: Clearing IP address
11-03 13:34:22.591   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-03 13:34:22.593   509   923 D CommandListener: Setting iface cfg
11-03 13:34:22.597  3637  5802 V NativeCrypto: Read error: ssl=0x7f74917180: I/O error during system call, Connection timed out
11-03 13:34:22.598  3637  5802 V NativeCrypto: SSL shutdown failed: ssl=0x7f74917180: I/O error during system call, Broken pipe
,11-03 13:34:22.604   930  3470 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-03 13:34:22.604   930  5783 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-03 13:34:22.604   930  5783 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-03 13:34:22.605   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-03 13:34:22.605   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-03 13:34:22.611   930  3026 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-03 13:34:22.611   591   591 E Parcel  : Reading a NULL string not supported here.
,11-03 13:34:22.612  3769  3918 W QCNEJ   : |CORE| network lost: 101
11-03 13:34:22.612  3769  3918 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-03 13:34:22.614   930   930 D RttService: SCAN_AVAILABLE : 1
11-03 13:34:22.615   930  3129 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 13:34:22.615   930  3017 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 13:34:22.617   930  5786 D DhcpClient: Receive thread stopped
,11-03 13:34:22.617   930  5783 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-03 13:34:22.618   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 13:34:22.636   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 13:34:22.655   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 13:34:22.655   509   923 D CommandListener: Clearing all IP addresses on wlan0
11-03 13:34:22.656   930  3026 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-03 13:34:22.656   930  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 13:34:22.657   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-03 13:34:22.661  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 13:34:22.661  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:22.661  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:22.661  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:22.661  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:34:22.661  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 13:34:22.661  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 13:34:22.661  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 13:34:22.661  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 13:34:22.661  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:22.661  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 13:34:22.662  3997  3997 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-03 13:34:22.663   930  3017 D DhcpClient: doQuit
,11-03 13:34:22.664   930  3017 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 13:34:22.664  5778  5778 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-03 13:34:22.664   930  5785 D DhcpClient: onQuitting
,11-03 13:34:22.668  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 13:34:22.668  4077  4077 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 13:34:22.668  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:22.668  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:22.668  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:22.668  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 13:34:22.668  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 13:34:22.668  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 13:34:22.668  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 13:34:22.668  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 13:34:22.668  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:22.668  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 13:34:22.672  4077  4077 D SystemUpdateService: onCreate
11-03 13:34:22.674  4077  4077 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 13:34:22.680  5778  5778 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 13:34:22.681  4077  5811 I SystemUpdateService: active receiver: enabled
,11-03 13:34:22.682  4077  4077 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 13:34:22.684  5778  5778 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 13:34:22.689  4077  4296 I iu.UploadsManager: num queued entries: 0
,11-03 13:34:22.689  4077  4296 I iu.UploadsManager: num updated entries: 0
,11-03 13:34:22.691  4077  4077 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 13:34:22.692  4077  4077 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 13:34:22.694  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 13:34:22.699  5748  5748 D SprintDMHelper: simOperator: 
11-03 13:34:22.699  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 13:34:22.711  4077  5811 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 13:34:22.712   509   923 E Netd    : netlink response contains error (No such file or directory)
,11-03 13:34:22.714   930  3026 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-03 13:34:22.720  5778  5778 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 13:34:22.722  4077  4296 I iu.SyncManager: NEXT; no task
,11-03 13:34:22.723  4077  5811 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-03 13:34:22.723  4077  5811 I SystemUpdateService: now status is 0 (complete)
11-03 13:34:22.723  4077  5811 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 13:34:22.723  4077  5811 I SystemUpdateService: file has been verified
11-03 13:34:22.723  4077  5811 I SystemUpdateService: OTA package size = 21989297
,11-03 13:34:22.726  5778  5778 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 13:34:22.733   930  3017 D wifi    : In wifi stop Hal
,11-03 13:34:22.733   930  3017 D wifi    : halHandle = 0x7f59b21b80, mVM = 0x7f7618d140, mCls = 0x10191e
11-03 13:34:22.733  4565  4565 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 13:34:22.733   930  5777 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 13:34:22.733   930  5777 D WifiHAL : Got a signal to exit!!!
,11-03 13:34:22.733   930  5777 I WifiHAL : Exit wifi_event_loop
11-03 13:34:22.733   930  3017 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 13:34:22.734   930  3017 E WifiHAL : Event processing terminated
11-03 13:34:22.734   930  3017 D wifi    : In wifi cleaned up handler
11-03 13:34:22.734   930  3017 I WifiHAL : Internal cleanup completed
11-03 13:34:22.734  3879  4226 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 13:34:22.735  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 13:34:22.738  4077  5811 I SystemUpdateService: showing system update notification
,11-03 13:34:22.745   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 13:34:22.746  4077  4077 D SystemUpdateService: onDestroy
,11-03 13:34:22.752   930  5777 D wifi    : set interface wlan0 flags (DOWN)
11-03 13:34:22.752   930  3017 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 13:34:22.934   593   593 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 13:34:22.957   930   947 D Tethering: InitialState.processMessage what=4
,11-03 13:34:22.964   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 13:34:23.405   930  3026 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-03 13:34:27.618   930   947 I ActivityManager: Start proc 5817:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 13:34:27.710  5817  5817 D AdapterServiceConfig: Adding HeadsetService
,11-03 13:34:27.711  5817  5817 D AdapterServiceConfig: Adding A2dpService
11-03 13:34:27.711  5817  5817 D AdapterServiceConfig: Adding HidService
11-03 13:34:27.711  5817  5817 D AdapterServiceConfig: Adding HealthService
11-03 13:34:27.711  5817  5817 D AdapterServiceConfig: Adding PanService
,11-03 13:34:27.711  5817  5817 D AdapterServiceConfig: Adding GattService
11-03 13:34:27.711  5817  5817 D AdapterServiceConfig: Adding BluetoothMapService
11-03 13:34:27.712  5817  5817 D AdapterServiceConfig: Adding SapService
,11-03 13:34:27.723   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aca5edd:true
,11-03 13:34:27.724  5817  5817 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 13:34:27.727  5817  5817 I bt_bluedroid: init
11-03 13:34:27.727  5817  5829 I BluetoothAdapterState: Entering OffState
,11-03 13:34:27.729  5817  5830 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 13:34:27.729  5817  5830 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 13:34:27.729  5817  5830 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 13:34:27.729  5817  5830 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-03 13:34:27.729  5817  5817 I bt_bluedroid: get_profile_interface socket
,11-03 13:34:27.731  5817  5833 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 13:34:27.731  5817  5817 I bt_bluedroid: get_profile_interface sdp
,11-03 13:34:27.732  5817  5833 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 13:34:27.735  5817  5828 I bt_bluedroid: config_hci_snoop_log
11-03 13:34:27.736   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 13:34:27.741  5817  5829 D BluetoothAdapterState: Current state: OFF, message: 0
11-03 13:34:27.741  5817  5829 D BluetoothAdapterProperties: Setting state to 14
11-03 13:34:27.741  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 13:34:27.743  5817  5829 D BluetoothBondStateMachine: make
,11-03 13:34:27.744  5817  5834 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 13:34:27.747  5817  5829 I BluetoothAdapterState: Entering PendingCommandState
,11-03 13:34:27.748  5817  5817 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 13:34:27.750  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@103424c
,11-03 13:34:27.750  5817  5817 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 13:34:27.751  5817  5817 D BtGatt.GattService: Received start request. Starting profile...
11-03 13:34:27.751  5817  5817 D BtGatt.GattService: start()
11-03 13:34:27.751  5817  5817 I bt_bluedroid: get_profile_interface gatt
,11-03 13:34:27.752  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@103424c
11-03 13:34:27.752  5817  5817 D BtGatt.AdvertiseManager: advertise manager created
,11-03 13:34:27.756  5817  5817 V BluetoothAdapterState: isTurningOff()=false
,11-03 13:34:27.756  5817  5817 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:27.756  5817  5817 V BluetoothAdapterState: isBleTurningOn()=true
11-03 13:34:27.756  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:27.757  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-03 13:34:27.758  5817  5829 I bt_bluedroid: bt_bluedroid
11-03 13:34:27.758  5817  5830 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-03 13:34:27.758  5817  5830 I bt_hci  : start_up
,11-03 13:34:27.764  5817  5830 I bt_vendor: alloc value 0xf4151871
11-03 13:34:27.764  5817  5830 I bt_vendor: init
,11-03 13:34:27.764  5817  5830 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 13:34:27.764  5817  5830 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 13:34:27.876  5817  5830 D bt_hci  : start_up starting async portion
,11-03 13:34:27.877  5817  5837 I bt_hci  : event_finish_startup
11-03 13:34:27.877  5817  5837 I bt_hci_h4: hal_open
11-03 13:34:27.877  5817  5837 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 13:34:27.875  5838  5838 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-03 13:34:27.880  5817  5837 I bt_userial_vendor: device fd = 54 open
,11-03 13:34:27.893  5817  5837 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 13:34:27.896  5817  5837 D bt_hwcfg: Chipset BCM4358A3
,11-03 13:34:27.896  5817  5837 D bt_hwcfg: Target name = [BCM4358A3]
11-03 13:34:27.897  5817  5837 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 13:34:28.304  5817  5837 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 13:34:28.304  5817  5837 D bt_hwcfg: Settlement delay -- 100 ms
,11-03 13:34:28.305  5817  5837 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 13:34:28.440  5817  5837 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 13:34:28.440  5817  5837 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-03 13:34:28.442  5817  5837 I bt_hwcfg: vendor lib fwcfg completed
,11-03 13:34:28.442  5817  5837 I bt_vendor: firmware callback
11-03 13:34:28.442  5817  5837 I bt_hci  : firmware_config_callback
,11-03 13:34:28.450  5817  5840 I bt_btu  : btu_task pending for preload complete event
,11-03 13:34:28.450  5817  5840 I bt_btu_task: Bluetooth chip preload is complete
,11-03 13:34:28.450  5817  5840 I bt_btu  : btu_task received preload complete event
,11-03 13:34:28.456  5817  5840 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 13:34:28.457  5817  5840 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-03 13:34:28.457  5817  5840 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 13:34:28.457  5817  5840 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 13:34:28.457  5817  5840 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-03 13:34:28.457  5817  5840 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 13:34:28.457  5817  5840 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-03 13:34:28.458  5817  5840 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 13:34:28.458  5817  5840 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 13:34:28.458  5817  5840 I         : BTE_InitTraceLevels -- TRC_PAN
,11-03 13:34:28.458  5817  5840 I         : BTE_InitTraceLevels -- TRC_SDP
11-03 13:34:28.458  5817  5840 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 13:34:28.458  5817  5840 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 13:34:28.458  5817  5840 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-03 13:34:28.458  5817  5840 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 13:34:28.546  5817  5840 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40cf549
,11-03 13:34:28.546  5817  5840 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40cf549 
,11-03 13:34:28.566  5817  5833 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 13:34:28.567  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 13:34:28.568  5817  5833 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 13:34:28.571  5817  5833 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 13:34:28.573  5817  5833 D BluetoothAdapterProperties: Scan Mode:20
11-03 13:34:28.574  5817  5833 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 13:34:28.574  5817  5833 D bt_hci  : do_postload posting postload work item
11-03 13:34:28.574  5817  5837 I bt_hci  : event_postload
,11-03 13:34:28.574  5817  5837 I bt_vendor: sco_config_cb
11-03 13:34:28.574  5817  5837 I bt_hci  : sco_config_callback postload finished.
11-03 13:34:28.577  5817  5833 D bt_bte_conf: Device ID record 1 : primary
11-03 13:34:28.577  5817  5833 D bt_bte_conf:   vendorId            = 000f
11-03 13:34:28.577  5817  5833 D bt_bte_conf:   vendorIdSource      = 0001
,11-03 13:34:28.578  5817  5833 D bt_bte_conf:   product             = 1200
,11-03 13:34:28.578  5817  5833 D bt_bte_conf:   version             = 1436
11-03 13:34:28.578  5817  5833 D bt_bte_conf:   clientExecutableURL = 
11-03 13:34:28.578  5817  5833 D bt_bte_conf:   serviceDescription  = 
11-03 13:34:28.578  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:34:28.578  5817  5833 D bt_bte_conf:   documentationURL    = 
11-03 13:34:28.578  5817  5833 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 13:34:28.578  5817  5830 D bt_stack_manager: event_start_up_stack finished
11-03 13:34:28.579  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-03 13:34:28.580  5817  5829 D BluetoothAdapterProperties: Setting state to 15
11-03 13:34:28.580  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 13:34:28.583  5817  5829 I BluetoothAdapterState: Entering BleOnState
,11-03 13:34:28.588  5817  5829 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 13:34:28.588  5817  5829 D BluetoothAdapterProperties: Setting state to 11
11-03 13:34:28.588  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 13:34:28.592  5817  5837 I bt_vendor: low_power_mode_cb
11-03 13:34:28.594  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@103424c
11-03 13:34:28.596  5817  5817 D HeadsetService: Received start request. Starting profile...
,11-03 13:34:28.597  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 13:34:28.600  5817  5817 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-03 13:34:28.601  5817  5817 D HeadsetStateMachine: make
,11-03 13:34:28.612  5817  5817 D HeadsetStateMachine: max_hf_connections = 1
,11-03 13:34:28.612  5817  5817 I bt_bluedroid: get_profile_interface handsfree
11-03 13:34:28.612  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 13:34:28.614  5817  5829 I BluetoothAdapterState: Entering PendingCommandState
,11-03 13:34:28.616  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@103424c
11-03 13:34:28.616  5817  5833 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-03 13:34:28.617  5817  5817 D A2dpService: Received start request. Starting profile...
,11-03 13:34:28.618  5817  5817 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 13:34:28.618  5817  5817 I bt_bluedroid: get_profile_interface avrcp
,11-03 13:34:28.627  5817  5817 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 13:34:28.627  5817  5817 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-03 13:34:28.627  5817  5817 D A2dpStateMachine: make
11-03 13:34:28.628  5817  5817 I bt_bluedroid: get_profile_interface a2dp
,11-03 13:34:28.629  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-03 13:34:28.631  5817  5848 D A2dpStateMachine: Enter Disconnected: -2
11-03 13:34:28.631  5817  5817 I BluetoothHidServiceJni: classInitNative: succeeds
11-03 13:34:28.632  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@103424c
,11-03 13:34:28.633  5710  5710 D BluetoothInputDevice: Proxy object connected
11-03 13:34:28.633  5817  5817 D HidService: Received start request. Starting profile...
,11-03 13:34:28.634  5817  5817 I bt_bluedroid: get_profile_interface hidhost
11-03 13:34:28.634  5710  5710 D HidProfile: Bluetooth service connected
11-03 13:34:28.634  5817  5833 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40b056d
11-03 13:34:28.634  5817  5817 D HidService: setHidService(): set to: null
11-03 13:34:28.634  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-03 13:34:28.635  5817  5817 I BluetoothHealthServiceJni: classInitNative: succeeds
11-03 13:34:28.636  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@103424c
11-03 13:34:28.637  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 13:34:28.637  5817  5817 D HealthService: Received start request. Starting profile...
,11-03 13:34:28.639  5817  5817 I bt_bluedroid: get_profile_interface health
11-03 13:34:28.639  5817  5817 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-03 13:34:28.640  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@103424c
,11-03 13:34:28.642  5710  5710 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 13:34:28.642  5817  5817 D PanService: Received start request. Starting profile...
11-03 13:34:28.642  5817  5817 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 13:34:28.643  5817  5817 I bt_bluedroid: get_profile_interface pan
11-03 13:34:28.643  5817  5833 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 13:34:28.643  5710  5710 D PanProfile: Bluetooth service connected
11-03 13:34:28.645  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@103424c
,11-03 13:34:28.646  5817  5817 D BluetoothMapService: Received start request. Starting profile...
,11-03 13:34:28.646  5817  5817 D BluetoothMapService: start()
11-03 13:34:28.646  5710  5710 D BluetoothMap: Proxy object connected
11-03 13:34:28.647  5710  5710 D MapProfile: Bluetooth service connected
11-03 13:34:28.647  5710  5710 D BluetoothMap: getConnectedDevices()
11-03 13:34:28.648  5710  5710 D BluetoothMap: Bluetooth is Not enabled
11-03 13:34:28.648  5817  5817 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-03 13:34:28.649  5817  5817 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 13:34:28.649  5817  5817 D BluetoothMapAppObserver: createReceiver()
11-03 13:34:28.650  5817  5817 D BluetoothMapAppObserver: initObservers()
,11-03 13:34:28.650  5817  5817 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 13:34:28.657  5817  5817 V SapService: SapBinder()
11-03 13:34:28.657  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@103424c
,11-03 13:34:28.658  5817  5817 D SapService: Received start request. Starting profile...
11-03 13:34:28.658  5817  5817 V SapService: start()
,11-03 13:34:28.659  5817  5817 V BluetoothAdapterState: isTurningOff()=false
,11-03 13:34:28.659  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:28.659  5817  5846 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 13:34:28.659  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:28.660  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:28.660  5817  5817 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:28.660  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:28.660  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:28.660  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:28.660  5817  5817 V BluetoothAdapterState: isTurningOff()=false
,11-03 13:34:28.660  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:28.660  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:28.660  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:28.660  5817  5817 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:28.661  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:28.661  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:28.661  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 13:34:28.661  5817  5817 V BluetoothAdapterState: isTurningOff()=false
,11-03 13:34:28.661  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:28.662  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:28.662  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:28.662  5817  5817 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:28.662  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:28.662  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:28.662  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 13:34:28.663  5817  5817 V BluetoothAdapterState: isTurningOff()=false
,11-03 13:34:28.663  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:28.663  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:28.663  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 13:34:28.664  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 13:34:28.664  5817  5829 D BluetoothAdapterProperties: ScanMode =  20
11-03 13:34:28.664  5817  5829 D BluetoothAdapterProperties: State =  11
,11-03 13:34:28.665  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 13:34:28.666  5817  5833 D BluetoothAdapterProperties: Scan Mode:21
11-03 13:34:28.666  5817  5829 D BluetoothAdapterProperties: Setting state to 12
11-03 13:34:28.666  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-03 13:34:28.666  5817  5833 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 13:34:28.667  5817  5829 I BluetoothAdapterState: Entering OnState
11-03 13:34:28.667  3799  3828 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 13:34:28.668  3193  3205 D BluetoothPan: onBluetoothStateChange on: true
,11-03 13:34:28.669  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:28.669  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:28.669  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:28.669  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 13:34:28.669  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 13:34:28.669  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 13:34:28.669  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 13:34:28.669  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 13:34:28.669  3193  3193 D BluetoothPan: BluetoothPAN Proxy object connected
,11-03 13:34:28.669  3193  3193 D PanProfile: Bluetooth service connected
11-03 13:34:28.669  5710  5722 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 13:34:28.670  5710  5721 D BluetoothPan: onBluetoothStateChange on: true
11-03 13:34:28.670  3193  5650 D BluetoothMap: onBluetoothStateChange: up=true
11-03 13:34:28.671  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 13:34:28.672  3193  3193 D BluetoothMap: Proxy object connected
,11-03 13:34:28.672  5710  5722 D BluetoothMap: onBluetoothStateChange: up=true
11-03 13:34:28.672  3193  3193 D MapProfile: Bluetooth service connected
11-03 13:34:28.672  3193  3193 D BluetoothMap: getConnectedDevices()
11-03 13:34:28.672  3193  3204 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 13:34:28.673  3193  3193 D BluetoothInputDevice: Proxy object connected
11-03 13:34:28.673  3193  4022 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 13:34:28.673  3193  3193 D HidProfile: Bluetooth service connected
11-03 13:34:28.674   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 13:34:28.675  3193  3204 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 13:34:28.676   930   930 D BluetoothA2dp: Proxy object connected
,11-03 13:34:28.677   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 13:34:28.677   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 13:34:28.677  5817  5817 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 13:34:28.677  5710  5721 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 13:34:28.677  5817  5817 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 13:34:28.678  5817  5817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 13:34:28.679  3193  3205 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 13:34:28.680  5817  5817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 13:34:28.680   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 13:34:28.680  3193  3193 D BluetoothA2dp: Proxy object connected
,11-03 13:34:28.681   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 13:34:28.682  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 13:34:28.684  5817  5817 D ObexServerSockets: Succeed to create listening sockets 
11-03 13:34:28.684  5817  5817 D ObexServerSockets0: startAccept()
11-03 13:34:28.684  5817  5817 D ObexServerSockets0: prepareForNewConnect()
,11-03 13:34:28.685  5710  5710 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-03 13:34:28.686  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:34:28.687  5817  5817 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 13:34:28.687  5817  5817 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 13:34:28.688  5817  5854 D ObexServerSockets0: Accepting socket connection...
11-03 13:34:28.688  5817  5817 D BluetoothMapService: onReceive
11-03 13:34:28.688  5817  5817 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 13:34:28.688  5817  5817 D BluetoothMapService: STATE_ON
11-03 13:34:28.688  5817  5855 D ObexServerSockets0: Accepting socket connection...
11-03 13:34:28.689  5710  5710 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-03 13:34:28.690  5817  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 13:34:28.691  5817  5856 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 13:34:28.691  5817  5856 D BluetoothSdpJni: SDP Create record success - handle: 1
11-03 13:34:28.695  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 13:34:28.697  5710  5710 D BluetoothA2dp: Proxy object connected
,11-03 13:34:28.700  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 13:34:28.705  5710  5710 D DockEventReceiver: finishStartingService: stopping service
,11-03 13:34:28.708  5710  5710 D BluetoothPbap: Proxy object connected
,11-03 13:34:28.708  5710  5710 D PbapServerProfile: Bluetooth service connected
,11-03 13:34:28.711  3193  3193 D BluetoothPbap: Proxy object connected
11-03 13:34:28.711  3193  3193 D PbapServerProfile: Bluetooth service connected
,11-03 13:34:28.713  5817  5817 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-03 13:34:28.713  5817  5817 D ObexServerSockets0: prepareForNewConnect()
11-03 13:34:28.715  5817  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 13:34:28.728  5817  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 13:34:28.730  5817  5864 I BtOppRfcommListener: Accept thread started.
,11-03 13:34:28.769   930   930 D BluetoothHeadset: Proxy object connected
,11-03 13:34:28.770  3799  4030 D BluetoothHeadset: Proxy object connected
11-03 13:34:28.770   930   930 D BluetoothHeadset: Proxy object connected
11-03 13:34:28.770  3193  4022 D BluetoothHeadset: Proxy object connected
11-03 13:34:28.770  3193  3193 D HeadsetProfile: Bluetooth service connected
11-03 13:34:28.770   930   930 D BluetoothHeadset: Proxy object connected
,11-03 13:34:28.774  3193  3204 D BluetoothHeadset: Proxy object connected
11-03 13:34:28.774  3193  3193 D HeadsetProfile: Bluetooth service connected
,11-03 13:34:28.776   930   947 D BluetoothHeadset: Proxy object connected
,11-03 13:34:28.777   930   947 D BluetoothHeadset: Proxy object connected
,11-03 13:34:28.781   930   947 D BluetoothHeadset: Proxy object connected
,11-03 13:34:28.791  5710  5721 D BluetoothHeadset: Proxy object connected
,11-03 13:34:28.794  5710  5710 D HeadsetProfile: Bluetooth service connected
,11-03 13:34:30.357   930  3026 D ConnectivityService: handlePromptUnvalidated 101
,11-03 13:34:30.433  3692  3872 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-03 13:34:30.433  3692  3872 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-03 13:34:30.466  3637  3637 I ConfigService: onCreate
,11-03 13:34:32.598  5817  5829 D BluetoothAdapterState: Current state: ON, message: 23
,11-03 13:34:32.599  5817  5829 D BluetoothAdapterProperties: Setting state to 13
,11-03 13:34:32.599  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-03 13:34:32.600  5817  5829 D BluetoothAdapterProperties: onBluetoothDisable()
11-03 13:34:32.602  5817  5829 I BluetoothAdapterState: Entering PendingCommandState
11-03 13:34:32.605  5817  5817 D BluetoothMapService: onReceive
11-03 13:34:32.605  5817  5817 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 13:34:32.606  5817  5817 D BluetoothMapService: STATE_TURNING_OFF
11-03 13:34:32.607  5817  5817 D BluetoothMapService: MAP Service closeService in
11-03 13:34:32.607  5817  5817 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 13:34:32.607  5817  5817 D ObexServerSockets0: shutdown(block = true)
11-03 13:34:32.608  5817  5817 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 13:34:32.608  5817  5854 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-03 13:34:32.609  5817  5842 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 13:34:32.609  5817  5817 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 13:34:32.609  5817  5855 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 13:34:32.614  5817  5817 I BtOppRfcommListener: stopping Accept Thread
11-03 13:34:32.615  5817  5864 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 13:34:32.615  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:32.615  5817  5864 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-03 13:34:32.616  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:32.616  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:32.616  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:32.616  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 13:34:32.616  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 13:34:32.616  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 13:34:32.616  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 13:34:32.616  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 13:34:32.618  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 13:34:32.618  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 13:34:32.619  5817  5833 D BluetoothAdapterProperties: Scan Mode:20
11-03 13:34:32.620  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-03 13:34:32.621  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 13:34:32.626  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 13:34:32.630  5817  5817 D HeadsetService: Received stop request...Stopping profile...
,11-03 13:34:32.634   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 13:34:32.635  3799  4030 D BluetoothHeadset: Proxy object disconnected
,11-03 13:34:32.635  5710  5721 D BluetoothHeadset: Proxy object disconnected
11-03 13:34:32.635   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 13:34:32.636  5817  5817 D A2dpService: Received stop request...Stopping profile...
11-03 13:34:32.636  3193  3205 D BluetoothHeadset: Proxy object disconnected
11-03 13:34:32.636  3193  3193 D HeadsetProfile: Bluetooth service disconnected
11-03 13:34:32.636   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 13:34:32.637  5817  5848 D A2dpStateMachine: Exit Disconnected: -1
11-03 13:34:32.637   930   930 D BluetoothA2dp: Proxy object disconnected
,11-03 13:34:32.638  3193  3193 D BluetoothA2dp: Proxy object disconnected
11-03 13:34:32.638  5817  5817 D HidService: Received stop request...Stopping profile...
11-03 13:34:32.638  5817  5817 D HidService: Stopping Bluetooth HidService
11-03 13:34:32.640  3193  3193 D BluetoothInputDevice: Proxy object disconnected
11-03 13:34:32.640  3193  3193 D HidProfile: Bluetooth service disconnected
11-03 13:34:32.641  5817  5817 D HealthService: Received stop request...Stopping profile...
,11-03 13:34:32.641  5710  5710 D DockEventReceiver: finishStartingService: stopping service
11-03 13:34:32.642  5710  5710 D HeadsetProfile: Bluetooth service disconnected
11-03 13:34:32.643  5817  5817 D PanService: Received stop request...Stopping profile...
11-03 13:34:32.643  5710  5710 D BluetoothA2dp: Proxy object disconnected
11-03 13:34:32.643  5710  5710 D BluetoothInputDevice: Proxy object disconnected
11-03 13:34:32.644  5710  5710 D HidProfile: Bluetooth service disconnected
11-03 13:34:32.644  3193  3193 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 13:34:32.644  3193  3193 D PanProfile: Bluetooth service disconnected
11-03 13:34:32.644  5710  5710 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 13:34:32.644  5710  5710 D PanProfile: Bluetooth service disconnected
,11-03 13:34:32.649  5817  5817 D BluetoothMapService: Received stop request...Stopping profile...
,11-03 13:34:32.649  5817  5817 D BluetoothMapService: stop()
11-03 13:34:32.649  5817  5817 D BluetoothMapAppObserver: deinitObservers()
11-03 13:34:32.649  5817  5817 D BluetoothMapAppObserver: removeReceiver()
,11-03 13:34:32.651  3193  3193 D BluetoothMap: Proxy object disconnected
,11-03 13:34:32.651  3193  3193 D MapProfile: Bluetooth service disconnected
11-03 13:34:32.652  5710  5710 D BluetoothMap: Proxy object disconnected
11-03 13:34:32.652  5817  5817 D SapService: Received stop request...Stopping profile...
11-03 13:34:32.652  5710  5710 D MapProfile: Bluetooth service disconnected
11-03 13:34:32.652  5817  5817 V SapService: stop()
,11-03 13:34:32.654  5817  5817 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:32.654  5817  5817 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:32.654  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 13:34:32.654  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 13:34:32.657  5817  5817 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 13:34:32.657  5817  5817 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 13:34:32.657  5817  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 13:34:32.657  5817  5817 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:32.657  5817  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 13:34:32.657  5817  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 13:34:32.657  5817  5817 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:32.657  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:32.657  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:32.658  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 13:34:32.659  5817  5833 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 13:34:32.659  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 13:34:32.659  5817  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 13:34:32.659  5817  5817 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:32.659  5817  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 13:34:32.659  5817  5817 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:32.659  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:32.659  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:32.660  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 13:34:32.660  5817  5840 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 13:34:32.660  5817  5840 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 13:34:32.660  5817  5840 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 13:34:32.660  5817  5840 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 13:34:32.661  5817  5817 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 13:34:32.661  5817  5817 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 13:34:32.661  5817  5817 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:32.661  5817  5817 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:32.661  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:32.661  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:32.661  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 13:34:32.661  5817  5817 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-03 13:34:32.662  5817  5833 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-03 13:34:32.663  5817  5817 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-03 13:34:32.663  5817  5817 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:32.663  5817  5817 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:32.663  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:32.663  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:32.664  5817  5817 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 13:34:32.664  5817  5817 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 13:34:32.665  5817  5817 D BluetoothMapService: MAP Service closeService in
11-03 13:34:32.665  5817  5817 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:32.665  5817  5817 V BluetoothAdapterState: isTurningOn()=false
,11-03 13:34:32.665  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:32.665  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:32.665  5817  5817 D BluetoothMapService: cleanup()
11-03 13:34:32.665  5817  5817 D BluetoothMapService: MAP Service closeService in
11-03 13:34:32.666  5817  5817 V BluetoothAdapterState: isTurningOff()=true
11-03 13:34:32.666  5817  5817 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:32.666  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:32.666  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:32.666  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-03 13:34:32.666  5817  5829 D BluetoothAdapterProperties: Setting state to 15
11-03 13:34:32.666  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 13:34:32.667  5817  5829 I BluetoothAdapterState: Entering BleOnState
11-03 13:34:32.667  3799  3830 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 13:34:32.668  3193  3193 D BluetoothPbap: Proxy object disconnected
11-03 13:34:32.668  3193  3193 D PbapServerProfile: Bluetooth service disconnected
11-03 13:34:32.668  3193  3205 D BluetoothPan: onBluetoothStateChange on: false
11-03 13:34:32.669  5710  5721 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-03 13:34:32.675  5710  5722 D BluetoothPan: onBluetoothStateChange on: false
,11-03 13:34:32.676  3193  5650 D BluetoothMap: onBluetoothStateChange: up=false
,11-03 13:34:32.677  5710  5721 D BluetoothMap: onBluetoothStateChange: up=false
11-03 13:34:32.678  3193  3204 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 13:34:32.678  3193  4022 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 13:34:32.678   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 13:34:32.679  3193  3205 D BluetoothPbap: onBluetoothStateChange: up=false
,11-03 13:34:32.679   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 13:34:32.679   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 13:34:32.679  5710  5722 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 13:34:32.680  3193  5650 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 13:34:32.681  5710  5721 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 13:34:32.681  5710  5722 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 13:34:32.681   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 13:34:32.682  5817  5829 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 13:34:32.682  5817  5829 D BluetoothAdapterProperties: Setting state to 16
11-03 13:34:32.682  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 13:34:32.682  5710  5710 D BluetoothPbap: Proxy object disconnected
11-03 13:34:32.682  5710  5710 D PbapServerProfile: Bluetooth service disconnected
11-03 13:34:32.682  5817  5829 D BluetoothAdapterProperties: onBleDisable
11-03 13:34:32.682  5817  5829 I BluetoothAdapterState: Entering PendingCommandState
11-03 13:34:32.683  5817  5830 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 13:34:32.684  5817  5833 D BluetoothAdapterProperties: Scan Mode:20
11-03 13:34:32.685  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 13:34:32.685  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:34:32.685  5817  5840 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 13:34:32.686  5817  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 13:34:32.690  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 13:34:32.690  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:34:32.691  5710  5710 D DockEventReceiver: finishStartingService: stopping service
,11-03 13:34:32.899  5817  5833 I bt_hci  : shut_down
,11-03 13:34:32.910  5817  5837 D bt_hwcfg: hw_epilog_process
,11-03 13:34:32.911  5817  5837 I bt_vendor: low_power_mode_cb
,11-03 13:34:32.914  5817  5837 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-03 13:34:32.914  5817  5837 I bt_vendor: epilog_cb
11-03 13:34:32.914  5817  5837 I bt_hci  : epilog_finished_callback
,11-03 13:34:32.921  5817  5833 I bt_hci_h4: hal_close
,11-03 13:34:32.922  5817  5833 I bt_userial_vendor: device fd = 54 close
,11-03 13:34:32.935   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:33.045  5817  5830 D bt_stack_manager: event_shut_down_stack finished.
,11-03 13:34:33.046  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 13:34:33.050  5817  5829 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-03 13:34:33.050  5817  5817 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 13:34:33.052  5817  5817 D BtGatt.GattService: Received stop request...Stopping profile...
,11-03 13:34:33.052  5817  5817 D BtGatt.GattService: stop()
11-03 13:34:33.052  5817  5817 D BtGatt.AdvertiseManager: advertise clients cleared
11-03 13:34:33.055  5817  5817 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:33.055  5817  5817 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:33.056  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:33.056  5817  5817 V BluetoothAdapterState: isBleTurningOff()=true
11-03 13:34:33.056  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-03 13:34:33.057  5817  5829 D BluetoothAdapterProperties: Setting state to 10
11-03 13:34:33.057  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 13:34:33.058  5817  5829 I BluetoothAdapterState: Entering OffState
,11-03 13:34:33.059   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 13:34:33.072  5817  5817 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 13:34:33.072  5817  5817 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-03 13:34:33.072  5817  5817 I BluetoothServiceJni: cleanupNative: return from cleanup
11-03 13:34:33.075  5817  5830 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 13:34:33.082  5817  5817 I art     : System.exit called, status: 0
,11-03 13:34:33.082  5817  5817 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 13:34:33.115   930   941 I ActivityManager: Process com.android.bluetooth (pid 5817) has died
,11-03 13:34:33.936   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:34.937   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:35.492  3637  3637 I ConfigService: onDestroy
,11-03 13:34:35.938   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:36.939   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:37.596  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 13:34:37.597  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 13:34:37.603  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:37.603  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e60c39e removed from the list
,11-03 13:34:37.603  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 13:34:37.605  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 13:34:37.606  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@53c7e95 added. We now have 4 listener(s)
,11-03 13:34:37.606  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:37.608  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:37.608  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@53c7e95 removed from the list
11-03 13:34:37.608  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:37.610  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 13:34:37.610  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5917baa added. We now have 4 listener(s)
11-03 13:34:37.610  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 13:34:37.940   593   593 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 13:34:42.004   930   950 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-03 13:34:42.015   940   940 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[28563]" dev="sockfs" ino=28563 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:34:42.015   940   940 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28563]" dev="sockfs" ino=28563 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 13:34:42.021  3692  3692 I Keyboard.Facilitator: onFinishInput()
,11-03 13:34:42.045   930   950 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 13:34:42.045   930   950 I Adreno  : Build Date                       : 12/06/15
11-03 13:34:42.045   930   950 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 13:34:42.045   930   950 I Adreno  : Local Branch                     : mybranch17112971
11-03 13:34:42.045   930   950 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 13:34:42.045   930   950 I Adreno  : Remote Branch                    : NONE
11-03 13:34:42.045   930   950 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 13:34:42.087   382   505 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (192 us)
,11-03 13:34:42.618  5651  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 13:34:42.649   930   947 I ActivityManager: Start proc 5875:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 13:34:42.756  5651  5651 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 13:34:42.756  5651  5651 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-03 13:34:42.781   930   950 I sensors : batch
11-03 13:34:42.781   930   950 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-03 13:34:42.785   930   950 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,11-03 13:34:42.785   930   950 I sensors : activate
11-03 13:34:42.785  5651  5651 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2bffaa Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@21ba39b, 16908290=android.view.AbsSavedState$1@21ba39b}, android:focusedViewId=100}]}]
11-03 13:34:42.785  5651  5651 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-03 13:34:42.786  5651  5651 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-03 13:34:42.786  5651  5651 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-03 13:34:42.786   930   948 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-03 13:34:42.787  5875  5875 D AdapterServiceConfig: Adding HeadsetService
,11-03 13:34:42.787  5875  5875 D AdapterServiceConfig: Adding A2dpService
11-03 13:34:42.787  5875  5875 D AdapterServiceConfig: Adding HidService
11-03 13:34:42.788  5875  5875 D AdapterServiceConfig: Adding HealthService
11-03 13:34:42.788  5875  5875 D AdapterServiceConfig: Adding PanService
11-03 13:34:42.788  5875  5875 D AdapterServiceConfig: Adding GattService
11-03 13:34:42.788  5875  5875 D AdapterServiceConfig: Adding BluetoothMapService
11-03 13:34:42.788  5875  5875 D AdapterServiceConfig: Adding SapService
11-03 13:34:42.789   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f8f2c3c00
,11-03 13:34:42.789   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-03 13:34:42.790   930  2800 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-03 13:34:42.792   930  2800 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-03 13:34:42.798   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@97e5655:true
11-03 13:34:42.798  5875  5875 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 13:34:42.800  5875  5875 I bt_bluedroid: init
,11-03 13:34:42.800  5875  5889 I BluetoothAdapterState: Entering OffState
,11-03 13:34:42.802  5875  5890 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-03 13:34:42.802  5875  5890 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 13:34:42.802  5875  5890 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 13:34:42.802  5875  5890 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-03 13:34:42.803  5875  5875 I bt_bluedroid: get_profile_interface socket
,11-03 13:34:42.804  5875  5893 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 13:34:42.805  5875  5875 I bt_bluedroid: get_profile_interface sdp
,11-03 13:34:42.807  5875  5893 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 13:34:42.810  5875  5886 I bt_bluedroid: config_hci_snoop_log
,11-03 13:34:42.811   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 13:34:42.816  5875  5889 D BluetoothAdapterState: Current state: OFF, message: 0
,11-03 13:34:42.816  5875  5889 D BluetoothAdapterProperties: Setting state to 14
11-03 13:34:42.816  5875  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-03 13:34:42.817  5875  5889 D BluetoothBondStateMachine: make
,11-03 13:34:42.819  5875  5894 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 13:34:42.821  5875  5889 I BluetoothAdapterState: Entering PendingCommandState
,11-03 13:34:42.822  5875  5875 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 13:34:42.824  5875  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
11-03 13:34:42.825  5875  5875 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 13:34:42.825  5875  5875 D BtGatt.GattService: Received start request. Starting profile...
11-03 13:34:42.825  5875  5875 D BtGatt.GattService: start()
11-03 13:34:42.826  5875  5875 I bt_bluedroid: get_profile_interface gatt
,11-03 13:34:42.826  5875  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
11-03 13:34:42.826  5875  5875 D BtGatt.AdvertiseManager: advertise manager created
,11-03 13:34:42.831  5875  5875 V BluetoothAdapterState: isTurningOff()=false
,11-03 13:34:42.831  5875  5875 V BluetoothAdapterState: isTurningOn()=false
11-03 13:34:42.831  5875  5875 V BluetoothAdapterState: isBleTurningOn()=true
11-03 13:34:42.831  5875  5875 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:42.832  5875  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-03 13:34:42.833  5875  5889 I bt_bluedroid: bt_bluedroid
11-03 13:34:42.833  5875  5890 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-03 13:34:42.834  5875  5890 I bt_hci  : start_up
,11-03 13:34:42.838  5875  5890 I bt_vendor: alloc value 0xf4151871
11-03 13:34:42.838  5875  5890 I bt_vendor: init
,11-03 13:34:42.838  5875  5890 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 13:34:42.838  5875  5890 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 13:34:42.947  5875  5890 D bt_hci  : start_up starting async portion
,11-03 13:34:42.947  5875  5897 I bt_hci  : event_finish_startup
11-03 13:34:42.947  5875  5897 I bt_hci_h4: hal_open
11-03 13:34:42.947  5875  5897 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 13:34:42.945  5898  5898 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 13:34:42.949  5875  5897 I bt_userial_vendor: device fd = 54 open
,11-03 13:34:42.963  5875  5897 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 13:34:42.966  5875  5897 D bt_hwcfg: Chipset BCM4358A3
11-03 13:34:42.966  5875  5897 D bt_hwcfg: Target name = [BCM4358A3]
11-03 13:34:42.966  5875  5897 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 13:34:43.094   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-03 13:34:43.095   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
11-03 13:34:43.096   930  3136 D SurfaceControl: Excessive delay in setPowerMode(): 310ms
,11-03 13:34:43.108   930   950 I DreamManagerService: Entering dreamland.
,11-03 13:34:43.109   930   950 I PowerManagerService: Dozing...
,11-03 13:34:43.110   930   945 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-03 13:34:43.142  3780  3780 W Binder_A: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33279]" dev="sockfs" ino=33279 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:34:43.145   930  3779 I sensors : batch
11-03 13:34:43.145   930  3779 I sensors : activate
11-03 13:34:43.142  3780  3780 W Binder_A: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33279]" dev="sockfs" ino=33279 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:34:43.148   930  2800 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-03 13:34:43.150   930  2800 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-03 13:34:43.155   514  3047 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-03 13:34:43.180  3799  4803 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-03 13:34:43.180  3799  4803 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-03 13:34:43.180  3799  4803 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 13:34:43.180   527  1285 D         : oem-qmi: Connection accepted
11-03 13:34:43.181   527  1285 D         : oem-qmi: Waiting to accept connection
,11-03 13:34:43.182   930   930 I sensors : activate
11-03 13:34:43.183   514   514 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-03 13:34:43.186   930  2800 I hubconnection: sensorhub said: 'activate 31 enable:0'
11-03 13:34:43.187  3799  4803 D         : oem_qmi_lib:output 0
11-03 13:34:43.187  3799  4803 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 13:34:43.215  3799  4803 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-03 13:34:43.215  3799  4803 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-03 13:34:43.215  3799  4803 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 13:34:43.215   527  1285 D         : oem-qmi: Connection accepted
,11-03 13:34:43.216   527  1285 D         : oem-qmi: Waiting to accept connection
,11-03 13:34:43.222  3799  4803 D         : oem_qmi_lib:output 0
,11-03 13:34:43.222  3799  4803 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 13:34:43.442  5875  5897 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 13:34:43.442  5875  5897 D bt_hwcfg: Settlement delay -- 100 ms
11-03 13:34:43.442  5875  5897 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 13:34:43.577  5875  5897 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-03 13:34:43.577  5875  5897 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 13:34:43.578  5875  5897 I bt_hwcfg: vendor lib fwcfg completed
11-03 13:34:43.579  5875  5897 I bt_vendor: firmware callback
11-03 13:34:43.579  5875  5897 I bt_hci  : firmware_config_callback
,11-03 13:34:43.591  5875  5904 I bt_btu  : btu_task pending for preload complete event
11-03 13:34:43.591  5875  5904 I bt_btu_task: Bluetooth chip preload is complete
,11-03 13:34:43.591  5875  5904 I bt_btu  : btu_task received preload complete event
,11-03 13:34:43.598  5875  5904 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 13:34:43.599  5875  5904 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 13:34:43.599  5875  5904 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-03 13:34:43.599  5875  5904 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 13:34:43.599  5875  5904 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-03 13:34:43.599  5875  5904 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 13:34:43.599  5875  5904 I         : BTE_InitTraceLevels -- TRC_BNEP
11-03 13:34:43.600  5875  5904 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 13:34:43.600  5875  5904 I         : BTE_InitTraceLevels -- TRC_GAP
,11-03 13:34:43.600  5875  5904 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 13:34:43.600  5875  5904 I         : BTE_InitTraceLevels -- TRC_SDP
11-03 13:34:43.600  5875  5904 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 13:34:43.600  5875  5904 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 13:34:43.600  5875  5904 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-03 13:34:43.600  5875  5904 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 13:34:43.701  5875  5904 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40cf549
11-03 13:34:43.701  5875  5904 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40cf549 
,11-03 13:34:43.734  5875  5893 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 13:34:43.737  5875  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 13:34:43.737  5875  5893 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-03 13:34:43.740  5875  5893 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 13:34:43.745  5875  5893 D BluetoothAdapterProperties: Scan Mode:20
11-03 13:34:43.745  5875  5893 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 13:34:43.745  5875  5893 D bt_hci  : do_postload posting postload work item
,11-03 13:34:43.745  5875  5897 I bt_hci  : event_postload
11-03 13:34:43.745  5875  5897 I bt_vendor: sco_config_cb
,11-03 13:34:43.746  5875  5897 I bt_hci  : sco_config_callback postload finished.
,11-03 13:34:43.748  5875  5893 D bt_bte_conf: Device ID record 1 : primary
11-03 13:34:43.748  5875  5893 D bt_bte_conf:   vendorId            = 000f
11-03 13:34:43.748  5875  5893 D bt_bte_conf:   vendorIdSource      = 0001
11-03 13:34:43.748  5875  5893 D bt_bte_conf:   product             = 1200
11-03 13:34:43.748  5875  5893 D bt_bte_conf:   version             = 1436
11-03 13:34:43.748  5875  5893 D bt_bte_conf:   clientExecutableURL = 
11-03 13:34:43.748  5875  5893 D bt_bte_conf:   serviceDescription  = 
11-03 13:34:43.748  5875  5893 D bt_bte_conf:   documentationURL    = 
11-03 13:34:43.749  5875  5893 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 13:34:43.749  5875  5890 D bt_stack_manager: event_start_up_stack finished
11-03 13:34:43.749  5875  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-03 13:34:43.750  5875  5889 D BluetoothAdapterProperties: Setting state to 15
11-03 13:34:43.750  5875  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 13:34:43.751  5875  5889 I BluetoothAdapterState: Entering BleOnState
,11-03 13:34:43.753  5875  5897 I bt_vendor: low_power_mode_cb
,11-03 13:34:43.756  5875  5889 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-03 13:34:43.756  5875  5889 D BluetoothAdapterProperties: Setting state to 11
11-03 13:34:43.757  5875  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 13:34:43.765  5875  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
,11-03 13:34:43.766  5875  5875 D HeadsetService: Received start request. Starting profile...
,11-03 13:34:43.768  5875  5875 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 13:34:43.769  5875  5875 D HeadsetStateMachine: make
,11-03 13:34:43.778  5875  5875 D HeadsetStateMachine: max_hf_connections = 1
11-03 13:34:43.779  5875  5875 I bt_bluedroid: get_profile_interface handsfree
11-03 13:34:43.779  5875  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-03 13:34:43.779  5875  5893 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-03 13:34:43.782  5875  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
11-03 13:34:43.783  5875  5889 I BluetoothAdapterState: Entering PendingCommandState
,11-03 13:34:43.784  5875  5875 D A2dpService: Received start request. Starting profile...
11-03 13:34:43.785  5875  5875 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 13:34:43.785  5875  5875 I bt_bluedroid: get_profile_interface avrcp
,11-03 13:34:43.792  5875  5875 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 13:34:43.792  5875  5875 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 13:34:43.793  5875  5875 D A2dpStateMachine: make
,11-03 13:34:43.794  5875  5875 I bt_bluedroid: get_profile_interface a2dp
11-03 13:34:43.795  5875  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 13:34:43.796  5875  5912 D A2dpStateMachine: Enter Disconnected: -2
,11-03 13:34:43.797  5875  5875 I BluetoothHidServiceJni: classInitNative: succeeds
11-03 13:34:43.798  5875  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
,11-03 13:34:43.799  5875  5875 D HidService: Received start request. Starting profile...
,11-03 13:34:43.799  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 13:34:43.799  5875  5875 I bt_bluedroid: get_profile_interface hidhost
11-03 13:34:43.799  5875  5875 D HidService: setHidService(): set to: null
11-03 13:34:43.799  5875  5893 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40b056d
,11-03 13:34:43.800  5875  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 13:34:43.800  5875  5875 I BluetoothHealthServiceJni: classInitNative: succeeds
11-03 13:34:43.800  5875  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
,11-03 13:34:43.801  5875  5875 D HealthService: Received start request. Starting profile...
11-03 13:34:43.802  5875  5875 I bt_bluedroid: get_profile_interface health
,11-03 13:34:43.804  5875  5875 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-03 13:34:43.805  5875  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
11-03 13:34:43.805  5875  5875 D PanService: Received start request. Starting profile...
11-03 13:34:43.806  5875  5875 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 13:34:43.806  5875  5875 I bt_bluedroid: get_profile_interface pan
11-03 13:34:43.806  5875  5893 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 13:34:43.808  5875  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
,11-03 13:34:43.809  5875  5875 D BluetoothMapService: Received start request. Starting profile...
11-03 13:34:43.809  5875  5875 D BluetoothMapService: start()
,11-03 13:34:43.811  5875  5875 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-03 13:34:43.812  5875  5875 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 13:34:43.812  5875  5875 D BluetoothMapAppObserver: createReceiver()
,11-03 13:34:43.813  5875  5875 D BluetoothMapAppObserver: initObservers()
11-03 13:34:43.813  5875  5875 D BluetoothMapAppObserver: getEnabledAccountItems()
11-03 13:34:43.818  5875  5875 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:43.818  5875  5875 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:43.818  5875  5875 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:43.818  5875  5909 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 13:34:43.818  5875  5875 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:43.819  5875  5875 V SapService: SapBinder()
11-03 13:34:43.819  5875  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
,11-03 13:34:43.820  5875  5875 D SapService: Received start request. Starting profile...
11-03 13:34:43.820  5875  5875 V SapService: start()
,11-03 13:34:43.821  5875  5875 V BluetoothAdapterState: isTurningOff()=false
,11-03 13:34:43.821  5875  5875 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:43.821  5875  5875 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:43.821  5875  5875 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:43.821  5875  5875 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:43.821  5875  5875 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:43.821  5875  5875 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:43.822  5875  5875 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:43.822  5875  5875 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:43.822  5875  5875 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:43.822  5875  5875 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:43.822  5875  5875 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 13:34:43.822  5875  5875 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:43.822  5875  5875 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:43.822  5875  5875 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:43.822  5875  5875 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:43.823  5875  5875 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:43.823  5875  5875 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:43.823  5875  5875 V BluetoothAdapterState: isBleTurningOn()=false
11-03 13:34:43.823  5875  5875 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:43.823  5875  5875 V BluetoothAdapterState: isTurningOff()=false
11-03 13:34:43.823  5875  5875 V BluetoothAdapterState: isTurningOn()=true
11-03 13:34:43.823  5875  5875 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 13:34:43.823  5875  5875 V BluetoothAdapterState: isBleTurningOff()=false
11-03 13:34:43.824  5875  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 13:34:43.824  5875  5889 D BluetoothAdapterProperties: ScanMode =  20
11-03 13:34:43.824  5875  5889 D BluetoothAdapterProperties: State =  11
11-03 13:34:43.824  5875  5889 D BluetoothAdapterProperties: Setting state to 12
11-03 13:34:43.824  5875  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 13:34:43.825  5875  5893 D BluetoothAdapterProperties: Scan Mode:21
11-03 13:34:43.825  3799  3828 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 13:34:43.825  5875  5893 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-03 13:34:43.825  3193  5650 D BluetoothPan: onBluetoothStateChange on: true
11-03 13:34:43.827  5875  5889 I BluetoothAdapterState: Entering OnState
,11-03 13:34:43.828  5710  5721 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 13:34:43.829  3193  3193 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 13:34:43.829  3193  3193 D PanProfile: Bluetooth service connected
,11-03 13:34:43.830  5710  5722 D BluetoothPan: onBluetoothStateChange on: true
11-03 13:34:43.832  3193  3205 D BluetoothMap: onBluetoothStateChange: up=true
,11-03 13:34:43.834  5710  5721 D BluetoothMap: onBluetoothStateChange: up=true
11-03 13:34:43.835  3193  3193 D BluetoothMap: Proxy object connected
,11-03 13:34:43.835  3193  3193 D MapProfile: Bluetooth service connected
11-03 13:34:43.835  3193  3193 D BluetoothMap: getConnectedDevices()
11-03 13:34:43.835  3193  5650 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 13:34:43.837  3193  4022 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 13:34:43.837  5710  5710 D BluetoothInputDevice: Proxy object connected
11-03 13:34:43.837  3193  3193 D BluetoothInputDevice: Proxy object connected
11-03 13:34:43.837  5710  5710 D HidProfile: Bluetooth service connected
11-03 13:34:43.837  3193  3193 D HidProfile: Bluetooth service connected
11-03 13:34:43.837   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 13:34:43.838  3193  3204 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 13:34:43.838  5710  5710 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 13:34:43.838  5710  5710 D PanProfile: Bluetooth service connected
11-03 13:34:43.838  5710  5710 D BluetoothMap: Proxy object connected
11-03 13:34:43.839  5710  5710 D MapProfile: Bluetooth service connected
11-03 13:34:43.839  5710  5710 D BluetoothMap: getConnectedDevices()
11-03 13:34:43.839  5875  5875 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 13:34:43.839   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 13:34:43.839   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 13:34:43.839  5875  5875 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 13:34:43.839  5710  5722 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 13:34:43.841  5875  5875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 13:34:43.842  3193  5650 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 13:34:43.843  5875  5875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 13:34:43.844  5710  5869 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 13:34:43.844  5710  5721 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 13:34:43.844  5875  5875 D ObexServerSockets: Succeed to create listening sockets 
,11-03 13:34:43.845  5875  5875 D ObexServerSockets0: startAccept()
11-03 13:34:43.845  5875  5875 D ObexServerSockets0: prepareForNewConnect()
11-03 13:34:43.845   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 13:34:43.846  5875  5875 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 13:34:43.846  5875  5875 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-03 13:34:43.847  5875  5918 D ObexServerSockets0: Accepting socket connection...
11-03 13:34:43.847  5875  5919 D ObexServerSockets0: Accepting socket connection...
11-03 13:34:43.848  3193  3193 D BluetoothA2dp: Proxy object connected
11-03 13:34:43.848  5875  5875 D BluetoothMapService: onReceive
,11-03 13:34:43.848  5875  5875 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 13:34:43.848   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 13:34:43.848  5875  5875 D BluetoothMapService: STATE_ON
11-03 13:34:43.848   930   930 D BluetoothA2dp: Proxy object connected
,11-03 13:34:43.853  5875  5921 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 13:34:43.854  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 13:34:43.854  5875  5921 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 13:34:43.854  5875  5921 D BluetoothSdpJni: SDP Create record success - handle: 1
11-03 13:34:43.856  5710  5710 D BluetoothA2dp: Proxy object connected
,11-03 13:34:43.860  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 13:34:43.864  5710  5710 D DockEventReceiver: finishStartingService: stopping service
,11-03 13:34:43.868  5710  5710 D BluetoothPbap: Proxy object connected
,11-03 13:34:43.868  5710  5710 D PbapServerProfile: Bluetooth service connected
,11-03 13:34:43.874  5875  5875 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 13:34:43.874  5875  5875 D ObexServerSockets0: prepareForNewConnect()
11-03 13:34:43.877  5875  5926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 13:34:43.879  3193  3193 D BluetoothPbap: Proxy object connected
11-03 13:34:43.879  3193  3193 D PbapServerProfile: Bluetooth service connected
,11-03 13:34:43.891  5875  5930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 13:34:43.892  5875  5930 I BtOppRfcommListener: Accept thread started.
,11-03 13:34:43.927   930   930 D BluetoothHeadset: Proxy object connected
,11-03 13:34:43.927  3799  4030 D BluetoothHeadset: Proxy object connected
,11-03 13:34:43.928  5710  5869 D BluetoothHeadset: Proxy object connected
11-03 13:34:43.928   930   930 D BluetoothHeadset: Proxy object connected
,11-03 13:34:43.929  3193  4022 D BluetoothHeadset: Proxy object connected
,11-03 13:34:43.929  3193  3193 D HeadsetProfile: Bluetooth service connected
11-03 13:34:43.929   930   930 D BluetoothHeadset: Proxy object connected
11-03 13:34:43.931  5710  5710 D HeadsetProfile: Bluetooth service connected
,11-03 13:34:43.938  3193  3205 D BluetoothHeadset: Proxy object connected
,11-03 13:34:43.938  3193  3193 D HeadsetProfile: Bluetooth service connected
,11-03 13:34:43.940   930   947 D BluetoothHeadset: Proxy object connected
,11-03 13:34:43.940   930   947 D BluetoothHeadset: Proxy object connected
,11-03 13:34:43.944  5710  5721 D BluetoothHeadset: Proxy object connected
,11-03 13:34:43.944  5710  5710 D HeadsetProfile: Bluetooth service connected
11-03 13:34:43.946   930   947 D BluetoothHeadset: Proxy object connected
,11-03 13:34:46.733  3879  4487 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-03 13:34:47.070  4077  5932 I EventLogService: Aggregate from 1478174677599 (log), 1478174677599 (data)
,11-03 13:34:47.635  5651  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:47.635  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:47.635  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:47.635  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 13:34:47.635  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 13:34:47.635  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 13:34:47.635  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 13:34:47.635  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 13:34:47.640  5651  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 13:34:47.641  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:47.641  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5917baa removed from the list
,11-03 13:34:47.641  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:47.642  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 13:34:47.642  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6801338 added. We now have 4 listener(s)
11-03 13:34:47.642  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:47.644   930   940 D WifiService: setWifiEnabled: false pid=5651, uid=10077
,11-03 13:34:47.645   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 13:34:52.654  5651  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 13:34:52.655   930  3822 D WifiService: setWifiEnabled: true pid=5651, uid=10077
11-03 13:34:52.655   930  3822 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 13:34:52.668   509   923 D SoftapController: Softap fwReload - Ok
,11-03 13:34:52.673   509   923 D CommandListener: Setting iface cfg
,11-03 13:34:52.673   509   923 D CommandListener: Trying to bring down wlan0
,11-03 13:34:52.675   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-03 13:34:52.680   930  3017 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 13:34:52.941   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:53.366   930  3017 D wifi    : set interface wlan0 flags (UP)
11-03 13:34:53.367   930  3017 I WifiHAL : Initializing wifi
11-03 13:34:53.367   930  3017 I WifiHAL : Creating socket
,11-03 13:34:53.374   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 13:34:53.375   930  3017 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 13:34:53.375   930  3017 D wifi    : Did set static halHandle = 0x7f59b21b80
11-03 13:34:53.375   930  3017 D wifi    : halHandle = 0x7f59b21b80, mVM = 0x7f7618d140, mCls = 0x141a
,11-03 13:34:53.375   930  3017 D wifi    : array field set
11-03 13:34:53.376   930  3017 I WifiNative-HAL: interface[0] = wlan0
,11-03 13:34:53.378   930  5937 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546965691264
11-03 13:34:53.379   930  5937 D wifi    : waitForHalEvents called, vm = 0x7f7618d140, obj = 0x141a, env = 0x7f6c3a22c0
,11-03 13:34:53.428  5938  5938 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 13:34:53.480   930  3017 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 13:34:53.497  5938  5938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 13:34:53.556  5938  5938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-03 13:34:53.556  5938  5938 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 13:34:53.577   930  3017 D WifiConfigStore: Loading config and enabling all networks 
,11-03 13:34:53.599   930  3017 D WifiConfigStore: loaded 0 passpoint configs
,11-03 13:34:53.601   930  3017 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 13:34:53.602   930  3017 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-03 13:34:53.603   930  3017 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-03 13:34:53.604   930  3017 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-03 13:34:53.604   930  3017 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 13:34:53.606   930  3017 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-03 13:34:53.606   930  3017 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 13:34:53.606   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 13:34:53.606   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 13:34:53.607   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-03 13:34:53.607   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 13:34:53.607   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 13:34:53.611   930  3017 D WifiNative-HAL: Setting external_sim to 1
,11-03 13:34:53.612  4565  4565 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 13:34:53.612   930  3017 D wifi    : setting dfs flag to true, 0x7f5ca6c060
11-03 13:34:53.612   930  3017 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 13:34:53.612   930  3017 D wifi    : setting scan oui 0x7f5ca6c060
11-03 13:34:53.613   930  3017 D WifiHAL : Sending mac address OUI
,11-03 13:34:53.617   930  3017 E native  : do suspend true
,11-03 13:34:53.626   930  3017 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-03 13:34:53.627   930   930 D RttService: SCAN_AVAILABLE : 3
11-03 13:34:53.627   930  3129 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 13:34:53.642   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 13:34:53.644   509   923 D CommandListener: Setting iface cfg
,11-03 13:34:53.650   930  3000 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,11-03 13:34:53.650   930  3000 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 13:34:53.659   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164172 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
11-03 13:34:53.660   930  3000 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 13:34:53.660   930  3000 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 13:34:53.943   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:54.944   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:55.946   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:56.798  5938  5938 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 13:34:56.826   930  3017 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 13:34:56.828   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
11-03 13:34:56.828   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 13:34:56.842   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 13:34:56.891   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 13:34:56.947   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:34:57.234  5938  5938 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 13:34:57.266  5938  5938 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 13:34:57.267  5938  5938 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 13:34:57.277   930  3017 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 13:34:57.277   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 13:34:57.277   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 13:34:57.295   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 13:34:57.308   509   923 D CommandListener: Setting iface cfg
,11-03 13:34:57.315   930  3017 D WifiStateMachine: Start Dhcp Watchdog 3
,11-03 13:34:57.319   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 13:34:57.324   930  5943 D DhcpClient: Receive thread started
,11-03 13:34:57.407   930  3017 E native  : do suspend false
,11-03 13:34:57.419   930  5942 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 13:34:57.434   930  5943 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-03 13:34:57.434   930  5942 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-03 13:34:57.436   930  5942 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 13:34:57.460   930  5943 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 13:34:57.461   930  5942 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-03 13:34:57.463   509   923 D CommandListener: Setting iface cfg
,11-03 13:34:57.467   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 13:34:57.472   930  3017 E native  : do suspend true
11-03 13:34:57.472   930  5942 D DhcpClient: Scheduling renewal in 86399s
,11-03 13:34:57.489   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-03 13:34:57.490   930  3017 D WifiConfigStore: No blacklist allowed without epno enabled
,11-03 13:34:57.490   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-03 13:34:57.491   930  3017 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-03 13:34:57.493   930  3026 D ConnectivityService: Adding iface wlan0 to network 102
,11-03 13:34:57.530   930  3026 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-03 13:34:57.530   930  3026 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-03 13:34:57.532   930  3026 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-03 13:34:57.534   930  3026 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-03 13:34:57.536   930  3026 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-03 13:34:57.542   930  3026 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 13:34:57.547   930  3026 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-03 13:34:57.547   930  3026 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-03 13:34:57.547   930  3026 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-03 13:34:57.547   930  3026 D ConnectivityService:    accepting network in place of null
11-03 13:34:57.547   930  3017 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 13:34:57.547   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 13:34:57.548   930  3026 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 13:34:57.558   930  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168071, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 13:34:57.572   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 13:34:57.592   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 13:34:57.597   930  3026 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-03 13:34:57.597   930  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 13:34:57.597  3769  3918 W QCNEJ   : |CORE| network available: 102
,11-03 13:34:57.598   930  3026 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-03 13:34:57.600   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-03 13:34:57.602  3769  3918 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-03 13:34:57.603  3769  3918 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 13:34:57.604  3769  3918 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-03 13:34:57.612  3997  3997 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-03 13:34:57.614  4077  4077 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 13:34:57.618  4077  4077 D SystemUpdateService: onCreate
11-03 13:34:57.621  4077  4077 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 13:34:57.633  4077  4077 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-03 13:34:57.638   930  5940 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 13:34:57.639  4077  4296 I iu.UploadsManager: num queued entries: 0
,11-03 13:34:57.640  4077  5952 I SystemUpdateService: active receiver: enabled
,11-03 13:34:57.643  4077  4077 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 13:34:57.644  4077  4077 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-03 13:34:57.646  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 13:34:57.651  5748  5748 D SprintDMHelper: simOperator: 
,11-03 13:34:57.651  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 13:34:57.663  4077  4296 I iu.UploadsManager: num updated entries: 0
,11-03 13:34:57.665  4077  5952 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 13:34:57.670  5651  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 13:34:57.670  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 13:34:57.670  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 13:34:57.670  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 13:34:57.670  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 13:34:57.670  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 13:34:57.670  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 13:34:57.670  5651  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 13:34:57.672  5651  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 13:34:57.672  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.672  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6801338 removed from the list
11-03 13:34:57.672  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:57.676  5651  5699 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-03 13:34:57.677  5651  5699 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-03 13:34:57.678  4077  4296 I iu.SyncManager: NEXT; no task
,11-03 13:34:57.680  5651  5699 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2bffaa Bundle[{}]
,11-03 13:34:57.680  5651  5699 I io.jxcore.node.LifeCycleMonitor: start: OK
11-03 13:34:57.680  5651  5699 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-03 13:34:57.681  5651  5699 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-03 13:34:57.681  5651  5699 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-03 13:34:57.682  5651  5699 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-03 13:34:57.682  5651  5699 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 13:34:57.684  4077  5952 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-03 13:34:57.684  4077  5952 I SystemUpdateService: now status is 0 (complete)
11-03 13:34:57.684  4077  5952 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 13:34:57.684  4077  5952 I SystemUpdateService: file has been verified
11-03 13:34:57.684  4077  5952 I SystemUpdateService: OTA package size = 21989297
,11-03 13:34:57.689  5651  5699 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-03 13:34:57.690  5651  5699 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-03 13:34:57.690  5651  5699 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-03 13:34:57.690  4077  5952 I SystemUpdateService: showing system update notification
11-03 13:34:57.690   930  5940 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 12:34:57 GMT], X-Android-Received-Millis=[1478176497689], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478176497663]}
,11-03 13:34:57.691   930  3026 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 13:34:57.691   930  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-03 13:34:57.691   930  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-03 13:34:57.691  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 13:34:57.692  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb36f11 added. We now have 3 listener(s)
11-03 13:34:57.692   930  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-03 13:34:57.693  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 13:34:57.693  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 13:34:57.693  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 13:34:57.694  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:57.694  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@363a876 added. We now have 4 listener(s)
11-03 13:34:57.694  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:57.694  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 13:34:57.696  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 13:34:57.696  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6de77 added. We now have 4 listener(s)
,11-03 13:34:57.698  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 13:34:57.698  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 13:34:57.698  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 13:34:57.698  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:57.698  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf2ae4 added. We now have 5 listener(s)
11-03 13:34:57.698  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:57.698  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:34:57.699  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:57.699  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:57.699  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:57.699  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:57.699  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 13:34:57.699  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb36f11 removed from the list
11-03 13:34:57.699  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.699  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@363a876 removed from the list
11-03 13:34:57.699  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 13:34:57.699  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.701   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 13:34:57.701  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.701  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.701  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.701  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:57.701  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:57.701  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.701  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@363a876 not in the list
11-03 13:34:57.701  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.702  4077  4077 D SystemUpdateService: onDestroy
,11-03 13:34:57.704  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.704  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.704  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.704  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:57.704  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:57.704  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.705  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf2ae4 removed from the list
11-03 13:34:57.705  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:57.705  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:57.705  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-03 13:34:57.705  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6de77 removed from the list
11-03 13:34:57.705  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 13:34:57.705  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dceeb4d added. We now have 3 listener(s)
11-03 13:34:57.706  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 13:34:57.706  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 13:34:57.707  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 13:34:57.707  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:57.707  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@759d602 added. We now have 4 listener(s)
11-03 13:34:57.707  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:57.707  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 13:34:57.708  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 13:34:57.708  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@800eb13 added. We now have 4 listener(s)
11-03 13:34:57.709  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 13:34:57.709  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 13:34:57.709  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 13:34:57.709  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:57.709  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b61150 added. We now have 5 listener(s)
11-03 13:34:57.709  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:57.709  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:34:57.709  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 13:34:57.709  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-03 13:34:57.710  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 13:34:57.710  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 13:34:57.711  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 13:34:57.713  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 13:34:57.714  5651  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 13:34:57.714  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 13:34:57.716  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.716  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 13:34:57.717  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 13:34:57.717  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 13:34:57.717  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 13:34:57.721  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.721  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 13:34:57.721  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 13:34:57.721  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 13:34:57.721  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 13:34:57.721  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.722  5651  5699 D BluetoothAdapter: STATE_ON
,11-03 13:34:57.725  5875  5922 D BtGatt.GattService: registerClient() - UUID=8fc59bc2-5a2b-466e-af46-e3e1696e490a
,11-03 13:34:57.725  5875  5893 D BtGatt.GattService: onClientRegistered() - UUID=8fc59bc2-5a2b-466e-af46-e3e1696e490a, clientIf=5
,11-03 13:34:57.726  5651  5692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 13:34:57.726  5875  5910 D BtGatt.GattService: start scan with filters
,11-03 13:34:57.729  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 13:34:57.729  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.729  5875  5896 D BtGatt.ScanManager: handling starting scan
11-03 13:34:57.729  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 13:34:57.729  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.729  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 13:34:57.729  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 13:34:57.730  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.730  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 13:34:57.730  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 13:34:57.730  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.730  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.730  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 13:34:57.730  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 13:34:57.731  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.731  5875  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@188927f
11-03 13:34:57.733  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.733  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 13:34:57.733  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.733  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.733  5651  5699 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 13:34:57.733  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.733  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:57.733  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 13:34:57.733  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:34:57.733  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 13:34:57.733  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:57.733  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 13:34:57.736  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 13:34:57.736  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.736  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.736  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.736  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 13:34:57.736  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 13:34:57.736  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 13:34:57.736  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 13:34:57.736  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.736  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.736  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.736  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 13:34:57.736  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.737  5651  5699 D BluetoothAdapter: STATE_ON
,11-03 13:34:57.737  5875  5885 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 13:34:57.737  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 13:34:57.738  5875  5893 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 13:34:57.738  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.738  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:34:57.738  5875  5910 D BtGatt.GattService: stopScan() - queue size =1
11-03 13:34:57.738  5875  5896 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 13:34:57.739  5875  5886 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 13:34:57.739  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-03 13:34:57.739  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.739  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 13:34:57.739  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.739  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.739  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.740  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.740  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 13:34:57.740  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.740  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.740  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.740  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 13:34:57.740  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 13:34:57.740  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 13:34:57.741  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.742  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.742  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:34:57.742  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.742  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.742  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:34:57.742  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:34:57.743  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 13:34:57.743  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-03 13:34:57.743  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 13:34:57.743  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 13:34:57.743  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.743  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.743  5875  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 13:34:57.743  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.743  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 13:34:57.744  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.744  5875  5896 D BtGatt.ScanManager: Starting BLE batch scan
11-03 13:34:57.744  5875  5896 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 13:34:57.745  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 13:34:57.745  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:57.745  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:57.745  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:57.745  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:57.745  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 13:34:57.745  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dceeb4d removed from the list
11-03 13:34:57.745  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.745  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@759d602 removed from the list
11-03 13:34:57.745  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:57.745  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.746  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.746  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.746  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.746  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:57.746  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:57.746  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.746  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.746  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btco,nnectorlib.DiscoveryManager@759d602 not in the list
11-03 13:34:57.746  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.746  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.746  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.746  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.746  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:34:57.747  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.747  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.747  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.747  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:57.747  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:57.747  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.748  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b61150 removed from the list
11-03 13:34:57.748  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:57.748  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 13:34:57.748  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 13:34:57.748  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@800eb13 removed from the list
11-03 13:34:57.748  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 13:34:57.748  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83b3705 added. We now have 3 listener(s)
11-03 13:34:57.749  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 13:34:57.749  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 13:34:57.750  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 13:34:57.750  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:57.750  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed8235a added. We now have 4 listener(s)
11-03 13:34:57.750  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:57.750  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 13:34:57.751  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 13:34:57.751  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68a98b added. We now have 4 listener(s)
11-03 13:34:57.752  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 13:34:57.752  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 13:34:57.752  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 13:34:57.752  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:57.753  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2baba68 added. We now have 5 listener(s)
,11-03 13:34:57.753  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:57.753  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:34:57.753  5875  5893 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 13:34:57.753  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.753  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:34:57.753  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 13:34:57.753  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 13:34:57.753  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 13:34:57.754  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 13:34:57.755  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 13:34:57.757  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 13:34:57.757  5651  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 13:34:57.757  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 13:34:57.758  5875  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 13:34:57.758  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:34:57.759  5875  5896 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 13:34:57.760  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.760  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 13:34:57.760  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 13:34:57.760  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 13:34:57.760  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 13:34:57.763  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.763  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 13:34:57.763  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 13:34:57.763  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-03 13:34:57.763  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 13:34:57.763  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.764  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:34:57.764  5875  5893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 13:34:57.764  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.765  5875  5893 E BtGatt.ContextMap: Context not found for ID 5
11-03 13:34:57.765  5875  5910 D BtGatt.GattService: registerClient() - UUID=f8148138-9c3b-4254-9572-71496cc8c8b0
11-03 13:34:57.766  5875  5893 D BtGatt.GattService: onClientRegistered() - UUID=f8148138-9c3b-4254-9572-71496cc8c8b0, clientIf=5
11-03 13:34:57.766  5651  5692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 13:34:57.766  5875  5886 D BtGatt.GattService: start scan with filters
,11-03 13:34:57.768  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 13:34:57.768  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.768  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 13:34:57.768  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.768  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 13:34:57.769  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 13:34:57.769  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.769  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 13:34:57.769  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 13:34:57.769  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.769  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.769  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 13:34:57.770  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 13:34:57.770  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.771  5875  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 13:34:57.771  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.771  5875  5896 D BtGatt.ScanManager: stopping BLe Batch
11-03 13:34:57.771  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.771  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 13:34:57.772  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.772  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.772  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.772  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:34:57.772  5651  5699 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 13:34:57.772  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:34:57.772  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:57.772  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:57.772  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:57.772  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:34:57.772  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 13:34:57.772  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:57.772  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 13:34:57.772  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83b3705 removed from the list
,11-03 13:34:57.772  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.772  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed8235a removed from the list
11-03 13:34:57.772  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:57.772  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:34:57.772  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 13:34:57.772  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-03 13:34:57.773  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-03 13:34:57.773  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:34:57.773  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 13:34:57.773  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.774  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.774  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.774  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 13:34:57.774  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.774  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.774  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:57.774  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.774  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:57.774  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.774  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.774  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed8235a not in the list
11-03 13:34:57.774  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 13:34:57.774  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-03 13:34:57.774  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 13:34:57.774  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 13:34:57.774  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.774  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.774  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.774  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 13:34:57.774  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.775  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:34:57.775  5875  5886 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-03 13:34:57.776  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 13:34:57.776  5875  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 13:34:57.776  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.776  5875  5896 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 13:34:57.776  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:34:57.777  5875  5922 D BtGatt.GattService: stopScan() - queue size =0
11-03 13:34:57.777  5875  5885 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 13:34:57.777  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.778  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 13:34:57.778  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-03 13:34:57.779  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 13:34:57.779  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.780  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.780  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:34:57.780  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.780  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.780  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:57.780  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:57.780  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:57.780  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:34:57.780  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2baba68 removed from the list
11-03 13:34:57.780  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:57.780  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 13:34:57.780  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:57.781  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 13:34:57.781  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 13:34:57.781  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-03 13:34:57.781  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68a98b removed from the list
11-03 13:34:57.781  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-03 13:34:57.781  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 13:34:57.781  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.781  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.781  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 13:34:57.781  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.781  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 13:34:57.781  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfe41bd added. We now have 3 listener(s)
11-03 13:34:57.782  5875  5893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 13:34:57.782  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.782  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.782  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.782  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.782  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-03 13:34:57.782  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:34:57.782  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 13:34:57.782  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 13:34:57.782  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 13:34:57.782  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:57.782  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@877c3b2 added. We now have 4 listener(s)
11-03 13:34:57.783  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 13:34:57.783  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 13:34:57.784  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 13:34:57.784  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64abf03 added. We now have 4 listener(s)
11-03 13:34:57.785  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 13:34:57.785  5875  5896 D BtGatt.ScanManager: handling starting scan
11-03 13:34:57.785  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 13:34:57.785  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 13:34:57.785  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:57.785  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3586e80 added. We now have 5 listener(s)
11-03 13:34:57.785  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:57.785  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:34:57.785  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-03 13:34:57.785  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 13:34:57.785  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 13:34:57.785  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 13:34:57.787  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 13:34:57.789  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 13:34:57.789  5651  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-03 13:34:57.789  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 13:34:57.792  5875  5893 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 13:34:57.792  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.792  5875  5896 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 13:34:57.794  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.794  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 13:34:57.795  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-03 13:34:57.795  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 13:34:57.795  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 13:34:57.797  5875  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 13:34:57.797  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.797  5875  5896 D BtGatt.ScanManager: Starting BLE batch scan
11-03 13:34:57.797  5875  5896 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 13:34:57.803  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.803  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-03 13:34:57.804  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 13:34:57.804  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 13:34:57.804  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 13:34:57.804  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.804  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:34:57.804  5875  5893 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 13:34:57.804  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:34:57.806  5875  5886 D BtGatt.GattService: registerClient() - UUID=760c1f64-02fe-4e85-b932-17b288a24171
11-03 13:34:57.806  5875  5893 D BtGatt.GattService: onClientRegistered() - UUID=760c1f64-02fe-4e85-b932-17b288a24171, clientIf=5
,11-03 13:34:57.807  5651  5692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 13:34:57.807  5875  5885 D BtGatt.GattService: start scan with filters
,11-03 13:34:57.809  5875  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 13:34:57.809  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:34:57.810  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 13:34:57.810  5875  5896 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 13:34:57.810  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.810  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-03 13:34:57.810  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.810  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 13:34:57.810  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 13:34:57.810  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.810  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 13:34:57.810  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 13:34:57.810  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.810  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.811  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-03 13:34:57.812  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 13:34:57.812  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.814  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.814  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 13:34:57.814  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.814  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.814  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.814  5875  5893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 13:34:57.814  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:34:57.816  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:34:57.816  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:57.816  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:57.816  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:57.816  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:34:57.816  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 13:34:57.816  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 13:34:57.816  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 13:34:57.816  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfe41bd removed from the list
11-03 13:34:57.816  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.817  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@877c3b2 removed from the list
11-03 13:34:57.817  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-03 13:34:57.817  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:34:57.817  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 13:34:57.817  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-03 13:34:57.817  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-03 13:34:57.817  5651  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 13:34:57.817  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 13:34:57.817  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.817  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.817  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.817  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.817  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.817  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 13:34:57.817  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.818  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.818  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.818  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.818  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:57.818  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:57.818  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 13:34:57.818  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@877c3b2 not in the list
11-03 13:34:57.818  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 13:34:57.818  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 13:34:57.818  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 13:34:57.818  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.818  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.818  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.818  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 13:34:57.818  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.819  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:34:57.820  5875  5885 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 13:34:57.820  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 13:34:57.820  5875  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 13:34:57.820  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.820  5875  5896 D BtGatt.ScanManager: stopping BLe Batch
11-03 13:34:57.820  5651  5699 D BluetoothAdapter: STATE_ON
11-03 13:34:57.821  5875  5920 D BtGatt.GattService: stopScan() - queue size =0
,11-03 13:34:57.822  5875  5922 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 13:34:57.822  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 13:34:57.822  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.822  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 13:34:57.822  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.823  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.823  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.823  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.823  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 13:34:57.823  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.823  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.823  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.823  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 13:34:57.823  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 13:34:57.824  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 13:34:57.824  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.824  5875  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 13:34:57.824  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.824  5875  5896 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 13:34:57.825  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.825  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:34:57.825  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.825  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.825  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:57.825  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:57.825  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.825  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:34:57.826  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3586e80 removed from the list
11-03 13:34:57.826  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 13:34:57.826  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 13:34:57.826  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:57.826  5651  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 13:34:57.826  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 13:34:57.826  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.826  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64abf03 removed from the list
11-03 13:34:57.826  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 13:34:57.826  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 13:34:57.826  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-03 13:34:57.826  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.826  5651  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 13:34:57.826  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.826  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 13:34:57.826  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@750eb75 added. We now have 3 listener(s)
11-03 13:34:57.827  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.827  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.827  5651  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.827  5651  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 13:34:57.827  5651  5651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 13:34:57.827  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 13:34:57.828  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 13:34:57.828  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 13:34:57.828  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:57.828  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b0170a added. We now have 4 listener(s)
11-03 13:34:57.828  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:57.828  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 13:34:57.828  5875  5893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 13:34:57.828  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.829  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 13:34:57.829  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbb0b7b added. We now have 4 listener(s)
11-03 13:34:57.830  5875  5896 D BtGatt.ScanManager: handling starting scan
11-03 13:34:57.831  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 13:34:57.831  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 13:34:57.831  5651  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 13:34:57.831  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 13:34:57.831  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8458d98 added. We now have 5 listener(s)
11-03 13:34:57.831  5651  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 13:34:57.831  5651  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 13:34:57.831  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:57.831  5651  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 13:34:57.831  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:57.831  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:57.831  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 13:34:57.831  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@750eb75 removed from the list
11-03 13:34:57.831  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.831  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b0170a removed from the list
11-03 13:34:57.831  5651  5699 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 13:34:57.832  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.833  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.834  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.834  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.834  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:57.834  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:57.834  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.834  5651  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b0170a not in the list
11-03 13:34:57.834  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.835  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 13:34:57.835  5875  5893 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 13:34:57.835  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.835  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.835  5651  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 13:34:57.835  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 13:34:57.835  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 13:34:57.835  5651  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 13:34:57.835  5875  5896 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 13:34:57.835  5651  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8458d98 removed from the list
,11-03 13:34:57.835  5651  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 13:34:57.835  5651  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 13:34:57.835  5651  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 13:34:57.835  5651  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbb0b7b removed from the list
11-03 13:34:57.836  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-03 13:34:57.836  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 13:34:57.836  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-03 13:34:57.836  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:34:57.836  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,11-03 13:34:57.836  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 13:34:57.839  5875  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 13:34:57.839  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.839  5875  5896 D BtGatt.ScanManager: Starting BLE batch scan
11-03 13:34:57.839  5875  5896 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 13:34:57.847  5875  5893 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-03 13:34:57.847  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:34:57.851  5875  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-03 13:34:57.851  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:34:57.852  5875  5896 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 13:34:57.856  5875  5893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 13:34:57.856  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.857  5875  5893 E BtGatt.ContextMap: Context not found for ID 5
,11-03 13:34:57.861  5875  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 13:34:57.861  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.862  5875  5896 D BtGatt.ScanManager: stopping BLe Batch
,11-03 13:34:57.866  5875  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 13:34:57.866  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 13:34:57.866  5875  5896 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 13:34:57.870  5875  5893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 13:34:57.870  5875  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 13:34:57.947   593   593 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 13:34:58.247  5651  5651 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 13:34:58.283  5651  5651 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 13:34:58.328  5651  5651 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 13:34:59.988  5651  5960 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 13:34:59.988  5651  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 13:35:00.796  5651  5960 W !!      : call onHalfStreamCopied
,11-03 13:35:00.796  5651  5960 I testCopyDataAndClose: closing input stream
,11-03 13:35:01.047  3637  5962 I VacuumService: Vacuum at: now=1478176501047 tag=VacuumService
,11-03 13:35:01.070  3637  5965 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-03 13:35:01.112  3637  5963 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-03 13:35:01.115  3637  5963 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-03 13:35:01.136  3637  5963 W Uploader:  no longer exists, so no auth token.
,11-03 13:35:01.142  3637  5965 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 13:35:01.474  3637  5967 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 13:35:01.558  5651  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 13:35:01.614  3637  5965 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 13:35:01.678  3637  5963 W Uploader:  no longer exists, so no auth token.
,11-03 13:35:01.684  3637  5967 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 13:35:01.759  3637  5965 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 13:35:01.844  3637  5967 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 13:35:05.555   930  3026 D ConnectivityService: handlePromptUnvalidated 102
,11-03 13:35:05.772  5651  5972 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-03 13:35:05.772  5651  5972 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 13:35:07.772  5651  5699 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-03 13:35:07.772  5651  5699 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 13:35:07.773  5651  5699 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-03 13:35:07.800  5651  5972 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-03 13:35:07.801  5651  5972 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-03 13:35:07.801  5651  5972 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-03 13:35:07.926  5651  5973 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 13:35:07.926  5651  5973 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 13:35:09.543  5651  5973 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 13:35:09.543  5651  5973 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 13:35:09.543  5651  5973 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 13:35:09.543  5651  5973 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 13:35:09.543  5651  5973 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 13:35:09.544  5651  5973 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 13:35:09.544  5651  5973 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-03 13:35:09.544  5651  5973 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 13:35:09.544  5651  5973 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 13:35:09.544  5651  5973 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 13:35:09.544  5651  5973 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 13:35:13.902  5651  5974 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-03 13:35:13.902  5651  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 13:35:13.903  5651  5974 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-03 13:35:13.903  5651  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 13:35:13.903  5651  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 13:35:13.903  5651  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 13:35:13.903  5651  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 13:35:13.903  5651  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 13:35:13.904  5651  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 13:35:13.904  5651  5974 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 13:35:13.904  5651  5974 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 13:35:13.904  5651  5974 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-03 13:35:13.904  5651  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-03 13:35:13.906  5651  5699 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-03 13:35:13.909  5651  5975 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-03 13:35:13.909  5651  5975 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 13:35:13.909  5651  5975 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,11-03 13:35:13.910  5651  5975 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-03 13:35:13.910  5651  5975 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-03 13:35:13.910  5651  5975 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-03 13:35:13.910  5651  5975 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-03 13:35:13.910  5651  5975 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-03 13:35:13.915  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-03 13:35:13.915  5651  5699 I jxcore-log: 
,11-03 13:35:13.915  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-03 13:35:13.915  5651  5699 I jxcore-log: 
11-03 13:35:13.916  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-03 13:35:13.916  5651  5699 I jxcore-log: 
11-03 13:35:13.916  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-03 13:35:13.916  5651  5699 I jxcore-log: 
11-03 13:35:13.916  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG UnitTest_app: 'Total duration:  91832'
11-03 13:35:13.916  5651  5699 I jxcore-log: 
,11-03 13:35:13.919  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-03 13:35:13.919  5651  5699 I jxcore-log: 
,11-03 13:35:13.924  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 13:35:13.924  5651  5699 I jxcore-log: 
,11-03 13:35:13.925  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 13:35:13.925  5651  5699 I jxcore-log: 
,11-03 13:35:13.926  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 13:35:13.926  5651  5699 I jxcore-log: 
11-03 13:35:13.926  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-03 13:35:13.926  5651  5699 I jxcore-log: 
11-03 13:35:13.927  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 13:35:13.927  5651  5699 I jxcore-log: 
11-03 13:35:13.927  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 13:35:13.927  5651  5699 I jxcore-log: 
,11-03 13:35:13.927  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 13:35:13.927  5651  5699 I jxcore-log: 
11-03 13:35:13.927  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 13:35:13.927  5651  5699 I jxcore-log: 
11-03 13:35:13.928  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 13:35:13.928  5651  5699 I jxcore-log: 
11-03 13:35:13.928  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 13:35:13.928  5651  5699 I jxcore-log: 
,11-03 13:35:13.928  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-03 13:35:13.928  5651  5699 I jxcore-log: 
11-03 13:35:13.928  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 13:35:13.928  5651  5699 I jxcore-log: 
11-03 13:35:13.929  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 13:35:13.929  5651  5699 I jxcore-log: 
11-03 13:35:13.929  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 13:35:13.929  5651  5699 I jxcore-log: 
11-03 13:35:13.929  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 13:35:13.929  5651  5699 I jxcore-log: 
,11-03 13:35:13.929  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 13:35:13.929  5651  5699 I jxcore-log: 
11-03 13:35:13.929  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 13:35:13.929  5651  5699 I jxcore-log: 
11-03 13:35:13.930  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 13:35:13.930  5651  5699 I jxcore-log: 
11-03 13:35:13.930  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 13:35:13.930  5651  5699 I jxcore-log: 
11-03 13:35:13.930  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 13:35:13.930  5651  5699 I jxcore-log: 
11-03 13:35:13.930  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 13:35:13.930  5651  5699 I jxcore-log: 
,11-03 13:35:13.931  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 13:35:13.931  5651  5699 I jxcore-log: 
11-03 13:35:13.931  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 13:35:13.931  5651  5699 I jxcore-log: 
11-03 13:35:13.931  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 13:35:13.931  5651  5699 I jxcore-log: 
11-03 13:35:13.933  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 13:35:13.933  5651  5699 I jxcore-log: 
11-03 13:35:13.933  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 13:35:13.933  5651  5699 I jxcore-log: 
,11-03 13:35:13.933  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 13:35:13.933  5651  5699 I jxcore-log: 
11-03 13:35:13.934  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 13:35:13.934  5651  5699 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-03 13:35:13.934  5651  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 13:35:13.934  5651  5699 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,11-03 13:35:13.934  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 13:35:13.934  5651  5699 I jxcore-log: 
11-03 13:35:13.934  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 13:35:13.934  5651  5699 I jxcore-log: 
11-03 13:35:13.934  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 13:35:13.934  5651  5699 I jxcore-log: 
11-03 13:35:13.935  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 13:35:13.935  5651  5699 I jxcore-log: 
,11-03 13:35:13.935  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 13:35:13.935  5651  5699 I jxcore-log: 
11-03 13:35:13.935  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 13:35:13.935  5651  5699 I jxcore-log: 
11-03 13:35:13.940  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-03 13:35:13.940  5651  5699 I jxcore-log: 
11-03 13:35:13.940  5651  5699 I jxcore-log: 2016-11-03 12:35:13 - WARN testUtils: 'myNameCallback not set!'
11-03 13:35:13.940  5651  5699 I jxcore-log: 
,11-03 13:35:13.941  5651  5651 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-03 13:35:16.029  5651  5699 I jxcore-log: 2016-11-03 12:35:16 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-03 13:35:16.029  5651  5699 I jxcore-log: 
,11-03 13:35:16.031  5651  5699 I jxcore-log: 2016-11-03 12:35:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-03 13:35:16.031  5651  5699 I jxcore-log: 
,11-03 13:35:16.380  5651  5699 I jxcore-log: 2016-11-03 12:35:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-03 13:35:16.380  5651  5699 I jxcore-log: 
,11-03 13:35:16.393  5651  5699 I jxcore-log: 2016-11-03 12:35:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-03 13:35:16.393  5651  5699 I jxcore-log: 
,11-03 13:35:17.515  5651  5699 I jxcore-log: 2016-11-03 12:35:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-03 13:35:17.515  5651  5699 I jxcore-log: 
,11-03 13:35:17.710  5651  5699 I jxcore-log: 2016-11-03 12:35:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-03 13:35:17.710  5651  5699 I jxcore-log: 
,11-03 13:35:17.716  5651  5699 I jxcore-log: 2016-11-03 12:35:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-03 13:35:17.716  5651  5699 I jxcore-log: 
,11-03 13:35:17.721  5651  5699 I jxcore-log: 2016-11-03 12:35:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-03 13:35:17.721  5651  5699 I jxcore-log: 
,11-03 13:35:17.948   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:35:18.212  5651  5699 I jxcore-log: 2016-11-03 12:35:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-03 13:35:18.212  5651  5699 I jxcore-log: 
,11-03 13:35:18.257  5651  5699 I jxcore-log: 2016-11-03 12:35:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-03 13:35:18.257  5651  5699 I jxcore-log: 
,11-03 13:35:18.270  5651  5699 I jxcore-log: 2016-11-03 12:35:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-03 13:35:18.270  5651  5699 I jxcore-log: 
,11-03 13:35:18.273  5651  5699 I jxcore-log: 2016-11-03 12:35:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-03 13:35:18.273  5651  5699 I jxcore-log: 
,11-03 13:35:18.565  5651  5699 I jxcore-log: 2016-11-03 12:35:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-03 13:35:18.565  5651  5699 I jxcore-log: 
,11-03 13:35:18.695  5651  5699 I jxcore-log: 2016-11-03 12:35:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-03 13:35:18.695  5651  5699 I jxcore-log: 
,11-03 13:35:18.949   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:35:19.060  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-03 13:35:19.060  5651  5699 I jxcore-log: 
,11-03 13:35:19.068  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-03 13:35:19.068  5651  5699 I jxcore-log: 
,11-03 13:35:19.072  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-03 13:35:19.072  5651  5699 I jxcore-log: 
,11-03 13:35:19.078  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-03 13:35:19.078  5651  5699 I jxcore-log: 
,11-03 13:35:19.083  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-03 13:35:19.083  5651  5699 I jxcore-log: 
,11-03 13:35:19.111  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-03 13:35:19.111  5651  5699 I jxcore-log: 
,11-03 13:35:19.147  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-03 13:35:19.147  5651  5699 I jxcore-log: 
,11-03 13:35:19.154  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-03 13:35:19.154  5651  5699 I jxcore-log: 
,11-03 13:35:19.161  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-03 13:35:19.161  5651  5699 I jxcore-log: 
,11-03 13:35:19.176  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-03 13:35:19.176  5651  5699 I jxcore-log: 
,11-03 13:35:19.180  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-03 13:35:19.180  5651  5699 I jxcore-log: 
,11-03 13:35:19.186  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-03 13:35:19.186  5651  5699 I jxcore-log: 
,11-03 13:35:19.191  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-03 13:35:19.191  5651  5699 I jxcore-log: 
,11-03 13:35:19.204  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-03 13:35:19.204  5651  5699 I jxcore-log: 
,11-03 13:35:19.210  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-03 13:35:19.210  5651  5699 I jxcore-log: 
,11-03 13:35:19.233  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-03 13:35:19.233  5651  5699 I jxcore-log: 
,11-03 13:35:19.243  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-03 13:35:19.243  5651  5699 I jxcore-log: 
,11-03 13:35:19.266  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-03 13:35:19.266  5651  5699 I jxcore-log: 
,11-03 13:35:19.277  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-03 13:35:19.277  5651  5699 I jxcore-log: 
,11-03 13:35:19.290  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-03 13:35:19.290  5651  5699 I jxcore-log: 
,11-03 13:35:19.301  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-03 13:35:19.301  5651  5699 I jxcore-log: 
,11-03 13:35:19.308  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-03 13:35:19.308  5651  5699 I jxcore-log: 
,11-03 13:35:19.330  5651  5699 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-03 13:35:19.331  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - INFO testUtils: 'BLE multiple advertisement supported'
11-03 13:35:19.331  5651  5699 I jxcore-log: 
,11-03 13:35:19.417  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:19.417  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:19.417  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:19.417  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:19.417  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:19.417  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:19.417  5651  5699 I jxcore-log: 
,11-03 13:35:19.647  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:19.647  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:19.647  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:19.647  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:19.647  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:19.647  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:19.647  5651  5699 I jxcore-log: 
11-03 13:35:19.649  5651  5699 I jxcore-log: 2016-11-03 12:35:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:19.649  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:19.649  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:19.649  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:19.649  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:19.649  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:19.649  5651  5699 I jxcore-log: 
,11-03 13:35:19.951   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:35:20.032  5651  5699 I jxcore-log: 2016-11-03 12:35:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:20.032  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:20.032  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:20.032  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:20.032  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:20.032  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:20.032  5651  5699 I jxcore-log: 
,11-03 13:35:20.034  5651  5699 I jxcore-log: 2016-11-03 12:35:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:20.034  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:20.034  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:20.034  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:20.034  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:20.034  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:20.034  5651  5699 I jxcore-log: 
,11-03 13:35:20.952   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:35:21.069  5651  5699 I jxcore-log: 2016-11-03 12:35:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:21.069  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:21.069  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:21.069  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:21.069  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:21.069  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:21.069  5651  5699 I jxcore-log: 
,11-03 13:35:21.074  5651  5699 I jxcore-log: 2016-11-03 12:35:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:21.074  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:21.074  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:21.074  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:21.074  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:21.074  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:21.074  5651  5699 I jxcore-log: 
,11-03 13:35:21.953   593   593 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 13:35:22.117  5651  5699 I jxcore-log: 2016-11-03 12:35:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:22.117  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:22.117  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:22.117  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:22.117  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:22.117  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:22.117  5651  5699 I jxcore-log: 
,11-03 13:35:22.123  5651  5699 I jxcore-log: 2016-11-03 12:35:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:22.123  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:22.123  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:22.123  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:22.123  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:22.123  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:22.123  5651  5699 I jxcore-log: 
,11-03 13:35:22.954   593   593 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 13:35:23.164  5651  5699 I jxcore-log: 2016-11-03 12:35:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:23.164  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:23.164  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:23.164  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:23.164  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:23.164  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:23.164  5651  5699 I jxcore-log: 
,11-03 13:35:23.168  5651  5699 I jxcore-log: 2016-11-03 12:35:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:23.168  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:23.168  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:23.168  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:23.168  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:23.168  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:23.168  5651  5699 I jxcore-log: 
,11-03 13:35:24.205  5651  5699 I jxcore-log: 2016-11-03 12:35:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:24.205  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:24.205  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:24.205  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:24.205  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:24.205  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:24.205  5651  5699 I jxcore-log: 
,11-03 13:35:24.210  5651  5699 I jxcore-log: 2016-11-03 12:35:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:24.210  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:24.210  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:24.210  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:24.210  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:24.210  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:24.210  5651  5699 I jxcore-log: 
,11-03 13:35:25.254  5651  5699 I jxcore-log: 2016-11-03 12:35:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:25.254  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:25.254  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:25.254  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:25.254  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:25.254  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:25.254  5651  5699 I jxcore-log: 
,11-03 13:35:25.260  5651  5699 I jxcore-log: 2016-11-03 12:35:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:25.260  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:25.260  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:25.260  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:25.260  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:25.260  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:25.260  5651  5699 I jxcore-log: 
,11-03 13:35:26.290  5651  5699 I jxcore-log: 2016-11-03 12:35:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:26.290  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:26.290  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:26.290  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:26.290  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:26.290  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:26.290  5651  5699 I jxcore-log: 
,11-03 13:35:26.294  5651  5699 I jxcore-log: 2016-11-03 12:35:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:26.294  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:26.294  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:26.294  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:26.294  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:26.294  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:26.294  5651  5699 I jxcore-log: 
,11-03 13:35:27.324  5651  5699 I jxcore-log: 2016-11-03 12:35:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:27.324  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:27.324  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:27.324  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:27.324  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:27.324  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:27.324  5651  5699 I jxcore-log: 
,11-03 13:35:27.328  5651  5699 I jxcore-log: 2016-11-03 12:35:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:27.328  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:27.328  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:27.328  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:27.328  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:27.328  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:27.328  5651  5699 I jxcore-log: 
,11-03 13:35:28.388  5651  5699 I jxcore-log: 2016-11-03 12:35:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:28.388  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:28.388  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:28.388  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:28.388  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:28.388  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:28.388  5651  5699 I jxcore-log: 
,11-03 13:35:28.391  5651  5699 I jxcore-log: 2016-11-03 12:35:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:28.391  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:28.391  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:28.391  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:28.391  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:28.391  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:28.391  5651  5699 I jxcore-log: 
,11-03 13:35:29.422  5651  5699 I jxcore-log: 2016-11-03 12:35:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:29.422  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:29.422  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:29.422  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:29.422  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:29.422  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:29.422  5651  5699 I jxcore-log: 
,11-03 13:35:29.429  5651  5699 I jxcore-log: 2016-11-03 12:35:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:29.429  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:29.429  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:29.429  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:29.429  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:29.429  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:29.429  5651  5699 I jxcore-log: 
,11-03 13:35:30.458  5651  5699 I jxcore-log: 2016-11-03 12:35:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:30.458  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:30.458  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:30.458  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:30.458  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:30.458  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:30.458  5651  5699 I jxcore-log: 
,11-03 13:35:30.462  5651  5699 I jxcore-log: 2016-11-03 12:35:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:30.462  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:30.462  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:30.462  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:30.462  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:30.462  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:30.462  5651  5699 I jxcore-log: 
,11-03 13:35:31.493  5651  5699 I jxcore-log: 2016-11-03 12:35:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:31.493  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:31.493  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:31.493  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:31.493  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:31.493  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:31.493  5651  5699 I jxcore-log: 
,11-03 13:35:31.497  5651  5699 I jxcore-log: 2016-11-03 12:35:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:31.497  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:31.497  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:31.497  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:31.497  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:31.497  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:31.497  5651  5699 I jxcore-log: 
,11-03 13:35:32.527  5651  5699 I jxcore-log: 2016-11-03 12:35:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:32.527  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:32.527  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:32.527  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:32.527  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:32.527  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:32.527  5651  5699 I jxcore-log: 
,11-03 13:35:32.530  5651  5699 I jxcore-log: 2016-11-03 12:35:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:32.530  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:32.530  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:32.530  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:32.530  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:32.530  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:32.530  5651  5699 I jxcore-log: 
,11-03 13:35:33.581  5651  5699 I jxcore-log: 2016-11-03 12:35:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 13:35:33.581  5651  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 13:35:33.581  5651  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 13:35:33.581  5651  5699 I jxcore-log: emit@events.js:82:1
11-03 13:35:33.581  5651  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 13:35:33.581  5651  5699 I jxcore-log: emit@events.js:82:1'
11-03 13:35:33.581  5651  5699 I jxcore-log: 
,11-03 13:35:33.591  5651  5699 E jxcore  : Error!: error is undefined
11-03 13:35:33.591  5651  5699 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-03 13:35:33.594  5651  5699 I jxcore-log: 2016-11-03 12:35:33 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-03 13:35:33.594  5651  5699 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-03 13:35:33.594  5651  5699 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-03 13:35:33.594  5651  5699 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-03 13:35:33.594  5651  5699 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-03 13:35:33.594  5651  5699 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-03 13:35:33.594  5651  5699 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-03 13:35:33.594  5651  5699 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-03 13:35:33.595  5651  5699 I jxcore-log: 2016-11-03 12:35:33 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-03 13:35:33.595  5651  5699 I jxcore-log: 
,11-03 13:35:33.597  5651  5699 E jxcore-log: TypeError: 
11-03 13:35:33.597  5651  5699 E jxcore-log: error is undefined
11-03 13:35:33.597  5651  5699 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-03 13:35:33.597  5651  5699 E jxcore-log: 
,11-03 13:35:33.691   930  3176 D GraphicsStats: Buffer count: 2
,11-03 13:35:33.691   930  3716 I WindowState: WIN DEATH: Window{56eef17 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-03 13:35:33.691   930  3025 D WifiService: Client connection lost with reason: 4
,11-03 13:35:33.702   529   529 I Zygote  : Process 5651 exited cleanly (139)
,11-03 13:35:33.707   930  3803 I ActivityManager: Process com.test.thalitest (pid 5651) has died
,11-03 13:35:33.720   930  3803 I ActivityManager: Start proc 5978:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-03 13:35:33.799  5978  5978 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-03 13:35:33.823  5978  5978 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-03 13:35:33.830  5978  5978 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4341-4343)
11-03 13:35:33.830  5978  5978 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 13:35:33.841  5978  5978 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b03f987}
,11-03 13:35:33.841  5978  5978 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 13:35:33.842  5978  5978 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 13:35:33.846  5978  5978 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 13:35:33.847  5978  5978 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 13:35:33.860  5978  5978 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 13:35:33.873  5978  5978 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-03 13:35:33.873  5978  5978 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 13:35:33.873  5978  5978 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 13:35:33.873  5978  5978 I Adreno  : Build Date                       : 12/06/15
11-03 13:35:33.873  5978  5978 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 13:35:33.873  5978  5978 I Adreno  : Local Branch                     : mybranch17112971
11-03 13:35:33.873  5978  5978 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 13:35:33.873  5978  5978 I Adreno  : Remote Branch                    : NONE
11-03 13:35:33.873  5978  5978 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 13:35:33.912   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4220fa2:true
,11-03 13:35:33.929   505   505 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[14639]" dev="sockfs" ino=14639 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 13:35:33.929   505   505 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[14639]" dev="sockfs" ino=14639 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 13:35:33.940  5978  5978 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 13:35:33.948  5978  5978 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 13:35:33.972   504   504 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33680]" dev="sockfs" ino=33680 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 13:35:33.972   504   504 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33680]" dev="sockfs" ino=33680 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 13:35:33.974  5978  6014 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 13:35:33.975  3803  3803 W Binder_B: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[14651]" dev="sockfs" ino=14651 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:35:33.975  3803  3803 W Binder_B: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[14651]" dev="sockfs" ino=14651 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:35:33.978  5978  6001 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 13:35:34.009  5978  6014 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 13:35:34.023   930  3176 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5651 uid 10077
,11-03 13:35:34.022  3176  3176 W Binder_3: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[15531]" dev="sockfs" ino=15531 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:35:34.022  3176  3176 W Binder_3: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[15531]" dev="sockfs" ino=15531 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:35:34.022  3208  3208 W Binder_4: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[15530]" dev="sockfs" ino=15530 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:35:34.028  3692  3692 I Keyboard.Facilitator: onFinishInput()
,11-03 13:35:34.022  3208  3208 W Binder_4: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[15530]" dev="sockfs" ino=15530 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 13:35:34.044   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +305ms (total +336ms)
,11-03 13:35:34.047  5978  5978 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5978
,11-03 13:35:34.100  5978  5978 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 13:35:34.143  5976  5976 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-03 13:35:34.159  5976  5976 D AndroidRuntime: CheckJNI is OFF
,11-03 13:35:34.181  5976  5976 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-03 13:35:34.206  5976  5976 I Radio-JNI: register_android_hardware_Radio DONE
,11-03 13:35:34.222  5976  5976 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-03 13:35:34.228   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-03 13:35:34.228   930   943 I ActivityManager: Killing 5978:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-03 13:35:34.262   930  3809 D GraphicsStats: Buffer count: 2
,11-03 13:35:34.262   930  3470 I WindowState: WIN DEATH: Window{6f042d9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-03 13:35:34.329   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-03 13:35:34.329   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-03 13:35:34.330   930   943 E ActivityManager: Failure starting process com.test.thalitest
11-03 13:35:34.330   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-03 13:35:34.330   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 13:35:34.330   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-03 13:35:34.330   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 13:35:34.330   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-03 13:35:34.331   930   943 I ActivityManager:   Force finishing activity ActivityRecord{c81da0c u0 com.test.thalitest/.MainActivity t68}
,11-03 13:35:34.333   930   953 I art     : Starting a blocking GC Explicit
11-03 13:35:34.342   930  3469 W ActivityManager: Spurious death for ProcessRecord{3f00b7f 0:com.test.thalitest/u0a77}, curProc for 5978: null
,11-03 13:35:34.416   930   953 I art     : Explicit concurrent mark sweep GC freed 12774(848KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.592ms total 82.595ms
,11-03 13:35:34.438   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-03 13:35:34.441  5976  5976 I art     : System.exit called, status: 0
,11-03 13:35:34.441  5976  5976 I AndroidRuntime: VM exiting with result code 0.
,11-03 13:35:34.447   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-03 13:35:34.454   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-03 13:35:34.459  3692  3692 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-03 13:35:34.459  3879  4142 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-03 13:35:34.460  5875  5875 D BluetoothMapAppObserver: onReceive
11-03 13:35:34.461  5875  5875 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-03 13:35:34.465   930  2990 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-03 13:35:34.497  3692  6029 I Keyboard.Facilitator.DecoderInitializer: run()
,11-03 13:35:34.520  3453  6030 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-03 13:35:34.521  3799  3799 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
11-03 13:35:34.523  3692  6029 I Decoder : createOrResetDecoder
,11-03 13:35:34.526  3637  3637 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-03 13:35:34.526  3637  3637 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-03 13:35:34.537   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-03 13:35:34.539    29    29 W kworker/3:1: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 13:35:34.541  4077  6035 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-03 13:35:34.543  4077  6035 D AccountUtils: Clearing selected account for com.test.thalitest
,11-03 13:35:34.542    29    29 W kworker/3:1: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 13:35:34.555    29    29 W kworker/3:1: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 13:35:34.565  3453  3479 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjBDEAFE915) - 
,--------- beginning of crash
11-03 13:35:34.566  3453  3479 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-03 13:35:34.566  3453  3479 E AndroidRuntime: Process: android.process.acore, PID: 3453
11-03 13:35:34.566  3453  3479 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 13:35:34.566  3453  3479 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-03 13:35:34.568   930  3822 I ActivityManager: Start proc 6038:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-03 13:35:34.569  3835  3955 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-03 13:35:34.569  3835  3955 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3835
11-03 13:35:34.569  3835  3955 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 13:35:34.569  3835  3955 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: Can't write: system_app_crash
11-03 13:35:34.571   930  6046 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 13:35:34.571   930  6046 E DropBoxManagerService: 	... 5 more
11-03 13:35:34.572   930   941 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-03 13:35:34.576  3835  3955 I Process : Sending signal. PID: 3835 SIG: 9
11-03 13:35:34.576   930  6045 E DropBoxManagerService: Can't write: system_app_crash
11-03 13:35:34.576   930  6045 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 13:35:34.576   930  6045 E DropBoxManagerService: 	... 5 more
11-03 13:35:34.595  3637  3637 I ConfigService: onCreate
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-03 13:35:34.598  3637  6052 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-03 13:35:34.598  3637  6052 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-03 13:35:34.600  3637  6052 W SQLiteOpenHelper: Opened config.db in read-only mode
11-03 13:35:34.601  3453  6030 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-03 13:35:34.601  3453  6030 I Process : Sending signal. PID: 3453 SIG: 9
,11-03 13:35:34.626  4077  6035 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-03 13:35:34.643   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
