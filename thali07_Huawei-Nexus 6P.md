#### Test 92380940385026b_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-04 18:40:46.905  3953  4221 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-04 18:40:46.984  3953  4221 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-04 18:40:47.340  5561  5561 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-04 18:40:47.345  5561  5561 D AndroidRuntime: CheckJNI is OFF
11-04 18:40:47.373  5561  5561 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-04 18:40:47.404  5561  5561 I Radio-JNI: register_android_hardware_Radio DONE
11-04 18:40:47.419  5561  5561 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-04 18:40:47.429   925  3127 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-04 18:40:47.449  5561  5561 D AndroidRuntime: Shutting down VM
11-04 18:40:47.456  3935  3947 W SearchService: Abort, client detached.
11-04 18:40:47.475  3935  3935 I HotwordDetector: Closing mic
11-04 18:40:47.475  3935  4194 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fa6af0c
11-04 18:40:47.475  3935  4202 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-04 18:40:47.486   925  3787 I ActivityManager: Start proc 5570:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-04 18:40:47.542   511  4207 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-04 18:40:47.544   511  4207 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-04 18:40:47.550   511  4207 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-04 18:40:47.550   511  4207 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-04 18:40:47.550   511  2963 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-04 18:40:47.552  3935  4197 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-04 18:40:47.554  3935  4200 I MicroRecognitionRnrImpl: Detection finished
11-04 18:40:47.591  5570  5570 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-04 18:40:47.622  5570  5570 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-04 18:40:47.683  5570  5570 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 9676-9732)
,11-04 18:40:47.684  5570  5570 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 18:40:47.719  5570  5570 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5e26b}
,11-04 18:40:47.721  5570  5570 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 18:40:47.721  5570  5570 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 18:40:47.727  5570  5570 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 18:40:47.728  5570  5570 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 18:40:47.778  5570  5570 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 18:40:47.793  5570  5570 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 18:40:47.794  5570  5570 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 18:40:47.794  5570  5570 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 18:40:47.794  5570  5570 I Adreno  : Build Date                       : 12/06/15
11-04 18:40:47.794  5570  5570 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 18:40:47.794  5570  5570 I Adreno  : Local Branch                     : mybranch17112971
11-04 18:40:47.794  5570  5570 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 18:40:47.794  5570  5570 I Adreno  : Remote Branch                    : NONE
11-04 18:40:47.794  5570  5570 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 18:40:47.850   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28d383e:true
,11-04 18:40:47.877   948   948 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[22215]" dev="sockfs" ino=22215 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 18:40:47.877   948   948 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22215]" dev="sockfs" ino=22215 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 18:40:47.891  5570  5570 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 18:40:47.901  5570  5570 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 18:40:47.927   402   402 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32314]" dev="sockfs" ino=32314 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 18:40:47.927   402   402 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32314]" dev="sockfs" ino=32314 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 18:40:47.929  5570  5607 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 18:40:47.931  3564  3564 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[15966]" dev="sockfs" ino=15966 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 18:40:47.931  3564  3564 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15966]" dev="sockfs" ino=15966 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 18:40:47.934  5570  5594 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 18:40:47.969  5570  5607 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 18:40:48.041  3813  3813 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32929]" dev="sockfs" ino=32929 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 18:40:48.041  3813  3813 W Binder_9: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32929]" dev="sockfs" ino=32929 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 18:40:48.044   935   935 W Binder_1: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32928]" dev="sockfs" ino=32928 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 18:40:48.044   935   935 W Binder_1: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32928]" dev="sockfs" ino=32928 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 18:40:48.045   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +585ms
11-04 18:40:48.046  3613  3613 I Keyboard.Facilitator: onFinishInput()
,11-04 18:40:48.090  5570  5570 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5570
,11-04 18:40:48.197  5570  5570 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 18:40:48.440  5570  5609 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -580388560
,11-04 18:40:48.444  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-04 18:40:48.444  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-04 18:40:48.444  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-04 18:40:48.444  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-04 18:40:48.444  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-04 18:40:48.445  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5185a59 added. We now have 1 listener(s)
,11-04 18:40:48.447  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-04 18:40:48.448  5570  5609 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:40:48.448  5570  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 18:40:48.448  5570  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-04 18:40:48.451  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a64cc added. We now have 1 listener(s)
11-04 18:40:48.451  5570  5609 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 18:40:48.456   925  2942 D WifiService: New client listening to asynchronous messages
,11-04 18:40:48.456  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 18:40:48.456  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-04 18:40:48.456  5570  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-04 18:40:48.457  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-04 18:40:48.457  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-04 18:40:48.457  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-04 18:40:48.457  5570  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-04 18:40:48.458  5570  5609 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-04 18:40:48.641  5570  5570 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-04 18:40:48.921  5570  5579 I art     : Background sticky concurrent mark sweep GC freed 74815(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 1.472ms total 228.201ms
,11-04 18:40:50.068   925  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 18:40:50.281  5570  5579 I art     : Background partial concurrent mark sweep GC freed 52834(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.549ms total 331.039ms
,11-04 18:40:50.558  5570  5617 W jxcore-log: Initializing JXcore engine
,11-04 18:40:50.558  5570  5617 W jxcore-log: JXcore engine is ready
,11-04 18:40:50.581  5617  5617 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12180 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-04 18:40:50.581  5617  5617 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13321]" dev="sockfs" ino=13321 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-04 18:40:50.581  5617  5617 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-04 18:40:50.581  5617  5617 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31357]" dev="sockfs" ino=31357 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-04 18:40:50.590  5570  5617 W jxcore-log: Starting JXcore engine
,11-04 18:40:50.640  5570  5617 W jxcore-log: Platform android
11-04 18:40:50.640  5570  5617 W jxcore-log: 
11-04 18:40:50.640  5570  5617 W jxcore-log: Process ARCH arm
11-04 18:40:50.640  5570  5617 W jxcore-log: 
,11-04 18:40:50.820  5570  5617 I jxcore-log: JXcore Cordova bridge is ready!
11-04 18:40:50.820  5570  5617 I jxcore-log: 
,11-04 18:40:50.820  5570  5617 W jxcore-log: JXcore engine is started
,11-04 18:40:50.826  5570  5609 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-04 18:40:50.832  5570  5570 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-04 18:40:51.000  3550  3550 I ConfigService: onDestroy
,11-04 18:40:52.100   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:40:52.470   925  3791 I ActivityManager: Killing 5124:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-04 18:40:53.101   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:40:54.102   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:40:55.102   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:40:56.104   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:40:57.104   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 18:40:59.567   925   925 I ActivityManager: Killing 5215:org.codeaurora.ims/1001 (adj 15): empty #17
,11-04 18:41:00.619  3935  5618 W CronetSyncConnectionRcs: Upload content type not set.
,11-04 18:41:00.690  4859  4889 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-04 18:41:00.692  4859  4859 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-04 18:41:00.744  5570  5617 I jxcore-log: 2016-11-04 17:41:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-04 18:41:00.744  5570  5617 I jxcore-log: 
,11-04 18:41:00.746  5570  5617 I jxcore-log: 2016-11-04 17:41:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-04 18:41:00.746  5570  5617 I jxcore-log: 
,11-04 18:41:00.749  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-04 18:41:00.749  5570  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 18:41:00.749  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:00.749  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:00.749  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 18:41:00.749  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 18:41:00.749  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 18:41:00.749  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 18:41:00.749  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 18:41:00.751  5570  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 18:41:00.752  5570  5617 I jxcore-log: 2016-11-04 17:41:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-04 18:41:00.752  5570  5617 I jxcore-log: 
11-04 18:41:00.753  5570  5617 I jxcore-log: 2016-11-04 17:41:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-04 18:41:00.753  5570  5617 I jxcore-log: 
,11-04 18:41:01.006  5570  5617 I jxcore-log: 2016-11-04 17:41:01 - DEBUG UnitTest_app: 'Running unit tests'
11-04 18:41:01.006  5570  5617 I jxcore-log: 
,11-04 18:41:01.007  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 18:41:01.007  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4250e8b added. We now have 2 listener(s)
11-04 18:41:01.008  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:41:01.008  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 18:41:01.008  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:41:01.008  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:41:01.008  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b7bb68 added. We now have 2 listener(s)
11-04 18:41:01.008  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 18:41:01.009  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 18:41:01.010  5570  5617 D executeNativeTests: Running unit tests
,11-04 18:41:01.046  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 18:41:01.046  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 added. We now have 3 listener(s)
11-04 18:41:01.047  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:41:01.047  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 18:41:01.047  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:41:01.047  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:41:01.047  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 added. We now have 3 listener(s)
11-04 18:41:01.047  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 18:41:01.048  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 18:41:01.049  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 18:41:01.049  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 18:41:01.049  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 18:41:01.049  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 18:41:01.050  5570  5617 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-04 18:41:01.050  5570  5617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 18:41:01.050  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 18:41:01.050  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 18:41:01.050  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 18:41:01.050  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 18:41:01.051  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:01.051  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:01.051  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:01.051  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:01.052  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 18:41:01.052  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:41:01.052  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 removed from the list
11-04 18:41:01.052  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:01.052  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 removed from the list
,11-04 18:41:01.052  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:01.052  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.053  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.053  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.053  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:01.053  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:01.053  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:01.053  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:01.053  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:01.054  5570  5617 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-04 18:41:01.054  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:01.054  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 18:41:01.054  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:01.054  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:01.054  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:01.054  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:01.054  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:01.054  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:01.054  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:01.054  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:01.055  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.055  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.055  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.055  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:01.055  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 18:41:01.055  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:01.055  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:01.057  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-04 18:41:01.057  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-04 18:41:01.057  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 18:41:01.057  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 18:41:01.057  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 18:41:01.057  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-04 18:41:01.057  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-04 18:41:01.058  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 18:41:01.058  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:01.058  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:01.058  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:01.058  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:01.058  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:01.059  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:01.059  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:01.059  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:01.059  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:01.059  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.059  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.059  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.059  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.059  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:01.059  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:01.059  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:01.059  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:01.060  5570  5617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-04 18:41:01.061  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 18:41:01.061  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 18:41:01.069  5570  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 18:41:01.069  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:01.069  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:01.069  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 18:41:01.069  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 18:41:01.069  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 18:41:01.069  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 18:41:01.069  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 18:41:01.070  5570  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 18:41:01.070  5570  5617 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 18:41:01.070  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 18:41:01.070  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 18:41:01.070  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 18:41:01.070  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 18:41:01.070  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 18:41:01.072  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:01.073  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:01.074  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 18:41:01.074  5570  5617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 18:41:01.074  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 18:41:01.077  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.077  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 18:41:01.077  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 18:41:01.078  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 18:41:01.078  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 18:41:01.079  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-04 18:41:01.080  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-04 18:41:01.080  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.080  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 18:41:01.080  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 18:41:01.080  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 18:41:01.080  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 18:41:01.080  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.081  5570  5617 D BluetoothAdapter: STATE_ON
11-04 18:41:01.083  4633  4854 D BtGatt.GattService: registerClient() - UUID=d69c0198-64c9-439d-9dc0-a2197f1a10b8
11-04 18:41:01.084  4633  4693 D BtGatt.GattService: onClientRegistered() - UUID=d69c0198-64c9-439d-9dc0-a2197f1a10b8, clientIf=5
11-04 18:41:01.086  5570  5580 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 18:41:01.087  4633  4646 D BtGatt.GattService: start scan with filters
11-04 18:41:01.093  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 18:41:01.093  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.093  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 18:41:01.094  4633  4696 D BtGatt.ScanManager: handling starting scan
11-04 18:41:01.094  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.094  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 18:41:01.094  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 18:41:01.094  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 18:41:01.094  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 18:41:01.095  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 18:41:01.095  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 18:41:01.095  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.095  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:41:01.095  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 18:41:01.095  4633  4696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:41:01.095  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 18:41:01.096  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.096  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.096  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:01.096  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 18:41:01.096  5570  5617 I io.jxcore.node.ConnectionHelper: start: OK
11-04 18:41:01.102  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:41:01.102  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 18:41:01.103  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:41:01.103  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 18:41:01.103  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:41:01.103  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 18:41:01.106  4633  4693 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 18:41:01.106  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:01.107  4633  4696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 18:41:01.117  4633  4693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 18:41:01.117  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:01.117  4633  4696 D BtGatt.ScanManager: Starting BLE batch scan
11-04 18:41:01.117  4633  4696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 18:41:01.133  4633  4693 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 18:41:01.133  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:01.141  4633  4693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 18:41:01.142  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:41:01.605  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 18:41:01.605  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 18:41:01.605  5570  5570 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 18:41:06.100  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 18:41:06.101  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:06.101  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-04 18:41:06.101  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 18:41:06.101  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 18:41:06.101  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:06.101  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-04 18:41:06.101  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 18:41:06.102  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 18:41:06.102  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 18:41:06.102  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.103  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:06.103  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.103  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 18:41:06.103  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.104  5570  5617 D BluetoothAdapter: STATE_ON
,11-04 18:41:06.104  4633  4843 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 18:41:06.105  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 18:41:06.106  5570  5617 D BluetoothAdapter: STATE_ON
,11-04 18:41:06.106  4633  4696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 18:41:06.107  4633  4854 D BtGatt.GattService: stopScan() - queue size =1
11-04 18:41:06.109  4633  4646 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 18:41:06.110  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 18:41:06.110  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.110  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 18:41:06.110  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:06.111  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.111  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.111  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:06.112  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 18:41:06.112  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.112  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.112  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.112  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 18:41:06.113  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 18:41:06.115  4633  4633 D BtGatt.ScanManager: awakened up at time 98163
11-04 18:41:06.119  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 18:41:06.119  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:06.121  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.121  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:41:06.122  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.122  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:06.122  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 18:41:06.122  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:41:06.122  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:06.122  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 18:41:06.122  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 18:41:06.123  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 18:41:06.123  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 18:41:06.123  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 18:41:06.123  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:06.123  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-04 18:41:06.123  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:06.123  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:41:06.123  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:06.123  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-04 18:41:06.123  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:06.123  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:06.123  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 18:41:06.123  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 18:41:06.123  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 18:41:06.126  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:41:06.126  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:41:06.126  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-04 18:41:06.126  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:41:06.126  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 18:41:06.137  4633  4693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-04 18:41:06.138  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:06.138  4633  4693 D BtGatt.GattService: current time is 98187063171
11-04 18:41:06.139  4633  4693 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -87, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -75, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -84, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-04 18:41:06.140  4633  4693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-04 18:41:06.141  4633  4693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 18:41:06.142  4633  4693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 18:41:06.142  4633  4693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-04 18:41:06.149  4633  4693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 18:41:06.149  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:06.149  4633  4696 D BtGatt.ScanManager: stopping BLe Batch
,11-04 18:41:06.155  4633  4693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 18:41:06.155  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:06.156  4633  4696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 18:41:06.162  4633  4693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 18:41:06.162  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:41:06.628  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 18:41:11.125  5570  5617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-04 18:41:11.131  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 18:41:11.131  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 18:41:11.147  5570  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 18:41:11.147  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:11.147  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:11.147  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 18:41:11.147  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 18:41:11.147  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 18:41:11.147  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 18:41:11.147  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 18:41:11.153  5570  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 18:41:11.154  5570  5617 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 18:41:11.154  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 18:41:11.154  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-04 18:41:11.155  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 18:41:11.155  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 18:41:11.155  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 18:41:11.160  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 18:41:11.162  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 18:41:11.162  5570  5617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-04 18:41:11.163  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 18:41:11.166  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 18:41:11.170  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.171  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 18:41:11.172  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-04 18:41:11.172  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 18:41:11.172  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 18:41:11.181  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:11.181  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 18:41:11.181  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 18:41:11.181  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 18:41:11.181  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 18:41:11.182  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:11.183  5570  5617 D BluetoothAdapter: STATE_ON
,11-04 18:41:11.187  4633  4843 D BtGatt.GattService: registerClient() - UUID=60ebdb83-55ed-4c87-a3b5-b07a813d850e
,11-04 18:41:11.188  4633  4693 D BtGatt.GattService: onClientRegistered() - UUID=60ebdb83-55ed-4c87-a3b5-b07a813d850e, clientIf=5
11-04 18:41:11.189  5570  5581 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 18:41:11.189  4633  4645 D BtGatt.GattService: start scan with filters
,11-04 18:41:11.193  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 18:41:11.193  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.193  4633  4696 D BtGatt.ScanManager: handling starting scan
11-04 18:41:11.193  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 18:41:11.194  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.194  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 18:41:11.194  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 18:41:11.194  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.194  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 18:41:11.194  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 18:41:11.194  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.195  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-04 18:41:11.195  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 18:41:11.196  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 18:41:11.197  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.201  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.202  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 18:41:11.202  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:11.202  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.202  5570  5617 I io.jxcore.node.ConnectionHelper: start: OK
11-04 18:41:11.202  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.204  4633  4693 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 18:41:11.204  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:11.205  4633  4696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 18:41:11.206  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:11.206  5570  5617 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 18:41:11.206  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:11.206  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 18:41:11.206  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 18:41:11.206  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 18:41:11.206  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:11.206  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 18:41:11.209  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.209  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.209  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.209  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.209  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 18:41:11.209  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 18:41:11.209  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 18:41:11.209  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 18:41:11.210  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.210  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.210  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.210  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 18:41:11.210  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:11.211  5570  5617 D BluetoothAdapter: STATE_ON
11-04 18:41:11.211  4633  4843 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 18:41:11.212  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-04 18:41:11.213  5570  5617 D BluetoothAdapter: STATE_ON
11-04 18:41:11.213  4633  4854 D BtGatt.GattService: stopScan() - queue size =1
,11-04 18:41:11.214  4633  4645 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 18:41:11.214  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 18:41:11.214  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:11.214  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-04 18:41:11.215  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:11.215  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.215  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.215  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.215  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 18:41:11.215  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.215  4633  4693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 18:41:11.215  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:11.215  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:11.215  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.215  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 18:41:11.215  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 18:41:11.215  4633  4696 D BtGatt.ScanManager: Starting BLE batch scan
11-04 18:41:11.215  4633  4696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 18:41:11.216  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 18:41:11.216  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.218  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.218  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:41:11.218  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.218  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.218  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:11.218  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 18:41:11.218  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 18:41:11.218  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:41:11.218  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:11.218  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:11.218  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:41:11.218  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:11.219  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 18:41:11.219  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:11.219  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:11.219  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.219  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 18:41:11.219  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 18:41:11.219  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 18:41:11.219  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.219  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.219  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 18:41:11.219  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.221  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.221  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.221  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-04 18:41:11.221  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.221  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:41:11.221  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.225  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.225  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.225  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.225  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:11.225  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 18:41:11.226  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:11.226  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:11.227  5570  5617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-04 18:41:11.228  4633  4693 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 18:41:11.228  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:41:11.229  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 18:41:11.229  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 18:41:11.236  4633  4693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 18:41:11.236  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:11.236  5570  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 18:41:11.236  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:11.236  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:11.236  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 18:41:11.236  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 18:41:11.236  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 18:41:11.236  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 18:41:11.236  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 18:41:11.238  4633  4696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 18:41:11.240  5570  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 18:41:11.240  5570  5617 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 18:41:11.240  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 18:41:11.240  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 18:41:11.240  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 18:41:11.240  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 18:41:11.240  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 18:41:11.243  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:11.244  4633  4693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 18:41:11.244  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:11.244  4633  4693 E BtGatt.ContextMap: Context not found for ID 5
,11-04 18:41:11.246  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 18:41:11.246  5570  5617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-04 18:41:11.246  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 18:41:11.246  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 18:41:11.249  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.250  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 18:41:11.250  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 18:41:11.250  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 18:41:11.250  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 18:41:11.252  4633  4693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 18:41:11.252  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:11.252  4633  4696 D BtGatt.ScanManager: stopping BLe Batch
,11-04 18:41:11.254  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:11.255  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 18:41:11.255  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 18:41:11.255  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 18:41:11.255  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-04 18:41:11.255  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.256  5570  5617 D BluetoothAdapter: STATE_ON
11-04 18:41:11.258  4633  4855 D BtGatt.GattService: registerClient() - UUID=70251fe1-5eef-4c26-bdb8-e9c427e08776
11-04 18:41:11.259  4633  4693 D BtGatt.GattService: onClientRegistered() - UUID=70251fe1-5eef-4c26-bdb8-e9c427e08776, clientIf=5
,11-04 18:41:11.259  4633  4693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 18:41:11.259  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:11.259  5570  5580 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 18:41:11.259  4633  4696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 18:41:11.260  4633  4645 D BtGatt.GattService: start scan with filters
,11-04 18:41:11.262  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 18:41:11.262  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.262  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 18:41:11.262  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.262  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 18:41:11.262  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 18:41:11.263  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 18:41:11.263  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 18:41:11.263  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 18:41:11.263  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.263  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.263  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 18:41:11.264  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 18:41:11.264  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:11.266  4633  4693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 18:41:11.266  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:11.266  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.267  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 18:41:11.267  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.267  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:11.267  5570  5617 I io.jxcore.node.ConnectionHelper: start: OK
11-04 18:41:11.267  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 18:41:11.268  4633  4696 D BtGatt.ScanManager: handling starting scan
,11-04 18:41:11.269  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.269  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.269  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.270  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:41:11.270  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 18:41:11.274  4633  4693 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 18:41:11.274  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:41:11.275  4633  4696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 18:41:11.280  4633  4693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 18:41:11.280  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:11.280  4633  4696 D BtGatt.ScanManager: Starting BLE batch scan
11-04 18:41:11.280  4633  4696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 18:41:11.289  4633  4693 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 18:41:11.289  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:41:11.293  4633  4693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 18:41:11.293  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:41:11.771  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-04 18:41:11.771  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-04 18:41:11.772  5570  5570 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 18:41:16.267  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:16.268  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-04 18:41:16.268  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-04 18:41:16.268  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 18:41:16.268  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 18:41:16.268  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:16.269  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 18:41:16.269  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 18:41:16.269  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 18:41:16.269  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 18:41:16.269  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.270  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.270  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.270  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 18:41:16.270  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.273  5570  5617 D BluetoothAdapter: STATE_ON
11-04 18:41:16.273  4633  4645 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 18:41:16.274  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 18:41:16.276  5570  5617 D BluetoothAdapter: STATE_ON
,11-04 18:41:16.277  4633  4646 D BtGatt.GattService: stopScan() - queue size =1
11-04 18:41:16.277  4633  4696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 18:41:16.279  4633  4843 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 18:41:16.280  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 18:41:16.280  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.280  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 18:41:16.280  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.280  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.281  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.281  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.281  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 18:41:16.281  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.282  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.282  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.282  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 18:41:16.282  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 18:41:16.284  4633  4633 D BtGatt.ScanManager: awakened up at time 108332
11-04 18:41:16.284  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 18:41:16.284  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.287  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.287  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:41:16.287  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.287  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:16.287  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:41:16.287  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:41:16.287  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 18:41:16.287   925  3564 I ActivityManager: Killing 5230:com.android.settings/1000 (adj 15): empty #17
11-04 18:41:16.288  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 18:41:16.288  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 18:41:16.288  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-04 18:41:16.288  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:41:16.288  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 18:41:16.288  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 18:41:16.288  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 18:41:16.290  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:41:16.290  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:41:16.290  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 18:41:16.290  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:41:16.290  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 18:41:16.318  4633  4693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-04 18:41:16.318  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:41:16.318  4633  4693 D BtGatt.GattService: current time is 108367195636
11-04 18:41:16.318  4633  4693 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -85, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -89, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 18:41:16.319  4633  4693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-04 18:41:16.319  4633  4693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 18:41:16.319  4633  4693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 18:41:16.319  4633  4693 E BtGatt.ContextMap: Context not found for ID 5
,11-04 18:41:16.326  4633  4693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 18:41:16.326  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:41:16.326  4633  4696 D BtGatt.ScanManager: stopping BLe Batch
,11-04 18:41:16.331  4633  4693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 18:41:16.331  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:41:16.332  4633  4696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 18:41:16.336  4633  4693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 18:41:16.336  4633  4693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:41:16.791  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 18:41:16.792  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:16.792  5570  5570 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 18:41:16.856   925  5344 D NetlinkSocketObserver: NeighborEvent{elapsedMs=108904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-04 18:41:21.288  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 18:41:21.289  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:21.289  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:21.289  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 18:41:21.289  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 18:41:21.290  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 18:41:21.290  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 18:41:21.290  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:21.290  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.290  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:21.290  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:21.290  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 18:41:21.293  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.299  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.300  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.301  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.301  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 18:41:21.301  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 18:41:21.301  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.301  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.303  5570  5617 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-04 18:41:21.306  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 18:41:21.307  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 18:41:21.307  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 18:41:21.307  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:21.307  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 18:41:21.308  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:21.308  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:41:21.308  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:21.308  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:21.308  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.312  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.313  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.313  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.313  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:21.313  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 18:41:21.313  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.314  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:21.317  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-04 18:41:21.317  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:21.317  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:21.317  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:21.318  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:21.318  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 18:41:21.319  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:21.319  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.319  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.319  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:21.320  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.323  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.324  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.324  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.324  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:21.324  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:21.324  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.324  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:21.326  5570  5617 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-04 18:41:21.326  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:21.326  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:21.327  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:21.327  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:21.327  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:21.327  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
,11-04 18:41:21.327  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.328  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.328  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:21.328  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.330  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.330  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.330  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.330  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:21.330  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:21.330  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.331  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:21.331  5570  5617 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-04 18:41:21.332  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:21.332  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:21.332  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:21.332  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 18:41:21.332  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:21.332  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:21.332  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.332  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.332  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:21.332  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.334  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.334  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.334  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.334  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:21.334  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:21.334  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.335  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.335  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-04 18:41:21.336  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 18:41:21.336  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 18:41:21.336  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 18:41:21.336  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 18:41:21.336  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 18:41:21.336  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-04 18:41:21.336  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 18:41:21.336  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 18:41:21.336  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:21.336  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:21.336  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:21.337  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:21.337  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:21.337  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:21.337  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:41:21.337  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.337  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:21.337  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.340  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.341  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.341  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.341  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:21.341  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 18:41:21.342  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.342  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.343  5570  5617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 18:41:21.344  5570  5617 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 18:41:21.345  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-04 18:41:21.352  5570  5617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-04 18:41:21.352  5570  5617 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-04 18:41:21.352  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-04 18:41:21.352  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 18:41:21.352  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 18:41:21.352  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 18:41:21.352  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 18:41:21.352  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 18:41:21.353  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 18:41:21.353  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 18:41:21.353  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 18:41:21.353  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 18:41:21.353  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 18:41:21.353  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 18:41:21.353  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 18:41:21.354  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 18:41:21.354  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 18:41:21.354  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 18:41:21.354  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 18:41:21.354  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-04 18:41:21.354  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-04 18:41:21.354  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 18:41:21.355  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 18:41:21.355  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 18:41:21.355  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-04 18:41:21.355  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-04 18:41:21.355  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 18:41:21.355  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections:, Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 18:41:21.355  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 18:41:21.355  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 18:41:21.355  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-04 18:41:21.355  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 18:41:21.355  5570  5617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-04 18:41:21.355  5570  5617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 18:41:21.356  5570  5617 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-04 18:41:21.356  5570  5617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 18:41:21.356  5570  5617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 18:41:21.356  5570  5617 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-04 18:41:21.356  5570  5617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 18:41:21.356  5570  5617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 18:41:21.356  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-04 18:41:21.363  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-04 18:41:21.364  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-04 18:41:21.364  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-04 18:41:21.364  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-04 18:41:21.364  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-04 18:41:21.364  5570  5617 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-04 18:41:21.365  5570  5617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-04 18:41:21.365  5570  5617 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-04 18:41:21.365  5570  5622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-04 18:41:21.365  5570  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-04 18:41:21.365  5570  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-04 18:41:21.365  5570  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-04 18:41:21.366  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:21.366  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:21.366  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:21.366  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:21.366  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:21.366  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-04 18:41:21.367  5570  5622 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-04 18:41:21.367  5570  5622 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 18:41:21.367  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:21.367  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.367  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.367  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:21.368  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.368  5570  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-04 18:41:21.368  5570  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-04 18:41:21.368  5570  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-04 18:41:21.368  5570  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
11-04 18:41:21.369  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.369  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.367  4854  4854 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31548]" dev="sockfs" ino=31548 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 18:41:21.367  4854  4854 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31548]" dev="sockfs" ino=31548 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 18:41:21.369  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.369  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 18:41:21.369  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:21.369  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.369  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:21.370  5570  5617 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-04 18:41:21.370  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:21.371  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:21.371  5570  5622 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-04 18:41:21.371  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:21.371  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:21.371  5570  5622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
,11-04 18:41:21.371  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:21.371  5570  5622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-04 18:41:21.371  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:21.371  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.371  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:21.372  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:21.372  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.373  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.373  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.373  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.373  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 18:41:21.373  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:21.373  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.373  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.375  5570  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-04 18:41:21.375  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:21.376  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:21.376  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 18:41:21.376  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:21.376  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:21.376  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:21.376  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.376  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.376  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:21.376  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.377  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.377  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.377  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.378  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:21.378  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:21.378  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.378  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:21.378  5570  5617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-04 18:41:21.378  5570  5617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-04 18:41:21.379  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 18:41:21.379  5570  5617 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-04 18:41:21.379  5570  5617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-04 18:41:21.379  5570  5617 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-04 18:41:21.379  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 18:41:21.379  5570  5617 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-04 18:41:21.379  5570  5617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 18:41:21.379  5570  5617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 18:41:21.379  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 18:41:21.379  5570  5617 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-04 18:41:21.379  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 18:41:21.379  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:21.379  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:21.379  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:21.379  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:21.380  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:21.380  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.380  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.380  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:21.380  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.381  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:21.381  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.381  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:21.381  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:21.381  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:21.381  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.381  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.382  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:21.382  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:21.382  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:21.382  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:21.382  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:21.382  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 18:41:22.105   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-04 18:41:22.106   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-04 18:41:25.446   925  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-04 18:41:26.383  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:41:26.383  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:26.383  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:26.383  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:26.384  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:26.384  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 18:41:26.384  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:26.384  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 18:41:26.385  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:26.386  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:26.386  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
,11-04 18:41:26.386  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:26.386  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:26.386  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:26.387  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:26.391  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:26.391  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.392  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:26.392  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:26.392  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:26.392  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:41:26.393  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:26.398  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-04 18:41:26.398  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 18:41:26.399  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 18:41:26.404  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 18:41:26.406  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-04 18:41:26.406  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 18:41:26.407  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 18:41:26.407  5570  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 18:41:26.407  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-04 18:41:26.407  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 18:41:26.407  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-04 18:41:26.408  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:26.408  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-04 18:41:26.408  5570  5624 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 18:41:26.408  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 18:41:26.409  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-04 18:41:26.409  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 18:41:26.410  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-04 18:41:26.410  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-04 18:41:26.411  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 18:41:26.411  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
,11-04 18:41:26.411  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:26.411  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 18:41:26.411  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 18:41:26.411  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 18:41:26.411  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.411  4843  4843 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32376]" dev="sockfs" ino=32376 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 18:41:26.411  4843  4843 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32376]" dev="sockfs" ino=32376 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 18:41:26.413  5570  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 18:41:26.413  5570  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-04 18:41:26.413  5570  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 18:41:26.414  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.415  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:41:26.415  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:26.415  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.415  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:26.416  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:41:26.416  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:26.416  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:41:26.416  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 18:41:26.416  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 18:41:26.416  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:26.416  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:26.416  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:26.416  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:41:26.416  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:26.416  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:26.416  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:41:26.416  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:26.416  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:26.417  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.419  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:26.419  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.419  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.419  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:26.419  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:26.419  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:26.420  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:26.422  5570  5617 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-04 18:41:26.422  5570  5617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 18:41:26.422  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 18:41:26.422  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 18:41:26.422  5570  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 18:41:26.423  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:26.423  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 18:41:26.423  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:26.423  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:26.423  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:26.423  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:26.424  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:26.424  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:26.425  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:26.426  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.429  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:26.430  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.430  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.430  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:26.430  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:26.430  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:26.430  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:26.436  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 18:41:26.436  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:41:26.436  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:26.437  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:26.437  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:41:26.437  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:26.437  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:26.437  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:26.437  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:26.437  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.439  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:26.439  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.439  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.439  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:41:26.439  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:41:26.439  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:41:26.439  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:26.441  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:41:26.441  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 18:41:26.441  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:41:26.441  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:41:26.441  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 18:41:26.441  5570  5617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e76f1 not in the list
11-04 18:41:26.441  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:26.441  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
,11-04 18:41:26.442  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:26.442  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.443  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:41:26.443  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.443  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:41:26.444  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 18:41:26.444  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 18:41:26.444  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:26.444  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c42d6 not in the list
11-04 18:41:26.446  5570  5617 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-04 18:41:26.446  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-04 18:41:26.446  5570  5617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-04 18:41:26.447  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 18:41:26.447  5570  5617 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-04 18:41:26.447  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-04 18:41:26.449  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-04 18:41:26.449  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-04 18:41:26.450  5570  5617 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-04 18:41:26.450  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 18:41:26.450  5570  5617 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-04 18:41:26.450  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 18:41:26.450  5570  5617 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-04 18:41:26.450  5570  5617 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-04 18:41:26.451  5570  5617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-04 18:41:26.451  5570  5617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-04 18:41:26.452  5570  5617 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-04 18:41:26.452  5570  5617 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-04 18:41:26.452  5570  5617 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-04 18:41:26.452  5570  5617 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-04 18:41:26.453  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 18:41:26.453  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eadc647 added. We now have 3 listener(s)
11-04 18:41:26.453  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 18:41:26.456  5570  5617 D BluetoothAdapter: enable(): BT is already enabled..!
,11-04 18:41:26.456   925  3787 D WifiService: setWifiEnabled: true pid=5570, uid=10077
11-04 18:41:26.456   925  3787 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 18:41:26.497  4633  4825 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-04 18:41:26.497  4633  4841 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-04 18:41:26.917  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 18:41:27.107   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:28.108   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:28.474   925  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-04 18:41:29.109   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:30.075   925  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 18:41:30.110   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:31.111   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:31.462  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 18:41:31.463  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4513e74 added. We now have 4 listener(s)
11-04 18:41:31.463  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 18:41:31.475  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:41:31.475  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4513e74 removed from the list
,11-04 18:41:31.475  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 18:41:31.478  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 18:41:31.479  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9571f9d added. We now have 4 listener(s)
11-04 18:41:31.479  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 18:41:31.482  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:41:31.482  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9571f9d removed from the list
11-04 18:41:31.483  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 18:41:31.485  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 18:41:31.485  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6287c12 added. We now have 4 listener(s)
11-04 18:41:31.485  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 18:41:31.491   925  3118 D WifiService: setWifiEnabled: false pid=5570, uid=10077
11-04 18:41:31.491   925  3118 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 18:41:31.501   925  2941 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-04 18:41:31.501   925  2941 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 18:41:31.501   925  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 18:41:31.502   925  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 18:41:31.507  4633  4689 D BluetoothAdapterState: Current state: ON, message: 23
11-04 18:41:31.507  4633  4689 D BluetoothAdapterProperties: Setting state to 13
11-04 18:41:31.507  4633  4689 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 18:41:31.508  4633  4689 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 18:41:31.510  4633  4689 I BluetoothAdapterState: Entering PendingCommandState
,11-04 18:41:31.512  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 18:41:31.512  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 18:41:31.515  4633  4693 D BluetoothAdapterProperties: Scan Mode:20
11-04 18:41:31.516  4633  4689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-04 18:41:31.519  4633  4633 D HeadsetService: Received stop request...Stopping profile...
,11-04 18:41:31.526   506   919 D CommandListener: Clearing all IP addresses on wlan0
11-04 18:41:31.526   925  5345 D DhcpClient: Clearing IP address
11-04 18:41:31.526  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:31.526  5570  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 18:41:31.526  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:31.526  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:31.526  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 18:41:31.526  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 18:41:31.526  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 18:41:31.526  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 18:41:31.526  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 18:41:31.527  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:31.527  5570  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 18:41:31.527  5570  5617 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 18:41:31.532  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 18:41:31.533   506   919 D CommandListener: Setting iface cfg
11-04 18:41:31.535  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 18:41:31.539  3550  5410 V NativeCrypto: Read error: ssl=0x7f7051b000: I/O error during system call, Connection timed out
11-04 18:41:31.541   925   938 I ActivityManager: Start proc 5628:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-04 18:41:31.541  3550  5410 V NativeCrypto: SSL shutdown failed: ssl=0x7f7051b000: I/O error during system call, Broken pipe
11-04 18:41:31.542   925  5346 D DhcpClient: Receive thread stopped
11-04 18:41:31.542   925   925 D BluetoothHeadset: Proxy object disconnected
11-04 18:41:31.543  3086  3846 D BluetoothHeadset: Proxy object disconnected
11-04 18:41:31.543   925   925 D BluetoothHeadset: Proxy object disconnected
,11-04 18:41:31.543   925   925 D BluetoothHeadset: Proxy object disconnected
,11-04 18:41:31.544  3774  3978 D BluetoothHeadset: Proxy object disconnected
,11-04 18:41:31.544  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:31.544  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:31.545  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:31.545  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:31.545  4633  4633 D BluetoothMapService: onReceive
11-04 18:41:31.545  4633  4633 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-04 18:41:31.545  4633  4633 D BluetoothMapService: STATE_TURNING_OFF
11-04 18:41:31.546   925  3385 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-04 18:41:31.547   925  5343 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-04 18:41:31.547  4633  4633 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 18:41:31.547  4633  4633 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 18:41:31.548  4633  4693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 18:41:31.548  4633  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 18:41:31.548  4633  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 18:41:31.548  4633  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 18:41:31.548  4633  4633 D A2dpService: Received stop request...Stopping profile...
,11-04 18:41:31.548  4633  4693 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 18:41:31.548  4633  4849 D A2dpStateMachine: Exit Disconnected: -1
11-04 18:41:31.550   925   925 D BluetoothA2dp: Proxy object disconnected
11-04 18:41:31.550   925  5343 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-04 18:41:31.551  4633  4633 D HidService: Received stop request...Stopping profile...
11-04 18:41:31.551   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-04 18:41:31.551  4633  4633 D HidService: Stopping Bluetooth HidService
,11-04 18:41:31.551   925  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-04 18:41:31.552  4633  4633 D BluetoothMapService: MAP Service closeService in
11-04 18:41:31.552  4633  4633 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 18:41:31.552  4633  4633 D ObexServerSockets0: shutdown(block = true)
11-04 18:41:31.552  4633  4857 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-04 18:41:31.553  3086  3086 D HeadsetProfile: Bluetooth service disconnected
11-04 18:41:31.553   925  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-04 18:41:31.553  3086  3086 D BluetoothA2dp: Proxy object disconnected
11-04 18:41:31.553  4633  4633 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 18:41:31.553  4633  4633 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 18:41:31.553  4633  4858 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 18:41:31.553  3086  3086 D BluetoothInputDevice: Proxy object disconnected
,11-04 18:41:31.554  3086  3086 D HidProfile: Bluetooth service disconnected
11-04 18:41:31.554  4633  4841 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 18:41:31.555  4633  4633 I BtOppRfcommListener: stopping Accept Thread
11-04 18:41:31.556  4633  5262 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 18:41:31.556  4633  5262 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-04 18:41:31.559   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-04 18:41:31.560   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-04 18:41:31.564  4633  4633 D HealthService: Received stop request...Stopping profile...
11-04 18:41:31.565  4633  4633 D PanService: Received stop request...Stopping profile...
11-04 18:41:31.566  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:31.566  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:31.566  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:31.566  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:31.567   925   925 D RttService: SCAN_AVAILABLE : 1
11-04 18:41:31.567   538   538 E Parcel  : Reading a NULL string not supported here.
11-04 18:41:31.568  4633  4633 D BluetoothMapService: Received stop request...Stopping profile...
11-04 18:41:31.568  4633  4633 D BluetoothMapService: stop()
,11-04 18:41:31.568   925  2943 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-04 18:41:31.569  4633  4633 D BluetoothMapAppObserver: deinitObservers()
11-04 18:41:31.569  4633  4633 D BluetoothMapAppObserver: removeReceiver()
11-04 18:41:31.569   925  3051 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 18:41:31.570  3727  3852 W QCNEJ   : |CORE| network lost: 100
11-04 18:41:31.570  3086  3086 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 18:41:31.570  3086  3086 D PanProfile: Bluetooth service disconnected
,11-04 18:41:31.570  3727  3852 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-04 18:41:31.573  3086  3086 D BluetoothMap: Proxy object disconnected
11-04 18:41:31.573  3086  3086 D MapProfile: Bluetooth service disconnected
11-04 18:41:31.573  4633  4693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-04 18:41:31.573  4633  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 18:41:31.574  4633  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 18:41:31.574  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:31.574  4633  4633 V BluetoothAdapterState: isTurningOn()=false
,11-04 18:41:31.574  4633  4825 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 18:41:31.574  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:31.574  4633  4825 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 18:41:31.574  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:31.574  4633  4825 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 18:41:31.574  4633  4825 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 18:41:31.574  4633  4633 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 18:41:31.574  4633  4633 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 18:41:31.574  4633  4693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 18:41:31.575  4633  4633 D SapService: Received stop request...Stopping profile...
11-04 18:41:31.575  4633  4633 V SapService: stop()
11-04 18:41:31.578  4633  4633 V BluetoothAdapterState: isTurningOff()=true
,11-04 18:41:31.578  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:31.578  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:31.578  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:31.578  4633  4633 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 18:41:31.578  4633  4693 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 18:41:31.579  4633  4633 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 18:41:31.579  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:31.579  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:31.579  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:31.579  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:31.580  4633  4633 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 18:41:31.580  4633  4633 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 18:41:31.582  4633  4633 D BluetoothMapService: MAP Service closeService in
11-04 18:41:31.582  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:31.582  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:31.582  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:31.582  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:31.582  4633  4633 D BluetoothMapService: cleanup()
11-04 18:41:31.582  4633  4633 D BluetoothMapService: MAP Service closeService in
,11-04 18:41:31.583  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:31.583  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:31.583  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:31.583  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:31.583  4633  4689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 18:41:31.583  4633  4689 D BluetoothAdapterProperties: Setting state to 15
11-04 18:41:31.583  4633  4689 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 18:41:31.584  4633  4689 I BluetoothAdapterState: Entering BleOnState
11-04 18:41:31.584  3086  3099 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-04 18:41:31.589  3086  3097 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 18:41:31.591   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 18:41:31.591   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 18:41:31.591  3774  3800 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 18:41:31.591  3086  3846 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 18:41:31.592  3086  3099 D BluetoothMap: onBluetoothStateChange: up=false
,11-04 18:41:31.592   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 18:41:31.598  3086  3097 D BluetoothPan: onBluetoothStateChange on: false
,11-04 18:41:31.607   925  2941 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-04 18:41:31.608   925  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 18:41:31.609   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 18:41:31.609   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-04 18:41:31.609  3086  3099 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 18:41:31.611  4633  4689 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 18:41:31.611  4633  4689 D BluetoothAdapterProperties: Setting state to 16
11-04 18:41:31.611  4633  4689 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-04 18:41:31.611  4633  4689 D BluetoothAdapterProperties: onBleDisable
11-04 18:41:31.611  4633  4689 I BluetoothAdapterState: Entering PendingCommandState
11-04 18:41:31.612  4633  4693 D BluetoothAdapterProperties: Scan Mode:20
11-04 18:41:31.613  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:31.613  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 18:41:31.613  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:31.613  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:31.613  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 18:41:31.613  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 18:41:31.613  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 18:41:31.613  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 18:41:31.613  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 18:41:31.613  5628  5628 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-04 18:41:31.613  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:31.614  5570  5570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 18:41:31.614  4633  4690 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-04 18:41:31.615   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 18:41:31.615   506   919 D CommandListener: Clearing all IP addresses on wlan0
11-04 18:41:31.616  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:31.616  4633  4825 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 18:41:31.616  4633  4825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 18:41:31.617   925  2943 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-04 18:41:31.617   925  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 18:41:31.617   925  2941 D DhcpClient: doQuit
11-04 18:41:31.617   925  2941 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 18:41:31.618   925  5345 D DhcpClient: onQuitting
,11-04 18:41:31.619  3415  3415 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-04 18:41:31.622  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 18:41:31.623   925   942 D Tethering: MasterInitialState.processMessage what=3
,11-04 18:41:31.629  5248  5248 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d87446 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-04 18:41:31.630  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:31.630  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 18:41:31.630  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:31.630  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:31.630  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 18:41:31.630  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 18:41:31.630  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 18:41:31.630  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 18:41:31.630  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 18:41:31.631  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:31.632  5570  5570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 18:41:31.634  3935  3935 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-04 18:41:31.641  3415  3415 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 18:41:31.645  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 18:41:31.645  3415  3415 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-04 18:41:31.651   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@80bc657:true
11-04 18:41:31.652  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 18:41:31.671  5628  5628 D LocalBluetoothProfileManager: Adding local MAP profile
,11-04 18:41:31.671   506   919 E Netd    : netlink response contains error (No such file or directory)
,11-04 18:41:31.672   925  2943 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 18:41:31.673   506   919 D TetherController: Setting IP forward enable = 0
11-04 18:41:31.673  5628  5628 D BluetoothMap: Create BluetoothMap proxy object
,11-04 18:41:31.681  5628  5628 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-04 18:41:31.686  5628  5628 D DockEventReceiver: finishStartingService: stopping service
,11-04 18:41:31.688  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 18:41:31.690  3415  3415 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 18:41:31.692  5628  5628 D DockEventReceiver: finishStartingService: stopping service
11-04 18:41:31.693  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 18:41:31.699   925  3787 I ActivityManager: Killing 5370:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-04 18:41:31.700  3415  3415 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 18:41:31.710   506   919 D TetherController: Setting IP forward enable = 0
,11-04 18:41:31.723  3953  3953 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 18:41:31.727  3953  3953 D SystemUpdateService: onCreate
11-04 18:41:31.729  3953  3953 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 18:41:31.734  3953  5664 I SystemUpdateService: active receiver: enabled
,11-04 18:41:31.736  3953  3953 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 18:41:31.740  3953  4204 I iu.UploadsManager: num queued entries: 0
,11-04 18:41:31.740  3953  4204 I iu.UploadsManager: num updated entries: 0
11-04 18:41:31.740  3953  4204 I iu.SyncManager: NEXT; no task
11-04 18:41:31.743  3953  3953 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 18:41:31.745  3953  3953 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 18:41:31.745  3953  5664 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-04 18:41:31.747  3953  5664 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-04 18:41:31.747  3953  5664 I SystemUpdateService: now status is 0 (complete)
11-04 18:41:31.747  3953  5664 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 18:41:31.747  3953  5664 I SystemUpdateService: file has been verified
11-04 18:41:31.748  3953  5664 I SystemUpdateService: OTA package size = 21989297
11-04 18:41:31.753  3953  5664 I SystemUpdateService: showing system update notification
11-04 18:41:31.756   925  3791 I ActivityManager: Start proc 5666:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-04 18:41:31.767   925   925 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-04 18:41:31.769  3953  3953 D SystemUpdateService: onDestroy
,11-04 18:41:31.789  5666  5666 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-04 18:41:31.792  5666  5666 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 18:41:31.798  5666  5666 D SprintDMHelper: simOperator: 
11-04 18:41:31.799  5666  5666 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 18:41:31.804   925  2941 D wifi    : In wifi stop Hal
,11-04 18:41:31.804   925  2941 D wifi    : halHandle = 0x7f59ee1400, mVM = 0x7f7658d140, mCls = 0x100a02
11-04 18:41:31.804   925  3414 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 18:41:31.804   925  3414 D WifiHAL : Got a signal to exit!!!
11-04 18:41:31.804   925  3414 I WifiHAL : Exit wifi_event_loop
11-04 18:41:31.804   925  2941 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-04 18:41:31.804   925  2941 E WifiHAL : Event processing terminated
,11-04 18:41:31.805   925  2941 D wifi    : In wifi cleaned up handler
11-04 18:41:31.805   925  2941 I WifiHAL : Internal cleanup completed
11-04 18:41:31.805  3712  4180 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 18:41:31.806  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 18:41:31.811  4479  4479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 18:41:31.819   925  3414 D wifi    : set interface wlan0 flags (DOWN)
,11-04 18:41:31.820   925  2941 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 18:41:31.825   925  3564 I ActivityManager: Start proc 5679:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-04 18:41:31.826   925  3564 I ActivityManager: Killing 5248:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-04 18:41:31.853  4633  4693 I bt_hci  : shut_down
,11-04 18:41:31.857  4633  4697 D bt_hwcfg: hw_epilog_process
,11-04 18:41:31.857  4633  4697 I bt_vendor: low_power_mode_cb
,11-04 18:41:31.860  4633  4697 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-04 18:41:31.860  4633  4697 I bt_vendor: epilog_cb
11-04 18:41:31.860  4633  4697 I bt_hci  : epilog_finished_callback
,11-04 18:41:31.862  4633  4693 I bt_hci_h4: hal_close
,11-04 18:41:31.862  4633  4693 I bt_userial_vendor: device fd = 54 close
,11-04 18:41:31.863  5679  5679 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-04 18:41:31.869   925  3564 I ActivityManager: Killing 3861:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-04 18:41:31.972  4633  4690 D bt_stack_manager: event_shut_down_stack finished.
,11-04 18:41:31.972  4633  4689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-04 18:41:31.975  4633  4689 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-04 18:41:31.975  4633  4633 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 18:41:31.976  4633  4633 D BtGatt.GattService: Received stop request...Stopping profile...
,11-04 18:41:31.976  4633  4633 D BtGatt.GattService: stop()
11-04 18:41:31.976  4633  4633 D BtGatt.AdvertiseManager: advertise clients cleared
11-04 18:41:31.978  4633  4633 V BluetoothAdapterState: isTurningOff()=false
11-04 18:41:31.978  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:31.978  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:31.978  4633  4633 V BluetoothAdapterState: isBleTurningOff()=true
11-04 18:41:31.979  4633  4689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-04 18:41:31.979  4633  4689 D BluetoothAdapterProperties: Setting state to 10
,11-04 18:41:31.979  4633  4689 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 18:41:31.981  4633  4689 I BluetoothAdapterState: Entering OffState
,11-04 18:41:31.982   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-04 18:41:31.989  4633  4633 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 18:41:31.990  4633  4633 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 18:41:31.990  4633  4633 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-04 18:41:31.992  4633  4690 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 18:41:31.997  4633  4633 I art     : System.exit called, status: 0
,11-04 18:41:31.997  4633  4633 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 18:41:32.022   925   942 D Tethering: InitialState.processMessage what=4
,11-04 18:41:32.024   925  3564 I ActivityManager: Process com.android.bluetooth (pid 4633) has died
,11-04 18:41:32.025   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 18:41:32.112   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-04 18:41:36.530   925  3385 D WifiService: setWifiEnabled: true pid=5570, uid=10077
11-04 18:41:36.530   925  3385 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 18:41:36.540   506   919 D SoftapController: Softap fwReload - Ok
,11-04 18:41:36.546   506   919 D CommandListener: Setting iface cfg
,11-04 18:41:36.547   506   919 D CommandListener: Trying to bring down wlan0
,11-04 18:41:36.550   506   919 D CommandListener: Clearing all IP addresses on wlan0
,11-04 18:41:36.557   925  2941 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 18:41:37.113   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:37.152   925  2941 D wifi    : set interface wlan0 flags (UP)
,11-04 18:41:37.153   925  2941 I WifiHAL : Initializing wifi
11-04 18:41:37.153   925  2941 I WifiHAL : Creating socket
,11-04 18:41:37.162   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 18:41:37.162   925  2941 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-04 18:41:37.162   925  2941 D wifi    : Did set static halHandle = 0x7f59ee1400
,11-04 18:41:37.162   925  2941 D wifi    : halHandle = 0x7f59ee1400, mVM = 0x7f7658d140, mCls = 0x101952
,11-04 18:41:37.162   925  2941 D wifi    : array field set
,11-04 18:41:37.163   925  2941 I WifiNative-HAL: interface[0] = wlan0
11-04 18:41:37.166   925  5695 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546969621504
11-04 18:41:37.166   925  5695 D wifi    : waitForHalEvents called, vm = 0x7f7658d140, obj = 0x101952, env = 0x7f5ec8c300
,11-04 18:41:37.227  5696  5696 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 18:41:37.268   925  2941 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 18:41:37.272  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 18:41:37.290  5696  5696 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 18:41:37.313  5696  5696 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 18:41:37.313  5696  5696 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 18:41:37.322   925  2941 D WifiConfigStore: Loading config and enabling all networks 
,11-04 18:41:37.325  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:37.325  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 18:41:37.325  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:37.325  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:37.325  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 18:41:37.325  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 18:41:37.325  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 18:41:37.325  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 18:41:37.325  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 18:41:37.325  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 18:41:37.325  5570  5570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 18:41:37.335   925  2941 D WifiConfigStore: loaded 0 passpoint configs
,11-04 18:41:37.335   925  2941 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-04 18:41:37.336   925  2941 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-04 18:41:37.336   925  2941 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-04 18:41:37.336   925  2941 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-04 18:41:37.336   925  2941 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-04 18:41:37.337   925  2941 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 18:41:37.337   925  2941 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 18:41:37.337   925  2941 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-04 18:41:37.337   925  2941 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-04 18:41:37.337   925  2941 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 18:41:37.337   925  2941 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-04 18:41:37.337   925  2941 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 18:41:37.339   925  2941 D WifiNative-HAL: Setting external_sim to 1
11-04 18:41:37.339   925  2941 D wifi    : setting dfs flag to true, 0x7f5ece19a0
,11-04 18:41:37.340   925  2941 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 18:41:37.340   925  2941 D wifi    : setting scan oui 0x7f5ece19a0
11-04 18:41:37.340   925  2941 D WifiHAL : Sending mac address OUI
11-04 18:41:37.340  4479  4479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 18:41:37.342   925  2941 E native  : do suspend false
,11-04 18:41:37.348   925  2941 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-04 18:41:37.348   925   925 D RttService: SCAN_AVAILABLE : 3
11-04 18:41:37.349   925  3051 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-04 18:41:37.349   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-04 18:41:37.351   506   919 D CommandListener: Setting iface cfg
,11-04 18:41:37.353   925  2933 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,11-04 18:41:37.353   925  2933 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 18:41:37.363   925  2933 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 18:41:37.364   925  2933 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 18:41:37.369   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129418 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-04 18:41:38.118   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:39.119   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:40.120   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:40.417  5696  5696 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 18:41:40.423  5696  5696 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 18:41:40.427  5696  5696 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 18:41:40.478   925  2941 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 18:41:40.479   925  2941 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-04 18:41:40.479   925  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 18:41:40.490   925  2941 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 18:41:40.522   925  2941 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 18:41:40.528  5696  5696 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 18:41:40.946  5696  5696 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 18:41:40.986  5696  5696 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 18:41:40.987  5696  5696 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 18:41:40.997   925  2941 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 18:41:40.997   925  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 18:41:40.997   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 18:41:41.015   925  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 18:41:41.027   506   919 D CommandListener: Setting iface cfg
,11-04 18:41:41.034   925  2941 D WifiStateMachine: Start Dhcp Watchdog 2
,11-04 18:41:41.040   925  5704 D DhcpClient: Receive thread started
,11-04 18:41:41.047   925  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 18:41:41.047   925  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-04 18:41:41.048   925  2943 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-04 18:41:41.121   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:41.128   925  2941 E native  : do suspend false
,11-04 18:41:41.139   925  5703 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 18:41:41.158   925  5704 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172708, domain null
,11-04 18:41:41.159   925  5703 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172708 seconds
,11-04 18:41:41.160   925  5703 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 18:41:41.186   925  5704 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 18:41:41.187   925  5703 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 18:41:41.190   506   919 D CommandListener: Setting iface cfg
,11-04 18:41:41.195   925  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 18:41:41.200   925  5703 D DhcpClient: Scheduling renewal in 86399s
,11-04 18:41:41.218   925  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 18:41:41.220   925  2941 D WifiConfigStore: No blacklist allowed without epno enabled
11-04 18:41:41.221   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-04 18:41:41.224   925  2943 D ConnectivityService: Adding iface wlan0 to network 101
,11-04 18:41:41.234   925  2941 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 18:41:41.271   925  2943 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-04 18:41:41.272   925  2943 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-04 18:41:41.274   925  2943 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
11-04 18:41:41.275   925  2943 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-04 18:41:41.277   925  2943 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-04 18:41:41.283   925  2943 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 18:41:41.288   925  2943 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-04 18:41:41.288   925  2943 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-04 18:41:41.288   925  2943 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-04 18:41:41.288   925  2943 D ConnectivityService:    accepting network in place of null
,11-04 18:41:41.288   925  2941 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-04 18:41:41.288   925  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 18:41:41.289   925  2943 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 18:41:41.302   925  5702 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133350, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 18:41:41.311   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 18:41:41.331   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 18:41:41.336   925  2943 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-04 18:41:41.336   925  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 18:41:41.336  3727  3852 W QCNEJ   : |CORE| network available: 101
,11-04 18:41:41.337   925  2943 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-04 18:41:41.339   925   942 D Tethering: MasterInitialState.processMessage what=3
11-04 18:41:41.343  3727  3852 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 18:41:41.343  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 18:41:41.344  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 18:41:41.344  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:41.344  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:41.344  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 18:41:41.344  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 18:41:41.344  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 18:41:41.344  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 18:41:41.344  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 18:41:41.344  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:41.344  5570  5570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 18:41:41.344  3727  3852 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 18:41:41.344  3727  3852 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-04 18:41:41.350  3935  3935 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-04 18:41:41.353  3953  3953 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-04 18:41:41.356  3953  3953 D SystemUpdateService: onCreate
,11-04 18:41:41.361  3953  3953 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 18:41:41.371  3953  3953 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 18:41:41.376   925  5701 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 18:41:41.380  3953  4204 I iu.UploadsManager: num queued entries: 0
,11-04 18:41:41.380  3953  4204 I iu.UploadsManager: num updated entries: 0
,11-04 18:41:41.381  3953  4204 I iu.SyncManager: NEXT; no task
,11-04 18:41:41.383  3953  5713 I SystemUpdateService: active receiver: enabled
,11-04 18:41:41.385  3953  3953 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 18:41:41.386  3953  3953 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 18:41:41.388  5666  5666 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 18:41:41.391  5666  5666 D SprintDMHelper: simOperator: 
,11-04 18:41:41.391  5666  5666 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 18:41:41.417  3953  5713 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 18:41:41.425   925  5701 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 17:41:41 GMT], X-Android-Received-Millis=[1478281301424], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478281301402]}
,11-04 18:41:41.425   925  2943 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 18:41:41.426   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-04 18:41:41.426   925  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-04 18:41:41.426  3953  5713 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-04 18:41:41.426  3953  5713 I SystemUpdateService: now status is 0 (complete)
,11-04 18:41:41.426  3953  5713 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-04 18:41:41.426  3953  5713 I SystemUpdateService: file has been verified
,11-04 18:41:41.427   925  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-04 18:41:41.427  3953  5713 I SystemUpdateService: OTA package size = 21989297
,11-04 18:41:41.432  3953  5713 I SystemUpdateService: showing system update notification
,11-04 18:41:41.442   925   925 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 18:41:41.443  3953  3953 D SystemUpdateService: onDestroy
,11-04 18:41:41.537   925  3831 D WifiService: setWifiEnabled: false pid=5570, uid=10077
11-04 18:41:41.538   925  3831 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 18:41:41.539   925  2941 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-04 18:41:41.539   925  2941 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 18:41:41.540   925  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 18:41:41.540   925  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 18:41:41.549   925  5703 D DhcpClient: Clearing IP address
,11-04 18:41:41.549   506   919 D CommandListener: Clearing all IP addresses on wlan0
,11-04 18:41:41.552   506   919 D CommandListener: Setting iface cfg
,11-04 18:41:41.560  3550  5720 V NativeCrypto: Read error: ssl=0x7f7051b000: I/O error during system call, Connection timed out
,11-04 18:41:41.560  3550  5720 V NativeCrypto: SSL shutdown failed: ssl=0x7f7051b000: I/O error during system call, Broken pipe
,11-04 18:41:41.562   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-04 18:41:41.562   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-04 18:41:41.565   538   538 E Parcel  : Reading a NULL string not supported here.
,11-04 18:41:41.566   925  5704 D DhcpClient: Receive thread stopped
11-04 18:41:41.567   925   925 D RttService: SCAN_AVAILABLE : 1
11-04 18:41:41.568   925  3051 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-04 18:41:41.571   925  2943 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-04 18:41:41.572   925  2941 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-04 18:41:41.574  3727  3852 W QCNEJ   : |CORE| network lost: 101
11-04 18:41:41.575  3727  3852 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-04 18:41:41.576   925  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 18:41:41.594   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 18:41:41.613   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 18:41:41.614   925  2943 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-04 18:41:41.614   506   919 D CommandListener: Clearing all IP addresses on wlan0
11-04 18:41:41.614   925  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 18:41:41.618   925   942 D Tethering: MasterInitialState.processMessage what=3
,11-04 18:41:41.618   925  2941 D DhcpClient: doQuit
11-04 18:41:41.618   925  2941 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 18:41:41.618   925  5703 D DhcpClient: onQuitting
11-04 18:41:41.619  5696  5696 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-04 18:41:41.621  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 18:41:41.621  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 18:41:41.621  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:41.621  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:41.621  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 18:41:41.621  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 18:41:41.621  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 18:41:41.621  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 18:41:41.621  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 18:41:41.621  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:41.621  5570  5570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 18:41:41.623  3935  3935 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-04 18:41:41.624  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:41.626  3953  3953 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 18:41:41.629  3953  3953 D SystemUpdateService: onCreate
,11-04 18:41:41.632  3953  3953 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-04 18:41:41.632  5696  5696 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 18:41:41.636  3953  5729 I SystemUpdateService: active receiver: enabled
,11-04 18:41:41.639  5696  5696 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-04 18:41:41.642  3953  3953 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 18:41:41.647  3953  4204 I iu.UploadsManager: num queued entries: 0
,11-04 18:41:41.647  3953  4204 I iu.UploadsManager: num updated entries: 0
,11-04 18:41:41.650  3953  3953 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 18:41:41.652  3953  3953 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 18:41:41.654  5666  5666 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 18:41:41.659  5666  5666 D SprintDMHelper: simOperator: 
,11-04 18:41:41.659  5666  5666 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 18:41:41.665   506   919 E Netd    : netlink response contains error (No such file or directory)
,11-04 18:41:41.666   925  2943 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-04 18:41:41.667  3953  5729 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 18:41:41.675  3953  4204 I iu.SyncManager: NEXT; no task
,11-04 18:41:41.676  3953  5729 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-04 18:41:41.676  3953  5729 I SystemUpdateService: now status is 0 (complete)
11-04 18:41:41.676  3953  5729 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 18:41:41.676  3953  5729 I SystemUpdateService: file has been verified
,11-04 18:41:41.676  3953  5729 I SystemUpdateService: OTA package size = 21989297
,11-04 18:41:41.681  5696  5696 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 18:41:41.691  3953  5729 I SystemUpdateService: showing system update notification
,11-04 18:41:41.696   925   925 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 18:41:41.698  3953  3953 D SystemUpdateService: onDestroy
,11-04 18:41:41.698  5696  5696 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 18:41:41.800   925  2941 D wifi    : In wifi stop Hal
11-04 18:41:41.800   925  2941 D wifi    : halHandle = 0x7f59ee1400, mVM = 0x7f7658d140, mCls = 0x101952
,11-04 18:41:41.801  4479  4479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 18:41:41.801   925  5695 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 18:41:41.801   925  5695 D WifiHAL : Got a signal to exit!!!
11-04 18:41:41.801   925  5695 I WifiHAL : Exit wifi_event_loop
11-04 18:41:41.802   925  2941 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-04 18:41:41.802   925  2941 E WifiHAL : Event processing terminated
11-04 18:41:41.802   925  2941 D wifi    : In wifi cleaned up handler
11-04 18:41:41.802   925  2941 I WifiHAL : Internal cleanup completed
11-04 18:41:41.803  3712  4180 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 18:41:41.803  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 18:41:41.825   925  5695 D wifi    : set interface wlan0 flags (DOWN)
,11-04 18:41:41.825   925  2941 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 18:41:42.030   925   942 D Tethering: InitialState.processMessage what=4
,11-04 18:41:42.037   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 18:41:42.121   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-04 18:41:42.337   925  2943 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-04 18:41:46.577   925   942 I ActivityManager: Start proc 5735:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 18:41:46.676  5735  5735 D AdapterServiceConfig: Adding HeadsetService
,11-04 18:41:46.676  5735  5735 D AdapterServiceConfig: Adding A2dpService
11-04 18:41:46.677  5735  5735 D AdapterServiceConfig: Adding HidService
11-04 18:41:46.677  5735  5735 D AdapterServiceConfig: Adding HealthService
11-04 18:41:46.677  5735  5735 D AdapterServiceConfig: Adding PanService
,11-04 18:41:46.677  5735  5735 D AdapterServiceConfig: Adding GattService
11-04 18:41:46.677  5735  5735 D AdapterServiceConfig: Adding BluetoothMapService
11-04 18:41:46.677  5735  5735 D AdapterServiceConfig: Adding SapService
,11-04 18:41:46.689   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b99a51b:true
,11-04 18:41:46.689  5735  5735 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 18:41:46.692  5735  5735 I bt_bluedroid: init
,11-04 18:41:46.692  5735  5747 I BluetoothAdapterState: Entering OffState
,11-04 18:41:46.694  5735  5748 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 18:41:46.694  5735  5748 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 18:41:46.694  5735  5748 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 18:41:46.694  5735  5748 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-04 18:41:46.695  5735  5735 I bt_bluedroid: get_profile_interface socket
,11-04 18:41:46.697  5735  5751 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 18:41:46.698  5735  5735 I bt_bluedroid: get_profile_interface sdp
11-04 18:41:46.698  5735  5751 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 18:41:46.703  5735  5746 I bt_bluedroid: config_hci_snoop_log
,11-04 18:41:46.704   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 18:41:46.708  5735  5747 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 18:41:46.708  5735  5747 D BluetoothAdapterProperties: Setting state to 14
11-04 18:41:46.708  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-04 18:41:46.710  5735  5747 D BluetoothBondStateMachine: make
,11-04 18:41:46.712  5735  5752 I BluetoothBondStateMachine: StableState(): Entering Off State
11-04 18:41:46.714  5735  5747 I BluetoothAdapterState: Entering PendingCommandState
,11-04 18:41:46.715  5735  5735 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 18:41:46.717  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:41:46.718  5735  5735 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 18:41:46.719  5735  5735 D BtGatt.GattService: Received start request. Starting profile...
11-04 18:41:46.719  5735  5735 D BtGatt.GattService: start()
11-04 18:41:46.719  5735  5735 I bt_bluedroid: get_profile_interface gatt
11-04 18:41:46.720  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:41:46.720  5735  5735 D BtGatt.AdvertiseManager: advertise manager created
,11-04 18:41:46.725  5735  5735 V BluetoothAdapterState: isTurningOff()=false
,11-04 18:41:46.725  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:46.725  5735  5735 V BluetoothAdapterState: isBleTurningOn()=true
11-04 18:41:46.725  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:46.725  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 18:41:46.726  5735  5747 I bt_bluedroid: bt_bluedroid
11-04 18:41:46.727  5735  5748 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-04 18:41:46.727  5735  5748 I bt_hci  : start_up
,11-04 18:41:46.732  5735  5748 I bt_vendor: alloc value 0xf41d5871
11-04 18:41:46.732  5735  5748 I bt_vendor: init
11-04 18:41:46.732  5735  5748 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 18:41:46.732  5735  5748 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 18:41:46.845  5735  5748 D bt_hci  : start_up starting async portion
,11-04 18:41:46.845  5735  5755 I bt_hci  : event_finish_startup
11-04 18:41:46.845  5735  5755 I bt_hci_h4: hal_open
11-04 18:41:46.846  5735  5755 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 18:41:46.844  5756  5756 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 18:41:46.849  5735  5755 I bt_userial_vendor: device fd = 54 open
,11-04 18:41:46.863  5735  5755 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 18:41:46.866  5735  5755 D bt_hwcfg: Chipset BCM4358A3
,11-04 18:41:46.866  5735  5755 D bt_hwcfg: Target name = [BCM4358A3]
11-04 18:41:46.867  5735  5755 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 18:41:47.270  5735  5755 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 18:41:47.270  5735  5755 D bt_hwcfg: Settlement delay -- 100 ms
,11-04 18:41:47.270  5735  5755 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 18:41:47.406  5735  5755 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 18:41:47.406  5735  5755 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-04 18:41:47.407  5735  5755 I bt_hwcfg: vendor lib fwcfg completed
11-04 18:41:47.408  5735  5755 I bt_vendor: firmware callback
11-04 18:41:47.408  5735  5755 I bt_hci  : firmware_config_callback
,11-04 18:41:47.419  5735  5758 I bt_btu  : btu_task pending for preload complete event
,11-04 18:41:47.419  5735  5758 I bt_btu_task: Bluetooth chip preload is complete
11-04 18:41:47.419  5735  5758 I bt_btu  : btu_task received preload complete event
,11-04 18:41:47.425  5735  5758 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 18:41:47.425  5735  5758 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 18:41:47.426  5735  5758 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 18:41:47.426  5735  5758 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-04 18:41:47.426  5735  5758 I         : BTE_InitTraceLevels -- TRC_AVRC
11-04 18:41:47.426  5735  5758 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 18:41:47.426  5735  5758 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 18:41:47.426  5735  5758 I         : BTE_InitTraceLevels -- TRC_BTM
,11-04 18:41:47.426  5735  5758 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 18:41:47.426  5735  5758 I         : BTE_InitTraceLevels -- TRC_PAN
,11-04 18:41:47.426  5735  5758 I         : BTE_InitTraceLevels -- TRC_SDP
11-04 18:41:47.427  5735  5758 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 18:41:47.427  5735  5758 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 18:41:47.427  5735  5758 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-04 18:41:47.427  5735  5758 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 18:41:47.514  5735  5758 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4153549
,11-04 18:41:47.515  5735  5758 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4153549 
,11-04 18:41:47.533  5735  5751 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 18:41:47.535  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 18:41:47.535  5735  5751 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 18:41:47.538  5735  5751 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 18:41:47.542  5735  5751 D BluetoothAdapterProperties: Scan Mode:20
,11-04 18:41:47.542  5735  5751 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 18:41:47.543  5735  5751 D bt_hci  : do_postload posting postload work item
,11-04 18:41:47.543  5735  5755 I bt_hci  : event_postload
11-04 18:41:47.543  5735  5755 I bt_vendor: sco_config_cb
,11-04 18:41:47.543  5735  5755 I bt_hci  : sco_config_callback postload finished.
11-04 18:41:47.546  5735  5751 D bt_bte_conf: Device ID record 1 : primary
11-04 18:41:47.546  5735  5751 D bt_bte_conf:   vendorId            = 000f
11-04 18:41:47.546  5735  5751 D bt_bte_conf:   vendorIdSource      = 0001
11-04 18:41:47.546  5735  5751 D bt_bte_conf:   product             = 1200
11-04 18:41:47.546  5735  5751 D bt_bte_conf:   version             = 1436
11-04 18:41:47.546  5735  5751 D bt_bte_conf:   clientExecutableURL = 
11-04 18:41:47.547  5735  5751 D bt_bte_conf:   serviceDescription  = 
11-04 18:41:47.547  5735  5751 D bt_bte_conf:   documentationURL    = 
,11-04 18:41:47.547  5735  5751 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 18:41:47.547  5735  5748 D bt_stack_manager: event_start_up_stack finished
11-04 18:41:47.548  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:47.548  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 18:41:47.549  5735  5747 D BluetoothAdapterProperties: Setting state to 15
11-04 18:41:47.549  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 18:41:47.551  5735  5747 I BluetoothAdapterState: Entering BleOnState
11-04 18:41:47.557  5735  5747 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-04 18:41:47.557  5735  5747 D BluetoothAdapterProperties: Setting state to 11
11-04 18:41:47.557  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-04 18:41:47.557  5735  5755 I bt_vendor: low_power_mode_cb
,11-04 18:41:47.563  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
,11-04 18:41:47.564  5735  5735 D HeadsetService: Received start request. Starting profile...
11-04 18:41:47.567  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:47.567  5735  5735 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 18:41:47.568  5735  5735 D HeadsetStateMachine: make
,11-04 18:41:47.578  5735  5747 I BluetoothAdapterState: Entering PendingCommandState
,11-04 18:41:47.584  5735  5735 D HeadsetStateMachine: max_hf_connections = 1
11-04 18:41:47.584  5735  5735 I bt_bluedroid: get_profile_interface handsfree
11-04 18:41:47.584  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 18:41:47.584  5735  5751 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-04 18:41:47.588  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
,11-04 18:41:47.588  5735  5735 D A2dpService: Received start request. Starting profile...
,11-04 18:41:47.589  5735  5735 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 18:41:47.589  5735  5735 I bt_bluedroid: get_profile_interface avrcp
,11-04 18:41:47.597  5735  5735 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-04 18:41:47.597  5735  5735 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 18:41:47.597  5735  5735 D A2dpStateMachine: make
,11-04 18:41:47.598  5735  5735 I bt_bluedroid: get_profile_interface a2dp
,11-04 18:41:47.600  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-04 18:41:47.601  5735  5766 D A2dpStateMachine: Enter Disconnected: -2
,11-04 18:41:47.602  5735  5735 I BluetoothHidServiceJni: classInitNative: succeeds
,11-04 18:41:47.603  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
,11-04 18:41:47.603  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 18:41:47.604  5628  5628 D BluetoothInputDevice: Proxy object connected
,11-04 18:41:47.605  5628  5628 D HidProfile: Bluetooth service connected
11-04 18:41:47.605  5735  5735 D HidService: Received start request. Starting profile...
11-04 18:41:47.605  5735  5735 I bt_bluedroid: get_profile_interface hidhost
11-04 18:41:47.605  5735  5751 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf413456d
11-04 18:41:47.606  5735  5735 D HidService: setHidService(): set to: null
11-04 18:41:47.606  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-04 18:41:47.606  5735  5735 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-04 18:41:47.607  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:41:47.608  5735  5735 D HealthService: Received start request. Starting profile...
,11-04 18:41:47.610  5735  5735 I bt_bluedroid: get_profile_interface health
11-04 18:41:47.610  5735  5735 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-04 18:41:47.611  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
,11-04 18:41:47.612  5628  5628 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 18:41:47.612  5735  5735 D PanService: Received start request. Starting profile...
11-04 18:41:47.612  5735  5735 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 18:41:47.612  5735  5735 I bt_bluedroid: get_profile_interface pan
11-04 18:41:47.613  5628  5628 D PanProfile: Bluetooth service connected
11-04 18:41:47.613  5735  5751 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-04 18:41:47.615  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
,11-04 18:41:47.616  5735  5735 D BluetoothMapService: Received start request. Starting profile...
,11-04 18:41:47.616  5735  5735 D BluetoothMapService: start()
11-04 18:41:47.619  5735  5735 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-04 18:41:47.619  5735  5735 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 18:41:47.619  5735  5735 D BluetoothMapAppObserver: createReceiver()
11-04 18:41:47.621  5735  5735 D BluetoothMapAppObserver: initObservers()
,11-04 18:41:47.621  5735  5735 D BluetoothMapAppObserver: getEnabledAccountItems()
11-04 18:41:47.621  5628  5628 D BluetoothMap: Proxy object connected
11-04 18:41:47.622  5628  5628 D MapProfile: Bluetooth service connected
11-04 18:41:47.622  5628  5628 D BluetoothMap: getConnectedDevices()
11-04 18:41:47.623  5628  5628 D BluetoothMap: Bluetooth is Not enabled
,11-04 18:41:47.628  5735  5735 V SapService: SapBinder()
,11-04 18:41:47.628  5735  5735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:41:47.628  5735  5735 D SapService: Received start request. Starting profile...
11-04 18:41:47.628  5735  5735 V SapService: start()
,11-04 18:41:47.631  5735  5735 V BluetoothAdapterState: isTurningOff()=false
,11-04 18:41:47.631  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-04 18:41:47.631  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:47.631  5735  5763 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 18:41:47.632  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:47.632  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-04 18:41:47.632  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-04 18:41:47.632  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:47.632  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 18:41:47.632  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-04 18:41:47.632  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-04 18:41:47.633  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:47.634  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:47.635  5735  5735 V BluetoothAdapterState: isTurningOff()=false
11-04 18:41:47.635  5735  5735 V BluetoothAdapterState: isTurningOn()=true
11-04 18:41:47.635  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:47.635  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:47.635  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-04 18:41:47.635  5735  5747 D BluetoothAdapterProperties: ScanMode =  20
,11-04 18:41:47.635  5735  5747 D BluetoothAdapterProperties: State =  11
11-04 18:41:47.635  5735  5747 D BluetoothAdapterProperties: Setting state to 12
11-04 18:41:47.635  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 18:41:47.636  5735  5747 I BluetoothAdapterState: Entering OnState
11-04 18:41:47.636  3086  3846 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 18:41:47.638  3086  3097 D BluetoothPbap: onBluetoothStateChange: up=true
,11-04 18:41:47.638  5735  5751 D BluetoothAdapterProperties: Scan Mode:21
11-04 18:41:47.638  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 18:41:47.639  5735  5751 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 18:41:47.639  3086  3086 D BluetoothA2dp: Proxy object connected
11-04 18:41:47.639   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 18:41:47.639   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 18:41:47.639  5628  5641 D BluetoothMap: onBluetoothStateChange: up=true
11-04 18:41:47.640  3774  3800 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 18:41:47.640  3086  3846 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 18:41:47.641  3086  3099 D BluetoothMap: onBluetoothStateChange: up=true
11-04 18:41:47.642  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 18:41:47.642  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:47.642  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:47.642  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 18:41:47.642  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 18:41:47.642  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 18:41:47.642  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 18:41:47.642  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 18:41:47.642  3086  3097 D BluetoothPan: onBluetoothStateChange on: true
11-04 18:41:47.642  3086  3086 D BluetoothMap: Proxy object connected
11-04 18:41:47.642  3086  3086 D MapProfile: Bluetooth service connected
11-04 18:41:47.642  3086  3086 D BluetoothMap: getConnectedDevices()
11-04 18:41:47.644  5570  5570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 18:41:47.646  3086  3086 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 18:41:47.646  3086  3086 D PanProfile: Bluetooth service connected
11-04 18:41:47.647  5628  5639 D BluetoothPan: onBluetoothStateChange on: true
,11-04 18:41:47.647  5628  5641 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 18:41:47.647  5735  5735 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 18:41:47.648  5735  5735 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 18:41:47.648  5628  5639 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 18:41:47.648   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 18:41:47.649   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 18:41:47.649   925   925 D BluetoothA2dp: Proxy object connected
11-04 18:41:47.649  5735  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 18:41:47.649  3086  3846 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 18:41:47.651  5735  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 18:41:47.651  3086  3086 D BluetoothInputDevice: Proxy object connected
11-04 18:41:47.651  3086  3086 D HidProfile: Bluetooth service connected
11-04 18:41:47.652   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
,11-04 18:41:47.652  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-04 18:41:47.655  5735  5735 D ObexServerSockets: Succeed to create listening sockets 
11-04 18:41:47.655  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:47.655  5735  5735 D ObexServerSockets0: startAccept()
,11-04 18:41:47.655  5735  5735 D ObexServerSockets0: prepareForNewConnect()
11-04 18:41:47.655  5628  5628 D LocalBluetoothProfileManager: Adding local A2DP profile
11-04 18:41:47.657  5735  5735 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 18:41:47.657  5735  5735 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 18:41:47.657  5735  5774 D ObexServerSockets0: Accepting socket connection...
11-04 18:41:47.657  5735  5735 D BluetoothMapService: onReceive
,11-04 18:41:47.657  5735  5735 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 18:41:47.657  5735  5735 D BluetoothMapService: STATE_ON
11-04 18:41:47.658  5735  5775 D ObexServerSockets0: Accepting socket connection...
11-04 18:41:47.659  5628  5628 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-04 18:41:47.659  5735  5776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 18:41:47.660  5735  5776 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-04 18:41:47.660  5735  5776 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 18:41:47.665  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 18:41:47.667  5628  5628 D BluetoothA2dp: Proxy object connected
,11-04 18:41:47.673  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 18:41:47.677  5628  5628 D DockEventReceiver: finishStartingService: stopping service
,11-04 18:41:47.681  5628  5628 D BluetoothPbap: Proxy object connected
,11-04 18:41:47.682  5628  5628 D PbapServerProfile: Bluetooth service connected
11-04 18:41:47.682  3086  3086 D BluetoothPbap: Proxy object connected
11-04 18:41:47.682  3086  3086 D PbapServerProfile: Bluetooth service connected
,11-04 18:41:47.685  5735  5735 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 18:41:47.685  5735  5735 D ObexServerSockets0: prepareForNewConnect()
,11-04 18:41:47.688  5735  5780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 18:41:47.704  5735  5784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 18:41:47.706  5735  5784 I BtOppRfcommListener: Accept thread started.
,11-04 18:41:47.741   925   925 D BluetoothHeadset: Proxy object connected
,11-04 18:41:47.741  3086  3846 D BluetoothHeadset: Proxy object connected
11-04 18:41:47.741  3086  3086 D HeadsetProfile: Bluetooth service connected
11-04 18:41:47.741   925   925 D BluetoothHeadset: Proxy object connected
11-04 18:41:47.741   925   925 D BluetoothHeadset: Proxy object connected
,11-04 18:41:47.742  3774  3978 D BluetoothHeadset: Proxy object connected
,11-04 18:41:47.748   925   942 D BluetoothHeadset: Proxy object connected
,11-04 18:41:47.761  5628  5639 D BluetoothHeadset: Proxy object connected
,11-04 18:41:47.763  5628  5628 D HeadsetProfile: Bluetooth service connected
,11-04 18:41:48.047  3613  3735 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-04 18:41:48.047  3613  3735 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-04 18:41:48.074  3550  3550 I ConfigService: onCreate
,11-04 18:41:49.295   925  2943 D ConnectivityService: handlePromptUnvalidated 101
,11-04 18:41:51.552  5735  5747 D BluetoothAdapterState: Current state: ON, message: 23
11-04 18:41:51.552  5735  5747 D BluetoothAdapterProperties: Setting state to 13
11-04 18:41:51.552  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 18:41:51.554  5735  5747 D BluetoothAdapterProperties: onBluetoothDisable()
,11-04 18:41:51.555  5735  5747 I BluetoothAdapterState: Entering PendingCommandState
,11-04 18:41:51.557  5735  5751 D BluetoothAdapterProperties: Scan Mode:20
11-04 18:41:51.558  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 18:41:51.561  5735  5735 D BluetoothMapService: onReceive
,11-04 18:41:51.562  5735  5735 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 18:41:51.562  5735  5735 D BluetoothMapService: STATE_TURNING_OFF
,11-04 18:41:51.562  5735  5735 D BluetoothMapService: MAP Service closeService in
11-04 18:41:51.562  5735  5735 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 18:41:51.562  5735  5735 D ObexServerSockets0: shutdown(block = true)
11-04 18:41:51.563  5735  5735 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-04 18:41:51.564  5735  5735 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 18:41:51.564  5735  5774 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-04 18:41:51.564  5735  5775 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 18:41:51.565  5735  5760 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 18:41:51.566  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:51.566  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 18:41:51.566  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:41:51.566  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:41:51.566  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 18:41:51.566  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 18:41:51.566  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 18:41:51.566  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 18:41:51.566  5570  5570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 18:41:51.567  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 18:41:51.567  5570  5570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 18:41:51.567  5570  5570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 18:41:51.573  5735  5735 I BtOppRfcommListener: stopping Accept Thread
,11-04 18:41:51.574  5735  5784 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-04 18:41:51.574  5735  5784 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-04 18:41:51.577  5735  5735 D HeadsetService: Received stop request...Stopping profile...
11-04 18:41:51.577  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:51.580   925   925 D BluetoothHeadset: Proxy object disconnected
11-04 18:41:51.581  3086  3097 D BluetoothHeadset: Proxy object disconnected
11-04 18:41:51.581   925   925 D BluetoothHeadset: Proxy object disconnected
11-04 18:41:51.582   925   925 D BluetoothHeadset: Proxy object disconnected
,11-04 18:41:51.582  5628  5641 D BluetoothHeadset: Proxy object disconnected
,11-04 18:41:51.583  5735  5735 D A2dpService: Received stop request...Stopping profile...
11-04 18:41:51.583  3774  3798 D BluetoothHeadset: Proxy object disconnected
11-04 18:41:51.583  5735  5766 D A2dpStateMachine: Exit Disconnected: -1
11-04 18:41:51.584  5628  5628 D DockEventReceiver: finishStartingService: stopping service
11-04 18:41:51.584   925   925 D BluetoothA2dp: Proxy object disconnected
11-04 18:41:51.585  3086  3086 D HeadsetProfile: Bluetooth service disconnected
11-04 18:41:51.586  3086  3086 D BluetoothA2dp: Proxy object disconnected
11-04 18:41:51.586  5628  5628 D HeadsetProfile: Bluetooth service disconnected
,11-04 18:41:51.586  5735  5735 D HidService: Received stop request...Stopping profile...
11-04 18:41:51.586  5735  5735 D HidService: Stopping Bluetooth HidService
11-04 18:41:51.586  5628  5628 D BluetoothA2dp: Proxy object disconnected
11-04 18:41:51.587  5628  5628 D BluetoothInputDevice: Proxy object disconnected
11-04 18:41:51.587  5628  5628 D HidProfile: Bluetooth service disconnected
11-04 18:41:51.588  3086  3086 D BluetoothInputDevice: Proxy object disconnected
11-04 18:41:51.588  3086  3086 D HidProfile: Bluetooth service disconnected
11-04 18:41:51.588  5735  5735 D HealthService: Received stop request...Stopping profile...
,11-04 18:41:51.592  5735  5735 D PanService: Received stop request...Stopping profile...
11-04 18:41:51.592  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 18:41:51.593  3086  3086 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-04 18:41:51.593  3086  3086 D PanProfile: Bluetooth service disconnected
11-04 18:41:51.595  5628  5628 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 18:41:51.595  5628  5628 D PanProfile: Bluetooth service disconnected
,11-04 18:41:51.595  5735  5735 D BluetoothMapService: Received stop request...Stopping profile...
11-04 18:41:51.595  5735  5735 D BluetoothMapService: stop()
,11-04 18:41:51.596  5735  5735 D BluetoothMapAppObserver: deinitObservers()
11-04 18:41:51.596  5735  5735 D BluetoothMapAppObserver: removeReceiver()
11-04 18:41:51.598  3086  3086 D BluetoothMap: Proxy object disconnected
11-04 18:41:51.598  3086  3086 D MapProfile: Bluetooth service disconnected
11-04 18:41:51.598  5628  5628 D BluetoothMap: Proxy object disconnected
11-04 18:41:51.598  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:51.598  5628  5628 D MapProfile: Bluetooth service disconnected
,11-04 18:41:51.598  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:51.598  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:51.598  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 18:41:51.599  5735  5735 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 18:41:51.600  5735  5735 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 18:41:51.600  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 18:41:51.600  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 18:41:51.600  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:51.600  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 18:41:51.600  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:51.600  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 18:41:51.600  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:51.600  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:51.600  5735  5751 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 18:41:51.601  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 18:41:51.602  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 18:41:51.602  5735  5735 D SapService: Received stop request...Stopping profile...
11-04 18:41:51.602  5735  5735 V SapService: stop()
11-04 18:41:51.603  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-04 18:41:51.603  5735  5758 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 18:41:51.603  5735  5758 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 18:41:51.603  5735  5758 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 18:41:51.603  5735  5758 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-04 18:41:51.604  5735  5735 V BluetoothAdapterState: isTurningOff()=true
,11-04 18:41:51.604  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:51.604  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:51.604  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:51.604  5735  5735 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 18:41:51.605  5735  5735 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 18:41:51.605  5735  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 18:41:51.606  5735  5735 V BluetoothAdapterState: isTurningOff()=true
,11-04 18:41:51.606  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:51.606  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:51.606  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:51.606  5735  5735 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 18:41:51.606  5735  5751 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 18:41:51.606  5735  5735 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-04 18:41:51.609  5628  5628 D BluetoothPbap: Proxy object disconnected
11-04 18:41:51.609  5628  5628 D PbapServerProfile: Bluetooth service disconnected
,11-04 18:41:51.609  3086  3086 D BluetoothPbap: Proxy object disconnected
11-04 18:41:51.609  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:51.609  3086  3086 D PbapServerProfile: Bluetooth service disconnected
11-04 18:41:51.609  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:51.609  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:51.609  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:51.610  5735  5735 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 18:41:51.610  5735  5735 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 18:41:51.611  5735  5735 D BluetoothMapService: MAP Service closeService in
11-04 18:41:51.611  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:51.611  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:51.611  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:51.611  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:41:51.611  5735  5735 D BluetoothMapService: cleanup()
11-04 18:41:51.611  5735  5735 D BluetoothMapService: MAP Service closeService in
11-04 18:41:51.611  5735  5735 V BluetoothAdapterState: isTurningOff()=true
11-04 18:41:51.611  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:51.612  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 18:41:51.612  5735  5735 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 18:41:51.614  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 18:41:51.614  5735  5747 D BluetoothAdapterProperties: Setting state to 15
11-04 18:41:51.614  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 18:41:51.614  5735  5747 I BluetoothAdapterState: Entering BleOnState
11-04 18:41:51.618  3086  3099 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 18:41:51.619  3086  3846 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 18:41:51.619   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 18:41:51.619   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-04 18:41:51.620  5628  5641 D BluetoothMap: onBluetoothStateChange: up=false
,11-04 18:41:51.621  3774  3800 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 18:41:51.621  3086  3097 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 18:41:51.622  3086  3099 D BluetoothMap: onBluetoothStateChange: up=false
11-04 18:41:51.623  3086  3846 D BluetoothPan: onBluetoothStateChange on: false
11-04 18:41:51.625  5628  5639 D BluetoothPan: onBluetoothStateChange on: false
,11-04 18:41:51.641  5628  5641 D BluetoothPbap: onBluetoothStateChange: up=false
,11-04 18:41:51.642  5628  5639 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 18:41:51.642  5628  5641 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 18:41:51.643   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 18:41:51.643   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 18:41:51.643  5628  5639 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-04 18:41:51.643  3086  3097 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-04 18:41:51.644  5735  5747 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 18:41:51.644  5735  5747 D BluetoothAdapterProperties: Setting state to 16
11-04 18:41:51.644  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 18:41:51.645  5735  5747 D BluetoothAdapterProperties: onBleDisable
11-04 18:41:51.645  5735  5747 I BluetoothAdapterState: Entering PendingCommandState
11-04 18:41:51.646  5735  5748 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 18:41:51.646  5735  5758 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 18:41:51.646  5735  5758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 18:41:51.647  5735  5751 D BluetoothAdapterProperties: Scan Mode:20
11-04 18:41:51.648  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 18:41:51.651  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:51.652  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:41:51.652  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 18:41:51.654  5628  5628 D DockEventReceiver: finishStartingService: stopping service
,11-04 18:41:51.859  5735  5751 I bt_hci  : shut_down
,11-04 18:41:51.868  5735  5755 D bt_hwcfg: hw_epilog_process
,11-04 18:41:51.869  5735  5755 I bt_vendor: low_power_mode_cb
,11-04 18:41:51.872  5735  5755 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-04 18:41:51.872  5735  5755 I bt_vendor: epilog_cb
11-04 18:41:51.872  5735  5755 I bt_hci  : epilog_finished_callback
,11-04 18:41:51.877  5735  5751 I bt_hci_h4: hal_close
,11-04 18:41:51.879  5735  5751 I bt_userial_vendor: device fd = 54 close
,11-04 18:41:52.002  5735  5748 D bt_stack_manager: event_shut_down_stack finished.
,11-04 18:41:52.002  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-04 18:41:52.007  5735  5735 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 18:41:52.007  5735  5747 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-04 18:41:52.008  5735  5735 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 18:41:52.009  5735  5735 D BtGatt.GattService: stop()
11-04 18:41:52.009  5735  5735 D BtGatt.AdvertiseManager: advertise clients cleared
,11-04 18:41:52.013  5735  5735 V BluetoothAdapterState: isTurningOff()=false
,11-04 18:41:52.013  5735  5735 V BluetoothAdapterState: isTurningOn()=false
11-04 18:41:52.013  5735  5735 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:41:52.013  5735  5735 V BluetoothAdapterState: isBleTurningOff()=true
11-04 18:41:52.014  5735  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-04 18:41:52.014  5735  5747 D BluetoothAdapterProperties: Setting state to 10
11-04 18:41:52.014  5735  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 18:41:52.016  5735  5747 I BluetoothAdapterState: Entering OffState
,11-04 18:41:52.018   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-04 18:41:52.029  5735  5735 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 18:41:52.029  5735  5735 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-04 18:41:52.030  5735  5735 I BluetoothServiceJni: cleanupNative: return from cleanup
11-04 18:41:52.032  5735  5748 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 18:41:52.039  5735  5735 I art     : System.exit called, status: 0
,11-04 18:41:52.039  5735  5735 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 18:41:52.072   925  3831 I ActivityManager: Process com.android.bluetooth (pid 5735) has died
,11-04 18:41:52.123   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:53.102  3550  3550 I ConfigService: onDestroy
,11-04 18:41:53.124   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:54.125   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:55.126   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:56.127   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:41:56.550  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:56.550  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 18:41:56.557  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:41:56.557  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6287c12 removed from the list
11-04 18:41:56.557  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 18:41:56.561  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 18:41:56.561  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18b1899 added. We now have 4 listener(s)
11-04 18:41:56.562  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 18:41:56.563  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:41:56.563  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18b1899 removed from the list
11-04 18:41:56.563  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:41:56.565  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 18:41:56.565  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@90e475e added. We now have 4 listener(s)
11-04 18:41:56.566  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 18:41:57.128   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-04 18:42:00.274   925   945 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-04 18:42:00.277  3385  3385 W Binder_5: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32928]" dev="sockfs" ino=32928 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:00.281  3385  3385 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32928]" dev="sockfs" ino=32928 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:00.288  3613  3613 I Keyboard.Facilitator: onFinishInput()
,11-04 18:42:00.303   925   945 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 18:42:00.303   925   945 I Adreno  : Build Date                       : 12/06/15
11-04 18:42:00.303   925   945 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 18:42:00.303   925   945 I Adreno  : Local Branch                     : mybranch17112971
11-04 18:42:00.303   925   945 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 18:42:00.303   925   945 I Adreno  : Remote Branch                    : NONE
11-04 18:42:00.303   925   945 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 18:42:00.340   381   402 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (142 us)
,11-04 18:42:01.045  5570  5570 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-04 18:42:01.046  5570  5570 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-04 18:42:01.075   925   945 I sensors : batch
11-04 18:42:01.076   925   945 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-04 18:42:01.079   925   945 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-04 18:42:01.079   925   945 I sensors : activate
11-04 18:42:01.080  5570  5570 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5d7ec99 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@587373f, 16908290=android.view.AbsSavedState$1@587373f}, android:focusedViewId=100}]}]
11-04 18:42:01.080  5570  5570 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-04 18:42:01.080  5570  5570 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 18:42:01.080  5570  5570 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-04 18:42:01.081   925   943 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-04 18:42:01.081   381   381 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f8dd03c00
11-04 18:42:01.081   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,11-04 18:42:01.083   925  2688 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-04 18:42:01.084   925  2688 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-04 18:42:01.384   381   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-04 18:42:01.389   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-04 18:42:01.391   925  3054 D SurfaceControl: Excessive delay in setPowerMode(): 310ms
,11-04 18:42:01.408   925   945 I DreamManagerService: Entering dreamland.
11-04 18:42:01.409   925   945 I PowerManagerService: Dozing...
,11-04 18:42:01.410   925   940 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-04 18:42:01.434  3831  3831 W Binder_A: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[33800]" dev="sockfs" ino=33800 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:01.438   925  3127 I sensors : batch
11-04 18:42:01.437  3831  3831 W Binder_A: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33800]" dev="sockfs" ino=33800 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 18:42:01.439   925  3127 I sensors : activate
,11-04 18:42:01.442   925  2688 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-04 18:42:01.444   925  2688 I hubconnection: sensorhub said: 'activate 21 enable:1'
11-04 18:42:01.448   511   511 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-04 18:42:01.474  3774  4706 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-04 18:42:01.474  3774  4706 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 18:42:01.474  3774  4706 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 18:42:01.474   524  1302 D         : oem-qmi: Connection accepted
11-04 18:42:01.475   524  1302 D         : oem-qmi: Waiting to accept connection
,11-04 18:42:01.476   925   925 I sensors : activate
11-04 18:42:01.477   511  2964 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
11-04 18:42:01.480   925  2688 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-04 18:42:01.481  3774  4706 D         : oem_qmi_lib:output 0
,11-04 18:42:01.481  3774  4706 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 18:42:01.512  3774  4706 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-04 18:42:01.512  3774  4706 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 18:42:01.512  3774  4706 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 18:42:01.512   524  1302 D         : oem-qmi: Connection accepted
11-04 18:42:01.513   524  1302 D         : oem-qmi: Waiting to accept connection
,11-04 18:42:01.519  3774  4706 D         : oem_qmi_lib:output 0
,11-04 18:42:01.519  3774  4706 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 18:42:01.573  5570  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 18:42:01.595   925   942 I ActivityManager: Start proc 5801:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 18:42:01.664  5801  5801 D AdapterServiceConfig: Adding HeadsetService
,11-04 18:42:01.664  5801  5801 D AdapterServiceConfig: Adding A2dpService
,11-04 18:42:01.665  5801  5801 D AdapterServiceConfig: Adding HidService
,11-04 18:42:01.665  5801  5801 D AdapterServiceConfig: Adding HealthService
11-04 18:42:01.665  5801  5801 D AdapterServiceConfig: Adding PanService
11-04 18:42:01.665  5801  5801 D AdapterServiceConfig: Adding GattService
11-04 18:42:01.665  5801  5801 D AdapterServiceConfig: Adding BluetoothMapService
11-04 18:42:01.665  5801  5801 D AdapterServiceConfig: Adding SapService
,11-04 18:42:01.676   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@96012a8:true
,11-04 18:42:01.676  5801  5801 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 18:42:01.679  5801  5801 I bt_bluedroid: init
,11-04 18:42:01.679  5801  5813 I BluetoothAdapterState: Entering OffState
,11-04 18:42:01.681  5801  5814 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 18:42:01.681  5801  5814 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 18:42:01.681  5801  5814 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 18:42:01.681  5801  5814 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 18:42:01.682  5801  5801 I bt_bluedroid: get_profile_interface socket
,11-04 18:42:01.683  5801  5817 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 18:42:01.684  5801  5801 I bt_bluedroid: get_profile_interface sdp
11-04 18:42:01.685  5801  5817 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 18:42:01.688  5801  5812 I bt_bluedroid: config_hci_snoop_log
11-04 18:42:01.689   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 18:42:01.693  5801  5813 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 18:42:01.693  5801  5813 D BluetoothAdapterProperties: Setting state to 14
11-04 18:42:01.693  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-04 18:42:01.694  5801  5813 D BluetoothBondStateMachine: make
,11-04 18:42:01.696  5801  5818 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 18:42:01.698  5801  5813 I BluetoothAdapterState: Entering PendingCommandState
,11-04 18:42:01.699  5801  5801 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 18:42:01.701  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:42:01.701  5801  5801 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 18:42:01.702  5801  5801 D BtGatt.GattService: Received start request. Starting profile...
,11-04 18:42:01.702  5801  5801 D BtGatt.GattService: start()
11-04 18:42:01.702  5801  5801 I bt_bluedroid: get_profile_interface gatt
,11-04 18:42:01.703  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:42:01.703  5801  5801 D BtGatt.AdvertiseManager: advertise manager created
,11-04 18:42:01.708  5801  5801 V BluetoothAdapterState: isTurningOff()=false
11-04 18:42:01.708  5801  5801 V BluetoothAdapterState: isTurningOn()=false
11-04 18:42:01.708  5801  5801 V BluetoothAdapterState: isBleTurningOn()=true
11-04 18:42:01.708  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:42:01.708  5801  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 18:42:01.709  5801  5813 I bt_bluedroid: bt_bluedroid
11-04 18:42:01.710  5801  5814 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-04 18:42:01.710  5801  5814 I bt_hci  : start_up
,11-04 18:42:01.715  5801  5814 I bt_vendor: alloc value 0xf41d5871
,11-04 18:42:01.715  5801  5814 I bt_vendor: init
11-04 18:42:01.715  5801  5814 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 18:42:01.715  5801  5814 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 18:42:01.825  5801  5814 D bt_hci  : start_up starting async portion
,11-04 18:42:01.825  5801  5821 I bt_hci  : event_finish_startup
,11-04 18:42:01.825  5801  5821 I bt_hci_h4: hal_open
11-04 18:42:01.825  5801  5821 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 18:42:01.824  5822  5822 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-04 18:42:01.828  5801  5821 I bt_userial_vendor: device fd = 54 open
,11-04 18:42:01.843  5801  5821 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 18:42:01.845  5801  5821 D bt_hwcfg: Chipset BCM4358A3
,11-04 18:42:01.845  5801  5821 D bt_hwcfg: Target name = [BCM4358A3]
,11-04 18:42:01.846  5801  5821 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 18:42:02.248  5801  5821 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 18:42:02.248  5801  5821 D bt_hwcfg: Settlement delay -- 100 ms
,11-04 18:42:02.249  5801  5821 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 18:42:02.383  5801  5821 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 18:42:02.383  5801  5821 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-04 18:42:02.384  5801  5821 I bt_hwcfg: vendor lib fwcfg completed
,11-04 18:42:02.385  5801  5821 I bt_vendor: firmware callback
11-04 18:42:02.385  5801  5821 I bt_hci  : firmware_config_callback
11-04 18:42:02.393  5801  5824 I bt_btu  : btu_task pending for preload complete event
11-04 18:42:02.393  5801  5824 I bt_btu_task: Bluetooth chip preload is complete
11-04 18:42:02.393  5801  5824 I bt_btu  : btu_task received preload complete event
,11-04 18:42:02.400  5801  5824 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 18:42:02.400  5801  5824 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 18:42:02.400  5801  5824 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 18:42:02.400  5801  5824 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 18:42:02.400  5801  5824 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-04 18:42:02.400  5801  5824 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 18:42:02.401  5801  5824 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 18:42:02.401  5801  5824 I         : BTE_InitTraceLevels -- TRC_BTM
,11-04 18:42:02.401  5801  5824 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 18:42:02.401  5801  5824 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 18:42:02.401  5801  5824 I         : BTE_InitTraceLevels -- TRC_SDP
,11-04 18:42:02.401  5801  5824 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 18:42:02.401  5801  5824 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 18:42:02.402  5801  5824 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-04 18:42:02.402  5801  5824 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 18:42:02.486  5801  5824 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4153549
11-04 18:42:02.486  5801  5824 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4153549 
,11-04 18:42:02.501  5801  5817 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 18:42:02.503  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 18:42:02.503  5801  5817 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-04 18:42:02.505  5801  5817 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 18:42:02.508  5801  5817 D BluetoothAdapterProperties: Scan Mode:20
,11-04 18:42:02.508  5801  5817 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-04 18:42:02.508  5801  5817 D bt_hci  : do_postload posting postload work item
11-04 18:42:02.509  5801  5821 I bt_hci  : event_postload
11-04 18:42:02.509  5801  5821 I bt_vendor: sco_config_cb
,11-04 18:42:02.509  5801  5821 I bt_hci  : sco_config_callback postload finished.
,11-04 18:42:02.511  5801  5817 D bt_bte_conf: Device ID record 1 : primary
11-04 18:42:02.511  5801  5817 D bt_bte_conf:   vendorId            = 000f
11-04 18:42:02.511  5801  5817 D bt_bte_conf:   vendorIdSource      = 0001
11-04 18:42:02.511  5801  5817 D bt_bte_conf:   product             = 1200
11-04 18:42:02.511  5801  5817 D bt_bte_conf:   version             = 1436
11-04 18:42:02.511  5801  5817 D bt_bte_conf:   clientExecutableURL = 
,11-04 18:42:02.511  5801  5817 D bt_bte_conf:   serviceDescription  = 
11-04 18:42:02.511  5801  5817 D bt_bte_conf:   documentationURL    = 
11-04 18:42:02.512  5801  5817 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 18:42:02.512  5801  5814 D bt_stack_manager: event_start_up_stack finished
11-04 18:42:02.513  5801  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 18:42:02.513  5801  5813 D BluetoothAdapterProperties: Setting state to 15
11-04 18:42:02.513  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 18:42:02.515  5801  5813 I BluetoothAdapterState: Entering BleOnState
,11-04 18:42:02.520  5801  5821 I bt_vendor: low_power_mode_cb
,11-04 18:42:02.522  5801  5813 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-04 18:42:02.523  5801  5813 D BluetoothAdapterProperties: Setting state to 11
11-04 18:42:02.523  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-04 18:42:02.532  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:42:02.532  5801  5801 D HeadsetService: Received start request. Starting profile...
11-04 18:42:02.535  5801  5801 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-04 18:42:02.535  5801  5801 D HeadsetStateMachine: make
,11-04 18:42:02.548  5801  5801 D HeadsetStateMachine: max_hf_connections = 1
,11-04 18:42:02.548  5801  5801 I bt_bluedroid: get_profile_interface handsfree
11-04 18:42:02.549  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 18:42:02.550  5801  5817 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-04 18:42:02.550  5801  5813 I BluetoothAdapterState: Entering PendingCommandState
11-04 18:42:02.551  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
,11-04 18:42:02.552  5801  5801 D A2dpService: Received start request. Starting profile...
,11-04 18:42:02.553  5801  5801 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 18:42:02.553  5801  5801 I bt_bluedroid: get_profile_interface avrcp
,11-04 18:42:02.559  5801  5801 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 18:42:02.559  5801  5801 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 18:42:02.559  5801  5801 D A2dpStateMachine: make
11-04 18:42:02.560  5801  5801 I bt_bluedroid: get_profile_interface a2dp
,11-04 18:42:02.560  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-04 18:42:02.562  5801  5832 D A2dpStateMachine: Enter Disconnected: -2
11-04 18:42:02.562  5801  5801 I BluetoothHidServiceJni: classInitNative: succeeds
,11-04 18:42:02.563  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:42:02.564  5801  5801 D HidService: Received start request. Starting profile...
11-04 18:42:02.564  5801  5801 I bt_bluedroid: get_profile_interface hidhost
11-04 18:42:02.564  5801  5801 D HidService: setHidService(): set to: null
11-04 18:42:02.564  5801  5817 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf413456d
11-04 18:42:02.564  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-04 18:42:02.565  5801  5801 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 18:42:02.566  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:42:02.567  5801  5801 D HealthService: Received start request. Starting profile...
11-04 18:42:02.567  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 18:42:02.569  5801  5801 I bt_bluedroid: get_profile_interface health
,11-04 18:42:02.569  5801  5801 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 18:42:02.570  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:42:02.572  5801  5801 D PanService: Received start request. Starting profile...
11-04 18:42:02.572  5801  5801 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 18:42:02.572  5801  5801 I bt_bluedroid: get_profile_interface pan
11-04 18:42:02.572  5801  5817 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-04 18:42:02.574  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
,11-04 18:42:02.575  5801  5801 D BluetoothMapService: Received start request. Starting profile...
11-04 18:42:02.575  5801  5801 D BluetoothMapService: start()
11-04 18:42:02.577  5801  5801 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-04 18:42:02.578  5801  5801 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 18:42:02.578  5801  5801 D BluetoothMapAppObserver: createReceiver()
,11-04 18:42:02.579  5801  5801 D BluetoothMapAppObserver: initObservers()
,11-04 18:42:02.579  5801  5801 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 18:42:02.585  5801  5801 V SapService: SapBinder()
11-04 18:42:02.585  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:42:02.585  5801  5801 D SapService: Received start request. Starting profile...
11-04 18:42:02.585  5801  5801 V SapService: start()
11-04 18:42:02.586  5801  5801 V BluetoothAdapterState: isTurningOff()=false
11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isTurningOn()=true
,11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:42:02.587  5801  5829 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isTurningOff()=false
11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isTurningOn()=true
11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isTurningOff()=false
11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isTurningOn()=true
11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 18:42:02.587  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:42:02.588  5801  5801 V BluetoothAdapterState: isTurningOff()=false
11-04 18:42:02.588  5801  5801 V BluetoothAdapterState: isTurningOn()=true
11-04 18:42:02.588  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:42:02.588  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:42:02.589  5801  5801 V BluetoothAdapterState: isTurningOff()=false
11-04 18:42:02.589  5801  5801 V BluetoothAdapterState: isTurningOn()=true
,11-04 18:42:02.589  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:42:02.589  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:42:02.589  5801  5801 V BluetoothAdapterState: isTurningOff()=false
11-04 18:42:02.589  5801  5801 V BluetoothAdapterState: isTurningOn()=true
11-04 18:42:02.589  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:42:02.589  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:42:02.590  5801  5801 V BluetoothAdapterState: isTurningOff()=false
11-04 18:42:02.590  5801  5801 V BluetoothAdapterState: isTurningOn()=true
,11-04 18:42:02.590  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
11-04 18:42:02.590  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
11-04 18:42:02.590  5801  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 18:42:02.590  5801  5813 D BluetoothAdapterProperties: ScanMode =  20
11-04 18:42:02.590  5801  5813 D BluetoothAdapterProperties: State =  11
11-04 18:42:02.590  5801  5813 D BluetoothAdapterProperties: Setting state to 12
,11-04 18:42:02.590  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 18:42:02.591  5801  5813 I BluetoothAdapterState: Entering OnState
11-04 18:42:02.591  3086  3099 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 18:42:02.592  5801  5817 D BluetoothAdapterProperties: Scan Mode:21
11-04 18:42:02.592  5801  5817 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-04 18:42:02.593  3086  3846 D BluetoothPbap: onBluetoothStateChange: up=true
,11-04 18:42:02.594  3086  3086 D BluetoothA2dp: Proxy object connected
11-04 18:42:02.595   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 18:42:02.595   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 18:42:02.595  5628  5639 D BluetoothMap: onBluetoothStateChange: up=true
11-04 18:42:02.597  3774  3978 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 18:42:02.597  3086  3097 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 18:42:02.598  3086  3846 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 18:42:02.599  3086  3086 D BluetoothMap: Proxy object connected
,11-04 18:42:02.599  3086  3097 D BluetoothPan: onBluetoothStateChange on: true
11-04 18:42:02.599  3086  3086 D MapProfile: Bluetooth service connected
11-04 18:42:02.599  3086  3086 D BluetoothMap: getConnectedDevices()
11-04 18:42:02.599  5628  5628 D BluetoothMap: Proxy object connected
11-04 18:42:02.600  5628  5628 D MapProfile: Bluetooth service connected
11-04 18:42:02.600  5628  5628 D BluetoothMap: getConnectedDevices()
11-04 18:42:02.601  5628  5639 D BluetoothPan: onBluetoothStateChange on: true
11-04 18:42:02.602  3086  3086 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 18:42:02.602  3086  3086 D PanProfile: Bluetooth service connected
,11-04 18:42:02.603  5628  5641 D BluetoothPbap: onBluetoothStateChange: up=true
,11-04 18:42:02.604  5801  5801 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 18:42:02.604  5801  5801 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 18:42:02.604  5628  5639 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 18:42:02.606  5801  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 18:42:02.606  5628  5641 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 18:42:02.607  5801  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 18:42:02.607   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 18:42:02.608   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 18:42:02.608   925   925 D BluetoothA2dp: Proxy object connected
11-04 18:42:02.608  5628  5639 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 18:42:02.609  3086  3099 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 18:42:02.609  5801  5801 D ObexServerSockets: Succeed to create listening sockets 
11-04 18:42:02.609  5801  5801 D ObexServerSockets0: startAccept()
11-04 18:42:02.609  5801  5801 D ObexServerSockets0: prepareForNewConnect()
11-04 18:42:02.611  5628  5628 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 18:42:02.611  5628  5628 D PanProfile: Bluetooth service connected
11-04 18:42:02.611  5628  5628 D BluetoothA2dp: Proxy object connected
,11-04 18:42:02.611   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 18:42:02.612  5801  5801 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 18:42:02.612  5801  5801 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 18:42:02.614  5801  5839 D ObexServerSockets0: Accepting socket connection...
11-04 18:42:02.614  5801  5840 D ObexServerSockets0: Accepting socket connection...
11-04 18:42:02.614  5801  5801 D BluetoothMapService: onReceive
11-04 18:42:02.614  3086  3086 D BluetoothInputDevice: Proxy object connected
11-04 18:42:02.614  5801  5801 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 18:42:02.614  3086  3086 D HidProfile: Bluetooth service connected
,11-04 18:42:02.614  5801  5801 D BluetoothMapService: STATE_ON
,11-04 18:42:02.617  5801  5841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 18:42:02.618  5801  5841 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 18:42:02.619  5801  5841 D BluetoothSdpJni: SDP Create record success - handle: 1
11-04 18:42:02.619  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 18:42:02.621  5628  5628 D BluetoothInputDevice: Proxy object connected
,11-04 18:42:02.621  5628  5628 D HidProfile: Bluetooth service connected
,11-04 18:42:02.624  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 18:42:02.625  5628  5628 D DockEventReceiver: finishStartingService: stopping service
,11-04 18:42:02.631  5628  5628 D BluetoothPbap: Proxy object connected
,11-04 18:42:02.631  5628  5628 D PbapServerProfile: Bluetooth service connected
,11-04 18:42:02.639  5801  5845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 18:42:02.642  3086  3086 D BluetoothPbap: Proxy object connected
,11-04 18:42:02.642  3086  3086 D PbapServerProfile: Bluetooth service connected
,11-04 18:42:02.648  5801  5801 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 18:42:02.648  5801  5801 D ObexServerSockets0: prepareForNewConnect()
,11-04 18:42:02.652  5801  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 18:42:02.653  5801  5849 I BtOppRfcommListener: Accept thread started.
,11-04 18:42:02.696   925   925 D BluetoothHeadset: Proxy object connected
,11-04 18:42:02.696  3086  3846 D BluetoothHeadset: Proxy object connected
11-04 18:42:02.696  3086  3086 D HeadsetProfile: Bluetooth service connected
11-04 18:42:02.696   925   925 D BluetoothHeadset: Proxy object connected
11-04 18:42:02.696   925   925 D BluetoothHeadset: Proxy object connected
11-04 18:42:02.696  3774  3798 D BluetoothHeadset: Proxy object connected
11-04 18:42:02.697  5628  5838 D BluetoothHeadset: Proxy object connected
11-04 18:42:02.697  3774  3800 D BluetoothHeadset: Proxy object connected
,11-04 18:42:02.698  3086  3099 D BluetoothHeadset: Proxy object connected
,11-04 18:42:02.700  5628  5628 D HeadsetProfile: Bluetooth service connected
,11-04 18:42:02.700  3086  3086 D HeadsetProfile: Bluetooth service connected
,11-04 18:42:02.709   925   942 D BluetoothHeadset: Proxy object connected
,11-04 18:42:02.709  5628  5641 D BluetoothHeadset: Proxy object connected
11-04 18:42:02.710  5628  5628 D HeadsetProfile: Bluetooth service connected
,11-04 18:42:05.025  3712  4406 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-04 18:42:06.585  5570  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 18:42:06.585  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:42:06.585  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:42:06.585  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 18:42:06.585  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 18:42:06.585  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 18:42:06.585  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 18:42:06.585  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 18:42:06.591  5570  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 18:42:06.592  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:42:06.592  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@90e475e removed from the list
11-04 18:42:06.593  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:42:06.595  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:42:06.595  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@721e80c added. We now have 4 listener(s)
,11-04 18:42:06.595  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 18:42:06.598   925  3118 D WifiService: setWifiEnabled: false pid=5570, uid=10077
,11-04 18:42:06.599   925  3118 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 18:42:11.608  5570  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 18:42:11.609   925  3564 D WifiService: setWifiEnabled: true pid=5570, uid=10077
11-04 18:42:11.609   925  3564 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 18:42:11.620   506   919 D SoftapController: Softap fwReload - Ok
,11-04 18:42:11.626   506   919 D CommandListener: Setting iface cfg
11-04 18:42:11.626   506   919 D CommandListener: Trying to bring down wlan0
11-04 18:42:11.627   506   919 D CommandListener: Clearing all IP addresses on wlan0
,11-04 18:42:11.633   925  2941 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 18:42:12.129   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:42:12.314   925  2941 D wifi    : set interface wlan0 flags (UP)
,11-04 18:42:12.315   925  2941 I WifiHAL : Initializing wifi
,11-04 18:42:12.316   925  2941 I WifiHAL : Creating socket
,11-04 18:42:12.321   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 18:42:12.323   925  2941 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-04 18:42:12.323   925  2941 D wifi    : Did set static halHandle = 0x7f59ee1400
,11-04 18:42:12.323   925  2941 D wifi    : halHandle = 0x7f59ee1400, mVM = 0x7f7658d140, mCls = 0x1606
,11-04 18:42:12.323   925  2941 D wifi    : array field set
11-04 18:42:12.324   925  2941 I WifiNative-HAL: interface[0] = wlan0
,11-04 18:42:12.326   925  5854 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546969621504
11-04 18:42:12.327   925  5854 D wifi    : waitForHalEvents called, vm = 0x7f7658d140, obj = 0x1606, env = 0x7f59efb700
,11-04 18:42:12.390  5855  5855 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 18:42:12.428   925  2941 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 18:42:12.462  5855  5855 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 18:42:12.538  5855  5855 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-04 18:42:12.538  5855  5855 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 18:42:12.564   925  2941 D WifiConfigStore: Loading config and enabling all networks 
,11-04 18:42:12.587   925  2941 D WifiConfigStore: loaded 0 passpoint configs
,11-04 18:42:12.589   925  2941 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-04 18:42:12.589   925  2941 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-04 18:42:12.590   925  2941 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-04 18:42:12.590   925  2941 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-04 18:42:12.591   925  2941 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-04 18:42:12.592   925  2941 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 18:42:12.592   925  2941 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-04 18:42:12.592   925  2941 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 18:42:12.592   925  2941 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-04 18:42:12.592   925  2941 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-04 18:42:12.592   925  2941 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 18:42:12.592   925  2941 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 18:42:12.596   925  2941 D WifiNative-HAL: Setting external_sim to 1
,11-04 18:42:12.596  4479  4479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 18:42:12.596   925  2941 D wifi    : setting dfs flag to true, 0x7f5db31ea0
,11-04 18:42:12.597   925  2941 D WifiStateMachine: Setting OUI to DA-A1-19
,11-04 18:42:12.597   925  2941 D wifi    : setting scan oui 0x7f5db31ea0
11-04 18:42:12.597   925  2941 D WifiHAL : Sending mac address OUI
,11-04 18:42:12.602   925  2941 E native  : do suspend true
,11-04 18:42:12.610   925  2941 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-04 18:42:12.610   925   925 D RttService: SCAN_AVAILABLE : 3
11-04 18:42:12.610   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-04 18:42:12.611   925  3051 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 18:42:12.611   506   919 D CommandListener: Setting iface cfg
,11-04 18:42:12.622   925  2933 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
11-04 18:42:12.622   925  2933 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 18:42:12.630   925  2933 D WifiNative-HAL: p2pGetDeviceAddress
11-04 18:42:12.630   925  2933 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 18:42:12.636   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164685 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,11-04 18:42:13.132   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:42:14.134   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:42:15.135   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:42:15.770  5855  5855 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 18:42:15.801   925  2941 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 18:42:15.810   925  2941 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,11-04 18:42:15.810   925  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 18:42:15.826   925  2941 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 18:42:15.874   925  2941 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 18:42:16.136   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:42:16.209  5855  5855 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 18:42:16.243  5855  5855 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 18:42:16.243  5855  5855 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 18:42:16.254   925  2941 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 18:42:16.255   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 18:42:16.254   925  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 18:42:16.280   925  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 18:42:16.292   506   919 D CommandListener: Setting iface cfg
,11-04 18:42:16.298   925  2941 D WifiStateMachine: Start Dhcp Watchdog 3
,11-04 18:42:16.301   925  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-04 18:42:16.306   925  5860 D DhcpClient: Receive thread started
,11-04 18:42:16.390   925  2941 E native  : do suspend false
,11-04 18:42:16.404   925  5859 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 18:42:16.419   925  5860 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-04 18:42:16.420   925  5859 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-04 18:42:16.422   925  5859 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 18:42:16.437   925  5860 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 18:42:16.438   925  5859 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 18:42:16.441   506   919 D CommandListener: Setting iface cfg
,11-04 18:42:16.445   925  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 18:42:16.449   925  2941 E native  : do suspend true
,11-04 18:42:16.450   925  5859 D DhcpClient: Scheduling renewal in 86399s
,11-04 18:42:16.474   925  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 18:42:16.476   925  2941 D WifiConfigStore: No blacklist allowed without epno enabled
,11-04 18:42:16.477   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-04 18:42:16.478   925  2943 D ConnectivityService: Adding iface wlan0 to network 102
11-04 18:42:16.487   925  2941 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 18:42:16.538   925  2943 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-04 18:42:16.538   925  2943 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-04 18:42:16.540   925  2943 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-04 18:42:16.542   925  2943 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-04 18:42:16.545   925  2943 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-04 18:42:16.552   925  2943 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-04 18:42:16.555   925  2943 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-04 18:42:16.556   925  2943 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-04 18:42:16.556   925  2943 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-04 18:42:16.556   925  2941 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 18:42:16.556   925  2943 D ConnectivityService:    accepting network in place of null
11-04 18:42:16.556   925  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 18:42:16.556   925  2943 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 18:42:16.574   925  5858 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168622, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 18:42:16.580   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 18:42:16.602   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 18:42:16.608   925  2943 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-04 18:42:16.608   925  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 18:42:16.608  3727  3852 W QCNEJ   : |CORE| network available: 102
11-04 18:42:16.609   925  2943 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-04 18:42:16.611  3727  3852 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-04 18:42:16.612  3727  3852 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 18:42:16.613  3727  3852 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-04 18:42:16.614   925   942 D Tethering: MasterInitialState.processMessage what=3
,11-04 18:42:16.623  3953  3953 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 18:42:16.625  3935  3935 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-04 18:42:16.626  5570  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 18:42:16.626  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 18:42:16.626  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 18:42:16.626  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 18:42:16.626  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 18:42:16.626  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 18:42:16.626  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 18:42:16.626  5570  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 18:42:16.627  3953  3953 D SystemUpdateService: onCreate
11-04 18:42:16.628  5570  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 18:42:16.628  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.628  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@721e80c removed from the list
11-04 18:42:16.628  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:42:16.631  5570  5617 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-04 18:42:16.632  3953  3953 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-04 18:42:16.632  5570  5617 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-04 18:42:16.634  5570  5617 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5d7ec99 Bundle[{}]
,11-04 18:42:16.634  5570  5617 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-04 18:42:16.635  5570  5617 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-04 18:42:16.635  5570  5617 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-04 18:42:16.636  5570  5617 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 18:42:16.636  5570  5617 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-04 18:42:16.637  5570  5617 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 18:42:16.643  3953  3953 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 18:42:16.644  5570  5617 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
11-04 18:42:16.644  5570  5617 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-04 18:42:16.644  5570  5617 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-04 18:42:16.646  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 18:42:16.646  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ba555 added. We now have 3 listener(s)
11-04 18:42:16.648  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 18:42:16.648  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 18:42:16.648  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:42:16.648  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:42:16.648  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f37b6a added. We now have 4 listener(s)
11-04 18:42:16.648  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 18:42:16.649  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 18:42:16.650  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 18:42:16.650  3953  4204 I iu.UploadsManager: num queued entries: 0
,11-04 18:42:16.650  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@642085b added. We now have 4 listener(s)
11-04 18:42:16.651  3953  4204 I iu.UploadsManager: num updated entries: 0
,11-04 18:42:16.652  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:42:16.652  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 18:42:16.652  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:42:16.652  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:42:16.652  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0b78f8 added. We now have 5 listener(s)
11-04 18:42:16.652  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 18:42:16.652  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:42:16.653  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:42:16.653  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:42:16.653  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:42:16.653  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 18:42:16.653  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:42:16.653  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ba555 removed from the list
11-04 18:42:16.654  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.654  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f37b6a removed from the list
11-04 18:42:16.654  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 18:42:16.654  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.655   925  5857 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 18:42:16.655  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.655  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.655  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.655  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:42:16.655  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:42:16.656  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.656  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f37b6a not in the list
11-04 18:42:16.656  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.657  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.657  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.657  3953  5869 I SystemUpdateService: active receiver: enabled
11-04 18:42:16.657  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.657  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:42:16.657  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:42:16.657  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.657  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0b78f8 removed from the list
11-04 18:42:16.658  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:42:16.658  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:42:16.658  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:42:16.658  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@642085b removed from the list
,11-04 18:42:16.658  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 18:42:16.658  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8e41d1 added. We now have 3 listener(s)
,11-04 18:42:16.659  3953  3953 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 18:42:16.660  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:42:16.660  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 18:42:16.660  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:42:16.660  3953  3953 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-04 18:42:16.660  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:42:16.660  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645e436 added. We now have 4 listener(s)
11-04 18:42:16.661  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 18:42:16.661  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 18:42:16.662  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 18:42:16.662  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0ecf37 added. We now have 4 listener(s)
,11-04 18:42:16.663  5666  5666 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-04 18:42:16.663  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:42:16.663  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 18:42:16.663  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:42:16.663  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:42:16.663  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fb2ca4 added. We now have 5 listener(s)
11-04 18:42:16.663  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 18:42:16.663  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 18:42:16.663  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 18:42:16.663  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 18:42:16.663  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 18:42:16.664  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 18:42:16.664  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 18:42:16.666  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-04 18:42:16.666  5570  5617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 18:42:16.666  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 18:42:16.667  5666  5666 D SprintDMHelper: simOperator: 
11-04 18:42:16.668  5666  5666 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-04 18:42:16.668  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.668  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 18:42:16.668  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 18:42:16.668  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-04 18:42:16.668  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 18:42:16.672  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.672  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 18:42:16.672  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 18:42:16.672  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 18:42:16.672  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 18:42:16.672  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.672  5570  5617 D BluetoothAdapter: STATE_ON
,11-04 18:42:16.674  3953  4204 I iu.SyncManager: NEXT; no task
11-04 18:42:16.674  5801  5811 D BtGatt.GattService: registerClient() - UUID=5633baa0-f5e9-4c3c-a32d-a6fae4c9fde6
11-04 18:42:16.675  5801  5817 D BtGatt.GattService: onClientRegistered() - UUID=5633baa0-f5e9-4c3c-a32d-a6fae4c9fde6, clientIf=5
,11-04 18:42:16.676  5570  5581 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 18:42:16.676  5801  5830 D BtGatt.GattService: start scan with filters
11-04 18:42:16.677  3953  5869 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-04 18:42:16.679  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 18:42:16.679  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.679  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 18:42:16.679  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.679  5801  5820 D BtGatt.ScanManager: handling starting scan
11-04 18:42:16.679  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-04 18:42:16.680  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 18:42:16.680  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 18:42:16.680  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 18:42:16.680  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 18:42:16.680  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.680  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.680  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 18:42:16.680  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 18:42:16.680  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.681  5801  5820 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a8012
11-04 18:42:16.682  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.682  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 18:42:16.682  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.682  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.682  5570  5617 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 18:42:16.682  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.682  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 18:42:16.682  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 18:42:16.683  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 18:42:16.683  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 18:42:16.683  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:42:16.683  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 18:42:16.685  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.685  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.686  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.686  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.686  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 18:42:16.686  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 18:42:16.686  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is disc,overing: true, is advertising: false
11-04 18:42:16.686  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 18:42:16.686  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.686  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.686  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.686  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 18:42:16.686  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.686  5570  5617 D BluetoothAdapter: STATE_ON
,11-04 18:42:16.687  5801  5812 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 18:42:16.687  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 18:42:16.688  5570  5617 D BluetoothAdapter: STATE_ON
11-04 18:42:16.688  5801  5817 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 18:42:16.688  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.689  5801  5811 D BtGatt.GattService: stopScan() - queue size =1
11-04 18:42:16.689  5801  5820 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 18:42:16.689  5801  5830 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 18:42:16.690  3953  5869 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-04 18:42:16.690  3953  5869 I SystemUpdateService: now status is 0 (complete)
11-04 18:42:16.690  3953  5869 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-04 18:42:16.690  3953  5869 I SystemUpdateService: file has been verified
11-04 18:42:16.690  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 18:42:16.690  3953  5869 I SystemUpdateService: OTA package size = 21989297
11-04 18:42:16.690  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.690  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 18:42:16.690  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.690  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.690  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.690  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.690  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 18:42:16.690  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.691  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.691  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.691  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 18:42:16.691  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 18:42:16.691  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 18:42:16.692  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.693  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.693  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:42:16.693  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.693  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.693  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:42:16.693  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 18:42:16.693  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 18:42:16.693  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.693  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 18:42:16.693  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 18:42:16.693  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.693  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.693  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 18:42:16.693  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 18:42:16.695  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:42:16.695  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:42:16.695  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:42:16.695  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:42:16.695  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:42:16.695  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:42:16.695  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.695  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 18:42:16.695  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8e41d1 removed from the list
,11-04 18:42:16.695  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.695  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.695  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.695  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.695  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645e436 removed from the list
11-04 18:42:16.695  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:42:16.696  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.696  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.696  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:42:16.696  5801  5820 D BtGatt.ScanManager: Starting BLE batch scan
11-04 18:42:16.696  5801  5820 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 18:42:16.696  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.696  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.696  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.696  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:42:16.696  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:42:16.696  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.696  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645e436 not in the list
11-04 18:42:16.696  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.698  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.698  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.698  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.698  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:42:16.698  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:42:16.698  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.698  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fb2ca4 removed from the list
11-04 18:42:16.698  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:42:16.698  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:42:16.698  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:42:16.698  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0ecf37 removed from the list
11-04 18:42:16.699  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 18:42:16.699  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8365a09 added. We now have 3 listener(s)
,11-04 18:42:16.699  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 18:42:16.700  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 18:42:16.700  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:42:16.700  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:42:16.700  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89440e added. We now have 4 listener(s)
11-04 18:42:16.700  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 18:42:16.700  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 18:42:16.701  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 18:42:16.701  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2f added. We now have 4 listener(s)
,11-04 18:42:16.702  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:42:16.702  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 18:42:16.702  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 18:42:16.702  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 18:42:16.702  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f56c3c added. We now have 5 listener(s)
11-04 18:42:16.702  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 18:42:16.702  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 18:42:16.702  3953  5869 I SystemUpdateService: showing system update notification
11-04 18:42:16.702  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 18:42:16.702  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 18:42:16.702  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 18:42:16.702  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 18:42:16.702  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 18:42:16.703  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 18:42:16.704  5801  5817 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 18:42:16.704  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.704   925  5857 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 17:42:16 GMT], X-Android-Received-Millis=[1478281336703], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478281336680]}
11-04 18:42:16.705   925  2943 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 18:42:16.705   925  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-04 18:42:16.705   925  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-04 18:42:16.706   925  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-04 18:42:16.706  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 18:42:16.706  5570  5617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 18:42:16.706  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 18:42:16.708  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 18:42:16.708  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:42:16.709  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.709  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 18:42:16.710  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 18:42:16.710  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 18:42:16.710  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 18:42:16.710  5801  5820 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 18:42:16.712  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.712  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 18:42:16.712  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 18:42:16.712  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-04 18:42:16.712  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 18:42:16.712  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.713  5570  5617 D BluetoothAdapter: STATE_ON
11-04 18:42:16.713  5801  5817 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 18:42:16.713  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.714  5801  5817 E BtGatt.ContextMap: Context not found for ID 5
11-04 18:42:16.714  5801  5812 D BtGatt.GattService: registerClient() - UUID=5966a005-d567-4b0a-8bae-55e3cf463dbf
11-04 18:42:16.715  5801  5817 D BtGatt.GattService: onClientRegistered() - UUID=5966a005-d567-4b0a-8bae-55e3cf463dbf, clientIf=5
11-04 18:42:16.715  5570  5874 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 18:42:16.715  5801  5830 D BtGatt.GattService: start scan with filters
11-04 18:42:16.717  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 18:42:16.717  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.717  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 18:42:16.717  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.717  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 18:42:16.717  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 18:42:16.717  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.717  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 18:42:16.717  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 18:42:16.717  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.717  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.717  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 18:42:16.718  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 18:42:16.718  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.719  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 18:42:16.719  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.719  5801  5820 D BtGatt.ScanManager: stopping BLe Batch
11-04 18:42:16.719  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.719  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 18:42:16.719  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.719  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.719  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-04 18:42:16.719  5570  5617 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 18:42:16.720  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:42:16.720  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.720  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:42:16.720  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:42:16.720  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:42:16.720  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 18:42:16.720  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 18:42:16.720  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:42:16.720  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:42:16.720  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8365a09 removed from the list
11-04 18:42:16.720  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.720  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89440e removed from the list
11-04 18:42:16.720  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:42:16.720  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 18:42:16.720  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 18:42:16.720  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-04 18:42:16.720  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-04 18:42:16.720  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 18:42:16.720  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 18:42:16.720  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.721   925   925 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-04 18:42:16.722  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.722  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.722  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.722  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:42:16.722  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:42:16.722  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.723  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89440e not in the list
11-04 18:42:16.723  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-04 18:42:16.723  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.723  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.723  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.723  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 18:42:16.723  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 18:42:16.724  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 18:42:16.724  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 18:42:16.724  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.724  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.724  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.724  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 18:42:16.724  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.725  5570  5617 D BluetoothAdapter: STATE_ON
11-04 18:42:16.725  5801  5811 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 18:42:16.725  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 18:42:16.726  5570  5617 D BluetoothAdapter: STATE_ON
11-04 18:42:16.726  5801  5837 D BtGatt.GattService: stopScan() - queue size =0
11-04 18:42:16.727  5801  5811 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 18:42:16.727  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 18:42:16.727  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 18:42:16.727  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.727  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.727  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 18:42:16.727  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.727  5801  5820 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 18:42:16.727  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.728  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.728  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.728  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 18:42:16.728  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.728  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.728  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.728  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 18:42:16.728  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 18:42:16.728  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 18:42:16.729  3953  3953 D SystemUpdateService: onDestroy
11-04 18:42:16.729  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.730  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.730  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:42:16.730  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.730  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.730  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:42:16.730  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:42:16.730  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.730  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 18:42:16.730  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f56c3c removed from the list
11-04 18:42:16.730  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:42:16.731  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:42:16.731  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:42:16.731  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 18:42:16.731  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:42:16.731  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.731  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2f removed from the list
11-04 18:42:16.731  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 18:42:16.731  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 18:42:16.731  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.731  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.731  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 18:42:16.731  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.731  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 18:42:16.731  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5524141 added. We now have 3 listener(s)
11-04 18:42:16.732  5801  5817 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 18:42:16.732  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.732  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.732  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.732  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.732  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.732  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:42:16.732  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:42:16.733  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 18:42:16.733  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:42:16.733  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:42:16.733  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2dc6e6 added. We now have 4 listener(s)
11-04 18:42:16.733  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 18:42:16.733  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 18:42:16.733  5801  5820 D BtGatt.ScanManager: handling starting scan
11-04 18:42:16.734  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 18:42:16.734  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afbf427 added. We now have 4 listener(s)
11-04 18:42:16.735  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:42:16.736  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 18:42:16.736  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:42:16.736  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:42:16.736  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed506d4 added. We now have 5 listener(s)
11-04 18:42:16.736  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 18:42:16.736  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 18:42:16.736  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 18:42:16.736  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 18:42:16.736  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 18:42:16.736  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 18:42:16.737  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 18:42:16.739  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 18:42:16.739  5570  5617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-04 18:42:16.739  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 18:42:16.740  5801  5817 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 18:42:16.740  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.740  5801  5820 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 18:42:16.745  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 18:42:16.745  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:42:16.745  5801  5820 D BtGatt.ScanManager: Starting BLE batch scan
11-04 18:42:16.745  5801  5820 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 18:42:16.746  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.746  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 18:42:16.746  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 18:42:16.747  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 18:42:16.747  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 18:42:16.749  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.749  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 18:42:16.749  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-04 18:42:16.749  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 18:42:16.749  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 18:42:16.749  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.750  5570  5617 D BluetoothAdapter: STATE_ON
,11-04 18:42:16.753  5801  5812 D BtGatt.GattService: registerClient() - UUID=585e9b5b-38b6-413d-8256-b05808376aff
11-04 18:42:16.753  5801  5817 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 18:42:16.753  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:42:16.754  5801  5817 D BtGatt.GattService: onClientRegistered() - UUID=585e9b5b-38b6-413d-8256-b05808376aff, clientIf=5
11-04 18:42:16.754  5570  5580 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 18:42:16.754  5801  5811 D BtGatt.GattService: start scan with filters
11-04 18:42:16.757  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 18:42:16.757  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.758  5801  5820 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 18:42:16.759  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 18:42:16.759  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.759  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 18:42:16.759  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.759  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 18:42:16.759  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-04 18:42:16.759  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.759  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 18:42:16.759  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 18:42:16.759  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.759  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.759  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 18:42:16.760  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 18:42:16.760  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.762  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.762  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 18:42:16.762  5801  5817 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 18:42:16.762  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.762  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.762  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.762  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 18:42:16.765  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:42:16.765  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:42:16.765  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:42:16.765  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:42:16.765  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 18:42:16.765  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 18:42:16.765  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:42:16.765  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:42:16.765  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5524141 removed from the list
11-04 18:42:16.765  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.765  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2dc6e6 removed from the list
11-04 18:42:16.765  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
11-04 18:42:16.765  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 18:42:16.765  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 18:42:16.765  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-04 18:42:16.766  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-04 18:42:16.766  5570  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 18:42:16.766  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 18:42:16.766  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.766  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.766  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-04 18:42:16.766  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.766  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.766  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 18:42:16.766  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.766  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.767  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.767  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.767  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:42:16.767  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:42:16.767  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.767  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2dc6e6 not in the list
11-04 18:42:16.767  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-04 18:42:16.767  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 18:42:16.767  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 18:42:16.767  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.767  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.767  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.767  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 18:42:16.767  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-04 18:42:16.768  5570  5617 D BluetoothAdapter: STATE_ON
,11-04 18:42:16.768  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 18:42:16.768  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.768  5801  5820 D BtGatt.ScanManager: stopping BLe Batch
11-04 18:42:16.768  5801  5811 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 18:42:16.769  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 18:42:16.769  5570  5617 D BluetoothAdapter: STATE_ON
11-04 18:42:16.770  5801  5837 D BtGatt.GattService: stopScan() - queue size =0
,11-04 18:42:16.770  5801  5830 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.771  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 18:42:16.771  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 18:42:16.772  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 18:42:16.772  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.773  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 18:42:16.773  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.773  5801  5820 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 18:42:16.773  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.773  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:42:16.773  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.773  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.773  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:42:16.773  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:42:16.773  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.773  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:42:16.773  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed506d4 removed from the list
11-04 18:42:16.774  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:42:16.774  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 18:42:16.774  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:42:16.774  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:42:16.774  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 18:42:16.774  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.774  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afbf427 removed from the list
11-04 18:42:16.774  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 18:42:16.774  5570  5570 D org.thaliproject.p2p.btconnectorlib.intern,al.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 18:42:16.774  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.774  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.774  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 18:42:16.774  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.774  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 18:42:16.774  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7acd779 added. We now have 3 listener(s)
11-04 18:42:16.775  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.775  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.775  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.775  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 18:42:16.775  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 18:42:16.775  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:42:16.775  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 18:42:16.775  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:42:16.776  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 18:42:16.776  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed4ccbe added. We now have 4 listener(s)
11-04 18:42:16.776  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 18:42:16.776  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 18:42:16.777  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 18:42:16.777  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff1411f added. We now have 4 listener(s)
11-04 18:42:16.778  5801  5817 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 18:42:16.778  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.778  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 18:42:16.778  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 18:42:16.778  5570  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 18:42:16.778  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 18:42:16.778  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88a5c6c added. We now have 5 listener(s)
11-04 18:42:16.778  5570  5617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 18:42:16.778  5570  5617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 18:42:16.779  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 18:42:16.779  5570  5617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 18:42:16.779  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:42:16.779  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:42:16.779  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:42:16.779  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7acd779 removed from the list
11-04 18:42:16.779  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.779  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed4ccbe removed from the list
,11-04 18:42:16.779  5570  5617 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 18:42:16.779  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.779  5801  5820 D BtGatt.ScanManager: handling starting scan
11-04 18:42:16.780  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.780  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.780  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.780  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:42:16.780  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:42:16.780  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 18:42:16.780  5570  5617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed4ccbe not in the list
11-04 18:42:16.780  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.782  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.782  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.782  5570  5617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 18:42:16.782  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 18:42:16.782  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 18:42:16.782  5570  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 18:42:16.782  5570  5617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88a5c6c removed from the list
,11-04 18:42:16.782  5570  5617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 18:42:16.782  5570  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 18:42:16.782  5570  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 18:42:16.782  5570  5617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff1411f removed from the list
11-04 18:42:16.783  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-04 18:42:16.783  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 18:42:16.783  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 18:42:16.783  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 18:42:16.783  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,11-04 18:42:16.783  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 18:42:16.784  5801  5817 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 18:42:16.784  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.785  5801  5820 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 18:42:16.789  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 18:42:16.789  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.789  5801  5820 D BtGatt.ScanManager: Starting BLE batch scan
11-04 18:42:16.789  5801  5820 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 18:42:16.798  5801  5817 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-04 18:42:16.798  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:42:16.803  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 18:42:16.803  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:42:16.804  5801  5820 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 18:42:16.809  5801  5817 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 18:42:16.809  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.809  5801  5817 E BtGatt.ContextMap: Context not found for ID 5
,11-04 18:42:16.814  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 18:42:16.814  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.814  5801  5820 D BtGatt.ScanManager: stopping BLe Batch
,11-04 18:42:16.818  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 18:42:16.819  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 18:42:16.819  5801  5820 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 18:42:16.823  5801  5817 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 18:42:16.823  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 18:42:17.136   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-04 18:42:17.196  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 18:42:17.233  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 18:42:17.276  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 18:42:18.957  5570  5878 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 18:42:18.957  5570  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 18:42:19.751  5570  5878 W !!      : call onHalfStreamCopied
11-04 18:42:19.751  5570  5878 I testCopyDataAndClose: closing input stream
,11-04 18:42:20.007  3550  5880 I VacuumService: Vacuum at: now=1478281340007 tag=VacuumService
,11-04 18:42:20.055  3550  5883 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-04 18:42:20.085  3550  5881 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-04 18:42:20.088  3550  5881 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-04 18:42:20.110  3550  5881 W Uploader:  no longer exists, so no auth token.
,11-04 18:42:20.116  3550  5883 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 18:42:20.431  3550  5885 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 18:42:20.523  5570  5878 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 18:42:20.523  5570  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 18:42:20.523  5570  5878 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 18:42:20.523  5570  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 18:42:20.523  5570  5878 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 18:42:20.523  5570  5878 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 18:42:20.523  5570  5878 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 18:42:20.523  5570  5878 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 18:42:20.523  5570  5878 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 18:42:20.524  5570  5878 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 18:42:20.524  5570  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 18:42:20.587  3550  5881 W Uploader:  no longer exists, so no auth token.
,11-04 18:42:20.592  3550  5883 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 18:42:20.668  3550  5885 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 18:42:20.748  3550  5883 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 18:42:20.833  3550  5885 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 18:42:24.561   925  2943 D ConnectivityService: handlePromptUnvalidated 102
,11-04 18:42:24.778  5570  5890 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-04 18:42:24.778  5570  5890 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 18:42:26.778  5570  5617 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-04 18:42:26.778  5570  5617 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 18:42:26.778  5570  5617 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-04 18:42:26.800  5570  5890 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
11-04 18:42:26.801  5570  5890 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-04 18:42:26.801  5570  5890 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-04 18:42:26.929  5570  5891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 18:42:26.929  5570  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 18:42:28.554  5570  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 18:42:32.715  5570  5892 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-04 18:42:32.715  5570  5892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 18:42:32.715  5570  5892 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-04 18:42:32.715  5570  5892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 18:42:32.715  5570  5892 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 18:42:32.715  5570  5892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 18:42:32.715  5570  5892 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 18:42:32.716  5570  5892 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 18:42:32.716  5570  5892 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 18:42:32.716  5570  5892 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-04 18:42:32.716  5570  5892 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 18:42:32.716  5570  5892 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-04 18:42:32.716  5570  5892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-04 18:42:32.718  5570  5617 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-04 18:42:32.721  5570  5893 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 18:42:32.721  5570  5893 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 18:42:32.722  5570  5893 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-04 18:42:32.722  5570  5893 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 18:42:32.722  5570  5893 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-04 18:42:32.722  5570  5893 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-04 18:42:32.722  5570  5893 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 18:42:32.722  5570  5893 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-04 18:42:32.727  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-04 18:42:32.727  5570  5617 I jxcore-log: 
,11-04 18:42:32.728  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-04 18:42:32.728  5570  5617 I jxcore-log: 
11-04 18:42:32.728  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-04 18:42:32.728  5570  5617 I jxcore-log: 
11-04 18:42:32.728  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-04 18:42:32.728  5570  5617 I jxcore-log: 
11-04 18:42:32.729  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG UnitTest_app: 'Total duration:  91679'
11-04 18:42:32.729  5570  5617 I jxcore-log: 
11-04 18:42:32.731  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-04 18:42:32.731  5570  5617 I jxcore-log: 
,11-04 18:42:32.734  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 18:42:32.734  5570  5617 I jxcore-log: 
,11-04 18:42:32.735  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 18:42:32.735  5570  5617 I jxcore-log: 
11-04 18:42:32.735  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 18:42:32.735  5570  5617 I jxcore-log: 
11-04 18:42:32.736  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-04 18:42:32.736  5570  5617 I jxcore-log: 
11-04 18:42:32.736  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 18:42:32.736  5570  5617 I jxcore-log: 
,11-04 18:42:32.736  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 18:42:32.736  5570  5617 I jxcore-log: 
11-04 18:42:32.736  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 18:42:32.736  5570  5617 I jxcore-log: 
11-04 18:42:32.736  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 18:42:32.736  5570  5617 I jxcore-log: 
11-04 18:42:32.737  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 18:42:32.737  5570  5617 I jxcore-log: 
11-04 18:42:32.737  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 18:42:32.737  5570  5617 I jxcore-log: 
11-04 18:42:32.737  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-04 18:42:32.737  5570  5617 I jxcore-log: 
,11-04 18:42:32.738  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 18:42:32.738  5570  5617 I jxcore-log: 
11-04 18:42:32.738  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 18:42:32.738  5570  5617 I jxcore-log: 
11-04 18:42:32.738  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 18:42:32.738  5570  5617 I jxcore-log: 
11-04 18:42:32.738  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 18:42:32.738  5570  5617 I jxcore-log: 
,11-04 18:42:32.738  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 18:42:32.738  5570  5617 I jxcore-log: 
11-04 18:42:32.739  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 18:42:32.739  5570  5617 I jxcore-log: 
11-04 18:42:32.739  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 18:42:32.739  5570  5617 I jxcore-log: 
,11-04 18:42:32.739  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 18:42:32.739  5570  5617 I jxcore-log: 
11-04 18:42:32.739  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 18:42:32.739  5570  5617 I jxcore-log: 
11-04 18:42:32.740  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 18:42:32.740  5570  5617 I jxcore-log: 
11-04 18:42:32.740  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 18:42:32.740  5570  5617 I jxcore-log: 
,11-04 18:42:32.740  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 18:42:32.740  5570  5617 I jxcore-log: 
11-04 18:42:32.741  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 18:42:32.741  5570  5617 I jxcore-log: 
11-04 18:42:32.742  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 18:42:32.742  5570  5617 I jxcore-log: 
11-04 18:42:32.742  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 18:42:32.742  5570  5617 I jxcore-log: 
11-04 18:42:32.743  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 18:42:32.743  5570  5617 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-04 18:42:32.743  5570  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 18:42:32.743  5570  5617 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-04 18:42:32.744  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 18:42:32.744  5570  5617 I jxcore-log: 
11-04 18:42:32.744  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 18:42:32.744  5570  5617 I jxcore-log: 
,11-04 18:42:32.744  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 18:42:32.744  5570  5617 I jxcore-log: 
11-04 18:42:32.744  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 18:42:32.744  5570  5617 I jxcore-log: 
11-04 18:42:32.744  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 18:42:32.744  5570  5617 I jxcore-log: 
11-04 18:42:32.745  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 18:42:32.745  5570  5617 I jxcore-log: 
,11-04 18:42:32.749  5570  5570 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-04 18:42:32.750  5570  5617 I jxcore-log: 2016-11-04 17:42:32 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-04 18:42:32.750  5570  5617 I jxcore-log: 
,11-04 18:42:34.862  5570  5617 I jxcore-log: 2016-11-04 17:42:34 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-04 18:42:34.862  5570  5617 I jxcore-log: 
,11-04 18:42:34.864  5570  5617 I jxcore-log: 2016-11-04 17:42:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-04 18:42:34.864  5570  5617 I jxcore-log: 
,11-04 18:42:35.218  5570  5617 I jxcore-log: 2016-11-04 17:42:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-04 18:42:35.218  5570  5617 I jxcore-log: 
,11-04 18:42:35.232  5570  5617 I jxcore-log: 2016-11-04 17:42:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-04 18:42:35.232  5570  5617 I jxcore-log: 
,11-04 18:42:36.367  5570  5617 I jxcore-log: 2016-11-04 17:42:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-04 18:42:36.367  5570  5617 I jxcore-log: 
,11-04 18:42:36.563  5570  5617 I jxcore-log: 2016-11-04 17:42:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-04 18:42:36.563  5570  5617 I jxcore-log: 
,11-04 18:42:36.568  5570  5617 I jxcore-log: 2016-11-04 17:42:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-04 18:42:36.568  5570  5617 I jxcore-log: 
,11-04 18:42:36.573  5570  5617 I jxcore-log: 2016-11-04 17:42:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-04 18:42:36.573  5570  5617 I jxcore-log: 
,11-04 18:42:36.922   925  5858 D NetlinkSocketObserver: NeighborEvent{elapsedMs=188970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-04 18:42:37.062  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-04 18:42:37.062  5570  5617 I jxcore-log: 
,11-04 18:42:37.109  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-04 18:42:37.109  5570  5617 I jxcore-log: 
,11-04 18:42:37.123  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-04 18:42:37.123  5570  5617 I jxcore-log: 
,11-04 18:42:37.127  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-04 18:42:37.127  5570  5617 I jxcore-log: 
,11-04 18:42:37.137   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:42:37.409  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-04 18:42:37.409  5570  5617 I jxcore-log: 
,11-04 18:42:37.539  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-04 18:42:37.539  5570  5617 I jxcore-log: 
,11-04 18:42:37.913  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-04 18:42:37.913  5570  5617 I jxcore-log: 
,11-04 18:42:37.921  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-04 18:42:37.921  5570  5617 I jxcore-log: 
,11-04 18:42:37.925  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-04 18:42:37.925  5570  5617 I jxcore-log: 
,11-04 18:42:37.930  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-04 18:42:37.930  5570  5617 I jxcore-log: 
,11-04 18:42:37.935  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-04 18:42:37.935  5570  5617 I jxcore-log: 
,11-04 18:42:37.963  5570  5617 I jxcore-log: 2016-11-04 17:42:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-04 18:42:37.963  5570  5617 I jxcore-log: 
,11-04 18:42:38.000  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-04 18:42:38.000  5570  5617 I jxcore-log: 
,11-04 18:42:38.008  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-04 18:42:38.008  5570  5617 I jxcore-log: 
,11-04 18:42:38.014  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-04 18:42:38.014  5570  5617 I jxcore-log: 
,11-04 18:42:38.030  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-04 18:42:38.030  5570  5617 I jxcore-log: 
,11-04 18:42:38.034  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-04 18:42:38.034  5570  5617 I jxcore-log: 
,11-04 18:42:38.040  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-04 18:42:38.040  5570  5617 I jxcore-log: 
,11-04 18:42:38.045  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-04 18:42:38.045  5570  5617 I jxcore-log: 
,11-04 18:42:38.058  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-04 18:42:38.058  5570  5617 I jxcore-log: 
,11-04 18:42:38.076  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-04 18:42:38.076  5570  5617 I jxcore-log: 
,11-04 18:42:38.090  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-04 18:42:38.090  5570  5617 I jxcore-log: 
,11-04 18:42:38.101  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-04 18:42:38.101  5570  5617 I jxcore-log: 
,11-04 18:42:38.124  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-04 18:42:38.124  5570  5617 I jxcore-log: 
,11-04 18:42:38.135  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-04 18:42:38.135  5570  5617 I jxcore-log: 
,11-04 18:42:38.138   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:42:38.148  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-04 18:42:38.148  5570  5617 I jxcore-log: 
,11-04 18:42:38.159  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-04 18:42:38.159  5570  5617 I jxcore-log: 
,11-04 18:42:38.166  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-04 18:42:38.166  5570  5617 I jxcore-log: 
,11-04 18:42:38.188  5570  5617 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-04 18:42:38.189  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - INFO testUtils: 'BLE multiple advertisement supported'
11-04 18:42:38.189  5570  5617 I jxcore-log: 
,11-04 18:42:38.275  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:38.275  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:38.275  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:38.275  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:38.275  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:38.275  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:38.275  5570  5617 I jxcore-log: 
,11-04 18:42:38.538  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:38.538  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:38.538  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:38.538  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:38.538  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:38.538  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:38.538  5570  5617 I jxcore-log: 
,11-04 18:42:38.541  5570  5617 I jxcore-log: 2016-11-04 17:42:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:38.541  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:38.541  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:38.541  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:38.541  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:38.541  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:38.541  5570  5617 I jxcore-log: 
,11-04 18:42:39.140   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:42:39.172  5570  5617 I jxcore-log: 2016-11-04 17:42:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:39.172  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:39.172  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:39.172  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:39.172  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:39.172  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:39.172  5570  5617 I jxcore-log: 
,11-04 18:42:39.175  5570  5617 I jxcore-log: 2016-11-04 17:42:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:39.175  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:39.175  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:39.175  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:39.175  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:39.175  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:39.175  5570  5617 I jxcore-log: 
,11-04 18:42:40.142   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:42:40.552  5570  5617 I jxcore-log: 2016-11-04 17:42:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:40.552  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:40.552  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:40.552  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:40.552  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:40.552  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:40.552  5570  5617 I jxcore-log: 
,11-04 18:42:40.557  5570  5617 I jxcore-log: 2016-11-04 17:42:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:40.557  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:40.557  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:40.557  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:40.557  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:40.557  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:40.557  5570  5617 I jxcore-log: 
,11-04 18:42:41.143   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 18:42:41.593  5570  5617 I jxcore-log: 2016-11-04 17:42:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:41.593  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:41.593  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:41.593  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:41.593  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:41.593  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:41.593  5570  5617 I jxcore-log: 
,11-04 18:42:41.598  5570  5617 I jxcore-log: 2016-11-04 17:42:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:41.598  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:41.598  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:41.598  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:41.598  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:41.598  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:41.598  5570  5617 I jxcore-log: 
,11-04 18:42:42.143   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 18:42:42.636  5570  5617 I jxcore-log: 2016-11-04 17:42:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:42.636  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:42.636  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:42.636  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:42.636  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:42.636  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:42.636  5570  5617 I jxcore-log: 
,11-04 18:42:42.639  5570  5617 I jxcore-log: 2016-11-04 17:42:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:42.639  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:42.639  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:42.639  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:42.639  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:42.639  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:42.639  5570  5617 I jxcore-log: 
,11-04 18:42:43.268   925  5858 D NetlinkSocketObserver: NeighborEvent{elapsedMs=195317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-04 18:42:43.671  5570  5617 I jxcore-log: 2016-11-04 17:42:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:43.671  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:43.671  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:43.671  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:43.671  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:43.671  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:43.671  5570  5617 I jxcore-log: 
,11-04 18:42:43.675  5570  5617 I jxcore-log: 2016-11-04 17:42:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:43.675  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:43.675  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:43.675  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:43.675  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:43.675  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:43.675  5570  5617 I jxcore-log: 
,11-04 18:42:44.708  5570  5617 I jxcore-log: 2016-11-04 17:42:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:44.708  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:44.708  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:44.708  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:44.708  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:44.708  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:44.708  5570  5617 I jxcore-log: 
,11-04 18:42:44.712  5570  5617 I jxcore-log: 2016-11-04 17:42:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:44.712  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:44.712  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:44.712  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:44.712  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:44.712  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:44.712  5570  5617 I jxcore-log: 
,11-04 18:42:45.743  5570  5617 I jxcore-log: 2016-11-04 17:42:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:45.743  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:45.743  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:45.743  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:45.743  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:45.743  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:45.743  5570  5617 I jxcore-log: 
,11-04 18:42:45.747  5570  5617 I jxcore-log: 2016-11-04 17:42:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:45.747  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:45.747  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:45.747  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:45.747  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:45.747  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:45.747  5570  5617 I jxcore-log: 
,11-04 18:42:46.782  5570  5617 I jxcore-log: 2016-11-04 17:42:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:46.782  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:46.782  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:46.782  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:46.782  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:46.782  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:46.782  5570  5617 I jxcore-log: 
,11-04 18:42:46.786  5570  5617 I jxcore-log: 2016-11-04 17:42:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:46.786  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:46.786  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:46.786  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:46.786  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:46.786  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:46.786  5570  5617 I jxcore-log: 
,11-04 18:42:47.865  5570  5617 I jxcore-log: 2016-11-04 17:42:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:47.865  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:47.865  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:47.865  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:47.865  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:47.865  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:47.865  5570  5617 I jxcore-log: 
,11-04 18:42:47.869  5570  5617 I jxcore-log: 2016-11-04 17:42:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:47.869  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:47.869  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:47.869  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:47.869  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:47.869  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:47.869  5570  5617 I jxcore-log: 
,11-04 18:42:48.903  5570  5617 I jxcore-log: 2016-11-04 17:42:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:48.903  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:48.903  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:48.903  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:48.903  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:48.903  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:48.903  5570  5617 I jxcore-log: 
,11-04 18:42:48.909  5570  5617 I jxcore-log: 2016-11-04 17:42:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:48.909  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:48.909  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:48.909  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:48.909  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:48.909  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:48.909  5570  5617 I jxcore-log: 
,11-04 18:42:49.936  5570  5617 I jxcore-log: 2016-11-04 17:42:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:49.936  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:49.936  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:49.936  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:49.936  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:49.936  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:49.936  5570  5617 I jxcore-log: 
,11-04 18:42:49.940  5570  5617 I jxcore-log: 2016-11-04 17:42:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:49.940  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:49.940  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:49.940  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:49.940  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:49.940  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:49.940  5570  5617 I jxcore-log: 
,11-04 18:42:50.974  5570  5617 I jxcore-log: 2016-11-04 17:42:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:50.974  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:50.974  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:50.974  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:50.974  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:50.974  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:50.974  5570  5617 I jxcore-log: 
,11-04 18:42:50.978  5570  5617 I jxcore-log: 2016-11-04 17:42:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:50.978  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:50.978  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:50.978  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:50.978  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:50.978  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:50.978  5570  5617 I jxcore-log: 
,11-04 18:42:52.012  5570  5617 I jxcore-log: 2016-11-04 17:42:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:52.012  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:52.012  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:52.012  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:52.012  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:52.012  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:52.012  5570  5617 I jxcore-log: 
,11-04 18:42:52.018  5570  5617 I jxcore-log: 2016-11-04 17:42:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:52.018  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:52.018  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:52.018  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:52.018  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:52.018  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:52.018  5570  5617 I jxcore-log: 
,11-04 18:42:53.049  5570  5617 I jxcore-log: 2016-11-04 17:42:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 18:42:53.049  5570  5617 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 18:42:53.049  5570  5617 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 18:42:53.049  5570  5617 I jxcore-log: emit@events.js:82:1
11-04 18:42:53.049  5570  5617 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 18:42:53.049  5570  5617 I jxcore-log: emit@events.js:82:1'
11-04 18:42:53.049  5570  5617 I jxcore-log: 
,11-04 18:42:53.059  5570  5617 E jxcore  : Error!: error is undefined
11-04 18:42:53.059  5570  5617 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-04 18:42:53.063  5570  5617 I jxcore-log: 2016-11-04 17:42:53 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-04 18:42:53.063  5570  5617 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-04 18:42:53.063  5570  5617 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-04 18:42:53.063  5570  5617 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-04 18:42:53.063  5570  5617 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-04 18:42:53.063  5570  5617 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-04 18:42:53.063  5570  5617 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-04 18:42:53.063  5570  5617 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-04 18:42:53.064  5570  5617 I jxcore-log: 2016-11-04 17:42:53 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-04 18:42:53.064  5570  5617 I jxcore-log: 
11-04 18:42:53.066  5570  5617 E jxcore-log: TypeError: 
11-04 18:42:53.066  5570  5617 E jxcore-log: error is undefined
,11-04 18:42:53.066  5570  5617 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-04 18:42:53.066  5570  5617 E jxcore-log: 
,11-04 18:42:53.164   925  2942 D WifiService: Client connection lost with reason: 4
11-04 18:42:53.164   925  3564 I WindowState: WIN DEATH: Window{566b425 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-04 18:42:53.165   925  3385 D GraphicsStats: Buffer count: 2
,11-04 18:42:53.178   526   526 I Zygote  : Process 5570 exited cleanly (139)
,11-04 18:42:53.180   925  3838 I ActivityManager: Process com.test.thalitest (pid 5570) has died
,11-04 18:42:53.198   925  3838 I ActivityManager: Start proc 5896:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-04 18:42:53.275  5896  5896 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-04 18:42:53.294  5896  5896 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-04 18:42:53.300  5896  5896 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5346-5348)
11-04 18:42:53.300  5896  5896 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 18:42:53.309  5896  5896 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ef533ba}
,11-04 18:42:53.309  5896  5896 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 18:42:53.309  5896  5896 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 18:42:53.312  5896  5896 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 18:42:53.313  5896  5896 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 18:42:53.322  5896  5896 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 18:42:53.330  5896  5896 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 18:42:53.330  5896  5896 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 18:42:53.330  5896  5896 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 18:42:53.330  5896  5896 I Adreno  : Build Date                       : 12/06/15
11-04 18:42:53.330  5896  5896 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 18:42:53.330  5896  5896 I Adreno  : Local Branch                     : mybranch17112971
11-04 18:42:53.330  5896  5896 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 18:42:53.330  5896  5896 I Adreno  : Remote Branch                    : NONE
11-04 18:42:53.330  5896  5896 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 18:42:53.361   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a80ea5:true
,11-04 18:42:53.374   948   948 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[22357]" dev="sockfs" ino=22357 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:53.374   948   948 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[22357]" dev="sockfs" ino=22357 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:53.385  5896  5896 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 18:42:53.393  5896  5896 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 18:42:53.414   402   402 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[37754]" dev="sockfs" ino=37754 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:53.417  5896  5932 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-04 18:42:53.414   402   402 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[37754]" dev="sockfs" ino=37754 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:53.421  3118  3118 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[38397]" dev="sockfs" ino=38397 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:53.421  3118  3118 W Binder_3: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[38397]" dev="sockfs" ino=38397 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:53.425  5896  5919 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 18:42:53.457  5896  5932 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 18:42:53.471  3564  3564 W Binder_6: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[34891]" dev="sockfs" ino=34891 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:53.471   925  3564 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5570 uid 10077
,11-04 18:42:53.471  3564  3564 W Binder_6: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[34891]" dev="sockfs" ino=34891 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:53.474  3813  3813 W Binder_9: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[34890]" dev="sockfs" ino=34890 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:53.474  3813  3813 W Binder_9: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[34890]" dev="sockfs" ino=34890 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 18:42:53.478  3613  3613 I Keyboard.Facilitator: onFinishInput()
,11-04 18:42:53.495   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +277ms (total +309ms)
,11-04 18:42:53.496  5896  5896 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5896
,11-04 18:42:53.557  5896  5896 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 18:42:53.601  5894  5894 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-04 18:42:53.617  5894  5894 D AndroidRuntime: CheckJNI is OFF
,11-04 18:42:53.638  5894  5894 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-04 18:42:53.664  5894  5894 I Radio-JNI: register_android_hardware_Radio DONE
,11-04 18:42:53.684  5894  5894 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-04 18:42:53.689   925   938 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-04 18:42:53.689   925   938 I ActivityManager: Killing 5896:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-04 18:42:53.723   925   935 I WindowState: WIN DEATH: Window{2a8c9b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-04 18:42:53.723   925  3127 D GraphicsStats: Buffer count: 2
,11-04 18:42:53.784   925   938 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-04 18:42:53.785   925   938 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-04 18:42:53.786   925   938 E ActivityManager: Failure starting process com.test.thalitest
11-04 18:42:53.786   925   938 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-04 18:42:53.786   925   938 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 18:42:53.786   925   938 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 18:42:53.786   925   938 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 18:42:53.786   925   938 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-04 18:42:53.786   925   949 I art     : Starting a blocking GC Explicit
11-04 18:42:53.787   925   938 I ActivityManager:   Force finishing activity ActivityRecord{b88e142 u0 com.test.thalitest/.MainActivity t68}
,11-04 18:42:53.792   925  3385 W ActivityManager: Spurious death for ProcessRecord{adf82f6 0:com.test.thalitest/u0a77}, curProc for 5896: null
,11-04 18:42:53.865   925   949 I art     : Explicit concurrent mark sweep GC freed 12758(848KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.591ms total 78.332ms
,11-04 18:42:53.882   925   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-04 18:42:53.885  5894  5894 I art     : System.exit called, status: 0
,11-04 18:42:53.885  5894  5894 I AndroidRuntime: VM exiting with result code 0.
,11-04 18:42:53.889   925   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-04 18:42:53.897   925   938 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-04 18:42:53.900  5801  5801 D BluetoothMapAppObserver: onReceive
11-04 18:42:53.900  5801  5801 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-04 18:42:53.907  3613  3613 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-04 18:42:53.908  3712  4080 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-04 18:42:53.908   925  2907 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-04 18:42:53.936  3613  5947 I Keyboard.Facilitator.DecoderInitializer: run()
,11-04 18:42:53.939  3371  5948 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-04 18:42:53.950  3613  5947 I Decoder : createOrResetDecoder
,11-04 18:42:53.959  3774  3774 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-04 18:42:53.976  3550  3550 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-04 18:42:53.976  3550  3550 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-04 18:42:53.983   925   925 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-04 18:42:53.981    17    17 W kworker/2:0: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 18:42:53.987    17    17 W kworker/2:0: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 18:42:53.997  3953  5953 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-04 18:42:53.997    17    17 W kworker/2:0: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 18:42:53.998  3953  5953 D AccountUtils: Clearing selected account for com.test.thalitest
,11-04 18:42:54.017  3550  3550 I ConfigService: onCreate
,11-04 18:42:54.021  3550  5956 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-04 18:42:54.021  3550  5956 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-04 18:42:54.021  3550  5956 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-04 18:42:54.023  3550  5956 W SQLiteOpenHelper: Opened config.db in read-only mode
11-04 18:42:54.024  3371  3395 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj70491098A) - 
11-04 18:42:54.031  3613  5947 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-04 18:42:54.053  3953  5953 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-04 18:42:54.063  3953  5953 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-04 18:42:54.063  3953  5953 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-04 18:42:54.064  3953  5953 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-04 18:42:54.079  3953  5953 W SQLiteOpenHelper: Opened phenotype.db in read-only mode

```
