#### Test 91479574e64d32d_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-03 15:14:58.380  3993  4251 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-03 15:14:58.451  3993  4251 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-03 15:14:58.808  5603  5603 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-03 15:14:58.814  5603  5603 D AndroidRuntime: CheckJNI is OFF
11-03 15:14:58.843  5603  5603 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-03 15:14:58.890  5603  5603 I Radio-JNI: register_android_hardware_Radio DONE
11-03 15:14:58.905  5603  5603 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-03 15:14:58.916   930  3840 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-03 15:14:58.935  5603  5603 D AndroidRuntime: Shutting down VM
11-03 15:14:58.946  3975  4235 W SearchService: Abort, client detached.
11-03 15:14:58.956  3975  3975 I HotwordDetector: Closing mic
11-03 15:14:58.956  3975  4244 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@738b6e4
11-03 15:14:58.957  3975  4255 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-03 15:14:58.973   930   940 I ActivityManager: Start proc 5612:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-03 15:14:59.028   511  4257 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-03 15:14:59.029   511  4257 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-03 15:14:59.033   511  4257 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-03 15:14:59.033   511  4257 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-03 15:14:59.033   511  3011 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-03 15:14:59.035  3975  4246 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-03 15:14:59.035  3975  4254 I MicroRecognitionRnrImpl: Detection finished
11-03 15:14:59.070  5612  5612 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-03 15:14:59.090  5612  5612 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-03 15:14:59.148  5612  5612 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 8799-8854)
11-03 15:14:59.148  5612  5612 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 15:14:59.188  5612  5612 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {73296bd}
,11-03 15:14:59.188  5612  5612 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 15:14:59.188  5612  5612 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 15:14:59.191  5612  5612 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 15:14:59.192  5612  5612 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 15:14:59.235  5612  5612 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 15:14:59.243  5612  5612 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-03 15:14:59.243  5612  5612 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 15:14:59.244  5612  5612 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 15:14:59.244  5612  5612 I Adreno  : Build Date                       : 12/06/15
11-03 15:14:59.244  5612  5612 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 15:14:59.244  5612  5612 I Adreno  : Local Branch                     : mybranch17112971
11-03 15:14:59.244  5612  5612 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 15:14:59.244  5612  5612 I Adreno  : Remote Branch                    : NONE
11-03 15:14:59.244  5612  5612 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 15:14:59.283   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@45f438e:true
,11-03 15:14:59.316   745   745 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[25215]" dev="sockfs" ino=25215 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 15:14:59.316   745   745 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25215]" dev="sockfs" ino=25215 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 15:14:59.329  5612  5612 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 15:14:59.338  5612  5612 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 15:14:59.360   745   745 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33252]" dev="sockfs" ino=33252 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 15:14:59.360   745   745 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33252]" dev="sockfs" ino=33252 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 15:14:59.363  5612  5649 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 15:14:59.366  3430  3430 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14987]" dev="sockfs" ino=14987 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 15:14:59.368  5612  5636 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-03 15:14:59.366  3430  3430 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14987]" dev="sockfs" ino=14987 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 15:14:59.396  5612  5649 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 15:14:59.470  3837  3837 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33258]" dev="sockfs" ino=33258 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 15:14:59.470  3837  3837 W Binder_8: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33258]" dev="sockfs" ino=33258 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 15:14:59.472   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +524ms
11-03 15:14:59.470  3665  3665 W Binder_7: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33257]" dev="sockfs" ino=33257 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 15:14:59.470  3665  3665 W Binder_7: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33257]" dev="sockfs" ino=33257 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 15:14:59.478  3664  3664 I Keyboard.Facilitator: onFinishInput()
,11-03 15:14:59.504  5612  5612 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5612
,11-03 15:14:59.615  5612  5612 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 15:14:59.912  5612  5652 D jxcore_app_log: JniHelper::setJavaVM(0xf52bc000), pthread_self() = -581170896
,11-03 15:14:59.944  5612  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-03 15:14:59.944  5612  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-03 15:14:59.944  5612  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-03 15:14:59.944  5612  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-03 15:14:59.944  5612  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-03 15:14:59.944  5612  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da5cb58 added. We now have 1 listener(s)
,11-03 15:14:59.953  5612  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-03 15:14:59.954  5612  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 15:14:59.959  5612  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 15:14:59.959  5612  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-03 15:14:59.968  5612  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8898d17 added. We now have 1 listener(s)
11-03 15:14:59.969  5612  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:14:59.976   930  2982 D WifiService: New client listening to asynchronous messages
,11-03 15:14:59.977  5612  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 15:14:59.978  5612  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-03 15:14:59.978  5612  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-03 15:14:59.978  5612  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-03 15:14:59.978  5612  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-03 15:14:59.979  5612  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-03 15:14:59.979  5612  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-03 15:14:59.983  5612  5652 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-03 15:15:00.234  5612  5612 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-03 15:15:00.596  5612  5621 I art     : Background sticky concurrent mark sweep GC freed 77661(7MB) AllocSpace objects, 16(1076KB) LOS objects, 25% free, 24MB/32MB, paused 1.583ms total 297.185ms
,11-03 15:15:01.038   930  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 15:15:01.841  5612  5659 E filemap : mmap(25460736,0) failed: Invalid argument
,11-03 15:15:01.841  5612  5659 W asset   : create map from entry failed
11-03 15:15:01.841  5612  5659 W jxcore-FileManager: aproxFileSize failed
11-03 15:15:01.841  5612  5659 W System.err: java.io.FileNotFoundException: www/jxcore/node_modules/tar-fs/test/fixtures/d/sub-dir/file5
11-03 15:15:01.844  5612  5621 I art     : Background partial concurrent mark sweep GC freed 51211(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.253ms total 343.849ms
,11-03 15:15:01.848  5612  5659 W System.err: 	at android.content.res.AssetManager.openAsset(Native Method)
,11-03 15:15:01.848  5612  5659 W System.err: 	at android.content.res.AssetManager.open(AssetManager.java:313)
11-03 15:15:01.848  5612  5659 W System.err: 	at io.jxcore.node.FileManager.aproxFileSize(FileManager.java:48)
11-03 15:15:01.848  5612  5659 W System.err: 	at io.jxcore.node.jxcore.Initialize(jxcore.java:281)
11-03 15:15:01.848  5612  5659 W System.err: 	at io.jxcore.node.jxcore.access$200(jxcore.java:25)
11-03 15:15:01.848  5612  5659 W System.err: 	at io.jxcore.node.jxcore$6.run(jxcore.java:343)
11-03 15:15:01.848  5612  5659 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 15:15:01.848  5612  5659 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,11-03 15:15:01.848  5612  5659 W System.err: 	at android.os.Looper.loop(Looper.java:148)
11-03 15:15:01.848  5612  5659 W System.err: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,11-03 15:15:02.275  5612  5659 W jxcore-log: Initializing JXcore engine
,11-03 15:15:02.275  5612  5659 W jxcore-log: JXcore engine is ready
,11-03 15:15:02.300  5659  5659 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1251 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-03 15:15:02.300  5659  5659 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13434]" dev="sockfs" ino=13434 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-03 15:15:02.300  5659  5659 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-03 15:15:02.300  5659  5659 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33223]" dev="sockfs" ino=33223 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-03 15:15:02.307  5612  5659 W jxcore-log: Starting JXcore engine
,11-03 15:15:02.355  5612  5659 W jxcore-log: Platform android
11-03 15:15:02.355  5612  5659 W jxcore-log: 
,11-03 15:15:02.355  5612  5659 W jxcore-log: Process ARCH arm
11-03 15:15:02.355  5612  5659 W jxcore-log: 
,11-03 15:15:02.520  3585  3585 I ConfigService: onDestroy
,11-03 15:15:02.535  5612  5659 I jxcore-log: JXcore Cordova bridge is ready!
11-03 15:15:02.535  5612  5659 I jxcore-log: 
11-03 15:15:02.535  5612  5659 W jxcore-log: JXcore engine is started
11-03 15:15:02.548  5612  5652 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-03 15:15:02.556  5612  5612 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-03 15:15:03.603   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:03.964   930   941 I ActivityManager: Killing 5259:org.codeaurora.ims/1001 (adj 15): empty #17
,11-03 15:15:04.002   930   941 I ActivityManager: Killing 5166:com.google.android.youtube/u0a75 (adj 15): empty #18
,11-03 15:15:04.604   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:05.605   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:06.606   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:07.607   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:08.608   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 15:15:09.047  3975  5660 W CronetSyncConnectionRcs: Upload content type not set.
,11-03 15:15:12.190  4896  4938 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-03 15:15:12.191  4896  4896 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-03 15:15:12.352  5612  5659 I jxcore-log: 2016-11-03 14:15:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-03 15:15:12.352  5612  5659 I jxcore-log: 
,11-03 15:15:12.355  5612  5659 I jxcore-log: 2016-11-03 14:15:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-03 15:15:12.355  5612  5659 I jxcore-log: 
,11-03 15:15:12.360  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-03 15:15:12.360  5612  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 15:15:12.360  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:12.360  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:12.360  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 15:15:12.360  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 15:15:12.360  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 15:15:12.360  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 15:15:12.360  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 15:15:12.361  5612  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 15:15:12.363  5612  5659 I jxcore-log: 2016-11-03 14:15:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-03 15:15:12.363  5612  5659 I jxcore-log: 
,11-03 15:15:12.365  5612  5659 I jxcore-log: 2016-11-03 14:15:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-03 15:15:12.365  5612  5659 I jxcore-log: 
,11-03 15:15:12.620  5612  5659 I jxcore-log: 2016-11-03 14:15:12 - DEBUG UnitTest_app: 'Running unit tests'
11-03 15:15:12.620  5612  5659 I jxcore-log: 
,11-03 15:15:12.620  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 15:15:12.620  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bd1b4 added. We now have 2 listener(s)
,11-03 15:15:12.621  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 15:15:12.621  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 15:15:12.621  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 15:15:12.621  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 15:15:12.621  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17551dd added. We now have 2 listener(s)
,11-03 15:15:12.621  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 15:15:12.622  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 15:15:12.623  5612  5659 D executeNativeTests: Running unit tests
,11-03 15:15:12.662  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 15:15:12.662  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 added. We now have 3 listener(s)
11-03 15:15:12.663  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 15:15:12.663  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 15:15:12.663  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 15:15:12.663  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 15:15:12.663  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 added. We now have 3 listener(s)
,11-03 15:15:12.663  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:15:12.663  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 15:15:12.665  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 15:15:12.665  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 15:15:12.665  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 15:15:12.665  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 15:15:12.666  5612  5659 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-03 15:15:12.666  5612  5659 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 15:15:12.666  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 15:15:12.666  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 15:15:12.666  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 15:15:12.666  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 15:15:12.666  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 15:15:12.667  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:12.667  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:12.667  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:12.668  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 15:15:12.668  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 15:15:12.668  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 removed from the list
11-03 15:15:12.668  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:12.668  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 removed from the list
,11-03 15:15:12.668  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 15:15:12.668  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:12.669  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.669  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.669  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.669  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:12.669  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:12.669  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:12.669  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:12.670  5612  5659 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-03 15:15:12.670  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:12.670  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:12.670  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:12.670  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:12.670  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 15:15:12.670  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:12.670  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:12.670  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:12.670  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:12.670  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.671  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.671  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.671  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:12.671  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:12.671  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:12.671  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:12.671  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:12.673  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-03 15:15:12.673  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 15:15:12.673  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 15:15:12.673  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 15:15:12.673  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-03 15:15:12.673  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 15:15:12.674  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-03 15:15:12.674  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:12.674  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:12.674  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:12.674  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 15:15:12.674  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:12.674  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:12.674  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:12.675  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:12.675  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:12.675  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.675  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.675  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.675  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.675  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 15:15:12.675  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:12.675  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:12.675  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:12.676  5612  5659 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 15:15:12.677  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 15:15:12.677  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 15:15:12.688  5612  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 15:15:12.688  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:12.688  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:12.688  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 15:15:12.688  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 15:15:12.688  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 15:15:12.688  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 15:15:12.688  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 15:15:12.689  5612  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 15:15:12.689  5612  5659 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 15:15:12.689  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 15:15:12.689  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 15:15:12.690  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 15:15:12.690  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 15:15:12.690  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 15:15:12.692  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:12.693  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:12.693  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 15:15:12.693  5612  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 15:15:12.694  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 15:15:12.696  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:12.696  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 15:15:12.697  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-03 15:15:12.697  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 15:15:12.697  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 15:15:12.698  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-03 15:15:12.699  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-03 15:15:12.699  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.699  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-03 15:15:12.699  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 15:15:12.699  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 15:15:12.699  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-03 15:15:12.699  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.700  5612  5659 D BluetoothAdapter: STATE_ON
,11-03 15:15:12.702  4685  4908 D BtGatt.GattService: registerClient() - UUID=991a1a2f-c002-4a31-85da-ca728385967a
,11-03 15:15:12.702  4685  4744 D BtGatt.GattService: onClientRegistered() - UUID=991a1a2f-c002-4a31-85da-ca728385967a, clientIf=5
,11-03 15:15:12.703  5612  5623 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 15:15:12.704  4685  4698 D BtGatt.GattService: start scan with filters
,11-03 15:15:12.710  4685  4748 D BtGatt.ScanManager: handling starting scan
,11-03 15:15:12.710  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 15:15:12.710  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.710  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 15:15:12.710  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:12.711  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 15:15:12.711  5612  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 15:15:12.711  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 15:15:12.711  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 15:15:12.711  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 15:15:12.711  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 15:15:12.711  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-03 15:15:12.711  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.711  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 15:15:12.711  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 15:15:12.712  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.712  4685  4748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
11-03 15:15:12.712  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.712  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:12.712  5612  5659 I io.jxcore.node.ConnectionHelper: start: OK
11-03 15:15:12.712  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 15:15:12.715  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 15:15:12.715  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 15:15:12.715  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 15:15:12.716  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 15:15:12.716  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 15:15:12.716  5612  5612 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 15:15:12.720  4685  4744 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 15:15:12.720  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:12.721  4685  4748 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 15:15:12.727  4685  4744 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-03 15:15:12.728  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:12.728  4685  4748 D BtGatt.ScanManager: Starting BLE batch scan
11-03 15:15:12.728  4685  4748 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 15:15:12.738  4685  4744 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 15:15:12.738  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:12.744  4685  4744 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 15:15:12.744  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:13.217  5612  5612 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-03 15:15:13.217  5612  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 15:15:13.218  5612  5612 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 15:15:17.716  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 15:15:17.717  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-03 15:15:17.717  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 15:15:17.717  5612  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 15:15:17.717  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 15:15:17.717  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:17.717  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 15:15:17.718  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-03 15:15:17.718  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-03 15:15:17.718  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 15:15:17.719  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:17.719  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.719  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:17.719  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-03 15:15:17.719  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.720  5612  5659 D BluetoothAdapter: STATE_ON
11-03 15:15:17.721  4685  4908 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 15:15:17.721  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-03 15:15:17.722  5612  5659 D BluetoothAdapter: STATE_ON
11-03 15:15:17.722  4685  4748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 15:15:17.722  4685  4697 D BtGatt.GattService: stopScan() - queue size =1
11-03 15:15:17.723  4685  4908 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 15:15:17.724  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 15:15:17.724  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:17.724  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 15:15:17.724  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.724  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:17.725  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.725  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.725  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 15:15:17.725  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.726  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.726  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.726  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 15:15:17.726  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 15:15:17.727  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 15:15:17.727  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:17.728  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.728  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 15:15:17.729  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.729  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:17.729  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:17.729  5612  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 15:15:17.729  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 15:15:17.729  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 15:15:17.729  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:17.729  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
,11-03 15:15:17.729  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:17.729  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 15:15:17.730  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:17.730  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:17.730  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 15:15:17.730  5612  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 15:15:17.730  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 15:15:17.730  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 15:15:17.730  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-03 15:15:17.731  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 15:15:17.731  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 15:15:17.731  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 15:15:17.731  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 15:15:17.732  4685  4685 D BtGatt.ScanManager: awakened up at time 97438
11-03 15:15:17.736  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 15:15:17.736  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 15:15:17.736  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-03 15:15:17.736  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 15:15:17.736  5612  5612 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 15:15:17.746  4685  4744 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-03 15:15:17.746  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:17.746  4685  4744 D BtGatt.GattService: current time is 97452730140
11-03 15:15:17.746  4685  4744 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -83, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:15:17.748  4685  4744 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:15:17.749  4685  4744 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:15:17.754  4685  4744 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 15:15:17.754  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:17.755  4685  4748 D BtGatt.ScanManager: stopping BLe Batch
,11-03 15:15:17.760  4685  4744 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 15:15:17.760  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:17.760  4685  4748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:15:17.765  4685  4744 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 15:15:17.765  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:18.238  5612  5612 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 15:15:22.732  5612  5659 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-03 15:15:22.734  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 15:15:22.735  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 15:15:22.742  5612  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 15:15:22.742  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:22.742  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:22.742  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 15:15:22.742  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 15:15:22.742  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 15:15:22.742  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 15:15:22.742  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 15:15:22.745  5612  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 15:15:22.745  5612  5659 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 15:15:22.745  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 15:15:22.746  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-03 15:15:22.746  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-03 15:15:22.746  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 15:15:22.746  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 15:15:22.752  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:22.755  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 15:15:22.755  5612  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-03 15:15:22.755  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 15:15:22.757  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:22.762  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:22.763  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 15:15:22.764  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 15:15:22.764  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 15:15:22.764  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 15:15:22.771  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.772  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-03 15:15:22.772  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 15:15:22.772  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 15:15:22.772  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 15:15:22.772  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.773  5612  5659 D BluetoothAdapter: STATE_ON
,11-03 15:15:22.777  4685  4908 D BtGatt.GattService: registerClient() - UUID=9fb5a12e-aff2-49bd-9030-256a376aa42b
,11-03 15:15:22.778  4685  4744 D BtGatt.GattService: onClientRegistered() - UUID=9fb5a12e-aff2-49bd-9030-256a376aa42b, clientIf=5
,11-03 15:15:22.779  5612  5623 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 15:15:22.779  4685  4916 D BtGatt.GattService: start scan with filters
,11-03 15:15:22.786  4685  4748 D BtGatt.ScanManager: handling starting scan
11-03 15:15:22.787  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 15:15:22.787  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.787  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-03 15:15:22.787  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:22.787  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 15:15:22.787  5612  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 15:15:22.788  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-03 15:15:22.788  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 15:15:22.788  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 15:15:22.788  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.788  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.788  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-03 15:15:22.791  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 15:15:22.791  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.796  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.796  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 15:15:22.796  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.796  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.796  5612  5659 I io.jxcore.node.ConnectionHelper: start: OK
11-03 15:15:22.796  4685  4744 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 15:15:22.796  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:22.797  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.797  4685  4748 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 15:15:22.801  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 15:15:22.801  5612  5659 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 15:15:22.802  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:22.802  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 15:15:22.802  5612  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 15:15:22.802  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 15:15:22.802  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:22.802  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 15:15:22.804  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.804  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.804  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.804  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-03 15:15:22.804  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 15:15:22.805  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 15:15:22.805  5612  5612 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 15:15:22.805  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 15:15:22.805  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.805  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.806  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:22.806  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 15:15:22.806  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.806  4685  4744 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 15:15:22.806  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:22.807  4685  4748 D BtGatt.ScanManager: Starting BLE batch scan
11-03 15:15:22.807  4685  4748 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 15:15:22.808  5612  5659 D BluetoothAdapter: STATE_ON
11-03 15:15:22.808  4685  4908 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 15:15:22.808  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 15:15:22.809  5612  5659 D BluetoothAdapter: STATE_ON
11-03 15:15:22.810  4685  4698 D BtGatt.GattService: stopScan() - queue size =1
,11-03 15:15:22.812  4685  4697 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 15:15:22.812  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 15:15:22.812  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.813  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 15:15:22.813  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.813  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.813  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.813  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.813  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-03 15:15:22.814  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.814  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.814  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.814  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 15:15:22.815  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 15:15:22.817  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 15:15:22.817  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.819  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.819  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 15:15:22.819  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.819  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.819  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:22.819  5612  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 15:15:22.819  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 15:15:22.819  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 15:15:22.819  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:22.819  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:22.820  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:22.820  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:22.820  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 15:15:22.820  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:22.820  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 15:15:22.820  5612  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-03 15:15:22.820  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.820  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 15:15:22.820  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 15:15:22.820  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.820  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.820  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 15:15:22.821  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.823  4685  4744 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 15:15:22.823  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:22.824  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.825  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.825  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.825  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.825  5612  5612 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 15:15:22.825  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:22.827  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.827  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:22.827  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.827  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:22.827  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:22.827  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:22.828  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:22.828  5612  5659 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 15:15:22.830  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 15:15:22.830  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 15:15:22.832  4685  4744 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-03 15:15:22.832  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:22.835  4685  4748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 15:15:22.837  5612  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 15:15:22.837  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:22.837  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:22.837  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 15:15:22.837  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 15:15:22.837  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 15:15:22.837  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 15:15:22.837  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 15:15:22.839  5612  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 15:15:22.839  5612  5659 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 15:15:22.839  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 15:15:22.839  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 15:15:22.839  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 15:15:22.839  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 15:15:22.839  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 15:15:22.841  4685  4744 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 15:15:22.841  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:22.841  4685  4744 E BtGatt.ContextMap: Context not found for ID 5
11-03 15:15:22.842  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:22.845  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 15:15:22.845  5612  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 15:15:22.845  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 15:15:22.846  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:22.851  4685  4744 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 15:15:22.851  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:22.851  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.851  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 15:15:22.851  4685  4748 D BtGatt.ScanManager: stopping BLe Batch
,11-03 15:15:22.852  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 15:15:22.852  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 15:15:22.852  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 15:15:22.857  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:22.857  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 15:15:22.857  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 15:15:22.857  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-03 15:15:22.857  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-03 15:15:22.857  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.857  4685  4744 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 15:15:22.858  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:22.858  4685  4748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 15:15:22.858  5612  5659 D BluetoothAdapter: STATE_ON
,11-03 15:15:22.861  4685  4698 D BtGatt.GattService: registerClient() - UUID=2fc03102-398f-47ae-b96b-80d9c2f626c7
11-03 15:15:22.862  4685  4744 D BtGatt.GattService: onClientRegistered() - UUID=2fc03102-398f-47ae-b96b-80d9c2f626c7, clientIf=5
11-03 15:15:22.862  5612  5622 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 15:15:22.862  4685  4908 D BtGatt.GattService: start scan with filters
,11-03 15:15:22.864  4685  4744 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 15:15:22.864  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:22.866  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 15:15:22.866  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.866  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 15:15:22.866  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.866  4685  4748 D BtGatt.ScanManager: handling starting scan
11-03 15:15:22.866  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 15:15:22.866  5612  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 15:15:22.866  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.866  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 15:15:22.867  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 15:15:22.867  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.867  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.867  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-03 15:15:22.868  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-03 15:15:22.869  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.871  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.871  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 15:15:22.871  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:22.871  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:22.871  5612  5659 I io.jxcore.node.ConnectionHelper: start: OK
,11-03 15:15:22.872  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 15:15:22.873  4685  4744 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 15:15:22.873  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:22.874  4685  4748 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 15:15:22.874  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.874  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.874  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-03 15:15:22.874  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 15:15:22.874  5612  5612 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 15:15:22.879  4685  4744 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 15:15:22.879  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:22.879  4685  4748 D BtGatt.ScanManager: Starting BLE batch scan
11-03 15:15:22.879  4685  4748 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 15:15:22.888  4685  4744 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 15:15:22.888  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:22.893  4685  4744 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 15:15:22.893  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:23.375  5612  5612 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-03 15:15:23.376  5612  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 15:15:23.376  5612  5612 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 15:15:24.281   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 15:15:24.290   930  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-03 15:15:27.309   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 15:15:27.316   930  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-03 15:15:27.872  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 15:15:27.872  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-03 15:15:27.872  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-03 15:15:27.872  5612  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 15:15:27.873  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 15:15:27.873  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:27.873  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-03 15:15:27.873  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 15:15:27.873  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 15:15:27.873  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-03 15:15:27.874  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.874  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.874  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:27.874  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-03 15:15:27.875  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.877  5612  5659 D BluetoothAdapter: STATE_ON
,11-03 15:15:27.877  4685  4916 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 15:15:27.878  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 15:15:27.879  4685  4748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 15:15:27.880  5612  5659 D BluetoothAdapter: STATE_ON
,11-03 15:15:27.883  4685  4697 D BtGatt.GattService: stopScan() - queue size =1
11-03 15:15:27.885  4685  4908 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 15:15:27.887  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-03 15:15:27.888  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.888  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 15:15:27.888  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:27.888  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.889  4685  4685 D BtGatt.ScanManager: awakened up at time 107595
11-03 15:15:27.889  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:27.889  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.889  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 15:15:27.890  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.891  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:27.892  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.892  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 15:15:27.892  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-03 15:15:27.893   930  3843 I ActivityManager: Killing 5298:com.android.settings/1000 (adj 15): empty #17
,11-03 15:15:27.922  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 15:15:27.922  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:27.924  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.924  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 15:15:27.924  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.924  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:27.924  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 15:15:27.925  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 15:15:27.925  5612  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-03 15:15:27.925  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 15:15:27.925  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 15:15:27.925  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 15:15:27.925  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 15:15:27.925  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 15:15:27.925  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 15:15:27.925  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 15:15:27.927  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 15:15:27.927  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 15:15:27.928  5612  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 15:15:27.928  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 15:15:27.928  5612  5612 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 15:15:27.933  4685  4744 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-03 15:15:27.934  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:27.934  4685  4744 D BtGatt.GattService: current time is 107640408257
,11-03 15:15:27.934  4685  4744 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -82, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:15:27.934  4685  4744 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:15:27.934  4685  4744 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:15:27.934  4685  4744 E BtGatt.ContextMap: Context not found for ID 5
,11-03 15:15:27.941  4685  4744 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 15:15:27.941  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:27.941  4685  4748 D BtGatt.ScanManager: stopping BLe Batch
,11-03 15:15:27.946  4685  4744 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 15:15:27.946  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:15:27.946  4685  4748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:15:27.952  4685  4744 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 15:15:27.952  4685  4744 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:15:28.429  5612  5612 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 15:15:28.429  5612  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 15:15:28.429  5612  5612 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 15:15:32.925  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 15:15:32.926  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 15:15:32.926  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 15:15:32.926  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:32.926  5612  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 15:15:32.926  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 15:15:32.927  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 15:15:32.927  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
,11-03 15:15:32.927  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 15:15:32.927  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
,11-03 15:15:32.927  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:32.928  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 15:15:32.931  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.934  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.934  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.934  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.935  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:32.935  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 15:15:32.935  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.935  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.937  5612  5659 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-03 15:15:32.939  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:32.939  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:32.939  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:32.939  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:32.939  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:32.940  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:32.940  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.940  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.940  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:32.942  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.945  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.945  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.945  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.945  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:32.945  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:32.945  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.945  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
,11-03 15:15:32.947  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 15:15:32.948  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:32.948  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:32.948  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 15:15:32.948  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:32.948  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:32.949  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:32.949  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.949  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
,11-03 15:15:32.949  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:32.949  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.951  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.951  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.952  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.952  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:32.952  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:32.952  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.952  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
,11-03 15:15:32.953  5612  5659 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-03 15:15:32.953  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:32.953  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:32.953  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:32.953  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:32.953  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 15:15:32.954  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:32.954  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.954  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.954  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:32.954  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.956  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.957  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.957  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.957  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 15:15:32.957  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:32.957  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.958  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
,11-03 15:15:32.959  5612  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-03 15:15:32.959  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:32.959  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:32.959  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:32.960  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:32.960  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:32.960  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:32.960  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.960  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.960  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 15:15:32.960  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.962  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.962  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.962  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.963  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:32.963  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:32.963  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.963  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
,11-03 15:15:32.964  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-03 15:15:32.964  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 15:15:32.964  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 15:15:32.964  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 15:15:32.965  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 15:15:32.965  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 15:15:32.965  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 15:15:32.965  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 15:15:32.965  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 15:15:32.966  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:32.966  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:32.966  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:32.966  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:32.966  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:32.966  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:32.966  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.966  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
,11-03 15:15:32.966  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:32.966  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.969  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.969  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.970  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.970  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:32.970  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:32.970  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.970  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.971  5612  5659 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 15:15:32.971  5612  5659 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-03 15:15:32.971  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-03 15:15:32.974  5612  5659 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-03 15:15:32.974  5612  5659 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-03 15:15:32.974  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 15:15:32.974  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 15:15:32.974  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 15:15:32.974  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-03 15:15:32.974  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-03 15:15:32.975  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 15:15:32.976  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 15:15:32.976  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 15:15:32.976  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 15:15:32.976  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-03 15:15:32.976  5612  5659 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-03 15:15:32.976  5612  5659 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 15:15:32.976  5612  5659 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-03 15:15:32.976  5612  5659 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 15:15:32.976  5612  5659 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-03 15:15:32.976  5612  5659 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-03 15:15:32.976  5612  5659 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 15:15:32.977  5612  5659 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 15:15:32.977  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-03 15:15:32.980  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-03 15:15:32.982  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-03 15:15:32.982  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-03 15:15:32.983  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-03 15:15:32.983  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,11-03 15:15:32.983  5612  5659 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-03 15:15:32.983  5612  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-03 15:15:32.983  5612  5659 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 15:15:32.983  5612  5659 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-03 15:15:32.983  5612  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-03 15:15:32.984  5612  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-03 15:15:32.984  5612  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-03 15:15:32.984  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 15:15:32.984  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:32.984  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:32.985  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:32.985  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:32.985  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-03 15:15:32.986  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
,11-03 15:15:32.986  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.986  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.986  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:32.986  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.986  5612  5664 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-03 15:15:32.986  5612  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-03 15:15:32.987  5612  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-03 15:15:32.987  5612  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 15:15:32.987  5612  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-03 15:15:32.987  5612  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
,11-03 15:15:32.988  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:32.986  4697  4697 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[28653]" dev="sockfs" ino=28653 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 15:15:32.988  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.988  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.988  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:32.988  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:32.988  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.988  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.989  5612  5659 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-03 15:15:32.986  4697  4697 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[28653]" dev="sockfs" ino=28653 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 15:15:32.989  5612  5664 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-03 15:15:32.989  5612  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-03 15:15:32.989  5612  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-03 15:15:32.989  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:32.990  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:32.990  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:32.990  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:32.990  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:32.990  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:32.990  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.990  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.990  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:32.990  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.991  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.991  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.991  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.991  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:32.991  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscov,ery
11-03 15:15:32.991  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.992  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.992  5612  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-03 15:15:32.993  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:32.993  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:32.993  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:32.993  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:32.993  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:32.993  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:32.993  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.993  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.993  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:32.993  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.995  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.995  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.995  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.995  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:32.995  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:32.995  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.995  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.996  5612  5659 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-03 15:15:32.996  5612  5659 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-03 15:15:32.996  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 15:15:32.996  5612  5659 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-03 15:15:32.996  5612  5659 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 15:15:32.996  5612  5659 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-03 15:15:32.996  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 15:15:32.996  5612  5659 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-03 15:15:32.996  5612  5659 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 15:15:32.996  5612  5659 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 15:15:32.996  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 15:15:32.996  5612  5659 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-03 15:15:32.997  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:32.997  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:32.997  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:32.997  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:32.997  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:32.997  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:32.997  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.997  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.997  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:32.997  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.998  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.999  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.999  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:32.999  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:32.999  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:32.999  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:32.999  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:32.999  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:33.000  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:33.000  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:33.000  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:33.000  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:33.000  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 15:15:33.608   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-03 15:15:33.609   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 15:15:38.001  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:38.001  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:38.001  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:38.001  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 15:15:38.001  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:38.002  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:38.002  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:38.002  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 15:15:38.002  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:38.002  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:38.003  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:38.003  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 15:15:38.003  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:38.003  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:38.004  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:38.006  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:38.007  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.007  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.007  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:38.007  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 15:15:38.008  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:38.008  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:38.012  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 15:15:38.012  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 15:15:38.013  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 15:15:38.018  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-03 15:15:38.019  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 15:15:38.019  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 15:15:38.019  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 15:15:38.020  5612  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 15:15:38.020  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 15:15:38.020  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 15:15:38.020  5612  5612 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-03 15:15:38.020  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:38.021  5612  5666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 15:15:38.021  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 15:15:38.021  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 15:15:38.021  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 15:15:38.021  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 15:15:38.022  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-03 15:15:38.022  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 15:15:38.022  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:38.022  5612  5612 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 15:15:38.022  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:38.020  4908  4908 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33320]" dev="sockfs" ino=33320 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 15:15:38.020  4908  4908 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33320]" dev="sockfs" ino=33320 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 15:15:38.022  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 15:15:38.022  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 15:15:38.022  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 15:15:38.022  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.024  5612  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 15:15:38.024  5612  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 15:15:38.024  5612  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-03 15:15:38.024  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.024  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 15:15:38.024  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.024  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:38.024  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:38.025  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 15:15:38.025  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 15:15:38.025  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:38.025  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 15:15:38.025  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:38.025  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:38.025  5612  5612 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 15:15:38.025  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 15:15:38.025  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:38.025  5612  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 15:15:38.025  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:38.025  5612  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:38.025  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
,11-03 15:15:38.025  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:38.025  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.027  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.027  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.027  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.027  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:38.027  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:38.027  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:38.027  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:38.029  5612  5659 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-03 15:15:38.029  5612  5659 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 15:15:38.029  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 15:15:38.029  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 15:15:38.029  5612  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 15:15:38.029  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:38.029  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:38.030  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:38.030  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:38.030  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 15:15:38.030  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:38.030  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:38.030  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:38.030  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:38.030  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.032  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.032  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.032  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.032  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:38.032  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:38.032  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:38.032  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
,11-03 15:15:38.036  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:15:38.037  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:38.037  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:38.037  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:38.037  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:38.037  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:38.037  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 15:15:38.037  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
,11-03 15:15:38.037  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:38.037  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:38.039  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:38.039  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.039  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.039  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:38.039  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:38.039  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:38.039  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:38.041  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 15:15:38.042  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:15:38.042  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:15:38.042  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:15:38.042  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:15:38.042  5612  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@452c302 not in the list
11-03 15:15:38.042  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:38.042  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:38.042  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 15:15:38.042  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:38.044  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:15:38.044  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.044  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:15:38.044  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:15:38.044  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:15:38.044  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:15:38.044  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d413 not in the list
11-03 15:15:38.045  5612  5659 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-03 15:15:38.045  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 15:15:38.045  5612  5659 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-03 15:15:38.045  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 15:15:38.045  5612  5659 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-03 15:15:38.045  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 15:15:38.047  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 15:15:38.047  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-03 15:15:38.048  5612  5659 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-03 15:15:38.048  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 15:15:38.048  5612  5659 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-03 15:15:38.048  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 15:15:38.048  5612  5659 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-03 15:15:38.048  5612  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-03 15:15:38.049  5612  5659 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-03 15:15:38.049  5612  5659 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-03 15:15:38.049  5612  5659 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-03 15:15:38.049  5612  5659 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-03 15:15:38.049  5612  5659 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-03 15:15:38.049  5612  5659 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-03 15:15:38.050  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 15:15:38.050  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dbae380 added. We now have 3 listener(s)
11-03 15:15:38.050  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:15:38.053  5612  5659 D BluetoothAdapter: enable(): BT is already enabled..!
,11-03 15:15:38.053   930  3159 D WifiService: setWifiEnabled: true pid=5612, uid=10077
11-03 15:15:38.053   930  3159 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 15:15:38.115  4685  4892 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-03 15:15:38.116  4685  4894 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-03 15:15:38.526  5612  5612 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 15:15:38.609   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:39.611   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:40.611   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:41.042   930  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 15:15:41.612   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:42.613   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:43.059  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 15:15:43.059  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee40db9 added. We now have 4 listener(s)
11-03 15:15:43.060  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:15:43.072  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 15:15:43.072  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee40db9 removed from the list
,11-03 15:15:43.072  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 15:15:43.074  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 15:15:43.075  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95e65fe added. We now have 4 listener(s)
,11-03 15:15:43.075  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:15:43.077  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 15:15:43.077  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95e65fe removed from the list
,11-03 15:15:43.078  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:15:43.079  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 15:15:43.079  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b9015f added. We now have 4 listener(s)
,11-03 15:15:43.079  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:15:43.083   930  3159 D WifiService: setWifiEnabled: false pid=5612, uid=10077
,11-03 15:15:43.083   930  3159 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 15:15:43.087   930  2981 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 15:15:43.088   930  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-03 15:15:43.088   930  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 15:15:43.088   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 15:15:43.095  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 15:15:43.095  4685  4740 D BluetoothAdapterState: Current state: ON, message: 23
11-03 15:15:43.096  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 15:15:43.096  4685  4740 D BluetoothAdapterProperties: Setting state to 13
11-03 15:15:43.096  4685  4740 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-03 15:15:43.097  4685  4740 D BluetoothAdapterProperties: onBluetoothDisable()
11-03 15:15:43.098  4685  4740 I BluetoothAdapterState: Entering PendingCommandState
,11-03 15:15:43.102  4685  4685 D BluetoothMapService: onReceive
,11-03 15:15:43.102  4685  4685 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-03 15:15:43.103  4685  4685 D BluetoothMapService: STATE_TURNING_OFF
11-03 15:15:43.103  4685  4685 D BluetoothMapService: MAP Service closeService in
11-03 15:15:43.104  4685  4685 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 15:15:43.104  4685  4685 D ObexServerSockets0: shutdown(block = true)
11-03 15:15:43.106  5612  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 15:15:43.108  5612  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 15:15:43.108  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:43.108  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:43.108  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 15:15:43.108  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 15:15:43.108  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 15:15:43.108  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 15:15:43.108  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 15:15:43.109  5612  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 15:15:43.109  5612  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 15:15:43.109  4685  4685 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 15:15:43.109  5612  5659 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 15:15:43.109  4685  4918 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-03 15:15:43.109  4685  4685 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 15:15:43.109  4685  4894 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 15:15:43.110  4685  4919 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 15:15:43.111  4685  4685 I BtOppRfcommListener: stopping Accept Thread
11-03 15:15:43.112  4685  5319 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 15:15:43.112  4685  5319 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-03 15:15:43.114   930  5393 D DhcpClient: Clearing IP address
,11-03 15:15:43.114   506   924 D CommandListener: Clearing all IP addresses on wlan0
11-03 15:15:43.115  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 15:15:43.119  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 15:15:43.121   930   943 I ActivityManager: Start proc 5670:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-03 15:15:43.123  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 15:15:43.124  3585  5441 V NativeCrypto: Read error: ssl=0x7f9bb05000: I/O error during system call, Connection timed out
,11-03 15:15:43.125   506   924 D CommandListener: Setting iface cfg
,11-03 15:15:43.126  3585  5441 V NativeCrypto: SSL shutdown failed: ssl=0x7f9bb05000: I/O error during system call, Broken pipe
,11-03 15:15:43.126  4685  4744 D BluetoothAdapterProperties: Scan Mode:20
11-03 15:15:43.126  4685  4740 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-03 15:15:43.128  4685  4685 D HeadsetService: Received stop request...Stopping profile...
11-03 15:15:43.128  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:43.130   930   930 D BluetoothHeadset: Proxy object disconnected
,11-03 15:15:43.130   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 15:15:43.130  3826  3842 D BluetoothHeadset: Proxy object disconnected
11-03 15:15:43.131  3125  3137 D BluetoothHeadset: Proxy object disconnected
11-03 15:15:43.131   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 15:15:43.131   930   941 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-03 15:15:43.131   930  5391 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-03 15:15:43.131  4685  4685 D A2dpService: Received stop request...Stopping profile...
11-03 15:15:43.132  4685  4911 D A2dpStateMachine: Exit Disconnected: -1
,11-03 15:15:43.133   930   930 D BluetoothA2dp: Proxy object disconnected
11-03 15:15:43.133  4685  4685 V BluetoothAdapterState: isTurningOff()=true
11-03 15:15:43.133  4685  4685 V BluetoothAdapterState: isTurningOn()=false
,11-03 15:15:43.133  4685  4685 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:43.133  4685  4685 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:43.133  3125  3125 D HeadsetProfile: Bluetooth service disconnected
11-03 15:15:43.134  3125  3125 D BluetoothA2dp: Proxy object disconnected
11-03 15:15:43.134   930  5391 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-03 15:15:43.134   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-03 15:15:43.134   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 15:15:43.136   930  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-03 15:15:43.140   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-03 15:15:43.140  4685  4685 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-03 15:15:43.141  4685  4685 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 15:15:43.141   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-03 15:15:43.141  4685  4744 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 15:15:43.141  4685  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:15:43.141  4685  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:15:43.141  4685  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:15:43.141  4685  4744 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 15:15:43.141  4685  4685 D HidService: Received stop request...Stopping profile...
11-03 15:15:43.141  4685  4685 D HidService: Stopping Bluetooth HidService
11-03 15:15:43.142  4685  4685 V BluetoothAdapterState: isTurningOff()=true
11-03 15:15:43.143  4685  4685 V BluetoothAdapterState: isTurningOn()=false
11-03 15:15:43.143  4685  4685 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:43.143  4685  4685 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:43.144   532   532 E Parcel  : Reading a NULL string not supported here.
11-03 15:15:43.145   930   930 D RttService: SCAN_AVAILABLE : 1
11-03 15:15:43.145   930  3089 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 15:15:43.146   930  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-03 15:15:43.147  4685  4744 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 15:15:43.147  4685  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:15:43.147  4685  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:15:43.147  4685  4892 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 15:15:43.147  4685  4892 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 15:15:43.147  4685  4892 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 15:15:43.147  4685  4892 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 15:15:43.149  4685  4685 D HealthService: Received stop request...Stopping profile...
11-03 15:15:43.150  3780  3888 W QCNEJ   : |CORE| network lost: 100
11-03 15:15:43.152  3780  3888 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-03 15:15:43.152  3125  3125 D BluetoothInputDevice: Proxy object disconnected
11-03 15:15:43.152  3125  3125 D HidProfile: Bluetooth service disconnected
11-03 15:15:43.153  4685  4685 D PanService: Received stop request...Stopping profile...
11-03 15:15:43.155  4685  4685 D BluetoothMapService: Received stop request...Stopping profile...
11-03 15:15:43.155  4685  4685 D BluetoothMapService: stop()
11-03 15:15:43.155  4685  4685 D BluetoothMapAppObserver: deinitObservers()
11-03 15:15:43.155  4685  4685 D BluetoothMapAppObserver: removeReceiver()
11-03 15:15:43.157   930  5394 D DhcpClient: Receive thread stopped
11-03 15:15:43.157  4685  4685 D SapService: Received stop request...Stopping profile...
11-03 15:15:43.157  4685  4685 V SapService: stop()
11-03 15:15:43.160   930  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-03 15:15:43.161  4685  4685 V BluetoothAdapterState: isTurningOff()=true
11-03 15:15:43.161  4685  4685 V BluetoothAdapterState: isTurningOn()=false
11-03 15:15:43.161  4685  4685 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:43.161  4685  4685 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:43.161  4685  4685 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 15:15:43.161  4685  4685 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 15:15:43.161  4685  4685 V BluetoothAdapterState: isTurningOff()=true
11-03 15:15:43.161  4685  4685 V BluetoothAdapterState: isTurningOn()=false
11-03 15:15:43.161  4685  4685 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:43.161  4685  4685 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:43.161  4685  4685 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-03 15:15:43.161  4685  4744 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 15:15:43.162  4685  4744 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 15:15:43.162  4685  4685 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 15:15:43.162  4685  4685 V BluetoothAdapterState: isTurningOff()=true
11-03 15:15:43.162  4685  4685 V BluetoothAdapterState: isTurningOn()=false
11-03 15:15:43.162  4685  4685 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:43.162  4685  4685 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:43.163  4685  4685 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 15:15:43.163  4685  4685 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 15:15:43.163  3125  3125 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 15:15:43.163  3125  3125 D PanProfile: Bluetooth service disconnected
11-03 15:15:43.164  3125  3125 D BluetoothMap: Proxy object disconnected
11-03 15:15:43.164  3125  3125 D MapProfile: Bluetooth service disconnected
11-03 15:15:43.164  4685  4685 D BluetoothMapService: MAP Service closeService in
11-03 15:15:43.164  4685  4685 V BluetoothAdapterState: isTurningOff()=true
11-03 15:15:43.164  4685  4685 V BluetoothAdapterState: isTurningOn()=false
11-03 15:15:43.164  4685  4685 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:43.164  4685  4685 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:43.165  4685  4685 D BluetoothMapService: cleanup()
11-03 15:15:43.165  4685  4685 D BluetoothMapService: MAP Service closeService in
11-03 15:15:43.165  4685  4685 V BluetoothAdapterState: isTurningOff()=true
11-03 15:15:43.165  4685  4685 V BluetoothAdapterState: isTurningOn()=false
11-03 15:15:43.165  4685  4685 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:43.165  4685  4685 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:43.166  4685  4740 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 15:15:43.166  4685  4740 D BluetoothAdapterProperties: Setting state to 15
11-03 15:15:43.166  4685  4740 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 15:15:43.166   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:15:43.167  4685  4740 I BluetoothAdapterState: Entering BleOnState
11-03 15:15:43.167  3125  4015 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 15:15:43.168  3125  3141 D BluetoothPan: onBluetoothStateChange on: false
11-03 15:15:43.168  3826  3842 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:15:43.169   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 15:15:43.169  3125  3378 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 15:15:43.170  3125  3137 D BluetoothMap: onBluetoothStateChange: up=false
11-03 15:15:43.171  3125  4015 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 15:15:43.172  3125  3141 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:15:43.172   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:15:43.172   930  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 15:15:43.172   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:15:43.172  4685  4740 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 15:15:43.172  4685  4740 D BluetoothAdapterProperties: Setting state to 16
11-03 15:15:43.172  4685  4740 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 15:15:43.173  4685  4740 D BluetoothAdapterProperties: onBleDisable
11-03 15:15:43.173  4685  4740 I BluetoothAdapterState: Entering PendingCommandState
11-03 15:15:43.173  4685  4741 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 15:15:43.175  4685  4892 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 15:15:43.175  4685  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:15:43.175  4685  4744 D BluetoothAdapterProperties: Scan Mode:20
11-03 15:15:43.180  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 15:15:43.180  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 15:15:43.180  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:43.180  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:43.180  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 15:15:43.180  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 15:15:43.180  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 15:15:43.180  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 15:15:43.180  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 15:15:43.181  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 15:15:43.181  5612  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 15:15:43.181  5670  5670 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-03 15:15:43.185  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:43.198   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 15:15:43.200  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 15:15:43.205   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@90aa868:true
,11-03 15:15:43.207  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 15:15:43.216   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 15:15:43.216   506   924 D CommandListener: Clearing all IP addresses on wlan0
11-03 15:15:43.216   506   924 D TetherController: Setting IP forward enable = 0
,11-03 15:15:43.217   930  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-03 15:15:43.217   930  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 15:15:43.219   930   947 D Tethering: MasterInitialState.processMessage what=3
11-03 15:15:43.220   930  2981 D DhcpClient: doQuit
11-03 15:15:43.220   930  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 15:15:43.221  3486  3486 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-03 15:15:43.221  5276  5276 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9c16f79 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-03 15:15:43.221   930  5393 D DhcpClient: onQuitting
11-03 15:15:43.221  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 15:15:43.224  3975  3975 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-03 15:15:43.228  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 15:15:43.228  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 15:15:43.228  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:43.228  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:43.228  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 15:15:43.228  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 15:15:43.228  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 15:15:43.228  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 15:15:43.228  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 15:15:43.229  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 15:15:43.229  5612  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 15:15:43.235  5670  5670 D LocalBluetoothProfileManager: Adding local MAP profile
,11-03 15:15:43.239  5670  5670 D BluetoothMap: Create BluetoothMap proxy object
,11-03 15:15:43.245  5670  5670 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-03 15:15:43.251  5670  5670 D DockEventReceiver: finishStartingService: stopping service
,11-03 15:15:43.256  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 15:15:43.257  3486  3486 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 15:15:43.261  5670  5670 D DockEventReceiver: finishStartingService: stopping service
,11-03 15:15:43.262  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 15:15:43.262   930  3159 I ActivityManager: Killing 5416:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-03 15:15:43.264  3486  3486 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 15:15:43.265   506   924 E Netd    : netlink response contains error (No such file or directory)
11-03 15:15:43.265   506   924 D TetherController: Setting IP forward enable = 0
11-03 15:15:43.266   930  2983 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-03 15:15:43.266   930  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-03 15:15:43.285  3993  3993 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 15:15:43.285  3486  3486 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 15:15:43.289  3993  3993 D SystemUpdateService: onCreate
,11-03 15:15:43.293  3993  3993 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 15:15:43.299  3993  5706 I SystemUpdateService: active receiver: enabled
,11-03 15:15:43.300  3993  3993 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 15:15:43.302  3486  3486 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 15:15:43.309  3993  3993 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 15:15:43.310  3993  3993 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 15:15:43.312  3993  4303 I iu.UploadsManager: num queued entries: 0
,11-03 15:15:43.313  3993  4303 I iu.UploadsManager: num updated entries: 0
11-03 15:15:43.314  3993  4303 I iu.SyncManager: NEXT; no task
,11-03 15:15:43.314  3993  5706 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 15:15:43.316  3993  5706 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-03 15:15:43.316  3993  5706 I SystemUpdateService: now status is 0 (complete)
11-03 15:15:43.316  3993  5706 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 15:15:43.316  3993  5706 I SystemUpdateService: file has been verified
11-03 15:15:43.316  3993  5706 I SystemUpdateService: OTA package size = 21989297
,11-03 15:15:43.323   930  3202 I ActivityManager: Start proc 5708:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-03 15:15:43.328  3993  5706 I SystemUpdateService: showing system update notification
,11-03 15:15:43.338   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 15:15:43.342  3993  3993 D SystemUpdateService: onDestroy
,11-03 15:15:43.362  5708  5708 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-03 15:15:43.365  5708  5708 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 15:15:43.372  5708  5708 D SprintDMHelper: simOperator: 
,11-03 15:15:43.372  5708  5708 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 15:15:43.380  4685  4744 I bt_hci  : shut_down
,11-03 15:15:43.386  4685  4750 I bt_vendor: low_power_mode_cb
,11-03 15:15:43.389  4685  4750 D bt_hwcfg: hw_epilog_process
,11-03 15:15:43.390   930  3202 I ActivityManager: Killing 5276:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-03 15:15:43.392  4685  4750 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-03 15:15:43.392  4685  4750 I bt_vendor: epilog_cb
11-03 15:15:43.392  4685  4750 I bt_hci  : epilog_finished_callback
,11-03 15:15:43.407  4513  4513 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 15:15:43.407   930  2981 D wifi    : In wifi stop Hal
11-03 15:15:43.407   930  2981 D wifi    : halHandle = 0x7f80d72b80, mVM = 0x7f9d38d140, mCls = 0x100a02
11-03 15:15:43.407   930  3485 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 15:15:43.408   930  3485 D WifiHAL : Got a signal to exit!!!
11-03 15:15:43.408   930  3485 I WifiHAL : Exit wifi_event_loop
11-03 15:15:43.408   930  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 15:15:43.408   930  2981 E WifiHAL : Event processing terminated
,11-03 15:15:43.408   930  2981 D wifi    : In wifi cleaned up handler
,11-03 15:15:43.408   930  2981 I WifiHAL : Internal cleanup completed
11-03 15:15:43.410  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 15:15:43.411  3751  4217 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 15:15:43.421   930   943 I ActivityManager: Start proc 5721:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-03 15:15:43.425  4685  4744 I bt_hci_h4: hal_close
,11-03 15:15:43.425  4685  4744 I bt_userial_vendor: device fd = 54 close
,11-03 15:15:43.429   930  3485 D wifi    : set interface wlan0 flags (DOWN)
,11-03 15:15:43.431   930  2981 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 15:15:43.451  5721  5721 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-03 15:15:43.458   930  3430 I ActivityManager: Killing 3897:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-03 15:15:43.535  4685  4741 D bt_stack_manager: event_shut_down_stack finished.
,11-03 15:15:43.535  4685  4740 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 15:15:43.537  4685  4740 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-03 15:15:43.537  4685  4685 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 15:15:43.537  4685  4685 D BtGatt.GattService: Received stop request...Stopping profile...
11-03 15:15:43.538  4685  4685 D BtGatt.GattService: stop()
11-03 15:15:43.538  4685  4685 D BtGatt.AdvertiseManager: advertise clients cleared
,11-03 15:15:43.540  4685  4685 V BluetoothAdapterState: isTurningOff()=false
,11-03 15:15:43.540  4685  4685 V BluetoothAdapterState: isTurningOn()=false
11-03 15:15:43.540  4685  4685 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:43.540  4685  4685 V BluetoothAdapterState: isBleTurningOff()=true
11-03 15:15:43.540  4685  4740 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-03 15:15:43.540  4685  4740 D BluetoothAdapterProperties: Setting state to 10
11-03 15:15:43.540  4685  4740 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 15:15:43.541  4685  4740 I BluetoothAdapterState: Entering OffState
,11-03 15:15:43.541   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 15:15:43.547  4685  4685 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 15:15:43.548  4685  4685 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 15:15:43.548  4685  4685 I BluetoothServiceJni: cleanupNative: return from cleanup
11-03 15:15:43.549  4685  4741 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 15:15:43.552  4685  4685 I art     : System.exit called, status: 0
,11-03 15:15:43.552  4685  4685 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 15:15:43.576   930  3599 I ActivityManager: Process com.android.bluetooth (pid 4685) has died
,11-03 15:15:43.614   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 15:15:43.633   930   947 D Tethering: InitialState.processMessage what=4
,11-03 15:15:43.637   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 15:15:44.269   930   939 I art     : Background partial concurrent mark sweep GC freed 50957(3MB) AllocSpace objects, 17(468KB) LOS objects, 33% free, 29MB/43MB, paused 1.587ms total 123.932ms
,11-03 15:15:48.112   930  3840 D WifiService: setWifiEnabled: true pid=5612, uid=10077
11-03 15:15:48.112   930  3840 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 15:15:48.126   506   924 D SoftapController: Softap fwReload - Ok
,11-03 15:15:48.131   506   924 D CommandListener: Setting iface cfg
,11-03 15:15:48.132   506   924 D CommandListener: Trying to bring down wlan0
11-03 15:15:48.133   506   924 D CommandListener: Clearing all IP addresses on wlan0
,11-03 15:15:48.137   930  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 15:15:48.614   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:48.697   930  2981 D wifi    : set interface wlan0 flags (UP)
,11-03 15:15:48.697   930  2981 I WifiHAL : Initializing wifi
11-03 15:15:48.698   930  2981 I WifiHAL : Creating socket
,11-03 15:15:48.703   930  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-03 15:15:48.703   930  2981 D wifi    : Did set static halHandle = 0x7f80d72b80
11-03 15:15:48.703   930  2981 D wifi    : halHandle = 0x7f80d72b80, mVM = 0x7f9d38d140, mCls = 0x2019fe
11-03 15:15:48.703   930  2981 D wifi    : array field set
11-03 15:15:48.704   930  2981 I WifiNative-HAL: interface[0] = wlan0
11-03 15:15:48.705   930  5739 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547622431616
11-03 15:15:48.705   930  5739 D wifi    : waitForHalEvents called, vm = 0x7f9d38d140, obj = 0x2019fe, env = 0x7f854d6840
,11-03 15:15:48.712   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 15:15:48.763  5740  5740 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 15:15:48.807   930  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 15:15:48.812  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:48.829  5740  5740 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 15:15:48.859  5740  5740 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 15:15:48.859  5740  5740 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 15:15:48.872   930  2981 D WifiConfigStore: Loading config and enabling all networks 
,11-03 15:15:48.878  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 15:15:48.878  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 15:15:48.878  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:48.878  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:48.878  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 15:15:48.878  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 15:15:48.878  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 15:15:48.878  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 15:15:48.878  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 15:15:48.878  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 15:15:48.878  5612  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 15:15:48.889   930  2981 D WifiConfigStore: loaded 0 passpoint configs
,11-03 15:15:48.890   930  2981 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-03 15:15:48.890   930  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-03 15:15:48.891   930  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-03 15:15:48.891   930  2981 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-03 15:15:48.891   930  2981 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-03 15:15:48.892   930  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-03 15:15:48.892   930  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-03 15:15:48.892   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 15:15:48.892   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 15:15:48.892   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 15:15:48.892   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 15:15:48.892   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 15:15:48.894   930  2981 D WifiNative-HAL: Setting external_sim to 1
,11-03 15:15:48.894   930  2981 D wifi    : setting dfs flag to true, 0x7f81c224e0
11-03 15:15:48.894   930  2981 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 15:15:48.894   930  2981 D wifi    : setting scan oui 0x7f81c224e0
,11-03 15:15:48.894   930  2981 D WifiHAL : Sending mac address OUI
,11-03 15:15:48.894  4513  4513 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 15:15:48.897   930  2981 E native  : do suspend false
,11-03 15:15:48.904   930  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-03 15:15:48.904   930   930 D RttService: SCAN_AVAILABLE : 3
11-03 15:15:48.904   930  3089 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 15:15:48.909   506   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 15:15:48.912   506   924 D CommandListener: Setting iface cfg
,11-03 15:15:48.913   930  2980 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-03 15:15:48.913   930  2980 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 15:15:48.920   930  2980 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 15:15:48.921   930  2980 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 15:15:48.927   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128633 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-03 15:15:49.618   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:50.619   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:51.621   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:51.982  5740  5740 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 15:15:51.987  5740  5740 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 15:15:51.992  5740  5740 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 15:15:52.046   930  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 15:15:52.047   930  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-03 15:15:52.048   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 15:15:52.058   930  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 15:15:52.091   930  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 15:15:52.095  5740  5740 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 15:15:52.537  5740  5740 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 15:15:52.568  5740  5740 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 15:15:52.569  5740  5740 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 15:15:52.579   930  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 15:15:52.580   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 15:15:52.580   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 15:15:52.594   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 15:15:52.606   506   924 D CommandListener: Setting iface cfg
,11-03 15:15:52.612   930  2981 D WifiStateMachine: Start Dhcp Watchdog 2
,11-03 15:15:52.617   930  5746 D DhcpClient: Receive thread started
,11-03 15:15:52.622   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 15:15:52.622   930  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 15:15:52.622   930  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
11-03 15:15:52.623   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:15:52.703   930  2981 E native  : do suspend false
,11-03 15:15:52.718   930  5745 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 15:15:52.736   930  5746 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-03 15:15:52.737   930  5745 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-03 15:15:52.739   930  5745 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 15:15:52.752   930  5746 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 15:15:52.753   930  5745 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-03 15:15:52.757   506   924 D CommandListener: Setting iface cfg
11-03 15:15:52.761   930  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 15:15:52.765   930  5745 D DhcpClient: Scheduling renewal in 86399s
,11-03 15:15:52.774   930  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-03 15:15:52.776   930  2981 D WifiConfigStore: No blacklist allowed without epno enabled
11-03 15:15:52.777   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-03 15:15:52.779   930  2983 D ConnectivityService: Adding iface wlan0 to network 101
,11-03 15:15:52.799   930  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-03 15:15:52.833   930  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-03 15:15:52.833   930  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-03 15:15:52.836   930  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-03 15:15:52.838   930  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-03 15:15:52.842   930  2983 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-03 15:15:52.849   930  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 15:15:52.853   930  2983 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-03 15:15:52.854   930  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-03 15:15:52.854   930  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-03 15:15:52.854   930  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 15:15:52.854   930  2983 D ConnectivityService:    accepting network in place of null
11-03 15:15:52.854   930  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 15:15:52.855   930  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 15:15:52.860   930  5744 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132566, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 15:15:52.885   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 15:15:52.907   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 15:15:52.911   930  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-03 15:15:52.911   930  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 15:15:52.911  3780  3888 W QCNEJ   : |CORE| network available: 101
,11-03 15:15:52.914   930   947 D Tethering: MasterInitialState.processMessage what=3
11-03 15:15:52.914   930  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-03 15:15:52.916  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 15:15:52.916  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 15:15:52.916  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:52.916  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:52.916  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 15:15:52.916  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 15:15:52.916  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 15:15:52.916  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 15:15:52.916  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 15:15:52.916  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 15:15:52.916  5612  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 15:15:52.917  3780  3888 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-03 15:15:52.918  3780  3888 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-03 15:15:52.919  3780  3888 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-03 15:15:52.925  3993  3993 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 15:15:52.928  3993  3993 D SystemUpdateService: onCreate
11-03 15:15:52.929  3975  3975 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-03 15:15:52.933  3993  3993 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 15:15:52.944  3993  3993 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-03 15:15:52.949  3993  4303 I iu.UploadsManager: num queued entries: 0
,11-03 15:15:52.950  3993  4303 I iu.UploadsManager: num updated entries: 0
11-03 15:15:52.951  3993  5756 I SystemUpdateService: active receiver: enabled
,11-03 15:15:52.954  3993  3993 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 15:15:52.955  3993  3993 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-03 15:15:52.957  5708  5708 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 15:15:52.960  5708  5708 D SprintDMHelper: simOperator: 
11-03 15:15:52.960  5708  5708 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 15:15:52.983  3993  5756 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 15:15:52.984  3993  4303 I iu.SyncManager: NEXT; no task
,11-03 15:15:52.990  3993  5756 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-03 15:15:52.990  3993  5756 I SystemUpdateService: now status is 0 (complete)
11-03 15:15:52.990  3993  5756 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 15:15:52.990  3993  5756 I SystemUpdateService: file has been verified
11-03 15:15:52.990  3993  5756 I SystemUpdateService: OTA package size = 21989297
,11-03 15:15:52.996  3993  5756 I SystemUpdateService: showing system update notification
,11-03 15:15:53.003   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 15:15:53.005  3993  3993 D SystemUpdateService: onDestroy
,11-03 15:15:53.085   930  5743 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 15:15:53.123   930  3840 D WifiService: setWifiEnabled: false pid=5612, uid=10077
11-03 15:15:53.124   930  3840 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 15:15:53.126   930  2981 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-03 15:15:53.126   930  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 15:15:53.126   930  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 15:15:53.126   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 15:15:53.136   930  5745 D DhcpClient: Clearing IP address
11-03 15:15:53.136   506   924 D CommandListener: Clearing all IP addresses on wlan0
,11-03 15:15:53.138   506   924 D CommandListener: Setting iface cfg
,11-03 15:15:53.140   930  5746 D DhcpClient: Receive thread stopped
,11-03 15:15:53.142   930  5743 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-03 15:15:53.143   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,11-03 15:15:53.147   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-03 15:15:53.147   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-03 15:15:53.150   532   532 E Parcel  : Reading a NULL string not supported here.
11-03 15:15:53.152   930   930 D RttService: SCAN_AVAILABLE : 1
11-03 15:15:53.153   930  3089 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 15:15:53.153   930  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 15:15:53.153   930  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-03 15:15:53.155  3780  3888 W QCNEJ   : |CORE| network lost: 101
11-03 15:15:53.155  3780  3888 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-03 15:15:53.157   930  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 15:15:53.175   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 15:15:53.194   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 15:15:53.194   506   924 D CommandListener: Clearing all IP addresses on wlan0
11-03 15:15:53.194   930  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-03 15:15:53.194   930  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 15:15:53.196   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-03 15:15:53.198   930  2981 D DhcpClient: doQuit
11-03 15:15:53.198   930  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 15:15:53.198   930  5745 D DhcpClient: onQuitting
11-03 15:15:53.199  5740  5740 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-03 15:15:53.200  3975  3975 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-03 15:15:53.204  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 15:15:53.204  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 15:15:53.204  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:53.204  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:53.204  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 15:15:53.204  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 15:15:53.204  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 15:15:53.204  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 15:15:53.204  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 15:15:53.204  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 15:15:53.204  5612  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 15:15:53.209  5740  5740 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-03 15:15:53.210  3993  3993 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 15:15:53.211  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:53.213  3993  3993 D SystemUpdateService: onCreate
,11-03 15:15:53.215  5740  5740 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 15:15:53.216  3993  3993 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 15:15:53.222  3993  5769 I SystemUpdateService: active receiver: enabled
,11-03 15:15:53.224  3993  3993 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 15:15:53.229  3993  4303 I iu.UploadsManager: num queued entries: 0
,11-03 15:15:53.229  3993  4303 I iu.UploadsManager: num updated entries: 0
11-03 15:15:53.230  3993  4303 I iu.SyncManager: NEXT; no task
,11-03 15:15:53.232  3993  3993 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 15:15:53.234  3993  3993 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 15:15:53.235  5708  5708 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 15:15:53.240  5708  5708 D SprintDMHelper: simOperator: 
11-03 15:15:53.240  5708  5708 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 15:15:53.249  5740  5740 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 15:15:53.252  3993  5769 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 15:15:53.255  5740  5740 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 15:15:53.259   506   924 E Netd    : netlink response contains error (No such file or directory)
,11-03 15:15:53.259  3993  5769 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-03 15:15:53.259  3993  5769 I SystemUpdateService: now status is 0 (complete)
11-03 15:15:53.259  3993  5769 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 15:15:53.260  3993  5769 I SystemUpdateService: file has been verified
11-03 15:15:53.260   930  2983 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-03 15:15:53.260   930  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-03 15:15:53.261  3993  5769 I SystemUpdateService: OTA package size = 21989297
,11-03 15:15:53.275  3993  5769 I SystemUpdateService: showing system update notification
,11-03 15:15:53.280   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 15:15:53.282  3993  3993 D SystemUpdateService: onDestroy
,11-03 15:15:53.359   930  2981 D wifi    : In wifi stop Hal
,11-03 15:15:53.359   930  2981 D wifi    : halHandle = 0x7f80d72b80, mVM = 0x7f9d38d140, mCls = 0x2019fe
11-03 15:15:53.360  4513  4513 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 15:15:53.360   930  5739 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 15:15:53.360   930  5739 D WifiHAL : Got a signal to exit!!!
,11-03 15:15:53.360   930  5739 I WifiHAL : Exit wifi_event_loop
,11-03 15:15:53.361  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 15:15:53.361   930  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 15:15:53.361   930  2981 E WifiHAL : Event processing terminated
,11-03 15:15:53.361   930  2981 D wifi    : In wifi cleaned up handler
11-03 15:15:53.362   930  2981 I WifiHAL : Internal cleanup completed
11-03 15:15:53.363  3751  4217 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 15:15:53.385   930  5739 D wifi    : set interface wlan0 flags (DOWN)
,11-03 15:15:53.385   930  2981 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 15:15:53.591   930   947 D Tethering: InitialState.processMessage what=4
,11-03 15:15:53.596   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 15:15:53.623   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 15:15:53.911   930  2983 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-03 15:15:58.165   930   947 I ActivityManager: Start proc 5776:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 15:15:58.252  5776  5776 D AdapterServiceConfig: Adding HeadsetService
,11-03 15:15:58.253  5776  5776 D AdapterServiceConfig: Adding A2dpService
11-03 15:15:58.253  5776  5776 D AdapterServiceConfig: Adding HidService
11-03 15:15:58.253  5776  5776 D AdapterServiceConfig: Adding HealthService
11-03 15:15:58.253  5776  5776 D AdapterServiceConfig: Adding PanService
11-03 15:15:58.253  5776  5776 D AdapterServiceConfig: Adding GattService
,11-03 15:15:58.253  5776  5776 D AdapterServiceConfig: Adding BluetoothMapService
11-03 15:15:58.253  5776  5776 D AdapterServiceConfig: Adding SapService
,11-03 15:15:58.263   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@988a10f:true
,11-03 15:15:58.264  5776  5776 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 15:15:58.267  5776  5776 I bt_bluedroid: init
,11-03 15:15:58.267  5776  5788 I BluetoothAdapterState: Entering OffState
,11-03 15:15:58.269  5776  5789 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-03 15:15:58.269  5776  5789 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 15:15:58.269  5776  5789 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 15:15:58.269  5776  5789 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-03 15:15:58.269  5776  5776 I bt_bluedroid: get_profile_interface socket
,11-03 15:15:58.271  5776  5792 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 15:15:58.272  5776  5776 I bt_bluedroid: get_profile_interface sdp
11-03 15:15:58.272  5776  5792 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 15:15:58.276  5776  5787 I bt_bluedroid: config_hci_snoop_log
,11-03 15:15:58.276   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 15:15:58.280  5776  5788 D BluetoothAdapterState: Current state: OFF, message: 0
11-03 15:15:58.280  5776  5788 D BluetoothAdapterProperties: Setting state to 14
,11-03 15:15:58.280  5776  5788 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-03 15:15:58.282  5776  5788 D BluetoothBondStateMachine: make
,11-03 15:15:58.283  5776  5793 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 15:15:58.285  5776  5788 I BluetoothAdapterState: Entering PendingCommandState
,11-03 15:15:58.286  5776  5776 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 15:15:58.288  5776  5776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
11-03 15:15:58.289  5776  5776 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 15:15:58.289  5776  5776 D BtGatt.GattService: Received start request. Starting profile...
11-03 15:15:58.289  5776  5776 D BtGatt.GattService: start()
11-03 15:15:58.289  5776  5776 I bt_bluedroid: get_profile_interface gatt
11-03 15:15:58.290  5776  5776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
11-03 15:15:58.290  5776  5776 D BtGatt.AdvertiseManager: advertise manager created
,11-03 15:15:58.294  5776  5776 V BluetoothAdapterState: isTurningOff()=false
11-03 15:15:58.295  5776  5776 V BluetoothAdapterState: isTurningOn()=false
11-03 15:15:58.295  5776  5776 V BluetoothAdapterState: isBleTurningOn()=true
11-03 15:15:58.295  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:58.295  5776  5788 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-03 15:15:58.296  5776  5788 I bt_bluedroid: bt_bluedroid
11-03 15:15:58.296  5776  5789 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-03 15:15:58.297  5776  5789 I bt_hci  : start_up
,11-03 15:15:58.302  5776  5789 I bt_vendor: alloc value 0xf3f71871
11-03 15:15:58.302  5776  5789 I bt_vendor: init
11-03 15:15:58.302  5776  5789 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 15:15:58.302  5776  5789 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 15:15:58.412  5776  5789 D bt_hci  : start_up starting async portion
11-03 15:15:58.412  5776  5796 I bt_hci  : event_finish_startup
11-03 15:15:58.412  5776  5796 I bt_hci_h4: hal_open
11-03 15:15:58.412  5776  5796 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 15:15:58.410  5797  5797 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 15:15:58.414  5776  5796 I bt_userial_vendor: device fd = 54 open
,11-03 15:15:58.427  5776  5796 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 15:15:58.429  5776  5796 D bt_hwcfg: Chipset BCM4358A3
,11-03 15:15:58.429  5776  5796 D bt_hwcfg: Target name = [BCM4358A3]
11-03 15:15:58.429  5776  5796 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 15:15:58.823  5776  5796 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 15:15:58.823  5776  5796 D bt_hwcfg: Settlement delay -- 100 ms
11-03 15:15:58.823  5776  5796 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 15:15:58.957  5776  5796 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-03 15:15:58.958  5776  5796 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 15:15:58.959  5776  5796 I bt_hwcfg: vendor lib fwcfg completed
,11-03 15:15:58.959  5776  5796 I bt_vendor: firmware callback
,11-03 15:15:58.959  5776  5796 I bt_hci  : firmware_config_callback
,11-03 15:15:58.968  5776  5799 I bt_btu  : btu_task pending for preload complete event
11-03 15:15:58.968  5776  5799 I bt_btu_task: Bluetooth chip preload is complete
11-03 15:15:58.968  5776  5799 I bt_btu  : btu_task received preload complete event
,11-03 15:15:58.974  5776  5799 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 15:15:58.975  5776  5799 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 15:15:58.975  5776  5799 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-03 15:15:58.975  5776  5799 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 15:15:58.975  5776  5799 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-03 15:15:58.975  5776  5799 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 15:15:58.975  5776  5799 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-03 15:15:58.975  5776  5799 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 15:15:58.975  5776  5799 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 15:15:58.975  5776  5799 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 15:15:58.976  5776  5799 I         : BTE_InitTraceLevels -- TRC_SDP
,11-03 15:15:58.976  5776  5799 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 15:15:58.976  5776  5799 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 15:15:58.976  5776  5799 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-03 15:15:58.976  5776  5799 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 15:15:59.062  5776  5799 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3eef549
11-03 15:15:59.062  5776  5799 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3eef549 
,11-03 15:15:59.084  5776  5792 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 15:15:59.085  5776  5792 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 15:15:59.086  5776  5792 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 15:15:59.088  5776  5792 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 15:15:59.090  5776  5792 D BluetoothAdapterProperties: Scan Mode:20
,11-03 15:15:59.091  5776  5792 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 15:15:59.091  5776  5792 D bt_hci  : do_postload posting postload work item
11-03 15:15:59.092  5776  5796 I bt_hci  : event_postload
11-03 15:15:59.092  5776  5796 I bt_vendor: sco_config_cb
11-03 15:15:59.092  5776  5796 I bt_hci  : sco_config_callback postload finished.
,11-03 15:15:59.097  5776  5792 D bt_bte_conf: Device ID record 1 : primary
,11-03 15:15:59.097  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:59.097  5776  5792 D bt_bte_conf:   vendorId            = 000f
11-03 15:15:59.097  5776  5792 D bt_bte_conf:   vendorIdSource      = 0001
11-03 15:15:59.097  5776  5792 D bt_bte_conf:   product             = 1200
,11-03 15:15:59.097  5776  5792 D bt_bte_conf:   version             = 1436
11-03 15:15:59.097  5776  5792 D bt_bte_conf:   clientExecutableURL = 
11-03 15:15:59.097  5776  5792 D bt_bte_conf:   serviceDescription  = 
11-03 15:15:59.097  5776  5792 D bt_bte_conf:   documentationURL    = 
11-03 15:15:59.097  5776  5792 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 15:15:59.098  5776  5789 D bt_stack_manager: event_start_up_stack finished
11-03 15:15:59.098  5776  5788 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-03 15:15:59.098  5776  5788 D BluetoothAdapterProperties: Setting state to 15
11-03 15:15:59.098  5776  5788 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 15:15:59.099  5776  5788 I BluetoothAdapterState: Entering BleOnState
11-03 15:15:59.100  5776  5796 I bt_vendor: low_power_mode_cb
11-03 15:15:59.102  5776  5788 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 15:15:59.102  5776  5788 D BluetoothAdapterProperties: Setting state to 11
11-03 15:15:59.102  5776  5788 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 15:15:59.107  5776  5776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
,11-03 15:15:59.107  5776  5776 D HeadsetService: Received start request. Starting profile...
11-03 15:15:59.108  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:15:59.110  5776  5776 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 15:15:59.110  5776  5776 D HeadsetStateMachine: make
,11-03 15:15:59.119  5776  5776 D HeadsetStateMachine: max_hf_connections = 1
,11-03 15:15:59.119  5776  5776 I bt_bluedroid: get_profile_interface handsfree
11-03 15:15:59.120  5776  5792 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-03 15:15:59.120  5776  5792 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
11-03 15:15:59.122  5776  5788 I BluetoothAdapterState: Entering PendingCommandState
,11-03 15:15:59.124  5776  5776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
,11-03 15:15:59.125  5776  5776 D A2dpService: Received start request. Starting profile...
,11-03 15:15:59.125  5776  5776 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 15:15:59.126  5776  5776 I bt_bluedroid: get_profile_interface avrcp
,11-03 15:15:59.131  5776  5776 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 15:15:59.131  5776  5776 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 15:15:59.131  5776  5776 D A2dpStateMachine: make
11-03 15:15:59.132  5776  5776 I bt_bluedroid: get_profile_interface a2dp
,11-03 15:15:59.132  5776  5792 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 15:15:59.135  5776  5807 D A2dpStateMachine: Enter Disconnected: -2
,11-03 15:15:59.135  5776  5776 I BluetoothHidServiceJni: classInitNative: succeeds
,11-03 15:15:59.136  5776  5776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
,11-03 15:15:59.137  5776  5776 D HidService: Received start request. Starting profile...
,11-03 15:15:59.137  5776  5776 I bt_bluedroid: get_profile_interface hidhost
11-03 15:15:59.138  5776  5792 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ed056d
11-03 15:15:59.138  5776  5776 D HidService: setHidService(): set to: null
11-03 15:15:59.138  5776  5792 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 15:15:59.139  5776  5776 I BluetoothHealthServiceJni: classInitNative: succeeds
11-03 15:15:59.140  5776  5776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
11-03 15:15:59.140  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 15:15:59.141  5776  5776 D HealthService: Received start request. Starting profile...
11-03 15:15:59.142  5670  5670 D BluetoothInputDevice: Proxy object connected
11-03 15:15:59.142  5776  5776 I bt_bluedroid: get_profile_interface health
11-03 15:15:59.142  5670  5670 D HidProfile: Bluetooth service connected
11-03 15:15:59.143  5776  5776 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-03 15:15:59.143  5776  5776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
11-03 15:15:59.144  5670  5670 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 15:15:59.145  5670  5670 D PanProfile: Bluetooth service connected
11-03 15:15:59.145  5776  5776 D PanService: Received start request. Starting profile...
11-03 15:15:59.145  5776  5776 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 15:15:59.145  5776  5776 I bt_bluedroid: get_profile_interface pan
11-03 15:15:59.146  5776  5792 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 15:15:59.148  5776  5776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
,11-03 15:15:59.149  5670  5670 D BluetoothMap: Proxy object connected
,11-03 15:15:59.149  5670  5670 D MapProfile: Bluetooth service connected
11-03 15:15:59.150  5670  5670 D BluetoothMap: getConnectedDevices()
11-03 15:15:59.150  5776  5776 D BluetoothMapService: Received start request. Starting profile...
11-03 15:15:59.150  5670  5670 D BluetoothMap: Bluetooth is Not enabled
11-03 15:15:59.150  5776  5776 D BluetoothMapService: start()
,11-03 15:15:59.153  5776  5776 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-03 15:15:59.153  5776  5776 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-03 15:15:59.154  5776  5776 D BluetoothMapAppObserver: createReceiver()
,11-03 15:15:59.155  5776  5776 D BluetoothMapAppObserver: initObservers()
,11-03 15:15:59.155  5776  5776 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 15:15:59.161  5776  5776 V SapService: SapBinder()
,11-03 15:15:59.161  5776  5776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
11-03 15:15:59.162  5776  5776 D SapService: Received start request. Starting profile...
11-03 15:15:59.162  5776  5776 V SapService: start()
,11-03 15:15:59.163  5776  5776 V BluetoothAdapterState: isTurningOff()=false
,11-03 15:15:59.163  5776  5776 V BluetoothAdapterState: isTurningOn()=true
11-03 15:15:59.163  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:59.164  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:59.164  5776  5776 V BluetoothAdapterState: isTurningOff()=false
11-03 15:15:59.164  5776  5776 V BluetoothAdapterState: isTurningOn()=true
,11-03 15:15:59.164  5776  5805 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 15:15:59.164  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:59.164  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 15:15:59.164  5776  5776 V BluetoothAdapterState: isTurningOff()=false
11-03 15:15:59.164  5776  5776 V BluetoothAdapterState: isTurningOn()=true
11-03 15:15:59.165  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:59.165  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:59.165  5776  5776 V BluetoothAdapterState: isTurningOff()=false
11-03 15:15:59.165  5776  5776 V BluetoothAdapterState: isTurningOn()=true
11-03 15:15:59.165  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:59.165  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 15:15:59.166  5776  5776 V BluetoothAdapterState: isTurningOff()=false
11-03 15:15:59.166  5776  5776 V BluetoothAdapterState: isTurningOn()=true
11-03 15:15:59.166  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:59.166  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:59.166  5776  5776 V BluetoothAdapterState: isTurningOff()=false
11-03 15:15:59.166  5776  5776 V BluetoothAdapterState: isTurningOn()=true
11-03 15:15:59.166  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:59.166  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 15:15:59.167  5776  5776 V BluetoothAdapterState: isTurningOff()=false
11-03 15:15:59.167  5776  5776 V BluetoothAdapterState: isTurningOn()=true
11-03 15:15:59.167  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:15:59.167  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:15:59.168  5776  5788 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 15:15:59.168  5776  5788 D BluetoothAdapterProperties: ScanMode =  20
11-03 15:15:59.168  5776  5788 D BluetoothAdapterProperties: State =  11
11-03 15:15:59.168  5776  5788 D BluetoothAdapterProperties: Setting state to 12
11-03 15:15:59.168  5776  5788 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 15:15:59.169  5776  5788 I BluetoothAdapterState: Entering OnState
11-03 15:15:59.169   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 15:15:59.169  3125  4015 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 15:15:59.170  5776  5792 D BluetoothAdapterProperties: Scan Mode:21
11-03 15:15:59.170  5776  5792 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 15:15:59.170  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 15:15:59.172  3125  3141 D BluetoothPan: onBluetoothStateChange on: true
11-03 15:15:59.173  3125  3125 D BluetoothA2dp: Proxy object connected
11-03 15:15:59.174  5670  5682 D BluetoothMap: onBluetoothStateChange: up=true
11-03 15:15:59.175  5670  5681 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 15:15:59.175  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 15:15:59.175  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:15:59.175  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:15:59.175  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 15:15:59.175  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 15:15:59.175  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 15:15:59.175  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 15:15:59.175  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 15:15:59.175  3125  3125 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 15:15:59.175  3125  3125 D PanProfile: Bluetooth service connected
11-03 15:15:59.176  3826  3841 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 15:15:59.176   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 15:15:59.177  5612  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 15:15:59.177   930   930 D BluetoothA2dp: Proxy object connected
11-03 15:15:59.177  5670  5682 D BluetoothPan: onBluetoothStateChange on: true
11-03 15:15:59.177  3125  4015 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 15:15:59.179  3125  3378 D BluetoothMap: onBluetoothStateChange: up=true
11-03 15:15:59.180  3125  3137 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 15:15:59.180  3125  3125 D BluetoothMap: Proxy object connected
11-03 15:15:59.180  3125  3125 D MapProfile: Bluetooth service connected
11-03 15:15:59.180  3125  3125 D BluetoothMap: getConnectedDevices()
11-03 15:15:59.181  5776  5776 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 15:15:59.181  5776  5776 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 15:15:59.181  3125  3378 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 15:15:59.182  3125  3125 D BluetoothInputDevice: Proxy object connected
11-03 15:15:59.182  3125  3125 D HidProfile: Bluetooth service connected
11-03 15:15:59.182  5670  5681 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 15:15:59.182   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 15:15:59.182   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 15:15:59.182  5776  5776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 15:15:59.184  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 15:15:59.184   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 15:15:59.185  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 15:15:59.188  5670  5670 D LocalBluetoothProfileManager: Adding local A2DP profile
11-03 15:15:59.188  5776  5776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 15:15:59.189  5776  5776 D ObexServerSockets: Succeed to create listening sockets 
11-03 15:15:59.189  5776  5776 D ObexServerSockets0: startAccept()
11-03 15:15:59.189  5776  5776 D ObexServerSockets0: prepareForNewConnect()
11-03 15:15:59.191  5776  5776 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 15:15:59.191  5776  5776 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 15:15:59.192  5776  5814 D ObexServerSockets0: Accepting socket connection...
11-03 15:15:59.192  5776  5776 D BluetoothMapService: onReceive
11-03 15:15:59.192  5776  5815 D ObexServerSockets0: Accepting socket connection...
11-03 15:15:59.192  5776  5776 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 15:15:59.192  5776  5776 D BluetoothMapService: STATE_ON
11-03 15:15:59.192  5670  5670 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-03 15:15:59.194  5776  5816 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 15:15:59.195  5776  5816 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 15:15:59.196  5776  5816 D BluetoothSdpJni: SDP Create record success - handle: 1
11-03 15:15:59.198  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 15:15:59.200  5670  5670 D BluetoothA2dp: Proxy object connected
,11-03 15:15:59.203  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 15:15:59.204  5670  5670 D DockEventReceiver: finishStartingService: stopping service
11-03 15:15:59.210  3125  3125 D BluetoothPbap: Proxy object connected
11-03 15:15:59.210  3125  3125 D PbapServerProfile: Bluetooth service connected
11-03 15:15:59.214  5670  5670 D BluetoothPbap: Proxy object connected
11-03 15:15:59.215  5670  5670 D PbapServerProfile: Bluetooth service connected
11-03 15:15:59.217  5776  5776 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 15:15:59.217  5776  5776 D ObexServerSockets0: prepareForNewConnect()
11-03 15:15:59.219  5776  5820 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 15:15:59.234  5776  5824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 15:15:59.235  5776  5824 I BtOppRfcommListener: Accept thread started.
,11-03 15:15:59.270   930   930 D BluetoothHeadset: Proxy object connected
,11-03 15:15:59.270   930   930 D BluetoothHeadset: Proxy object connected
11-03 15:15:59.271  3826  3842 D BluetoothHeadset: Proxy object connected
,11-03 15:15:59.271  3125  3137 D BluetoothHeadset: Proxy object connected
,11-03 15:15:59.271  3125  3125 D HeadsetProfile: Bluetooth service connected
11-03 15:15:59.271   930   930 D BluetoothHeadset: Proxy object connected
,11-03 15:15:59.276  3826  3988 D BluetoothHeadset: Proxy object connected
,11-03 15:15:59.282  3125  3378 D BluetoothHeadset: Proxy object connected
,11-03 15:15:59.283  3125  3125 D HeadsetProfile: Bluetooth service connected
11-03 15:15:59.283   930   947 D BluetoothHeadset: Proxy object connected
11-03 15:15:59.283   930   947 D BluetoothHeadset: Proxy object connected
,11-03 15:15:59.294  5670  5681 D BluetoothHeadset: Proxy object connected
11-03 15:15:59.295  5670  5670 D HeadsetProfile: Bluetooth service connected
,11-03 15:15:59.480  3664  3873 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-03 15:15:59.480  3664  3873 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-03 15:15:59.507  3585  3585 I ConfigService: onCreate
,11-03 15:16:00.861   930  2983 D ConnectivityService: handlePromptUnvalidated 101
,11-03 15:16:03.143  5776  5788 D BluetoothAdapterState: Current state: ON, message: 23
,11-03 15:16:03.143  5776  5788 D BluetoothAdapterProperties: Setting state to 13
,11-03 15:16:03.143  5776  5788 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-03 15:16:03.145  5776  5788 D BluetoothAdapterProperties: onBluetoothDisable()
,11-03 15:16:03.146  5776  5788 I BluetoothAdapterState: Entering PendingCommandState
11-03 15:16:03.150  5776  5776 D BluetoothMapService: onReceive
11-03 15:16:03.150  5776  5776 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 15:16:03.150  5776  5776 D BluetoothMapService: STATE_TURNING_OFF
11-03 15:16:03.150  5776  5776 D BluetoothMapService: MAP Service closeService in
11-03 15:16:03.150  5776  5776 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 15:16:03.151  5776  5776 D ObexServerSockets0: shutdown(block = true)
11-03 15:16:03.151  5776  5814 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-03 15:16:03.152  5776  5776 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 15:16:03.152  5776  5776 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-03 15:16:03.152  5776  5815 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 15:16:03.156  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 15:16:03.156  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 15:16:03.156  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:16:03.156  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:16:03.156  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 15:16:03.156  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 15:16:03.156  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 15:16:03.156  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 15:16:03.156  5612  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 15:16:03.159  5612  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 15:16:03.159  5612  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 15:16:03.159  5776  5792 D BluetoothAdapterProperties: Scan Mode:20
11-03 15:16:03.161  5776  5788 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-03 15:16:03.161  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 15:16:03.164  5776  5801 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-03 15:16:03.165  5776  5776 I BtOppRfcommListener: stopping Accept Thread
11-03 15:16:03.165  5776  5824 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 15:16:03.166  5776  5824 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-03 15:16:03.168  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 15:16:03.169  5776  5776 D HeadsetService: Received stop request...Stopping profile...
11-03 15:16:03.171   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 15:16:03.171   930   930 D BluetoothHeadset: Proxy object disconnected
,11-03 15:16:03.171  5670  5681 D BluetoothHeadset: Proxy object disconnected
11-03 15:16:03.172  3826  3841 D BluetoothHeadset: Proxy object disconnected
11-03 15:16:03.172  5776  5776 D A2dpService: Received stop request...Stopping profile...
11-03 15:16:03.172  3125  4015 D BluetoothHeadset: Proxy object disconnected
11-03 15:16:03.172   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 15:16:03.174   930   930 D BluetoothA2dp: Proxy object disconnected
11-03 15:16:03.174  5776  5807 D A2dpStateMachine: Exit Disconnected: -1
11-03 15:16:03.177  5670  5670 D DockEventReceiver: finishStartingService: stopping service
11-03 15:16:03.178  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 15:16:03.178  5670  5670 D HeadsetProfile: Bluetooth service disconnected
11-03 15:16:03.178  5776  5776 D HidService: Received stop request...Stopping profile...
11-03 15:16:03.178  5776  5776 D HidService: Stopping Bluetooth HidService
11-03 15:16:03.178  5670  5670 D BluetoothA2dp: Proxy object disconnected
,11-03 15:16:03.181  3125  3125 D HeadsetProfile: Bluetooth service disconnected
,11-03 15:16:03.181  3125  3125 D BluetoothA2dp: Proxy object disconnected
11-03 15:16:03.182  5670  5670 D BluetoothInputDevice: Proxy object disconnected
11-03 15:16:03.182  5670  5670 D HidProfile: Bluetooth service disconnected
11-03 15:16:03.182  3125  3125 D BluetoothInputDevice: Proxy object disconnected
11-03 15:16:03.183  3125  3125 D HidProfile: Bluetooth service disconnected
11-03 15:16:03.184  5776  5776 D HealthService: Received stop request...Stopping profile...
11-03 15:16:03.185  5776  5776 V BluetoothAdapterState: isTurningOff()=true
11-03 15:16:03.185  5776  5776 V BluetoothAdapterState: isTurningOn()=false
11-03 15:16:03.185  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:03.185  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 15:16:03.187  5776  5776 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 15:16:03.187  5776  5776 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 15:16:03.187  5776  5792 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 15:16:03.187  5776  5799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:16:03.187  5776  5799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:16:03.187  5776  5799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:16:03.187  5776  5776 V BluetoothAdapterState: isTurningOff()=true
11-03 15:16:03.187  5776  5776 V BluetoothAdapterState: isTurningOn()=false
11-03 15:16:03.187  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:03.187  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 15:16:03.188  5776  5792 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-03 15:16:03.189  5776  5799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:16:03.189  5776  5799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 15:16:03.189  5776  5792 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 15:16:03.189  5776  5799 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 15:16:03.189  5776  5799 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 15:16:03.189  5776  5799 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 15:16:03.190  5776  5799 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 15:16:03.190  3125  3125 D BluetoothPbap: Proxy object disconnected
11-03 15:16:03.190  3125  3125 D PbapServerProfile: Bluetooth service disconnected
11-03 15:16:03.190  5776  5776 V BluetoothAdapterState: isTurningOff()=true
11-03 15:16:03.190  5776  5776 V BluetoothAdapterState: isTurningOn()=false
11-03 15:16:03.190  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:03.191  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:03.191  5670  5670 D BluetoothPbap: Proxy object disconnected
11-03 15:16:03.191  5670  5670 D PbapServerProfile: Bluetooth service disconnected
11-03 15:16:03.191  5776  5776 D PanService: Received stop request...Stopping profile...
,11-03 15:16:03.193  3125  3125 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-03 15:16:03.193  3125  3125 D PanProfile: Bluetooth service disconnected
,11-03 15:16:03.193  5776  5776 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 15:16:03.193  5776  5776 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-03 15:16:03.193  5776  5792 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 15:16:03.194  5776  5776 D BluetoothMapService: Received stop request...Stopping profile...
,11-03 15:16:03.194  5776  5776 D BluetoothMapService: stop()
11-03 15:16:03.194  5670  5670 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 15:16:03.194  5670  5670 D PanProfile: Bluetooth service disconnected
11-03 15:16:03.195  5776  5776 D BluetoothMapAppObserver: deinitObservers()
,11-03 15:16:03.195  5776  5776 D BluetoothMapAppObserver: removeReceiver()
11-03 15:16:03.196  5670  5670 D BluetoothMap: Proxy object disconnected
11-03 15:16:03.196  5670  5670 D MapProfile: Bluetooth service disconnected
11-03 15:16:03.196  3125  3125 D BluetoothMap: Proxy object disconnected
11-03 15:16:03.196  3125  3125 D MapProfile: Bluetooth service disconnected
11-03 15:16:03.196  5776  5776 D SapService: Received stop request...Stopping profile...
11-03 15:16:03.196  5776  5776 V SapService: stop()
11-03 15:16:03.198  5776  5776 V BluetoothAdapterState: isTurningOff()=true
,11-03 15:16:03.198  5776  5776 V BluetoothAdapterState: isTurningOn()=false
11-03 15:16:03.198  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:03.198  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:03.198  5776  5776 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-03 15:16:03.198  5776  5792 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 15:16:03.199  5776  5776 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-03 15:16:03.199  5776  5776 V BluetoothAdapterState: isTurningOff()=true
11-03 15:16:03.199  5776  5776 V BluetoothAdapterState: isTurningOn()=false
11-03 15:16:03.199  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:03.199  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:03.199  5776  5776 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 15:16:03.199  5776  5776 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 15:16:03.202  5776  5776 D BluetoothMapService: MAP Service closeService in
,11-03 15:16:03.202  5776  5776 V BluetoothAdapterState: isTurningOff()=true
,11-03 15:16:03.202  5776  5776 V BluetoothAdapterState: isTurningOn()=false
11-03 15:16:03.202  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:03.202  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:03.202  5776  5776 D BluetoothMapService: cleanup()
,11-03 15:16:03.202  5776  5776 D BluetoothMapService: MAP Service closeService in
11-03 15:16:03.203  5776  5776 V BluetoothAdapterState: isTurningOff()=true
11-03 15:16:03.203  5776  5776 V BluetoothAdapterState: isTurningOn()=false
11-03 15:16:03.203  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:03.203  5776  5776 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 15:16:03.203  5776  5788 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-03 15:16:03.203  5776  5788 D BluetoothAdapterProperties: Setting state to 15
11-03 15:16:03.203  5776  5788 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 15:16:03.204  5776  5788 I BluetoothAdapterState: Entering BleOnState
11-03 15:16:03.204   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:16:03.204  3125  3378 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-03 15:16:03.205  3125  4015 D BluetoothPan: onBluetoothStateChange on: false
,11-03 15:16:03.206  5670  5682 D BluetoothMap: onBluetoothStateChange: up=false
11-03 15:16:03.209  5670  5681 D BluetoothPbap: onBluetoothStateChange: up=false
,11-03 15:16:03.209  5670  5682 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:16:03.210  3826  3842 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:16:03.210   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 15:16:03.211  5670  5681 D BluetoothPan: onBluetoothStateChange on: false
11-03 15:16:03.211  3125  4015 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 15:16:03.212  3125  3378 D BluetoothMap: onBluetoothStateChange: up=false
11-03 15:16:03.213  3125  3141 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 15:16:03.213  3125  3137 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:16:03.213  5670  5682 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 15:16:03.214   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:16:03.214   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 15:16:03.214  5670  5681 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 15:16:03.215  5776  5788 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 15:16:03.215  5776  5788 D BluetoothAdapterProperties: Setting state to 16
11-03 15:16:03.215  5776  5788 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-03 15:16:03.215  5776  5788 D BluetoothAdapterProperties: onBleDisable
11-03 15:16:03.215  5776  5788 I BluetoothAdapterState: Entering PendingCommandState
11-03 15:16:03.216  5776  5789 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 15:16:03.216  5776  5799 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 15:16:03.217  5776  5799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 15:16:03.218  5776  5792 D BluetoothAdapterProperties: Scan Mode:20
11-03 15:16:03.218  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:16:03.221  5612  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:16:03.223  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 15:16:03.229  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 15:16:03.231  5670  5670 D DockEventReceiver: finishStartingService: stopping service
,11-03 15:16:03.422  5776  5792 I bt_hci  : shut_down
,11-03 15:16:03.428  5776  5796 D bt_hwcfg: hw_epilog_process
11-03 15:16:03.428  5776  5796 I bt_vendor: low_power_mode_cb
,11-03 15:16:03.430  5776  5796 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-03 15:16:03.430  5776  5796 I bt_vendor: epilog_cb
,11-03 15:16:03.430  5776  5796 I bt_hci  : epilog_finished_callback
,11-03 15:16:03.434  5776  5792 I bt_hci_h4: hal_close
,11-03 15:16:03.435  5776  5792 I bt_userial_vendor: device fd = 54 close
,11-03 15:16:03.556  5776  5789 D bt_stack_manager: event_shut_down_stack finished.
,11-03 15:16:03.557  5776  5788 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 15:16:03.559  5776  5788 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-03 15:16:03.559  5776  5776 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 15:16:03.560  5776  5776 D BtGatt.GattService: Received stop request...Stopping profile...
,11-03 15:16:03.560  5776  5776 D BtGatt.GattService: stop()
11-03 15:16:03.560  5776  5776 D BtGatt.AdvertiseManager: advertise clients cleared
11-03 15:16:03.562  5776  5776 V BluetoothAdapterState: isTurningOff()=false
11-03 15:16:03.562  5776  5776 V BluetoothAdapterState: isTurningOn()=false
11-03 15:16:03.562  5776  5776 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:03.562  5776  5776 V BluetoothAdapterState: isBleTurningOff()=true
11-03 15:16:03.563  5776  5788 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-03 15:16:03.563  5776  5788 D BluetoothAdapterProperties: Setting state to 10
,11-03 15:16:03.563  5776  5788 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-03 15:16:03.564   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
11-03 15:16:03.565  5776  5788 I BluetoothAdapterState: Entering OffState
,11-03 15:16:03.574  5776  5776 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-03 15:16:03.575  5776  5776 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-03 15:16:03.575  5776  5776 I BluetoothServiceJni: cleanupNative: return from cleanup
11-03 15:16:03.576  5776  5789 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 15:16:03.582  5776  5776 I art     : System.exit called, status: 0
,11-03 15:16:03.582  5776  5776 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 15:16:03.608   930  3202 I ActivityManager: Process com.android.bluetooth (pid 5776) has died
,11-03 15:16:03.623   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:04.535  3585  3585 I ConfigService: onDestroy
,11-03 15:16:04.624   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:05.625   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:06.626   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:07.627   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:08.140  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 15:16:08.140  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 15:16:08.146  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:16:08.146  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b9015f removed from the list
,11-03 15:16:08.147  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:16:08.150  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 15:16:08.150  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@236e40a added. We now have 4 listener(s)
,11-03 15:16:08.150  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:16:08.152  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:16:08.152  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@236e40a removed from the list
,11-03 15:16:08.152  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 15:16:08.155  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 15:16:08.155  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@496547b added. We now have 4 listener(s)
11-03 15:16:08.155  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:16:08.628   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 15:16:11.711   930   950 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-03 15:16:11.716  3840  3840 W Binder_9: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33257]" dev="sockfs" ino=33257 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 15:16:11.720  3840  3840 W Binder_9: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33257]" dev="sockfs" ino=33257 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 15:16:11.727  3664  3664 I Keyboard.Facilitator: onFinishInput()
,11-03 15:16:11.742   930   950 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 15:16:11.742   930   950 I Adreno  : Build Date                       : 12/06/15
11-03 15:16:11.742   930   950 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 15:16:11.742   930   950 I Adreno  : Local Branch                     : mybranch17112971
11-03 15:16:11.742   930   950 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 15:16:11.742   930   950 I Adreno  : Remote Branch                    : NONE
11-03 15:16:11.742   930   950 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 15:16:11.779   384   407 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (154 us)
,11-03 15:16:12.458  5612  5612 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 15:16:12.459  5612  5612 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-03 15:16:12.493   930   950 I sensors : batch
,11-03 15:16:12.494   930   950 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-03 15:16:12.495  5612  5612 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@df2887b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3e1a298, 16908290=android.view.AbsSavedState$1@3e1a298}, android:focusedViewId=100}]}]
11-03 15:16:12.495  5612  5612 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-03 15:16:12.495  5612  5612 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-03 15:16:12.496  5612  5612 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,11-03 15:16:12.500   930  2729 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-03 15:16:12.500   930   950 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-03 15:16:12.500   930   950 I sensors : activate
11-03 15:16:12.501   384   384 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fa6643c00
11-03 15:16:12.502   384   384 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-03 15:16:12.502   930   948 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,11-03 15:16:12.505   930  2729 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-03 15:16:12.805   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-03 15:16:12.806   384   384 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-03 15:16:12.808   930  3093 D SurfaceControl: Excessive delay in setPowerMode(): 306ms
,11-03 15:16:12.821   930   950 I DreamManagerService: Entering dreamland.
11-03 15:16:12.822   930   950 I PowerManagerService: Dozing...
,11-03 15:16:12.823   930   945 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-03 15:16:12.843  3599  3599 W Binder_6: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[33983]" dev="sockfs" ino=33983 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 15:16:12.843  3599  3599 W Binder_6: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33983]" dev="sockfs" ino=33983 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 15:16:12.847   930   941 I sensors : batch
11-03 15:16:12.847   930   941 I sensors : activate
,11-03 15:16:12.852   930  2729 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
11-03 15:16:12.852   930  2729 I hubconnection: sensorhub said: 'activate 21 enable:1'
11-03 15:16:12.854   511  3013 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-03 15:16:12.874  3826  4769 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-03 15:16:12.874  3826  4769 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-03 15:16:12.874  3826  4769 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 15:16:12.874   524  1474 D         : oem-qmi: Connection accepted
11-03 15:16:12.875   524  1474 D         : oem-qmi: Waiting to accept connection
,11-03 15:16:12.876   930   930 I sensors : activate
11-03 15:16:12.877   511   511 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-03 15:16:12.879   930  2729 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-03 15:16:12.881  3826  4769 D         : oem_qmi_lib:output 0
,11-03 15:16:12.881  3826  4769 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 15:16:12.902  3826  4769 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-03 15:16:12.902  3826  4769 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-03 15:16:12.902  3826  4769 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 15:16:12.902   524  1474 D         : oem-qmi: Connection accepted
11-03 15:16:12.902   524  1474 D         : oem-qmi: Waiting to accept connection
,11-03 15:16:12.908  3826  4769 D         : oem_qmi_lib:output 0
11-03 15:16:12.909  3826  4769 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 15:16:13.168  5612  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:16:13.203   930   947 I ActivityManager: Start proc 5840:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 15:16:13.296  5840  5840 D AdapterServiceConfig: Adding HeadsetService
,11-03 15:16:13.297  5840  5840 D AdapterServiceConfig: Adding A2dpService
11-03 15:16:13.297  5840  5840 D AdapterServiceConfig: Adding HidService
,11-03 15:16:13.297  5840  5840 D AdapterServiceConfig: Adding HealthService
,11-03 15:16:13.297  5840  5840 D AdapterServiceConfig: Adding PanService
11-03 15:16:13.298  5840  5840 D AdapterServiceConfig: Adding GattService
11-03 15:16:13.298  5840  5840 D AdapterServiceConfig: Adding BluetoothMapService
11-03 15:16:13.298  5840  5840 D AdapterServiceConfig: Adding SapService
,11-03 15:16:13.312   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@74cd1de:true
,11-03 15:16:13.312  5840  5840 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 15:16:13.315  5840  5840 I bt_bluedroid: init
,11-03 15:16:13.316  5840  5852 I BluetoothAdapterState: Entering OffState
,11-03 15:16:13.319  5840  5853 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 15:16:13.319  5840  5853 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 15:16:13.319  5840  5853 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 15:16:13.319  5840  5853 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-03 15:16:13.320  5840  5840 I bt_bluedroid: get_profile_interface socket
,11-03 15:16:13.322  5840  5856 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-03 15:16:13.322  5840  5840 I bt_bluedroid: get_profile_interface sdp
11-03 15:16:13.324  5840  5856 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 15:16:13.327  5840  5851 I bt_bluedroid: config_hci_snoop_log
,11-03 15:16:13.329   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 15:16:13.333  5840  5852 D BluetoothAdapterState: Current state: OFF, message: 0
11-03 15:16:13.333  5840  5852 D BluetoothAdapterProperties: Setting state to 14
11-03 15:16:13.333  5840  5852 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 15:16:13.336  5840  5852 D BluetoothBondStateMachine: make
,11-03 15:16:13.338  5840  5857 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 15:16:13.343  5840  5840 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-03 15:16:13.344  5840  5852 I BluetoothAdapterState: Entering PendingCommandState
11-03 15:16:13.345  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
,11-03 15:16:13.346  5840  5840 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 15:16:13.346  5840  5840 D BtGatt.GattService: Received start request. Starting profile...
11-03 15:16:13.347  5840  5840 D BtGatt.GattService: start()
11-03 15:16:13.347  5840  5840 I bt_bluedroid: get_profile_interface gatt
,11-03 15:16:13.348  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
11-03 15:16:13.348  5840  5840 D BtGatt.AdvertiseManager: advertise manager created
,11-03 15:16:13.354  5840  5840 V BluetoothAdapterState: isTurningOff()=false
11-03 15:16:13.354  5840  5840 V BluetoothAdapterState: isTurningOn()=false
11-03 15:16:13.355  5840  5840 V BluetoothAdapterState: isBleTurningOn()=true
11-03 15:16:13.355  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:13.355  5840  5852 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-03 15:16:13.356  5840  5852 I bt_bluedroid: bt_bluedroid
,11-03 15:16:13.357  5840  5853 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-03 15:16:13.357  5840  5853 I bt_hci  : start_up
,11-03 15:16:13.363  5840  5853 I bt_vendor: alloc value 0xf3f71871
,11-03 15:16:13.363  5840  5853 I bt_vendor: init
11-03 15:16:13.363  5840  5853 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 15:16:13.363  5840  5853 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 15:16:13.473  5840  5853 D bt_hci  : start_up starting async portion
,11-03 15:16:13.473  5840  5860 I bt_hci  : event_finish_startup
,11-03 15:16:13.475  5840  5860 I bt_hci_h4: hal_open
,11-03 15:16:13.475  5840  5860 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 15:16:13.477  5840  5860 I bt_userial_vendor: device fd = 54 open
,11-03 15:16:13.473  5861  5861 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 15:16:13.494  5840  5860 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 15:16:13.498  5840  5860 D bt_hwcfg: Chipset BCM4358A3
11-03 15:16:13.498  5840  5860 D bt_hwcfg: Target name = [BCM4358A3]
11-03 15:16:13.498  5840  5860 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 15:16:14.012  5840  5860 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-03 15:16:14.012  5840  5860 D bt_hwcfg: Settlement delay -- 100 ms
,11-03 15:16:14.012  5840  5860 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 15:16:14.146  5840  5860 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 15:16:14.146  5840  5860 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 15:16:14.148  5840  5860 I bt_hwcfg: vendor lib fwcfg completed
11-03 15:16:14.148  5840  5860 I bt_vendor: firmware callback
11-03 15:16:14.148  5840  5860 I bt_hci  : firmware_config_callback
,11-03 15:16:14.159  5840  5863 I bt_btu  : btu_task pending for preload complete event
,11-03 15:16:14.159  5840  5863 I bt_btu_task: Bluetooth chip preload is complete
,11-03 15:16:14.159  5840  5863 I bt_btu  : btu_task received preload complete event
,11-03 15:16:14.167  5840  5863 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 15:16:14.168  5840  5863 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 15:16:14.168  5840  5863 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 15:16:14.168  5840  5863 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 15:16:14.168  5840  5863 I         : BTE_InitTraceLevels -- TRC_AVRC
11-03 15:16:14.168  5840  5863 I         : BTE_InitTraceLevels -- TRC_A2D
,11-03 15:16:14.168  5840  5863 I         : BTE_InitTraceLevels -- TRC_BNEP
11-03 15:16:14.168  5840  5863 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 15:16:14.169  5840  5863 I         : BTE_InitTraceLevels -- TRC_GAP
,11-03 15:16:14.169  5840  5863 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 15:16:14.169  5840  5863 I         : BTE_InitTraceLevels -- TRC_SDP
11-03 15:16:14.169  5840  5863 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 15:16:14.169  5840  5863 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 15:16:14.169  5840  5863 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-03 15:16:14.169  5840  5863 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 15:16:14.261  5840  5863 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3eef549
11-03 15:16:14.261  5840  5863 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3eef549 
,11-03 15:16:14.276  5840  5856 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 15:16:14.278  5840  5856 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 15:16:14.278  5840  5856 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 15:16:14.282  5840  5856 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 15:16:14.288  5840  5856 D BluetoothAdapterProperties: Scan Mode:20
,11-03 15:16:14.289  5840  5856 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 15:16:14.289  5840  5856 D bt_hci  : do_postload posting postload work item
11-03 15:16:14.289  5840  5860 I bt_hci  : event_postload
11-03 15:16:14.289  5840  5860 I bt_vendor: sco_config_cb
,11-03 15:16:14.289  5840  5860 I bt_hci  : sco_config_callback postload finished.
,11-03 15:16:14.292  5840  5856 D bt_bte_conf: Device ID record 1 : primary
11-03 15:16:14.292  5840  5856 D bt_bte_conf:   vendorId            = 000f
11-03 15:16:14.293  5840  5856 D bt_bte_conf:   vendorIdSource      = 0001
11-03 15:16:14.293  5840  5856 D bt_bte_conf:   product             = 1200
11-03 15:16:14.293  5840  5856 D bt_bte_conf:   version             = 1436
11-03 15:16:14.293  5840  5856 D bt_bte_conf:   clientExecutableURL = 
,11-03 15:16:14.293  5840  5856 D bt_bte_conf:   serviceDescription  = 
,11-03 15:16:14.293  5840  5856 D bt_bte_conf:   documentationURL    = 
11-03 15:16:14.293  5840  5856 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 15:16:14.293  5840  5853 D bt_stack_manager: event_start_up_stack finished
,11-03 15:16:14.294  5840  5852 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 15:16:14.295  5840  5852 D BluetoothAdapterProperties: Setting state to 15
11-03 15:16:14.295  5840  5852 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 15:16:14.297  5840  5852 I BluetoothAdapterState: Entering BleOnState
11-03 15:16:14.299  5840  5860 I bt_vendor: low_power_mode_cb
,11-03 15:16:14.302  5840  5852 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 15:16:14.302  5840  5852 D BluetoothAdapterProperties: Setting state to 11
11-03 15:16:14.302  5840  5852 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 15:16:14.315  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
,11-03 15:16:14.319  5840  5840 D HeadsetService: Received start request. Starting profile...
,11-03 15:16:14.321  5840  5840 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 15:16:14.321  5840  5840 D HeadsetStateMachine: make
,11-03 15:16:14.326  5840  5852 I BluetoothAdapterState: Entering PendingCommandState
,11-03 15:16:14.330  5840  5840 D HeadsetStateMachine: max_hf_connections = 1
,11-03 15:16:14.330  5840  5840 I bt_bluedroid: get_profile_interface handsfree
11-03 15:16:14.331  5840  5856 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-03 15:16:14.331  5840  5856 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-03 15:16:14.336  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
11-03 15:16:14.336  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 15:16:14.338  5840  5840 D A2dpService: Received start request. Starting profile...
,11-03 15:16:14.338  5840  5840 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 15:16:14.339  5840  5840 I bt_bluedroid: get_profile_interface avrcp
,11-03 15:16:14.344  5840  5840 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-03 15:16:14.345  5840  5840 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 15:16:14.345  5840  5840 D A2dpStateMachine: make
,11-03 15:16:14.346  5840  5840 I bt_bluedroid: get_profile_interface a2dp
,11-03 15:16:14.348  5840  5871 D A2dpStateMachine: Enter Disconnected: -2
,11-03 15:16:14.349  5840  5840 I BluetoothHidServiceJni: classInitNative: succeeds
,11-03 15:16:14.349  5840  5856 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-03 15:16:14.350  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
,11-03 15:16:14.351  5840  5840 D HidService: Received start request. Starting profile...
11-03 15:16:14.351  5840  5840 I bt_bluedroid: get_profile_interface hidhost
11-03 15:16:14.351  5840  5840 D HidService: setHidService(): set to: null
,11-03 15:16:14.351  5840  5856 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ed056d
11-03 15:16:14.352  5840  5840 I BluetoothHealthServiceJni: classInitNative: succeeds
11-03 15:16:14.352  5840  5856 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 15:16:14.352  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
11-03 15:16:14.353  5840  5840 D HealthService: Received start request. Starting profile...
,11-03 15:16:14.354  5840  5840 I bt_bluedroid: get_profile_interface health
,11-03 15:16:14.355  5840  5840 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-03 15:16:14.356  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
,11-03 15:16:14.356  5840  5840 D PanService: Received start request. Starting profile...
,11-03 15:16:14.357  5840  5840 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 15:16:14.357  5840  5840 I bt_bluedroid: get_profile_interface pan
11-03 15:16:14.357  5840  5856 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 15:16:14.359  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
,11-03 15:16:14.360  5840  5840 D BluetoothMapService: Received start request. Starting profile...
,11-03 15:16:14.360  5840  5840 D BluetoothMapService: start()
11-03 15:16:14.363  5840  5840 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-03 15:16:14.363  5840  5840 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 15:16:14.363  5840  5840 D BluetoothMapAppObserver: createReceiver()
11-03 15:16:14.365  5840  5840 D BluetoothMapAppObserver: initObservers()
11-03 15:16:14.365  5840  5840 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 15:16:14.371  5840  5840 V SapService: SapBinder()
11-03 15:16:14.371  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
,11-03 15:16:14.372  5840  5840 D SapService: Received start request. Starting profile...
,11-03 15:16:14.372  5840  5840 V SapService: start()
,11-03 15:16:14.374  5840  5840 V BluetoothAdapterState: isTurningOff()=false
11-03 15:16:14.374  5840  5840 V BluetoothAdapterState: isTurningOn()=true
11-03 15:16:14.374  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:14.374  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:14.375  5840  5869 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 15:16:14.375  5840  5840 V BluetoothAdapterState: isTurningOff()=false
11-03 15:16:14.375  5840  5840 V BluetoothAdapterState: isTurningOn()=true
11-03 15:16:14.375  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:14.375  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:14.375  5840  5840 V BluetoothAdapterState: isTurningOff()=false
11-03 15:16:14.375  5840  5840 V BluetoothAdapterState: isTurningOn()=true
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isTurningOff()=false
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isTurningOn()=true
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isTurningOff()=false
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isTurningOn()=true
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isTurningOff()=false
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isTurningOn()=true
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:14.376  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:14.377  5840  5840 V BluetoothAdapterState: isTurningOff()=false
,11-03 15:16:14.377  5840  5840 V BluetoothAdapterState: isTurningOn()=true
11-03 15:16:14.377  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
11-03 15:16:14.378  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
11-03 15:16:14.378  5840  5852 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 15:16:14.379  5840  5852 D BluetoothAdapterProperties: ScanMode =  20
11-03 15:16:14.379  5840  5852 D BluetoothAdapterProperties: State =  11
11-03 15:16:14.380  5840  5856 D BluetoothAdapterProperties: Scan Mode:21
11-03 15:16:14.380  5840  5852 D BluetoothAdapterProperties: Setting state to 12
11-03 15:16:14.380  5840  5852 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 15:16:14.380  5840  5856 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 15:16:14.380   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 15:16:14.380  3125  3141 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 15:16:14.381  5840  5852 I BluetoothAdapterState: Entering OnState
11-03 15:16:14.382  3125  4015 D BluetoothPan: onBluetoothStateChange on: true
11-03 15:16:14.383  3125  3125 D BluetoothA2dp: Proxy object connected
,11-03 15:16:14.384  5670  5681 D BluetoothMap: onBluetoothStateChange: up=true
,11-03 15:16:14.386  3125  3125 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 15:16:14.386  3125  3125 D PanProfile: Bluetooth service connected
,11-03 15:16:14.387  5670  5682 D BluetoothPbap: onBluetoothStateChange: up=true
,11-03 15:16:14.389  5670  5681 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 15:16:14.389  3826  3988 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 15:16:14.389   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 15:16:14.390   930   930 D BluetoothA2dp: Proxy object connected
11-03 15:16:14.390  5670  5682 D BluetoothPan: onBluetoothStateChange on: true
11-03 15:16:14.390  5840  5840 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-03 15:16:14.391  5840  5840 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-03 15:16:14.391  3125  3141 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 15:16:14.392  5670  5670 D BluetoothMap: Proxy object connected
11-03 15:16:14.392  5670  5670 D MapProfile: Bluetooth service connected
11-03 15:16:14.392  5670  5670 D BluetoothMap: getConnectedDevices()
11-03 15:16:14.392  5840  5840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 15:16:14.394  3125  3137 D BluetoothMap: onBluetoothStateChange: up=true
,11-03 15:16:14.394  5840  5840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 15:16:14.394  5670  5670 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 15:16:14.394  5670  5670 D PanProfile: Bluetooth service connected
11-03 15:16:14.395  5840  5840 D ObexServerSockets: Succeed to create listening sockets 
11-03 15:16:14.395  5840  5840 D ObexServerSockets0: startAccept()
11-03 15:16:14.395  5840  5840 D ObexServerSockets0: prepareForNewConnect()
11-03 15:16:14.395  3125  3137 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 15:16:14.395  3125  3125 D BluetoothMap: Proxy object connected
11-03 15:16:14.395  3125  3125 D MapProfile: Bluetooth service connected
,11-03 15:16:14.395  3125  3125 D BluetoothMap: getConnectedDevices()
11-03 15:16:14.397  3125  3378 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 15:16:14.397  5670  5681 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 15:16:14.398  5840  5840 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 15:16:14.398  5840  5840 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 15:16:14.399  5840  5878 D ObexServerSockets0: Accepting socket connection...
,11-03 15:16:14.399  5840  5879 D ObexServerSockets0: Accepting socket connection...
11-03 15:16:14.400  3125  3125 D BluetoothInputDevice: Proxy object connected
11-03 15:16:14.400  3125  3125 D HidProfile: Bluetooth service connected
,11-03 15:16:14.401   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 15:16:14.401   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 15:16:14.401  5670  5877 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 15:16:14.403  5670  5670 D BluetoothInputDevice: Proxy object connected
11-03 15:16:14.403  5670  5670 D HidProfile: Bluetooth service connected
11-03 15:16:14.404  5840  5840 D BluetoothMapService: onReceive
11-03 15:16:14.404  5840  5840 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 15:16:14.404  5840  5840 D BluetoothMapService: STATE_ON
11-03 15:16:14.404   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-03 15:16:14.406  5670  5670 D BluetoothA2dp: Proxy object connected
,11-03 15:16:14.408  5840  5880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 15:16:14.409  5840  5880 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 15:16:14.409  5840  5880 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-03 15:16:14.413  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 15:16:14.418  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 15:16:14.419  5670  5670 D DockEventReceiver: finishStartingService: stopping service
,11-03 15:16:14.425  5670  5670 D BluetoothPbap: Proxy object connected
,11-03 15:16:14.425  5670  5670 D PbapServerProfile: Bluetooth service connected
,11-03 15:16:14.429  3125  3125 D BluetoothPbap: Proxy object connected
,11-03 15:16:14.429  3125  3125 D PbapServerProfile: Bluetooth service connected
,11-03 15:16:14.431  5840  5840 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 15:16:14.431  5840  5840 D ObexServerSockets0: prepareForNewConnect()
,11-03 15:16:14.433  5840  5884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 15:16:14.446  5840  5888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 15:16:14.448  5840  5888 I BtOppRfcommListener: Accept thread started.
,11-03 15:16:14.482   930   930 D BluetoothHeadset: Proxy object connected
,11-03 15:16:14.482   930   930 D BluetoothHeadset: Proxy object connected
,11-03 15:16:14.483  5670  5681 D BluetoothHeadset: Proxy object connected
,11-03 15:16:14.483  3826  3841 D BluetoothHeadset: Proxy object connected
11-03 15:16:14.484  3125  3137 D BluetoothHeadset: Proxy object connected
,11-03 15:16:14.484   930   930 D BluetoothHeadset: Proxy object connected
11-03 15:16:14.484  3125  3125 D HeadsetProfile: Bluetooth service connected
11-03 15:16:14.484  5670  5670 D HeadsetProfile: Bluetooth service connected
,11-03 15:16:14.489  5670  5682 D BluetoothHeadset: Proxy object connected
,11-03 15:16:14.490  3826  3842 D BluetoothHeadset: Proxy object connected
11-03 15:16:14.490  5670  5670 D HeadsetProfile: Bluetooth service connected
,11-03 15:16:14.497  3125  3378 D BluetoothHeadset: Proxy object connected
,11-03 15:16:14.498  3125  3125 D HeadsetProfile: Bluetooth service connected
,11-03 15:16:14.501   930   947 D BluetoothHeadset: Proxy object connected
,11-03 15:16:14.501   930   947 D BluetoothHeadset: Proxy object connected
,11-03 15:16:16.451  3751  4472 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-03 15:16:18.184  5612  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 15:16:18.184  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:16:18.184  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:16:18.184  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 15:16:18.184  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 15:16:18.184  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 15:16:18.184  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 15:16:18.184  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 15:16:18.189  5612  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 15:16:18.190  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 15:16:18.191  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@496547b removed from the list
11-03 15:16:18.191  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 15:16:18.194  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 15:16:18.194  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cbaf1 added. We now have 4 listener(s)
11-03 15:16:18.194  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:16:18.197   930  3665 D WifiService: setWifiEnabled: false pid=5612, uid=10077
11-03 15:16:18.197   930  3665 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 15:16:23.206  5612  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 15:16:23.207   930   941 D WifiService: setWifiEnabled: true pid=5612, uid=10077
11-03 15:16:23.208   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 15:16:23.218   506   924 D SoftapController: Softap fwReload - Ok
11-03 15:16:23.223   506   924 D CommandListener: Setting iface cfg
11-03 15:16:23.225   506   924 D CommandListener: Trying to bring down wlan0
,11-03 15:16:23.227   506   924 D CommandListener: Clearing all IP addresses on wlan0
,11-03 15:16:23.234   930  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 15:16:23.629   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:23.902   930  2981 D wifi    : set interface wlan0 flags (UP)
,11-03 15:16:23.902   930  2981 I WifiHAL : Initializing wifi
11-03 15:16:23.903   930  2981 I WifiHAL : Creating socket
,11-03 15:16:23.909   930  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-03 15:16:23.909   930  2981 D wifi    : Did set static halHandle = 0x7f80d72b80
,11-03 15:16:23.909   930  2981 D wifi    : halHandle = 0x7f80d72b80, mVM = 0x7f9d38d140, mCls = 0x10163a
11-03 15:16:23.910   930  2981 D wifi    : array field set
11-03 15:16:23.910   930  2981 I WifiNative-HAL: interface[0] = wlan0
,11-03 15:16:23.911   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 15:16:23.915   930  5893 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547622431616
,11-03 15:16:23.915   930  5893 D wifi    : waitForHalEvents called, vm = 0x7f9d38d140, obj = 0x10163a, env = 0x7f854d6000
,11-03 15:16:23.974  5894  5894 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 15:16:24.019   930  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 15:16:24.044  5894  5894 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 15:16:24.134  5894  5894 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 15:16:24.134  5894  5894 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 15:16:24.160   930  2981 D WifiConfigStore: Loading config and enabling all networks 
,11-03 15:16:24.185   930  2981 D WifiConfigStore: loaded 0 passpoint configs
11-03 15:16:24.186   930  2981 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-03 15:16:24.186   930  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-03 15:16:24.187   930  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-03 15:16:24.188   930  2981 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-03 15:16:24.189   930  2981 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 15:16:24.190   930  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-03 15:16:24.191   930  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-03 15:16:24.191   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 15:16:24.191   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 15:16:24.191   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 15:16:24.191   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 15:16:24.191   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 15:16:24.196   930  2981 D WifiNative-HAL: Setting external_sim to 1
11-03 15:16:24.196  4513  4513 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 15:16:24.197   930  2981 D wifi    : setting dfs flag to true, 0x7f81c2c680
11-03 15:16:24.198   930  2981 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 15:16:24.198   930  2981 D wifi    : setting scan oui 0x7f81c2c680
,11-03 15:16:24.198   930  2981 D WifiHAL : Sending mac address OUI
,11-03 15:16:24.203   930  2981 E native  : do suspend true
,11-03 15:16:24.210   930  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-03 15:16:24.210   930   930 D RttService: SCAN_AVAILABLE : 3
11-03 15:16:24.210   506   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 15:16:24.210   930  3089 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-03 15:16:24.211   506   924 D CommandListener: Setting iface cfg
,11-03 15:16:24.222   930  2980 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,11-03 15:16:24.222   930  2980 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 15:16:24.235   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163942 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,11-03 15:16:24.236   930  2980 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 15:16:24.237   930  2980 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 15:16:24.631   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:25.633   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:26.634   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:27.376  5894  5894 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 15:16:27.405   930  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 15:16:27.412   930  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
11-03 15:16:27.412   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 15:16:27.424   930  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 15:16:27.477   930  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 15:16:27.635   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:27.813  5894  5894 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 15:16:27.846  5894  5894 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 15:16:27.847  5894  5894 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 15:16:27.858   930  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-03 15:16:27.858   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 15:16:27.858   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 15:16:27.876   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 15:16:27.890   506   924 D CommandListener: Setting iface cfg
,11-03 15:16:27.895   930  2981 D WifiStateMachine: Start Dhcp Watchdog 3
,11-03 15:16:27.899   930  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 15:16:27.904   930  5899 D DhcpClient: Receive thread started
,11-03 15:16:27.987   930  2981 E native  : do suspend false
,11-03 15:16:28.002   930  5898 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 15:16:28.015   930  5899 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-03 15:16:28.016   930  5898 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-03 15:16:28.018   930  5898 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 15:16:28.031   930  5899 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 15:16:28.032   930  5898 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-03 15:16:28.035   506   924 D CommandListener: Setting iface cfg
,11-03 15:16:28.040   930  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 15:16:28.044   930  2981 E native  : do suspend true
,11-03 15:16:28.044   930  5898 D DhcpClient: Scheduling renewal in 86399s
,11-03 15:16:28.065   930  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-03 15:16:28.067   930  2981 D WifiConfigStore: No blacklist allowed without epno enabled
,11-03 15:16:28.068   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-03 15:16:28.069   930  2983 D ConnectivityService: Adding iface wlan0 to network 102
11-03 15:16:28.074   930  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-03 15:16:28.120   930  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-03 15:16:28.121   930  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-03 15:16:28.123   930  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-03 15:16:28.127   930  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-03 15:16:28.128   930  2983 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-03 15:16:28.138   930  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 15:16:28.143   930  2983 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-03 15:16:28.143   930  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-03 15:16:28.143   930  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-03 15:16:28.143   930  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 15:16:28.143   930  2983 D ConnectivityService:    accepting network in place of null
11-03 15:16:28.143   930  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 15:16:28.144   930  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 15:16:28.163   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167868, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 15:16:28.174   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 15:16:28.199   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 15:16:28.204   930  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-03 15:16:28.205   930  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 15:16:28.205  3780  3888 W QCNEJ   : |CORE| network available: 102
11-03 15:16:28.206   930  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-03 15:16:28.206  3780  3888 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-03 15:16:28.207   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-03 15:16:28.208  3780  3888 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-03 15:16:28.209  3780  3888 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-03 15:16:28.219  5612  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 15:16:28.219  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 15:16:28.219  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 15:16:28.219  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 15:16:28.219  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 15:16:28.219  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 15:16:28.219  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 15:16:28.219  5612  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 15:16:28.221  5612  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 15:16:28.222  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:16:28.222  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cbaf1 removed from the list
11-03 15:16:28.222  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:16:28.224  5612  5659 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-03 15:16:28.225  5612  5659 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-03 15:16:28.226  5612  5659 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@df2887b Bundle[{}]
,11-03 15:16:28.226  5612  5659 I io.jxcore.node.LifeCycleMonitor: start: OK
11-03 15:16:28.226  5612  5659 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-03 15:16:28.226  5612  5659 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-03 15:16:28.227  5612  5659 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-03 15:16:28.227  5612  5659 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-03 15:16:28.227  5612  5659 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 15:16:28.230   930  5896 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 15:16:28.234  5612  5659 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-03 15:16:28.235  5612  5659 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-03 15:16:28.235  5612  5659 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-03 15:16:28.237  3975  3975 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-03 15:16:28.237  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 15:16:28.237  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6736d6 added. We now have 3 listener(s)
,11-03 15:16:28.238  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 15:16:28.238  3993  3993 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 15:16:28.239  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 15:16:28.239  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 15:16:28.239  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 15:16:28.239  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2bbd57 added. We now have 4 listener(s)
11-03 15:16:28.239  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:16:28.240  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 15:16:28.241  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 15:16:28.241  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a5044 added. We now have 4 listener(s)
,11-03 15:16:28.242  3993  3993 D SystemUpdateService: onCreate
11-03 15:16:28.242  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 15:16:28.242  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 15:16:28.242  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 15:16:28.242  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 15:16:28.242  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c1152d added. We now have 5 listener(s)
11-03 15:16:28.242  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 15:16:28.243  5612  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 15:16:28.243  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 15:16:28.243  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 15:16:28.243  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:16:28.243  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:16:28.243  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 15:16:28.243  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6736d6 removed from the list
11-03 15:16:28.243  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:16:28.243  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2bbd57 removed from the list
11-03 15:16:28.243  5612  5659 D io.jxcore.node.ConnectivityMonitor: stop
11-03 15:16:28.243  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.244  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.244  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.244  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.245  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:16:28.245  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:16:28.245  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:16:28.245  5612  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2bbd57 not in the list
11-03 15:16:28.245  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.246  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11,-03 15:16:28.246  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.246  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.246  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 15:16:28.246  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 15:16:28.246  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 15:16:28.246  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c1152d removed from the list
11-03 15:16:28.246  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 15:16:28.246  3993  3993 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-03 15:16:28.246  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:16:28.246  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 15:16:28.246  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a5044 removed from the list
11-03 15:16:28.247  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 15:16:28.247  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@977ea62 added. We now have 3 listener(s)
,11-03 15:16:28.248  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 15:16:28.248  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 15:16:28.248  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 15:16:28.248  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 15:16:28.248  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b44d7f3 added. We now have 4 listener(s)
11-03 15:16:28.248  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 15:16:28.249  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 15:16:28.250  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 15:16:28.250  5612  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0e2cb0 added. We now have 4 listener(s)
,11-03 15:16:28.251  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 15:16:28.251  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 15:16:28.251  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 15:16:28.251  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 15:16:28.251  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6d729 added. We now have 5 listener(s)
11-03 15:16:28.251  5612  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 15:16:28.251  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 15:16:28.251  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 15:16:28.252  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 15:16:28.252  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 15:16:28.252  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 15:16:28.253  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 15:16:28.258  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 15:16:28.258  5612  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 15:16:28.258  5612  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 15:16:28.261  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:16:28.261  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 15:16:28.262  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 15:16:28.262  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 15:16:28.262  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 15:16:28.264  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:16:28.264  5612  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 15:16:28.264  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 15:16:28.264  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 15:16:28.264  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 15:16:28.264  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.265  5612  5659 D BluetoothAdapter: STATE_ON
11-03 15:16:28.265  3993  3993 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-03 15:16:28.267  5840  5868 D BtGatt.GattService: registerClient() - UUID=79ad8fcd-45ad-44cc-b34f-6b7d633ba774
,11-03 15:16:28.268  5840  5856 D BtGatt.GattService: onClientRegistered() - UUID=79ad8fcd-45ad-44cc-b34f-6b7d633ba774, clientIf=5
,11-03 15:16:28.269  5612  5622 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 15:16:28.270  5840  5851 D BtGatt.GattService: start scan with filters
11-03 15:16:28.271  3993  4303 I iu.UploadsManager: num queued entries: 0
11-03 15:16:28.271  3993  4303 I iu.UploadsManager: num updated entries: 0
11-03 15:16:28.272  3993  4303 I iu.SyncManager: NEXT; no task
11-03 15:16:28.273  3993  5908 I SystemUpdateService: active receiver: enabled
11-03 15:16:28.273  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 15:16:28.273  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.273  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-03 15:16:28.273  5840  5859 D BtGatt.ScanManager: handling starting scan
11-03 15:16:28.273  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.273  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 15:16:28.273  5612  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 15:16:28.274  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 15:16:28.274  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 15:16:28.274  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 15:16:28.274  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 15:16:28.274  5612  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 15:16:28.274  5612  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-03 15:16:28.274  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 15:16:28.274  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 15:16:28.275  3993  3993 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 15:16:28.276  5840  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@daa9bac
11-03 15:16:28.276  3993  3993 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 15:16:28.278  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.278  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 15:16:28.278  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.278  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 15:16:28.278  5612  5659 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 15:16:28.278  5612  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 15:16:28.278  5612  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 15:16:28.278  5612  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 15:16:28.278  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 15:16:28.278  5612  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 15:16:28.278  5612  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 15:16:28.278  5612  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 15:16:28.278  5612  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 15:16:28.278  5612  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 15:16:28.279  5708  5708 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 15:16:28.284  5840  5856 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 15:16:28.284  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:16:28.284   930  5896 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 14:16:28 GMT], X-Android-Received-Millis=[1478182588283], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478182588255]}
11-03 15:16:28.284  5840  5859 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 15:16:28.284  5708  5708 D SprintDMHelper: simOperator: 
11-03 15:16:28.284   930  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 15:16:28.284  5708  5708 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 15:16:28.285   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-03 15:16:28.285   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-03 15:16:28.286   930  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-03 15:16:28.292  5840  5856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-03 15:16:28.293  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:16:28.293  5840  5859 D BtGatt.ScanManager: Starting BLE batch scan
11-03 15:16:28.293  5840  5859 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 15:16:28.297  3993  5908 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 15:16:28.304  5840  5856 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-03 15:16:28.304  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:16:28.305  3993  5908 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-03 15:16:28.305  3993  5908 I SystemUpdateService: now status is 0 (complete)
11-03 15:16:28.305  3993  5908 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 15:16:28.305  3993  5908 I SystemUpdateService: file has been verified
11-03 15:16:28.305  3993  5908 I SystemUpdateService: OTA package size = 21989297
,11-03 15:16:28.309  5840  5856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-03 15:16:28.309  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:16:28.311  3993  5908 I SystemUpdateService: showing system update notification
,11-03 15:16:28.318   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 15:16:28.319  3993  3993 D SystemUpdateService: onDestroy
,11-03 15:16:28.636   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 15:16:36.151   930  2983 D ConnectivityService: handlePromptUnvalidated 102
,11-03 15:16:48.638   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:49.640   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:50.642   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:51.644   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:52.645   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:16:53.646   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 15:17:04.791   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=204497, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 15:17:11.729  3664  3873 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-03 15:17:11.729  3664  3873 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-03 15:17:11.771  3585  3585 I ConfigService: onCreate
,11-03 15:17:16.810  3585  3585 I ConfigService: onDestroy
,11-03 15:17:18.647   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-03 15:17:18.648   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 15:17:28.296   930   943 W BroadcastQueue: Timeout of broadcast BroadcastRecord{be8d899 u-1 android.net.conn.CONNECTIVITY_CHANGE} - receiver=android.os.BinderProxy@379075e, started 60001ms ago
11-03 15:17:28.296   930   943 W BroadcastQueue: Receiver during timeout: ResolveInfo{b7af73f com.test.thalitest/io.jxcore.node.ConnectivityChangeListener m=0x108000}
,11-03 15:17:28.324  5840  5840 D BtGatt.ScanManager: awakened up at time 228030
,11-03 15:17:28.325  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:17:28.346   930   943 I Process : Sending signal. PID: 5612 SIG: 3
,11-03 15:17:28.346  5612  5617 I art     : Thread[2,tid=5617,WaitingInMainSignalCatcherLoop,Thread*=0xef38b000,peer=0x12c2f0a0,"Signal Catcher"]: reacting to signal 3
,11-03 15:17:28.359  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-03 15:17:28.359  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:17:28.359  5840  5856 D BtGatt.GattService: current time is 228065855837
,11-03 15:17:28.360  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -85, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -52, 11, 57, -70, 107, -17, 1, 0, -100, -92, 2, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0]
,11-03 15:17:28.363  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:17:28.364  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:17:28.365  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:17:28.365  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:17:28.365  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:17:28.366  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:17:28.366  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
,11-03 15:17:28.446  3585  5918 I VacuumService: Vacuum at: now=1478182648446 tag=VacuumService
,11-03 15:17:28.472  3585  5921 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-03 15:17:28.503  3585  5919 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-03 15:17:28.506  3585  5919 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-03 15:17:28.527  3585  5919 W Uploader:  no longer exists, so no auth token.
,11-03 15:17:28.534  3585  5921 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 15:17:28.546   930   943 I Process : Sending signal. PID: 930 SIG: 3
,11-03 15:17:28.546   930   935 I art     : Thread[2,tid=935,WaitingInMainSignalCatcherLoop,Thread*=0x7f97243000,peer=0x12c010a0,"Signal Catcher"]: reacting to signal 3
,11-03 15:17:28.648   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:28.747   930   943 I Process : Sending signal. PID: 3826 SIG: 3
,11-03 15:17:28.747  3826  3834 I art     : Thread[2,tid=3834,WaitingInMainSignalCatcherLoop,Thread*=0x7f97243000,peer=0x12c560a0,"Signal Catcher"]: reacting to signal 3
11-03 15:17:28.752  5612  5617 I art     : Wrote stack traces to '/data/anr/traces.txt'
11-03 15:17:28.752   930   943 I Process : Sending signal. PID: 3804 SIG: 3
11-03 15:17:28.752  3804  3812 I art     : Thread[2,tid=3812,WaitingInMainSignalCatcherLoop,Thread*=0x7f97243000,peer=0x12c550a0,"Signal Catcher"]: reacting to signal 3
,11-03 15:17:28.804  3804  3812 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-03 15:17:28.804   930   943 I Process : Sending signal. PID: 3780 SIG: 3
11-03 15:17:28.804  3780  3792 I art     : Thread[2,tid=3792,WaitingInMainSignalCatcherLoop,Thread*=0x7f97243000,peer=0x12c520a0,"Signal Catcher"]: reacting to signal 3
,11-03 15:17:28.893  3780  3792 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-03 15:17:28.893   930   943 I Process : Sending signal. PID: 3125 SIG: 3
11-03 15:17:28.894  3125  3130 I art     : Thread[2,tid=3130,WaitingInMainSignalCatcherLoop,Thread*=0x7f97243000,peer=0x12c310a0,"Signal Catcher"]: reacting to signal 3
,11-03 15:17:28.926  3826  3834 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-03 15:17:29.080  3125  3130 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-03 15:17:29.431  3585  5928 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 15:17:29.458   930   935 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-03 15:17:29.649   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:29.660  3585  5929 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 15:17:29.861  3585  5919 W Uploader:  no longer exists, so no auth token.
,11-03 15:17:29.873  3585  5928 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 15:17:29.972  3585  5929 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 15:17:30.093  3585  5928 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 15:17:30.649   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:31.650   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:31.931   930   943 E ActivityManager: ANR in com.test.thalitest
11-03 15:17:31.931   930   943 E ActivityManager: PID: 5612
11-03 15:17:31.931   930   943 E ActivityManager: Reason: Broadcast of Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.test.thalitest/io.jxcore.node.ConnectivityChangeListener (has extras) }
11-03 15:17:31.931   930   943 E ActivityManager: Load: 6.34 / 4.15 / 1.77
11-03 15:17:31.931   930   943 E ActivityManager: CPU usage from 55157ms to 0ms ago:
11-03 15:17:31.931   930   943 E ActivityManager:   0.4% 930/system_server: 0.1% user + 0.3% kernel / faults: 15 minor
11-03 15:17:31.931   930   943 E ActivityManager:   0.3% 213/kworker/0:2: 0% user + 0.3% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0.2% 390/msm_irqbalance: 0% user + 0.1% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0.1% 45/kworker/u16:2: 0% user + 0.1% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0.1% 517/thermal-engine: 0% user + 0.1% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 200/kworker/u16:3: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 291/msm-core:sampli: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 250/mmcqd/0: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 3585/com.google.process.gapps: 0% user + 0% kernel / faults: 320 minor
11-03 15:17:31.931   930   943 E ActivityManager:   0% 3664/com.google.android.inputmethod.latin: 0% user + 0% kernel / faults: 35 minor
11-03 15:17:31.931   930   943 E ActivityManager:   0% 241/cfinteractive: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 8/rcu_preempt: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 30/kworker/1:1H: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 35/kworker/u17:0: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 37/kworker/u17:1: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 382/lmkd: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 383/servicemanager: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 435/irq/215-fc38800: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 477/dmcrypt_write: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 501/adbd: 0% user + 0% kernel / faults: 4 minor
11-03 15:17:31.931   930   943 E ActivityManager:   0% 519/perfd: 0% user + 0% kernel / faults: 39 minor
11-03 15:17:31.931   930   943 E ActivityManager:   0% 534/ATFWD-daemon: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 547/kworker/u17:6: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 3804/com.android.nfc: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 5551/com.google.android.apps.docs: 0% user + 0% kernel / faults: 21 minor
11-03 15:17:31.931   930   943 E ActivityManager:   0% 5600/logcat: 0% user + 0% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   0% 5840/com.android.bluetooth: 0% user + 0% kernel / faults: 764 minor
11-03 15:17:31.931   930   943 E ActivityManager: 0.2% TOTAL: 0% user + 0.1% kernel + 0% iowait + 0% softirq
11-03 15:17:31.931   930   943 E ActivityManager: CPU usage from 3073ms to 3593ms later:
11-03 15:17:31.931   930   943 E ActivityManager:   7.5% 930/system_server: 1.8% user + 5.6% kernel / faults: 1 minor
11-03 15:17:31.931   930   943 E ActivityManager:     5.6% 943/ActivityManager: 0% user + 5.6% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   1.4% 200/kworker/u16:3: 0% user + 1.4% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   1.5% 390/msm_irqbalance: 0% user + 1.5% kernel
11-03 15:17:31.931   930   943 E ActivityManager:   1.6% 534/ATFWD-daemon: 0% user + 1.6% kernel
11-03 15:17:31.931   930   943 E ActivityManager:     1.6% 534/ATFWD-daemon: 0% user + 1.6% kernel
11-03 15:17:31.931 ,  930   943 E ActivityManager: 0.7% TOTAL: 0% user + 0.7% kernel
,11-03 15:17:31.976   407   407 W Binder_2: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[35320]" dev="sockfs" ino=35320 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 15:17:31.976   407   407 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[35320]" dev="sockfs" ino=35320 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 15:17:31.980   745   745 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[35903]" dev="sockfs" ino=35903 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 15:17:31.981   930  5932 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 15:17:31.980   745   745 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[35903]" dev="sockfs" ino=35903 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 15:17:31.985  5840  5840 D BtGatt.ScanManager: awakened up at time 231692
,11-03 15:17:31.986  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:17:32.000  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-03 15:17:32.000  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:17:32.000  5840  5856 D BtGatt.GattService: current time is 231706621564
11-03 15:17:32.000  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -91, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -78, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:17:32.000  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:17:32.001  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:17:32.001  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-03 15:17:32.001  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:17:32.094   930  5932 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 15:17:32.651   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:33.384   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=233090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 15:17:33.652   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 15:17:37.004  5840  5840 D BtGatt.ScanManager: awakened up at time 236710
,11-03 15:17:37.006  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:17:37.040  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:17:37.040  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:17:37.041  5840  5856 D BtGatt.GattService: current time is 236747182578
,11-03 15:17:37.041  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -84, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -90, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -86, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:17:37.041  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:17:37.042  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:17:37.042  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-03 15:17:37.042  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:17:37.043  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:17:37.043  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:17:38.654   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:39.655   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:40.656   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:41.658   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:42.059  5840  5840 D BtGatt.ScanManager: awakened up at time 241765
,11-03 15:17:42.061  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:17:42.082  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-03 15:17:42.082  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:17:42.082  5840  5856 D BtGatt.GattService: current time is 241789054737
11-03 15:17:42.083  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -85, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:17:42.083  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:17:42.083  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:17:42.083  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:17:42.083  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:17:42.084  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:17:42.084  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:17:42.659   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:43.660   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 15:17:47.110  5840  5840 D BtGatt.ScanManager: awakened up at time 246816
,11-03 15:17:47.111  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:17:47.134  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:17:47.134  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:17:47.135  5840  5856 D BtGatt.GattService: current time is 246841257612
11-03 15:17:47.135  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -91, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -78, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:17:47.135  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:17:47.135  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:17:47.136  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-03 15:17:47.136  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:17:47.136  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:17:52.166  5840  5840 D BtGatt.ScanManager: awakened up at time 251872
,11-03 15:17:52.168  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:17:52.190  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:17:52.191  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:17:52.191  5840  5856 D BtGatt.GattService: current time is 251897475595
11-03 15:17:52.191  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -84, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -92, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -85, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:17:52.191  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:17:52.192  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:17:52.192  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:17:52.192  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:17:52.192  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:17:52.192  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:17:53.662   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:54.663   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:55.665   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:56.666   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:57.236  5840  5840 D BtGatt.ScanManager: awakened up at time 256942
11-03 15:17:57.238  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:17:57.263  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:17:57.264  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:17:57.264  5840  5856 D BtGatt.GattService: current time is 256970397862
11-03 15:17:57.264  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -86, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:17:57.264  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:17:57.264  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:17:57.265  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:17:57.265  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:17:57.265  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 15:17:57.667   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:17:58.668   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 15:18:02.297  5840  5840 D BtGatt.ScanManager: awakened up at time 262003,
,11-03 15:18:02.299  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:02.323  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-03 15:18:02.323  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:18:02.324  5840  5856 D BtGatt.GattService: current time is 262030276199
,11-03 15:18:02.324  5840  5856 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -89, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -76, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -106, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -83, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -84, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:18:02.324  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:18:02.324  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:18:02.324  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:18:02.325  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:18:02.325  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:18:02.325  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:18:06.265   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=265970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 15:18:07.329  5840  5840 D BtGatt.ScanManager: awakened up at time 267035
,11-03 15:18:07.332  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:07.367  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:18:07.367  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:07.367  5840  5856 D BtGatt.GattService: current time is 267073640576
11-03 15:18:07.367  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -86, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -84, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -91, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -86, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:18:07.368  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:18:07.368  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-03 15:18:07.368  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:18:07.368  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:18:07.368  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 15:18:12.372  5840  5840 D BtGatt.ScanManager: awakened up at time 272078
,11-03 15:18:12.374  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:12.407  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:18:12.408  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:12.408  5840  5856 D BtGatt.GattService: current time is 272114463870
11-03 15:18:12.408  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -86, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 20, -72, -37, 11, 81, 81, 1, -128, -91, 35, 0, 3, 2, 1, 26, 0]
11-03 15:18:12.409  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:18:12.409  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:18:12.409  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:18:12.410  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:18:12.410  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
,11-03 15:18:13.670   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:18:14.671   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:18:15.673   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:18:16.674   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:18:17.423  5840  5840 D BtGatt.ScanManager: awakened up at time 277129
11-03 15:18:17.424  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:17.440  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-03 15:18:17.440  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:17.440  5840  5856 D BtGatt.GattService: current time is 277147060347
11-03 15:18:17.441  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -84, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 20, -72, -37, 11, 81, 81, 1, -128, -85, 37, 0, 3, 2, 1, 26, 0]
11-03 15:18:17.441  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:18:17.441  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-03 15:18:17.441  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-03 15:18:17.441  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
,11-03 15:18:17.675   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:18:18.676   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 15:18:22.473  5840  5840 D BtGatt.ScanManager: awakened up at time 282179
,11-03 15:18:22.475  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:22.498  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-03 15:18:22.498  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:22.498  5840  5856 D BtGatt.GattService: current time is 282204872379
11-03 15:18:22.498  5840  5856 D BtGatt.GattService: Batch record : [20, -72, -37, 11, 81, 81, 1, -128, -99, 39, 0, 3, 2, 1, 26, 0, -46, -4, -117, 6, 105, -37, 1, -128, -80, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -85, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -99, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -83, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -91, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -86, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:18:22.499  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:18:22.499  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:18:22.499  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:18:22.499  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:18:22.499  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:18:22.500  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:18:22.500  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:18:26.612   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=286318, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 15:18:27.527  5840  5840 D BtGatt.ScanManager: awakened up at time 287234
11-03 15:18:27.528  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:27.551  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:18:27.551  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:27.551  5840  5856 D BtGatt.GattService: current time is 287258032986
11-03 15:18:27.552  5840  5856 D BtGatt.GattService: Batch record : [20, -72, -37, 11, 81, 81, 1, -128, -84, 41, 0, 3, 2, 1, 26, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -83, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -86, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:18:27.552  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:18:27.552  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:18:27.552  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:18:27.552  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:18:27.553  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:18:27.553  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:18:32.582  5840  5840 D BtGatt.ScanManager: awakened up at time 292288
,11-03 15:18:32.584  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:32.606  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-03 15:18:32.606  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:32.606  5840  5856 D BtGatt.GattService: current time is 292313072445
11-03 15:18:32.607  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 20, -72, -37, 11, 81, 81, 1, -128, -99, 51, 0, 3, 2, 1, 26, 0, 71, -122, -77, 84, 69, -12, 1, -128, -84, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -85, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:18:32.607  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:18:32.607  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:18:32.608  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:18:32.608  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:18:32.608  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:18:32.608  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:18:37.638  5840  5840 D BtGatt.ScanManager: awakened up at time 297344
,11-03 15:18:37.640  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:37.663  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-03 15:18:37.663  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:37.663  5840  5856 D BtGatt.GattService: current time is 297369739401
11-03 15:18:37.663  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -87, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 20, -72, -37, 11, 81, 81, 1, -128, -94, 49, 0, 3, 2, 1, 26, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -91, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:18:37.664  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:18:37.664  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:18:37.664  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:18:37.664  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:18:37.664  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:18:37.665  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:18:37.665  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:18:38.678   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:18:39.679   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:18:40.681   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:18:41.682   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:18:42.683   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:18:42.699  5840  5840 D BtGatt.ScanManager: awakened up at time 302405
,11-03 15:18:42.700  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:42.723  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-03 15:18:42.724  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:42.724  5840  5856 D BtGatt.GattService: current time is 302430369282
11-03 15:18:42.724  5840  5856 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -85, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -81, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 20, -72, -37, 11, 81, 81, 1, -128, -104, 42, 0, 3, 2, 1, 26, 0, 81, 34, 97, 112, -14, -5, 1, -128, -86, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:18:42.724  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:18:42.724  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:18:42.725  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:18:42.725  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:18:42.725  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:18:42.725  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:18:42.725  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:18:43.684   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 15:18:47.755  5840  5840 D BtGatt.ScanManager: awakened up at time 307461
11-03 15:18:47.756  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:47.780  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-03 15:18:47.780  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:47.780  5840  5856 D BtGatt.GattService: current time is 307486555265
,11-03 15:18:47.780  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -83, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -91, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -84, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:18:47.781  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:18:47.781  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:18:47.781  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:18:47.781  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:18:47.781  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:18:52.809  5840  5840 D BtGatt.ScanManager: awakened up at time 312516
,11-03 15:18:52.811  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:52.834  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:18:52.834  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:52.834  5840  5856 D BtGatt.GattService: current time is 312540909668
11-03 15:18:52.835  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -79, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -85, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -93, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:18:52.835  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:18:52.835  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:18:52.835  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:18:52.835  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:18:52.836  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:18:52.836  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:18:57.864  5840  5840 D BtGatt.ScanManager: awakened up at time 317570
,11-03 15:18:57.865  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:18:57.888  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:18:57.888  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:18:57.888  5840  5856 D BtGatt.GattService: current time is 317594514504
11-03 15:18:57.888  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -85, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -80, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -86, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:18:57.888  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:18:57.889  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:18:57.889  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:18:57.889  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:18:57.889  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:18:57.889  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:19:02.691   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=322397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 15:19:02.922  5840  5840 D BtGatt.ScanManager: awakened up at time 322628
,11-03 15:19:02.925  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:02.949  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:19:02.949  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:02.949  5840  5856 D BtGatt.GattService: current time is 322655724389
11-03 15:19:02.949  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -90, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -87, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
,11-03 15:19:02.950  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:02.950  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:19:02.950  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:19:02.950  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:19:02.951  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,11-03 15:19:07.954  5840  5840 D BtGatt.ScanManager: awakened up at time 327660
,11-03 15:19:07.956  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:07.983  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:19:07.983  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:07.983  5840  5856 D BtGatt.GattService: current time is 327689516819
11-03 15:19:07.983  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -86, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -92, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:19:07.983  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:19:07.984  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:19:07.984  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:07.984  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:19:07.985  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:19:07.985  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:19:08.685   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-03 15:19:08.685   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 15:19:12.987  5840  5840 D BtGatt.ScanManager: awakened up at time 332693
,11-03 15:19:12.991  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:13.018  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:19:13.018  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:13.018  5840  5856 D BtGatt.GattService: current time is 332724544678
11-03 15:19:13.018  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -83, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:19:13.018  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:13.019  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:19:13.019  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:19:13.019  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:19:13.019  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 15:19:14.478   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=334184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 15:19:18.039  5840  5840 D BtGatt.ScanManager: awakened up at time 337745
,11-03 15:19:18.040  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:18.063  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-03 15:19:18.063  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:18.063  5840  5856 D BtGatt.GattService: current time is 337769674482
11-03 15:19:18.063  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -85, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:19:18.064  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:18.064  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:19:18.064  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:19:18.064  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:19:23.092  5840  5840 D BtGatt.ScanManager: awakened up at time 342798
,11-03 15:19:23.094  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:23.116  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-03 15:19:23.117  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:23.117  5840  5856 D BtGatt.GattService: current time is 342823441859
,11-03 15:19:23.117  5840  5856 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -85, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -101, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -90, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:19:23.117  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:19:23.118  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:19:23.118  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:19:23.118  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:23.119  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:19:23.119  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:19:23.686   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:24.688   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:25.689   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:26.691   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:27.692   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:28.145  5840  5840 D BtGatt.ScanManager: awakened up at time 347851
11-03 15:19:28.146  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:28.168  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:19:28.168  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:28.169  5840  5856 D BtGatt.GattService: current time is 347875278720
11-03 15:19:28.169  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -81, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -80, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -86, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:19:28.169  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:28.169  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:19:28.170  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:19:28.170  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:19:28.170  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:19:28.170  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:19:28.693   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 15:19:33.202  5840  5840 D BtGatt.ScanManager: awakened up at time 352908
,11-03 15:19:33.204  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:33.220  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
11-03 15:19:33.220  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:19:33.221  5840  5856 D BtGatt.GattService: current time is 352927274418
11-03 15:19:33.221  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -84, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:19:33.221  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:33.221  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:19:33.222  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:19:33.695   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:34.696   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:35.698   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:36.699   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:37.701   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:38.256  5840  5840 D BtGatt.ScanManager: awakened up at time 357962
,11-03 15:19:38.258  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:38.281  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:19:38.281  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:38.281  5840  5856 D BtGatt.GattService: current time is 357987504786
11-03 15:19:38.281  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -84, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -91, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -86, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:19:38.281  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:38.282  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:19:38.282  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:19:38.282  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:19:38.282  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:19:38.282  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:19:38.702   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 15:19:43.311  5840  5840 D BtGatt.ScanManager: awakened up at time 363017
,11-03 15:19:43.313  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:43.335  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:19:43.336  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:43.336  5840  5856 D BtGatt.GattService: current time is 363042380795
11-03 15:19:43.336  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -86, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:19:43.336  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:43.337  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:19:43.337  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:19:43.337  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:19:43.337  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:19:43.337  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:19:48.379  5840  5840 D BtGatt.ScanManager: awakened up at time 368085
,11-03 15:19:48.382  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:48.407  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-03 15:19:48.407  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:48.407  5840  5856 D BtGatt.GattService: current time is 368113939701
,11-03 15:19:48.408  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -76, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -83, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -90, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:19:48.408  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:19:48.408  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:48.408  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:19:48.408  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:19:48.408  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-03 15:19:48.703   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:49.705   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:50.692   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=370397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 15:19:50.706   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:51.708   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:52.709   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:19:53.432  5840  5840 D BtGatt.ScanManager: awakened up at time 373138
,11-03 15:19:53.434  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:53.457  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:19:53.457  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:53.457  5840  5856 D BtGatt.GattService: current time is 373163977061
11-03 15:19:53.458  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -91, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -87, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:19:53.458  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:53.458  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:19:53.458  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:19:53.459  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:19:53.459  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:19:53.459  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:19:53.710   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 15:19:58.486  5840  5840 D BtGatt.ScanManager: awakened up at time 378193
,11-03 15:19:58.488  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:19:58.510  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:19:58.511  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:19:58.511  5840  5856 D BtGatt.GattService: current time is 378217421157
,11-03 15:19:58.511  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -78, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -79, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -87, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:19:58.511  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:19:58.512  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:19:58.512  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:19:58.512  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:19:58.512  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:19:58.512  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:20:03.545  5840  5840 D BtGatt.ScanManager: awakened up at time 383251
,11-03 15:20:03.546  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:03.572  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:20:03.573  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:03.573  5840  5856 D BtGatt.GattService: current time is 383279337879
11-03 15:20:03.573  5840  5856 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -100, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -85, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -90, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -76, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:20:03.573  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:20:03.574  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:20:03.574  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:03.574  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:20:03.574  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:03.574  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:20:08.578  5840  5840 D BtGatt.ScanManager: awakened up at time 388284
,11-03 15:20:08.582  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:08.614  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:20:08.614  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:08.614  5840  5856 D BtGatt.GattService: current time is 388320575441
11-03 15:20:08.614  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -92, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -87, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:08.615  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:20:08.615  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:20:08.615  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:20:08.615  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:08.616  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:20:08.616  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:20:08.711   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:20:09.712   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:20:10.714   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:20:11.715   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:20:12.717   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:20:13.619  5840  5840 D BtGatt.ScanManager: awakened up at time 393325
,11-03 15:20:13.621  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:13.656  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:20:13.657  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:13.657  5840  5856 D BtGatt.GattService: current time is 393363724601
11-03 15:20:13.658  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -86, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:20:13.658  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:13.659  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:13.659  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:20:13.659  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:20:13.660  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:20:13.660  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:20:13.718   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 15:20:18.670  5840  5840 D BtGatt.ScanManager: awakened up at time 398376
,11-03 15:20:18.671  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:18.693  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:20:18.694  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:18.694  5840  5856 D BtGatt.GattService: current time is 398400445382
11-03 15:20:18.694  5840  5856 D BtGatt.GattService: Batch record : [20, -72, -37, 11, 81, 81, 1, -128, -96, 65, 0, 3, 2, 1, 26, 0, -46, -4, -117, 6, 105, -37, 1, -128, -76, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -91, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -83, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:20:18.694  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:20:18.694  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:20:18.695  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:18.695  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:20:18.695  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:20:23.729  5840  5840 D BtGatt.ScanManager: awakened up at time 403435
,11-03 15:20:23.731  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:23.755  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-03 15:20:23.755  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:23.756  5840  5856 D BtGatt.GattService: current time is 403462265184
11-03 15:20:23.756  5840  5856 D BtGatt.GattService: Batch record : [20, -72, -37, 11, 81, 81, 1, -128, -96, 74, 0, 3, 2, 1, 26, 0, -46, -4, -117, 6, 105, -37, 1, -128, -80, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -92, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -85, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:23.756  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:20:23.756  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:20:23.757  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:20:23.757  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:20:23.757  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:23.757  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:20:23.757  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97,, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:20:28.780  5840  5840 D BtGatt.ScanManager: awakened up at time 408486
,11-03 15:20:28.781  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:28.803  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:20:28.803  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:28.803  5840  5856 D BtGatt.GattService: current time is 408509455550
11-03 15:20:28.803  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -86, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:20:28.803  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:28.803  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:28.804  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:20:28.804  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:20:28.804  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:20:28.804  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:20:33.519   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=413224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 15:20:33.719   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:20:33.840  5840  5840 D BtGatt.ScanManager: awakened up at time 413546
,11-03 15:20:33.843  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:33.866  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:20:33.866  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:33.866  5840  5856 D BtGatt.GattService: current time is 413572625149
11-03 15:20:33.866  5840  5856 D BtGatt.GattService: Batch record : [20, -72, -37, 11, 81, 81, 1, -128, -104, 93, 0, 3, 2, 1, 26, 0, -46, -4, -117, 6, 105, -37, 1, -128, -76, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -83, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -90, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:33.866  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:20:33.867  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:20:33.867  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:20:33.867  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:20:33.868  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:33.868  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-03 15:20:34.721   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:20:35.722   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:20:36.724   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:20:37.725   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:20:38.726   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 15:20:38.895  5840  5840 D BtGatt.ScanManager: awakened up at time 418601
,11-03 15:20:38.896  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:38.919  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-03 15:20:38.919  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:38.919  5840  5856 D BtGatt.GattService: current time is 418625980705
,11-03 15:20:38.920  5840  5856 D BtGatt.GattService: Batch record : [20, -72, -37, 11, 81, 81, 1, -128, -88, 69, 0, 3, 2, 1, 26, 0, 35, 97, 126, -92, 22, -56, 1, -128, -86, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -79, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -94, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:20:38.920  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:20:38.920  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:38.920  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:38.921  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:20:38.921  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:20:38.921  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:20:43.942  5840  5840 D BtGatt.ScanManager: awakened up at time 423649
,11-03 15:20:43.944  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:43.967  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-03 15:20:43.967  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:43.967  5840  5856 D BtGatt.GattService: current time is 423673706104
11-03 15:20:43.967  5840  5856 D BtGatt.GattService: Batch record : [20, -72, -37, 11, 81, 81, 1, -128, -90, 68, 0, 3, 2, 1, 26, 0, 71, -122, -77, 84, 69, -12, 1, -128, -82, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -79, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -76, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:20:43.968  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:20:43.968  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:20:43.968  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 15:20:43.968  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:43.968  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:20:43.969  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:43.969  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:20:48.999  5840  5840 D BtGatt.ScanManager: awakened up at time 428706
,11-03 15:20:49.001  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:49.024  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:20:49.024  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:49.024  5840  5856 D BtGatt.GattService: current time is 428731119363
11-03 15:20:49.025  5840  5856 D BtGatt.GattService: Batch record : [20, -72, -37, 11, 81, 81, 1, -128, -94, 74, 0, 3, 2, 1, 26, 0, -46, -4, -117, 6, 105, -37, 1, -128, -76, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -96, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -90, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:49.025  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:20:49.025  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:20:49.025  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:20:49.025  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:49.026  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:20:49.026  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:20:54.059  5840  5840 D BtGatt.ScanManager: awakened up at time 433765
,11-03 15:20:54.060  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:54.087  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:20:54.087  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:20:54.087  5840  5856 D BtGatt.GattService: current time is 433793556062
11-03 15:20:54.087  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -87, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -85, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -92, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:20:54.087  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:54.088  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:54.088  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:20:54.088  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:20:54.088  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:20:54.088  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:20:59.116  5840  5840 D BtGatt.ScanManager: awakened up at time 438822
,11-03 15:20:59.118  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:20:59.142  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-03 15:20:59.143  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:20:59.143  5840  5856 D BtGatt.GattService: current time is 438849358056
11-03 15:20:59.143  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 20, -72, -37, 11, 81, 81, 1, -128, -102, 75, 0, 3, 2, 1, 26, 0, 81, 34, 97, 112, -14, -5, 1, -128, -85, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:20:59.143  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:20:59.143  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:20:59.144  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:20:59.144  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 26]
11-03 15:20:59.144  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:20:59.144  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 15:20:59.144  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:21:03.727   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-03 15:21:03.727   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 15:21:04.172  5840  5840 D BtGatt.ScanManager: awakened up at time 443878
,11-03 15:21:04.173  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:04.196  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-03 15:21:04.196  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:04.197  5840  5856 D BtGatt.GattService: current time is 443903222362
11-03 15:21:04.197  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -101, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -91, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -84, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:21:04.197  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:21:04.198  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:21:04.198  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:21:04.198  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:21:04.198  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:21:09.202  5840  5840 D BtGatt.ScanManager: awakened up at time 448908
,11-03 15:21:09.204  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:09.240  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-03 15:21:09.241  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:21:09.241  5840  5856 D BtGatt.GattService: current time is 448947520836
,11-03 15:21:09.242  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -87, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -84, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -92, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -52, 11, 57, -70, 107, -17, 1, 0, -94, 75, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,11-03 15:21:09.242  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:21:09.243  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:21:09.244  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:21:09.244  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:21:09.244  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,11-03 15:21:09.245  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,11-03 15:21:09.625   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=449330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 15:21:14.246  5840  5840 D BtGatt.ScanManager: awakened up at time 453952
11-03 15:21:14.249  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:14.277  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-03 15:21:14.277  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:14.277  5840  5856 D BtGatt.GattService: current time is 453983700630
11-03 15:21:14.277  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -85, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -84, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:21:14.278  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:21:14.278  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:21:14.278  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:21:14.278  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:21:14.278  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:21:14.279  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-03 15:21:19.299  5840  5840 D BtGatt.ScanManager: awakened up at time 459005
,11-03 15:21:19.301  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:19.323  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:21:19.324  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:19.324  5840  5856 D BtGatt.GattService: current time is 459030456702
11-03 15:21:19.324  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -83, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -91, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -87, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
11-03 15:21:19.324  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:21:19.325  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:21:19.325  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:21:19.325  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:21:19.325  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,11-03 15:21:23.729   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:24.352  5840  5840 D BtGatt.ScanManager: awakened up at time 464059
,11-03 15:21:24.354  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:24.384  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-03 15:21:24.384  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:24.384  5840  5856 D BtGatt.GattService: current time is 464090579506
11-03 15:21:24.384  5840  5856 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -84, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -76, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -52, 11, 57, -70, 107, -17, 1, 0, -94, 82, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 35, 97, 126, -92, 22, -56, 1, -128, -86, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -93, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:21:24.385  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:21:24.385  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:21:24.385  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:21:24.385  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:21:24.385  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
11-03 15:21:24.386  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:21:24.,386  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:21:24.730   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:25.732   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:26.733   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:27.735   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:28.736   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 15:21:29.402  5840  5840 D BtGatt.ScanManager: awakened up at time 469108
,11-03 15:21:29.403  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:29.433  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-03 15:21:29.433  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:29.433  5840  5856 D BtGatt.GattService: current time is 469139575998
11-03 15:21:29.433  5840  5856 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -80, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -85, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -85, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -76, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -52, 11, 57, -70, 107, -17, 1, 0, -97, 76, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
11-03 15:21:29.434  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:21:29.434  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:21:29.434  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:21:29.434  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:21:29.435  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:21:29.435  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:21:29.435  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,11-03 15:21:33.292   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=472998, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 15:21:33.737   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:34.471  5840  5840 D BtGatt.ScanManager: awakened up at time 474177
,11-03 15:21:34.473  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:34.496  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-03 15:21:34.496  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:34.497  5840  5856 D BtGatt.GattService: current time is 474203209775
11-03 15:21:34.497  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:21:34.497  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:21:34.497  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:21:34.497  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:21:34.739   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:35.740   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:36.742   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:37.743   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:38.744   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 15:21:39.526  5840  5840 D BtGatt.ScanManager: awakened up at time 479232
,11-03 15:21:39.527  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:39.549  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:21:39.549  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:39.549  5840  5856 D BtGatt.GattService: current time is 479255693226
11-03 15:21:39.549  5840  5856 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -84, 100, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -92, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -87, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -84, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:21:39.550  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:21:39.550  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:21:39.550  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:21:39.550  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:21:39.550  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:21:44.579  5840  5840 D BtGatt.ScanManager: awakened up at time 484285
,11-03 15:21:44.581  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:44.603  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-03 15:21:44.604  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:44.604  5840  5856 D BtGatt.GattService: current time is 484310380171
,11-03 15:21:44.604  5840  5856 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -81, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -91, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -86, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -76, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:21:44.604  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:21:44.605  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:21:44.605  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:21:44.605  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:21:44.605  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:21:44.605  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:21:48.746   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:49.632  5840  5840 D BtGatt.ScanManager: awakened up at time 489338
11-03 15:21:49.634  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:49.656  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-03 15:21:49.656  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:49.657  5840  5856 D BtGatt.GattService: current time is 489363161212
11-03 15:21:49.657  5840  5856 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -84, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -84, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -90, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:21:49.657  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:21:49.658  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:21:49.658  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:21:49.658  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:21:49.658  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:21:49.747   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:50.748   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:51.750   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:52.751   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:21:53.752   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 15:21:54.686  5840  5840 D BtGatt.ScanManager: awakened up at time 494392
,11-03 15:21:54.687  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:54.710  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:21:54.710  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:54.710  5840  5856 D BtGatt.GattService: current time is 494417096998
11-03 15:21:54.711  5840  5856 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -94, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -75, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:21:54.711  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:21:54.711  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:21:54.711  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:21:54.712  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:21:54.712  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-03 15:21:54.712  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:21:59.748  5840  5840 D BtGatt.ScanManager: awakened up at time 499454
,11-03 15:21:59.750  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:21:59.774  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:21:59.774  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:21:59.774  5840  5856 D BtGatt.GattService: current time is 499480579119
11-03 15:21:59.774  5840  5856 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -76, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -85, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -92, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:21:59.774  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:21:59.775  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:21:59.775  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:21:59.775  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:21:59.775  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:21:59.775  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-03 15:22:04.805  5840  5840 D BtGatt.ScanManager: awakened up at time 504511
11-03 15:22:04.807  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:04.840  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-03 15:22:04.841  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:22:04.841  5840  5856 D BtGatt.GattService: current time is 504547326817
11-03 15:22:04.841  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -52, 11, 57, -70, 107, -17, 1, 0, -97, 91, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 116, -43, -111, -91, -20, -29, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -85, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -93, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:22:04.841  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:22:04.842  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
11-03 15:22:04.842  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:22:04.842  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:22:04.842  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 15:22:04.842  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:22:04.842  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:22:08.754   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:22:09.359   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=509065, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 15:22:09.756   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:22:09.846  5840  5840 D BtGatt.ScanManager: awakened up at time 509552
,11-03 15:22:09.848  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:09.882  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:22:09.883  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:22:09.883  5840  5856 D BtGatt.GattService: current time is 509589458483
11-03 15:22:09.883  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -75, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:22:09.883  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:22:09.884  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:22:09.884  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:22:09.884  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:22:09.884  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 15:22:10.757   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:22:11.759   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:22:12.760   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:22:13.761   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 15:22:14.889  5840  5840 D BtGatt.ScanManager: awakened up at time 514595
,11-03 15:22:14.892  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:14.927  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:22:14.927  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:22:14.928  5840  5856 D BtGatt.GattService: current time is 514634169574
,11-03 15:22:14.928  5840  5856 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -79, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -76, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -98, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 15:22:14.929  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:22:14.929  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,11-03 15:22:14.929  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:22:14.930  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:22:14.931  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 15:22:19.942  5840  5840 D BtGatt.ScanManager: awakened up at time 519649
,11-03 15:22:19.944  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:19.966  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:22:19.966  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:22:19.967  5840  5856 D BtGatt.GattService: current time is 519673191547
11-03 15:22:19.967  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 100, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -94, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -52, 11, 57, -70, 107, -17, 1, 0, -99, 87, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, -46, -4, -117, 6, 105, -37, 1, -128, -78, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:22:19.967  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:22:19.968  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:22:19.968  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
11-03 15:22:19.968  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:22:19.968  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:22:19.968  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 15:22:24.995  5840  5840 D BtGatt.ScanManager: awakened up at time 524701
,11-03 15:22:24.997  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:25.019  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-03 15:22:25.020  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:22:25.020  5840  5856 D BtGatt.GattService: current time is 524726426423
,11-03 15:22:25.020  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -75, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -80, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -52, 11, 57, -70, 107, -17, 1, 0, -98, 10, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0, 81, 34, 97, 112, -14, -5, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:22:25.021  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:22:25.021  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:22:25.021  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:22:25.022  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:22:25.022  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:22:25.022  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
11-03 15:22:25.022  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:22:30.049  5840  5840 D BtGatt.ScanManager: awakened up at time 529755
,11-03 15:22:30.051  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:30.066  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-03 15:22:30.066  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:22:30.067  5840  5856 D BtGatt.GattService: current time is 529773254830
,11-03 15:22:30.067  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -90, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -76, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:22:30.067  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:22:30.067  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:22:30.068  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:22:30.585   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=530291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 15:22:33.763   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:22:34.764   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:22:35.102  5840  5840 D BtGatt.ScanManager: awakened up at time 534808
,11-03 15:22:35.104  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:35.126  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-03 15:22:35.127  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:22:35.127  5840  5856 D BtGatt.GattService: current time is 534833439276
11-03 15:22:35.127  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -94, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:22:35.127  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:22:35.128  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:22:35.128  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:22:35.128  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 15:22:35.128  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:22:35.766   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:22:36.767   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:22:37.769   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 15:22:38.770   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 15:22:40.155  5840  5840 D BtGatt.ScanManager: awakened up at time 539861
,11-03 15:22:40.157  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:40.180  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-03 15:22:40.180  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:22:40.180  5840  5856 D BtGatt.GattService: current time is 539886745541
11-03 15:22:40.180  5840  5856 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -75, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -89, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -86, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:22:40.181  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:22:40.181  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:22:40.181  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:22:40.181  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,11-03 15:22:40.181  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:22:40.182  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:22:45.208  5840  5840 D BtGatt.ScanManager: awakened up at time 544915
,11-03 15:22:45.210  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:45.233  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-03 15:22:45.233  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:22:45.233  5840  5856 D BtGatt.GattService: current time is 544939859409
11-03 15:22:45.234  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -90, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -76, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:22:45.234  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:22:45.234  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:22:45.234  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:22:45.235  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:22:50.264  5840  5840 D BtGatt.ScanManager: awakened up at time 549970
,11-03 15:22:50.265  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:50.286  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:22:50.287  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:22:50.287  5840  5856 D BtGatt.GattService: current time is 549993461325
11-03 15:22:50.287  5840  5856 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -87, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -85, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -94, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:22:50.287  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:22:50.288  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:22:50.288  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:22:50.288  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:22:50.288  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:22:50.288  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:22:55.318  5840  5840 D BtGatt.ScanManager: awakened up at time 555024
,11-03 15:22:55.319  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:22:55.342  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:22:55.342  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:22:55.343  5840  5856 D BtGatt.GattService: current time is 555049219036
11-03 15:22:55.343  5840  5856 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -85, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:22:55.343  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:22:55.344  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:22:55.344  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:22:55.344  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 15:22:55.344  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:22:55.344  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:23:00.373  5840  5840 D BtGatt.ScanManager: awakened up at time 560079
11-03 15:23:00.374  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:23:00.398  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-03 15:23:00.398  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 15:23:00.398  5840  5856 D BtGatt.GattService: current time is 560104726987
,11-03 15:23:00.398  5840  5856 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -76, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -85, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:23:00.399  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:23:00.399  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:23:00.399  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 15:23:00.399  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:23:00.399  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 15:23:03.771   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-03 15:23:03.771   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 15:23:05.404  5840  5840 D BtGatt.ScanManager: awakened up at time 565110
,11-03 15:23:05.406  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 15:23:05.439  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 15:23:05.439  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 15:23:05.439  5840  5856 D BtGatt.GattService: current time is 565145757395
11-03 15:23:05.439  5840  5856 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -85, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -80, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -92, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:23:05.440  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 15:23:05.440  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 15:23:05.440  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 15:23:05.441  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 15:23:05.441  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 15:23:05.441  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 15:23:06.745   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=566451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}

```
